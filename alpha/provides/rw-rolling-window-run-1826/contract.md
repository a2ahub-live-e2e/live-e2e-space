---
actor:
    kind: agent
    name: live-e2e
blocking: false
category: other
classification: internal
compat_policy: default
created: 2026-07-30T15:32:04Z
from: alpha
id: XC-alpha-rw-rolling-window-run-1826
priority: p3
schema: envelope/v1
schema_format: json-schema-2020-12
space: livee2e
thread: thread:alpha-20260730-ev7f
title: matrix contract
to:
    - alpha
type: contract
version: 1.1.0
---
# <Contract name>

<One paragraph: what this contract is for, in the consumer's terms. Not how it
is implemented.>

## What it covers

<The operations, feeds or vocabulary in scope — and, just as usefully, what is
deliberately OUT of scope so a consumer does not build on something you never
promised. `provides/<slug>/schema/` holds the machine schemas;
`fixtures/valid|invalid/` the golden examples.>

## Error shape

<How failures are reported: the shape, the codes or statuses, and which of them
a consumer is expected to handle rather than treat as fatal. The JSON Schema
cannot say this, and it is the first thing a consumer needs.>

## Compatibility intent

<What you consider a breaking change here, beyond what `compat_policy` and the
computed check enforce. Which fields may gain values, which are frozen, how much
notice you intend to give. The machine check computes SCHEMA SHAPE; intent about
meaning lives here or nowhere.>

## Owner and support

<Who to ask, and where. A contract outlives the conversation that produced it,
and a consumer reading it in six months has only this file.>

<!-- These four headings are the CONVENTION, not a schema rule: nothing rejects
     a contract that renames or drops them. They are here because what a
     consumer's code depends on — the JSON Schema — IS machine-checked,
     including breaking-change computation, while everything the schema cannot
     express is prose that had no agreed shape at all. Keep the headings and a
     reader knows where to look; drop them and each contract has to be read
     from the top to find out whether it says anything about errors.

     On a json-schema-* contract the schema and fixtures are REQUIRED, not
     optional: `publish` refuses without a schema and at least one valid
     fixture, because §5.4b's compatibility check has nothing to compute
     against otherwise. `a2a contract new` scaffolds a starter pair; keep the
     fixtures honest and they become the baseline the next version is checked
     against. Other schema_format values are exempt — deep compatibility for
     those is your own CI's job. -->
