---
schema: genesis-helpdesk-report/v1
schema_version: 1
report_date: 2026-11-03
figures_as_of: 2026-11-03T22:55:00+02:00
timezone: Africa/Johannesburg (SAST, +02:00)
language: en
period_start: 2026-10-22
working_days_to_date: 9
source: Genesis Helpdesk records (support posts, responses, Board moves) plus Board reads; test items excluded
refresh: nightly, every weekday evening; this file is overwritten in place and archived by date
url: https://morganphillipsamsquaredsystems.github.io/genesis-helpdesk-report/report.md
archive_url: https://morganphillipsamsquaredsystems.github.io/genesis-helpdesk-report/reports/2026-11-03.md
html_reports:
  en: https://morganphillipsamsquaredsystems.github.io/genesis-helpdesk-report/en/
images:
  en_today: https://morganphillipsamsquaredsystems.github.io/genesis-helpdesk-report/img/en-today.png
  en_to_date: https://morganphillipsamsquaredsystems.github.io/genesis-helpdesk-report/img/en-todate.png
board_status_values: ["1 -- Backlog", "2 -- Open", "3 -- In Progress", "4 -- Resolved", "5 -- Closed", "7 -- Maybe Later", "No Status"]
figures:
  intake_per_working_day: [6, 3, 6, 3, 2, 5, 2, 18, 5]
  resolved_per_working_day: [0, 3, 7, 2, 7, 3, 3, 20, 6]
  intake_today: 5
  resolved_today: 6
  intake_to_date: 50
  resolved_to_date: 51
  average_intake_per_day: 5.6
  capacity_lower_limit_per_day: 5.7
  capacity_confidence: low
automated_qa_status: on_hold
cards_listed: 15
release_notes_candidates: 4
---

# Genesis Helpdesk stats: 3 Nov 2026

Figures as of 3 Nov 2026, 22:55 SAST. Refreshed every weekday evening. Full dark report: https://morganphillipsamsquaredsystems.github.io/genesis-helpdesk-report/en/.

## Summary

- Today: Since last night midnight 5 Helpdesk tickets were created, 6 cards moved to Resolved, and 9 progress comments went to reporters.
- To date: Since the Helpdesk started on 22 Oct, 50 new tickets have been placed on the Board and 51 cards have moved to Resolved.
- Capacity: To date an average of 5.6 new tickets come in per working day, against 5.7 that are resolved, so the open work is slightly shrinking.
- Automated QA: QA stays deliberately on hold so it does not overwhelm dev capacity. Intake to date is 5.6 a day against the lower limit of 5.7.
- What to watch: Still Backlog: Stuart favourite, Dan docs, Dayalan Calendar, Danie plural-s, Sandra Whiteboard recurrence. In Progress updates went to Feed scrollbar, CSV thousand-sep, Timestamp format and Canvas field display. Cascade related-dropdowns is still Open (Status PUT 403) after an In Progress-style comment. Open load is 33.

## Today

Period: Tuesday 3 Nov 2026 · from last night 00:00 SAST.

| Measure | Value | Detail |
|:---|---:|:---|
| New tickets triaged | 5 | 2 bugs · 3 enhancements · cards created since last night midnight |
| First responses from the desk | 2 / 5 | Stuart and Dayalan · 3 handover (no desk first) |
| Outcome replies sent | 3 | Stuart · Dayalan · Forms dates (Morgan override) |
| Progress updates to reporters | 9 | Resolved 4 · In Progress 5 (incl. cascade comment) |
| Cards moved to Resolved | 6 | Resolved column 194 → 200 · no Closed moves |
| Satisfaction polls sent | 0 | none sent today |

### Response times (today)

