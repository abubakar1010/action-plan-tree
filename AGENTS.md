# Action Plans — working notes for future sessions

Everything here is about **building and maintaining the user's study action plans in Notion**. There is no code in this repo; the working directory exists only to anchor the session, memory and this file.

Last updated: **2026-09-18**.

---

## 1. Context

The user is studying four things at once and wants each one turned into an executable Notion plan:

| Plan | Subject | Status |
|---|---|---|
| **Phitron AI/ML** | Phitron course: ML track + Deep Learning track | Built (rebuilt twice, then shifted), **runs 19–29 Sep** |
| **English (IELTS)** | Band 8 target | Built, **paused**, dates still say 16 Sep |
| **AWS** | 10 AWS modules | The user built it themselves, **paused**, dates still say 16–28 Sep |
| **Skiena** | Analysis of Algorithms, 26 lectures | Page exists, **database is empty**, not built yet |

What the user wants from a plan, in their own words: goals that can be **counted and measured**, and a page that is **"clean, clear and brutally executable"**. They do not want process descriptions without a finish line.

**Working hours:** the user gets up around 2:45 AM. Their slots are 3:00–7:00 AM, 10:00–11:00 AM, 1:30–2:30 PM and 5:30–9:30 PM. All Notion times are local **UTC+6 (Asia/Dhaka)**.

---

## 2. Notion IDs

Everything lives under the **Notes** page: `3533592a-b337-8010-9247-f0c61cdcc052`.

### Phitron AI/ML (active)
| Thing | ID |
|---|---|
| Page `🤖 Action Plan - Phitron AI/ML` | `3dc3592a-b337-81dd-9d25-f4de45e9e630` |
| Database `Phitron Sprint` | `2b320935414b4d24b1cb2ead12e83e87` |
| Data source | `collection://ba3ebba7-fe9e-4098-b243-1b4d181fada4` |
| View `Sprint` (table) | `view://7bf3d9d8-bc4b-4e84-acc6-6595bfd37670` |
| Old 30-day database (in Trash) | `6ee0b2dcae734da69c6901132d0648b4` |

Day rows, in order:

| Day | Page ID |
|---|---|
| 1 | `3dc3592a-b337-818d-bae7-d38b2eb63dad` |
| 2 | `3dc3592a-b337-812c-83fb-db0ecc7a80db` |
| 3 | `3dc3592a-b337-8108-b8ac-db053f5e3e5d` |
| 4 | `3dc3592a-b337-814d-b67e-f21e897e80b4` |
| 5 | `3dc3592a-b337-8188-a409-fd3162156ccb` |
| 6 | `3dc3592a-b337-8151-8b54-d9003fd654a5` |
| 7 | `3dd3592a-b337-81da-a7d9-c6fa0c67e102` |
| 8 | `3dd3592a-b337-8109-a1f6-cddd2aa4df46` |
| 9 | `3dd3592a-b337-81f3-80ed-ceb0c73ff0e9` |
| 10 | `3dd3592a-b337-81a6-9913-d5f926eb008a` |
| 11 | `3dd3592a-b337-8101-a624-e2c56386327e` |

### English (IELTS)
| Thing | ID |
|---|---|
| Page `📘 Action Plan - English` | `3dc3592a-b337-80cc-a8b0-cc3187a62ce3` |
| Database `English Weekly Plan` | `399496b07c2740068964b9917879092c` |
| Data source | `collection://70cd5b30-a8ef-4ea4-889e-6361231bb7e6` |
| View `Plan` | `view://c4a88686-60b4-4695-8111-2ed6417675eb` |
| View `Scoreboard` | `view://3dc3592a-b337-8171-8f94-000cac89a8ef` |

Week rows: W0 `3dc3592a-b337-81ab-81cb-f2e5fc560f89` · W1 `…-8179-baa2-c46c0a0168eb` · W2 `…-81c4-9a7f-d80380dd1898` · W3 `…-81c6-a713-cdccb32460ed` · W4 `…-81a5-92bd-e3a69c397daa` · W5 `…-817b-b241-fd63f88f24b3` · W6 `…-8186-aed3-ce0d2e73ef5f` · W7 `…-81cf-a807-d31c0fc65dda` · W8 `…-8195-9812-d9460b506dad` · W9 `…-81cb-9f3b-d10038ffe351` · W10 `…-81cb-84f9-d53173aee8f6` · W11 `…-81d1-bea8-d8f41b9df858` · W12 `…-8164-bef2-fafe50b17753` (all start `3dc3592a-b337`).

### AWS and Skiena (the user's own pages)
| Thing | ID |
|---|---|
| Page `☁️ Action Plan - AWS` | `3dc3592a-b337-819a-937f-c5ab8748fe8c` |
| Database `AWS Action Plan` | `137cd01d-5e96-4560-8f04-35b480d8db31` (ds `21c0ea21-9e32-488f-8762-0a6225f0726c`) |
| Page `Action Plan - Skiena Analysis of algorithm` | `3dc3592a-b337-8020-9ac8-c3da1ee38e23` |
| Database `Action Plans Template` (empty) | `7773592a-b337-828f-a6f8-01e7a7331bdb` (ds `0ac3592a-b337-8334-ae72-07c127e62986`) |
| Page `Action Plan` — the user's English strategy notes | `3d23592a-b337-8056-ad1c-c71220f65ceb` |

