---
schema: envelope/v1
id: XR-bravo-matrix-lifecycle-req # standing ID grammar §3.3
type: requirement
title: matrix requirement
space: livee2e
from: bravo
to: [alpha]
actor: {kind: agent, name: live-e2e}
created: 2026-07-29T17:44:17Z
category: other # closed enum, §5.2.1
priority: p3
blocking: false # if false, interim_behavior below is REQUIRED
interim_behavior: we proceed with the current shape # required when blocking: false
needed_by: 2026-12-31 # optional — staleness reference, never auto-closes
# target_contract: XC-<id>            # optional — omit for a brand-new capability
acceptance_criteria: ["the artifact validates"]
expected_response: # optional
    shape: a short prose answer
classification: internal
thread: thread:bravo-20260729-w17n
---
## What we need
## The rule for judging a value
## Why
