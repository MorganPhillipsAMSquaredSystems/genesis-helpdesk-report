---
schema: genesis-helpdesk-report/v1
schema_version: 1
report_date: 2026-11-02
figures_as_of: 2026-11-02T21:29:00+02:00
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
  intake_per_working_day: [6, 3, 6, 3, 2, 5, 2, 18]
  resolved_per_working_day: [0, 3, 7, 2, 7, 3, 3, 20]
  intake_today: 18
  resolved_today: 20
  intake_to_date: 45
  resolved_to_date: 45
  average_intake_per_day: 5.6
  capacity_lower_limit_per_day: 5.6
  capacity_confidence: low
automated_qa_status: on_hold
cards_listed: 6
release_notes_candidates: 3
---

# Genesis Helpdesk stats: 2 Nov 2026

Figures as of 2 Nov 2026, 21:29 SAST. Refreshed every weekday evening. Full dark report: https://morganphillipsamsquaredsystems.github.io/genesis-helpdesk-report/en/.

## Summary

- Today: Catch-up from desk ledgers: 18 new tickets, 20 cards to Resolved (column 174 → 194). Open load 29.
- To date: Since 22 Oct, 45 new tickets and 45 cards to Resolved across 8 working days.
- Capacity: To date an average of 5.6 new tickets come in per working day, against 5.6 that are resolved, so the open work is even.
- Automated QA: QA stays deliberately on hold so it does not overwhelm dev capacity. Intake to date is 5.6 a day, the same as the lower limit of 5.6.
- What to watch: Still Backlog: Danie feed scrollbar, virtual-link chart, mv-expand, derived query parameters, CSV thousand separators, and the 500-bucket chart. In Progress includes the blank space description, relationship lookup, and the self-relation wrong-side link. Open load is 29. Autofill, comma clipping, dark mode, document read-only, derived self-relations, hidden relationship fields, and the extra process-flow chips are on Resolved.

## Today

Period: Monday 2 Nov 2026.

| Measure | Value | Detail |
|:---|---:|:---|
| New tickets triaged | 18 | Board total 463 → 481 since the 30 Oct evening snapshot |
| First responses from the desk | 2 / 2 | both first_contact_posted on the brief · timings not in brief |
| Outcome replies sent | 0 / 2 | new tickets not yet at outcome on the brief |
| Progress updates to reporters | 3 | Board movement; individual comment count is not in this brief |
| Cards moved to Resolved | 20 | Resolved column 174 → 194 |
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
| New tickets (cards created) | 45 | 17 bugs · 7 enhancements · 2 not categorised · 1 user error |
| First responses sent | 18 | median 3.5 min historically (average 4.9, 12 timed) · today's 2 first_contact_posted |
| Expert / outcome answers sent | 16 | median 21 min historically · no new-ticket outcomes on today's brief |
| Progress updates to reporters | 43 | Open 3 · In Progress 13 · Resolved 15 · Maybe Later 11 · Backlog 1 |
| Cards moved to Resolved | 45 | Resolved column 149 → 194 |

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
| Resolved | 149 | 174 | 194 |
| Closed | 226 | 228 | 228 |
| Maybe Later | 24 | 24 | 24 |
| No Status | 4 | 6 | 6 |
| Total | 429 | 463 | 481 |

The whole Board. Now is the 21:29 SAST read (Backlog 15, Open 6, In Progress 8, Resolved 194, Maybe Later 24). Closed and No Status are carried from the 30 Oct file (228 / 6).

## Capacity

Team size: 6 developers.

### Today

Today 18 in vs 20 resolved, net -2. Lower limit 5.6/day.

| Measure | Team (6 developers) | Per developer |
|:---|---:|---:|
| New tickets | 18 | 3.00 |
| Resolved | 20 | 3.33 |
| Net flow (in minus resolved) | -2 · shrinking | not applicable |
| Open load (Backlog + Open + In Progress) | 29 | 4.8 |

Today is 1 working day; open load is a snapshot of the whole Board, excluding test items.

### To date

To date an average of 5.6 new tickets come in per working day, against 5.6 that are resolved, so the open work is even.

| Measure | Team (6 developers) | Per developer |
|:---|---:|---:|
| New tickets per working day | 5.6 | 0.93 |
| Resolved per working day | 5.6 | 0.93 |
| Net flow (in minus resolved) | 0 · even | not applicable |
| Open load (Backlog + Open + In Progress) | 29 | 4.8 |

8 working days (22 Oct through Mon 2 Nov, weekends excluded); open load is a snapshot of the whole Board, excluding test items.

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

Resolved cards on 22 Oct count as 0, because tracking only began that evening.

### Lower-limit estimate

- Estimate: 5.6 new tickets a day the team can handle (0.9 per developer · confidence: low (45 resolved cards over 8 working days)).
- Method: The lower limit is the lower of the average resolution rate to date (45 resolved over 8 working days = 5.6) and the average over the last 3 working days. Because 22 Oct counts as 0, the estimate leans low rather than high.
- Warning: Intake matches the lower limit at 5.6 a day. If both rates hold, the open work stays about even (estimate).
- Analysis: The open pile went from 31 to 29, because In Progress moved from 10 to 8 while 20 cards reached Resolved (column 174 → 194). At 5.6 a day, the current 29 open cards are about 5.2 working days of work, or about 4.8 cards per developer (estimate). The 18 new tickets are the Board total change since the 30 Oct evening snapshot (463 → 481), booked to Monday because there is no 1 Nov file.

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

QA stays deliberately on hold so it does not overwhelm dev capacity. Intake to date is 5.6 a day, the same as the lower limit of 5.6.

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

- Source: the Helpdesk Board read at 21:29 SAST on Mon 2 Nov 2026, rolled forward from the 30 Oct evening file. Period: 22 Oct to 2 Nov 2026 (8 working days). Test posts and test cards are excluded.
- Gaps: Start of today is the 30 Oct evening Board figure. Resolved today is the column delta 174 to 194 (20). Closed and No Status are carried (228 / 6). Intake today (18) is the Board total delta (463 → 481) and includes anything that landed after that 30 Oct snapshot. Named ticket tables below are not rebuilt by the roll-forward.
- Test items are excluded from every count and table.
- Workaround is "not recorded" where the report has no workaround field for that card.
- Test items are excluded from every count and table.
- Workaround is "not recorded" where the report has no workaround field for that card.
- The Cards table lists the cards whose reporter got a progress update today; 3 of today's 20 moves to 4 -- Resolved are listed, and the rest had no reporter update, so their titles are not in this report.

## What to watch

Still Backlog: Danie feed scrollbar, virtual-link chart, mv-expand, derived query parameters, CSV thousand separators, and the 500-bucket chart. In Progress includes the blank space description, relationship lookup, and the self-relation wrong-side link. Open load is 29. Autofill, comma clipping, dark mode, document read-only, derived self-relations, hidden relationship fields, and the extra process-flow chips are on Resolved.
