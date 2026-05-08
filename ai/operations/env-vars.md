# Environment Variables

Document only variables that are confirmed in runtime/config.

## Template entry format
- `NAME`
  - Required: `yes/no`
  - Default: `<value or none>`
  - Scope: `local/dev/staging/prod`
  - Secret: `yes/no`
  - Used by: `<service or module>`
  - Purpose: `<short description>`
  - Validation: `<format/range>`
  - Source of truth: `<file/path>`

## Current status
No verified env var inventory yet.

## Next action
- Extract from config files and startup scripts.
- Mark each as `VERIFIED` only after source confirmation.
