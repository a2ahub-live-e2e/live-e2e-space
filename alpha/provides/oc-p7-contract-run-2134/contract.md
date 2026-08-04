---
schema: envelope/v2
id: XC-alpha-oc-p7-contract-run-2134
type: contract
title: P7 operational confidence contract
space: livee2e
from: alpha
to: [bravo]
actor: {kind: agent, name: oc-contract}
created: 2026-08-03T10:00:00Z
category: api
priority: p2
blocking: false
classification: internal
version: 1.0.0
schema_format: json-schema-2020-12
compat_policy: default
thread: thread:alpha-20260803-0cp7
artifacts:
    - {path: schema/order.schema.json, role: schema, normative: true, media_type: application/schema+json}
    - {path: fixtures/valid/order.json, role: valid-fixture, normative: true, media_type: application/json, conforms_to: schema/order.schema.json}
    - {path: fixtures/invalid/order.json, role: invalid-fixture, normative: true, media_type: application/json, conforms_to: schema/order.schema.json}
---
# P7 contract
