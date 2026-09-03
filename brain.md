# GitRadar / Creative Radar — operational brain

Last verified: 2026-09-03 21:39 Europe/Kyiv

This file is the operational memory for GitRadar. **Do not rediscover the update procedure from scratch.**

## 0. Golden rule

There are TWO different operations. Do not confuse them.

1. **FULL DAILY RADAR RUN** — collect GitHub data, validate raw input, score, update seen ledger, build today's shortlist, rebuild site/feeds, publish mirror.
2. **MANUAL CARD PUBLISH** — after curated `cards/*.md` were added/edited, rebuild derived artifacts and publish them. **Do not rerun raw collection/scoring/shortlist for this.**

If the user says "делаем карточки", "добавь карточки", "опубликуй карточки", "обнови радар после карточек" → use **MANUAL CARD PUBLISH**.

If the user explicitly wants a fresh daily crawl / today's new GitHub catch → use **FULL DAILY RADAR RUN**.

Never invent command names. All commands below are verified real files on Circus.

---

## 1. Canonical host and paths

Canonical runtime host: **Circus**.

From Camelot:

```bash
ssh deisign@100.82.248.7
```

Creative Radar root:

```text
/home/deisign/Exchange/notes/90-radars/creative-radar
```

Scripts:

```text
/home/deisign/Exchange/notes/90-radars/scripts
```

Canonical curated cards (SOURCE OF TRUTH):

```text
/home/deisign/Exchange/notes/90-radars/creative-radar/cards/
```

Generated artifacts:

```text
/home/deisign/Exchange/notes/90-radars/creative-radar/site/cards.jsonl
/home/deisign/Exchange/notes/90-radars/creative-radar/site/cards-meta.json
/home/deisign/Exchange/notes/90-radars/creative-radar/site/lancelot.jsonl
/home/deisign/Exchange/notes/90-radars/creative-radar/site/llm.txt
/home/deisign/Exchange/notes/90-radars/creative-radar/site/llm-YYYY-MM-DD.txt
```

Public machine mirror:

```text
deisign/gitradar-feed
```

Dashboard:

```text
https://gitradar.deisign.me/
```

---

## 2. VERIFIED MANUAL CARD PUBLISH

### When to use

Use this after manually creating or editing curated card files under `cards/`.

**DO NOT start `creative-radar-daily.service` for this job.** The daily service starts raw collection + scoring + shortlist work first and can take time/block. It is the wrong operation for publishing already-curated cards.

### Verified pipeline

The actual dependency chain is:

```text
cards/*.md
  ↓
build-creative-radar-site
  ↓
  site/index.html
  cards.jsonl + cards-meta.json
  lancelot.jsonl + lancelot-meta.json
  ↓
build-creative-radar-llm
  ↓
  cards/index.md
  site/llm.md
  site/llm.txt
  ↓
copy dated llm snapshot
  ↓
publish-creative-radar-github RUN_DATE
  ↓
deisign/gitradar-feed
```

Important: `build-creative-radar-site` is a SAFE BUILD wrapper and **already calls `build-creative-radar-lancelot-feed` internally**. Do not separately rebuild Lancelot unless diagnosing that specific stage.

### Exact verified commands on Circus

```bash
set -euo pipefail

RUN_DATE="$(date +%F)"
ROOT="$HOME/Exchange/notes/90-radars"
RADAR="$ROOT/creative-radar"
SCRIPTS="$ROOT/scripts"

cd "$RADAR"

"$SCRIPTS/build-creative-radar-site"
"$SCRIPTS/build-creative-radar-llm"
cp -f "$RADAR/site/llm.txt" "$RADAR/site/llm-$RUN_DATE.txt"
"$SCRIPTS/publish-creative-radar-github" "$RUN_DATE"
```

### Same operation from Camelot in one SSH block

```bash
ssh deisign@100.82.248.7 'bash -s' <<'REMOTE'
set -euo pipefail

RUN_DATE="$(date +%F)"
ROOT="$HOME/Exchange/notes/90-radars"
RADAR="$ROOT/creative-radar"
SCRIPTS="$ROOT/scripts"

cd "$RADAR"

"$SCRIPTS/build-creative-radar-site"
"$SCRIPTS/build-creative-radar-llm"
cp -f "$RADAR/site/llm.txt" "$RADAR/site/llm-$RUN_DATE.txt"
"$SCRIPTS/publish-creative-radar-github" "$RUN_DATE"

ls -lh \
  site/cards.jsonl \
  site/cards-meta.json \
  site/lancelot.jsonl \
  site/llm.txt \
  "site/llm-$RUN_DATE.txt"

printf '\nCARD-ONLY GITRADAR PUBLISH: OK\n'
REMOTE
```

### Verification after card changes

Before publish or immediately after site build, verify expected repos exist in the generated feed:

```bash
for repo in \
  'OWNER/REPO1' \
  'OWNER/REPO2'
do
  printf '%-50s ' "$repo"
  grep -Fq "\"repo\":\"$repo\"" site/cards.jsonl \
    && echo OK \
    || { echo MISSING; exit 1; }
done
```

Success indicators from the publisher:

```text
[main <sha>] Radar snapshot YYYY-MM-DD
To https://github.com/deisign/gitradar-feed.git
<old>..<new>  main -> main
published: deisign/gitradar-feed
```

### Proven successful run — 2026-09-03

This exact card-only procedure was executed successfully at 21:39 Europe/Kyiv after adding six cards.

Observed result:

```text
SAFE BUILD: accepted
cards: 182
cards sha256: 24ac3b387a35d9ef1866cc00884220d145af48652400d04d60bca7d33808fad4
records: 26
cards=182 buckets=20
published: deisign/gitradar-feed
CARD-ONLY GITRADAR PUBLISH: OK
```

