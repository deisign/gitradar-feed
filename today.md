---
title: Creative Radar Shortlist 2026-10-28
date: 2026-10-28
status: shortlist
tags:
  - radar
  - creative-radar
  - shortlist
---

# Creative Radar Shortlist — 2026-10-28

Source: [[../scored/2026-10-28|Scored 2026-10-28]]

## Навигация

- [Agent Memory / Context](#agent-memory-context) — 5
- [Agent Reliability / Evals & Production](#agent-reliability-evals-&-production) — 1
- [Automation / Event Workflows](#automation-event-workflows) — 6
- [Design / Image Editing](#design-image-editing) — 1
- [Design Systems / Visual QA](#design-systems-visual-qa) — 1
- [Document Parsing / Ingestion](#document-parsing-ingestion) — 2
- [Font Creation / Typography Tools](#font-creation-typography-tools) — 2
- [Infographics / Visual Storytelling](#infographics-visual-storytelling) — 1
- [Lancelot / Agent Infrastructure](#lancelot-agent-infrastructure) — 8
- [OSINT / Investigations](#osint-investigations) — 1
- [Speech / TTS & Voice](#speech-tts-&-voice) — 3
- [System Architecture / Engineering Patterns](#system-architecture-engineering-patterns) — 1
- [Telegram Bots / Automation](#telegram-bots-automation) — 1
- [Video Production / Editing](#video-production-editing) — 1
- [Web Data / Crawling & Extraction](#web-data-crawling-&-extraction) — 1

## Agent Memory / Context

### wrg32786/aigent-os

- Verdict: **WATCH**
- Score: 18
- Stars: 25
- Raw: #798
- URL: https://github.com/wrg32786/aigent-os
- Description: Claude Code harness and alternative to context compaction: at 80% context it writes a verified capsule, runs /clear and resumes with persistent memory in git. Long-running and multi-agent Claude Code sessions, auto clear instead of auto-compact. MIT, local, Node 18+. Codex adapter.
- Why: compound agent memory/context fit, persistent memory, stars>=20

### Gentleman-Programming/gentle-shell

- Verdict: **WATCH**
- Score: 18
- Stars: 1463
- Raw: #799
- URL: https://github.com/Gentleman-Programming/gentle-shell
- Description: Gentle Shell is a Pi-native workspace for AI-assisted development, bringing parallel coding agents, live tasks, Git diffs, persistent memory, and permission controls into one terminal interface. Powered by Gentle AI and Organic Driven Development (ODD).
- Why: compound agent memory/context fit, persistent memory, stars>=1000

### mthines/lorekit

- Verdict: **WATCH**
- Score: 18
- Stars: 20
- Raw: #800
- URL: https://github.com/mthines/lorekit
- Description: Free, open source, local & remote, persistent memory for your AI coding agents.
- Why: compound agent memory/context fit, persistent memory, stars>=20

### AgentGameLab/mneme

- Verdict: **WATCH**
- Score: 18
- Stars: 7
- Raw: #789
- URL: https://github.com/AgentGameLab/mneme
- Description: Persistent long-term memory for Claude Code agents — SQLite + FTS5 + sqlite-vec + RRF hybrid recall over MCP, with Chinese tokenization. Local-first, graceful degradation.
- Why: compound agent memory/context fit, long-term memory
- Caution: game

### AegeanWorks/NeuroCore

- Verdict: **WATCH**
- Score: 18
- Stars: 8
- Raw: #790
- URL: https://github.com/AegeanWorks/NeuroCore
- Description: A self-hosted, modular AI agent framework for persistent, tool-using autonomous systems: workflows, long-term memory, RAG and a plugin architecture in one platform. Free personal use under AL-1.1; commercial use under ACL-1.0.
- Why: compound agent memory/context fit, long-term memory


## Agent Reliability / Evals & Production

### microsoft/AKS-Lab-GitHubCopilot

- Verdict: **WATCH**
- Score: 18
- Stars: 10
- Raw: #936
- URL: https://github.com/microsoft/AKS-Lab-GitHubCopilot
- Description: ZavaShop multi-agent retail demo on AKS + ACA. Specs, MCP servers, agents, tests, Bicep/Helm and CI are all authored by 6 GitHub Copilot Custom Coding Agents using Microsoft Agent Framework + Copilot SDK.
- Why: compound agent reliability/evals fit


## Automation / Event Workflows

### creviolabs/n8n-nodes-crevio

- Verdict: **WATCH**
- Score: 31
- Stars: 0
- Raw: #654
- URL: https://github.com/creviolabs/n8n-nodes-crevio
- Description: n8n community nodes for Crevio: customers, products, orders, checkouts, bookings, the Crevio AI agent, and a trigger for Crevio events
- Why: automation AI/MCP fit, automation reusable implementation, n8n, n8n identity fit, n8n node/plugin fit, trigger, workflow/event integration fit

### quietengineco/n8n-workflow-architect-lite

- Verdict: **WATCH**
- Score: 22
- Stars: 0
- Raw: #678
- URL: https://github.com/quietengineco/n8n-workflow-architect-lite
- Description: Free agent skill for planning n8n workflows, plus an offline validator for workflow JSON (Python, no dependencies).
- Why: automation high-value tooling, automation reusable implementation, n8n, n8n identity fit, workflow/event integration fit

### inwendo/n8n-nodes-inwendo-erp

- Verdict: **WATCH**
- Score: 19
- Stars: 0
- Raw: #688
- URL: https://github.com/inwendo/n8n-nodes-inwendo-erp
- Description: n8n integration for inwendo ERP / vynst
- Why: n8n, n8n identity fit, n8n node/plugin fit, workflow/event integration fit

### Chamm286/MedicareGuard

- Verdict: **WATCH**
- Score: 18
- Stars: 0
- Raw: #644
- URL: https://github.com/Chamm286/MedicareGuard
- Description: Full-stack SOC platform for healthcare: Next.js console, Express API, PostgreSQL, n8n automation, 541 endpoints and 4 response workflows.
- Why: automation ops/tooling fit, automation reusable implementation, n8n, n8n identity fit, workflow/event integration fit

### devtechedge/handoffkit

- Verdict: **WATCH**
- Score: 18
- Stars: 0
- Raw: #679
- URL: https://github.com/devtechedge/handoffkit
- Description: Client-ready handover packs for AI automation agencies. Import an n8n workflow export and get a branded pack: readiness score, AI register, data and credential map, runbook, share link, Markdown and PDF. Deterministic analysis, no LLM, no workflow stored. One free pack; Pro billing opens after early-access testing. Next.js and Neon.
- Why: automation ops/tooling fit, automation reusable implementation, n8n, n8n identity fit, workflow/event integration fit

### Shahyan360/n8n-ecommerce-inventory-sync

- Verdict: **WATCH**
- Score: 18
- Stars: 0
- Raw: #672
- URL: https://github.com/Shahyan360/n8n-ecommerce-inventory-sync
- Description: E-commerce order, inventory and shipping automation: 13 n8n workflows, atomic PostgreSQL reservations, TypeScript services and a credential-free public demo.
- Why: automation ops/tooling fit, automation reusable implementation, n8n, n8n identity fit, workflow/event integration fit


## Design / Image Editing

### ClaudiuJitea/compositorLX

- Verdict: **WATCH**
- Score: 20
- Stars: 6
- Raw: #1356
- URL: https://github.com/ClaudiuJitea/compositorLX
- Description: Native Linux port of Compositor — a layer-based raster image editor with masks, adjustments, and local subject removal.
- Why: image editing fit, image editor, layer-based


## Design Systems / Visual QA

### facebook/meta-ray-ban-display-ui-toolkit-web

- Verdict: **WATCH**
- Score: 20
- Stars: 21
- Raw: #1363
- URL: https://github.com/facebook/meta-ray-ban-display-ui-toolkit-web
- Description: UI Toolkit brings the Meta Ray-Ban Display design system to React. Use its components, semantic tokens, materials, motion, accessibility behavior, and directional focus navigation to build interfaces that stay consistent across applications.
- Why: design QA fit, design system, stars>=20, tokens


## Document Parsing / Ingestion

### CHEN010325/paddleocr-local

- Verdict: **WATCH**
- Score: 18
- Stars: 138
- Raw: #1053
- URL: https://github.com/CHEN010325/paddleocr-local
- Description: Local-first document parsing workbench for five OCR models: PDF/Office to Markdown with WebUI, model switching, CLI and Apple Silicon support.
- Why: compound document parsing/ingestion fit, ocr, stars>=100

### zhihengli-casia/PureDocBench

- Verdict: **WATCH**
- Score: 18
- Stars: 49
- Raw: #1055
- URL: https://github.com/zhihengli-casia/PureDocBench
- Description: PureDocBench: source-traceable benchmark for document parsing across clean, degraded, and real-world settings
- Why: compound document parsing/ingestion fit, ocr, stars>=20


## Font Creation / Typography Tools

### yashau/fonts.mv

- Verdict: **WATCH**
- Score: 28
- Stars: 6
- Raw: #33
- URL: https://github.com/yashau/fonts.mv
- Description: Open Dhivehi (Thaana) fonts for the web: a Google-Fonts-style CSS API and downloads, plus agent-ready @yashau/thaana packages for React, Svelte, Vue and plain JS (phonetic keyboard, bidi toolkit, llms.txt).
- Why: font/typography tooling fit, fonts, fonttools, typography, webfont

### damieng/ch8ter

- Verdict: **WATCH**
- Score: 18
- Stars: 9
- Raw: #5
- URL: https://github.com/damieng/ch8ter
- Description: CH8 font editor for the web
- Why: font, font editor, font/typography tooling fit


## Infographics / Visual Storytelling

### sirioberati/YouTube-AI-Motion-Graphics

- Verdict: **KEEP**
- Score: 38
- Stars: 26
- Raw: #96
- URL: https://github.com/sirioberati/YouTube-AI-Motion-Graphics
- Description: AI motion graphics for YouTube explainer videos: 74 animated HTML explainer boards (charts, diagrams, Venn, timeline, heatmap) synced to your voice with Whisper, exported frame by frame with Chrome + FFmpeg. Every prompt + Claude skills. By TEIN AI.
- Why: agent-native workflow, chart, diagram, infographics/visual storytelling fit, map, stars>=20, timeline


## Lancelot / Agent Infrastructure

### ruelbelmonte/mcp-notes

- Verdict: **KEEP**
- Score: 35
- Stars: 0
- Raw: #587
- URL: https://github.com/ruelbelmonte/mcp-notes
- Description: An MCP server exposing read-only, sandboxed tools over a markdown notes vault. Path-traversal protection and search logic are unit-tested; the MCP wiring is a thin adapter. TypeScript.
- Why: lancelot high fit

### Vampsecure-Labs/vamp-mcp-audit

- Verdict: **KEEP**
- Score: 35
- Stars: 2
- Raw: #634
- URL: https://github.com/Vampsecure-Labs/vamp-mcp-audit
- Description: MCP server security auditor — tool poisoning, ASCII smuggling detection, prompt injection, OWASP Agentic Top 10. First OSS tool for MCP security.
- Why: lancelot high fit

### arjunbhandage/trip-planner

- Verdict: **KEEP**
- Score: 35
- Stars: 0
- Raw: #554
- URL: https://github.com/arjunbhandage/trip-planner
- Description: Trip planning chat agent on Cloudflare Agents SDK, Workers AI and Workflows
- Why: lancelot high fit

### sharonita610/agent-harness

- Verdict: **KEEP**
- Score: 35
- Stars: 0
- Raw: #593
- URL: https://github.com/sharonita610/agent-harness
- Description: Domain-pluggable LLM agent runtime with tool permissions, human approval, MCP server, and a repeatable eval harness. Local models (llama.cpp) and hosted APIs.
- Why: lancelot high fit

### hyperbolictonic/hyperbolic-gateway

- Verdict: **WATCH**
- Score: 18
- Stars: 2
- Raw: #600
- URL: https://github.com/hyperbolictonic/hyperbolic-gateway
- Description: Kuang Grade Mark Eleven: a self-hosted MCP browser agent - a real Chromium your LLM can drive. Local-first, no cloud, no API keys, no telemetry. A DIY alternative to browser-use, Playwright agents and hosted browser clouds.
- Why: lancelot keep fit

### mohanish3/AgentPreflightSec

- Verdict: **WATCH**
- Score: 18
- Stars: 0
- Raw: #633
- URL: https://github.com/mohanish3/AgentPreflightSec
- Description: Security scanner for MCP servers and AI agent skills. Detects tool poisoning, prompt injection, secrets, and unsafe code with offline static analysis.
- Why: lancelot keep fit

### AxiomatAI/dojo-hub

- Verdict: **WATCH**
- Score: 18
- Stars: 0
- Raw: #572
- URL: https://github.com/AxiomatAI/dojo-hub
- Description: DojoHub is a self-hosted, enterprise-grade registry for AI agent skills (SKILL.md), with SSO, security scanning, BYOK LLM verification, team approval workflows, and npx skills compatibility.
- Why: lancelot keep fit

### Err0ric/lure

- Verdict: **WATCH**
- Score: 18
- Stars: 0
- Raw: #632
- URL: https://github.com/Err0ric/lure
- Description: Open-source test harness for AI agents: prompt injection, tool poisoning and MCP attacks in an isolated Docker sandbox, with approval reports mapped to MITRE ATLAS and OWASP LLM Top 10
- Why: lancelot keep fit


## OSINT / Investigations

### vaishantsah/watson-AI-osint-all-in-one

- Verdict: **WATCH**
- Score: 18
- Stars: 204
- Raw: #1590
- URL: https://github.com/vaishantsah/watson-AI-osint-all-in-one
- Description: Watson — free OSINT tool for Windows: people search across 3,100+ public sites by nickname, email, phone or website. Open-source intelligence made simple: digital footprint check, username lookup, social media search. No account, no tracking. Site: watsonfind.icu
- Why: osint/investigations fit, stars>=100, username lookup


## Speech / TTS & Voice

### oddmeta/oddtts

- Verdict: **WATCH**
- Score: 18
- Stars: 22
- Raw: #1000
- URL: https://github.com/oddmeta/oddtts
- Description: A powerful multi-engine text-to-speech synthesis service that provides a unified API interface and a user-friendly Web UI. With a single set of APIs, it supports multiple mainstream TTS engines, including EdgeTTS, Kokoro-82M-v1.1-zh, ZipVoice, ChatTTS, Bert-VITS2, GptSovits v2, Moss-TTS-Nano, Audio8, etc., and also supports OpenAI TTS API calls.
- Why: compound deployable speech/TTS fit, speech synthesis, stars>=20, text-to-speech, tts

### remsky/Kokoro-FastAPI

- Verdict: **WATCH**
- Score: 18
- Stars: 5604
- Raw: #969
- URL: https://github.com/remsky/Kokoro-FastAPI
- Description: Dockerized OpenAI-compatible wrapper for Kokoro-82M text-to-speech w/multiplatform CPU, AMD, NVIDIA GPU PyTorch; multi-speaker, clone-tuning, caption timestamps, SSML, optional readalong web UI
- Why: compound deployable speech/TTS fit, stars>=1000, text-to-speech, tts

### rodaddy/agent-voice

- Verdict: **WATCH**
- Score: 18
- Stars: 20
- Raw: #1009
- URL: https://github.com/rodaddy/agent-voice
- Description: Give any LLM agent a cloned voice: its reply in, one spoken line out, via an OmniVoice TTS server.
- Why: compound deployable speech/TTS fit, stars>=20, tts


## System Architecture / Engineering Patterns

### TerraSkye/eventsourcing

- Verdict: **WATCH**
- Score: 23
- Stars: 6
- Raw: #1451
- URL: https://github.com/TerraSkye/eventsourcing
- Description: Event Sourcing in Go
- Why: cqrs, event sourcing, high-value architecture pattern, system architecture / engineering patterns fit


## Telegram Bots / Automation

### adityash4rma/flaregram

- Verdict: **WATCH**
- Score: 18
- Stars: 81
- Raw: #385
- URL: https://github.com/adityash4rma/flaregram
- Description: Telegram bot API framework for Cloudflare workers.
- Why: stars>=20, telegram bot, telegram bot api, telegram bot/agent fit


## Video Production / Editing

### siri2moon/moonreel

- Verdict: **WATCH**
- Score: 28
- Stars: 7
- Raw: #1277
- URL: https://github.com/siri2moon/moonreel
- Description: Open-source Meta Muse video generator: no Muse video API yet, so MoonReel automates muse.ai for you. One idea in, a scripted, subtitled short video out for TikTok, Reels, Shorts and YouTube.
- Why: ffmpeg, short video, subtitle, video, video production fit


## Web Data / Crawling & Extraction

### felipecsl/wombat

- Verdict: **WATCH**
- Score: 18
- Stars: 1360
- Raw: #1032
- URL: https://github.com/felipecsl/wombat
- Description: Lightweight Ruby web crawler/scraper with an elegant DSL which extracts structured data from pages.
- Why: compound web crawling/extraction fit, stars>=1000, web crawler
