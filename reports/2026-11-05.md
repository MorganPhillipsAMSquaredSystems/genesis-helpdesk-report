---
schema: genesis-helpdesk-report/v1
schema_version: 1
report_date: 2026-11-05
figures_as_of: 2026-11-05T18:50:00+02:00
timezone: Africa/Johannesburg (SAST, +02:00)
language: en
period_start: 2026-10-22
working_days_to_date: 11
source: Genesis Helpdesk records (support posts, responses, Board moves) plus Board reads; test items excluded
refresh: nightly, every weekday evening; this file is overwritten in place and archived by date
url: https://morganphillipsamsquaredsystems.github.io/genesis-helpdesk-report/report.md
archive_url: https://morganphillipsamsquaredsystems.github.io/genesis-helpdesk-report/reports/2026-11-05.md
html_reports:
  en: https://morganphillipsamsquaredsystems.github.io/genesis-helpdesk-report/en/
images:
  en_today: https://morganphillipsamsquaredsystems.github.io/genesis-helpdesk-report/img/en-today.png
  en_to_date: https://morganphillipsamsquaredsystems.github.io/genesis-helpdesk-report/img/en-todate.png
board_status_values: ["1 -- Backlog", "2 -- Open", "3 -- In Progress", "4 -- Resolved", "5 -- Closed", "7 -- Maybe Later", "No Status"]
figures:
  intake_per_working_day: [6, 3, 6, 3, 2, 5, 2, 18, 5, 0, 3]
  resolved_per_working_day: [0, 3, 7, 2, 7, 3, 3, 20, 6, 0, 12]
  intake_today: 3
  resolved_today: 12
  intake_to_date: 53
  resolved_to_date: 63
  average_intake_per_day: 4.8
  capacity_lower_limit_per_day: 5.7
  capacity_confidence: low
automated_qa_status: on_hold
cards_listed: 9
release_notes_candidates: 1
publish_note: Agent-readable Markdown published 5 Nov evening from Cursor ledgers. Dark HTML/PNG Pages were not rebuilt (report-html publish.sh not on this machine); en/ may still show 3 Nov until the box nightly runs.
---

# Genesis Helpdesk stats: 5 Nov 2026

Figures as of 5 Nov 2026, 18:50 SAST. Refreshed every weekday evening. Full dark report: https://morganphillipsamsquaredsystems.github.io/genesis-helpdesk-report/en/ (HTML may lag until box publish).

## Summary

- Today: Since last night midnight 3 Helpdesk tickets were created (all bugs), 12 cards moved to Resolved (column 200 → 212), and 1 desk Stage 10 progress comment went to a reporter.
- To date: Since the Helpdesk started on 22 Oct, 53 new tickets have been placed on the Board and 63 cards have moved to Resolved.
- Capacity: To date an average of 4.8 new tickets come in per working day, against 5.7 that are resolved, so the open work is shrinking.
- Automated QA: QA stays deliberately on hold so it does not overwhelm dev capacity. Intake to date is 4.8 a day against the lower limit of 5.7.
- What to watch: New Backlog today — Danie multi-join virtual relation, Gabriel derived number/date display settings, Shelley new fields on existing views (High / urgent). Earlier leftovers still Backlog: Stuart favourite, Dan docs, Dayalan Calendar, Danie plural-s, Sandra Whiteboard recurrence. Open load is 24. HOLD active from 18:24 (Morgan pause).

## Today

Period: Thursday 5 Nov 2026 · from last night 00:00 SAST.

| Measure | Value | Detail |
|:---|---:|:---|
| New tickets triaged | 3 | 3 bugs · 0 enhancements · cards created since last night midnight |
| First responses from the desk | 3 / 3 | Danie · Gabriel · Shelley |
| Outcome replies sent | 3 | same three (second contact) |
| Progress updates to reporters | 1 | Resolved 1 (Shelley Mim) · no desk Stage 10 guessed from other Resolved deltas |
| Cards moved to Resolved | 12 | Resolved column 200 → 212 · no Closed moves |
| Satisfaction polls sent | 0 | none sent today |

### Response times (today)

All three new tickets got desk first contact and second contact the same pass. Exact minute timings are not in the ledger.

| Measure | Median (min) | Average (min) | Number timed |
|:---|---:|---:|---:|
| First response (desk) | — | — | 3 (of 3) |
| Outcome / expert reply | — | — | 3 |

### New tickets by area (today)

| Area | New tickets |
|:---|---:|
| Entity Table / derived | 2 |
| Detail View | 1 |

### Progress updates by status (today)

| Status | Updates |
|:---|---:|
| 2 -- Open | 0 |
| 3 -- In Progress | 0 |
| 4 -- Resolved | 1 |
| 7 -- Maybe Later | 0 |
| 1 -- Backlog | 0 |

### Expert review outcome (today)

| Outcome | Tickets | Detail |
|:---|---:|:---|
| Bug | 3 | multi-join virtual · derived display settings · new fields on existing views |
| Enhancement | 0 |  |
| User error | 0 |  |

### By reporter (today)

| Reporter | New posts | Progress updates received |
|:---|---:|---:|
| Danie.Rheeders | 1 | 0 |
| Gabriel Yssel | 1 | 0 |
| Shelley | 1 | 1 |

### New tickets today

| Reporter | Card | Type | Current stage |
|:---|:---|:---|:---|
| Danie.Rheeders | Derived / virtual: multi-join relation (71d2a46c) | Bug | 1 -- Backlog |
| Gabriel Yssel | Entity Table: derived fields hide number and date display settings (337a2bac) | Bug | 1 -- Backlog |
| Shelley | Detail View: new fields are added to existing views (f5c659af) | Bug · High | 1 -- Backlog |

