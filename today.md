---
title: Creative Radar Shortlist 2026-10-18
date: 2026-10-18
status: shortlist
tags:
  - radar
  - creative-radar
  - shortlist
---

# Creative Radar Shortlist — 2026-10-18

Source: [[../scored/2026-10-18|Scored 2026-10-18]]

## Навигация

- [Agent Memory / Context](#agent-memory-context) — 9
- [Agent Reliability / Evals & Production](#agent-reliability-evals-&-production) — 1
- [Agent Security / Governance](#agent-security-governance) — 2
- [Automation / Event Workflows](#automation-event-workflows) — 8
- [Design / Image Editing](#design-image-editing) — 1
- [Design Systems / Visual QA](#design-systems-visual-qa) — 2
- [Document Parsing / Ingestion](#document-parsing-ingestion) — 3
- [Font Creation / Typography Tools](#font-creation-typography-tools) — 2
- [Interactive Reports / Data Apps](#interactive-reports-data-apps) — 1
- [Lancelot / Agent Infrastructure](#lancelot-agent-infrastructure) — 7
- [OSINT / Investigations](#osint-investigations) — 1
- [Reverse Engineering / Binary Analysis](#reverse-engineering-binary-analysis) — 3
- [Search / Retrieval Engineering](#search-retrieval-engineering) — 4
- [Speech / TTS & Voice](#speech-tts-&-voice) — 6

## Agent Memory / Context

### felinics/Memoh

- Verdict: **WATCH**
- Score: 18
- Stars: 2702
- Raw: #793
- URL: https://github.com/felinics/Memoh
- Description: ✨ The open-source multi-agent platform. Every agent gets its own computer, desktop, network, and long-term memory.  You can bring your own key, or host your coding agent like Claude Code, Codex and so on.
- Why: compound agent memory/context fit, long-term memory, stars>=1000

### NirDiamant/Agent_Memory_Techniques

- Verdict: **WATCH**
- Score: 18
- Stars: 1107
- Raw: #823
- URL: https://github.com/NirDiamant/Agent_Memory_Techniques
- Description: Agent memory for LLMs: 30 runnable Jupyter notebooks covering conversation buffers, vector stores, knowledge graphs, episodic and semantic memory, MemGPT, Mem0, Letta, Zep, Graphiti, LoCoMo benchmarks, and production patterns.
- Why: agent memory, compound agent memory/context fit, semantic memory, stars>=1000

### mycelium-io/mycelium

- Verdict: **WATCH**
- Score: 18
- Stars: 121
- Raw: #799
- URL: https://github.com/mycelium-io/mycelium
- Description: Multi-agent coordination + persistent memory, semantic negotiation, async rooms, and a shared knowledge graph
- Why: compound agent memory/context fit, persistent memory, stars>=100

### rockywuest/qdrant-mcp-pi5

- Verdict: **WATCH**
- Score: 18
- Stars: 15
- Raw: #825
- URL: https://github.com/rockywuest/qdrant-mcp-pi5
- Description: Persistent semantic memory for AI agents on Raspberry Pi 5 — local Qdrant + MCP, no cloud, ~3s per query
- Why: compound agent memory/context fit, semantic memory

### juanmackie/mnemosyne-hermes

- Verdict: **WATCH**
- Score: 18
- Stars: 14
- Raw: #826
- URL: https://github.com/juanmackie/mnemosyne-hermes
- Description: Local-first persistent semantic memory and agent orchestration for Hermes, Claude Code, and MCP-compatible personal AI agents.
- Why: compound agent memory/context fit, semantic memory

### philbert440/rivetOS

- Verdict: **WATCH**
- Score: 18
- Stars: 9
- Raw: #787
- URL: https://github.com/philbert440/rivetOS
- Description: Agent memory and delegation tooling.
- Why: agent memory, compound agent memory/context fit

### IndelibleVivi/agent-memory-study

- Verdict: **WATCH**
- Score: 18
- Stars: 32
- Raw: #788
- URL: https://github.com/IndelibleVivi/agent-memory-study
- Description: Source-linked readings and reproducible studies of agent memory, belief revision, and experience reuse.
- Why: agent memory, compound agent memory/context fit, stars>=20

### YuanYeYouTao/Yuki

- Verdict: **WATCH**
- Score: 18
- Stars: 23
- Raw: #795
- URL: https://github.com/YuanYeYouTao/Yuki
- Description: An open-source social AI agent for QQ group chats: persistent identity, long-term memory, relationships, opt-in autonomous participation, and durable work.
- Why: compound agent memory/context fit, long-term memory, stars>=20

### EtanHey/brainlayer

- Verdict: **WATCH**
- Score: 18
- Stars: 9
- Raw: #804
- URL: https://github.com/EtanHey/brainlayer
- Description: Persistent memory MCP for AI agents — SQLite, knowledge graph, 13-tool Python MCP + 17-tool BrainBar surface with ToolAnnotations
- Why: compound agent memory/context fit, persistent memory


## Agent Reliability / Evals & Production

### dimitar-radenkov/Pointframe

- Verdict: **WATCH**
- Score: 18
- Stars: 14
- Raw: #934
- URL: https://github.com/dimitar-radenkov/Pointframe
- Description: Let your coding agent test the real Windows UI: an MCP server and CLI that inspect your app, drive its controls, and run repeatable checks with screenshots and signed evidence. Also a free screenshot, annotation and recording app. Open source, Windows x64.
- Why: compound agent reliability/evals fit


## Agent Security / Governance

### mcpware/IntentProbe

- Verdict: **WATCH**
- Score: 30
- Stars: 9
- Raw: #501
- URL: https://github.com/mcpware/IntentProbe
- Description: Activation-probe security scanner for AI agent tooling. Reads a model's internal activations to detect poisoned MCP servers, skills, and packages before install.
- Why: agent control-plane security fit, agent security/governance fit, strong agent-security signal

### pierce-boggan/AegisTrace

- Verdict: **WATCH**
- Score: 24
- Stars: 188
- Raw: #529
- URL: https://github.com/pierce-boggan/AegisTrace
- Description: Verifiable execution for durable AI agents: policy-bound workflow compiler, hash-chained journal, offline replay, and Merkle + Ed25519 proofs. Go.
- Why: agent control-plane security fit, agent security/governance fit, stars>=100, strong agent-security signal


## Automation / Event Workflows

### ejlevin1/n8n-nodes-hermes

- Verdict: **KEEP**
- Score: 36
- Stars: 0
- Raw: #666
- URL: https://github.com/ejlevin1/n8n-nodes-hermes
- Description: n8n community nodes for Nous Research Hermes Agent: API server actions, outbound-event trigger, signed webhook routes
- Why: automation ops/tooling fit, automation reusable implementation, n8n, n8n identity fit, n8n node/plugin fit, trigger, webhook, workflow/event integration fit

### nicholasbergesen/n8n-nodes-vivere

- Verdict: **WATCH**
- Score: 26
- Stars: 0
- Raw: #659
- URL: https://github.com/nicholasbergesen/n8n-nodes-vivere
- Description: n8n node for Vivere: get alerted when a workflow stops running, does nothing, or fails
- Why: automation ops/tooling fit, automation reusable implementation, n8n, n8n identity fit, n8n node/plugin fit, workflow/event integration fit

### HP-jh/TarsN8N

- Verdict: **WATCH**
- Score: 25
- Stars: 0
- Raw: #677
- URL: https://github.com/HP-jh/TarsN8N
- Description: TSG MCP adapter for N8N - workflow automation platform
- Why: automation platform, event/workflow automation identity fit, n8n, n8n identity fit, workflow automation, workflow/event integration fit

### tonyyield/n8n-nodes-databox

- Verdict: **WATCH**
- Score: 22
- Stars: 0
- Raw: #657
- URL: https://github.com/tonyyield/n8n-nodes-databox
- Description: n8n community node for Databox. Push records into Databox datasets in confirmed batches, create and list datasets, and check ingestion status. Built for n8n Cloud verification. n8n n8n-community-node-package n8n-nodes databox analytics etl data-integration
- Why: automation reusable implementation, n8n, n8n identity fit, n8n node/plugin fit, workflow/event integration fit

### Groundmail/n8n-nodes-groundmail

- Verdict: **WATCH**
- Score: 20
- Stars: 0
- Raw: #661
- URL: https://github.com/Groundmail/n8n-nodes-groundmail
- Description: n8n community node for Groundmail, the transactional email API
- Why: automation ops/tooling fit, automation reusable implementation, n8n, n8n identity fit, n8n node/plugin fit

### Icelordpro11/My-Calendar-App

- Verdict: **WATCH**
- Score: 20
- Stars: 0
- Raw: #681
- URL: https://github.com/Icelordpro11/My-Calendar-App
- Description: An Android calendar application built with Kotlin, featuring appointment management, client tracking, reminders, financial management, and n8n workflow automation for AI-powered voice input and appointment processing.
- Why: automation ops/tooling fit, n8n, n8n identity fit, workflow automation, workflow/event integration fit

### sumitrmardy/email-verifier-api

- Verdict: **WATCH**
- Score: 19
- Stars: 0
- Raw: #708
- URL: https://github.com/sumitrmardy/email-verifier-api
- Description: Bulk email verification API for n8n, AI agents & MCP — SMTP, MX, catch-all, disposable. Schema-stable JSON, never null. EN / 中文
- Why: automation AI/MCP fit, automation ops/tooling fit, n8n, n8n identity fit, workflow/event integration fit

### assa83/medium-scraper-api

- Verdict: **WATCH**
- Score: 18
- Stars: 0
- Raw: #703
- URL: https://github.com/assa83/medium-scraper-api
- Description: Medium API in Python & JS: scrape Medium articles by tag, author, publication or search, with claps, reading time and full text as Markdown for RAG. n8n + MCP.
- Why: automation ops/tooling fit, automation reusable implementation, n8n, n8n identity fit, workflow/event integration fit


## Design / Image Editing

### Capture-Moment/CaptureMoment

- Verdict: **WATCH**
- Score: 20
- Stars: 15
- Raw: #1346
- URL: https://github.com/Capture-Moment/CaptureMoment
- Description: Open-source non-destructive photo editor (GPLv3). Cross-platform. RAW processing, cataloging (SQLite/XMP), color science (OCIO), performance (OIIO/Halide). No commercial forks without source disclosure. Maintains original name/credits.
- Why: image editing fit, non-destructive, photo editor


## Design Systems / Visual QA

### EthanY33/atelier

- Verdict: **KEEP**
- Score: 35
- Stars: 6
- Raw: #1417
- URL: https://github.com/EthanY33/atelier
- Description: Claude Code plugin, listed in awesome-claude-code. One brand.json drives tokens, social cards, icons, images, video and two audits across 8 skills. Also a CLI and a GitHub Action.
- Why: agent-native structured implementation, agent-native workflow, audit, design QA fit, figma, tokens

### hackclub/theme

- Verdict: **WATCH**
- Score: 25
- Stars: 68
- Raw: #1370
- URL: https://github.com/hackclub/theme
- Description: The design system behind Hack Club's website, available as tokens, CSS and web components. Works with any framework, or none at all.
- Why: design QA fit, design system, design-system, stars>=20, tokens


## Document Parsing / Ingestion

### nfsarch33/pdf-mcp-server

- Verdict: **WATCH**
- Score: 18
- Stars: 7
- Raw: #1098
- URL: https://github.com/nfsarch33/pdf-mcp-server
- Description: Local-first CLI + MCP server for everything PDF: form fill, OCR, redaction, signatures, table extraction, and LLM-backed document understanding.
- Why: compound document parsing/ingestion fit, ocr, table extraction

### myhloli/DocVortex

- Verdict: **WATCH**
- Score: 18
- Stars: 71
- Raw: #1057
- URL: https://github.com/myhloli/DocVortex
- Description: A fast, multi-format document parsing and conversion engine
- Why: compound document parsing/ingestion fit, stars>=20

### muippt/mu-pdf-converter

- Verdict: **WATCH**
- Score: 18
- Stars: 6
- Raw: #1100
- URL: https://github.com/muippt/mu-pdf-converter
- Description: PDF文件高保真转换器｜High-fidelity PDF format converter — four-layer PPT conversion, three-engine table extraction, auto-translation. 100% local, open source.
- Why: compound document parsing/ingestion fit, ocr, table extraction


## Font Creation / Typography Tools

### fontgarden/runebender

- Verdict: **WATCH**
- Score: 30
- Stars: 96
- Raw: #1
- URL: https://github.com/fontgarden/runebender
- Description: A font editor built on the Linebender ecosystem of Rust crates.
- Why: font, font editor, font/typography tooling fit, fonts, opentype, stars>=20

### harshpreet931/harshpreet-hand

- Verdict: **WATCH**
- Score: 30
- Stars: 29
- Raw: #32
- URL: https://github.com/harshpreet931/harshpreet-hand
- Description: I gave Claude Code 120 pages of my handwritten college notes. It gave me back my handwriting as a real font, in 66 minutes for $13.68.
- Why: font/typography tooling fit, fonttools, opentype, stars>=20, typography, webfont


## Interactive Reports / Data Apps

### NihalJain/opensource-contributions-tracker

- Verdict: **WATCH**
- Score: 18
- Stars: 9
- Raw: #1571
- URL: https://github.com/NihalJain/opensource-contributions-tracker
- Description: Track the open source work of a person, a team or an organization: pull requests authored and reviewed, issues reported on GitHub and Jira. Runs on GitHub Actions and publishes an interactive dashboard, a Markdown report and an embeddable stats card.
- Why: dashboard, interactive/reporting implementation fit, report


## Lancelot / Agent Infrastructure

### Adi15Jain/cf_ai_next_doctor

- Verdict: **KEEP**
- Score: 35
- Stars: 0
- Raw: #559
- URL: https://github.com/Adi15Jain/cf_ai_next_doctor
- Description: Deploy doctor for Next.js on Cloudflare Workers: evidence-backed static checks, a Workflow per scan, and Llama 3.3 explanations, built on the Agents SDK
- Why: lancelot high fit

### AftabIbrahimKazi/ai-dev-kit

- Verdict: **KEEP**
- Score: 35
- Stars: 7
- Raw: #579
- URL: https://github.com/AftabIbrahimKazi/ai-dev-kit
- Description: Agent skills (SKILL.md), layered coding standards, a project-wide code audit and optional free/local MCP servers for AI-assisted development: Claude Code, OpenCode, Codex and any agent that reads markdown.
- Why: lancelot high fit

### jiapengLi11/AgentGuard

- Verdict: **KEEP**
- Score: 35
- Stars: 1
- Raw: #637
- URL: https://github.com/jiapengLi11/AgentGuard
- Description: Sujie: runtime security gateway for prompt injection and MCP tool abuse defense
- Why: lancelot high fit

### schembora/cf_ai_atc_trainer

- Verdict: **KEEP**
- Score: 35
- Stars: 0
- Raw: #558
- URL: https://github.com/schembora/cf_ai_atc_trainer
- Description: Practice ATC radio phraseology against an AI controller with live weather. Built on Cloudflare Workers, Agents SDK, Workflows and Workers AI.
- Why: lancelot high fit

### BenniAlencar/agent-cyber-sentinel

- Verdict: **WATCH**
- Score: 18
- Stars: 2
- Raw: #638
- URL: https://github.com/BenniAlencar/agent-cyber-sentinel
- Description: Tier-0 Zero-Trust Runtime Security Shield, Prompt Injection Firewall, Secret Leak Interceptor and Tool Call Sanitizer for AI Agents and MCP Servers. Governed by Benni Master OS v9.4 (Skill 63 Cyber Sentinel OS).
- Why: lancelot keep fit

### jimku233/workflow-visualizer

- Verdict: **WATCH**
- Score: 18
- Stars: 0
- Raw: #574
- URL: https://github.com/jimku233/workflow-visualizer
- Description: Turn a business process into an interactive, self-contained HTML flowchart — zero dependencies, fully offline, no build step. Also exports Mermaid source plus SVG/PNG. Runs as an agent skill (SKILL.md / AGENTS.md) or as a Node >= 18 CLI.
- Why: lancelot keep fit

### KeithScholz/mcp-rest-api

- Verdict: **WATCH**
- Score: 18
- Stars: 0
- Raw: #590
- URL: https://github.com/KeithScholz/mcp-rest-api
- Description: A TypeScript-based MCP server that enables testing of REST APIs through Cline. This tool allows you to test and interact with any REST API endpoints directly from your development environment.
- Why: lancelot keep fit


## OSINT / Investigations

### KillaMeep/waypoint-osint

- Verdict: **WATCH**
- Score: 18
- Stars: 9
- Raw: #1608
- URL: https://github.com/KillaMeep/waypoint-osint
- Description: Free, open-source desktop app that estimates where a photo was taken. Self-contained, Windows, no paid APIs.
- Why: geoint, geolocation, osint/investigations fit


## Reverse Engineering / Binary Analysis

### morluto/awesome-reverse-engineering

- Verdict: **WATCH**
- Score: 18
- Stars: 710
- Raw: #1146
- URL: https://github.com/morluto/awesome-reverse-engineering
- Description: Curated reverse-engineering tools and learning resources for binaries, apps, firmware, formats, and protocols.
- Why: compound reverse engineering fit, decompiler, disassembler, ghidra, stars>=100
- Caution: ctf

### nhuhuan/sba

- Verdict: **WATCH**
- Score: 18
- Stars: 52
- Raw: #1152
- URL: https://github.com/nhuhuan/sba
- Description: Static Binary Analysis Framework
- Why: binary analysis, compound reverse engineering fit, stars>=20

### zhuyansen/awesome-ai-reverse-engineering

- Verdict: **WATCH**
- Score: 18
- Stars: 6
- Raw: #1156
- URL: https://github.com/zhuyansen/awesome-ai-reverse-engineering
- Description: Open-source AI reverse engineering tools for coding agents: Ghidra MCP, IDA Pro MCP, jadx, Frida, skills and REA. 122 repos, each read and security-graded. EN + 中文.
- Why: compound reverse engineering fit, decompiler, ghidra, reverse engineering


## Search / Retrieval Engineering

### Soren-ABT/dsh-knowledge

- Verdict: **WATCH**
- Score: 18
- Stars: 77
- Raw: #851
- URL: https://github.com/Soren-ABT/dsh-knowledge
- Description: Knowledge base & RAG plugin for DeepSeek Harness (DSH): chunking, local embeddings, hybrid search, management panel
- Why: compound search/retrieval fit, hybrid search, stars>=20

### Dicklesworthstone/meta_skill

- Verdict: **WATCH**
- Score: 18
- Stars: 206
- Raw: #856
- URL: https://github.com/Dicklesworthstone/meta_skill
- Description: Local-first skill management platform for AI coding agents: dual SQLite+Git persistence, semantic search, bandit-optimized suggestions, and MCP integration
- Why: compound search/retrieval fit, semantic search, stars>=100

### meta-recsys/silvertorch

- Verdict: **WATCH**
- Score: 18
- Stars: 36
- Raw: #862
- URL: https://github.com/meta-recsys/silvertorch
- Description: Silvertorch is a high-performance open-source GPU retrieval engine designed for large-scale recommender systems, generative retrieval (RAG), and vector search — optimized for latency, throughput, and GPU cost efficiency.
- Why: compound search/retrieval fit, retrieval engine, stars>=20, vector search

### wosledon/Hetu

- Verdict: **WATCH**
- Score: 18
- Stars: 11
- Raw: #857
- URL: https://github.com/wosledon/Hetu
- Description: 本地优先的 AI 知识与 Agent 工作台：Markdown 笔记 + 对话/编码会话，配向量检索、知识图谱、Wiki、记忆、看板与工作流，支持 MCP / 技能 / 多模型 · Local-first AI knowledge & agent workspace with semantic search, knowledge graph, memories, kanban, workflows & MCP
- Why: compound search/retrieval fit, semantic search


## Speech / TTS & Voice

### lukaszliniewicz/Pandrator

- Verdict: **WATCH**
- Score: 18
- Stars: 636
- Raw: #982
- URL: https://github.com/lukaszliniewicz/Pandrator
- Description: Turn PDFs and EPUBs into audiobooks; subtitles or videos into dubbed videos (including translation), and more. For free. Pandrator uses local models, including voice-cloning (instant, RVC-enhanced, XTTS fine-tuning) and LLM processing. It aspires to be a user-friendly app with a GUI, an installer and all-in-one packages.
- Why: compound deployable speech/TTS fit, stars>=100, text-to-speech, tts

### MohammedAly22/VoiceTuT-TTS

- Verdict: **WATCH**
- Score: 18
- Stars: 41
- Raw: #973
- URL: https://github.com/MohammedAly22/VoiceTuT-TTS
- Description: VoiceTut-TTS is an Egyptian-Arabic text-to-speech system fine-tuned from OmniVoice on ~380 hours of Egyptian podcast speech. It produces natural Egyptian speech with seamless Arabic ↔ English code-switching, ships 15 built-in studio voices, supports zero-shot voice cloning
- Why: compound deployable speech/TTS fit, stars>=20, text-to-speech, tts, voice cloning

### NVIDIA-NeMo/Speech

- Verdict: **WATCH**
- Score: 18
- Stars: 18597
- Raw: #972
- URL: https://github.com/NVIDIA-NeMo/Speech
- Description: A scalable generative AI framework built for researchers and developers working on Large Language Models, Multimodal, and Speech AI (Automatic Speech Recognition and Text-to-Speech)
- Why: compound deployable speech/TTS fit, stars>=1000, text-to-speech, tts

### OHF-Voice/piper1-gpl

- Verdict: **WATCH**
- Score: 18
- Stars: 5906
- Raw: #976
- URL: https://github.com/OHF-Voice/piper1-gpl
- Description: Fast and local neural text-to-speech engine
- Why: compound deployable speech/TTS fit, stars>=1000, text-to-speech

### FurkanGozukara/Stable-Diffusion

- Verdict: **WATCH**
- Score: 18
- Stars: 2780
- Raw: #981
- URL: https://github.com/FurkanGozukara/Stable-Diffusion
- Description: FLUX, Stable Diffusion, SDXL, SD3, LoRA, Fine Tuning, DreamBooth, Training, Automatic1111, Forge WebUI, SwarmUI, DeepFake, TTS, Animation, Text To Video, Tutorials, Guides, Lectures, Courses, ComfyUI, Google Colab, RunPod, Kaggle, NoteBooks, ControlNet, TTS, Voice Cloning, AI, AI News, ML, ML News, News, Tech, Tech News, Kohya, Midjourney, RunPod
- Why: stars>=1000, tts, voice cloning

### Somnius/shadowrealms-ai

- Verdict: **WATCH**
- Score: 18
- Stars: 21
- Raw: #985
- URL: https://github.com/Somnius/shadowrealms-ai
- Description: Self-hosted AI Storyteller for World of Darkness: Classic (oWoD Revised) and V5 rules, dice pools from your character sheet, Discord-style chat with voice (listen and speak, local TTS and Whisper), local LLMs (LM Studio / Ollama) with RAG memory, English and Greek.
- Why: compound deployable speech/TTS fit, stars>=20, text-to-speech, tts
- Caution: game
