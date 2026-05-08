# Prompt: Debug

Use when behavior is broken, inconsistent, or failing verification.

## Instructions to agent
1. Start with `ai/MEMORY.md` + relevant operations docs.
2. Reproduce issue (or clearly state why not reproducible).
3. Form 1-2 hypotheses max.
4. Test hypotheses with minimal changes.
5. Verify fix and document residual risk.

## Guardrails
- No speculative rewrites.
- No multiple simultaneous large edits.
- Preserve unrelated behavior.

## Required output
- Symptom
- Reproduction status
- Root cause (`VERIFIED`/`UNVERIFIED`)
- Fix scope
- Verification results
- Follow-up tasks
