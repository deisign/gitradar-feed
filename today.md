---
title: Creative Radar Shortlist 2026-10-15
date: 2026-10-15
status: shortlist
tags:
  - radar
  - creative-radar
  - shortlist
---

# Creative Radar Shortlist — 2026-10-15

Source: [[../scored/2026-10-15|Scored 2026-10-15]]

## Навигация

- [Agent Security / Governance](#agent-security-governance) — 1
- [Lancelot / Agent Infrastructure](#lancelot-agent-infrastructure) — 11
- [Media / Social Monitoring](#media-social-monitoring) — 1
- [n8n / Workflow Automation](#n8n-workflow-automation) — 2
- [Newsroom / Source Security](#newsroom-source-security) — 1
- [System Architecture / Engineering Patterns](#system-architecture-engineering-patterns) — 1

## Agent Security / Governance

### AgentLatch/agent-latch

- Verdict: **WATCH**
- Score: 33
- Stars: 6
- Raw: #442
- URL: https://github.com/AgentLatch/agent-latch
- Description: Local-first AI agent security scanner. Finds prompt injection, over-privileged tools, and secrets in agent code, manifests, and prompts. CLI, pre-commit, GitHub Action, SARIF
- Why: agent control-plane security fit, agent security/governance fit, strong agent-security signal


## Lancelot / Agent Infrastructure

### abpandey-dev/agent-memory-engine

- Verdict: **KEEP**
- Score: 35
- Stars: 0
- Raw: #571
- URL: https://github.com/abpandey-dev/agent-memory-engine
- Description: Long-term memory for AI agents: Claude extracts facts, decides add/update/skip with history, hybrid graph + keyword recall, MCP server, and a benchmark (100% at 9x fewer tokens than full history).
- Why: lancelot high fit

### delltrak/wamcp

- Verdict: **WATCH**
- Score: 18
- Stars: 24
- Raw: #553
- URL: https://github.com/delltrak/wamcp
- Description: WhatsApp MCP Server — Connect AI agents to WhatsApp via Model Context Protocol. 61 tools, 10 resources, 12 real-time events. Supports Baileys (WhatsApp Web) and Cloud API. Built with TypeScript, BullMQ, and Docker.
- Why: lancelot keep fit, stars>=20

### mokahq/mokalabs

- Verdict: **WATCH**
- Score: 18
- Stars: 7
- Raw: #559
- URL: https://github.com/mokahq/mokalabs
- Description: See every MCP message. Chat with any LLM and MCP server, compare models, call tools, and see what your AI editor (Copilot, Cursor, Claude, Gemini) sends to your MCP servers. 100% local.
- Why: lancelot keep fit

### masakaai/rea-captcha

- Verdict: **WATCH**
- Score: 18
- Stars: 1
- Raw: #576
- URL: https://github.com/masakaai/rea-captcha
- Description: Local MCP and SDK for browser-agent verification flows: provider test keys, owned image/text, and same-session resume.
- Why: lancelot keep fit

### animalaidunlimited/virtuous-ts-mcp

- Verdict: **WATCH**
- Score: 18
- Stars: 0
- Raw: #554
- URL: https://github.com/animalaidunlimited/virtuous-ts-mcp
- Description: MCP server for Virtuous CRM+, built in TypeScript on virtuous-ts. Read tools for contacts, gifts and journeys, with confirm-gated writes and rate-limit-aware paging.
- Why: lancelot keep fit

### bensantamaria-boop/signal-tpm-command-center

- Verdict: **WATCH**
- Score: 18
- Stars: 0
- Raw: #513
- URL: https://github.com/bensantamaria-boop/signal-tpm-command-center
- Description: AI-powered technical program management copilot built with Cloudflare Agents, Workers AI, Durable Objects, chat, and voice input.
- Why: lancelot keep fit

### CharlieCardenasToledo/mcp-canvas-server

- Verdict: **WATCH**
- Score: 18
- Stars: 0
- Raw: #558
- URL: https://github.com/CharlieCardenasToledo/mcp-canvas-server
- Description: MCP server for Canvas LMS — lets AI assistants manage courses, grades, quizzes, and more via natural language. 51 tools for teachers.
- Why: lancelot keep fit

### browser-use/browser-use

- Verdict: **WATCH**
- Score: 18
- Stars: 118014
- Raw: #577
- URL: https://github.com/browser-use/browser-use
- Description: Open-source Python library for AI browser agents, plus Browser Use Cloud: stealth browsers and a hosted agent API.
- Why: lancelot keep fit, stars>=1000

### Aryavvij/nullify

- Verdict: **WATCH**
- Score: 18
- Stars: 0
- Raw: #580
- URL: https://github.com/Aryavvij/nullify
- Description: Stops click hijacking for AI browser agents and for people: invisible overlays, unwanted pop-ups and redirects, hidden instructions.
- Why: lancelot keep fit

### Sohail-5678/forward-deploy-os

- Verdict: **WATCH**
- Score: 18
- Stars: 0
- Raw: #579
- URL: https://github.com/Sohail-5678/forward-deploy-os
- Description: Self-healing ETL and legacy-portal browser agent with signed human checkpoints, hash-chained audit and seeded benchmarks. Runs at $0. All data synthetic.
- Why: lancelot keep fit

### Truta446/agent-permission-kit

- Verdict: **WATCH**
- Score: 18
- Stars: 0
- Raw: #561
- URL: https://github.com/Truta446/agent-permission-kit
- Description: Give your AI agents permissions, not unlimited access. Allow, deny, or require human approval for every tool call — typed, in-process, fail-closed. MCP adapter included.
- Why: lancelot keep fit


## Media / Social Monitoring

### abewartech/socialmediamonitoring

- Verdict: **WATCH**
- Score: 22
- Stars: 6
- Raw: #312
- URL: https://github.com/abewartech/socialmediamonitoring
- Description: Social Media Monitoring
- Why: media monitoring, media source + observation fit, monitoring exact-phrase fit, social media monitoring


## n8n / Workflow Automation

### Xquik-dev/n8n-nodes-xquik

- Verdict: **WATCH**
- Score: 21
- Stars: 1
- Raw: #634
- URL: https://github.com/Xquik-dev/n8n-nodes-xquik
- Description: n8n community node for Twitter search, user lookup, trends & follow checks through Xquik. Not affiliated with X Corp.
- Why: n8n identity fit, n8n node/plugin fit, n8n ops/tooling fit, n8n reusable implementation, n8n workflow/integration fit

### quitegoodproject/n8n-nodes-tokenmarkdown

- Verdict: **WATCH**
- Score: 19
- Stars: 0
- Raw: #632
- URL: https://github.com/quitegoodproject/n8n-nodes-tokenmarkdown
- Description: Official n8n Community Node for TokenMarkdown. Converts any URL into clean, LLM-ready Markdown in <150ms, cutting 90%+ prompt token bloat inside n8n AI Agent workflows.
- Why: n8n AI/MCP fit, n8n identity fit, n8n node/plugin fit, n8n ops/tooling fit, n8n reusable implementation


## Newsroom / Source Security

### freedomofpress/securedrop-workstation

- Verdict: **WATCH**
- Score: 20
- Stars: 185
- Raw: #1119
- URL: https://github.com/freedomofpress/securedrop-workstation
- Description: Qubes-based SecureDrop Journalist Workstation environment for submission handling
- Why: securedrop, source security fit, stars>=100


## System Architecture / Engineering Patterns

### thenativeweb/architecturekit-golang

- Verdict: **WATCH**
- Score: 23
- Stars: 7
- Raw: #937
- URL: https://github.com/thenativeweb/architecturekit-golang
- Description: Building blocks for DDD-based applications with CQRS and event sourcing, in Go, on top of the EventSourcingDB.
- Why: cqrs, event sourcing, high-value architecture pattern, system architecture / engineering patterns fit
