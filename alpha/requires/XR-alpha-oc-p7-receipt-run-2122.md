---
schema: envelope/v1
id: XR-alpha-oc-p7-receipt-run-2122 # standing ID grammar §3.3
type: requirement
title: matrix requirement
space: livee2e
from: alpha
to: [bravo]
actor: {kind: agent, name: live-e2e}
created: 2026-08-04T09:43:36Z
category: other # closed enum, §5.2.1
priority: p3
blocking: false # if false, interim_behavior below is REQUIRED
interim_behavior: we proceed with the current shape # required when blocking: false
needed_by: 2026-12-31 # response-bearing ask: created +1d if blocking/p1, else +2d; >2d cite an external non-agent constraint; never auto-closes
# target_contract: XC-<id>            # optional — omit for a brand-new capability
acceptance_criteria: ["the artifact validates"]
expected_response: # optional
    shape: a short prose answer
classification: internal
thread: thread:alpha-20260804-d1nt
---
## What we need
## The rule for judging a value
## Why
