# DADLINGO

Public evaluation build of a Cantonese-first Traditional Chinese literacy game.

## Current build

The live build currently contains one complete vertical slice:

- E03 — `遊樂場尋寶`
- meaning recognition, four-pair matching, reading comprehension and transfer
- delayed evidence visual and English support
- mobile-first layout
- a persistent `Tester：跳關` control for remote stage-by-stage review; jumped
  sessions are visibly marked test-only and never receive a learning score
- no analytics, account, network API, or learner-data upload

This is an evaluation sample, not the completed curriculum.

## Audio phases

```mermaid
flowchart LR
    A[Phase 1<br/>Core learning product] --> B[Device Cantonese TTS<br/>local voice when available]
    B --> C[Phase 2<br/>optional high-quality audio]
    C --> D[VoxCPM2 or approved voice adapter]
```

Phase 1 uses only a Cantonese voice available on the learner's device and must
remain usable without audio. It never falls back to Mandarin. Phase 2 may add an
optional higher-quality male/female voice path after pronunciation, rights and
device integration pass review.

The current E03 sample intentionally shows audio as unavailable because its
voice assets have not passed that later gate.

## Rights

Copyright © 2026 Alex. Public evaluation only. No redistribution license is
granted by this repository at this stage.
