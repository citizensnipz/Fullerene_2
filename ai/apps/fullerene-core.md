# App: fullerene-core

## Purpose
Core subsystem for Fullerene's local-first cognitive architecture.

## Responsibilities
- Host/coordinate core cognitive architecture concepts.
- Provide stable place to document core patterns and constraints.
- Integrate with shared `/ai` memory system for multi-tool continuity.

## Boundaries
- Should not define unrelated product/UI concerns unless explicitly linked.
- Should not assume external infra unless verified.
- Architecture changes require explicit instruction + decision log.

## Known patterns (initial)
- Local-first orientation
- Memory-first workflow for AI tools
- Verification-before-completion discipline

## Unknowns / to verify
- Concrete runtime modules: `UNVERIFIED`
- Public interfaces: `UNVERIFIED`
- Persistence/sync strategy: `UNVERIFIED`
