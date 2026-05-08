# Prompt: Implement

Use for feature work or scoped improvements.

## Instructions to agent
1. Load `ai/MEMORY.md` and only relevant linked files.
2. Restate task boundaries in bullets.
3. Plan smallest viable change set.
4. Implement incrementally.
5. Verify before completion.
6. Update harness logs/knowledge.

## Non-negotiables
- Small, scoped edits.
- No architecture rewrite without explicit instruction.
- No guessing; mark unknowns as `UNVERIFIED`.
- Include exact verification evidence.

## Completion checklist
- [ ] Requirements addressed
- [ ] Verification run
- [ ] Session log updated
- [ ] Changelog updated (if behavior changed)
- [ ] Relevant memory docs updated
