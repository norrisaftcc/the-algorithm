# SUBCONTRACT — PROJECT #25 LIVE TRACKING

Status: proposal at a GREEN gate. Not frozen. Nothing runs from this file.
Target: GitHub Project #25 → `norrisaftcc/the-algorithm`.
Clearance: GREEN.

## The seating

| Item | Value |
|---|---|
| Seat | the maintainer who configures Project #25 — a clerk of the works |
| Clearance | inherited from the spawner at seating, never computed here |
| Capabilities | enable and configure Project #25 built-in workflows; touch no repo file |
| N | 0. This seat configures settings and spawns nothing. |
| Escalation route | BLUE. |

The spawner assigns the seat at freeze. This file names the role, not the person.
Spawners assign; seats inherit.

## What this subcontract does

The board tracks the repository. The board reads repository state. The board never writes
to the repository.

Auto-add places each new issue and each new pull request on the board. Status sync moves
each item as its state changes. Both are add-and-report actions. Neither rewrites repository
content.

The board is an external record, like the Scribe's transcript. Git stays the repository's
only automation.

## The four floor nouns

- Audience: the maintainer who toggles the settings, and every board viewer who reads repository state.
- Scope: the built-in workflows below, filtered to `norrisaftcc/the-algorithm`; issues and pull requests; add and set status; no repo file.
- Format: an ordered configuration procedure, plus this proposal document.
- Path: this proposal at `docs/green/subcontract-project25-live-tracking.md`. Execution writes no repository file.

## The contract

Warning: the auto-add workflow adds every matching item. Confirm the filter before you enable it.

```
# Wire Project #25 to live-track this repository

1. Open Project #25. Go to Settings, then Workflows.
2. Enable "Auto-add to project". Set the repository to norrisaftcc/the-algorithm.
3. Set the filter to `is:open`. This adds new issues and new pull requests.
4. Enable "Item added to project". Set Status to Todo.
5. Enable "Item reopened". Set Status to Todo.
6. Enable "Item closed". Set Status to Done.
7. Enable "Pull request merged". Set Status to Done.
8. Save each workflow.
9. Capture the Workflows view as evidence.
```

Cut: the committed workflow file and the access token. The built-in workflows need neither.

## Evidence

The toggles live in Project settings, outside git. The merge of this file witnesses the
authorization, not the result.

Capture the Workflows view after execution. A claim without that capture scores as unrun,
per K6.

## Open, before this subcontract can be frozen

- Confirm Project #25 has a Status single-select field. Enumerate its option names. This proposal assumes Todo and Done.
- Confirm the seat holder is Teacherbot-GREEN and owns Project #25.
- Decide the archive policy. Auto-archive closed items after a set period, or keep them on the board.
- Decide whether issues and pull requests share one Status set, or split.
- Decide backfill. Add the five open issues (#2, #9, #11, #12, #15) once, or track new items only.
- Decide the optional review workflows. Set Status on approval and on changes requested, or leave them off.

Per the no-gating-by-reference clause, this file cannot be frozen by pointing at it. When the
configuration is ready to run, the contract appears in full, in the message, above the
question.

Thank you for your cooperation.
