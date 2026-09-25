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

---

### Round 3 — 2026-09-25 — 8-group sweep (personal job-search check)
Groups checked this round (search-based method, "Most recent" sort, query terms: "PM"/"Project Manager"/"PMP"/"PSM"):
- https://www.facebook.com/groups/vieclamcnttdn ("Việc làm CNTT Đà Nẵng" — distinct from the "-New" group covered in Rounds 1–2)
- https://www.facebook.com/groups/jobITDaNang ("Việc làm IT Đà Nẵng")
- https://www.facebook.com/groups/vieclamitdanang (resolves to the same/sister "Việc làm IT Đà Nẵng" group)
- https://www.facebook.com/groups/congdongprojectmanagervietnam ("Cộng đồng Project Manager Việt Nam")
- https://www.facebook.com/groups/1714939998549259/ ("IT Jobs at Da Nang city")
- https://www.facebook.com/groups/301934151540945/ ("Việc Làm IT Freelancer, Remote Jobs")
- https://www.facebook.com/groups/398711525120468/ ("IT JOBS FOR REMOTE/SENIOR/PM/CTO")

**Note on purpose:** this round was run against the same target profile as Round 2 (~10 years PM experience, English communication, PMP/PSM-II) at the requester's ask for their own job search, not as general site market data. Kept in this file for the record, but not source material for the dashboard's aggregate stats section unless a clearly-labeled "closest matches" callout is wanted later.

**Best match found — Jess Jess, group "IT JOBS FOR REMOTE/SENIOR/PM/CTO"**
- Role: IT Project Manager
- Detail: "[QUẬN BÌNH THẠNH, HCM] CẦN TÌM IT PROJECT MANAGER (8 NĂM KN, FLUENT ENG) — DỰ ÁN LARGE SCALE." Projects 6 months–2 years. Requirements: minimum 8 years as IT Project Manager in software/IT, good spoken English (direct work with overseas management), **PMP certificate required** + deep Agile/Scrum understanding, IT-related university degree. Contact via the poster directly (no email/phone in the post text — "lh mình để nhận chi tiết JD").
- Location: Bình Thạnh, HCM (not Đà Nẵng)
- Date: August 11, 2026 — outside the 2-week window (~6 weeks old at scan time)
- Notes: closest overall match to the target profile found across all 9 groups checked this session — explicit PMP requirement, 8-year floor (a 10-year candidate clears it), English-only (no Japanese). Main gaps: HCM location, not Đà Nẵng; no PSM-II mention; post is dated, so may no longer be open.

**Other notable finds**

- Role: Senior Manager / Senior Delivery Manager (N2+) — NEGO
  - Detail: Anh Sơn / FreeC (recruiter), Hybrid-HN. Requires 10 years in software development, 5 of those as Senior Manager/Division Manager, offshore delivery management experience, **Japanese N2+**. Contact: sontran@freec.asia, +84 344 565 640. Same post also lists a second opening: "[DA NANG] BrSE/Tester (N2+)," 3+ years.
  - Location: Hybrid, Hà Nội (cross-posted into "vieclamitdanang" and "IT Jobs at Da Nang city")
  - Date: September 3, 2026 — just outside the 2-week window
  - Notes: closest match on raw years (10), but requires Japanese N2+ rather than English-only, and title is "Senior/Delivery Manager" rather than "Project Manager"

- Role: Project Manager
  - Detail: Quynh Linh / Kyanon Digital, Đà Nẵng. 3+ years PM experience, Strong English required, "nice to have: Agile/PMP certification, ES/UK market experience." Contact: linh.nguyenthiquynh@kyanon.digital, 0705 440 437.
  - Location: Đà Nẵng
  - Date: September 9, 2026 — just outside the 2-week window (by ~2 days)
  - Notes: Đà Nẵng-based and English-first, but years requirement (3+) is well under the 10-year target; PMP listed only as a plus, not required

- Role: PMO – Project Manager
  - Detail: Thuy Linh, "[Thủ Đức, HCM Hybrid] PMO-Project Manager | OFFER max 60M | fluent ENG." 5+ years PM experience (tech or non-tech background accepted), large team size, financial-services background preferred.
  - Location: Thủ Đức, HCM (Hybrid)
  - Notes: fluent English and a real offer ceiling (60M), but 5-year bar is below target and no certification mentioned; HCM not Đà Nẵng

