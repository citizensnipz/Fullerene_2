# Ownership Map

Purpose: define responsibility boundaries for safe, scoped changes.

## Domains
- `Project Direction`
  - Source: user/maintainer directives
  - Files: `ai/project/*`
- `Operational Practices`
  - Source: runbook/process maintainers
  - Files: `ai/operations/*`
- `Knowledge Curation`
  - Source: all contributors after verified work
  - Files: `ai/knowledge/*`
- `Session History`
  - Source: each meaningful AI/human work session
  - Files: `ai/logs/*`, `ai/retros/*`
- `Prompt Standards`
  - Source: workflow maintainers
  - Files: `ai/prompts/*`

## Change safety rules
- If touching multiple domains, state why in session log.
- No cross-domain rewrite without explicit instruction.
- Keep ownership map aligned with actual team practices.

## Contact/owner placeholders
- Primary owner: `UNVERIFIED`
- Secondary owner(s): `UNVERIFIED`
- Escalation path: `UNVERIFIED`
