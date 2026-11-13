---
schema: genesis-helpdesk-report/v1
schema_version: 1
report_date: 2026-11-13
figures_as_of: 2026-11-13T20:34:00+02:00
timezone: Africa/Johannesburg (SAST, +02:00)
language: en
period_start: 2026-10-22
working_days_to_date: 17
source: Genesis Helpdesk records (support posts, responses, Board moves) plus Board reads; test items excluded
refresh: nightly, every weekday evening; this file is overwritten in place and archived by date
url: https://morganphillipsamsquaredsystems.github.io/genesis-helpdesk-report/report.md
archive_url: https://morganphillipsamsquaredsystems.github.io/genesis-helpdesk-report/reports/2026-11-13.md
html_reports:
  en: https://morganphillipsamsquaredsystems.github.io/genesis-helpdesk-report/en/
images:
  en_today: https://morganphillipsamsquaredsystems.github.io/genesis-helpdesk-report/img/en-today.png
  en_to_date: https://morganphillipsamsquaredsystems.github.io/genesis-helpdesk-report/img/en-todate.png
board_status_values: ["1 -- Backlog", "2 -- Open", "3 -- In Progress", "4 -- Resolved", "5 -- Closed", "7 -- Maybe Later", "No Status"]
figures:
  intake_per_working_day: [6, 3, 6, 3, 2, 5, 2, 18, 5, 0, 3, 0, 0, 0, 0, 1, 2]
  resolved_per_working_day: [0, 3, 7, 2, 7, 3, 3, 20, 6, 0, 12, 0, 0, 0, 11, 1, 15]
  intake_today: 2
  resolved_today: 15
  intake_to_date: 56
  resolved_to_date: 90
  average_intake_per_day: 3.3
  capacity_lower_limit_per_day: 5.3
  capacity_confidence: low
automated_qa_status: on_hold
cards_listed: 2
release_notes_candidates: 1
---

# Genesis Helpdesk stats: 13 Nov 2026

Figures as of 13 Nov 2026, 20:34 SAST. Refreshed every weekday evening. Full dark report: https://morganphillipsamsquaredsystems.github.io/genesis-helpdesk-report/en/.

## Summary

- Today: Live board: 2 cards created today; Resolved column 224 → 239 (15 moves). Open load 23 (Backlog 2, Open 3, In Progress 18).
- To date: Since 22 Oct, 56 new tickets and 90 cards to Resolved across 17 working days.
- Capacity: To date average intake 3.3/day vs lower limit 5.3/day, so the open work is shrinking.
- Automated QA: QA stays deliberately on hold so it does not overwhelm dev capacity. Intake to date is 5.6 a day against the lower limit of 5.7.
- What to watch: New cards today: Client documentation and catalog templates integration (In Progress); Jenkins: Genesis Cowboy workflow (Resolved). Open load 23. HOLD is clear.

## Today

Period: Friday 13 Nov 2026.

| Measure | Value | Detail |
|:---|---:|:---|
| Cards created today | 2 | Issues cards whose createdAt falls on this SAST day. Read from the full board, not the unassigned queue. |
| First responses posted | 0 | No desk first-contact lines on reply-history for this SAST day. |
| Outcome replies posted | 0 | Outcome replies the desk posted. Drafts still proposed are not counted. |
| Progress comments posted | 0 | Progress comments the desk posted on a reporter's thread. A card's updatedAt is not a comment. |
| Cards moved to Resolved | 15 | Resolved column 224 → 239. Includes board moves, not only cards created today. |
| Satisfaction polls sent | 0 | none recorded on the snapshot today |

### Response times (today)

No desk first-contact or outcome replies on reply-history for 13 Nov. Minute timings are not on the ledger.

| Measure | Median (min) | Average (min) | Number timed |
|:---|---:|---:|---:|
| First response (desk) | — | — | not timed |
| Outcome / expert reply | — | — | not timed |

Median and average minutes are left blank. The snapshot has no first-seen clock, so a timing would be invented.

### New tickets by area (today)

| Area | New tickets |
|:---|---:|
| Client documentation and catalog templates integration | 1 |
| Jenkins | 1 |

### Progress updates by status (today)

| Status | Updates |
|:---|---:|
| 2 -- Open | 0 |
| 3 -- In Progress | 0 |
| 4 -- Resolved | 0 |
| 7 -- Maybe Later | 0 |
| 1 -- Backlog | 0 |

### Expert review outcome (today)

| Outcome | Tickets | Detail |
|:---|---:|:---|
| Bug | 1 |  |
| Not categorised | 1 |  |

### By reporter (today)

| Reporter | New posts | Progress updates received |
|:---|---:|---:|

## To date

Period: 22 to 13 Nov 2026 · 17 working days.

