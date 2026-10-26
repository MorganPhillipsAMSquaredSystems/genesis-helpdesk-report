---
schema: genesis-helpdesk-report/v1
schema_version: 1
report_date: 2026-10-26
figures_as_of: 2026-10-26T19:20:00+02:00
timezone: Africa/Johannesburg (SAST, +02:00)
language: en
period_start: 2026-10-22
working_days_to_date: 3
source: Genesis Helpdesk records (support posts, responses, Board moves) plus Board reads; test items excluded
refresh: nightly, every weekday evening; this file is overwritten in place and archived by date
url: https://morganphillipsamsquaredsystems.github.io/genesis-helpdesk-report/report.md
archive_url: https://morganphillipsamsquaredsystems.github.io/genesis-helpdesk-report/reports/2026-10-26.md
html_reports:
  en: https://morganphillipsamsquaredsystems.github.io/genesis-helpdesk-report/en/
  af: https://morganphillipsamsquaredsystems.github.io/genesis-helpdesk-report/af/
images:
  en_today: https://morganphillipsamsquaredsystems.github.io/genesis-helpdesk-report/img/en-today.png
  en_to_date: https://morganphillipsamsquaredsystems.github.io/genesis-helpdesk-report/img/en-todate.png
  af_today: https://morganphillipsamsquaredsystems.github.io/genesis-helpdesk-report/img/af-today.png
  af_to_date: https://morganphillipsamsquaredsystems.github.io/genesis-helpdesk-report/img/af-todate.png
board_status_values: ["1 -- Backlog", "2 -- Open", "3 -- In Progress", "4 -- Resolved", "5 -- Closed", "7 -- Maybe Later", "No Status"]
figures:
  intake_per_working_day: [6, 3, 6]
  resolved_per_working_day: [0, 3, 7]
  intake_today: 6
  resolved_today: 7
  intake_to_date: 15
  resolved_to_date: 10
  average_intake_per_day: 5.0
  capacity_lower_limit_per_day: 3.3
  capacity_confidence: low
automated_qa_status: on_hold
cards_listed: 14
release_notes_candidates: 6
---

# Genesis Helpdesk stats: 26 Oct 2026

Figures as of 26 Oct 2026, 19:20 SAST. Refreshed every weekday evening. Full dark reports: English https://morganphillipsamsquaredsystems.github.io/genesis-helpdesk-report/en/ and Afrikaans https://morganphillipsamsquaredsystems.github.io/genesis-helpdesk-report/af/.

## Summary

- Today: Today 6 new tickets were triaged and each one received a first response and an expert answer, while 7 cards moved to Resolved.
- To date: Since the Helpdesk started on 22 Oct, 17 posts have been handled, 15 new tickets have been placed on the Board and 10 cards have moved to Resolved.
- Capacity: To date an average of 5.0 new tickets come in per working day, against 3.3 that are resolved, so the open work is growing.
- Automated QA: The QA process worked end to end and is now deliberately on hold, because intake of 5.0 a day is already above the lower limit of 3.3 (see Capacity above). Without the QA bugs, intake to date would have been 13 (4.3 per working day).
- What to watch: Whether the resolution rate keeps up with intake of about 5 tickets a day, and the self-relations theme in the Entity Table.

## Today

Period: Monday 26 Oct 2026.

| Measure | Value | Detail |
|:---|---:|:---|
| New tickets triaged | 6 | 4 bugs · 2 enhancements |
| First responses sent | 6 / 6 | median 2.5 min after the post was seen (average 2.8) |
| Expert answers sent | 6 / 6 | median 15.5 min after the post was seen (average 21.5) |
| Progress updates to reporters | 10 | 6 Resolved · 4 In Progress |
| Cards moved to Resolved | 7 | plus 1 moved to Closed |
| Satisfaction polls sent | 2 | no replies yet |

### Response times (today)

Today every new ticket received a first response within a median of 2.5 minutes, and the expert answer followed within a median of 15.5 minutes.

| Measure | Median (min) | Average (min) | Number timed |
|:---|---:|---:|---:|
| First response | 2.5 | 2.8 | 6 |
| Expert answer | 15.5 | 21.5 | 6 |

Times are measured from the moment the Helpdesk first saw a post.

### New tickets by area (today)

| Area | New tickets |
|:---|---:|
| Entity Table | 2 |
| Chart View | 1 |
| Forms | 1 |
| List View | 1 |
| Navigation | 1 |

### Progress updates by status (today)

| Status | Updates |
|:---|---:|
| 2 -- Open | 0 |
| 3 -- In Progress | 4 |
| 4 -- Resolved | 6 |
| 7 -- Maybe Later | 0 |

### Expert review outcome (today)

| Outcome | Tickets | Detail |
|:---|---:|:---|
| Bug | 4 | 3 with a workaround |
| Enhancement | 2 | both with a workaround |
| User error | 0 |  |

### By reporter (today)

| Reporter | New posts | Progress updates received |
|:---|---:|---:|
| Gabriel Yssel | 3 | 2 |
| Morgan Phillips | 2 | 0 |
| Shelley | 1 | 3 |
| Reinhardt Coetzee | 0 | 3 |
| Falynn Missing | 0 | 1 |
| Angelique Steyn | 0 | 1 |

