# Claude Adapter (Root)

This repository uses a shared AI harness under `/ai`.

## Load Order (required)
1. `ai/MEMORY.md`
2. Relevant files linked from the memory index
3. Relevant prompt from `ai/prompts/`

## Global Rules
- Verify before claiming completion.
- Make small, scoped changes.
- Do not rewrite architecture without explicit instruction.
- Do not guess unknowns; mark as `UNVERIFIED`.
- After meaningful work, update:
  - `ai/logs/SESSION_LOG.md`
  - `ai/logs/CHANGELOG_AI.md` (if behavior changed)
  - any impacted `/ai` knowledge files

If this file conflicts with `/ai`, `/ai` is the source of truth.
