# Station Brain

**Captured:** 2026-11-17  
**Status:** concept / project seed  
**Context:** Noosphere / coma.fm / future radio-TV stack  
**Trigger:** RadioBox discussion — affordable station software suite with PlayerBox, ScheduleBox, QuizBox and BingoBox.

## Core thesis

Do **not** build another full radio automation suite.

Existing systems already cover library, scheduling, playout, jingles, voice tracks, clocks and basic station operations.

The more interesting gap is the semantic layer **above playout**:

```text
what we planned
  -> what actually went on air
  -> what was in that broadcast
  -> what is worth preserving / finding / reusing / publishing
```

Working name: **Station Brain**.

Alternative name for the first concrete module: **Aircheck Lab**.

## Positioning

**Station Brain = observe -> understand -> archive -> reuse**

It should ingest an existing broadcast/stream rather than replace the playout engine.

Possible upstream systems:
- SUB/WAVE
- AzuraCast
- LibreTime
- Liquidsoap
- Icecast
- local audio output
- later: TV/video playout

## Core pipeline

```text
stream / playout output
        |
continuous recorder
        |
speech / music / ad / jingle / silence segmentation
        |
metadata reconciliation
        |
transcription + speaker diarization
        |
semantic broadcast timeline
        |
+----------------+----------------+----------------+
| aircheck       | search/archive | clip/reuse      |
| QA/report      | retrieval      | publishing      |
+----------------+----------------+----------------+
```

The primary asset is **not the four-hour audio file**.

The primary asset is a **semantically indexed broadcast timeline**.

## Timeline entities

At minimum:

- track
- presenter / DJ speech
- jingle
- station ident
- promo
- commercial
- news
- weather
- silence / dead air
- unknown / mixed

Later:

- interview
- phone call
- guest
- sponsor mention
- competition / quiz
- voice-track
- traffic
- emergency bulletin

## MVP

### 1. Capture
Continuously record an Icecast/local stream with reliable timestamps.

### 2. Segment
Classify the timeline into:
- music
- speech
- speech + music
- jingle/promo
- silence

### 3. Reconcile metadata
Consume now-playing / playout metadata where available and align it with detected audio boundaries.

### 4. Speech understanding
For every speech segment:
- transcript
- word timestamps
- speaker / presenter where possible

### 5. Aircheck view
Render one shift/show as a compressed timeline:
- exact order
- durations
- track titles
- speech breaks
- jingles/promos
- silence/anomalies

### 6. Search
Queries such as:
- “where did the presenter mention Bowie?”
- “all breaks about the weather”
- “all promos used this week”
- “show me dead air over 2 seconds”

### 7. Clip extraction
One click / API call:
- select semantic segment
- add handles
- export audio clip
- keep source/timestamp provenance

## Phase 2

- planned clock vs actual clock
- talk/music ratio
- break-length statistics
- loudness/clipping anomalies
- repeated promo/jingle detection
- advertiser detection
- automatic show notes
- podcast cut generation
- social clip generation
- presenter coaching / aircheck summaries
- content reuse suggestions
- archive deduplication

## Phase 3: Broadcast Intelligence

Extend the same data model to television/video:

```text
programme / continuity / ident / promo / commercial / presenter / news
```

Add:
- shot/scene boundaries
- OCR
- visual logo/ident detection
- faces/personas
- subtitle alignment
- video clip factory

The long-term project therefore becomes a **Broadcast Intelligence layer**, not a radio-only utility.

## Why RadioBox matters

RadioBox is a useful signal because it attacks the familiar operational gaps of small stations:

- PlayerBox — music playback/library
- ScheduleBox — shows/shifts
- QuizBox — live quizzes
- BingoBox — on-air bingo

The author explicitly asks broadcasters which remaining jobs still live in spreadsheets, workarounds or unaffordable software.

Our answer is a different layer:

> the station usually knows what it intended to broadcast, but has poor structured memory of what actually happened on air.

Station Brain should become that memory.

## Build-vs-buy boundary

Do not rebuild:
- playout
- music scheduling
- stream server
- generic station CRM
- generic calendar
- generic audio editor

Build:
- ingestion adapters
- semantic timeline
- reconciliation
- aircheck UX
- search/retrieval
- QA
- clip/reuse pipeline
- broadcaster-specific intelligence

## Existing components to investigate/reuse

Likely donors/components:
- inaVAMOS — speech/music segmentation
- faster-whisper — transcription
- pyannote / equivalent — diarization
- FFmpeg — capture/cuts/loudness
- existing stream metadata APIs
- WavePulse — research reference for radio-stream analysis
- Aircheck-type commercial products — product/UX reference, not code dependency

## First proving experiment

Use one real or synthetic 2–4 hour station recording.

Success criterion:

From one ingest run, produce a searchable HTML timeline where a user can:
1. see every song/speech/jingle/silence block;
2. search transcript text;
3. jump to the matching audio;
4. export a selected break as a clip;
5. inspect basic show statistics.

If this works reliably, the concept is real.

## Strategic fit

- **coma.fm:** retrospective archive, show QA, reuse, era/world continuity.
- **Noosphere:** broadcast/media intelligence module.
- **future fictional TV channel:** same timeline/event architecture with video features.
- **media-monitoring:** potential reuse of segmentation/transcription/provenance patterns.

## Key design rule

**Playout systems decide what should happen next.  
Station Brain explains what actually happened.**
