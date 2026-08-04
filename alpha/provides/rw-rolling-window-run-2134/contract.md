---
schema: envelope/v2
id: XC-alpha-rw-rolling-window-run-2134 # e.g. XC-axon-ingest — standing ID grammar §3.3
type: contract
title: matrix contract
space: livee2e
from: alpha
to: [alpha]
actor: {kind: agent, name: live-e2e} # kind: human|agent
created: 2026-08-04T11:03:02Z
category: other
priority: p3
blocking: false
classification: internal
version: 1.0.0
schema_format: json-schema-2020-12
compat_policy: default
# generated_from:                    # include only for a code-generated contract
#   tool: "<generator name and version>"
#   source_digest: "sha256:<export-source-v1 digest>"
thread: thread:alpha-20260804-s5ze
# refs:
#   - {ref: "<XC-id>@<version>", note: "<why>"}
artifacts:
    - path: schema/rw-rolling-window-run-2134.schema.json
      role: schema
      normative: true
      media_type: application/schema+json
    - path: fixtures/valid/rw-rolling-window-run-2134.json
      role: valid-fixture
      normative: true
      media_type: application/json
      conforms_to: schema/rw-rolling-window-run-2134.schema.json
    - path: fixtures/invalid/rw-rolling-window-run-2134.json
      role: invalid-fixture
      normative: true
      media_type: application/json
      conforms_to: schema/rw-rolling-window-run-2134.schema.json
# Declare every other regular carried file exactly once. Companion roles live
# under artifacts/: errors, vocabulary, limits, changelog, example, or other.
# `conforms_to` is required only on valid-fixture and invalid-fixture entries.
#  - path: artifacts/errors.yaml
#    role: errors
#    normative: true
#    media_type: application/yaml
---
# <Contract name>

<One paragraph describing the contract in the consumer's terms.>

## What it covers

<The operations, feeds, or vocabulary in scope, plus deliberate exclusions.>

## Error shape

<How failures are represented and which codes or statuses consumers handle.>

## Compatibility intent

<What is breaking beyond the computed schema-shape check, and what may grow.>

## Owner and support

<Who owns this contract and where consumers can ask for help.>
