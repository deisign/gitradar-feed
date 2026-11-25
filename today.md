---
title: Creative Radar Shortlist 2026-11-25
date: 2026-11-25
status: shortlist
tags:
  - radar
  - creative-radar
  - shortlist
---

# Creative Radar Shortlist — 2026-11-25

Source: [[../scored/2026-11-25|Scored 2026-11-25]]

## Навигация

- [Agent Memory / Context](#agent-memory-context) — 3
- [Agent Security / Governance](#agent-security-governance) — 1
- [Automation / Event Workflows](#automation-event-workflows) — 5
- [Design / Image Editing](#design-image-editing) — 1
- [Document Parsing / Ingestion](#document-parsing-ingestion) — 1
- [Lancelot / Agent Infrastructure](#lancelot-agent-infrastructure) — 7
- [Mixing / Mastering / Audio Engineering](#mixing-mastering-audio-engineering) — 1
- [OSINT / Investigations](#osint-investigations) — 1
- [Search / Retrieval Engineering](#search-retrieval-engineering) — 1
- [Speech / TTS & Voice](#speech-tts-&-voice) — 1
- [System Architecture / Engineering Patterns](#system-architecture-engineering-patterns) — 1
- [Video Production / Editing](#video-production-editing) — 3
- [Web Data / Crawling & Extraction](#web-data-crawling-&-extraction) — 3

## Agent Memory / Context

### scoutme/milk

- Verdict: **WATCH**
- Score: 18
- Stars: 8
- Raw: #824
- URL: https://github.com/scoutme/milk
- Description: Switch models, not context. Terminal agent host that routes each prompt between a cheap primary and a deep escalation agent (local, Bedrock, Claude Code, aider, …) with full context handoff — plus tools, MCP, multi-agent workflows, persistent memory, loop detection, and milk eval.
- Why: compound agent memory/context fit, persistent memory

### hyperb1iss/sibyl

- Verdict: **WATCH**
- Score: 18
- Stars: 70
- Raw: #810
- URL: https://github.com/hyperb1iss/sibyl
- Description: Cross-agent memory for AI coding tools: one self-hostable knowledge graph shared by Claude Code, Codex, OpenCode, Cursor, and the agents you build.
- Why: agent memory, compound agent memory/context fit, stars>=20

### substrate-systems/evermatter

- Verdict: **WATCH**
- Score: 18
- Stars: 9
- Raw: #816
- URL: https://github.com/substrate-systems/evermatter
- Description: Evermatter: governed long-term memory for AI agents. A typed knowledge graph with sources, evidence and epistemic status, served over MCP to Claude, ChatGPT, Codex and Cursor. Self-hosted or Evermatter Cloud.
- Why: compound agent memory/context fit, long-term memory


## Agent Security / Governance

### fmariv/osm-agent-guardrails

- Verdict: **WATCH**
- Score: 24
- Stars: 6
- Raw: #531
- URL: https://github.com/fmariv/osm-agent-guardrails
- Description: Agent Skills and developer tools for building responsible OpenStreetMap applications without overloading public infrastructure.
- Why: agent control-plane security fit, agent security/governance fit, strong agent-security signal


## Automation / Event Workflows

### cemora-ai/n8n-nodes-proofloop

- Verdict: **WATCH**
- Score: 27
- Stars: 0
- Raw: #731
- URL: https://github.com/cemora-ai/n8n-nodes-proofloop
- Description: Official PROOFLOOP community integration for n8n — AI agent monitoring, evidence tracking and cost control.
- Why: automation AI/MCP fit, automation ops/tooling fit, n8n, n8n identity fit, n8n node/plugin fit, workflow/event integration fit

### kaypee90/n8n-tui

- Verdict: **WATCH**
- Score: 25
- Stars: 1
- Raw: #705
- URL: https://github.com/kaypee90/n8n-tui
- Description: A Terminal User Interface (TUI) for interacting with n8n workflow automation platform instances.
- Why: automation platform, event/workflow automation identity fit, n8n, n8n identity fit, workflow automation, workflow/event integration fit

### engmohamedy100-byte/n8n-workflows

- Verdict: **WATCH**
- Score: 24
- Stars: 1
- Raw: #706
- URL: https://github.com/engmohamedy100-byte/n8n-workflows
- Description: Production n8n workflow automations with full documentation: AI customer service, sales pipeline, appointment booking and reminders, proposal generation, recruitment, job search, competitor monitoring and social publishing. Sanitized JSON plus honest READMEs.
- Why: automation AI/MCP fit, automation ops/tooling fit, n8n, n8n identity fit, workflow automation, workflow/event integration fit

### ketannsaint/apify-browserless-scrapers

- Verdict: **WATCH**
- Score: 18
- Stars: 0
- Raw: #726
- URL: https://github.com/ketannsaint/apify-browserless-scrapers
- Description: Fast browserless Apify web scrapers (Node.js, Python, n8n, MCP) ? Google Maps + free emails, Reddit, YouTube transcripts/videos/comments, ATS jobs, Google Ads & Shopify.
- Why: automation ops/tooling fit, automation reusable implementation, n8n, n8n identity fit, workflow/event integration fit

### undsky/doudou-stt-skill

- Verdict: **WATCH**
- Score: 18
- Stars: 0
- Raw: #676
- URL: https://github.com/undsky/doudou-stt-skill
- Description: 基于 WhisperX / faster-whisper 的音视频转写与字幕生成工具
- Why: automation ops/tooling fit, automation reusable implementation, n8n, n8n identity fit, workflow/event integration fit


## Design / Image Editing

### Arandreev/anthropics-smart-photo-editor

- Verdict: **WATCH**
- Score: 27
- Stars: 96
- Raw: #1411
- URL: https://github.com/Arandreev/anthropics-smart-photo-editor
- Description: Anthropics Smart Photo Editor for Windows 10/11. Edits photos with one-click style presets, brush-based local adjustments and layer masks, then exports finished images for print or web galleries.
- Why: brush, image editing fit, photo editor, photoshop, stars>=20


## Document Parsing / Ingestion

### reductoai/parsejudge

- Verdict: **WATCH**
- Score: 18
- Stars: 6
- Raw: #1135
- URL: https://github.com/reductoai/parsejudge
- Description: Open-source document parser benchmark. Compare PDF parsing and OCR APIs (Reducto, LlamaParse, Azure Document Intelligence, AWS Textract, Mistral OCR, Extend, Datalab, Pulse, Cohere) on your own documents with a blind LLM judge.
- Why: compound document parsing/ingestion fit, document parser, ocr


## Lancelot / Agent Infrastructure

### AnvitDevadiga/Ghost-Scan

- Verdict: **KEEP**
- Score: 35
- Stars: 0
- Raw: #661
- URL: https://github.com/AnvitDevadiga/Ghost-Scan
- Description: X-ray for the invisible text your AI agent obeys. Finds ASCII smuggling, hidden prompt injection, MCP tool poisoning in AGENTS.md, SKILL.md and MCP configs.
- Why: lancelot high fit

### Particle-Academy/prism-mcp-server-ts

- Verdict: **KEEP**
- Score: 35
- Stars: 0
- Raw: #612
- URL: https://github.com/Particle-Academy/prism-mcp-server-ts
- Description: Serving Prism tools to MCP clients over authenticated loopback HTTP. TypeScript.
- Why: lancelot high fit

### sakompella/cf-stumble

- Verdict: **KEEP**
- Score: 35
- Stars: 0
- Raw: #593
- URL: https://github.com/sakompella/cf-stumble
- Description: A single-owner coding agent on Cloudflare Workers, Durable Objects and Containers that can test, activate and roll back new versions of its own harness.
- Why: lancelot high fit

### subhadipjana866/cf-image-agents

- Verdict: **KEEP**
- Score: 35
- Stars: 0
- Raw: #573
- URL: https://github.com/subhadipjana866/cf-image-agents
- Description: Image creation and editing chat on Cloudflare Agents SDK: interpret → select → readiness → dispatch loop in a Durable Object, Python agents in a Cloudflare Container
- Why: lancelot high fit

### JMBargueno/skanvil

- Verdict: **WATCH**
- Score: 18
- Stars: 0
- Raw: #603
- URL: https://github.com/JMBargueno/skanvil
- Description: ⚒️ Forge, validate, and distribute shared Agent Skills (SKILL.md) across your team and AI coding agents. CLI & Node.js library.
- Why: lancelot keep fit

### WinSoftLabs30/test-fix-skill

- Verdict: **WATCH**
- Score: 18
- Stars: 0
- Raw: #604
- URL: https://github.com/WinSoftLabs30/test-fix-skill
- Description: Agent skill: fix failing tests without weakening them. Workflow and hard rules for Claude Code, OpenCode, Cursor and any agent that reads SKILL.md.
- Why: lancelot keep fit

### Ziqing7226/BossLoop

- Verdict: **WATCH**
- Score: 18
- Stars: 0
- Raw: #635
- URL: https://github.com/Ziqing7226/BossLoop
- Description: Open-source AI agent workflows for long-horizon tasks: bounded rounds, an independent check on every round, and a ledger to resume from after any interrupt. One loop develops software autonomously; one iterates research ideas through blind review. You set the requirement and decide what continues.
- Why: lancelot keep fit


## Mixing / Mastering / Audio Engineering

### kimberlymedina66/softube-weiss-mm-1

- Verdict: **WATCH**
- Score: 25
- Stars: 96
- Raw: #200
- URL: https://github.com/kimberlymedina66/softube-weiss-mm-1
- Description: Softube Weiss Mm 1 for Windows 10/11. Mixes and masters tracks with the Weiss MM-1 mastering compressor, shaping dynamics and loudness on individual stems or full mixes for release-ready audio.
- Why: compressor, loudness, mastering, mixing/mastering/audio engineering fit, stars>=20


## OSINT / Investigations

### ArgeliusLabs/chinese_osint_search_dorks

- Verdict: **WATCH**
- Score: 23
- Stars: 123
- Raw: #1687
- URL: https://github.com/ArgeliusLabs/chinese_osint_search_dorks
- Description: A Bilingual Field Guide to Baidu, Chinese-Language Query Pivots, Public Records, and Verification
- Why: osint/investigations fit, public records, stars>=100, verification


## Search / Retrieval Engineering

### louvain-ai/louvain-engine

- Verdict: **WATCH**
- Score: 18
- Stars: 14
- Raw: #901
- URL: https://github.com/louvain-ai/louvain-engine
- Description: Permission-aware hybrid retrieval for AI agents and RAG: keyword and vector search over your documents with a permission fence inside every query. Self-hosted, MCP, Postgres + pgvector.
- Why: bm25, compound search/retrieval fit, vector search


## Speech / TTS & Voice

### Lyrcaxis/KokoroSharp

- Verdict: **WATCH**
- Score: 18
- Stars: 253
- Raw: #1021
- URL: https://github.com/Lyrcaxis/KokoroSharp
- Description: Fast local TTS inference engine in C# with ONNX runtime. Multi-speaker, multi-platform and multilingual.  Integrate on your .NET projects using a plug-and-play NuGet package, complete with all voices.
- Why: compound deployable speech/TTS fit, stars>=100, text-to-speech, tts


## System Architecture / Engineering Patterns

### orcher-io/orcher

- Verdict: **WATCH**
- Score: 18
- Stars: 6
- Raw: #1518
- URL: https://github.com/orcher-io/orcher
- Description: Durable workflow engine, built in Rust
- Why: durable workflow, high-value architecture pattern, system architecture / engineering patterns fit


## Video Production / Editing

### ValejuJa62/ai-shorts-factory

- Verdict: **WATCH**
- Score: 25
- Stars: 66
- Raw: #1370
- URL: https://github.com/ValejuJa62/ai-shorts-factory
- Description: Vertical video generator: text in, finished Shorts with voice and subtitles out. | ai shorts reels tiktok video-factory tts | Portable x64 prebuilt for Windows
- Why: stars>=20, subtitle, subtitles, video, video production fit

### QuforiXa48/shorts-generator-ai

- Verdict: **WATCH**
- Score: 25
- Stars: 61
- Raw: #1369
- URL: https://github.com/QuforiXa48/shorts-generator-ai
- Description: Vertical video generator: text in, finished Shorts with voice and subtitles out. | ai shorts reels tiktok video-factory tts | Portable x64 prebuilt for Windows
- Why: stars>=20, subtitle, subtitles, video, video production fit

### mergelooplab03/kdenlive

- Verdict: **WATCH**
- Score: 20
- Stars: 103
- Raw: #1353
- URL: https://github.com/mergelooplab03/kdenlive
- Description: Kdenlive for Windows 10/11. Edits multi-track video projects with timeline trimming, transitions, effects and audio mixing, then exports finished clips for YouTube, presentations or social media in common formats.
- Why: kdenlive, stars>=100, timeline, video


## Web Data / Crawling & Extraction

### geonodecom/sdk-typescript

- Verdict: **WATCH**
- Score: 18
- Stars: 26
- Raw: #1077
- URL: https://github.com/geonodecom/sdk-typescript
- Description: Geonode TypeScript SDK: Web Scraping & Data Extraction. Extract Markdown or HTML, crawl websites and search the web from server-side JavaScript or TypeScript using the Geonode Scraper API.
- Why: compound web crawling/extraction fit, stars>=20, web scraping

### geonodecom/sdk-python

- Verdict: **WATCH**
- Score: 18
- Stars: 26
- Raw: #1078
- URL: https://github.com/geonodecom/sdk-python
- Description: Geonode Python SDK: Web Scraping & Data Extraction. Extract Markdown or HTML, crawl websites, discover URLs and search the web using typed Python clients for the Geonode Scraper API.
- Why: compound web crawling/extraction fit, stars>=20, web scraping

### geonodecom/integration-make

- Verdict: **WATCH**
- Score: 18
- Stars: 27
- Raw: #1080
- URL: https://github.com/geonodecom/integration-make
- Description: Geonode for Make.com: Web Scraping & Data Extraction. Turn website URLs into Markdown or HTML in Make.com, then send the content to your next scenario module with the private Geonode connector.
- Why: compound web crawling/extraction fit, stars>=20, web scraping
