---
title: Creative Radar Shortlist 2026-11-06
date: 2026-11-06
status: shortlist
tags:
  - radar
  - creative-radar
  - shortlist
---

# Creative Radar Shortlist — 2026-11-06

Source: [[../scored/2026-11-06|Scored 2026-11-06]]

## Навигация

- [Agent Memory / Context](#agent-memory-context) — 4
- [Agent Reliability / Evals & Production](#agent-reliability-evals-&-production) — 1
- [Agent Security / Governance](#agent-security-governance) — 4
- [Automation / Event Workflows](#automation-event-workflows) — 11
- [Design Systems / Visual QA](#design-systems-visual-qa) — 1
- [Device Control / Capture](#device-control-capture) — 1
- [Document Parsing / Ingestion](#document-parsing-ingestion) — 2
- [Full-Song AI / Suno Alternatives](#full-song-ai-suno-alternatives) — 1
- [Infographics / Visual Storytelling](#infographics-visual-storytelling) — 2
- [Lancelot / Agent Infrastructure](#lancelot-agent-infrastructure) — 13
- [Mixing / Mastering / Audio Engineering](#mixing-mastering-audio-engineering) — 1
- [OSINT / Investigations](#osint-investigations) — 1
- [Reverse Engineering / Binary Analysis](#reverse-engineering-binary-analysis) — 1
- [Speech / TTS & Voice](#speech-tts-&-voice) — 2
- [System Architecture / Engineering Patterns](#system-architecture-engineering-patterns) — 1
- [Video Production / Editing](#video-production-editing) — 2

## Agent Memory / Context

### Glen-Web-App/best-agent-memory-mcp

- Verdict: **WATCH**
- Score: 20
- Stars: 152
- Raw: #841
- URL: https://github.com/Glen-Web-App/best-agent-memory-mcp
- Description: Best Agent Memory MCP servers, ranked and compared: long-term memory for Claude Code, Codex, Cursor and any MCP client. Glen, Mem0, Supermemory, Zep, Hindsight, Basic Memory, claude-mem, Graphiti, Cognee, the official memory server and more, with storage, capture model, team sharing, license and live stars.
- Why: agent memory, compound agent memory/context fit, long-term memory, memory server, stars>=100

### get-engram/engram

- Verdict: **WATCH**
- Score: 18
- Stars: 22
- Raw: #797
- URL: https://github.com/get-engram/engram
- Description: Persistent, searchable long-term memory for AI agents. MCP-native. Works with ChatGPT, Claude, Cursor, and any MCP client.
- Why: compound agent memory/context fit, long-term memory, stars>=20

### qwwiwi/public-gbrain-agentos

- Verdict: **WATCH**
- Score: 18
- Stars: 13
- Raw: #848
- URL: https://github.com/qwwiwi/public-gbrain-agentos
- Description: Second Brain distribution: self-host shared agent memory (MCP + Postgres+pgvector) + inbox-agent + personal agent workspace generator. Apache 2.0.
- Why: agent memory, compound agent memory/context fit, second brain

### GiulioDER/RE-call

- Verdict: **WATCH**
- Score: 18
- Stars: 6
- Raw: #793
- URL: https://github.com/GiulioDER/RE-call
- Description: Memory that abstains instead of guessing: agent memory on your own Postgres with a verdict, confidence and provenance on every hit, and a calibrated refusal when nothing clears the threshold.
- Why: agent memory, compound agent memory/context fit


## Agent Reliability / Evals & Production

### evolving-foundry/ember-evaluator

- Verdict: **WATCH**
- Score: 18
- Stars: 27
- Raw: #917
- URL: https://github.com/evolving-foundry/ember-evaluator
- Description: Many ways to evaluate. One framework to bring them together. Unify benchmarks, agent evaluations, and performance testing across coding, terminal, office, web, and more.
- Why: agent evaluation, compound agent reliability/evals fit, stars>=20


## Agent Security / Governance

### aquasecurity/trivy

- Verdict: **WATCH**
- Score: 27
- Stars: 39063
- Raw: #1736
- URL: https://github.com/aquasecurity/trivy
- Description: Find vulnerabilities, misconfigurations, secrets, SBOM in containers, Kubernetes, code repositories, clouds and more
- Why: agent control-plane security fit, agent security/governance fit, stars>=1000, strong agent-security signal

### tailscale/tailscale

- Verdict: **WATCH**
- Score: 22
- Stars: 38712
- Raw: #1737
- URL: https://github.com/tailscale/tailscale
- Description: The easiest, most secure way to use WireGuard and 2FA.
- Why: agent security/governance fit, stars>=1000, strong agent-security signal

### horizon-ai-labs/agent-io-guards

- Verdict: **WATCH**
- Score: 22
- Stars: 6
- Raw: #492
- URL: https://github.com/horizon-ai-labs/agent-io-guards
- Description: Code for small open models that guard LLM apps: prompt-injection detection, PII redaction, groundedness (Apache-2.0)
- Why: agent security/governance fit, strong agent-security signal

### finic-ai/kairos

- Verdict: **WATCH**
- Score: 19
- Stars: 227
- Raw: #1786
- URL: https://github.com/finic-ai/kairos
- Description: Real time event intelligence, fraud and risk decisioning for financial behavior.
- Why: agent security/governance fit, stars>=100, strong agent-security signal


## Automation / Event Workflows

### OpenTodoApp/n8n-nodes-opentodo

- Verdict: **KEEP**
- Score: 36
- Stars: 0
- Raw: #671
- URL: https://github.com/OpenTodoApp/n8n-nodes-opentodo
- Description: n8n community nodes for OpenTodo, the self-hosted task manager: tasks, projects, labels, comments and a signed webhook trigger.
- Why: automation ops/tooling fit, automation reusable implementation, n8n, n8n identity fit, n8n node/plugin fit, trigger, webhook, workflow/event integration fit

### Funnelchat20/n8n-nodes-funnelchat

- Verdict: **WATCH**
- Score: 33
- Stars: 0
- Raw: #661
- URL: https://github.com/Funnelchat20/n8n-nodes-funnelchat
- Description: n8n community node for the Funnelchat public API (actions and webhook trigger)
- Why: automation ops/tooling fit, n8n, n8n identity fit, n8n node/plugin fit, trigger, webhook, workflow/event integration fit

### chat33-io/n8n-nodes-chat33

- Verdict: **WATCH**
- Score: 27
- Stars: 0
- Raw: #670
- URL: https://github.com/chat33-io/n8n-nodes-chat33
- Description: n8n community node for Chat33: publish to 8 social networks, answer Instagram and Facebook DMs, trigger workflows on new DMs and leads
- Why: automation reusable implementation, n8n, n8n identity fit, n8n node/plugin fit, trigger, workflow/event integration fit

### hookdeck/n8n-nodes-hookdeck

- Verdict: **WATCH**
- Score: 24
- Stars: 1
- Raw: #662
- URL: https://github.com/hookdeck/n8n-nodes-hookdeck
- Description: n8n community node for Hookdeck: trigger workflows from events delivered by the Hookdeck Event Gateway, and manage sources, destinations and connections.
- Why: n8n, n8n identity fit, n8n node/plugin fit, trigger, workflow/event integration fit

### zerogpu/n8n-nodes-zerogpu

- Verdict: **WATCH**
- Score: 22
- Stars: 0
- Raw: #665
- URL: https://github.com/zerogpu/n8n-nodes-zerogpu
- Description: Official ZeroGPU nodes for n8n. ZeroGPU is a compute-efficient inference provider for apps and agents — purpose-built small and nano language models on an edge network that run the repeatable tasks frontier models shouldn’t, ~10x faster and 50%+ cheaper. Auto-scaling, with zero GPU infrastructure. Plug in and you’re live.
- Why: automation reusable implementation, n8n, n8n identity fit, n8n node/plugin fit, workflow/event integration fit

### emilvrana/n8n-workflows

- Verdict: **WATCH**
- Score: 20
- Stars: 0
- Raw: #689
- URL: https://github.com/emilvrana/n8n-workflows
- Description: Practical n8n workflow templates: webhooks, health checks, AI-powered RSS digest
- Why: automation ops/tooling fit, n8n, n8n identity fit, webhook, workflow/event integration fit

### LeenJazmati/medplum-clinical-agent

- Verdict: **WATCH**
- Score: 19
- Stars: 1
- Raw: #716
- URL: https://github.com/LeenJazmati/medplum-clinical-agent
- Description: n8n AI agent that reads and writes FHIR data on Medplum for a hospital system: patients, coded clinical data, lab/imaging orders, scheduling
- Why: automation AI/MCP fit, automation ops/tooling fit, n8n, n8n identity fit, workflow/event integration fit

### slidecraft-in/n8n-nodes-presentations-ai

- Verdict: **WATCH**
- Score: 19
- Stars: 0
- Raw: #672
- URL: https://github.com/slidecraft-in/n8n-nodes-presentations-ai
- Description: Official n8n community node for Presentations.AI. Generate, transform and export AI-powered slide decks from a topic, raw text, or document (PDF/DOCX/PPTX) directly inside n8n workflows.
- Why: n8n, n8n identity fit, n8n node/plugin fit, workflow/event integration fit

### pgmaximo/S5_ProjetoIntegrador_UrbanAI

- Verdict: **WATCH**
- Score: 19
- Stars: 1
- Raw: #717
- URL: https://github.com/pgmaximo/S5_ProjetoIntegrador_UrbanAI
- Description: Conversational property search: Flutter + Firebase app where an n8n AI agent decides when to fetch real listings (SerpAPI) and recommends homes. Mauá integrated project · Busca de imóveis por conversa com IA.
- Why: automation AI/MCP fit, automation ops/tooling fit, n8n, n8n identity fit, workflow/event integration fit

### cihatcoban/otomasyon-all

- Verdict: **WATCH**
- Score: 19
- Stars: 0
- Raw: #684
- URL: https://github.com/cihatcoban/otomasyon-all
- Description: ⚡ 285+ Production-ready n8n workflows & AI agents (OpenAI, DeepSeek, Gemini, Claude). Docker-ready stack featuring RAG, CRM automation, GitOps backups, and AI security guardrails built with Keystone Framework.
- Why: automation AI/MCP fit, automation ops/tooling fit, n8n, n8n identity fit, workflow/event integration fit

### nluecke/grafana-n8n-datasource

- Verdict: **WATCH**
- Score: 18
- Stars: 0
- Raw: #654
- URL: https://github.com/nluecke/grafana-n8n-datasource
- Description: Grafana data source for n8n Cloud and self-hosted n8n via the n8n public API: executions, statistics, Insights, alerting, bundled dashboard
- Why: automation ops/tooling fit, automation reusable implementation, n8n, n8n identity fit, workflow/event integration fit


## Design Systems / Visual QA

### PuzzleomJade/pursr-rpocket

- Verdict: **WATCH**
- Score: 24
- Stars: 37
- Raw: #1418
- URL: https://github.com/PuzzleomJade/pursr-rpocket
- Description: Visual QA, browser automation, accessibility auditing, screenshot diffing, and MCP tooling for coding agents.
- Why: agent-native structured implementation, agent-native workflow, audit, screenshot diff, stars>=20


## Device Control / Capture

### zhoujun94511/WebAppFlaskscrcpy

- Verdict: **WATCH**
- Score: 18
- Stars: 6
- Raw: #972
- URL: https://github.com/zhoujun94511/WebAppFlaskscrcpy
- Description: 📱基于Scrcpy的Web安卓设备群控平台 - A browser-based Android device control platform powered by scrcpy, supporting real-time screen streaming, low-latency remote interaction, multi-device monitoring, and synchronized control of multiple Android devices from a single interface.
- Why: compound device control/capture fit, device control, scrcpy


## Document Parsing / Ingestion

### nampara-ai/librarian

- Verdict: **WATCH**
- Score: 18
- Stars: 49
- Raw: #1066
- URL: https://github.com/nampara-ai/librarian
- Description: Text corpus cleaner and organizer. Local-first document parsing/copyediting/indexing pipeline. Feed it transcripts, PDFs, DOCX, images, or scans. Librarian extracts the text, cleans it with an LLM to CMOS style and punctuation standards, files each document under a Dewey-style classification, and makes the whole collection full-text searchable.
- Why: compound document parsing/ingestion fit, stars>=20

### MartinsMessias/rasgapdf

- Verdict: **WATCH**
- Score: 18
- Stars: 14
- Raw: #1076
- URL: https://github.com/MartinsMessias/rasgapdf
- Description: Blazing-fast 2D Spatial PDF Parser in Pure Rust (Python, Node.js, Go, C#). Extract exact [x0, y0, x1, y1] bounding boxes, text blocks, tables, images & vector paths in ~3-8ms/page for RAG & LLMs.
- Why: compound document parsing/ingestion fit, ocr, pdf parser


## Full-Song AI / Suno Alternatives

### HanosThePlacid/yue2-studio

- Verdict: **WATCH**
- Score: 20
- Stars: 0
- Raw: #438
- URL: https://github.com/HanosThePlacid/yue2-studio
- Description: Local web studio for YuE2 song generation: lyrics + style prompt to a full song with vocals, on your own GPU via audio.cpp. Unofficial.
- Why: full-song identity fit, lyrics/vocals full-song fit


## Infographics / Visual Storytelling

### razorback16/cc-intelligent-ui

- Verdict: **WATCH**
- Score: 27
- Stars: 146
- Raw: #1811
- URL: https://github.com/razorback16/cc-intelligent-ui
- Description: Claude's answers, rendered: Markdown, math, charts and diagrams drawn in the Claude Code terminal. Independent project, not affiliated with Anthropic.
- Why: agent-native structured implementation, agent-native workflow, chart, diagram, stars>=100

### haydenschmitty/floorplan

- Verdict: **WATCH**
- Score: 26
- Stars: 3040
- Raw: #1779
- URL: https://github.com/haydenschmitty/floorplan
- Description: See how your app actually fits together. An interactive, plain-English map of your codebase, drawn by Claude or Codex.
- Why: agent-native workflow, diagram, map, stars>=1000


## Lancelot / Agent Infrastructure

### superwavvy/wall-a

- Verdict: **KEEP**
- Score: 35
- Stars: 1
- Raw: #642
- URL: https://github.com/superwavvy/wall-a
- Description: A runtime security gateway for AI agents that intercepts MCP tool calls, enforces deterministic policies, prevents prompt injection via session taint tracking, and requires human approval for high-risk actions.
- Why: lancelot high fit

### kbkb628/memex

- Verdict: **KEEP**
- Score: 35
- Stars: 0
- Raw: #568
- URL: https://github.com/kbkb628/memex
- Description: 一个人用的 agent，不该需要一台服务器。跑在 Cloudflare Durable Objects 上的个人 agent 骨架：发一条消息，页面可以立刻关掉，它做完了答案还在等你。
- Why: lancelot high fit

### kostia7alania/agent-stealth

- Verdict: **WATCH**
- Score: 18
- Stars: 0
- Raw: #612
- URL: https://github.com/kostia7alania/agent-stealth
- Description: AI Browser Agent Detector & Stealth Benchmark (Codex, Claude, Kimi, Playwright MCP, Chrome DevTools MCP, agent-browser, Browser-Use) + Installable Agent Skills
- Why: lancelot keep fit

### vercel-labs/agent-skills

- Verdict: **WATCH**
- Score: 18
- Stars: 33626
- Raw: #1739
- URL: https://github.com/vercel-labs/agent-skills
- Description: Vercel's official collection of agent skills
- Why: lancelot keep fit, stars>=1000

### Nasiko-Labs/nasiko

- Verdict: **WATCH**
- Score: 18
- Stars: 11857
- Raw: #1742
- URL: https://github.com/Nasiko-Labs/nasiko
- Description: The Open Runtime for AI Agents
- Why: lancelot keep fit, stars>=1000

### Orkas-AI/Orkas

- Verdict: **WATCH**
- Score: 18
- Stars: 9059
- Raw: #1728
- URL: https://github.com/Orkas-AI/Orkas
- Description: Orkas is an open-source (MIT), local-first AI team for your desktop: a Commander turns your goal into to-dos and coordinates 16 built-in specialist agents plus Claude Code, Codex, OpenCode, OpenClaw and Hermes, with projects, scheduled automations and connectors. Free app for macOS & Windows; built-in models or your own keys.
- Why: lancelot keep fit, stars>=1000

### agentgateway/agentgateway

- Verdict: **WATCH**
- Score: 18
- Stars: 5981
- Raw: #1745
- URL: https://github.com/agentgateway/agentgateway
- Description: Next Generation Agentic Proxy for AI Agents and MCP servers
- Why: lancelot keep fit, stars>=1000

### Ryder-Sun/Meldwork

- Verdict: **WATCH**
- Score: 18
- Stars: 1450
- Raw: #1807
- URL: https://github.com/Ryder-Sun/Meldwork
- Description: Local-first AI agent workspace for multi-agent collaboration, agent orchestration, scoped permissions, evidence-aware runs, and human-in-the-loop decisions.
- Why: lancelot keep fit, stars>=1000

### NiazMorshed2007/reanimate

- Verdict: **WATCH**
- Score: 18
- Stars: 1284
- Raw: #1792
- URL: https://github.com/NiazMorshed2007/reanimate
- Description: A Claude Code skill that reverse-engineers any animation frame by frame, then proves the copy moves the same.
- Why: lancelot keep fit, stars>=1000

### Moh4696/open-3d-skills

- Verdict: **WATCH**
- Score: 18
- Stars: 266
- Raw: #1794
- URL: https://github.com/Moh4696/open-3d-skills
- Description: Eight agent skills for 3D and animated websites: three.js scenes from code, scroll films, transparent video, cursor rigs, exploded views, AI motion assets, browser checks and 60 fps recording. Claude Code, Codex, Cursor, Gemini CLI.
- Why: lancelot keep fit, stars>=100

### Attentionform/astra

- Verdict: **WATCH**
- Score: 18
- Stars: 0
- Raw: #597
- URL: https://github.com/Attentionform/astra
- Description: Word (.docx) engine for AI agents: MCP server, command-line tool and TypeScript library.
- Why: lancelot keep fit

### furkankoykiran/furkankoykiran

- Verdict: **WATCH**
- Score: 18
- Stars: 0
- Raw: #596
- URL: https://github.com/furkankoykiran/furkankoykiran
- Description: GitHub profile README of Furkan Köykıran: Python and TypeScript developer building MCP servers, AI agent tooling and trading automation. Recent activity is refreshed daily by a GitHub Actions workflow.
- Why: lancelot keep fit
- Caution: portfolio, trading

### kostia7alania/agent-tells

- Verdict: **WATCH**
- Score: 18
- Stars: 0
- Raw: #611
- URL: https://github.com/kostia7alania/agent-tells
- Description: Local-only AI browser agent and automation detector. Explainable browser fingerprints, behavioral tests, MCP/Playwright diagnostics, no uploads.
- Why: lancelot keep fit


## Mixing / Mastering / Audio Engineering

### tomderham/curve

- Verdict: **WATCH**
- Score: 20
- Stars: 26
- Raw: #240
- URL: https://github.com/tomderham/curve
- Description: Menu bar macOS app that hosts audio plugins
- Why: audio plugin, mixing/mastering/audio engineering fit, stars>=20, vst


## OSINT / Investigations

### AlanBacker/audio-flyover-geolocation

- Verdict: **WATCH**
- Score: 18
- Stars: 6
- Raw: #1632
- URL: https://github.com/AlanBacker/audio-flyover-geolocation
- Description: Locate where a recording was made from the Doppler curves of aircraft in its background, matched against ADS-B history. Agent skill + tested Python pipeline, English / 简体中文.
- Why: forensics, geolocation, osint/investigations fit


## Reverse Engineering / Binary Analysis

### Issue421/leica-m10-toolkit

- Verdict: **WATCH**
- Score: 18
- Stars: 6
- Raw: #1183
- URL: https://github.com/Issue421/leica-m10-toolkit
- Description: Read-only Leica M10 firmware analysis toolkit: package codec, offline inspector, XPan crop math, ASC/WB recipes. No firmware writer, no flashing.
- Why: compound reverse engineering fit, firmware analysis


## Speech / TTS & Voice

### KoljaB/RealtimeTTS

- Verdict: **WATCH**
- Score: 23
- Stars: 4051
- Raw: #979
- URL: https://github.com/KoljaB/RealtimeTTS
- Description: Converts text to speech in realtime
- Why: stars>=1000, text to speech, text-to-speech, tts

### bdim404/Qwen3-TTS-WebUI

- Verdict: **WATCH**
- Score: 22
- Stars: 36
- Raw: #1038
- URL: https://github.com/bdim404/Qwen3-TTS-WebUI
- Description: 基于阿里巴巴 Qwen3-TTS 模型（17 亿参数）的全栈文本转语音 Web 应用，支持语音定制、语音设计和语音克隆，有声书生成功能。A text-to-speech web application based on Qwen3-TTS, supporting custom voice, voice design, voice cloning, and audiobook generation..
- Why: stars>=20, text-to-speech, tts, voice cloning, voice design


## System Architecture / Engineering Patterns

### oskardudycz/EventSourcing.NetCore

- Verdict: **WATCH**
- Score: 31
- Stars: 3685
- Raw: #1481
- URL: https://github.com/oskardudycz/EventSourcing.NetCore
- Description: Examples and Tutorials of Event Sourcing in .NET
- Why: cqrs, event sourcing, high-value architecture pattern, stars>=1000, system architecture / engineering patterns fit


## Video Production / Editing

### Vincentwei1021/video-shotcraft

- Verdict: **WATCH**
- Score: 21
- Stars: 17400
- Raw: #1741
- URL: https://github.com/Vincentwei1021/video-shotcraft
- Description: AI video skill for Claude Code & Codex — cinematic, editable product promos with Remotion: 124 shot recipe cards, 150 motion previews, beat sync, sound design, Motion Workbench & JianYing (CapCut CN) export.
- Why: agent-native workflow, stars>=1000, video

### 0xS4N4TG/papercut-explainer

- Verdict: **WATCH**
- Score: 18
- Stars: 152
- Raw: #1758
- URL: https://github.com/0xS4N4TG/papercut-explainer
- Description: Short vertical cut-paper explainer reels, made by your coding agent. Nine Agent Skills plus a Remotion library. Works with Claude Code, OpenCode, Codex, Gemini CLI, Cursor, Copilot and more.
- Why: agent-native workflow, stars>=100, video
