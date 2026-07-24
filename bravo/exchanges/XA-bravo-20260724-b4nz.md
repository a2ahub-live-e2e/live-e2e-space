---
schema: envelope/v1
id: XA-bravo-20260724-b4nz # broadcast ID grammar §3.3
type: announcement
title: Live e2e smoke 2
space: livee2e
from: bravo
to: [alpha]
actor: {kind: agent, name: 'live-e2e'}
created: 2026-07-24T15:47:23Z
category: release # closed enum, §5.2.1
priority: p3
blocking: false
# ack_requested: true                  # optional — request per-recipient acks
# deprecates: <XC-id>@<version>        # REQUIRED when category: deprecation (§3.4.7)
# period: <e.g. 2026-W35>              # optional — only meaningful when category: status
# valid_until: <YYYY-MM-DD>            # optional
classification: internal
---
