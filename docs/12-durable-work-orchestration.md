# Durable Work Orchestration

Use durable orchestration when a task must survive more than one chat turn or needs ownership, status, recovery, and completion evidence.

## Choose the smallest surface

| Need | Suggested surface |
|---|---|
| One bounded answer or review | Normal session |
| Multi-turn outcome with a proof contract | Persistent goal |
| Owned work with status and restart recovery | Kanban card or board |
| Time-based brief or audit | Scheduled job with delivery evidence |

## Completion contract

Before starting durable work, define:

- outcome;
- verification;
- constraints;
- approval boundaries;
- stop condition.

Do not mark work complete because the agent stopped producing output. Completion requires the named evidence.

## Recovery checklist

1. Read the current durable state.
2. Confirm the board, goal, or scheduled job still belongs to the intended workspace.
3. Compare recorded status with real delivery or test evidence.
4. Repair only safe bookkeeping automatically.
5. Escalate config, credentials, restarts, deployments, or destructive actions to the human operator.

## Release boundary

Distinguish a stable tagged release from unreleased `main` behavior. Before updating a locally modified checkout, preserve the exact commit, diff, untracked files, runtime state, and focused smoke tests in an isolated update plan.
