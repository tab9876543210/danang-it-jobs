# Community-Sourced Data Log (Facebook Groups)

Unverified, anecdotal data points gathered from Vietnamese IT hiring / recruitment Facebook groups, at An's direction. This is **not** affiliated with or verified against the ITviec / TopCV official reports the rest of the site is built from — treat it as "chatter I saw in a group," not a vetted statistic.

## How this file is used

- Claude (via Chrome) only visits a group and logs entries here when explicitly asked to check a specific group/link.
- Each visit is a one-off, human-triggered read of what's currently visible on the page — not an automated recurring crawl.
- Entries capture structured facts only (role, salary/detail mentioned, location, rough date, group name) — not verbatim post text or the poster's name/profile, to respect group members' privacy.
- This file is reviewed together periodically. Nothing here reaches `index.html` or `da-nang-detail.html` until An decides it's solid enough — likely as a clearly-labeled "Community reports" section, kept visually separate from the sourced-report numbers.

## Entry format

```
### YYYY-MM-DD — [Group name]
- Role: ...
- Detail: (salary mentioned / role opened / trend noted / etc.)
- Location: ...
- Notes: ...
```

---

## Log

### Round 1 — 2026-09-25 — Việc làm CNTT Đà Nẵng - New
Group: https://www.facebook.com/groups/vieclamcnttdanangnew (Public, ~21.7K members)
Scan notes: sorted by "New posts", read top of feed. This group is very high-volume — every post visible in this pass was timestamped within the same ~24h window (Facebook was still showing "X hours ago", never "X days ago"), so this round covers roughly the last day of activity, not the full 2 weeks requested. Flagging this so we can decide together whether to do more rounds to reach back 2 weeks, or treat "most recent activity" as the practical target given the volume.

- Role: Senior Backend (NodeJS/NestJS), Senior Tester (Automation+Manual)
  - Detail: Glory Software Vietnam hiring; conversational English required for all positions
  - Location: Đà Nẵng
  - Notes: No salary listed

- Role: Backend Java Developer, 4+ YOE
  - Detail: CMC Global Đà Nẵng; Java/Spring Boot, AWS/Azure experience
  - Location: Đà Nẵng
  - Notes: No salary listed

- Role: Fresher (Matlab/Simulink), 15 openings
  - Detail: FPT Software (Fsoft) Đà Nẵng; no experience required, 3-month paid training at 7M VND/month, offer after training 10–15M VND/month
  - Location: Đà Nẵng
  - Notes: Only post this round with a concrete salary range

- Role: QA, Japanese language, 1+ year experience
  - Detail: Poster "My Hang" — full post truncated ("See more"), salary not visible in preview
  - Location: Not stated in preview
  - Notes: Incomplete — would need to open the full post to get details

- Role: 4 open positions incl. BrSE (Japanese N2+)
  - Detail: D-Soft Đà Nẵng hiring
  - Location: Đà Nẵng
  - Notes: No salary listed

- Role: PM/Presales/BrSE, DevOps Engineer (Python/AWS, 3yr), Senior Java Developer (4yr), Tester (Japanese N3+, 3yr)
  - Detail: CMC Global Đà Nẵng — multi-role hiring post
  - Location: Đà Nẵng
  - Notes: No salary listed

- Role: R&D Engineer (various)
  - Detail: LG Electronics Development Vietnam (LGEDV) Đà Nẵng; bachelor's degree required
  - Location: Đà Nẵng
  - Notes: No salary listed

- Role: PM, 3+ YOE, Japan-market project experience
  - Detail: "Up to 50M VND" — no language requirement stated
  - Location: Not stated (group is Đà Nẵng-focused)
  - Notes: Highest salary figure seen this round; unverified single-poster claim

- Role: DevOps Engineer, 3+ YOE
  - Detail: SETA International, remote; Linux/Kubernetes/Terraform/Cloud, night shift 9PM–5AM, "attractive salary + quarterly bonus" (no number)
  - Location: Remote
  - Notes: No salary figure

- Role: Golang Developer (Junior–Senior)
  - Detail: SotaTek; remote/onsite, no foreign-language requirement, "competitive offer & good benefits" (no number)
  - Location: Remote/onsite
  - Notes: No salary figure

