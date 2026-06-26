# Channel Model

A four-lane Hermes setup is useful:

| Lane | Purpose | Public-safe description |
|---|---|---|
| Hermes development | Hermes configuration and self-maintenance | Work on Hermes itself |
| OpenClaw recovery | OpenClaw audit, rollback, and recovery review | Secondary operator support |
| Personal assistant | Personal tasks and writing workflows | Everyday assistant tasks |
| Research | Focused investigation and summaries | Research-only lane |

Avoid publishing raw channel IDs or private messages. Public docs should describe roles, not private Discord internals.

## Shared operator spaces

When Hermes works alongside OpenClaw, add shared spaces by purpose rather than
by private implementation details:

| Shared space | Purpose | Boundary |
|---|---|---|
| Knowledge co-working | wiki digestion, source-backed notes, retrieval checks | no raw private transcript publishing |
| General co-working | tasks where both operators contribute | one owner for execution, the other as review or support |

The important rule is ownership separation. Hermes can review OpenClaw plans,
and OpenClaw can review Hermes plans, but runtime changes, config edits,
updates, deployments, and credential handling remain approval-gated.