Assigned To empty on all three. Product Area left empty (field missing on Issues definition).

### Progress updates today

| Reporter | Card | Type | Status |
|:---|:---|:---|:---|
| Shelley | Mim / related Resolved note (92767176) | Bug | 4 -- Resolved |

Board Resolved also rose for other-team cards (Jenkins stack, Adapter error, Jenkins image noted in the 14:15 pass). Column history is not stored, so no extra Stage 10 was invented from count deltas.

## To date

Period: 22 Oct to 5 Nov 2026 · 11 working days (Wed 4 Nov quiet: 0 intake, 0 resolved).

| Measure | Value |
|:---|---:|
| New tickets | 53 |
| Cards moved to Resolved | 63 |
| Average intake / working day | 4.8 |
| Average resolved / working day | 5.7 |
| Open load (Backlog + Open + In Progress) | 24 |

### Board, all columns

| Column | At start (22 Oct) | Start of today (midnight) | Now (14:15 pass) |
|:---|---:|---:|---:|
| Backlog | 18 | 14 | 8 |
| Open | 2 | 3 | 4 |
| In Progress | 6 | 16 | 12 |
| Resolved | 149 | 200 | 212 |
| Closed | 226 | 229 | 229 |
| Maybe Later | 24 | 24 | 24 |
| No Status | 4 | 9 | 11 |
| Total | 429 | 495 | 500 |

Start of today = 4 Nov close / 3 Nov 21:20 live counts (Board unchanged all of 4 Nov). Now = 5 Nov 14:15 Unassigned+board pass. Closed unchanged today.

## Capacity

Since last night midnight more went out than came in: 3 new tickets against 12 resolved cards, a net flow of -9.

| Measure | Team (6 developers) | Per developer |
|:---|---:|---:|
| New tickets | 3 | 0.50 |
| Resolved | 12 | 2.00 |
| Net flow (in minus resolved) | -9 · shrinking | not applicable |
| Open load (Backlog + Open + In Progress) | 24 | 4.0 |

Lower limit manageable new tickets/day = 5.7 (lower of to-date resolution rate 63/11 and last-3-working-day rate (6+0+12)/3 = 6). Confidence: low.

The open pile went from 33 to 24 since last night midnight. At 5.7 a day, 24 open cards are about 4.2 working days of work, or about 4.0 cards per developer (estimate).

## Automated QA (trial run) On hold

QA stays on hold; no new QA findings since last night midnight.

| Card | Posted (SAST) | Status | Severity | Workaround | Update (SAST) |
|:---|:---|:---|:---|:---|:---|
| Navigation: view page breadcrumb and tab title show the wrong space | 26 Oct 11:49 | Backlog | Bug · Medium (cosmetic) | Yes | 27 Oct 12:57 |
| List View: right-click on a group header shows no menu | 26 Oct 12:50 | Backlog | Enhancement · Medium (low impact) | Yes | 27 Oct 13:57 |

## Cards (release glance)

| Card | Type | Area | Status | Workaround | Reporter | New today | Resolved today | Release-notes candidate | QA ref | Note |
|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|
| Derived / virtual: multi-join relation | Bug | Entity Table | 1 -- Backlog | not recorded | Danie.Rheeders | yes | no | no |  | 71d2a46c |
| Entity Table: derived fields hide number and date display settings | Bug | Entity Table | 1 -- Backlog | not recorded | Gabriel Yssel | yes | no | no |  | 337a2bac |
| Detail View: new fields are added to existing views | Bug | Detail View | 1 -- Backlog | not recorded | Shelley | yes | no | no |  | f5c659af · High |
| Mim related (92767176) | Bug | Forms / Mim | 4 -- Resolved | not recorded | Shelley | no | yes | yes |  | desk Stage 10 |
| Navigation: favourite a specific item instead of the whole view | Enhancement | Navigation | 1 -- Backlog | not recorded | Stuart | no | no | no |  | leftover |
| Documents: open files in a new tab instead of downloading | Enhancement | Documents | 1 -- Backlog | not recorded | Dan | no | no | no |  | leftover |
| Calendar: Personal Space create/open race | Bug | Calendar | 1 -- Backlog | not recorded | Dayalan | no | no | no |  | leftover |
| Relations: default name adds a plural s | Enhancement | Relations | 1 -- Backlog | not recorded | Danie.Rheeders | no | no | no |  | leftover |
| Whiteboard: failed to save (recurrence) | Bug | Whiteboard | 1 -- Backlog | not recorded | Sandra Dekker | no | no | no |  | leftover |

## Data notes

Source: Helpdesk daily log and reply-history for 5 Nov 2026 (08:40, 11:50, 14:15 passes), plus 4 Nov quiet board (unchanged at B14 O3 IP16 R200 C229 ML24 NS9 total 495). Today's window is 5 Nov 00:00 SAST through 18:50 SAST. Period: 22 Oct to 5 Nov 2026 (11 working days). Test posts and test cards are excluded.

Intake today (3) is Helpdesk cards created since midnight, not the Board total delta (495 → 500). Resolved today is the column delta 200 → 212 (12). Desk Stage 10 posted only for Shelley Mim; other Resolved moves were not given invented Feed updates (column history not stored).

HOLD: Morgan set STATE active at 18:24 — pause triage until he says run triage / clear HOLD.

## What to watch

Still / new Backlog: Danie multi-join virtual, Gabriel derived display settings, Shelley new fields on existing views (High), Stuart favourite, Dan docs, Dayalan Calendar, Danie plural-s, Sandra Whiteboard recurrence. Open load 24. HOLD active since 18:24.
