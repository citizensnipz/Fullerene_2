# Agent Adapter (Root)

For Codex/OpenAI-style agents and compatible tools.

## Required Boot Sequence
- Read `ai/MEMORY.md` first.
- Open only the minimum linked files needed for the current task.
- Use one task prompt from `ai/prompts/` to structure work.

## Execution Policy
- Prefer minimal context and focused edits.
- Verify with commands/tests/checks before completion.
- No speculative architecture edits.
- Record meaningful outcomes in:
  - `ai/logs/SESSION_LOG.md`
  - `ai/logs/CHANGELOG_AI.md` (when user-visible behavior changes)

## Truth Model
- Verified repository state > assumptions.
- If unknown: write `UNVERIFIED` + what to check next.
