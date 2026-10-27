---
schema: genesis-helpdesk-report/v1
schema_version: 1
report_date: 2026-10-27
figures_as_of: 2026-10-27T19:10:00+02:00
timezone: Africa/Johannesburg (SAST, +02:00)
language: en
period_start: 2026-10-22
working_days_to_date: 4
source: Genesis Helpdesk records (support posts, responses, Board moves) plus Board reads; test items excluded
refresh: nightly, every weekday evening; this file is overwritten in place and archived by date
url: https://morganphillipsamsquaredsystems.github.io/genesis-helpdesk-report/report.md
archive_url: https://morganphillipsamsquaredsystems.github.io/genesis-helpdesk-report/reports/2026-10-27.md
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
  intake_per_working_day: [6, 3, 6, 3]
  resolved_per_working_day: [0, 3, 7, 2]
  intake_today: 3
  resolved_today: 2
  intake_to_date: 18
  resolved_to_date: 12
  average_intake_per_day: 4.5
  capacity_lower_limit_per_day: 3.0
  capacity_confidence: low
automated_qa_status: on_hold
cards_listed: 9
release_notes_candidates: 2
---

# Genesis Helpdesk stats: 27 Oct 2026

Figures as of 27 Oct 2026, 19:10 SAST. Refreshed every weekday evening. Full dark reports: English https://morganphillipsamsquaredsystems.github.io/genesis-helpdesk-report/en/ and Afrikaans https://morganphillipsamsquaredsystems.github.io/genesis-helpdesk-report/af/.

## Summary

- Today: Today 3 new tickets were triaged and a compliment on release 1.3.10 was answered, while 2 cards moved to Resolved and 1 to Closed.
- To date: Since the Helpdesk started on 22 Oct, 21 posts have been handled, 18 new tickets have been placed on the Board and 12 cards have moved to Resolved.
- Capacity: To date an average of 4.5 new tickets come in per working day, against 3.0 that are resolved, so the open work is growing.
- Automated QA: QA stays deliberately on hold so it doesn't overwhelm dev capacity, because intake of 4.5 a day is still above the lower limit of 3.0 (see Capacity above). Without the QA findings, intake to date would have been 16 (4.0 per working day).
- What to watch: Whether resolutions pick up again after today's 2, and the derived-entity and self-relations theme in the Entity Table, which now has a second reporter.

## Today

Period: Tuesday 27 Oct 2026.

| Measure | Value | Detail |
|:---|---:|:---|
| New tickets triaged | 3 | 1 bug · 2 enhancements |
| First responses sent | 3 / 3 | median 2 min after the post was seen (average 6.3) |
| Expert answers sent | 2 / 2 | median 20 min after the post was seen (average 20) |
| Progress updates to reporters | 6 | 2 Resolved · 2 In Progress · 1 Open · 1 Backlog |
| Cards moved to Resolved | 2 | plus 1 moved to Closed |
| Satisfaction reply received | 1 | score 5 out of 5 · no new polls sent |

### Response times (today)

Today every post that needed a Helpdesk reply got a first response within a median of 2 minutes, and both expert answers followed within a median of 20 minutes.

| Measure | Median (min) | Average (min) | Number timed |
|:---|---:|---:|---:|
| First response | 2 | 6.3 | 3 |
| Expert answer | 20 | 20 | 2 |

Times are measured from the moment the Helpdesk first saw a post.

### New tickets by area (today)

| Area | New tickets |
|:---|---:|
| Entity Table | 1 |
| Feed | 1 |
| Fields | 1 |

### Progress updates by status (today)

| Status | Updates |
|:---|---:|
| 2 -- Open | 1 |
| 3 -- In Progress | 2 |
| 4 -- Resolved | 2 |
| 7 -- Maybe Later | 0 |
| 1 -- Backlog | 1 |

### Expert review outcome (today)

| Outcome | Tickets | Detail |
|:---|---:|:---|
| Bug | 1 | no user workaround yet |
| Enhancement | 2 | 1 with a workaround |
| User error | 0 |  |

### By reporter (today)

| Reporter | New posts | Progress updates received |
|:---|---:|---:|
| Gabriel Yssel | 2 | 2 |
| Leeroy Stander | 1 | 0 |
| June | 1 | 0 |
| Morgan Phillips | 0 | 2 |
| Shelley | 0 | 1 |
| Reinhardt Coetzee | 0 | 1 |

## To date

Period: 22 to 27 Oct 2026 · 4 working days.

| Measure | Value | Detail |
|:---|---:|:---|
| Support posts handled | 21 | 18 needed a card · 3 needed no action |
| New tickets (cards created) | 18 | 10 bugs · 6 enhancements · 2 not categorised |
| First responses sent | 13 | median 3.5 min after the post was seen (average 4.9, 12 timed) |
| Expert answers sent | 11 | median 21 min after the post was seen (average 23.1) |
| Progress updates to reporters | 36 | Open 3 · In Progress 10 · Resolved 11 · Maybe Later 11 · Backlog 1 |
| Cards moved to Resolved | 12 | Resolved column 149 → 161 |