## To date

Period: 22 to 26 Oct 2026 · 3 working days.

| Measure | Value | Detail |
|:---|---:|:---|
| Support posts handled | 17 | 15 needed a card · 2 needed no action |
| New tickets (cards created) | 15 | 10 bugs · 3 enhancements · 2 not categorised |
| First responses sent | 10 | median 4 min after the post was seen (average 4.4, 9 timed) |
| Expert answers sent | 9 | median 21 min after the post was seen (average 23.8) |
| Progress updates to reporters | 30 | Open 2 · In Progress 8 · Resolved 9 · Maybe Later 11 |
| Cards moved to Resolved | 10 | Resolved column 149 → 159 |

### Response times (to date)

To date, the median first response time is 4 minutes and the median time to an expert answer is 21 minutes.

| Measure | Median (min) | Average (min) | Number timed |
|:---|---:|---:|---:|
| First response | 4 | 4.4 | 9 (of 10) |
| Expert answer | 21 | 23.8 | 9 |

Times are measured from the moment the Helpdesk first saw a post.

### New tickets by area (to date)

| Area | New tickets |
|:---|---:|
| Entity Table | 3 |
| Formulas / Formula Editor | 2 |
| Chart View | 1 |
| Canvas View | 1 |
| Board View | 1 |
| List View | 1 |
| Forms | 1 |
| Rules | 1 |
| Documents | 1 |
| Dashboard | 1 |
| Feed | 1 |
| Navigation | 1 |

### Progress updates by status (to date)

| Status | Updates |
|:---|---:|
| 2 -- Open | 2 |
| 3 -- In Progress | 8 |
| 4 -- Resolved | 9 |
| 7 -- Maybe Later | 11 |

### Expert review outcome (to date)

| Outcome | Tickets | Detail |
|:---|---:|:---|
| Bug | 6 | 4 with a workaround |
| Enhancement | 2 | both with a workaround |
| User error | 1 | answered with the correct steps |

### By reporter (to date)

| Reporter | New posts | Progress updates received |
|:---|---:|---:|
| Gabriel Yssel | 6 | 4 |
| Shelley | 4 | 5 |
| Morgan Phillips | 3 | 1 |
| Reinhardt Coetzee | 2 | 4 |
| Falynn Missing | 1 | 9 |
| Angelique Steyn | 1 | 6 |
| Leeroy Stander | 0 | 1 |

### Board, all columns

| Column | At start (22 Oct, cards) | Start of today (cards) | Now (cards) |
|:---|---:|---:|---:|
| Backlog | 18 | 12 | 13 |
| Open | 2 | 4 | 3 |
| In Progress | 6 | 10 | 10 |
| Resolved | 149 | 152 | 159 |
| Closed | 226 | 226 | 227 |
| Maybe Later | 24 | 24 | 24 |
| No Status | 4 | 4 | 4 |
| Total | 429 | 432 | 440 |

The whole Board, not only Helpdesk cards; Now is the last full count (15:12 SAST) plus the moves and new cards recorded up to 18:30 SAST.

## Capacity

Team size: 6 developers.

### Today

Today more work went out than came in: 6 new tickets against 7 resolved cards, a net flow of −1.

| Measure | Team (6 developers) | Per developer |
|:---|---:|---:|
| New tickets | 6 | 1.00 |
| Resolved | 7 | 1.17 |
| Net flow (in minus resolved) | −1 · shrinking | not applicable |
| Open load (Backlog + Open + In Progress) | 25 | 4.2 |

Today is 1 working day; open load is a snapshot of the whole Board, excluding test items.

### To date

To date an average of 5.0 new tickets come in per working day, against 3.3 that are resolved, so the open work is growing.

| Measure | Team (6 developers) | Per developer |
|:---|---:|---:|
| New tickets per working day | 5.0 | 0.83 |
| Resolved per working day | 3.3 | 0.56 |
| Net flow (in minus resolved) | +5 · growing | not applicable |
| Open load (Backlog + Open + In Progress) | 25 | 4.2 |

3 working days (Thu 22, Fri 23 and Mon 26 Oct); open load is a snapshot of the whole Board, excluding test items.

### New tickets against resolved cards per working day

| Working day | New tickets | Resolved |
|:---|---:|---:|
| Thu 22 Oct | 6 | 0 |
| Fri 23 Oct | 3 | 3 |
| Mon 26 Oct | 6 | 7 |

Resolved cards on 22 Oct count as 0, because tracking only began that evening.

### Lower-limit estimate

- Estimate: 3.3 new tickets a day the team can handle (0.56 per developer · confidence: low (10 resolved cards over 3 working days)).
- Method: The lower limit is the lower of the average resolution rate to date (10 resolved over 3 working days = 3.3) and the average over the last 3 working days (the same 3 days, so also 3.3). Because 22 Oct counts as 0, the estimate leans low rather than high.
- Warning: Intake is about 1.5 times the lower limit. If both rates hold, the open work will grow by about 1.7 cards per working day (estimate).
- Analysis: The open pile has only stayed at 25 since the start because today was a big resolve day. At 3.3 a day, the current 25 open cards are about 7.5 working days of work, or about 4 cards per developer (estimate). Two of today's 6 new tickets came from internal QA, and the person who posts them is also one of the 6 developers, so QA intake competes with the time available for fixes.

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

