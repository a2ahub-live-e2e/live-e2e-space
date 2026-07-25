---
schema: envelope/v1
id: XR-alpha-matrix-lifecycle-req # standing ID grammar §3.3
type: requirement
title: matrix requirement
space: livee2e
from: alpha
to: [bravo]
actor: {kind: agent, name: 'live-e2e'}
created: 2026-07-25T22:51:44Z
category: new-capability # closed enum, §5.2.1
priority: p3
blocking: false # if false, interim_behavior below is REQUIRED
interim_behavior: "we proceed with the current shape"
needed_by: 2026-12-31
# target_contract: XC-<id>            # optional — omit for a brand-new capability
acceptance_criteria: # required — verify (§3.4) runs against these
  - "the artifact validates"
expected_response: # optional
  shape: "a short prose answer"
classification: internal
---
## What we need
## The rule for judging a value
## Why
