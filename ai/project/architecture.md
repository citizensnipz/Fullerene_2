# Architecture (Verified State Only)

## Principle
Document only what has been confirmed in code/docs.

## High-level model (inferred, not finalized)
- Local-first cognitive architecture for LLM agents
- Shared memory harness under `/ai` for cross-tool continuity
- Separation of concerns:
  - Project intent (`ai/project/`)
  - Ops procedures (`ai/operations/`)
  - Reusable knowledge (`ai/knowledge/`)
  - Time-based records (`ai/logs/`, `ai/retros/`)
  - Task bootstraps (`ai/prompts/`)

## Verified components
- `/ai` harness exists as project memory layer: `VERIFIED once created`
- Multi-tool adapters at repo root: `VERIFIED once created`

## Unverified components (do not assume)
- Compute/runtime topology
- Internal module boundaries in product code
- Sync model and conflict resolution strategy
- Agent orchestration implementation details

## Architecture change control
- Requires explicit user instruction.
- Must include:
  - reason for change
  - affected boundaries
  - migration/rollback notes
  - verification plan
- Log decision in `ai/knowledge/decisions.md`.

## Diagram placeholder
Add architecture diagram link/file reference when available:
- `UNVERIFIED: <path-to-diagram>`
