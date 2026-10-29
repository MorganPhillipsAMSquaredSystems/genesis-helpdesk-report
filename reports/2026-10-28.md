---
schema: genesis-helpdesk-report/v1
schema_version: 1
report_date: 2026-10-28
figures_as_of: 2026-10-28T19:50:00+02:00
timezone: Africa/Johannesburg (SAST, +02:00)
language: en
period_start: 2026-10-22
working_days_to_date: 5
source: Genesis Helpdesk records (support posts, responses, Board moves) plus Board reads; test items excluded
refresh: nightly, every weekday evening; this file is overwritten in place and archived by date
url: https://morganphillipsamsquaredsystems.github.io/genesis-helpdesk-report/report.md
archive_url: https://morganphillipsamsquaredsystems.github.io/genesis-helpdesk-report/reports/2026-10-28.md
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
  intake_per_working_day: [6, 3, 6, 3, 2]
  resolved_per_working_day: [0, 3, 7, 2, 7]
  intake_today: 2
  resolved_today: 7
  intake_to_date: 20
  resolved_to_date: 19
  average_intake_per_day: 4.0
  capacity_lower_limit_per_day: 3.8
  capacity_confidence: low
automated_qa_status: on_hold
cards_listed: 3
release_notes_candidates: 1
---

# Genesis Helpdesk stats: 28 Oct 2026

Figures as of 28 Oct 2026, 19:50 SAST. Refreshed every weekday evening. Full dark reports: English https://morganphillipsamsquaredsystems.github.io/genesis-helpdesk-report/en/ and Afrikaans https://morganphillipsamsquaredsystems.github.io/genesis-helpdesk-report/af/.

## Summary

- Today: Today 2 urgent tickets from Shells were triaged (Documents bug, Forms enhancement), 7 cards moved to Resolved, and 1 progress update went to a reporter.
- To date: Since the Helpdesk started on 22 Oct, 23 posts have been handled, 20 new tickets have been placed on the Board and 19 cards have moved to Resolved.
- Capacity: To date an average of 4.0 new tickets come in per working day, against 3.8 that are resolved, so the open work is still growing slowly.
- Automated QA: QA stays deliberately on hold so it does not overwhelm dev capacity, because intake of 4.0 a day is still above the lower limit of 3.8 (see Capacity). Without the QA findings, intake to date would have been 18 (3.6 per working day).
- What to watch: Whether the Resolved column keeps moving at today's pace, and the permissions theme on Forms and Documents after Shells' two urgent posts. Entity Table derived-entity and self-relations remains the repeating area theme.

## Today

Period: Wednesday 28 Oct 2026.

| Measure | Value | Detail |
|:---|---:|:---|
| New tickets triaged | 2 | 1 bug · 1 enhancement |
| First responses from the desk | 0 / 2 | both already had a reply (Reinhardt) before the desk ran |
| Outcome replies sent | 2 / 2 | second contacts after expert review |
| Progress updates to reporters | 1 | 1 Resolved |
| Cards moved to Resolved | 7 | Resolved column 161 → 168 · no Closed moves |
| Satisfaction polls sent | 1 | Forms link block · no new reply logged today |

### Response times (today)

Today's two new posts already had a reply before the desk; the desk posted confirmed outcomes on both after expert review.

| Measure | Median (min) | Average (min) | Number timed |
|:---|---:|---:|---:|
| First response (desk) | — | — | 0 (of 2) |
| Outcome / expert reply | — | — | 2 |

Times are measured from the moment the Helpdesk first saw a post. Today's new posts already had a human reply before the desk ran; desk outcome replies are timed below as expert answers.

### New tickets by area (today)

| Area | New tickets |
|:---|---:|
| Documents | 1 |
| Forms | 1 |

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
| Bug | 1 | Documents read-only edit/save |
| Enhancement | 1 | Forms read-only submit without entity data |
| User error | 0 |  |

### By reporter (today)

| Reporter | New posts | Progress updates received |
|:---|---:|---:|
| Shells | 2 | 2 |
| Shelley | 0 | 1 |

## To date

Period: 22 to 28 Oct 2026 · 5 working days.

