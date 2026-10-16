---
title: Creative Radar Shortlist 2026-10-16
date: 2026-10-16
status: shortlist
tags:
  - radar
  - creative-radar
  - shortlist
---

# Creative Radar Shortlist — 2026-10-16

Source: [[../scored/2026-10-16|Scored 2026-10-16]]

## Навигация

- [Agent Security / Governance](#agent-security-governance) — 2
- [Design / Image Editing](#design-image-editing) — 9
- [Lancelot / Agent Infrastructure](#lancelot-agent-infrastructure) — 7
- [Mixing / Mastering / Audio Engineering](#mixing-mastering-audio-engineering) — 1
- [Radio / Audio Ops](#radio-audio-ops) — 13
- [Video Production / Editing](#video-production-editing) — 1

## Agent Security / Governance

### pipelab-org/pipelock

- Verdict: **KEEP**
- Score: 35
- Stars: 930
- Raw: #486
- URL: https://github.com/pipelab-org/pipelock
- Description: Open-source AI agent firewall for MCP security and agent egress. Scans mediated HTTP, MCP, A2A, and WebSocket traffic for exfiltration, SSRF, and prompt injection, and emits mediator-signed action receipts: verifiable audit evidence from outside the agent.
- Why: agent security/governance fit, stars>=100, strong agent-security signal

### Hannay001/lockkeeper

- Verdict: **WATCH**
- Score: 22
- Stars: 16
- Raw: #487
- URL: https://github.com/Hannay001/lockkeeper
- Description: Skill router and prompt-injection firewall for AI coding agents: gives Claude Code, Codex and Cursor the few skills, MCP servers and tools each task needs.
- Why: agent security/governance fit, strong agent-security signal


## Design / Image Editing

### igorski/bitmappery

- Verdict: **KEEP**
- Score: 35
- Stars: 347
- Raw: #900
- URL: https://github.com/igorski/bitmappery
- Description: Browser based non-destructive image editor with layering, masking, animation timeline, spritesheet editor, customizable brushes and cloud storage integration for all your online editing.
- Why: brush, image editing fit, image editor, non-destructive, photoshop, stars>=100

### CyberTimon/RapidRAW

- Verdict: **WATCH**
- Score: 33
- Stars: 10527
- Raw: #890
- URL: https://github.com/CyberTimon/RapidRAW
- Description: A beautiful, non-destructive, and GPU-accelerated RAW image editor built with performance in mind.
- Why: image editing fit, image editor, non-destructive, stars>=1000, tauri

### vomitselfie/NekoPhoto

- Verdict: **WATCH**
- Score: 30
- Stars: 8
- Raw: #887
- URL: https://github.com/vomitselfie/NekoPhoto
- Description: NekoPhoto, An Open-source image editor with PSD interoperability, Photoshop/Clip Studio/Procreate brush support, native vectors, smart selections and more.
- Why: brush, image editing fit, image editor, non-destructive, photoshop

### storytold/lightcraft

- Verdict: **WATCH**
- Score: 28
- Stars: 13021
- Raw: #882
- URL: https://github.com/storytold/lightcraft
- Description: LightCraft: An open-source non-destructive photo editor written by scratch in pure Rust
- Why: image editing fit, non-destructive, photo editor, stars>=1000

### visorcraft/Arte-Ogre

- Verdict: **WATCH**
- Score: 25
- Stars: 10
- Raw: #901
- URL: https://github.com/visorcraft/Arte-Ogre
- Description: A Rust-native, GPU-accelerated layered image editor for Linux. Paint, composite, select, and cut out with layers that keep their exact position; backed by a sparse tiled copy-on-write engine, 32-bit linear-light compositing on wgpu + egui, non-destructive vector layers, sandboxed plugins, and a no-telemetry offline core.
- Why: image editing fit, image editor, layers, non-destructive

### lucky-bai/paintlet

- Verdict: **WATCH**
- Score: 20
- Stars: 10
- Raw: #897
- URL: https://github.com/lucky-bai/paintlet
- Description: A small MS Paint-style raster image editor for macOS. Inspired by Windows 11 Paint's layout and features, built with Tauri, React, and TypeScript.
- Why: image editing fit, image editor, tauri

### gpex-cloud/opengpex

- Verdict: **WATCH**
- Score: 20
- Stars: 8
- Raw: #903
- URL: https://github.com/gpex-cloud/opengpex
- Description: open-source, browser-native image editor that combines traditional layer-based editing with ComfyUI integration and AI tooling.
- Why: image editing fit, image editor, layer-based

### hety0211/lumen-raw

- Verdict: **WATCH**
- Score: 20
- Stars: 113
- Raw: #886
- URL: https://github.com/hety0211/lumen-raw
- Description: 开源多品牌 RAW 照片编辑器，集调色、AI 增强、智能蒙版与照片合成于一体。 / An open-source multi-brand RAW photo editor with color grading, AI enhancement, smart masks, and photo merging.
- Why: image editing fit, photo editor, stars>=100

### Ehtasham-Arif01/PixelSpark

- Verdict: **WATCH**
- Score: 20
- Stars: 8
- Raw: #902
- URL: https://github.com/Ehtasham-Arif01/PixelSpark
- Description: PixelSpark is a professional AI photo editor for Android that enhances low-light images using MIRNet TFLite 100% offline, no cloud required. Built with Flutter and a high-performance C++ core via dart:ffi, it delivers 21+ pro editing tools, non-destructive workflow, and a smooth white/sky-blue UI. Features: AI Enhancement
- Why: image editing fit, non-destructive, photo editor


## Lancelot / Agent Infrastructure

### FCortezSecurity/mcp-security-lab

- Verdict: **KEEP**
- Score: 35
- Stars: 0
- Raw: #642
- URL: https://github.com/FCortezSecurity/mcp-security-lab
- Description: Local lab for attacking and defending an LLM agent that uses MCP tools: prompt injection, tool poisoning, and defenses, with measured security and utility results.
- Why: lancelot high fit

### Gowthaman90/mcp-bastion

- Verdict: **WATCH**
- Score: 18
- Stars: 7
- Raw: #588
- URL: https://github.com/Gowthaman90/mcp-bastion
- Description: Reliability & security proxy for the Model Context Protocol (MCP). Self-healing connections, runtime tool-poisoning/shadowing defense, and NIST AI RMF + OWASP LLM Top-10 audit trails for any MCP server. Works with Claude, Cursor, Cline, Windsurf.
- Why: lancelot keep fit

### stanleys12/skilljail

- Verdict: **WATCH**
- Score: 18
- Stars: 1
- Raw: #569
- URL: https://github.com/stanleys12/skilljail
- Description: Manifest-declared, kernel-enforced least privilege for AI agent skills (Claude Code SKILL.md). Seatbelt/Landlock jail + egress proxy bound to skill activation.
- Why: lancelot keep fit

### basitalisandhu/claude-mcp-allow

- Verdict: **WATCH**
- Score: 18
- Stars: 0
- Raw: #585
- URL: https://github.com/basitalisandhu/claude-mcp-allow
- Description: Generate least-privilege Claude Code permission rules for MCP tools from their live annotations: readOnlyHint tools go to allow, everything else to ask, one mcp__server__tool rule each, never a glob. Merges into settings files, prints a diff, and --check exits 1 when annotations drift. TypeScript CLI on npm.
- Why: lancelot keep fit

### lorenzocarvalho70-sys/RMA-logistics-workflow-dashboard

- Verdict: **WATCH**
- Score: 18
- Stars: 0
- Raw: #546
- URL: https://github.com/lorenzocarvalho70-sys/RMA-logistics-workflow-dashboard
- Description: An AI-assisted control tower for data center hardware logistics, built on Cloudflare Agents, Workflows, Durable Objects and **Llama 3.3 on Workers AI**.
- Why: lancelot keep fit

### basitalisandhu/agentic-semgrep-rules

- Verdict: **WATCH**
- Score: 18
- Stars: 0
- Raw: #587
- URL: https://github.com/basitalisandhu/agentic-semgrep-rules
- Description: Semgrep rules for AI agent code: static analysis for LLM applications in Python, TypeScript and JavaScript. Finds model output reaching exec, shells, SQL, URLs, files and HTML, user input in system prompts, over-broad tools, MCP servers without auth, leaked keys and unsafe model loading. 36 tested rules, CWE and OWASP mapping.
- Why: lancelot keep fit

### ericmaster/skills-manager

- Verdict: **WATCH**
- Score: 18
- Stars: 0
- Raw: #583
- URL: https://github.com/ericmaster/skills-manager
- Description: CLI and agent skill for managing agentskills.io-format skills across every AI coding agent on your machine — single source of truth, survivable customizations.
- Why: lancelot keep fit


## Mixing / Mastering / Audio Engineering

### Dimethoxy/Disflux

- Verdict: **WATCH**
- Score: 25
- Stars: 90
- Raw: #241
- URL: https://github.com/Dimethoxy/Disflux
- Description: Phase Dispersion Audio Plugin for Windows, MacOS and Linux
- Why: audio plugin, linux audio, mixing/mastering/audio engineering fit, stars>=20, vst


## Radio / Audio Ops

### Borewit/music-metadata

- Verdict: **WATCH**
- Score: 31
- Stars: 1330
- Raw: #314
- URL: https://github.com/Borewit/music-metadata
- Description: Metadata parser for audio and video media files. Supports file and stream inputs in Node.js and browser environments, extracting format, tag, and duration information.
- Why: music metadata/taxonomy fit, musicbrainz, picard, stars>=1000, stream

### quodlibet/mutagen

- Verdict: **WATCH**
- Score: 26
- Stars: 1970
- Raw: #344
- URL: https://github.com/quodlibet/mutagen
- Description: Python module for handling audio metadata
- Why: audio metadata, music metadata/taxonomy fit, mutagen, stars>=1000

### NeptuneHub/AudioMuse-AI

- Verdict: **WATCH**
- Score: 23
- Stars: 2729
- Raw: #332
- URL: https://github.com/NeptuneHub/AudioMuse-AI
- Description: AudioMuse-AI uses sonic analysis to rediscover forgotten songs, uncover hidden connections in your music library, and generate intelligent playlists for Navidrome, Jellyfin, LMS, Lyrion, Emby and Plex: no metadata or external services required.
- Why: navidrome, playlist, self-hosted, stars>=1000

### Iranman/beets-web-manager

- Verdict: **WATCH**
- Score: 23
- Stars: 14
- Raw: #330
- URL: https://github.com/Iranman/beets-web-manager
- Description: Self-hosted Beets music library manager with import review, playlist repair, cleanup jobs, and metadata verification.
- Why: beets, music metadata/taxonomy fit, playlist, self-hosted

### metabrainz/picard-plugins

- Verdict: **WATCH**
- Score: 23
- Stars: 180
- Raw: #336
- URL: https://github.com/metabrainz/picard-plugins
- Description: Picard plugins: use 1.0 branch for Picard < 2.0 (python 2/Qt4) and 2.0 branch for Picard >= 2.0 (python 3/Qt5)
- Why: music metadata/taxonomy fit, musicbrainz, picard, stars>=100

### troykelly/emby-to-m3u

- Verdict: **WATCH**
- Score: 23
- Stars: 4
- Raw: #321
- URL: https://github.com/troykelly/emby-to-m3u
- Description: A Python tool that connects to the Emby API, retrieves music tracks, and generates M3U playlist files for genres, artists, albums, and more. Supports custom radio playlists and syncs with AzuraCast. Dockerised for easy deployment.
- Why: azuracast, playlist, radio, radio backend fit

### Angrido/Lidarr-YouTube-Downloader

- Verdict: **WATCH**
- Score: 20
- Stars: 80
- Raw: #312
- URL: https://github.com/Angrido/Lidarr-YouTube-Downloader
- Description: Lidarr YouTube Downloader: free self-hosted Docker app that auto-downloads missing albums from YouTube as tagged songs with ID3 metadata, MusicBrainz/AcoustID fingerprinting, and automatic Lidarr import. Flask + yt-dlp music automation for your home media server.
- Why: music metadata/taxonomy fit, musicbrainz, self-hosted, stars>=20

### jyourstone/jellyfin-musictags-plugin

- Verdict: **WATCH**
- Score: 20
- Stars: 62
- Raw: #318
- URL: https://github.com/jyourstone/jellyfin-musictags-plugin
- Description: A Jellyfin plugin that automatically extracts metadata from audio files - such as ID3 tags, Vorbis comments, and more - and converts them into standard Jellyfin tags.
- Why: id3 tag, music metadata/taxonomy fit, stars>=20, vorbis comment

### izaz4141/picard-lrclib

- Verdict: **WATCH**
- Score: 20
- Stars: 50
- Raw: #334
- URL: https://github.com/izaz4141/picard-lrclib
- Description: A Picard Musicbrainz Plugins for Fetching Lyrics from LRCLIB
- Why: music metadata/taxonomy fit, musicbrainz, picard, stars>=20

### Serial-ATA/lofty-rs

- Verdict: **WATCH**
- Score: 18
- Stars: 371
- Raw: #326
- URL: https://github.com/Serial-ATA/lofty-rs
- Description: Audio metadata library
- Why: audio metadata, music metadata/taxonomy fit, stars>=100

### metabrainz/picard-plugin-replaygain2

- Verdict: **WATCH**
- Score: 18
- Stars: 6
- Raw: #335
- URL: https://github.com/metabrainz/picard-plugin-replaygain2
- Description: MusicBrainz Picard 3 Replaygain 2.0 plugin
- Why: music metadata/taxonomy fit, musicbrainz, picard

### ikelvingo/navidrome-netease-metadata-plugin

- Verdict: **WATCH**
- Score: 18
- Stars: 13
- Raw: #342
- URL: https://github.com/ikelvingo/navidrome-netease-metadata-plugin
- Description: navidrome的网易云刮削插件 | NetEase Cloud Music Metadata Plugin for Navidrome
- Why: music metadata, music metadata/taxonomy fit, navidrome

### XBisATrouble/netease-music-plugin

- Verdict: **WATCH**
- Score: 18
- Stars: 5
- Raw: #341
- URL: https://github.com/XBisATrouble/netease-music-plugin
- Description: Netease Music Metadata Plugin for Navidrome
- Why: music metadata, music metadata/taxonomy fit, navidrome


## Video Production / Editing

### equalang/equalang-mcp

- Verdict: **KEEP**
- Score: 36
- Stars: 6
- Raw: #840
- URL: https://github.com/equalang/equalang-mcp
- Description: MCP server for Equalang: translate PDF, DOCX, PPTX, XLSX, EPUB, subtitles, pictures, audio and video with the layout kept; transcribe recordings.
- Why: agent-native workflow, subtitle, subtitles, transcription, video, video production fit
