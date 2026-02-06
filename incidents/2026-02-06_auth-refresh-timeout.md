# Incident: gh auth refresh timed out

- Date: 2026-02-06
- Owner: assistant
- Related issue: (create if needed)

## Summary
`gh auth refresh` timed out multiple times because device-code verification required user action outside the CLI, and the command was retried without an interactive handoff.

## Impact
Project setup was delayed and required manual intervention from the user.

## Root Cause
The process assumed the CLI refresh could be completed without a clear handoff step, despite the device flow being non-interactive in this environment.

## Fix / Prevention
- In future, ask the user to run the refresh locally once and confirm completion before retrying.
- Document the expected device-code flow in the incident log and operating guidance.

## Follow-ups
- [ ] Keep a short runbook entry for auth refresh in `docs/PROJECTS.md` if it becomes common