### Response times (to date)

To date, the median first response time is 3.5 minutes and the median time to an expert answer is 21 minutes.

| Measure | Median (min) | Average (min) | Number timed |
|:---|---:|---:|---:|
| First response | 3.5 | 4.9 | 12 (of 13) |
| Expert answer | 21 | 23.1 | 11 |

Times are measured from the moment the Helpdesk first saw a post.

### New tickets by area (to date)

| Area | New tickets |
|:---|---:|
| Entity Table | 4 |
| Formulas / Formula Editor | 2 |
| Feed | 2 |
| Chart View | 1 |
| Canvas View | 1 |
| Board View | 1 |
| List View | 1 |
| Forms | 1 |
| Rules | 1 |
| Documents | 1 |
| Dashboard | 1 |
| Navigation | 1 |
| Fields | 1 |

### Progress updates by status (to date)

| Status | Updates |
|:---|---:|
| 2 -- Open | 3 |
| 3 -- In Progress | 10 |
| 4 -- Resolved | 11 |
| 7 -- Maybe Later | 11 |
| 1 -- Backlog | 1 |

### Expert review outcome (to date)

| Outcome | Tickets | Detail |
|:---|---:|:---|
| Bug | 6 | 3 with a workaround |
| Enhancement | 5 | 4 with a workaround |
| User error | 1 | answered with the correct steps |

### By reporter (to date)

| Reporter | New posts | Progress updates received |
|:---|---:|---:|
| Gabriel Yssel | 8 | 6 |
| Shelley | 4 | 6 |
| Morgan Phillips | 3 | 3 |
| Reinhardt Coetzee | 2 | 5 |
| Falynn Missing | 1 | 9 |
| Angelique Steyn | 1 | 6 |
| Leeroy Stander | 1 | 1 |
| June | 1 | 0 |

### Board, all columns

| Column | At start (22 Oct, cards) | Start of today (cards) | Now (cards) |
|:---|---:|---:|---:|
| Backlog | 18 | 13 | 12 |
| Open | 2 | 3 | 3 |
| In Progress | 6 | 10 | 12 |
| Resolved | 149 | 159 | 161 |
| Closed | 226 | 227 | 228 |
| Maybe Later | 24 | 24 | 24 |
| No Status | 4 | 4 | 4 |
| Total | 429 | 440 | 444 |

The whole Board, not only Helpdesk cards; Now is the last full count (17:21 SAST) plus the 2 new cards recorded up to 18:40 SAST.

## Capacity

Team size: 6 developers.

### Today

Today more came in than went out: 3 new tickets against 2 resolved cards, a net flow of +1.

| Measure | Team (6 developers) | Per developer |
|:---|---:|---:|
| New tickets | 3 | 0.50 |
| Resolved | 2 | 0.33 |
| Net flow (in minus resolved) | +1 · growing | not applicable |
| Open load (Backlog + Open + In Progress) | 26 | 4.3 |

Today is 1 working day; open load is a snapshot of the whole Board, excluding test items.

### To date

To date an average of 4.5 new tickets come in per working day, against 3.0 that are resolved, so the open work is growing.

| Measure | Team (6 developers) | Per developer |
|:---|---:|---:|
| New tickets per working day | 4.5 | 0.75 |
| Resolved per working day | 3.0 | 0.50 |
| Net flow (in minus resolved) | +6 · growing | not applicable |
| Open load (Backlog + Open + In Progress) | 26 | 4.3 |

4 working days (Thu 22, Fri 23, Mon 26 and Tue 27 Oct); open load is a snapshot of the whole Board, excluding test items.

### New tickets against resolved cards per working day

| Working day | New tickets | Resolved |
|:---|---:|---:|
| Thu 22 Oct | 6 | 0 |
| Fri 23 Oct | 3 | 3 |
| Mon 26 Oct | 6 | 7 |
| Tue 27 Oct | 3 | 2 |

Resolved cards on 22 Oct count as 0, because tracking only began that evening.

### Lower-limit estimate

- Estimate: 3.0 new tickets a day the team can handle (0.50 per developer · confidence: low (12 resolved cards over 4 working days)).
- Method: The lower limit is the lower of the average resolution rate to date (12 resolved over 4 working days = 3.0) and the average over the last 3 working days (12 resolved over 23, 26 and 27 Oct = 4.0). Because 22 Oct counts as 0, the estimate leans low rather than high.
- Warning: Intake is about 1.5 times the lower limit. If both rates hold, the open work will grow by about 1.5 cards per working day (estimate).
- Analysis: The open pile went from 25 to 26 today, because 3 new tickets came in and 2 cards were resolved. At 3.0 a day, the current 26 open cards are about 8.7 working days of work, or about 4.3 cards per developer (estimate). Today's intake of 3 was below the average of 4.5, and none of it came from QA.

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