| Measure | Value | Detail |
|:---|---:|:---|
| Support posts handled | 23 | 20 needed a card · 3 needed no action |
| New tickets (cards created) | 20 | 11 bugs · 7 enhancements · 2 not categorised |
| First responses sent | 13 | median 3.5 min after the post was seen (average 4.9, 12 timed) · today's 2 were already replied |
| Expert / outcome answers sent | 13 | median 21 min historically · today's 2 were desk second contacts |
| Progress updates to reporters | 37 | Open 3 · In Progress 10 · Resolved 12 · Maybe Later 11 · Backlog 1 |
| Cards moved to Resolved | 19 | Resolved column 149 → 168 |

### Response times (to date)

To date, the median first response time is 3.5 minutes (on posts the desk answered first).

| Measure | Median (min) | Average (min) | Number timed |
|:---|---:|---:|---:|
| First response | 3.5 | 4.9 | 12 (of 13) |
| Expert answer | 21 | 23.1 | 13 |

Times are measured from the moment the Helpdesk first saw a post. Today's new posts already had a human reply before the desk ran; desk outcome replies are timed below as expert answers.

### New tickets by area (to date)

| Area | New tickets |
|:---|---:|
| Entity Table | 4 |
| Formulas / Formula Editor | 2 |
| Feed | 2 |
| Forms | 2 |
| Documents | 2 |
| Chart View | 1 |
| Canvas View | 1 |
| Board View | 1 |
| List View | 1 |
| Rules | 1 |
| Dashboard | 1 |
| Navigation | 1 |
| Fields | 1 |

### Progress updates by status (to date)

| Status | Updates |
|:---|---:|
| 2 -- Open | 3 |
| 3 -- In Progress | 10 |
| 4 -- Resolved | 12 |
| 7 -- Maybe Later | 11 |
| 1 -- Backlog | 1 |

### Expert review outcome (to date)

| Outcome | Tickets | Detail |
|:---|---:|:---|
| Bug | 7 | 3 with a workaround |
| Enhancement | 6 | 4 with a workaround |
| User error | 1 | answered with the correct steps |

### By reporter (to date)

| Reporter | New posts | Progress updates received |
|:---|---:|---:|
| Gabriel Yssel | 8 | 6 |
| Shelley | 4 | 7 |
| Morgan Phillips | 3 | 3 |
| Reinhardt Coetzee | 2 | 5 |
| Shells | 2 | 2 |
| Falynn Missing | 1 | 9 |
| Angelique Steyn | 1 | 6 |
| Leeroy Stander | 1 | 1 |
| June | 1 | 0 |

### Board, all columns

| Column | At start (22 Oct, cards) | Start of today (cards) | Now (cards) |
|:---|---:|---:|---:|
| Backlog | 18 | 12 | 17 |
| Open | 2 | 3 | 3 |
| In Progress | 6 | 12 | 7 |
| Resolved | 149 | 161 | 168 |
| Closed | 226 | 228 | 228 |
| Maybe Later | 24 | 24 | 24 |
| No Status | 4 | 4 | 6 |
| Total | 429 | 444 | 453 |

The whole Board, not only Helpdesk cards; Now is the last full count (19:50 SAST).

## Capacity

Team size: 6 developers.

### Today

Today more went out than came in: 2 new tickets against 7 resolved cards, a net flow of -5.

| Measure | Team (6 developers) | Per developer |
|:---|---:|---:|
| New tickets | 2 | 0.33 |
| Resolved | 7 | 1.17 |
| Net flow (in minus resolved) | -5 · shrinking | not applicable |
| Open load (Backlog + Open + In Progress) | 27 | 4.5 |

Today is 1 working day; open load is a snapshot of the whole Board, excluding test items.

### To date

To date an average of 4.0 new tickets come in per working day, against 3.8 that are resolved, so the open work is still growing slowly.

| Measure | Team (6 developers) | Per developer |
|:---|---:|---:|
| New tickets per working day | 4.0 | 0.67 |
| Resolved per working day | 3.8 | 0.63 |
| Net flow (in minus resolved) | +1 · growing | not applicable |
| Open load (Backlog + Open + In Progress) | 27 | 4.5 |

5 working days (Thu 22, Fri 23, Mon 26, Tue 27 and Wed 28 Oct); open load is a snapshot of the whole Board, excluding test items.

