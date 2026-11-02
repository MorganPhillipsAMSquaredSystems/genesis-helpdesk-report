---
schema: genesis-helpdesk-report/v1
schema_version: 1
report_date: 2026-11-02
figures_as_of: 2026-11-02T20:11:00+02:00
timezone: Africa/Johannesburg (SAST, +02:00)
language: en
period_start: 2026-10-22
working_days_to_date: 8
source: Genesis Helpdesk records (support posts, responses, Board moves) plus Board reads; test items excluded
refresh: nightly, every weekday evening; this file is overwritten in place and archived by date
url: https://morganphillipsamsquaredsystems.github.io/genesis-helpdesk-report/report.md
archive_url: https://morganphillipsamsquaredsystems.github.io/genesis-helpdesk-report/reports/2026-11-02.md
html_reports:
  en: https://morganphillipsamsquaredsystems.github.io/genesis-helpdesk-report/en/
images:
  en_today: https://morganphillipsamsquaredsystems.github.io/genesis-helpdesk-report/img/en-today.png
  en_to_date: https://morganphillipsamsquaredsystems.github.io/genesis-helpdesk-report/img/en-todate.png
board_status_values: ["1 -- Backlog", "2 -- Open", "3 -- In Progress", "4 -- Resolved", "5 -- Closed", "7 -- Maybe Later", "No Status"]
figures:
  intake_per_working_day: [6, 3, 6, 3, 2, 5, 2, 3]
  resolved_per_working_day: [0, 3, 7, 2, 7, 3, 3, 5]
  intake_today: 3
  resolved_today: 5
  intake_to_date: 30
  resolved_to_date: 30
  average_intake_per_day: 3.8
  capacity_lower_limit_per_day: 3.7
  capacity_confidence: low
automated_qa_status: on_hold
cards_listed: 6
release_notes_candidates: 3
---

# Genesis Helpdesk stats: 2 Nov 2026

Figures as of 2 Nov 2026, 20:11 SAST. Refreshed every weekday evening. Full dark report: https://morganphillipsamsquaredsystems.github.io/genesis-helpdesk-report/en/.

## Summary

- Today: Catch-up from desk ledgers: 3 new tickets, 5 cards to Resolved (column 174 → 179). Open load 29.
- To date: Since 22 Oct, 30 new tickets and 30 cards to Resolved across 8 working days.
- Capacity: To date an average of 3.9 new tickets come in per working day, against 3.6 that are resolved, so the open work is still growing slowly.
- Automated QA: QA stays deliberately on hold so it does not overwhelm dev capacity, because intake of 3.9 a day is still above the lower limit of 3.6 (see Capacity). Without the QA findings, intake to date would have been 25 (3.6 per working day).
- What to watch: Whether the many card_pending posts (import 1000-separator, freeze space name, datetime picker, dark mode, formulas) get Board cards, whether Documents read-only leaves the open columns, and whether self-relations keeps repeating. Open load is 31. CSV Import, Feed reconnect and Forms are on Resolved.

## Today

Period: Monday 2 Nov 2026.

| Measure | Value | Detail |
|:---|---:|:---|
| New tickets triaged | 3 | 2 bugs · Board total +2 |
| First responses from the desk | 2 / 2 | both first_contact_posted on the brief · timings not in brief |
| Outcome replies sent | 0 / 2 | new tickets not yet at outcome on the brief |
| Progress updates to reporters | 3 | 3 Resolved on the brief |
| Cards moved to Resolved | 5 | Resolved column 174 → 179 |
| Satisfaction polls sent | 0 | none sent today |

### Response times (today)

Today the desk first-contacted both new posts (first_contact_posted on the brief). Exact minute timings are not in the brief.

| Measure | Median (min) | Average (min) | Number timed |
|:---|---:|---:|---:|
| First response (desk) | — | — | 2 (of 2) |
| Outcome / expert reply | — | — | 0 |

Times are measured from the moment the Helpdesk first saw a post. Today's two new first_contact_posted items are counted as desk first contacts; exact minute timings are not in the brief.

### New tickets by area (today)

| Area | New tickets |
|:---|---:|
| Navigation | 1 |
| Canvas View | 1 |

### Progress updates by status (today)

| Status | Updates |
|:---|---:|
| 2 -- Open | 0 |
| 3 -- In Progress | 0 |
| 4 -- Resolved | 3 |
| 7 -- Maybe Later | 0 |
| 1 -- Backlog | 0 |

### Expert review outcome (today)

| Outcome | Tickets | Detail |
|:---|---:|:---|
| Bug | 2 | Navigation view mix-up · Canvas self-relations |
| Enhancement | 0 |  |
| User error | 0 |  |

### By reporter (today)

