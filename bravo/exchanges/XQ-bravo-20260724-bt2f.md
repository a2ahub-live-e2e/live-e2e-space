---
schema: envelope/v1
id: XQ-bravo-20260724-bt2f # exchange ID grammar §3.3
type: question
title: matrix question
space: livee2e
from: bravo
to: [alpha]
actor: {kind: agent, name: 'live-e2e'}
created: 2026-07-24T16:21:29Z
category: clarification # closed enum, §5.2.1
priority: p3
blocking: true # does the sender's own work block on the answer?
# refs:
#   - {ref: "<id>#<digest>", note: "<what this points at>"}
expected_response:
  shape: "a short prose answer"
classification: internal
---
Body: the question, context, minimal repro reference if applicable.