- Role: Fullstack .NET Developer, 3+ YOE
  - Detail: Axon Active Đà Nẵng; good English, working on a European healthcare project
  - Location: Đà Nẵng
  - Notes: No salary listed

Skipped as not IT/dev-relevant: a customer-service/call-center hiring post (7–10M VND, unrelated to CNTT), an agency self-promo post, and an unpaid internship post — kept out of the log since they don't inform IT salary/hiring data.

---

### Round 2 — 2026-09-25 — Việc làm CNTT Đà Nẵng - New
Group: https://www.facebook.com/groups/vieclamcnttdanangnew
Ask this round: find Project Manager postings matching ~10 years experience, English communication, PMP/PSM-II certification.

**Methodology change — much better performance:** instead of scrolling the main feed chronologically, used the group's built-in search (search icon → query → "Most recent" sort). This goes straight to matching posts instead of wading through unrelated content, and search results show real dates immediately, so filtering to "last 2 weeks" is direct rather than inferred from "X hours ago" labels. Searched: "PMP", "Project Manager", "PSM", "PMP Project Manager".

**Finding: no post in the last 2 weeks asks for exactly 10 years PM experience + PMP/PSM-II.** This group's PM demand tops out around "5+ years / Senior PM" — a 10-year bar doesn't appear to be how roles get posted here, at least not in this window. Closest matches:

- Role: Senior Project Manager — **closest match this round**
  - Detail: DTalent (recruiting agency) for a client; up to 70M VND gross. Requires 5+ years PM (software dev) or PM+BrSE, 2+ years specifically as Senior PM on large-scale/multi-project portfolios, offshore Japan-market projects, presales (scoping/proposals/estimation), Japanese N1/N2 business level, **English business level (TOEIC 750+)**, Agile/Scrum/Jira/Backlog/Confluence, budget/risk/stakeholder management, PM mentoring
  - Location: Đà Nẵng, Mon–Fri 8:00–17:30
  - Date: 2026-09-25 (posted ~3 hours before this scan)
  - Notes: Highest-seniority, highest-salary PM post found; no PMP/PSM certificate explicitly required, though the profile (budget/risk/stakeholder mgmt) is PMP-adjacent

- Role: Project Manager (Software Development)
  - Detail: FPT Software Đà Nẵng; explicitly "no foreign language required," 2–3 years experience, ops/AMS-Infra background, JP calendar 7:00–16:00, only 1 slot
  - Location: Đà Nẵng
  - Date: 6 days before scan (~2026-09-19)
  - Notes: Doesn't match criteria (too junior, no English requirement) — logged for contrast

- Role: Project Manager / Scrum Master
  - Detail: Finance-sector product company (Núi Thành St., Đà Nẵng); offer up to 50M gross, 3+ years PM/Scrum Master experience, developer background, good English communication
  - Location: Đà Nẵng
  - Date: August 25, 2026 — **outside the 2-week window**, kept for context only

- Reference only (outside window): VTI Đà Nẵng — "Senior/Middle Project Manager," posted June 9, 2026. 3–5+ years PM in IT Outsourcing, **explicitly prefers PMP, PSM/CSM, PRINCE2 certification**, strong tech base, estimation, Japanese-language proposal writing. This is the only post found (any date) that names PMP/PSM as a preference rather than a generic training perk — useful as a signal of what a matching listing looks like, even though it predates the 2-week window.

- Not an employer post — logged for market context: an individual (posting anonymously) seeking a Scrum Master / Junior PM role, 1.5 years experience, **states they hold a PSM Level II certificate**, and can communicate in English with overseas clients. Shows the certification circulates locally even at the junior end, not just as a senior requirement.

**Takeaway:** a PM opening that literally requires 10 years + PMP/PSM-II doesn't show up in this group's recent activity — Đà Nẵng's outsourcing-heavy market posts "Senior PM" around the 5-year mark instead. Worth deciding whether to (a) keep watching this group for a rarer senior post, (b) check a more senior-skewed group/source, or (c) treat "5+ years, Senior PM, up to 70M, English required" as the realistic local ceiling for the site's data.
