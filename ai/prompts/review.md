# Prompt: Review

Use for code/design/ops review with risk-first analysis.

## Instructions to agent
1. Load `ai/MEMORY.md` and targeted docs/code context.
2. Review for:
   - correctness risks
   - regression risks
   - missing verification
   - boundary violations
3. Report findings by severity.
4. Recommend minimal corrective actions.

## Guardrails
- No style-only nitpicks unless requested.
- No assumptions beyond verified context.
- Distinguish facts from uncertainty.

## Output format
- Findings (high -> low)
- Open questions/assumptions
- Suggested fixes
- Verification gaps
