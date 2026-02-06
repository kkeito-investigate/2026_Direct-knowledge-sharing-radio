# 2026 Direct Knowledge Sharing (AI)

Weekly AI knowledge sharing for executives.

## Schedule
- Tuesdays: AI development basics ("iroha")
- Thursdays: tips and general trends

First session: 2026-02-10 (Tue)

## How We Manage Work (GitHub Projects)
We use GitHub Projects (v2) as the single workspace for ideas, preparation, and delivery.
See `docs/PROJECTS.md` for the recommended fields, views, and automation.

## Repo Structure (Assets)
- `sessions/`: per-session materials (outline, slides draft, script, references)
- `templates/`: reusable templates
- `assets/`: shared images or snippets
- `runs/`: agent outputs and intermediate drafts
- `docs/`: operating rules and guidance
- `incidents/`: postmortems for mistakes to prevent repeats

## Quick Start
1. Create a new issue using the "Session Proposal" template.
2. Manage the issue in GitHub Projects.
3. When confirmed, create a session folder under `sessions/tue/` or `sessions/thu/`.
4. Use `templates/session/` to start drafting materials.

## Conventions
- Session folder name: `YYYY-MM-DD_topic`
- All sources go into `references.md` (per session)
- Large files stay outside GitHub; store a link + hash
 - Log mistakes in `docs/INCIDENTS.md` and `incidents/`