| Reporter | New posts | Progress updates received |
|:---|---:|---:|
| Gabriel Yssel | 1 | 2 |
| Morgan Phillips | 1 | 0 |
| Shells | 0 | 1 |

## To date

Period: 22 to 2 Nov 2026 · 8 working days.

| Measure | Value | Detail |
|:---|---:|:---|
| Support posts handled | 31 | 27 needed a card · 4 needed no action |
| New tickets (cards created) | 30 | 17 bugs · 7 enhancements · 2 not categorised · 1 user error |
| First responses sent | 18 | median 3.5 min historically (average 4.9, 12 timed) · today's 2 first_contact_posted |
| Expert / outcome answers sent | 16 | median 21 min historically · no new-ticket outcomes on today's brief |
| Progress updates to reporters | 43 | Open 3 · In Progress 13 · Resolved 15 · Maybe Later 11 · Backlog 1 |
| Cards moved to Resolved | 30 | Resolved column 149 → 174 |

### Response times (to date)

To date, the median first response time is 3.5 minutes (on posts the desk answered first).

| Measure | Median (min) | Average (min) | Number timed |
|:---|---:|---:|---:|
| First response | 3.5 | 4.9 | 15 (of 18) |
| Expert answer | 21 | 23.1 | 16 |

Times are measured from the moment the Helpdesk first saw a post. Today's two new first_contact_posted items are counted as desk first contacts; exact minute timings are not in the brief.

### New tickets by area (to date)

| Area | New tickets |
|:---|---:|
| Entity Table | 5 |
| Feed | 3 |
| Formulas / Formula Editor | 2 |
| Forms | 2 |
| Documents | 2 |
| List View | 2 |
| Navigation | 2 |
| Canvas View | 2 |
| Chart View | 1 |
| Board View | 1 |
| Rules | 1 |
| Dashboard | 1 |
| Fields | 1 |
| CSV Import | 1 |
| Workspaces | 1 |

### Progress updates by status (to date)

| Status | Updates |
|:---|---:|
| 2 -- Open | 3 |
| 3 -- In Progress | 13 |
| 4 -- Resolved | 15 |
| 7 -- Maybe Later | 11 |
| 1 -- Backlog | 1 |

### Expert review outcome (to date)

| Outcome | Tickets | Detail |
|:---|---:|:---|
| Bug | 13 | 4 with a workaround |
| Enhancement | 6 | 4 with a workaround |
| User error | 2 | answered with the correct steps |

### By reporter (to date)

| Reporter | New posts | Progress updates received |
|:---|---:|---:|
| Gabriel Yssel | 10 | 10 |
| Shelley | 7 | 7 |
| Morgan Phillips | 5 | 3 |
| Shells | 2 | 4 |
| Reinhardt Coetzee | 2 | 5 |
| Falynn Missing | 1 | 9 |
| Angelique Steyn | 1 | 6 |
| Leeroy Stander | 1 | 1 |
| June | 1 | 0 |

### Board, all columns

| Column | At start (22 Oct, cards) | Start of today (cards) | Now (cards) |
|:---|---:|---:|---:|
| Backlog | 18 | 15 | 15 |
| Open | 2 | 6 | 6 |
| In Progress | 6 | 10 | 8 |
| Resolved | 149 | 174 | 179 |
| Closed | 226 | 228 | 228 |
| Maybe Later | 24 | 24 | 24 |
| No Status | 4 | 6 | 6 |
| Total | 429 | 463 | 466 |

The whole Board, not only Helpdesk cards; Now is the desk-brief count (15:37 SAST). Closed and No Status are carried from last night (228 / 6).

## Capacity

Team size: 6 developers.

### Today

Today 3 in vs 5 resolved, net -2. Lower limit 3.7/day.

| Measure | Team (6 developers) | Per developer |
|:---|---:|---:|
| New tickets | 3 | 0.50 |
| Resolved | 5 | 0.83 |
| Net flow (in minus resolved) | -2 · shrinking | not applicable |
| Open load (Backlog + Open + In Progress) | 29 | 4.8 |

Today is 1 working day; open load is a snapshot of the whole Board, excluding test items.

### To date

To date an average of 3.9 new tickets come in per working day, against 3.6 that are resolved, so the open work is still growing slowly.

| Measure | Team (6 developers) | Per developer |
|:---|---:|---:|
| New tickets per working day | 3.8 | 0.63 |
| Resolved per working day | 3.8 | 0.63 |
| Net flow (in minus resolved) | 0 · even | not applicable |
| Open load (Backlog + Open + In Progress) | 29 | 4.8 |

7 working days (Thu 22, Fri 23, Mon 26, Tue 27, Wed 28, Thu 29 and Fri 30 Oct); open load is a snapshot of the whole Board, excluding test items.

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
| Mon 2 Nov | 3 | 5 |

