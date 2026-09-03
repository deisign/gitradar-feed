# GitRadar / Creative Radar — operational brain

Last verified: 2026-09-03

This file exists so the radar update procedure is **not rediscovered from scratch every day**.

## Golden rule

When asked to **update the radar**, **add cards**, **publish cards**, or **refresh GitRadar**:

1. Read this file first.
2. Do not invent command names.
3. Do not begin with exploratory `rg`/`find` archaeology unless a documented command actually fails.
4. Prefer the known systemd entrypoint or the known real scripts below.
5. Never treat `today.md` as “new discoveries” until it has been deduplicated against the canonical card collection.

---

## Hosts and paths

### Canonical host

`Circus` is the always-on machine and canonical runtime for Creative Radar / GitRadar.

Tailscale SSH from Camelot:

```bash
ssh deisign@100.82.248.7
```

### Canonical Creative Radar working directory

```text
/home/deisign/Exchange/notes/90-radars/creative-radar
```

Short form after logging into Circus:

```bash
cd ~/Exchange/notes/90-radars/creative-radar
```

### Canonical cards

```text
/home/deisign/Exchange/notes/90-radars/creative-radar/cards/
```

The **Creative Radar card collection is the source of truth**.

### Generated site/feed directory

```text
/home/deisign/Exchange/notes/90-radars/creative-radar/site/
```

Known generated artifacts include:

```text
site/cards.jsonl
site/cards-meta.json
site/llm.txt
site/lancelot.jsonl
```

The public GitHub mirror is:

```text
deisign/gitradar-feed
```

Canonical dashboard:

```text
https://gitradar.deisign.me/
```

---

## Real daily entrypoint

The actual systemd service is:

```text
creative-radar-daily.service
```

Its real `ExecStart` is:

```text
/home/deisign/bin/creative-radar-daily
```

The timer is:

```text
creative-radar-daily.timer
```

and runs at:

```text
08:10 daily
```

### Canonical full refresh

When a **full daily radar refresh** is wanted, use the real service instead of reconstructing the pipeline by hand:

```bash
systemctl --user start creative-radar-daily.service
```

Check result:

```bash
systemctl --user status creative-radar-daily.service --no-pager
journalctl --user -u creative-radar-daily.service -n 120 --no-pager
```

The historical logs confirm that the daily pipeline generates the card/Lancelot feeds and publishes `deisign/gitradar-feed`.

Do **not** make up substitute names for this entrypoint.

---

## Known real site builder

The real site builder exists at:

```text
/home/deisign/Exchange/notes/90-radars/scripts/build-creative-radar-site
```

This path is documented by the local `SWISS_VIEW_HANDOFF.md` and must be preferred over guessed commands.

### Explicitly forbidden invented commands

These names were previously guessed and are **not established entrypoints**:

```text
build-creative-radar-llm
build-creative-radar-lancelot-feed
publish-creative-radar-github
```

Do not use them unless they are later actually created and this file is updated.

---

## Manual card workflow

When new curated cards are approved:

1. Work on Circus.
2. Create one Markdown file per GitHub repository under `cards/`.
3. Keep a single canonical `repo: owner/name` identity per card.
4. Do not create one card that represents two different repositories; this breaks repo-level dedup.
5. Before adding a card, confirm that the repo is not already in the canonical card collection.
6. After the card files are written, perform a radar refresh using a documented real entrypoint.

### Safest known refresh after manual card changes

Until a separately verified card-only publish entrypoint is documented here, use the canonical daily service:

```bash
systemctl --user start creative-radar-daily.service
```

This may rerun collection/scoring as well, but it is the known real end-to-end pipeline and is preferable to invented partial commands.

### Verify cards reached generated feed

Example:

```bash
cd ~/Exchange/notes/90-radars/creative-radar

grep -F '"repo":"OWNER/REPO"' site/cards.jsonl
```

For several repos:

```bash
for repo in \
  'OWNER/REPO1' \
  'OWNER/REPO2'
do
  printf '%-50s ' "$repo"
  if grep -Fq "\"repo\":\"$repo\"" site/cards.jsonl; then
    echo OK
  else
    echo MISSING
  fi
done
```

### Verify public mirror updated

The feed repository should receive a new push. Historical daily logs contain lines equivalent to:

```text
To https://github.com/deisign/gitradar-feed.git
published: deisign/gitradar-feed
```

Also check timestamps in generated files:

```bash
ls -lh \
  site/cards.jsonl \
  site/cards-meta.json \
  site/llm.txt \
  site/lancelot.jsonl
```

---

## Dedup invariant

A major bug discovered on 2026-09-03: `today.md` can resurface repositories that already have curated cards.

Therefore the conceptual invariant must be:

```text
today_new = scored_today(KEEP/WATCH) - canonical_card_repositories
```

Normalize repository identity as `owner/repo` case-insensitively (or by stable GitHub repository id when available).

### Required behavior

- A repo already present in cards must not be presented as a new discovery.
- A repo carded yesterday must not become “new” today because its stars or score changed.
- Reference/seed repos may remain in scoring inputs, but should not appear in the public “new catch” unless explicitly requested.
- Category counts must be computed **after** the final dedup/filter, not before it.

### Regression tests that should exist

1. carded repo cannot appear in today shortlist;
2. yesterday-carded repo remains excluded today;
3. repo URL/casing/trailing `.git` normalization works;
4. displayed bucket count equals number of rendered entries;
5. reference seeds can be scored without becoming new discoveries.

---

## What to do when a command fails

Do not start guessing command names.

Use this order:

1. Inspect the exact failing command.
2. If the daily pipeline is involved, read the real script:

```bash
sed -n '1,320p' /home/deisign/bin/creative-radar-daily
```

3. If site generation is involved, inspect the real builder:

```bash
sed -n '1,320p' /home/deisign/Exchange/notes/90-radars/scripts/build-creative-radar-site
```

4. Check the service log:

```bash
journalctl --user -u creative-radar-daily.service -n 200 --no-pager
```

5. Only then diagnose the specific failing stage.

The goal is **targeted diagnosis of an established pipeline**, not rediscovery of the pipeline.

---

## Interaction contract for future ChatGPT sessions

If the user says something equivalent to:

- “обнови радар”;
- “делаем карточки”;
- “закинь карточки в радар”;
- “опубликуй сегодняшний улов”;
- “шо там сегодня в GitRadar”;

then:

1. Treat Circus and the paths above as established facts.
2. Treat the cards collection as canonical dedup state.
3. Do not ask where GitRadar lives.
4. Do not invent builders or publishers.
5. For a full refresh, use `creative-radar-daily.service`.
6. For a partial/manual refresh, use only partial commands explicitly documented in this file; otherwise use the known full service rather than guessing.
7. When discussing “today”, first subtract existing cards.
8. If a new reliable maintenance command is discovered, update **this file in the same session**.

---

## 2026-09-03 incident note

Six manual cards were created successfully under `cards/`:

```text
duragraph-duragraph.md
kyungseo-skillstead.md
skydashnet-material-design-3-ui-skill.md
convertiv-handoff-app.md
filliptm-comfyui-fl-heartmula.md
monnky-comfyui-rt-heartmula.md
```

The card creation succeeded.

A later refresh failed because nonexistent commands were guessed (`build-creative-radar-site` without its real path, followed by other invented `build-*`/publish names) under `set -euo pipefail`, which terminated the SSH shell at the first `command not found`.

Correct lesson: **never reconstruct GitRadar operations from memory when the canonical service/script paths are already known and documented here.**

---

## Keep this file alive

`brain.md` is operational documentation, **not a generated feed artifact**.

The publisher must preserve it across daily mirror updates. If a future publish deletes it, fix the publisher so non-generated repository files are retained.