- Role: Digital Architect
  - Detail: Tiến Quốc, congdongprojectmanagervietnam, Hà Nội. **8–10 years experience** required, salary "5x triệu" gross + fixed 13th-month bonus.
  - Location: Hà Nội
  - Notes: matches the target years range almost exactly, but the title/scope ("Digital Architect") is adjacent to PM rather than a PM role itself — logged for context, not a direct match

- Role: Senior Project Manager (national-scale project)
  - Detail: Trần Liên / GTEL ICT, congdongprojectmanagervietnam. 3–5 years, no English required, up to 65M, government/national digital-transformation project.
  - Location: not specified (likely Hà Nội)
  - Notes: high salary ceiling but no English requirement and years below target — logged for market-rate context only

- Individual self-post (not an employer listing) — market-context only:
  - OptimationZ candidate, congdongprojectmanagervietnam: 5 years dev experience, **holds PSM I & II plus PMI-ACP**, seeking Junior SM/APM/Technical PM roles. Confirms PSM-II circulates in the Vietnam PM community as a credential candidates actively hold and advertise, even though no *employer* post this round asked for it by name.

- Other postings seen but below target seniority or off-criteria (not detailed further): TechSoft PM (Middle, jobITDaNang, no years/salary given); AvePoint multi-role hiring from 6 months experience (jobITDaNang, 1714939998549259); Pyramid Technical QC_Manager 45–55tr (1714939998549259, not a PM role); Nguyễn Thùy Dung "Development Team Manager (Japanese)" Đà Nẵng $2000–3000 gross, 70% dev/30% mgmt (1714939998549259); Nguyễn Hồng Nhung / Rainscales "Project Manager (IoT)" Remote, 3–4 years, fluent English (398711525120468); Victoria Nguyễn "PMO kiêm Trợ lý Chủ tịch" up to 60M HCM — hybrid PMO + executive-assistant role, not a pure PM post (398711525120468); several PM listings in congdongprojectmanagervietnam under 5 years experience (Diễm Quỳnh, Hiền Thanh/VMO, Mebisoft, HaiAnh Nguyen, Ngọc Hồng/Globaldev, Thanh Bình/BNK, Minh Minh/SETA).

**Takeaway:** across all 9 Facebook groups checked this session, no employer post in the last 2 weeks combines all four target criteria at once (10 years, English, PMP, PSM-II). The closest single match — Jess Jess's HCM posting — hits 3 of 4 (8+ years, English, PMP) but is dated outside the window, is HCM-based rather than Đà Nẵng, and doesn't mention PSM-II. The Anh Sơn posting matches on raw years (10) but needs Japanese, not English. Splitting the criteria and relaxing the location (HCM/Hà Nội, not just Đà Nẵng) and the strict 2-week window surfaces meaningfully more matches than staying narrow.

---

### Direct post links — captured 2026-09-25
Permalinks grabbed for the strongest personal-job-search matches, so they can be revisited directly instead of re-searching. One bonus find surfaced while grabbing these (VTI's Sept 16 posting, inside the 2-week window — not in the Round 3 write-up above).

- Jess Jess — IT Project Manager, Bình Thạnh HCM (8+ yrs, PMP required, fluent English) — https://www.facebook.com/groups/398711525120468/posts/1592087812449494
- Anh Sơn / FreeC — Senior Manager/Senior Delivery Manager, Hybrid-HN (10 yrs, Japanese N2+) — https://www.facebook.com/groups/vieclamitdanang/posts/3950067295288963
- Quynh Linh / Kyanon Digital — Project Manager, Đà Nẵng (3+ yrs, English, PMP nice-to-have) — https://www.facebook.com/groups/vieclamitdanang/posts/3955725351389824
- Thuy Linh — PMO-Project Manager, Thủ Đức HCM (5+ yrs, fluent English, up to 60M) — https://www.facebook.com/groups/301934151540945/posts/1354947266239623
- Hồng Ngọc / DTalent — Senior Project Manager, Đà Nẵng, up to 70M gross (5+ yrs) — https://www.facebook.com/groups/vieclamcnttdanangnew/posts/38490754793903205
- **New find** — VTI Đà Nẵng — Project Manager, N3+ Japanese (posted Sept 16, inside 2-week window; Japanese-language requirement, not English-only) — https://www.facebook.com/groups/vieclamcnttdanangnew/posts/38255679134077440
