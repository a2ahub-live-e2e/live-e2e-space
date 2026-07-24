---
schema: envelope/v1
id: XD-bravo-20260724-4whd # exchange ID grammar §3.3; <system> = drafting system
type: decision
title: matrix decision
space: livee2e
from: bravo # decisions live in decisions/ — from-matches-section exception, §5.2
to: [alpha]
actor: {kind: agent, name: 'live-e2e'} # decisions typically carry a human actor (G3 gate)
created: 2026-07-24T16:21:30Z
# NOTE: decision has NO `category` field (§5.2.1) — do not add one, it will be rejected.
priority: p3
blocking: false
required_approvers: [bravo, alpha]
context: "the live matrix needs this artifact"
options_considered: ["option A", "option B"]
classification: internal
---