The `Action Plan` page is the source for the English targets: Band 7 → 8, roughly 5,000–6,000 word families, Anki with FSRS 35–45 min a day, weekly process metrics and quarterly outcome checks.

---

## 3. The house style for an action plan

Copied from the user's own AWS page, then extended.

1. **Summary at the top**, a few plain lines: what is covered, how many days, the date range, the daily time slots, the milestones.
2. **A rules block** right after, as a coloured quote or callout. Short, imperative, with the reasons the user already wrote in their notes.
3. **An inline database** immediately after that, so the page opens onto today's work.
4. **One row per unit of work** — a day for course-style plans, a week for habit-style plans.
5. **Every row page** has: a callout naming the day and its load, then a heading per time slot with `- [ ]` checkboxes carrying clock times, then a Notes section.
6. **Every target is countable.** "5 graded readers", "38 modules", not "read more".
7. **Times are explicit.** `3:00 **DL Module 08:** Backpropagation Fundamentals (2h)` beats "morning: backprop".
8. **Name the failure mode** next to the target: what it means when a number is off, what does not count, what to do when a module runs over.

### Plan structure, three layers
Used to turn a process into goals (this is the strategy the user accepted):
- **Output count** — countable, tickable. "How many did I finish?"
- **Quality trend** — a number logged each time. "Is each one getting better?"
- **Checkpoint** — a test every few weeks. "Did the real outcome move?"

---

## 4. Current plans in detail

### 4.1 Phitron AI/ML sprint (active)

- **19–29 Sep 2026, 11 days, 10 hours a day** (Day 11 is mornings only, finishing 7:00 AM Tue 29 Sep). Day N falls on 18+N Sep.
- Milestones: ML modules done Wed 23 Sep · ML Final Exam Thu 24 Sep, 3 AM · DL Mid Term Mon 28 Sep, 3 AM.
- Slots: **3:00–7:00 AM** and **5:30–9:30 PM** hold **2 modules each**; **10:00–11:00 AM** and **1:30–2:30 PM** are for assignments, summaries and overflow, and never start a module.
- **A module takes 1h45–2h** — the user's own estimate, given 2026-09-16. An earlier 1-hour assumption was wrong and caused a full rebuild. Plan at 2h; the 15 minutes saved per module is the slack.
- Totals: 38 modules + 4 assignments + 2 exams ≈ **88 hours** against 104 hours of slots.
- Order: all ML first (Days 1–5, exam Day 6), then DL (Days 6–11, mid term Day 10).
- Exams are always **first thing at 3 AM**, with a revision hour the day before.
- Assignments are **split across the two 1-hour slots** (part 1 plan and start, part 2 finish and submit), except DL Assignment 01, which has a full evening block on Day 7.
- **Deadline: 15 Oct 2026.** Finishing on 29 Sep leaves 16 days of margin.

Course content mapping (taken from the user's paste; the course's original dates and 4 PM times are deliberately dropped):
- **ML modules:** 01, 02, 03, 05, 06, 07, 08, 09, 10, 11, 12, 14, 15, 16, 18, 19, 20, 21, 22, 23 (20 modules). Module 04 and 17 appear to be Assignments 01 and 03; Module 13 is Assignment 02; Module 24 is the Final Exam.
- **DL modules:** 01–06, 08–13, 15–20 (18 modules). Module 07 is Assignment 01; Module 14 is the Mid Term.
- **Titles missing from the source:** ML Modules 11, 15 and 16. They appear in Notion as bare "Module 11" etc.

### 4.2 English (IELTS), paused

- 12 weeks + Week 0 baseline, **5:00–7:00 AM**, roughly 120 min a day.
- Writing days Mon/Wed/Fri, speaking days Tue/Thu/Sat, Sunday is rewrite plus leech review plus measurement.
- Week rows carry the metric properties; the `On target` formula scores each week out of 7.
- Weekly targets: retention 85–92%, new cards 55–85, collocations 15–30, **Stage 5 items 3–8 (the key metric)**, rewrite done, transcript minutes 120–180, leeches cleared.
- 12-week finish line: 5 graded readers, 34 hard texts, 60 episodes, 10 dictations, 12 essays, 10 rewrites, 40 recordings, about 800 cards, 3 mocks.
- Topics run one per fortnight: Education, Environment, Technology, Health, Crime, Work.
- **Assumptions to confirm:** Band 8 came from the user's older notes, not from them directly. Task 1 was missing from their system, so I added it every other Saturday. Anki deck and template setup is left to Week 0.

### 4.3 AWS, paused
The user's own plan: 10 modules over 10 days plus 3 buffer days, 10:00–11:00 AM and 2:00–3:00 PM. Rows are `Day N · Module X` with two session checklists. Currently dated 16–28 Sep, which now clashes with the sprint.

