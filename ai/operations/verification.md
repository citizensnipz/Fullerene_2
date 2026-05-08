# Verification Policy

## Core rule
Verification is mandatory before completion.

## Verification matrix (starter)
- Docs-only changes
  - [ ] Links valid
  - [ ] Cross-file references updated
- Code changes
  - [ ] Relevant tests run
  - [ ] Lint/static checks run (if configured)
  - [ ] Build/type checks run (if configured)
- Config/ops changes
  - [ ] Command/runbook steps validated
  - [ ] Failure path/rollback sanity checked

## Reporting format
For each completed task, record:
- What was changed
- What checks were run
- Result per check
- What could not be verified and why

## If verification is blocked
- Mark task `PARTIALLY VERIFIED`.
- List exact blocker and next command/action.
