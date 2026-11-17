# GitRadar Product Signals

This directory stores **non-repository product signals**: external tools, services, browser extensions, hosted products and other useful discoveries that do not have a suitable canonical GitHub repository card.

They are intentionally separate from `cards.jsonl` and the curated `cards/*.md` source model.

## Minimal schema

Each signal should record:

- `product`
- `url`
- `source_type`
- `captured`
- `priority`
- `action`
- `target`
- why it matters
- risks / verification status
- concrete next test

## Rule

Do **not** invent a fake `owner/repo` to force a service into GitRadar cards.

If a product later gets a canonical open repository, create the normal repo card and cross-link or retire the product signal.