### New tickets against resolved cards per working day

| Working day | New tickets | Resolved |
|:---|---:|---:|
| Thu 22 Oct | 6 | 0 |
| Fri 23 Oct | 3 | 3 |
| Mon 26 Oct | 6 | 7 |
| Tue 27 Oct | 3 | 2 |
| Wed 28 Oct | 2 | 7 |

Resolved cards on 22 Oct count as 0, because tracking only began that evening.

### Lower-limit estimate

- Estimate: 3.8 new tickets a day the team can handle (0.63 per developer · confidence: low (19 resolved cards over 5 working days)).
- Method: The lower limit is the lower of the average resolution rate to date (19 resolved over 5 working days = 3.8) and the average over the last 3 working days (16 resolved over 26, 27 and 28 Oct = 5.3). Because 22 Oct counts as 0, the estimate leans low rather than high.
- Warning: Intake is about 1.1 times the lower limit. If both rates hold, the open work will grow by about 0.2 cards per working day (estimate).
- Analysis: The open pile went from 26 to 27 today, because 2 new tickets came in and 7 cards were resolved (Resolved column 161 to 168). At 3.8 a day, the current 27 open cards are about 7.1 working days of work, or about 4.5 cards per developer (estimate). Today's intake of 2 was below the average of 4.0.

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

The automated QA trial run on 26 Oct raised two minor findings, both with a workaround; they are 2 of the 20 new tickets to date, and one has since been reclassified as a feature request.

| QA ref | Card | Posted (SAST) | Status | Severity | Workaround | Update (SAST) |
|:---|:---|---:|:---|:---|:---|:---|
| SN-31 | Navigation: view page breadcrumb and tab title show the wrong space | 26 Oct 11:49 | Backlog | Bug · Medium (cosmetic) | Yes | 27 Oct 12:57 |
| LV-01 | List View: right-click on a group header shows no menu | 26 Oct 12:50 | Backlog | Enhancement · Medium (low impact) | Yes | 27 Oct 13:57 |

Both are Morgan Phillips's posts and are already included in the ticket counts on this page, not added on top.

QA stays deliberately on hold so it does not overwhelm dev capacity, because intake of 4.0 a day is still above the lower limit of 3.8 (see Capacity). Without the QA findings, intake to date would have been 18 (3.6 per working day).

## Cards

Cards that were created or updated today. Status is the Board column. A release-notes candidate is a card in 4 -- Resolved; area is the screen named at the start of the card title (the Board's Product Area field is not read here).

| Card | Type | Area | Status | Workaround | Reporter | New today | Resolved today | Release-notes candidate | QA ref | Note |
|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|
| Documents: read-only users can still edit and save | Bug | Documents | 1 -- Backlog | not recorded | Shells | yes | no | no |  |  |
| Forms: read-only users must submit forms without entity data access | Enhancement | Forms | 1 -- Backlog | not recorded | Shells | yes | no | no |  |  |
| Forms: add a link block to the form designer | Enhancement | Forms | 4 -- Resolved | not recorded | Shelley | no | yes | yes |  |  |

## Data notes

- Source: the Helpdesk's own records of posts, responses and Board moves, plus Board reads. Period: 22 to 28 Oct 2026 (5 working days), with today as Wednesday 28 Oct. Test posts and test cards are excluded.
- Gaps: Start of today is last night's published Board figure (27 Oct). Today's Resolved count uses the column delta 161 to 168 (7). Four of those moves were logged at midday (Forms link block plus three cards with no linked GS post). First-contact times for today's Shells posts are not desk first contacts (Reinhardt had already replied). Developer lanes are still from the 26 Oct Board read.
- Test items are excluded from every count and table.
- Workaround is "not recorded" where the report has no workaround field for that card.
- Test items are excluded from every count and table.
- Workaround is "not recorded" where the report has no workaround field for that card.
- The Cards table lists the cards whose reporter got a progress update today; 1 of today's 7 moves to 4 -- Resolved are listed, and the rest had no reporter update, so their titles are not in this report.

## What to watch

Whether the Resolved column keeps moving at today's pace, and the permissions theme on Forms and Documents after Shells' two urgent posts. Entity Table derived-entity and self-relations remains the repeating area theme.
