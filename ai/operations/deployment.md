# Deployment Runbook

## Goal
Define repeatable deployment/release procedure with rollback guidance.

## Current status
Deployment pipeline details are `UNVERIFIED`.

## Required sections to fill
- Environments (dev/staging/prod)
- Build/package steps
- Release trigger method
- Health checks after deploy
- Rollback steps
- Incident escalation path

## Template
1. Preconditions
2. Deploy steps
3. Verification steps
4. Rollback steps
5. Post-deploy logging updates

## Rule
No deploy completion claim without post-deploy verification evidence.
