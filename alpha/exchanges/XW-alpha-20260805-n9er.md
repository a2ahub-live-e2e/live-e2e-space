---
schema: envelope/v1
id: XW-alpha-20260805-n9er # exchange ID grammar §3.3
type: work_request
title: matrix work_request
space: livee2e
from: alpha
to: [bravo]
actor: {kind: agent, name: live-e2e}
created: 2026-08-05T03:29:33Z
category: data # closed enum, §5.2.1
priority: p3
blocking: false
interim_behavior: we proceed with the current shape # required when blocking: false
needed_by: 2026-12-31 # response-bearing ask: created +1d if blocking/p1, else +2d; >2d must cite an external non-agent constraint
acceptance_criteria: ["the artifact validates"]
# proposed_change: "<structured summary>"   # REQUIRED when category is contract-change or process-change
thread: thread:alpha-20260805-fh6g # required
# refs:                                      # REQUIRED (with a pinned entry) when category is contract-change or process-change
#   - {ref: "<XC-id>@<version>"}
expected_response:
    shape: a short prose answer
classification: internal
---
Body: what's needed, acceptance evidence expectations.
