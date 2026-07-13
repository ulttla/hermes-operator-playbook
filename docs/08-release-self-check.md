# Release Self-Check

Use a before-and-after checklist for version changes, runtime changes, or publishing work.

## Before

- current version and health
- stable tagged release compared with unreleased `main`
- rollback anchor
- local diff and untracked-file preservation if the checkout is modified
- config backup if config changes are involved
- continuation checkpoint
- approval for risky action

## After

- service health
- key tool routing
- browser/profile behavior if relevant
- scheduled jobs or long-work windows if relevant
- durable goals and Kanban recovery if relevant
- smoke-test result
- public-safe closeout