### 4.4 Skiena, not built
Their page says: 26 lectures (26–36 days), 5 homeworks (5–10 days), 2 midterms (3–6 days), 34–52 days total, **3 hours a day**. The database has no rows, only a "Quick Action Plan" template (`cf63592a-b337-8270-af76-01d5a23b8af8`).

---

## 5. Decision log

| Date | Decision | Why |
|---|---|---|
| 15 Sep | Goals get three layers: output count, quality trend, checkpoint | The user's notes described method but had no finish line |
| 15 Sep | English uses **weekly** rows; courses use **daily** rows | A week of habits is one unit; a course module is one unit |
| 15 Sep | English built into the existing empty `Action Plan - English` page | It already existed beside the other plans |
| 15 Sep | Added Task 1 practice to English | It was missing entirely and is a third of the writing score |
| 15 Sep | Phitron first drafted as 30 days at 2h (3–5 AM) | Original deadline of 15 Oct with everything else running |
| 15 Sep | Phitron rebuilt as a 6-day sprint at 10h a day | The user paused English, AWS and Skiena to focus |
| 16 Sep | Phitron rebuilt again: 11 days from 17 Sep, 2h per module | The user corrected the estimate to 1h45–2h per module |
| 16 Sep | The two 1-hour slots hold assignments and overflow only | A 2-hour module does not fit in a 1-hour slot |
| 18 Sep | Phitron shifted 2 days: now starts Sat 19 Sep, ends Tue 29 Sep | The user asked to start on 19 Sep; only dates moved, day contents unchanged |

**Recommendations the user has not yet acted on:** stagger the restart instead of running English, AWS and Skiena together (that is about 9h a day again); with the sprint ending 29 Sep, a proposed order is AWS from 30 Sep, English Week 0 from 30 Sep (Week 1 on Mon 5 Oct), Skiena after AWS.

---

## 6. Open items

1. **Shift AWS and English dates** now that the sprint ends 29 Sep. Both still show 16 Sep. Offered, awaiting a yes.
2. **Build the Skiena plan:** need a start date and a time slot. 3 hours a day, 34–52 days.
3. **Confirm the English target band** and the exam date, if there is one.
4. **Ask which Phitron modules are already done** if the user mentions prior progress; shift rows rather than rebuilding.
5. **ML Module 11, 15, 16 titles** are still unknown.

---

## 7. Notion MCP: how to do this without breaking things

The connection is `claude mcp add --transport http notion https://mcp.notion.com/mcp`, authenticated in this project. AI search is not on this plan; use plain `notion-search` with short keywords. Always `notion-fetch` `self` before the first search of a session.

**Order of operations when building a plan**
1. `notion-create-pages` for the hub page (or reuse an existing empty one).
2. `notion-create-database` with `parent.page_id` — it lands as a **non-inline** child.
3. `notion-update-page` with `replace_content`, ending with `<database url="…" inline="true">Title</database>` — this both embeds it inline and keeps it from being deleted.
4. `notion-create-pages` with `parent.data_source_id` for the rows (up to 100 per call; split large batches and run them in parallel).
5. `notion-update-view` to rename and sort the default view, `notion-create-view` for extra views.
6. Re-fetch the page and one row to confirm it rendered.

**Gotchas that cost time**
- `replace_content` **deletes child databases that aren't referenced** in the new content. It errors unless you pass `allow_deleting_content: true`. That is how the old 30-day database was retired; it went to Notion's Trash, not permanent deletion.
- **Rows cannot be deleted** through this MCP. To shrink a plan, either rewrite the existing rows or replace the whole database.
- Date properties are split: `date:Due:start`, `date:Due:end`, `date:Due:is_datetime`. Times must be **UTC**: 3:00 AM local is `T21:00:00.000Z` the previous day; 9:30 PM local is `T15:30:00.000Z` the same day.
- Checkboxes are `"__YES__"` / `"__NO__"`. Multi-select values are a JSON **string**: `"[\"ML\", \"DL\"]"`.
- Properties named `id` or `url` need a `userDefined:` prefix.
- `update_properties` and `replace_content` are separate calls. Doing both on one page in the same batch risks a race; run content first, then properties.
- Notion-flavoured Markdown: callout and toggle children must be **tab-indented**; escape `* ~ \` $ [ ] < > { } | ^`; tables are XML-ish `<table><tr><td>` and cells take rich text only; `<empty-block/>` for a blank line.
- Formula columns use `FORMULA('…')` in the `CREATE TABLE` DDL; `format(...) + " / 7"` works for a score string.
- Emoji are set through the `icon` field, not in the title.

---

## 8. Memory files

`C:\Users\ACC\.claude\projects\C--Users-ACC-project-action-plan\memory\`
- `MEMORY.md` — the index loaded every session.
- `ielts-english-action-plan.md`
- `phitron-aiml-action-plan.md`

Keep these in step with this file when plans change: the memory files hold the short version, this file the full one.