Resolved cards on 22 Oct count as 0, because tracking only began that evening.

### Lower-limit estimate

- Estimate: 3.7 new tickets a day the team can handle (0.6 per developer · confidence: low (25 resolved cards over 7 working days)).
- Method: The lower limit is the lower of the average resolution rate to date (25 resolved over 7 working days = 3.6) and the average over the last 3 working days (13 resolved over 28, 29 and 30 Oct = 4.3). Because 22 Oct counts as 0, the estimate leans low rather than high.
- Warning: Intake is about 1.1 times the lower limit. If both rates hold, the open work will grow by about 0.3 cards per working day (estimate).
- Analysis: The open pile went from 32 to 31 today, because 2 new tickets came in and 3 cards were resolved (Resolved column 171 to 174). At 3.6 a day, the current 31 open cards are about 8.6 working days of work, or about 5.2 cards per developer (estimate). Today's intake of 2 was below the average of 3.9.

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

The automated QA trial run on 26 Oct raised two minor findings, both with a workaround; they are 2 of the 27 new tickets to date, and one has since been reclassified as a feature request.

| QA ref | Card | Posted (SAST) | Status | Severity | Workaround | Update (SAST) |
|:---|:---|---:|:---|:---|:---|:---|
| SN-31 | Navigation: view page breadcrumb and tab title show the wrong space | 26 Oct 11:49 | Backlog | Bug · Medium (cosmetic) | Yes | 27 Oct 12:57 |
| LV-01 | List View: right-click on a group header shows no menu | 26 Oct 12:50 | Backlog | Enhancement · Medium (low impact) | Yes | 27 Oct 13:57 |

Both are Morgan Phillips's posts and are already included in the ticket counts on this page, not added on top.

QA stays deliberately on hold so it does not overwhelm dev capacity, because intake of 3.9 a day is still above the lower limit of 3.6 (see Capacity). Without the QA findings, intake to date would have been 25 (3.6 per working day).

## Cards

Cards that were created or updated today. Status is the Board column. A release-notes candidate is a card in 4 -- Resolved; area is the screen named at the start of the card title (the Board's Product Area field is not read here).

| Card | Type | Area | Status | Workaround | Reporter | New today | Resolved today | Release-notes candidate | QA ref | Note |
|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|
| Navigation: view page mix-up on space / breadcrumb | Bug | Navigation | 2 -- Open | not recorded | Morgan Phillips | yes | no | no |  |  |
| Canvas View: self-relations to children or parent not shown | Bug | Canvas View | 2 -- Open | not recorded | Gabriel Yssel | yes | no | no |  |  |
| CSV Import: settings import does not list available spaces | Bug | CSV Import | 4 -- Resolved | not recorded | Gabriel Yssel | no | yes | yes |  |  |
| Feed: a deleted system Feed link on an entity can't be reconnected | Bug | Feed | 4 -- Resolved | not recorded | Gabriel Yssel | no | yes | yes |  |  |
| Forms: read-only users must submit forms without entity data access | Enhancement | Forms | 4 -- Resolved | not recorded | Shells | no | yes | yes |  |  |
| Documents: read-only users can still edit and save | Bug | Documents | 3 -- In Progress | not recorded | Shells | no | no | no |  |  |

## Data notes

- Source: the Helpdesk's own records of posts, responses and Board moves, plus the desk brief Board snapshot. Period: 22 to 30 Oct 2026 (7 working days), with today as Friday 30 Oct. Test posts and test cards are excluded.
- Gaps: Start of today is last night's published Board figure (29 Oct). Today's Resolved count uses the column delta 171 to 174 (3) from the desk brief (Backlog 15, Open 6, In Progress 10, Resolved 174, Maybe Later 24). Closed and No Status are carried from last night (228 / 6); the brief's separate closed counter is not the Board Closed column. Intake today ({INTAKE_TODAY}) is the Board total delta (461 → 463). New-ticket titles are the two first_contact_posted queue posts that were not on yesterday's cards table; other card_pending posts are noted but not counted as triaged. First-contact minute timings are not in the brief. Developer lanes are still from the 26 Oct Board read.
- Test items are excluded from every count and table.
- Workaround is "not recorded" where the report has no workaround field for that card.
- Test items are excluded from every count and table.
- Workaround is "not recorded" where the report has no workaround field for that card.
- The Cards table lists the cards whose reporter got a progress update today; 3 of today's 5 moves to 4 -- Resolved are listed, and the rest had no reporter update, so their titles are not in this report.

## What to watch

Whether the many card_pending posts (import 1000-separator, freeze space name, datetime picker, dark mode, formulas) get Board cards, whether Documents read-only leaves the open columns, and whether self-relations keeps repeating. Open load is 31. CSV Import, Feed reconnect and Forms are on Resolved.
