# Incident Log (Process Memory)

We keep an explicit log of mistakes so the process improves over time.

## When to write an incident
- A repeated mistake happens
- A setup step fails due to unclear instructions
- The assistant runs into a predictable tool or auth issue

## Where to log
1. Create a GitHub issue using the "Incident / Mistake Log" template.
2. Add a short postmortem file under `incidents/` using `templates/incident.md`.

## Minimum content
- What happened
- Impact
- Root cause
- Fix / prevention

## Example file name
`2026-02-06_auth-refresh-timeout.md`