| Measure | Value | Detail |
|:---|---:|:---|
| Support posts handled | 38 | 31 on the 2 Nov file · 7 handled since last night midnight |
| New tickets (cards created) | 56 | 19 bugs · 10 enhancements · 2 not categorised · 1 user error |
| First responses sent | 20 | median 3.5 min historically (average 4.9, 12 timed) · 2 desk first contacts in this window |
| Expert / outcome answers sent | 19 | median 21 min historically · 3 outcome replies in this window |
| Progress updates to reporters | 52 | Open 3 · In Progress 18 · Resolved 19 · Maybe Later 11 · Backlog 1 |
| Cards moved to Resolved | 90 | Resolved column 149 → 200 |

### Response times (to date)

To date, the median first response time is 3.5 minutes (on posts the desk answered first).

| Measure | Median (min) | Average (min) | Number timed |
|:---|---:|---:|---:|
| First response | 3.5 | 4.9 | 15 (of 20) |
| Expert answer | 21 | 23.1 | 19 |

Median and average minutes are left blank. The snapshot has no first-seen clock, so a timing would be invented.

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
| Backlog | 18 | 8 | 2 |
| Open | 2 | 4 | 3 |
| In Progress | 6 | 12 | 18 |
| Resolved | 149 | 224 | 239 |
| Closed | 226 | 229 | 262 |
| Maybe Later | 24 | 24 | 27 |
| No Status | 4 | 11 | 11 |
| Total | 429 | 512 | 562 |

Now is the live Board read at 20:34 SAST on 13 Nov 2026 (Backlog 2, Open 3, In Progress 18, Resolved 239, Maybe Later 27, Closed 262). Start of today is the previous file's Now column.

## Capacity

Team size: 6 developers.

### Today

Today 2 in vs 15 resolved, net -13. Lower limit 5.3/day.

| Measure | Team (6 developers) | Per developer |
|:---|---:|---:|
| New tickets | 2 | 0.33 |
| Resolved | 15 | 2.50 |
| Net flow (in minus resolved) | -13 · shrinking | not applicable |
| Open load (Backlog + Open + In Progress) | 23 | 3.8 |

Today is 1 working day, counted from last night midnight; open load is a snapshot of the whole Board, excluding test items.

### To date

To date average intake 3.3/day vs lower limit 5.3/day, so the open work is shrinking.

| Measure | Team (6 developers) | Per developer |
|:---|---:|---:|
| New tickets per working day | 3.3 | 0.55 |
| Resolved per working day | 5.3 | 0.88 |
| Net flow (in minus resolved) | -34 · shrinking | not applicable |
| Open load (Backlog + Open + In Progress) | 23 | 3.8 |

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
| Wed 4 Nov | 0 | 0 |
| Thu 5 Nov | 3 | 12 |
| Fri 6 Nov | 0 | 0 |
| Mon 9 Nov | 0 | 0 |
| Tue 10 Nov | 0 | 0 |
| Wed 11 Nov | 0 | 11 |
| Thu 12 Nov | 1 | 1 |
| Fri 13 Nov | 2 | 15 |

Resolved cards on 22 Oct count as 0, because tracking only began that evening.

### Lower-limit estimate

- Estimate: 5.3 new tickets a day the team can handle (0.95 per developer · confidence: low (51 resolved cards over 9 working days)).
- Method: The lower limit is the lower of the average resolution rate to date (51 resolved over 9 working days = 5.7) and the average over the last 3 working days (29 resolved over 30 Oct, 2 Nov and 3 Nov = 9.7). Because 22 Oct counts as 0, the estimate leans low rather than high.
- Warning: Intake is about 1.0 times the lower limit. If both rates hold, the open work stays about even (estimate).
- Analysis: Catch-up evening report from live Issues board + ledger roll-forward (Nov 5 baseline, Nov 11–12 Stage 10 catch-up). Quiet desk Feed day; board Resolved stock rose 15. Open work is shrinking versus the 5.3/day lower limit.

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

Automated QA stays on hold.

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
| Client documentation and catalog templates integration | Bug | Not recorded | 3 -- In Progress | not recorded | — | yes | no | no |  |  |
| Jenkins: Genesis Cowboy workflow | Not categorised | Jenkins | 4 -- Resolved | not recorded | — | yes | no | yes |  |  |

## Data notes

- Source: the full Issues board at 20:34 SAST on 13 Nov 2026 (562 cards). New tickets are cards created today. Replies are desk posts with HTTP 200. Drafts are not counted.
- Start of today on the Board table is the previous file's Now column. Now is the live column count. A falling column is not rewritten as zero tickets. Named tables list cards created today. Cards that were only edited are omitted.
- Test items are excluded from every count and table.
- Workaround is "not recorded" where the report has no workaround field for that card.
- Test items are excluded from every count and table.
- Workaround is "not recorded" where the report has no workaround field for that card.
- The Cards table lists the cards whose reporter got a progress update today; 0 of today's 15 moves to 4 -- Resolved are listed, and the rest had no reporter update, so their titles are not in this report.

## What to watch

New cards today: Client documentation and catalog templates integration (In Progress); Jenkins: Genesis Cowboy workflow (Resolved). Open load 23. HOLD is clear.
