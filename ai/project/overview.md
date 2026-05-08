# Project Overview - Fullerene

## One-line description
Fullerene is an experimental local-first cognitive architecture for LLM agents.

## Objectives
- Build a reusable cognitive substrate for AI agents.
- Preserve local-first behavior and controllability.
- Reduce repeated context loading through structured memory.
- Improve reliability via disciplined workflows and verification.

## Non-goals (until explicitly changed)
- Large-scale architecture rewrites without explicit direction
- Unverified assumptions about runtime, infra, or stack
- Premature optimization without measured evidence

## Current Scope (initial)
- Define/maintain AI harness structure under `/ai`
- Keep architectural, operational, and historical knowledge separated
- Support multi-tool agent usage (Claude, Codex, Cursor, others)

## Constraints
- Only verified repo facts should become project truth.
- Unknown details must be tracked as `UNVERIFIED`.
- Updates to this file should reflect decisions, not speculation.

## Open Questions
- Primary runtime and language stack: `UNVERIFIED`
- Current deployment model: `UNVERIFIED`
- Current persistence/data model: `UNVERIFIED`
- Auth/payment relevance in active product path: `UNVERIFIED`

## Update protocol
When scope changes:
1. Update this file.
2. Add decision entry in `ai/knowledge/decisions.md`.
3. Reflect operational impact in `ai/operations/*`.
