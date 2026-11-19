---
title: Creative Radar Shortlist 2026-11-19
date: 2026-11-19
status: shortlist
tags:
  - radar
  - creative-radar
  - shortlist
---

# Creative Radar Shortlist — 2026-11-19

Source: [[../scored/2026-11-19|Scored 2026-11-19]]

## Навигация

- [Agent Memory / Context](#agent-memory-context) — 4
- [Agent Security / Governance](#agent-security-governance) — 1
- [Automation / Event Workflows](#automation-event-workflows) — 8
- [Design / Image Editing](#design-image-editing) — 1
- [Design Systems / Visual QA](#design-systems-visual-qa) — 1
- [Document Parsing / Ingestion](#document-parsing-ingestion) — 1
- [Font Creation / Typography Tools](#font-creation-typography-tools) — 1
- [Full-Song AI / Suno Alternatives](#full-song-ai-suno-alternatives) — 2
- [Lancelot / Agent Infrastructure](#lancelot-agent-infrastructure) — 5
- [Newsroom / Data Journalism](#newsroom-data-journalism) — 1
- [Reverse Engineering / Binary Analysis](#reverse-engineering-binary-analysis) — 2
- [Search / Retrieval Engineering](#search-retrieval-engineering) — 3
- [System Architecture / Engineering Patterns](#system-architecture-engineering-patterns) — 2

## Agent Memory / Context

### ipiton/agent-memory-mcp

- Verdict: **WATCH**
- Score: 18
- Stars: 46
- Raw: #795
- URL: https://github.com/ipiton/agent-memory-mcp
- Description: MCP server that gives AI agents persistent memory with semantic search
- Why: compound agent memory/context fit, persistent memory, stars>=20

### ontogr/ontogr-agent-memory

- Verdict: **WATCH**
- Score: 18
- Stars: 9
- Raw: #794
- URL: https://github.com/ontogr/ontogr-agent-memory
- Description: OntoGr Agent Memory is an open source Python library that stores what an agent learned, where it learned it, and when it was true. It ingests source material as episodes, extracts entities and facts, resolves duplicate entities, reconciles facts on two time axes, and returns a budgeted context block that is ready for an answering model.
- Why: agent memory, compound agent memory/context fit

### Bo1202/Aivy-OS

- Verdict: **WATCH**
- Score: 18
- Stars: 111
- Raw: #812
- URL: https://github.com/Bo1202/Aivy-OS
- Description: Your own digital life form — local AI companion with persistent memory, IDE workspace, MCP support, and 30+ tools. Companion-first alternative to Hermes Agent / OpenClaw / Claude Code.
- Why: compound agent memory/context fit, persistent memory, stars>=100

### caseclose/cma-harness

- Verdict: **WATCH**
- Score: 18
- Stars: 16
- Raw: #824
- URL: https://github.com/caseclose/cma-harness
- Description: Cognitive-structured Multimodal Agent (CMA-Harness): a memory-centric agent for long-horizon multimodal understanding, generation, and editing — externalizing visual history into episodic memory with selective retrieval. Includes the M2CA-Bench benchmark.
- Why: compound agent memory/context fit, episodic memory


## Agent Security / Governance

### Agentboxx-dev/Agentboxx

- Verdict: **WATCH**
- Score: 24
- Stars: 6
- Raw: #528
- URL: https://github.com/Agentboxx-dev/Agentboxx
- Description: A tamper-evident flight recorder for AI agents. Sandboxed execution, cryptographic signing (HMAC & Ed25519), loop detection, and audit reports. pip install agentboxx
- Why: agent control-plane security fit, agent security/governance fit, strong agent-security signal


## Automation / Event Workflows

### taskade/integrations

- Verdict: **WATCH**
- Score: 28
- Stars: 9
- Raw: #667
- URL: https://github.com/taskade/integrations
- Description: Taskade Integration Kit: the public source for the Taskade apps on Zapier, n8n and Make, built on the Taskade Public API.
- Why: automation ops/tooling fit, automation reusable implementation, n8n, n8n identity fit, trigger, webhook, workflow/event integration fit

### shoaibmahmud244-lang/n8n-workflow-pack

- Verdict: **WATCH**
- Score: 23
- Stars: 0
- Raw: #700
- URL: https://github.com/shoaibmahmud244-lang/n8n-workflow-pack
- Description: Production-shaped n8n workflows (lead intake & scheduled diff scraping) with an offline graph validator and pytest suite.
- Why: automation ops/tooling fit, automation reusable implementation, n8n, n8n identity fit, webhook, workflow/event integration fit

### Zrk1212/n8n-nodes-zrk-scrapers

- Verdict: **WATCH**
- Score: 20
- Stars: 0
- Raw: #664
- URL: https://github.com/Zrk1212/n8n-nodes-zrk-scrapers
- Description: n8n community node: 9 web scrapers (jobs, PageSpeed, UK companies, TikTok transcripts, Luma, Google Hotels, Google Ads, Telegram) via Apify
- Why: automation ops/tooling fit, automation reusable implementation, n8n, n8n identity fit, n8n node/plugin fit

### felixw-ctrl/n8n-ai-lead-triage

- Verdict: **WATCH**
- Score: 19
- Stars: 2
- Raw: #720
- URL: https://github.com/felixw-ctrl/n8n-ai-lead-triage
- Description: n8n AI agent that triages inbound requests with Claude: CRM updates, Slack alerts with suggested replies, and human review for unclear cases.
- Why: automation AI/MCP fit, automation ops/tooling fit, n8n, n8n identity fit, workflow/event integration fit

### lunox-work/n8n-to-claude

- Verdict: **WATCH**
- Score: 18
- Stars: 0
- Raw: #665
- URL: https://github.com/lunox-work/n8n-to-claude
- Description: Run your n8n workflows in Claude. One command shows which of your n8n workflows run on the Claude plan you already pay for; the ones that do move, and n8n switches off without sending anything twice.
- Why: automation ops/tooling fit, automation reusable implementation, n8n, n8n identity fit, workflow/event integration fit

### BigDevEdu/punk-records-oss

- Verdict: **WATCH**
- Score: 18
- Stars: 0
- Raw: #728
- URL: https://github.com/BigDevEdu/punk-records-oss
- Description: Memória de longo prazo compartilhada entre agentes de IA via MCP (Claude Code, n8n). Self-hosted sobre o EpochDB, com token por agente, isolamento por projeto e painel de administração.
- Why: automation ops/tooling fit, automation reusable implementation, n8n, n8n identity fit, workflow/event integration fit

### shreephansalkar1234/atylx-b2b-mx-lead-verifier

- Verdict: **WATCH**
- Score: 18
- Stars: 0
- Raw: #699
- URL: https://github.com/shreephansalkar1234/atylx-b2b-mx-lead-verifier
- Description: Zero-API-key B2B MX, Null-MX, SPF & DMARC lead verifier CLI + n8n workflow template by Atylx AI
- Why: automation ops/tooling fit, automation reusable implementation, n8n, n8n identity fit, workflow/event integration fit

### Onto-IQ/n8n-workflow-automation

- Verdict: **WATCH**
- Score: 18
- Stars: 12
- Raw: #666
- URL: https://github.com/Onto-IQ/n8n-workflow-automation
- Description: Production-ready n8n self-hosting template via Docker Compose, optimized for students and lightweight environments. Includes PostgreSQL, Redis, and Traefik integration.
- Why: automation ops/tooling fit, automation reusable implementation, n8n, n8n identity fit, workflow/event integration fit


## Design / Image Editing

### metalrahul/photocraft-vfx

- Verdict: **WATCH**
- Score: 20
- Stars: 6
- Raw: #1393
- URL: https://github.com/metalrahul/photocraft-vfx
- Description: Photocraft VFX: a layer-based image editor that works like Nuke. 32-bit scene-linear ACEScg, OpenColorIO 2.4 colorspaces (ARRI, RED, Sony log), Nuke Merge blend modes, Grade and ColorLookup-style Curves, multi-channel EXR export and one-click Nuke script generation.
- Why: image editing fit, image editor, layer-based


## Design Systems / Visual QA

### Sepantapouya/Kashi

- Verdict: **WATCH**
- Score: 30
- Stars: 42
- Raw: #1442
- URL: https://github.com/Sepantapouya/Kashi
- Description: Open-source Persian design system — RTL-first, dark-first, accessible. React, Web Components, CSS, Tailwind, 13,000 icons, Figma kit and an MCP server. دیزاین‌سیستم فارسی و متن‌باز
- Why: design QA fit, design system, design-system, figma, stars>=20, tokens


## Document Parsing / Ingestion

### NoteNerdOfficial/convert-to-markdown

- Verdict: **WATCH**
- Score: 18
- Stars: 8
- Raw: #1117
- URL: https://github.com/NoteNerdOfficial/convert-to-markdown
- Description: Convert PDF, Word, PowerPoint, Excel, and image files in your vault into Markdown notes with images and dropped assets listed alongside the output. Process everything fully offline on your machine — no cloud, service, external binary, or API key required; documents parse deterministically while images use local OCR with confidence reporting.
- Why: compound document parsing/ingestion fit, ocr


## Font Creation / Typography Tools

### googlefonts/compreffor

- Verdict: **WATCH**
- Score: 25
- Stars: 24
- Raw: #33
- URL: https://github.com/googlefonts/compreffor
- Description: A CFF table subroutinizer for FontTools
- Why: font, font/typography tooling fit, fonts, fonttools, stars>=20


## Full-Song AI / Suno Alternatives

### techfreakworm/ace-music-studio

- Verdict: **WATCH**
- Score: 33
- Stars: 2
- Raw: #458
- URL: https://github.com/techfreakworm/ace-music-studio
- Description: Open-source song generation studio on ACE-Step 1.5 XL SFT — Generate, Cover, Extend, Edit, draft Lyrics. Runs on MPS, CUDA, and HF Spaces ZeroGPU.
- Why: full-song ecosystem fit, full-song identity fit, lyrics/vocals full-song fit

### michael-borck/canturia

- Verdict: **WATCH**
- Score: 33
- Stars: 0
- Raw: #431
- URL: https://github.com/michael-borck/canturia
- Description: Privacy-first text-to-song: lyrics or a topic plus a genre, rendered by your own ACE-Step server.
- Why: full-song ecosystem fit, full-song identity fit, lyrics/vocals full-song fit


## Lancelot / Agent Infrastructure

### pranavsaji/exorcist-98

- Verdict: **KEEP**
- Score: 35
- Stars: 0
- Raw: #652
- URL: https://github.com/pranavsaji/exorcist-98
- Description: The 90s antivirus, resurrected for AI coding agents: scans repos, MCP servers, hooks and steering files for prompt injection and tool poisoning. Built with Kiro for Kiroween 2026.
- Why: lancelot high fit

### bartrumb/cf_ai_ask_brett

- Verdict: **KEEP**
- Score: 35
- Stars: 1
- Raw: #571
- URL: https://github.com/bartrumb/cf_ai_ask_brett
- Description: AI advocate that answers interviewers' questions about Brett by text or voice. Workers AI, AI Gateway, Durable Objects, Agents SDK + Think.
- Why: lancelot high fit

### mattjcarpenter/cloudflare-logistics-agent

- Verdict: **KEEP**
- Score: 35
- Stars: 0
- Raw: #573
- URL: https://github.com/mattjcarpenter/cloudflare-logistics-agent
- Description: AI logistics assistant on Cloudflare Workers: a multi-step tool-calling agent (Workers AI, Agents SDK, Durable Objects, AI Search) for order tracking, rate quotes, address validation and policy Q&A.
- Why: lancelot high fit

### Akshat-Gurnani/local-orbit

- Verdict: **WATCH**
- Score: 18
- Stars: 0
- Raw: #601
- URL: https://github.com/Akshat-Gurnani/local-orbit
- Description: One shared memory for all your AI tools, stored on your own machine. MCP server, CLI installer, and dashboard.
- Why: lancelot keep fit

### AdJIa/opencode-plugin-skill-evo

- Verdict: **WATCH**
- Score: 18
- Stars: 0
- Raw: #592
- URL: https://github.com/AdJIa/opencode-plugin-skill-evo
- Description: Self-evolving Agent Skills for OpenCode v2 — a dedicated judge model mines finished sessions and auto-writes/patches SKILL.md (project or global scope)
- Why: lancelot keep fit


## Newsroom / Data Journalism

### datadesk/air-quality-index

- Verdict: **WATCH**
- Score: 20
- Stars: 8
- Raw: #1683
- URL: https://github.com/datadesk/air-quality-index
- Description: Download air quality index data from AirNow
- Why: datadesk, journalism, newsroom fit


## Reverse Engineering / Binary Analysis

### imjustprism/borer

- Verdict: **WATCH**
- Score: 22
- Stars: 23
- Raw: #1163
- URL: https://github.com/imjustprism/borer
- Description: Blazing fast, Rust-based reverse engineering tool built for humans and AI. Next-generation binary analysis in pure Rust: desktop app, CLI and MCP server.
- Why: binary analysis, compound reverse engineering fit, decompiler, disassembler, reverse engineering, stars>=20

### GrammaTech/gtirb

- Verdict: **WATCH**
- Score: 18
- Stars: 381
- Raw: #1170
- URL: https://github.com/GrammaTech/gtirb
- Description: Intermediate Representation for Binary analysis and transformation
- Why: binary analysis, compound reverse engineering fit, disassembler, stars>=100


## Search / Retrieval Engineering

### kochetkov-ma/claude-brewcode

- Verdict: **WATCH**
- Score: 18
- Stars: 39
- Raw: #868
- URL: https://github.com/kochetkov-ma/claude-brewcode
- Description: Claude Code plugin suite: brewcode (skill/agent/rule authoring, semble semantic search, superreview and teams setups), brewdoc (doc sync, PDF, publish), brewtools (text optimization, secrets scan, deploy, SSH, subagent guards)
- Why: compound search/retrieval fit, semantic search, stars>=20

### essmos/nonodb

- Verdict: **WATCH**
- Score: 18
- Stars: 21
- Raw: #887
- URL: https://github.com/essmos/nonodb
- Description: The all-in-one JSON document database for small VMs and edge boxes. ~5 MB idle RAM,  BM25/fuzzy/vector search, SQL, encrypted backups, replication, and GUI. MIT licensed.
- Why: bm25, compound search/retrieval fit, stars>=20, vector search

### benolabsai/benodb

- Verdict: **WATCH**
- Score: 18
- Stars: 6
- Raw: #892
- URL: https://github.com/benolabsai/benodb
- Description: Embedded Apache Iceberg database in Rust & Python — SQL, 100M-scale vector search, BM25, and CSR graph via detached Puffin overlays.
- Why: bm25, compound search/retrieval fit, vector search


## System Architecture / Engineering Patterns

### pyeventsourcing/eventsourcing

- Verdict: **WATCH**
- Score: 31
- Stars: 1691
- Raw: #1492
- URL: https://github.com/pyeventsourcing/eventsourcing
- Description: A library for event sourcing in Python.
- Why: cqrs, event sourcing, high-value architecture pattern, stars>=1000, system architecture / engineering patterns fit

### kirimatt/goncordia

- Verdict: **WATCH**
- Score: 20
- Stars: 70
- Raw: #1464
- URL: https://github.com/kirimatt/goncordia
- Description: Background job queue for Go on the database you already use: Postgres, MySQL, MariaDB, SQLite, MongoDB, Redis, DynamoDB, Firestore, Cassandra, ClickHouse. Transactional outbox enqueue, typed futures (await job results), retries, cron, retention, admin UI, OpenTelemetry.
- Why: high-value architecture pattern, stars>=20, system architecture / engineering patterns fit, transactional outbox
