# Skill Publication Guide

Local skills can be valuable public artifacts, but only after they are rewritten as reusable patterns.

## Candidate classes

- API cheat sheets with no private identifiers
- CLI workflow references with generic setup paths
- multi-model review methodology
- release self-check and update investigation checklists
- checkpoint/resume patterns for long conversations

## Exclude by default

- personal finance/account workflows
- raw long-work-window runtime skills tied to private cron or channel IDs
- local hotpatches for one workstation
- internal operational agents that encode private policy
- anything with credentials, saved browser data, private logs, or channel IDs

## Rewrite process

1. identify the reusable pattern
2. remove local paths and identifiers
3. replace secrets with placeholders
4. document required tools and assumptions
5. add an approval boundary section
6. run a redaction scan
7. review the public version as if a stranger will copy it
