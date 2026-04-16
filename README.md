---
title: Home
layout: home
nav_order: 1
---

# Banking Exam Preparation — Second Brain

Personal knowledge base and strategy layer for Indian banking and insurance competitive exams. Used as the **strategic resource for planning and critical notes** — not a problem bank.

## Target Exams

- IBPS PO / Clerk
- SBI PO / Clerk
- RBI Grade B
- NABARD Grade A/B
- SEBI Grade A
- LIC AAO and allied insurance exams

## Current Focus

**Quantitative Aptitude.** Plans and notes are currently optimized for building a strong, exam-agnostic quant base using the **Pareto (80/20) principle** — prioritize the 20% of topics that decide 80% of quant marks (Arithmetic core + DI), and treat everything else as secondary.

Start here → [plans/quant-starter-plan.md](plans/quant-starter-plan.md)

### Other active plans

- [plans/english-starter-plan.md](plans/english-starter-plan.md) — Pareto plan for English (RC + Cloze + Grammar basics).
- [plans/descriptive-starter-plan.md](plans/descriptive-starter-plan.md) — Two-track descriptive writing (Track A: PO letter/essay; Track B: RBI/NABARD/SEBI Phase 2 theme-based).

## AI-Assisted Study Workflow

This repo is the **persistent memory layer** for AI-assisted prep. Every new chat starts blank — but files here are readable by Claude, so all plans, progress, and insights live in files, not in conversation.

### Per-chapter loop

Open a chapter with one line:

```text
Start chapter: <name>. Day 1 of the loop from plans/quant-starter-plan.md.
```

Claude reads the plan, runs the 6-day loop (concept map → worked examples → speed drill → mixed recall → traps + shortcuts → DI integration). You distill each session into the chapter note.

Close a chapter:

```text
Finish chapter: <name>. Update checkpoint in quant-starter-plan.md and log progress.
```

### The three files that do 90% of the work

1. **`notes/<subject>/<chapter>.md`** — distilled concept map, formulas that matter, traps, shortcuts, revision triggers. Max 1–2 pages per chapter.
2. **[`plans/progress-log.md`](plans/progress-log.md)** — one line per session. Claude reads this to resume context instantly.
3. **[`notes/quantitative-aptitude/mistake-log.md`](notes/quantitative-aptitude/mistake-log.md)** — cross-chapter recurring error patterns. Gold for revision week.

### Minimum ritual per session

```text
1. "Check progress-log and quant-starter-plan. What's next?"
2. Claude says the next step.
3. Do the work.
4. "Log today: <one line>. Update chapter note with <insight>."
```

No re-context, no re-planning. Files do the remembering.

## Structure

| Folder | What's Inside |
|--------|--------------|
| `strategy/` | Preparation framework — goals, philosophy, timetable, readiness checkpoints |
| `plans/` | Study plans, schedules, progress tracking |
| `notes/` | Subject-wise notes (Quant, Reasoning, English, GA, Banking, Finance, Computer) |
| `exams/` | Exam-specific syllabus, pattern, and cutoff info |
| `docs/` | Interactive HTML study tools (GitHub Pages) |

## GitHub Pages

The entire repo is served as a Jekyll site using the [Just the Docs](https://just-the-docs.com/) theme. All markdown files are rendered as navigable web pages with a sidebar and search.

**Setup:** GitHub Pages source should be set to **`/` (root)** on the `main` branch.

### Interactive Study Tools

The `docs/` folder hosts standalone HTML tools:

- **Multiplication Tables** (1–30)
- **Squares** (1–100)
- **Cubes** (1–50)

To view locally, run `bundle exec jekyll serve` or open the HTML files in `docs/` directly in a browser.
