---
schema: genesis-helpdesk-report/v1
schema_version: 1
report_date: 2026-11-03
figures_as_of: 2026-11-03T20:16:00+02:00
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
  intake_per_working_day: [6, 3, 6, 3, 2, 5, 2, 18, 13]
  resolved_per_working_day: [0, 3, 7, 2, 7, 3, 3, 20, 6]
  intake_today: 13
  resolved_today: 6
  intake_to_date: 58
  resolved_to_date: 51
  average_intake_per_day: 6.4
  capacity_lower_limit_per_day: 5.7
  capacity_confidence: low
automated_qa_status: on_hold
cards_listed: 6
release_notes_candidates: 3
---

# Genesis Helpdesk stats: 3 Nov 2026

Figures as of 3 Nov 2026, 20:16 SAST. Refreshed every weekday evening. Full dark report: https://morganphillipsamsquaredsystems.github.io/genesis-helpdesk-report/en/.

## Summary

- Today: Catch-up from desk ledgers: 13 new tickets, 6 cards to Resolved (column 194 → 200). Open load 32.
- To date: Since 22 Oct, 58 new tickets and 51 cards to Resolved across 9 working days.
- Capacity: To date an average of 6.4 new tickets come in per working day, against 5.7 that are resolved, so the open work is still growing.
- Automated QA: QA stays deliberately on hold so it does not overwhelm dev capacity. Intake to date is 6.4 a day, above the lower limit of 5.7.
- What to watch: Still Backlog: Calendar personal space, favourite a specific item, docs in a new tab, Tag Register relations, virtual-join timeout, derived query parameters, and the 500-bucket chart. In Progress includes Timestamp format, CSV thousand separators, Feed scrollbar, Canvas field display, Canvas self-relations, space description, and lookup. Open includes cascading form dropdowns. mv-expand, Details add items, and empty folder delete reached Resolved.

## Today

Period: Tuesday 3 Nov 2026.

| Measure | Value | Detail |
|:---|---:|:---|
| New tickets triaged | 13 | Board total 463 → 481 since the 30 Oct evening snapshot |
| First responses from the desk | 2 / 2 | both first_contact_posted on the brief · timings not in brief |
| Outcome replies sent | 0 / 2 | new tickets not yet at outcome on the brief |
| Progress updates to reporters | 3 | Board movement; individual comment count is not in this brief |
| Cards moved to Resolved | 6 | Resolved column 194 → 200 |
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

Period: 22 to 3 Nov 2026 · 9 working days.

| Measure | Value | Detail |
|:---|---:|:---|
| Support posts handled | 31 | 27 needed a card · 4 needed no action |
| New tickets (cards created) | 58 | 17 bugs · 7 enhancements · 2 not categorised · 1 user error |
| First responses sent | 18 | median 3.5 min historically (average 4.9, 12 timed) · today's 2 first_contact_posted |
| Expert / outcome answers sent | 16 | median 21 min historically · no new-ticket outcomes on today's brief |
| Progress updates to reporters | 43 | Open 3 · In Progress 13 · Resolved 15 · Maybe Later 11 · Backlog 1 |
| Cards moved to Resolved | 51 | Resolved column 149 → 194 |

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
| Backlog | 18 | 15 | 13 |
| Open | 2 | 6 | 3 |
| In Progress | 6 | 8 | 16 |
| Resolved | 149 | 194 | 200 |
| Closed | 226 | 228 | 229 |
| Maybe Later | 24 | 24 | 24 |
| No Status | 4 | 6 | 9 |
| Total | 429 | 481 | 494 |

The whole Board. Now is the 21:29 SAST read (Backlog 15, Open 6, In Progress 8, Resolved 194, Maybe Later 24). Closed and No Status are carried from the 30 Oct file (228 / 6).

## Capacity

Team size: 6 developers.

### Today

Today 13 in vs 6 resolved, net +7. Lower limit 5.7/day.

| Measure | Team (6 developers) | Per developer |
|:---|---:|---:|
| New tickets | 13 | 2.17 |
| Resolved | 6 | 1.00 |
| Net flow (in minus resolved) | +7 · growing | not applicable |
| Open load (Backlog + Open + In Progress) | 32 | 5.3 |

Today is 1 working day; open load is a snapshot of the whole Board, excluding test items.

### To date

To date an average of 6.4 new tickets come in per working day, against 5.7 that are resolved, so the open work is still growing.

| Measure | Team (6 developers) | Per developer |
|:---|---:|---:|
| New tickets per working day | 6.4 | 1.07 |
| Resolved per working day | 5.7 | 0.95 |
| Net flow (in minus resolved) | +7 · growing | not applicable |
| Open load (Backlog + Open + In Progress) | 32 | 5.3 |

9 working days (22 Oct through Tue 3 Nov, weekends excluded); open load is a snapshot of the whole Board, excluding test items.

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
| Tue 3 Nov | 13 | 6 |

Resolved cards on 22 Oct count as 0, because tracking only began that evening.

### Lower-limit estimate

- Estimate: 5.7 new tickets a day the team can handle (1.0 per developer · confidence: low (51 resolved cards over 9 working days)).
- Method: The lower limit is the lower of the average resolution rate to date (51 resolved over 9 working days = 5.7) and the average over the last 3 working days (9.7). Because 22 Oct counts as 0, the estimate leans low rather than high.
- Warning: Intake at 6.4 a day is above the lower limit of 5.7. If both rates hold, the open work keeps growing (estimate).
- Analysis: The open pile went from 29 to 32, because In Progress moved from 8 to 16 while 6 cards reached Resolved (column 194 → 200). At 5.7 a day, the current 32 open cards are about 5.6 working days of work, or about 5.3 cards per developer (estimate). Today's intake of 13 was above the average of 6.4.

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

QA stays deliberately on hold so it does not overwhelm dev capacity. Intake to date is 6.4 a day, above the lower limit of 5.7.

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

- Source: the Helpdesk Board read at 20:16 SAST on Tue 3 Nov 2026, rolled forward from the 2 Nov evening file. Period: 22 Oct to 3 Nov 2026 (9 working days). Test posts and test cards are excluded.
- Gaps: Start of today is the 2 Nov evening Board figure (total 481). Resolved today is the column delta 194 to 200 (6). Closed and No Status are the live Board read (229 / 9). Intake today (13) is the Board total delta (481 → 494). Named ticket tables below are not rebuilt by the roll-forward.
- Test items are excluded from every count and table.
- Workaround is "not recorded" where the report has no workaround field for that card.
- Test items are excluded from every count and table.
- Workaround is "not recorded" where the report has no workaround field for that card.
- The Cards table lists the cards whose reporter got a progress update today; 3 of today's 6 moves to 4 -- Resolved are listed, and the rest had no reporter update, so their titles are not in this report.

## What to watch

Still Backlog: Calendar personal space, favourite a specific item, docs in a new tab, Tag Register relations, virtual-join timeout, derived query parameters, and the 500-bucket chart. In Progress includes Timestamp format, CSV thousand separators, Feed scrollbar, Canvas field display, Canvas self-relations, space description, and lookup. Open includes cascading form dropdowns. mv-expand, Details add items, and empty folder delete reached Resolved.
