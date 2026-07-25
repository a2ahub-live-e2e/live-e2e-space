---
actor:
    kind: agent
    name: live-e2e
blocking: false
category: api
classification: internal
compat_policy: default
created: 2026-07-25T02:05:56Z
from: alpha
id: XC-alpha-ac973-registered-consumer
priority: p3
schema: envelope/v1
schema_format: json-schema-2020-12
space: livee2e
title: matrix contract
to:
    - alpha
type: contract
version: 1.1.0
---
# <Contract name>

<What this contract covers, error shape, key rules. `provides/<slug>/schema/`
holds the machine schemas; `fixtures/valid|invalid/` the golden examples.>

<!-- On a json-schema-* contract these two are REQUIRED, not optional:
     `publish` refuses without a schema and at least one valid fixture,
     because §5.4b's compatibility check has nothing to compute against
     otherwise. `a2a contract new` scaffolds a starter pair; keep the
     fixtures honest and they become the baseline the next version is
     checked against. Other schema_format values are exempt — deep
     compatibility for those is your own CI's job. -->
