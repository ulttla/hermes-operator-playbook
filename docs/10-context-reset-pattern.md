# Context Reset Pattern

Long-running AI work needs safe reset and resume rules.

## Prepare

- write current goal
- record decisions already made
- list blockers and next action
- store the file or wiki pointer needed after reset

## Resume

- read only the checkpoint needed
- verify current repo/runtime state
- continue from the next action instead of replaying the full history
