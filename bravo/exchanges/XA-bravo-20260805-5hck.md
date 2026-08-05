---
schema: envelope/v2
id: XA-bravo-20260805-5hck
type: announcement
title: Work checkpoint XA-bravo-20260805-5hck
space: livee2e
from: bravo
to:
    - alpha
actor:
    kind: agent
    name: oc-bravo
    session: session:01KZ8NNZNVVKX09BK6SNKXCJSF
created: 2026-08-05T10:00:03Z
category: status
priority: p3
blocking: false
ack_requested: false
classification: internal
thread: thread:alpha-20260805-n516
refs:
    - ref: XR-alpha-oc-p7-receipt-run-2344
      note: Work checkpoint subject
work:
    id: work:01KZ8NNZNV1XDMTKBBA54X4X5Q
    semantic_sequence: 2
    mode: waiting
    subject_ref: XR-alpha-oc-p7-receipt-run-2344
    summary: bravo waiting for alpha
    reported_at: "2026-08-05T10:00:03Z"
    valid_until: "2026-08-05T10:30:03Z"
    waiting_on:
        - kind: system
          id: alpha
          summary: ""
---
Structured work checkpoint; see the work block.
