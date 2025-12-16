# Security Policy

## Scope
This is an educational repository and not a production service. There are no deployed systems tied to this code. The primary goal is learning and experimentation.

## Reporting
- Vulnerability reports are not required because the code is not shipped or hosted.
- If you still notice a security concern in the source, open a short issue describing the affected file and a minimal repro. Do **not** include secrets, tokens, or private data in reports.

## Secrets and private data
- No credentials, API keys, or proprietary datasets should be added to this repository.
- Before pushing, run a secret scan (e.g., GitGuardian CLI) and review the diff to ensure binaries, logs, and editor artifacts remain untracked.

## Dependencies
- Keep any future third-party libraries minimal. Favor standard C library facilities where possible.

## Safe handling
- Treat all inputs as untrusted when expanding these exercises. Add basic checks to avoid buffer overflows and undefined behavior while experimenting.
