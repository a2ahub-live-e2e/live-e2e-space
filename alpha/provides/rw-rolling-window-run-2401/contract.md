---
schema: envelope/v2
id: XC-alpha-rw-rolling-window-run-2401 # e.g. XC-axon-ingest — standing ID grammar §3.3
type: contract
title: matrix contract
space: livee2e
from: alpha
to: [alpha]
actor: {kind: agent, name: live-e2e} # kind: human|agent
created: 2026-08-05T12:03:07Z
category: other
priority: p3
blocking: false
classification: internal
version: 2.0.0 # set by `a2a contract publish`, never by hand — see the note at the bottom
schema_format: json-schema-2020-12
compat_policy: default
# generated_from:                    # include only for a code-generated contract
#   tool: "<generator name and version>"
#   source_digest: "sha256:<export-source-v1 digest>"
thread: thread:alpha-20260805-fc44
# refs:
#   - {ref: "<XC-id>@<version>", note: "<why>"}
artifacts:
    - path: schema/rw-rolling-window-run-2401.schema.json
      role: schema
      normative: true
      media_type: application/schema+json
    - path: fixtures/valid/rw-rolling-window-run-2401.json
      role: valid-fixture
      normative: true
      media_type: application/json
      conforms_to: schema/rw-rolling-window-run-2401.schema.json
    - path: fixtures/invalid/rw-rolling-window-run-2401.json
      role: invalid-fixture
      normative: true
      media_type: application/json
      conforms_to: schema/rw-rolling-window-run-2401.schema.json
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

<!-- THE VERSION FIELD IS NOT YOURS TO SET. Leave it at 0.0.0.
     `a2a contract publish` finalizes this descriptor with the version you are
     publishing, and its commit — the one where the version FLIPS — is what
     makes that version resolvable ever after. `a2a contract materialize`
     depends on it, and so does every later version, which resolves the
     earlier one as its compatibility baseline.

     Set this to the version you intend to publish and there is nothing left
     to flip: publish writes byte-identical bytes, its commit carries only the
     publish event, and no commit establishes the version. `publish` refuses
     that up front — "publication-would-not-establish" — while it is still a
     one-line fix here. Bump by publishing (`--version 1.1.0`, or
     `--bump minor`), never by editing this field. -->
