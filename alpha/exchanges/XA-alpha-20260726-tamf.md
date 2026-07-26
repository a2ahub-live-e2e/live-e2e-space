---
schema: envelope/v1
id: XA-alpha-20260726-tamf # broadcast ID grammar §3.3
type: announcement
title: layer3 concurrent write A
space: livee2e
from: alpha
to: [bravo]
actor: {kind: agent, name: 'live-e2e'}
created: 2026-07-26T21:08:41Z
category: release # closed enum, §5.2.1
priority: p3
blocking: false
# ack_requested: true                  # optional — request per-recipient acks
# deprecates: <XC-id>@<version>        # REQUIRED when category: deprecation (§3.4.7)
# period: <e.g. 2026-W35>              # optional — only meaningful when category: status
# valid_until: <YYYY-MM-DD>            # optional
classification: internal
thread: thread:alpha-20260726-dzra
---
