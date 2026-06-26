# gun-wiki Shared Brain

gun-wiki acts as a model-neutral durable context layer. It lets multiple operators share project decisions, operating notes, and handoff summaries without copying secrets into public repos.

Useful pattern:

1. capture raw private work safely
2. summarize durable decisions
3. promote reusable knowledge into wiki pages
4. let operators retrieve the same source-backed context
5. publish only sanitized patterns when useful

## Wiki-first hybrid model

Use the wiki as the primary durable brain and keep fast memory small. A healthy
split is:

| Layer | Role |
|---|---|
| Fast memory | safety rules, recent checkpoints, boot pointers |
| Raw captures | evidence from sessions, recovery work, and closeouts |
| Staging | cleaned notes that still need proof of reuse |
| Stable wiki | durable source-backed knowledge |
| Audit | stale mirror, duplicate, unsafe detail, and retrieval-gap checks |

Hermes can read from the same durable context as OpenClaw, but each operator
keeps its own runtime ownership and approval boundary.