The automated QA trial run on 26 Oct found two minor bugs, both with a workaround, and they are 2 of the 15 new tickets to date.

Specialist QA checks on Genesis look for bugs, Morgan approves each finding, and it is then posted on the Helpdesk feed in his name. From there it follows the normal Helpdesk flow: a card on the Board, an expert review and an update to the reporter.

| QA ref | Card | Posted (SAST) | Status | Severity | Workaround | Update (SAST) |
|:---|:---|---:|:---|:---|:---|:---|
| SN-31 | Navigation: view page breadcrumb and tab title show the wrong space | 11:49 | Backlog | Bug · Medium (cosmetic) | Yes | 12:04 |
| LV-01 | List View: right-click on a group header shows no menu | 12:50 | Backlog | Bug · Medium (low impact) | Yes | 13:02 |

Both are Morgan Phillips's posts and are already included in the ticket counts on this page, not added on top.

The QA process worked end to end and is now deliberately on hold, because intake of 5.0 a day is already above the lower limit of 3.3 (see Capacity above). Without the QA bugs, intake to date would have been 13 (4.3 per working day).

## Cards

Cards that were created or updated today. Status is the Board column. A release-notes candidate is a card in 4 -- Resolved; area is the screen named at the start of the card title (the Board's Product Area field is not read here).

| Card | Type | Area | Status | Workaround | Reporter | New today | Resolved today | Release-notes candidate | QA ref | Note |
|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|
| Entity Table: self-relation link shows on the wrong side until refresh | Bug | Entity Table | 1 -- Backlog | yes | Gabriel Yssel | yes | no | no |  |  |
| Navigation: view page breadcrumb and tab title show the wrong space | Bug | Navigation | 1 -- Backlog | yes | Morgan Phillips | yes | no | no | SN-31 |  |
| Forms: add a link block to the form designer | Enhancement | Forms | 3 -- In Progress | yes | Shelley | yes | no | no |  |  |
| List View: right-click on a group header shows no menu | Bug | List View | 1 -- Backlog | yes | Morgan Phillips | yes | no | no | LV-01 |  |
| Chart View: filter using values from a linked item (e.g. current shift start and end) | Enhancement | Chart View | 3 -- In Progress | partial | Gabriel Yssel | yes | no | no |  |  |
| Entity Table: self-relations on a derived entity don't show | Bug | Entity Table | 1 -- Backlog | no | Gabriel Yssel | yes | no | no |  |  |
| Entities: Present item GUID/identifier in UI | Enhancement | Entities | 4 -- Resolved | not recorded | Falynn Missing | no | yes | yes |  |  |
| Rules: Name/Title not working | Bug | Rules | 4 -- Resolved | not recorded | Reinhardt Coetzee | no | yes | yes |  |  |
| Rules: relation-linked rule passes test but doesn't fire | Bug | Rules | 4 -- Resolved | not recorded | Shelley | no | yes | yes |  |  |
| Entity Table: Bulk update errors | Bug | Entity Table | 4 -- Resolved | not recorded | Shelley | no | yes | yes |  | urgent, data loss |
| Documents: Lexical toolbar obscuring text | Bug | Documents | 4 -- Resolved | not recorded | Angelique Steyn | no | yes | yes |  |  |
| Feed: Comments disappearing | Bug | Feed | 4 -- Resolved | not recorded | Reinhardt Coetzee | no | yes | yes |  |  |
| Canvas View: Self relations not displaying correctly | Bug | Canvas View | 3 -- In Progress | not recorded | Gabriel Yssel | no | no | no |  |  |
| Board View: Sorting not working properly | Bug | Board View | 3 -- In Progress | not recorded | Reinhardt Coetzee | no | no | no |  |  |

## Data notes

- Source: the Helpdesk's own records of posts, responses and Board moves, plus Board reads. Period: 22 to 26 Oct 2026 (3 working days), with today as Monday 26 Oct. Test posts and test cards are excluded.
- Gaps: since 15:12 SAST a Board filter has hidden some columns, so later Board figures are built from the recorded moves rather than a fresh full count. Resolved cards per developer within the period are not available. Satisfaction polls started on 23 Oct and have no scores yet. Resolved cards before the start are by Assigned To as at 22 Oct; another 9 sat with Gabriel Yssel, who now has no developer lane.
- Test items are excluded from every count and table.
- Workaround is "not recorded" where the report has no workaround field for that card.
- The Cards table lists the cards whose reporter got a progress update today; 6 of today's 7 moves to 4 -- Resolved are listed, and the rest had no reporter update, so their titles are not in this report.

## What to watch

Whether the resolution rate keeps up with intake of about 5 tickets a day, and the self-relations theme in the Entity Table.
