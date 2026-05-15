# Skills and Reusable Workflows

Some local skills are useful beyond one workstation, but they must be packaged carefully.

## Good candidates

- long work window orchestration patterns
- reset/checkpoint readiness
- update self-check and rollback review
- context/hotpatch verification patterns
- browser profile safety helpers
- worklog sync templates

## Usually private or internal-only

- skills containing local channel IDs, private paths, credentials, or personal workflow assumptions
- skills that depend on private browser profiles or unpublished APIs
- skills that expose raw memory or private logs

## Packaging rule

Publish a generic skill only after removing private IDs, replacing local paths with placeholders, adding a threat model, and documenting required tools.
