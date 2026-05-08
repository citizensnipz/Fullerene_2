# Prompt: Explore

Use when understanding unfamiliar code/structure before proposing changes.

## Instructions to agent
1. Start at `ai/MEMORY.md`.
2. Load only files needed to answer the question.
3. Separate:
   - `VERIFIED facts`
   - `UNVERIFIED assumptions`
4. Produce:
   - Current understanding
   - Gaps and how to verify them
   - Minimal next actions

## Guardrails
- No blind edits.
- No architecture assumptions.
- No broad scans unless justified by task.

## Output format
- Goal
- Verified findings
- Unknowns
- Suggested next step (smallest useful step)
