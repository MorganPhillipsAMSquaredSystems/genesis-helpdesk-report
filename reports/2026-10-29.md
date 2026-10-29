---
schema: genesis-helpdesk-report/v1
schema_version: 1
report_date: 2026-10-29
figures_as_of: 2026-10-29T18:45:00+02:00
timezone: Africa/Johannesburg (SAST, +02:00)
language: en
period_start: 2026-10-22
working_days_to_date: 6
source: Genesis Helpdesk records (support posts, responses, Board moves) plus Board reads; test items excluded
refresh: nightly, every weekday evening; this file is overwritten in place and archived by date
url: https://morganphillipsamsquaredsystems.github.io/genesis-helpdesk-report/report.md
archive_url: https://morganphillipsamsquaredsystems.github.io/genesis-helpdesk-report/reports/2026-10-29.md
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
  intake_per_working_day: [6, 3, 6, 3, 2, 5]
  resolved_per_working_day: [0, 3, 7, 2, 7, 3]
  intake_today: 5
  resolved_today: 3
  intake_to_date: 25
  resolved_to_date: 22
  average_intake_per_day: 4.2
  capacity_lower_limit_per_day: 3.7
  capacity_confidence: low
automated_qa_status: on_hold
cards_listed: 7
release_notes_candidates: 0
---

# Genesis Helpdesk stats: 29 Oct 2026

Figures as of 29 Oct 2026, 18:45 SAST. Refreshed every weekday evening. Full dark reports: English https://morganphillipsamsquaredsystems.github.io/genesis-helpdesk-report/en/ and Afrikaans https://morganphillipsamsquaredsystems.github.io/genesis-helpdesk-report/af/.

## Summary