Lanes read on 26 Oct at 18:32 SAST with a Created At filter (last 7 days) active; resolved cards per developer within the period are not available.

## Automated QA

Status: on hold (trial run).

The automated QA trial run on 26 Oct raised two minor findings, both with a workaround; they are 2 of the 18 new tickets to date, and one has since been reclassified as a feature request.

Specialist QA checks on Genesis look for bugs, Morgan approves each finding, and it is then posted on the Helpdesk feed in his name. From there it follows the normal Helpdesk flow: a card on the Board, an expert review and an update to the reporter.

| QA ref | Card | Posted (SAST) | Status | Type and severity | Workaround | Last update (SAST) |
|:---|:---|---:|:---|:---|:---|:---|
| SN-31 | Navigation: view page breadcrumb and tab title show the wrong space | 26 Oct 11:49 | Backlog | Bug · Medium (cosmetic) | Yes | 27 Oct 12:57 |
| LV-01 | List View: right-click on a group header shows no menu | 26 Oct 12:50 | Backlog | Enhancement · Medium (low impact) | Yes | 27 Oct 13:57 |

Both are Morgan Phillips's posts from 26 Oct and are already included in the ticket counts on this page, not added on top.

QA stays deliberately on hold so it doesn't overwhelm dev capacity, because intake of 4.5 a day is still above the lower limit of 3.0 (see Capacity above). Without the QA findings, intake to date would have been 16 (4.0 per working day).

## Cards

Cards that were created or updated today. Status is the Board column. A release-notes candidate is a card in 4 -- Resolved; area is the screen named at the start of the card title (the Board's Product Area field is not read here).

| Card | Type | Area | Status | Workaround | Reporter | New today | Resolved today | Release-notes candidate | QA ref | Note |
|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|
| Entity Table: relating two derived entities shows a count instead of the related item | Enhancement | Entity Table | 1 -- Backlog | no | Leeroy Stander | yes | no | no |  |  |
| Feed: a deleted system Feed link on an entity can't be reconnected | Bug | Feed | 1 -- Backlog | not recorded | Gabriel Yssel | yes | no | no |  |  |
| Fields: add a Time data type and date/time helper functions in formulas | Enhancement | Fields | 1 -- Backlog | yes | Gabriel Yssel | yes | no | no |  |  |
| Entity Table: self-relations on a derived entity don't show | Bug | Entity Table | 3 -- In Progress | not recorded | Gabriel Yssel | no | no | no |  |  |
| Table View: Fields not showing on detail screen | Bug | Table View | 4 -- Resolved | not recorded | Shelley | no | yes | yes |  |  |
| Navigation: view page breadcrumb and tab title show the wrong space | Bug | Navigation | 2 -- Open | not recorded | Morgan Phillips | no | no | no | SN-31 |  |
| Board View: Sorting not working properly | Bug | Board View | 4 -- Resolved | not recorded | Reinhardt Coetzee | no | yes | yes |  |  |
| List View: right-click on a group header shows no menu | Enhancement | List View | 1 -- Backlog | not recorded | Morgan Phillips | no | no | no | LV-01 |  |
| Entity Table: self-relation link shows on the wrong side until refresh | Bug | Entity Table | 3 -- In Progress | not recorded | Gabriel Yssel | no | no | no |  |  |

## Data notes

- Source: the Helpdesk's own records of posts, responses and Board moves, plus Board reads. Period: 22 to 27 Oct 2026 (4 working days), with today as Tuesday 27 Oct. Test posts and test cards are excluded.
- Gaps: Start of today is last night's figure, which was built from recorded moves, so it doesn't line up exactly with today's full counts. The first response time for the Time data type post is approximate, because that post had no support tag and was found in a full feed scan. Resolved cards per developer within the period are not available. Satisfaction: 2 polls were sent on 26 Oct and 1 reply has come in so far (score 5 out of 5). Developer lanes are from the 26 Oct Board read; resolved cards before the start are by Assigned To as at 22 Oct, and another 9 sat with Gabriel Yssel, who has no developer lane.
- Test items are excluded from every count and table.
- Workaround is "not recorded" where the report has no workaround field for that card.
- The Cards table lists the cards whose reporter got a progress update today; 2 of today's 2 moves to 4 -- Resolved are listed, and the rest had no reporter update, so their titles are not in this report.

## What to watch

Whether resolutions pick up again after today's 2, and the derived-entity and self-relations theme in the Entity Table, which now has a second reporter.
