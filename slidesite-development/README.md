# SlideSite Development

Temporary cross-runtime canonical checkpoint for the SlideSite / SLS project, housed inside `presentation-hub` until it is moved to its own repository.

## Roles
- **ChatGPT Project:** fast working context.
- **This folder in GitHub:** canonical cross-runtime checkpoint for material project state.
- **presentation-hub deployment areas:** live HTML publishing/testing.

## Mandatory sync safety
**Never overwrite newer working material with an older GitHub copy.**

“Sync” means:
1. Identify the current working version and the GitHub version.
2. Compare freshness/state before replacement.
3. Preserve the newest authoritative work.
4. Reconcile deliberate changes rather than blindly copying in either direction.
5. After reconciliation, write the current canonical state to GitHub.

GitHub should be consulted at checkpoints and cross-runtime handoffs—not reread on every chat turn.

## Canonical contents
- `PROJECT_MASTER.md` — project state and next actions.
- `SDB.md` — Software Design Brief (to be populated from the current authoritative SDB).
- `canonical-sls/` — location for the declared canonical standalone SLS build.
- Additional specs/architecture/brand docs should be added only when they are genuinely canonical.
