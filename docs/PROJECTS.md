# GitHub Projects Workspace (Best Practices)

This repo uses GitHub Projects (v2) as the workspace. The goal is to keep all preparation visible, searchable, and easy for agents to pick up.

## Recommended Fields
- Phase: Backlog, In Prep, Ready, Presented, Archived
- Date (YYYY-MM-DD)
- Slot: Tue, Thu
- Theme: Basics, Tips, Trends, Tools
- Effort: S, M, L
- Type: Session, Tip, Trend, Incident
- Source: Internal, External
- Slide Link
- Recording Link

## Recommended Views
- This Week (Tue): filter Slot = Tue and Date in current week
- This Week (Thu): filter Slot = Thu and Date in current week
- Backlog: Phase = Backlog
- In Prep: Phase = In Prep
- Ready: Phase = Ready
- History: Phase = Presented or Archived
- Incidents: Type = Incident

## Manual UI Setup (once)
1. Create a Board view grouped by `Phase`.
2. Hide the default `Status` field from the view.
3. Add a Table view with columns: Title, Phase, Date, Slot, Theme, Type, Effort.

## Automation Rules
- Auto-add new issues and PRs from this repo to the Project
- Set Phase = Backlog on item added
- When issue is closed, set Phase = Archived

## Workflow
1. Create an issue with the "Session Proposal" form.
2. Triage and assign Date/Slot/Theme/Type.
3. Move Phase to In Prep when drafting starts.
4. Move Phase to Ready when materials are finalized.
5. Move Phase to Presented after the session.

## Notes
- Keep one issue per session.
- Use the `Phase` field for Kanban grouping (leave default `Status` as-is).
- Use labels for quick search (examples below):
  - session
  - tip
  - trend
  - tool
  - incident
