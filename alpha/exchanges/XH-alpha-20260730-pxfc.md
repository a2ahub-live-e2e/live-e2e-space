---
schema: envelope/v1
id: XH-alpha-20260730-pxfc # exchange ID grammar §3.3
type: handoff
title: matrix handoff
space: livee2e
from: alpha
to: [bravo]
actor: {kind: agent, name: live-e2e}
created: 2026-07-30T01:14:48Z
# NOTE: handoff has NO `category` field (§5.2.1) — do not add one, it will be rejected.
priority: p3
blocking: false
fulfills: [XR-alpha-matrix-req]
thread: thread:alpha-20260730-8m03
refs: []
deliverables: [{"name": "matrix artifact", "ref": "live-e2e/matrix@1.0.0", "kind": "doc"}]
verification: the matrix re-ran the suite; all green # required
acceptance_criteria: ["the artifact validates"]
limitations: [] # required — an empty list is a claim, not an omission
# env_requirements: "<what the receiver's environment must provide>"   # optional
classification: internal # required, §16.2 — each: name, ref, kind
---
## Context
## What was built
## How to verify
## How to operate
## Limitations & next steps