Since last night midnight the desk first-contacted Stuart and Dayalan. Dan, Danie plural-s and Sandra were handover. Forms dates (last night's post) got an outcome reply this morning. Exact minute timings are not in the ledger.

| Measure | Median (min) | Average (min) | Number timed |
|:---|---:|---:|---:|
| First response (desk) | — | — | 2 (of 5) |
| Outcome / expert reply | — | — | 3 |

Two of five new tickets got a desk first contact (Stuart, Dayalan). Three were handover. Three outcome replies went out (Stuart, Dayalan, and Forms dates on Morgan's override). Minute timings are not on the ledger.

### New tickets by area (today)

| Area | New tickets |
|:---|---:|
| Navigation | 1 |
| Documents | 1 |
| Calendar | 1 |
| Relations | 1 |
| Whiteboard | 1 |

### Progress updates by status (today)

| Status | Updates |
|:---|---:|
| 2 -- Open | 0 |
| 3 -- In Progress | 5 |
| 4 -- Resolved | 4 |
| 7 -- Maybe Later | 0 |
| 1 -- Backlog | 0 |

### Expert review outcome (today)

| Outcome | Tickets | Detail |
|:---|---:|:---|
| Bug | 2 | Calendar create/open race · Whiteboard failed to save |
| Enhancement | 3 | favourite item · docs new tab · relation plural s |
| User error | 0 |  |

### By reporter (today)

| Reporter | New posts | Progress updates received |
|:---|---:|---:|
| Danie.Rheeders | 1 | 6 |
| Stuart | 1 | 0 |
| Dan | 1 | 0 |
| Dayalan | 1 | 0 |
| Sandra Dekker | 1 | 0 |
| Shelley | 0 | 2 |
| Gabriel Yssel | 0 | 1 |
| Leeroy Stander | 0 | 1 |

## To date

Period: 22 Oct to 3 Nov 2026 · 9 working days.

| Measure | Value | Detail |
|:---|---:|:---|
| Support posts handled | 38 | 31 on the 2 Nov file · 7 handled since last night midnight |
| New tickets (cards created) | 50 | 19 bugs · 10 enhancements · 2 not categorised · 1 user error |
| First responses sent | 20 | median 3.5 min historically (average 4.9, 12 timed) · 2 desk first contacts in this window |
| Expert / outcome answers sent | 19 | median 21 min historically · 3 outcome replies in this window |
| Progress updates to reporters | 52 | Open 3 · In Progress 18 · Resolved 19 · Maybe Later 11 · Backlog 1 |
| Cards moved to Resolved | 51 | Resolved column 149 → 200 |

### Response times (to date)

To date, the median first response time is 3.5 minutes (on posts the desk answered first).

| Measure | Median (min) | Average (min) | Number timed |
|:---|---:|---:|---:|
| First response | 3.5 | 4.9 | 15 (of 20) |
| Expert answer | 21 | 23.1 | 19 |

Two of five new tickets got a desk first contact (Stuart, Dayalan). Three were handover. Three outcome replies went out (Stuart, Dayalan, and Forms dates on Morgan's override). Minute timings are not on the ledger.

### New tickets by area (to date)

| Area | New tickets |
|:---|---:|
| Entity Table | 5 |
| Feed | 3 |
| Formulas / Formula Editor | 2 |
| Forms | 2 |
| Documents | 3 |
| List View | 2 |
| Navigation | 3 |
| Canvas View | 2 |
| Chart View | 1 |
| Board View | 1 |
| Rules | 1 |
| Dashboard | 1 |
| Fields | 1 |
| CSV Import | 1 |
| Workspaces | 1 |
| Calendar | 1 |
| Relations | 1 |
| Whiteboard | 1 |

### Progress updates by status (to date)

| Status | Updates |
|:---|---:|
| 2 -- Open | 3 |
| 3 -- In Progress | 18 |
| 4 -- Resolved | 19 |
| 7 -- Maybe Later | 11 |
| 1 -- Backlog | 1 |

### Expert review outcome (to date)

| Outcome | Tickets | Detail |
|:---|---:|:---|
| Bug | 15 | 4 with a workaround |
| Enhancement | 9 | 4 with a workaround |
| User error | 2 | answered with the correct steps |

### By reporter (to date)

| Reporter | New posts | Progress updates received |
|:---|---:|---:|
| Gabriel Yssel | 10 | 11 |
| Shelley | 7 | 9 |
| Morgan Phillips | 5 | 3 |
| Danie.Rheeders | 1 | 6 |
| Shells | 2 | 4 |
| Reinhardt Coetzee | 2 | 5 |
| Falynn Missing | 1 | 9 |
| Angelique Steyn | 1 | 6 |
| Leeroy Stander | 1 | 2 |
| Stuart | 1 | 0 |
| Dan | 1 | 0 |
| Dayalan | 1 | 0 |
| Sandra Dekker | 1 | 0 |
| June | 1 | 0 |

### Board, all columns

| Column | At start (22 Oct, cards) | Start of today (cards) | Now (cards) |
|:---|---:|---:|---:|
| Backlog | 18 | 15 | 14 |
| Open | 2 | 6 | 3 |
| In Progress | 6 | 8 | 16 |
| Resolved | 149 | 194 | 200 |
| Closed | 226 | 227 | 229 |
| Maybe Later | 24 | 24 | 24 |
| No Status | 4 | 8 | 9 |
| Total | 429 | 482 | 495 |

The whole Board, not only Helpdesk cards. Now is the 21:20 SAST board pass (Backlog 14, Open 3, In Progress 16, Resolved 200, Closed 229, Maybe Later 24, No Status 9). Start of today is last night midnight, using the 2 Nov 21:16 live counts (last snapshot before 00:00).

## Capacity

Team size: 6 developers.

### Today

Since last night midnight more went out than came in: 5 new tickets against 6 resolved cards, a net flow of -1.

| Measure | Team (6 developers) | Per developer |
|:---|---:|---:|
| New tickets | 5 | 0.83 |
| Resolved | 6 | 1.00 |
| Net flow (in minus resolved) | -1 · shrinking | not applicable |
| Open load (Backlog + Open + In Progress) | 33 | 5.5 |

Today is 1 working day, counted from last night midnight; open load is a snapshot of the whole Board, excluding test items.

### To date

To date an average of 5.6 new tickets come in per working day, against 5.7 that are resolved, so the open work is slightly shrinking.

| Measure | Team (6 developers) | Per developer |
|:---|---:|---:|
| New tickets per working day | 5.6 | 0.93 |
| Resolved per working day | 5.7 | 0.95 |
| Net flow (in minus resolved) | -1 · shrinking | not applicable |
| Open load (Backlog + Open + In Progress) | 33 | 5.5 |

9 working days (Thu 22 through Tue 3 Nov, weekends excluded); open load is a snapshot of the whole Board, excluding test items.

### New tickets against resolved cards per working day

| Working day | New tickets | Resolved |
|:---|---:|---:|
| Thu 22 Oct | 6 | 0 |
| Fri 23 Oct | 3 | 3 |
| Mon 26 Oct | 6 | 7 |
| Tue 27 Oct | 3 | 2 |
| Wed 28 Oct | 2 | 7 |
| Thu 29 Oct | 5 | 3 |
| Fri 30 Oct | 2 | 3 |
| Mon 2 Nov | 18 | 20 |
| Tue 3 Nov | 5 | 6 |

Resolved cards on 22 Oct count as 0, because tracking only began that evening.

### Lower-limit estimate

- Estimate: 5.7 new tickets a day the team can handle (0.95 per developer · confidence: low (51 resolved cards over 9 working days)).
- Method: The lower limit is the lower of the average resolution rate to date (51 resolved over 9 working days = 5.7) and the average over the last 3 working days (29 resolved over 30 Oct, 2 Nov and 3 Nov = 9.7). Because 22 Oct counts as 0, the estimate leans low rather than high.
- Warning: Intake is about 1.0 times the lower limit. If both rates hold, the open work stays about even (estimate).
- Analysis: The open pile went from 29 to 33 since last night midnight, because In Progress moved from 8 to 16 while 6 cards reached Resolved (column 194 → 200) and 5 Helpdesk tickets were created. At 5.7 a day, the current 33 open cards are about 5.8 working days of work, or about 5.5 cards per developer (estimate).

### Developer lanes on the Board

| Lane (Assigned To) | Cards in lane (created in the last 7 days) | Resolved cards before the start |
|:---|---:|---:|
| Ben Strachan | 3 | 25 |
| James Ashworth | 1 | 29 |
| Brandon Herselman | 5 | 24 |
| Reinhardt Coetzee | 5 | 20 |
| Almo Smith | 4 | 26 |
| Morgan Phillips | 3 | 11 |
| Not assigned (excluded) | 7 | 3 |

Lanes read at 18:32 SAST with a Created At filter (last 7 days) active; resolved cards per developer within the period are not available.

## Automated QA

Status: on hold (trial run).

The automated QA trial run on 26 Oct found two minor findings, both with a workaround; they remain on the Backlog.

The automated QA trial run on 26 Oct raised two minor findings, both with a workaround; they are 2 of the 50 new tickets to date, and one has since been reclassified as a feature request.

| QA ref | Card | Posted (SAST) | Status | Severity | Workaround | Update (SAST) |
|:---|:---|---:|:---|:---|:---|:---|
| SN-31 | Navigation: view page breadcrumb and tab title show the wrong space | 26 Oct 11:49 | Backlog | Bug · Medium (cosmetic) | Yes | 27 Oct 12:57 |
| LV-01 | List View: right-click on a group header shows no menu | 26 Oct 12:50 | Backlog | Enhancement · Medium (low impact) | Yes | 27 Oct 13:57 |

Both are Morgan Phillips's posts and are already included in the ticket counts on this page, not added on top.

QA stays deliberately on hold so it does not overwhelm dev capacity. Intake to date is 5.6 a day against the lower limit of 5.7.

## Cards

Cards that were created or updated today. Status is the Board column. A release-notes candidate is a card in 4 -- Resolved; area is the screen named at the start of the card title (the Board's Product Area field is not read here).

| Card | Type | Area | Status | Workaround | Reporter | New today | Resolved today | Release-notes candidate | QA ref | Note |
|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|
| Navigation: favourite a specific item instead of the whole view | Enhancement | Navigation | 1 -- Backlog | not recorded | Stuart | yes | no | no |  |  |
| Documents: open files in a new tab instead of downloading | Enhancement | Documents | 1 -- Backlog | not recorded | Dan | yes | no | no |  |  |
| Calendar: Personal Space create/open race | Bug | Calendar | 1 -- Backlog | not recorded | Dayalan | yes | no | no |  |  |
| Relations: default name adds a plural s | Enhancement | Relations | 1 -- Backlog | not recorded | Danie.Rheeders | yes | no | no |  |  |
| Whiteboard: failed to save (recurrence) | Bug | Whiteboard | 1 -- Backlog | not recorded | Sandra Dekker | yes | no | no |  |  |
| Derived query: mv-expand | Bug | Derived query | 4 -- Resolved | not recorded | Danie.Rheeders | no | yes | yes |  |  |
| List View: cannot add items from Details panel | Bug | List View | 4 -- Resolved | not recorded | Shelley | no | yes | yes |  |  |
| Navigation: empty folder cannot be deleted | Bug | Navigation | 4 -- Resolved | not recorded | Shelley | no | yes | yes |  |  |
| Entity Table: fill down a value like Excel | Bug | Entity Table | 4 -- Resolved | not recorded | Gabriel Yssel | no | yes | yes |  |  |
| Feed: long post no scrollbar | Bug | Feed | 3 -- In Progress | not recorded | Danie.Rheeders | no | no | no |  |  |
| CSV Import: thousand separator and decimal mishandled | Bug | CSV Import | 3 -- In Progress | not recorded | Danie.Rheeders | no | no | no |  |  |
| Derived query: Timestamp format | Bug | Derived query | 3 -- In Progress | not recorded | Danie.Rheeders | no | no | no |  |  |
| Canvas View: field display | Bug | Canvas View | 3 -- In Progress | not recorded | Leeroy Stander | no | no | no |  |  |
| Forms: dynamic filtering on related dropdowns | Enhancement | Forms | 2 -- Open | not recorded | Danie.Rheeders | no | no | no |  |  |
| Forms: cross-field date validation on start and end | Enhancement | Forms | 1 -- Backlog | not recorded | Danie.Rheeders | no | no | no |  |  |

## Data notes

- Source: Helpdesk daily log, reply-history and resolved-tracker for 3 Nov 2026, plus the 21:20 SAST Board pass. Today's window is 3 Nov 00:00 SAST (last night midnight) through 22:55 SAST — not the 10:25 morning triage. Period: 22 Oct to 3 Nov 2026 (9 working days). Test posts and test cards are excluded.
- Start of today is last night midnight, using the 2 Nov 21:16 live Board (Backlog 15, Open 6, In Progress 8, Resolved 194, Closed 227, Maybe Later 24, No Status 8, total 482). Now is the 21:20 pass (total 495). Resolved today is the column delta 194 → 200 (6). Intake today (5) is Helpdesk cards created since midnight, not the Board total delta (482 → 495). Named tables are rebuilt for this window.
- Test items are excluded from every count and table.
- Workaround is "not recorded" where the report has no workaround field for that card.
- Test items are excluded from every count and table.
- Workaround is "not recorded" where the report has no workaround field for that card.
- The Cards table lists the cards whose reporter got a progress update today; 4 of today's 6 moves to 4 -- Resolved are listed, and the rest had no reporter update, so their titles are not in this report.

## What to watch

Still Backlog: Stuart favourite, Dan docs, Dayalan Calendar, Danie plural-s, Sandra Whiteboard recurrence. In Progress updates went to Feed scrollbar, CSV thousand-sep, Timestamp format and Canvas field display. Cascade related-dropdowns is still Open (Status PUT 403) after an In Progress-style comment. Open load is 33.
