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

## Review gates

Before publishing, answer these checks:

- **Can a reader copy this safely?** If not, add setup assumptions or a warning.
- **Does the doc include a read-only first step?** If not, add one.
- **Are write actions separated from read actions?** If not, split the workflow.
- **Is every credential represented as a placeholder?** If not, stop and redact.
- **Is there a validation step?** Prefer a dry run, link check, smoke test, or explicit manual review.

## Rewrite examples

| Private source | Public rewrite |
| --- | --- |
| Exact channel id | “the target operations channel” |
| Local profile name with saved session | “an authenticated browser profile” |
| Raw tool transcript | “summary of the observed failure and fix” |
| One-off hotpatch | “general recovery pattern and rollback boundary” |
| Credentialed API call | “command shape using environment variable placeholders” |
