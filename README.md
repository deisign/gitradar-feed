# GitRadar Feed

Machine-readable mirror of Creative Radar / GitRadar.

Canonical dashboard:

https://gitradar.deisign.me/

Generated files:

- `cards.jsonl` — all curated cards
- `cards-meta.json` — card feed metadata
- `llm.txt` — current full LLM snapshot
- `today.md` — current daily shortlist
- `lancelot.jsonl` — Lancelot subset
- `lancelot-meta.json` — Lancelot feed metadata
- `meta.json` — mirror metadata

Operational runbook:

- [`brain.md`](brain.md) — canonical hosts, paths, refresh procedure, dedup invariants, verification and troubleshooting. Read this before changing or refreshing GitRadar; do not rediscover the pipeline from scratch.

Source-of-truth remains the Creative Radar card collection.