- Today: Today 5 tickets were triaged (4 bugs, 1 user error), 3 cards moved to Resolved, and 3 In Progress updates went to reporters.
- To date: Since the Helpdesk started on 22 Oct, 28 posts have been handled, 25 new tickets have been placed on the Board and 22 cards have moved to Resolved.
- Capacity: To date an average of 4.2 new tickets come in per working day, against 3.7 that are resolved, so the open work is still growing.
- Automated QA: QA stays deliberately on hold so it does not overwhelm dev capacity, because intake of 4.2 a day is still above the lower limit of 3.7 (see Capacity). Without the QA findings, intake to date would have been 23 (3.8 per working day).
- What to watch: Whether CSV Import (UI #1234–#1236) and Documents read-only leave In Progress, whether Shelley's Spaces and List View chips get a developer, and whether Entity Table derived / self-relations keeps repeating. Open load is 32.

## Today

Period: Thursday 29 Oct 2026.

| Measure | Value | Detail |
|:---|---:|:---|
| New tickets triaged | 5 | 4 bugs · 1 user error |
| First responses from the desk | 3 / 5 | 2 already had first and second contact before the desk ran |
| Outcome replies sent | 3 / 5 | second contacts after expert review · 2 already answered |
| Progress updates to reporters | 3 | 3 In Progress |
| Cards moved to Resolved | 3 | Resolved column 168 → 171 · no Closed moves |
| Satisfaction polls sent | 0 | none sent today |

### Response times (today)

Today the desk first-contacted 3 of 5 new posts (median 5 min). Two afternoon posts already had first and second contact.

| Measure | Median (min) | Average (min) | Number timed |
|:---|---:|---:|---:|
| First response (desk) | 5 | 5.0 | 3 (of 5) |
| Outcome / expert reply | 8 | 9.0 | 3 |

Times are measured from the moment the Helpdesk first saw a post. Today's three desk first contacts were 2, 5 and 8 minutes after the post was seen; two afternoon posts already had a reply.

### New tickets by area (today)

| Area | New tickets |
|:---|---:|
| Entity Table | 1 |
| CSV Import | 1 |
| Feed | 1 |
| List View | 1 |
| Workspaces | 1 |

### Progress updates by status (today)

| Status | Updates |
|:---|---:|
| 2 -- Open | 0 |
| 3 -- In Progress | 3 |
| 4 -- Resolved | 0 |
| 7 -- Maybe Later | 0 |
| 1 -- Backlog | 0 |

### Expert review outcome (today)

| Outcome | Tickets | Detail |
|:---|---:|:---|
| Bug | 4 | User Story warnings · CSV Import · Spaces description · List View chips |
| Enhancement | 0 |  |
| User error | 1 | Feed likes are counted separately on post and comment |

### By reporter (today)

| Reporter | New posts | Progress updates received |
|:---|---:|---:|
| Shelley | 3 | 0 |
| Gabriel Yssel | 1 | 2 |
| Morgan Phillips | 1 | 0 |
| Shells | 0 | 1 |

## To date

Period: 22 to 29 Oct 2026 · 6 working days.

| Measure | Value | Detail |
|:---|---:|:---|
| Support posts handled | 28 | 25 needed a card · 3 needed no action |
| New tickets (cards created) | 25 | 15 bugs · 7 enhancements · 2 not categorised · 1 user error |
| First responses sent | 16 | median 3.5 min historically (average 4.9, 12 timed) · today's 3 timed at 2, 5 and 8 min |
| Expert / outcome answers sent | 16 | median 21 min historically · today's 3 were desk second contacts |
| Progress updates to reporters | 40 | Open 3 · In Progress 13 · Resolved 12 · Maybe Later 11 · Backlog 1 |
| Cards moved to Resolved | 22 | Resolved column 149 → 171 |

### Response times (to date)

To date, the median first response time is 3.5 minutes (on posts the desk answered first).

| Measure | Median (min) | Average (min) | Number timed |
|:---|---:|---:|---:|
| First response | 3.5 | 4.9 | 15 (of 16) |
| Expert answer | 21 | 23.1 | 16 |

Times are measured from the moment the Helpdesk first saw a post. Today's three desk first contacts were 2, 5 and 8 minutes after the post was seen; two afternoon posts already had a reply.

### New tickets by area (to date)

| Area | New tickets |
|:---|---:|
| Entity Table | 5 |
| Feed | 3 |
| Formulas / Formula Editor | 2 |
| Forms | 2 |
| Documents | 2 |
| List View | 2 |
| Chart View | 1 |
| Canvas View | 1 |
| Board View | 1 |
| Rules | 1 |
| Dashboard | 1 |
| Navigation | 1 |
| Fields | 1 |
| CSV Import | 1 |
| Workspaces | 1 |

### Progress updates by status (to date)

| Status | Updates |
|:---|---:|
| 2 -- Open | 3 |
| 3 -- In Progress | 13 |
| 4 -- Resolved | 12 |
| 7 -- Maybe Later | 11 |
| 1 -- Backlog | 1 |

### Expert review outcome (to date)

| Outcome | Tickets | Detail |
|:---|---:|:---|
| Bug | 11 | 4 with a workaround |
| Enhancement | 6 | 4 with a workaround |
| User error | 2 | answered with the correct steps |

### By reporter (to date)

| Reporter | New posts | Progress updates received |
|:---|---:|---:|
| Gabriel Yssel | 9 | 8 |
| Shelley | 7 | 7 |
| Morgan Phillips | 4 | 3 |
| Reinhardt Coetzee | 2 | 5 |
| Shells | 2 | 3 |
| Falynn Missing | 1 | 9 |
| Angelique Steyn | 1 | 6 |
| Leeroy Stander | 1 | 1 |
| June | 1 | 0 |

### Board, all columns

| Column | At start (22 Oct, cards) | Start of today (cards) | Now (cards) |
|:---|---:|---:|---:|
| Backlog | 18 | 17 | 18 |
| Open | 2 | 3 | 4 |
| In Progress | 6 | 7 | 10 |
| Resolved | 149 | 168 | 171 |
| Closed | 226 | 228 | 228 |
| Maybe Later | 24 | 24 | 24 |
| No Status | 4 | 6 | 6 |
| Total | 429 | 453 | 461 |

The whole Board, not only Helpdesk cards; Now is the last full count (18:45 SAST).

## Capacity

Team size: 6 developers.

### Today

Today more came in than went out: 5 new tickets against 3 resolved cards, a net flow of +2.

| Measure | Team (6 developers) | Per developer |
|:---|---:|---:|
| New tickets | 5 | 0.83 |
| Resolved | 3 | 0.50 |
| Net flow (in minus resolved) | +2 · growing | not applicable |
| Open load (Backlog + Open + In Progress) | 32 | 5.3 |

Today is 1 working day; open load is a snapshot of the whole Board, excluding test items.

### To date

To date an average of 4.2 new tickets come in per working day, against 3.7 that are resolved, so the open work is still growing.

| Measure | Team (6 developers) | Per developer |
|:---|---:|---:|
| New tickets per working day | 4.2 | 0.70 |
| Resolved per working day | 3.7 | 0.62 |
| Net flow (in minus resolved) | +3 · growing | not applicable |
| Open load (Backlog + Open + In Progress) | 32 | 5.3 |

6 working days (Thu 22, Fri 23, Mon 26, Tue 27, Wed 28 and Thu 29 Oct); open load is a snapshot of the whole Board, excluding test items.

### New tickets against resolved cards per working day

| Working day | New tickets | Resolved |
|:---|---:|---:|
| Thu 22 Oct | 6 | 0 |
| Fri 23 Oct | 3 | 3 |
| Mon 26 Oct | 6 | 7 |
| Tue 27 Oct | 3 | 2 |
| Wed 28 Oct | 2 | 7 |
| Thu 29 Oct | 5 | 3 |

Resolved cards on 22 Oct count as 0, because tracking only began that evening.

### Lower-limit estimate

- Estimate: 3.7 new tickets a day the team can handle (0.62 per developer · confidence: low (22 resolved cards over 6 working days)).
- Method: The lower limit is the lower of the average resolution rate to date (22 resolved over 6 working days = 3.7) and the average over the last 3 working days (12 resolved over 27, 28 and 29 Oct = 4.0). Because 22 Oct counts as 0, the estimate leans low rather than high.
- Warning: Intake is about 1.1 times the lower limit. If both rates hold, the open work will grow by about 0.5 cards per working day (estimate).
- Analysis: The open pile went from 27 to 32 today, because 5 new tickets came in and 3 cards were resolved (Resolved column 168 to 171). At 3.7 a day, the current 32 open cards are about 8.6 working days of work, or about 5.3 cards per developer (estimate). Today's intake of 5 was above the average of 4.2.

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

The automated QA trial run on 26 Oct raised two minor findings, both with a workaround; they are 2 of the 25 new tickets to date, and one has since been reclassified as a feature request.

| QA ref | Card | Posted (SAST) | Status | Severity | Workaround | Update (SAST) |
|:---|:---|---:|:---|:---|:---|:---|
| SN-31 | Navigation: view page breadcrumb and tab title show the wrong space | 26 Oct 11:49 | Backlog | Bug · Medium (cosmetic) | Yes | 27 Oct 12:57 |
| LV-01 | List View: right-click on a group header shows no menu | 26 Oct 12:50 | Backlog | Enhancement · Medium (low impact) | Yes | 27 Oct 13:57 |

Both are Morgan Phillips's posts and are already included in the ticket counts on this page, not added on top.

QA stays deliberately on hold so it does not overwhelm dev capacity, because intake of 4.2 a day is still above the lower limit of 3.7 (see Capacity). Without the QA findings, intake to date would have been 23 (3.8 per working day).

## Cards

Cards that were created or updated today. Status is the Board column. A release-notes candidate is a card in 4 -- Resolved; area is the screen named at the start of the card title (the Board's Product Area field is not read here).

| Card | Type | Area | Status | Workaround | Reporter | New today | Resolved today | Release-notes candidate | QA ref | Note |
|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|
| Entity Table: User Story shows This instance may have been deleted | Bug | Entity Table | 1 -- Backlog | not recorded | Shelley | yes | no | no |  |  |
| CSV Import: settings import does not list available spaces | Bug | CSV Import | 3 -- In Progress | not recorded | Gabriel Yssel | yes | no | no |  |  |
| Feed: parent post like count stays 0 when comments have likes | Not categorised | Feed | 1 -- Backlog | not recorded | Morgan Phillips | yes | no | no |  |  |
| List View: extra Add Process Flow chips on the right | Bug | List View | 1 -- Backlog | not recorded | Shelley | yes | no | no |  |  |
| Spaces: blank description does not save | Bug | Spaces | 1 -- Backlog | not recorded | Shelley | yes | no | no |  |  |
| Feed: a deleted system Feed link on an entity can't be reconnected | Bug | Feed | 3 -- In Progress | not recorded | Gabriel Yssel | no | no | no |  |  |
| Documents: read-only users can still edit and save | Bug | Documents | 3 -- In Progress | not recorded | Shells | no | no | no |  |  |

## Data notes

- Source: the Helpdesk's own records of posts, responses and Board moves, plus Board reads. Period: 22 to 29 Oct 2026 (6 working days), with today as Thursday 29 Oct. Test posts and test cards are excluded.
- Gaps: Start of today is last night's published Board figure (28 Oct). Today's Resolved count uses the column delta 168 to 171 (3). One of those moves is thought to be Chart View percentage (card not located for a status post). Shelley's two afternoon posts already had first and second contact, so those times are not desk first contacts. Developer lanes are still from the 26 Oct Board read. Lookup Field (Open) and several In Progress chores have no linked Genesis Support post.
- Test items are excluded from every count and table.
- Workaround is "not recorded" where the report has no workaround field for that card.
- Test items are excluded from every count and table.
- Workaround is "not recorded" where the report has no workaround field for that card.
- The Cards table lists the cards whose reporter got a progress update today; 0 of today's 3 moves to 4 -- Resolved are listed, and the rest had no reporter update, so their titles are not in this report.

## What to watch

Whether CSV Import (UI #1234–#1236) and Documents read-only leave In Progress, whether Shelley's Spaces and List View chips get a developer, and whether Entity Table derived / self-relations keeps repeating. Open load is 32.
