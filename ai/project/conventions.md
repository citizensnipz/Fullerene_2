# Project Conventions

## Workflow conventions
- Start from `ai/MEMORY.md`.
- Load only relevant files to reduce token usage.
- Use appropriate prompt from `ai/prompts/`.
- Make smallest useful change first.

## Change conventions
- Prefer scoped commits/patches.
- Avoid mixed concerns in one change.
- Do not refactor unrelated code opportunistically.
- Record meaningful updates in logs + memory docs.

## Verification conventions
- No completion claim without executed checks.
- Map checks to change type:
  - docs-only: link/structure sanity
  - code changes: tests/lint/build as applicable
  - ops changes: command/runbook validation where possible
- If checks cannot run, state exactly why and what remains.

## Knowledge conventions
- Use `VERIFIED` vs `UNVERIFIED` labels explicitly.
- Timestamp major updates (YYYY-MM-DD).
- Keep decisions in `ai/knowledge/decisions.md`.
- Keep known defects in `ai/knowledge/known-issues.md`.

## Language conventions for AI notes
- Prefer concise bullets over long prose.
- Avoid ambiguous claims.
- Include clear next actions when unresolved.