Published mirror commit:

```text
4f73afc47d69e3bb186c5badbef62dcedde6ca0d
```

Public `cards-meta.json` changed from 176 to 182 cards and carried the same cards SHA256 above. This verifies not just local generation but successful mirror publication.

The six verified cards were:

```text
Duragraph/duragraph
kyungseo/skillstead
skydashnet/material-design-3-ui-skill
Convertiv/handoff-app
filliptm/ComfyUI_FL-HeartMuLa
monnky/ComfyUI-RT-HeartMuLa
```

---

## 3. VERIFIED FULL DAILY RADAR RUN

### When to use

Use only when a new daily GitHub crawl / scoring / shortlist is wanted.

Systemd service:

```text
creative-radar-daily.service
```

ExecStart:

```text
/home/deisign/bin/creative-radar-daily
```

Timer:

```text
creative-radar-daily.timer
```

Schedule:

```text
08:10 daily
```

Full daily pipeline implemented in `/home/deisign/bin/creative-radar-daily`:

```text
creative-radar-raw
→ creative-radar-validate-raw RUN_DATE
→ creative-radar-score RUN_DATE
→ creative-radar-seen-ledger
→ creative-radar-shortlist RUN_DATE
→ build-creative-radar-site
→ build-creative-radar-llm
→ copy llm-RUN_DATE.txt
→ publish-creative-radar-github RUN_DATE
```

Manual start when a fresh full run is explicitly wanted:

```bash
systemctl --user start creative-radar-daily.service
```

Inspect status/logs:

```bash
systemctl --user status creative-radar-daily.service --no-pager
journalctl --user -u creative-radar-daily.service -n 200 --no-pager
```

Again: **do not use this just to publish manual cards.**

---

## 4. Verified real scripts

These files exist and are executable on Circus:

```text
/home/deisign/Exchange/notes/90-radars/scripts/build-creative-radar-site
/home/deisign/Exchange/notes/90-radars/scripts/build-creative-radar-site.impl
/home/deisign/Exchange/notes/90-radars/scripts/build-creative-radar-site.core
/home/deisign/Exchange/notes/90-radars/scripts/build-creative-radar-lancelot-feed
/home/deisign/Exchange/notes/90-radars/scripts/build-creative-radar-llm
/home/deisign/Exchange/notes/90-radars/scripts/publish-creative-radar-github
/home/deisign/Exchange/notes/90-radars/scripts/creative-radar-validate-raw
/home/deisign/Exchange/notes/90-radars/scripts/creative-radar-score
/home/deisign/Exchange/notes/90-radars/scripts/creative-radar-seen-ledger
/home/deisign/Exchange/notes/90-radars/scripts/creative-radar-shortlist
```

Previous documentation incorrectly called some of these names invented. That was false; the 2026-09-03 inspection proved they exist. Do not repeat that mistake.

---

## 5. Manual card rules

- One Markdown file per GitHub repository.
- `repo:` is canonical `owner/name` identity.
- Do not combine two repositories into one card; repo-level dedup depends on one repo identity per card.
- Before creating a card, check the canonical cards collection to ensure it is not already present.
- Card files are source-of-truth; `cards.jsonl` is generated output.
- After cards are added, use the **VERIFIED MANUAL CARD PUBLISH** above.

---

## 6. Dedup invariant for today's catch

Bug discovered 2026-09-03: `today.md` can contain repositories that already exist in curated cards.

Required conceptual invariant:

```text
today_new = scored_today(KEEP/WATCH) - canonical_card_repositories
```

Normalize repo identity case-insensitively as `owner/repo` (or stable GitHub repo id where available).

Required behavior:

- already-carded repo must not be presented as new;
- yesterday-carded repo must remain excluded even if stars/score changed;
- reference/seed repos may be scored but should not become new discoveries;
- category counts must be computed after final dedup/filter.

Regression tests to add:

1. carded repo cannot appear in today shortlist;
2. yesterday-carded repo remains excluded today;
3. URL/case/trailing `.git` normalization works;
4. rendered category count equals actual rendered entries;
5. reference seeds can score without becoming new discoveries.

---

## 7. Failure handling

Do not guess replacements when a documented command fails.

For card-only failures, diagnose the exact stage:

```text
build-creative-radar-site
build-creative-radar-llm
publish-creative-radar-github
```

Useful inspection commands:

```bash
sed -n '1,260p' /home/deisign/Exchange/notes/90-radars/scripts/build-creative-radar-site
sed -n '1,260p' /home/deisign/Exchange/notes/90-radars/scripts/publish-creative-radar-github
```

For full daily failures:

```bash
sed -n '1,320p' /home/deisign/bin/creative-radar-daily
journalctl --user -u creative-radar-daily.service -n 200 --no-pager
```

Target the failing established stage. Do not restart pipeline archaeology.

---

## 8. Interaction contract for future ChatGPT sessions

When asked to work with GitRadar:

1. Read `brain.md` first.
2. Treat Circus and paths here as established facts.
3. Treat `cards/` as canonical dedup state.
4. Distinguish manual-card publish from full daily crawl.
5. Never invent commands or PATH aliases; use full verified paths.
6. Do not run the full daily service merely to publish curated cards.
7. When discussing "today's catch", dedup against cards first.
8. If a procedure changes, first prove the new procedure with an actual successful run, then update this file.
9. **Never write an unverified operational procedure into this file.**

---

## 9. Important mirror behavior

`brain.md` is operational documentation and must persist in `deisign/gitradar-feed` across publisher runs.

The publisher regenerates the feed snapshot and may rewrite generated/support files such as README content. Do not rely on README as the only pointer to this runbook. The runbook itself must remain preserved in the repository.
