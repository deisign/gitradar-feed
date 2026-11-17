---
product: "chat.cx"
url: "https://chat.cx/"
source_type: "browser-extension / hosted-product"
captured: "2026-11-17"
priority: "VERY HIGH"
action: "TRY"
target: "Rubka / Noosphere operator cockpit"
status: "product-signal"
---

# chat.cx

## Why it matters

Browser side-panel cockpit that can keep real ChatGPT, Claude, Gemini and other provider UIs next to the current page, while also supporting native OpenAI-compatible chats, local models, MCP, page context, context compaction and browser-agent actions.

The interesting pattern is:

```text
current browser session
  + authenticated AI provider tabs
  + local/API models
  + MCP tools
  + page context
  + human approval / takeover
  -> one operator surface
```

This is close to the desired **Rubka** interaction model: one persistent browser-side control surface over multiple models and tools without forcing all work into a new monolithic app.

## Adoption role

**Rubka browser cockpit** — persistent side-panel UI for multiple AI providers, local/API models, MCP tools, current-page context and human takeover.

## What to test

Use a separate Brave/Chrome profile first:

1. ChatGPT + Claude + Gemini side-by-side.
2. One local Ollama/LM Studio endpoint.
3. One harmless MCP server.
4. Ask-before-acting browser mode.
5. Page-context / Ask Page flow on GitHub and Reddit.
6. Context-ring / compact behavior on a long chat.
7. Inspect network activity and extension permissions before exposing work accounts.

## Security / privacy caveat

The extension requires broad browser permissions to embed authenticated provider sites and act on pages. The developer states that sessions and keys stay local, but this has not been independently verified here.

Treat privacy claims as **unverified until local inspection**. First test in an isolated browser profile.

## Follow-up

If the test is useful, promote this `product-signals` directory into the normal GitRadar build/dashboard so non-repo discoveries can be searched alongside repository cards without weakening canonical repo dedup.
