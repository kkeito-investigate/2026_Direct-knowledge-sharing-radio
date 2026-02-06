# GitHub Projects Workspace (Best Practices)

This repo uses GitHub Projects (v2) as the workspace. The goal is to keep all preparation visible, searchable, and easy for agents to pick up.

## Recommended Fields
- Status: Backlog, In Prep, Ready, Presented, Archived
- Date (YYYY-MM-DD)
- Slot: Tue, Thu
- Theme: Basics, Tips, Trends, Tools
- Effort: S, M, L
- Owner
- Source: Internal, External
- Slide Link
- Recording Link

## Recommended Views
- This Week (Tue): filter Slot = Tue and Date in current week
- This Week (Thu): filter Slot = Thu and Date in current week
- Backlog: Status = Backlog
- In Prep: Status = In Prep
- Ready: Status = Ready
- History: Status = Presented or Archived

## Automation Rules
- Auto-add new issues and PRs from this repo to the Project
- Set Status = Backlog on item added
- When issue is closed, set Status = Archived

## Workflow
1. Create an issue with the "Session Proposal" form.
2. Triage and assign Date/Slot/Theme.
3. Move to In Prep when drafting starts.
4. Move to Ready when materials are finalized.
5. Move to Presented after the session.

## Notes
- Keep one issue per session.
- Use labels for quick search (examples below):
  - session
  - tip
  - trend
  - tool
