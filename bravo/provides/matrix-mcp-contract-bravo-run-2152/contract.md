---
schema: envelope/v2
id: XC-bravo-matrix-mcp-contract-bravo-run-2152 # e.g. XC-axon-ingest — standing ID grammar §3.3
type: contract
title: matrix contract
space: livee2e
from: bravo
to: [alpha]
actor: {kind: agent, name: live-e2e} # kind: human|agent
created: 2026-08-05T00:32:27Z
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
thread: thread:bravo-20260805-6a3x
# refs:
#   - {ref: "<XC-id>@<version>", note: "<why>"}
artifacts:
    - path: schema/matrix-mcp-contract-bravo-run-2152.schema.json
      role: schema
      normative: true
      media_type: application/schema+json
    - path: fixtures/valid/matrix-mcp-contract-bravo-run-2152.json
      role: valid-fixture
      normative: true
      media_type: application/json
      conforms_to: schema/matrix-mcp-contract-bravo-run-2152.schema.json
    - path: fixtures/invalid/matrix-mcp-contract-bravo-run-2152.json
      role: invalid-fixture
      normative: true
      media_type: application/json
      conforms_to: schema/matrix-mcp-contract-bravo-run-2152.schema.json
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
