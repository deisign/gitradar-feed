---
title: Creative Radar Shortlist 2026-10-29
date: 2026-10-29
status: shortlist
tags:
  - radar
  - creative-radar
  - shortlist
---

# Creative Radar Shortlist — 2026-10-29

Source: [[../scored/2026-10-29|Scored 2026-10-29]]

## Навигация

- [Agent Memory / Context](#agent-memory-context) — 6
- [Agent Security / Governance](#agent-security-governance) — 1
- [Automation / Event Workflows](#automation-event-workflows) — 11
- [Lancelot / Agent Infrastructure](#lancelot-agent-infrastructure) — 5
- [Mixing / Mastering / Audio Engineering](#mixing-mastering-audio-engineering) — 1
- [Newsroom / Data Journalism](#newsroom-data-journalism) — 1
- [Reverse Engineering / Binary Analysis](#reverse-engineering-binary-analysis) — 4
- [Search / Retrieval Engineering](#search-retrieval-engineering) — 3
- [Speech / TTS & Voice](#speech-tts-&-voice) — 4
- [System Architecture / Engineering Patterns](#system-architecture-engineering-patterns) — 1
- [Web Data / Crawling & Extraction](#web-data-crawling-&-extraction) — 1

## Agent Memory / Context

### cluster1900/apexo-code

- Verdict: **WATCH**
- Score: 18
- Stars: 74
- Raw: #804
- URL: https://github.com/cluster1900/apexo-code
- Description: Apexo: An open-source, general-purpose coding agent for terminal (TUI), web, and desktop with autonomous goals, workflows, persistent memory, command sandboxing, and first-class support for Gemini, Grok, and OpenAI-compatible models.
- Why: compound agent memory/context fit, persistent memory, stars>=20

### inite-ai/inite-brain-service

- Verdict: **WATCH**
- Score: 18
- Stars: 43
- Raw: #796
- URL: https://github.com/inite-ai/inite-brain-service
- Description: Open-source bitemporal knowledge graph — long-term memory for AI agents. Hybrid retrieval, conflict-aware ingest, GDPR forget. REST + native MCP.
- Why: compound agent memory/context fit, long-term memory, stars>=20

### maximem-ai/memory_and_context_eval_harness

- Verdict: **WATCH**
- Score: 18
- Stars: 12
- Raw: #788
- URL: https://github.com/maximem-ai/memory_and_context_eval_harness
- Description: Open evaluation harness for AI agent memory systems. Runs LongMemEval and LoCoMo against Synap, Mem0, Zep and Supermemory with pluggable provider adapters. Synap: 95.6% LongMemEval (gemini-3.8-flash), 98.1% Recall@20, 93.2% LoCoMo (gpt-5-mini).
- Why: agent memory, compound agent memory/context fit

### oceanbase/powercontext

- Verdict: **WATCH**
- Score: 18
- Stars: 1394
- Raw: #793
- URL: https://github.com/oceanbase/powercontext
- Description: Self-evolving long-term memory for Claude Code, Codex, and other AI agents. Pick up where another agent left off.
- Why: compound agent memory/context fit, long-term memory, stars>=1000

### jlrickert/tapper

- Verdict: **WATCH**
- Score: 18
- Stars: 6
- Raw: #784
- URL: https://github.com/jlrickert/tapper
- Description: CLI for cross-domain personal knowledge and agent memory, with linked notes and structured metadata.
- Why: agent memory, compound agent memory/context fit

### GeekFamilyCorp/TricorderKit

- Verdict: **WATCH**
- Score: 18
- Stars: 32
- Raw: #841
- URL: https://github.com/GeekFamilyCorp/TricorderKit
- Description: The local-first second brain for your AI agents - measured, self-improving, and gated so it can't leak what you keep private. 13 Claude Code plugins, 21 skills, Ollama, Neo4j, Qdrant.
- Why: compound agent memory/context fit, second brain, stars>=20


## Agent Security / Governance

### vasikmansuri/agentconfig-doctor

- Verdict: **WATCH**
- Score: 33
- Stars: 13
- Raw: #492
- URL: https://github.com/vasikmansuri/agentconfig-doctor
- Description: MCP security scanner & config linter for AI coding agents. Finds leaked secrets, risky commands, broad permissions and invalid MCP servers in Claude Code, Cursor and VS Code (Copilot) configs. Local-first CLI, no telemetry.
- Why: agent control-plane security fit, agent security/governance fit, strong agent-security signal


## Automation / Event Workflows

### yuniruyuni/n8n-nodes-discord

- Verdict: **WATCH**
- Score: 33
- Stars: 0
- Raw: #654
- URL: https://github.com/yuniruyuni/n8n-nodes-discord
- Description: n8n node for Discord API integration. Supports Discord REST operations, webhooks, interactions, and Gateway triggers.
- Why: automation ops/tooling fit, n8n, n8n identity fit, n8n node/plugin fit, trigger, webhook, workflow/event integration fit

### yuniruyuni/n8n-nodes-twitch

- Verdict: **WATCH**
- Score: 24
- Stars: 2
- Raw: #646
- URL: https://github.com/yuniruyuni/n8n-nodes-twitch
- Description: yet another n8n-nodes-twitch with comprehensive event-sub trigger supports
- Why: n8n, n8n identity fit, n8n node/plugin fit, trigger, workflow/event integration fit

### shaggyistaken/n8n-nodes-superbotai

- Verdict: **WATCH**
- Score: 24
- Stars: 0
- Raw: #659
- URL: https://github.com/shaggyistaken/n8n-nodes-superbotai
- Description: n8n community nodes for SuperBot AI (AI customer-support chatbot): lead, conversation and escalation triggers; create leads and add training answers.
- Why: n8n, n8n identity fit, n8n node/plugin fit, trigger, workflow/event integration fit

### agentsearchhq-coder/n8n-nodes-agentsearch

- Verdict: **WATCH**
- Score: 23
- Stars: 0
- Raw: #667
- URL: https://github.com/agentsearchhq-coder/n8n-nodes-agentsearch
- Description: n8n community node: free live web search for workflows and AI agents
- Why: automation AI/MCP fit, n8n, n8n identity fit, n8n node/plugin fit, workflow/event integration fit

### MervinPraison/n8n-nodes-praisonai

- Verdict: **WATCH**
- Score: 23
- Stars: 0
- Raw: #661
- URL: https://github.com/MervinPraison/n8n-nodes-praisonai
- Description: n8n community node for PraisonAI - Run AI agents with PraisonAI
- Why: automation AI/MCP fit, n8n, n8n identity fit, n8n node/plugin fit, workflow/event integration fit

### jonorl/agentic-ai-news-to-image

- Verdict: **WATCH**
- Score: 22
- Stars: 0
- Raw: #709
- URL: https://github.com/jonorl/agentic-ai-news-to-image
- Description: n8n AI agent that picks the day’s top headline and turns it into an image, with a React site, an Android app and an Express API.
- Why: automation AI/MCP fit, automation ops/tooling fit, automation reusable implementation, n8n, n8n identity fit, workflow/event integration fit

### kabxxr7-jpg/opsflow

- Verdict: **WATCH**
- Score: 21
- Stars: 0
- Raw: #679
- URL: https://github.com/kabxxr7-jpg/opsflow
- Description: Field-service ops automation + AI reporting: trigger/filter/action engine, Gemini classification with grounding checks, signed webhooks, a real n8n workflow, OCR intake
- Why: n8n, n8n identity fit, trigger, webhook, workflow/event integration fit

### invoapi/n8n-nodes-invoapi

- Verdict: **WATCH**
- Score: 20
- Stars: 0
- Raw: #662
- URL: https://github.com/invoapi/n8n-nodes-invoapi
- Description: n8n community node for invoapi.de – generate, validate, parse and convert e-invoices (XRechnung, ZUGFeRD, EN 16931, Peppol)
- Why: automation ops/tooling fit, automation reusable implementation, n8n, n8n identity fit, n8n node/plugin fit

### appu1029-spec/SE-AI-B12-1-W4-D1-n8n-gmail-summariser

- Verdict: **WATCH**
- Score: 20
- Stars: 0
- Raw: #707
- URL: https://github.com/appu1029-spec/SE-AI-B12-1-W4-D1-n8n-gmail-summariser
- Description: n8n AI Agent workflow that fetches my latest 5 unread Gmail emails, summarises each in one line using an OpenAI chat model, and emails all five summaries back to me as one message. Nodes: Manual Trigger, Gmail (Get Many, Unread, Limit 5), AI Agent + OpenAI Chat Model, Aggregate, Gmail (Send). Hi everyone, I have successfully completed the project
- Why: automation AI/MCP fit, n8n, n8n identity fit, trigger, workflow/event integration fit

### turbo-notify/n8n-nodes-turbo-notify

- Verdict: **WATCH**
- Score: 19
- Stars: 0
- Raw: #664
- URL: https://github.com/turbo-notify/n8n-nodes-turbo-notify
- Description: n8n community node for Turbo Notify: send and receive WhatsApp messages from your n8n workflows.
- Why: n8n, n8n identity fit, n8n node/plugin fit, workflow/event integration fit

### subnoto/n8n-nodes-subnoto

- Verdict: **WATCH**
- Score: 19
- Stars: 2
- Raw: #695
- URL: https://github.com/subnoto/n8n-nodes-subnoto
- Description: N8N integration for Subnoto electronic signature, automate document, recipients, blocks and signatures
- Why: n8n, n8n identity fit, n8n node/plugin fit, workflow/event integration fit


## Lancelot / Agent Infrastructure

### CartagoGit/DelendAI

- Verdict: **WATCH**
- Score: 18
- Stars: 1
- Raw: #585
- URL: https://github.com/CartagoGit/DelendAI
- Description: Extensible MCP server core and CLI plugin tooling.
- Why: lancelot keep fit

### Everloot/everloot

- Verdict: **WATCH**
- Score: 18
- Stars: 0
- Raw: #591
- URL: https://github.com/Everloot/everloot
- Description: Player-built database and tools for WoW: Forever: the in-game addon, everloot.app, the desktop app and the MCP server. AGPL-3.0 code, CC BY-SA 4.0 data.
- Why: lancelot keep fit
- Caution: game

### kenmwara/securing-ai-agents-ad

- Verdict: **WATCH**
- Score: 18
- Stars: 0
- Raw: #633
- URL: https://github.com/kenmwara/securing-ai-agents-ad
- Description: Securing an AI agent in Active Directory: a real MCP toolset for a live AD domain, attacked with prompt injection and tool misuse to find which control contains it: AD delegation, human approval, or detection on the DC.
- Why: lancelot keep fit

### sheepk95/The-Cartographer

- Verdict: **WATCH**
- Score: 18
- Stars: 0
- Raw: #573
- URL: https://github.com/sheepk95/The-Cartographer
- Description: Ask which agent skills fit a task before you start it. One model call reads your task against the whole SKILL.md catalogue (193 skills bundled, plus yours) and names the few worth reading. CLI and MCP server for Claude Code, Codex, the Anthropic API or a local model. Python, standard library only.
- Why: lancelot keep fit

### KyuuKyuuStone/UEMCP-OpenSource

- Verdict: **WATCH**
- Score: 18
- Stars: 1
- Raw: #590
- URL: https://github.com/KyuuKyuuStone/UEMCP-OpenSource
- Description: Client-agnostic MCP server for Unreal Engine 5.4 & 5.7 editor automation: a pure-Python editor plugin (no C++ build) exposing 10 audited tools over Streamable HTTP, SSE or stdio. Loopback-only, token-rotated, dual permission gates. MIT.
- Why: lancelot keep fit
- Caution: game


## Mixing / Mastering / Audio Engineering

### vvvv/VL.Audio.VST

- Verdict: **WATCH**
- Score: 18
- Stars: 9
- Raw: #247
- URL: https://github.com/vvvv/VL.Audio.VST
- Description: VST3 audio plugin support for vvvv
- Why: audio plugin, mixing/mastering/audio engineering fit, vst


## Newsroom / Data Journalism

### biglocalnews/bln-python-client

- Verdict: **WATCH**
- Score: 20
- Stars: 7
- Raw: #1664
- URL: https://github.com/biglocalnews/bln-python-client
- Description: Python client for the biglocalnews.org API
- Why: biglocalnews, journalism, newsroom fit


## Reverse Engineering / Binary Analysis

### kth-step/HolBA

- Verdict: **WATCH**
- Score: 18
- Stars: 47
- Raw: #1154
- URL: https://github.com/kth-step/HolBA
- Description: Binary analysis in HOL
- Why: binary analysis, compound reverse engineering fit, stars>=20

### St0rn/SigLens

- Verdict: **WATCH**
- Score: 18
- Stars: 44
- Raw: #1151
- URL: https://github.com/St0rn/SigLens
- Description: SigLens is a Windows binary analysis tool designed to pinpoint the exact regions responsible for antivirus detections. It narrows detections down to precise offsets and maps them to PE sections, RVA, VA, hexdump, and nearby strings, making evasion faster and easier. Built for fast AV signature triage on Windows
- Why: binary analysis, compound reverse engineering fit, stars>=20

### sebastianspicker/tiz0wn

- Verdict: **WATCH**
- Score: 18
- Stars: 10
- Raw: #1170
- URL: https://github.com/sebastianspicker/tiz0wn
- Description: Evidence-first Samsung Tizen TV security research: reversible debloating, firmware analysis, validated Remote PC/CIFS UID-0 injection, and hardening.
- Why: compound reverse engineering fit, firmware analysis

### BadChemical/IoT-Vulnerability-Research-Public

- Verdict: **WATCH**
- Score: 18
- Stars: 17
- Raw: #1169
- URL: https://github.com/BadChemical/IoT-Vulnerability-Research-Public
- Description: Independent IoT security research, vulnerability disclosures, and PoCs focusing on firmware analysis, hardware interfaces, and cryptographic flaws.
- Why: compound reverse engineering fit, firmware analysis


## Search / Retrieval Engineering

### blue-idea/linkit

- Verdict: **WATCH**
- Score: 18
- Stars: 107
- Raw: #858
- URL: https://github.com/blue-idea/linkit
- Description: AI bookmark manager for desktop — local-first, offline, read-it-later and PKM tool with AI summaries, semantic search, knowledge graph, and free self-hosted sync. 100% free, no paywalls, no ads.
- Why: compound search/retrieval fit, semantic search, stars>=100

### yjid/kensaku

- Verdict: **WATCH**
- Score: 18
- Stars: 70
- Raw: #854
- URL: https://github.com/yjid/kensaku
- Description: Search inside documents, code, and even screenshots - instantly and locally. A free, open-source file launcher with OCR, semantic search, and MCP agent access.
- Why: compound search/retrieval fit, semantic search, stars>=20

### 00200200/ollama-rag-reranker

- Verdict: **WATCH**
- Score: 18
- Stars: 13
- Raw: #889
- URL: https://github.com/00200200/ollama-rag-reranker
- Description: Interactive CLI for Retrieval-Augmented Generation (RAG) with ranking — uses Ollama embeddings + HNSW vector DB + optional reranker for more accurate results
- Why: compound search/retrieval fit, reranker


## Speech / TTS & Voice

### abusuraihsakhri/qwen3-tts-local

- Verdict: **WATCH**
- Score: 20
- Stars: 14
- Raw: #982
- URL: https://github.com/abusuraihsakhri/qwen3-tts-local
- Description: A lightweight, local Python wrapper for Qwen3-TTS (1.7B) using Gradio. Run high-quality voice cloning and text-to-speech generation directly on your NVIDIA GPU.
- Why: compound deployable speech/TTS fit, speech generation, text-to-speech, tts, voice cloning

### abbccdd/dsh-localtts

- Verdict: **WATCH**
- Score: 18
- Stars: 9
- Raw: #983
- URL: https://github.com/abbccdd/dsh-localtts
- Description: Local TTS speech synthesis and playback for DeepSeek Harness.
- Why: compound deployable speech/TTS fit, speech synthesis, text-to-speech, tts

### hgneng/ekho

- Verdict: **WATCH**
- Score: 18
- Stars: 1217
- Raw: #973
- URL: https://github.com/hgneng/ekho
- Description: Chinese text-to-speech engine
- Why: compound deployable speech/TTS fit, stars>=1000, text-to-speech, tts

### 3265807971-cloud/voice-design-prompt-guide

- Verdict: **WATCH**
- Score: 18
- Stars: 8
- Raw: #1029
- URL: https://github.com/3265807971-cloud/voice-design-prompt-guide
- Description: 中文 ElevenLabs Voice Design 提示词教程：格式模板、中英词表、常见坑，以及换模型后声音变年轻/变高的六步排查
- Why: compound deployable speech/TTS fit, text-to-speech, tts, voice design


## System Architecture / Engineering Patterns

### PrestaShop/ADR

- Verdict: **WATCH**
- Score: 18
- Stars: 10
- Raw: #1478
- URL: https://github.com/PrestaShop/ADR
- Description: Architecture Decision Records for the PrestaShop project
- Why: architecture decision record, high-value architecture pattern, system architecture / engineering patterns fit


## Web Data / Crawling & Extraction

### tylergibbs1/feedstock

- Verdict: **WATCH**
- Score: 18
- Stars: 15
- Raw: #1040
- URL: https://github.com/tylergibbs1/feedstock
- Description: High-performance web crawler and scraper for TypeScript, powered by Bun and Playwright
- Why: compound web crawling/extraction fit, web crawler
- Caution: stock
