---
schema: envelope/v1
id: XD-alpha-20260730-sp6w # exchange ID grammar §3.3; <system> = drafting system
type: decision
title: matrix decision
space: livee2e
from: alpha # decisions live in decisions/ — from-matches-section exception, §5.2
to: [alpha, bravo]
actor: {kind: human, name: live-e2e-operator} # decisions typically carry a human actor (G3 gate)
created: 2026-07-30T16:12:00Z
# NOTE: decision has NO `category` field (§5.2.1) — do not add one, it will be rejected.
priority: p3
blocking: false
required_approvers: [alpha, bravo]
context: the live matrix needs this artifact # required
options_considered: ["option A", "option B"]
classification: internal
thread: thread:alpha-20260730-t0mz
---
