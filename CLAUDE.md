# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Purpose

Personal "second brain" for Indian banking exam preparation — IBPS PO/Clerk, SBI PO/Clerk, RBI Grade B, NABARD, SEBI, and related exams. This is a content-and-tools repo, not a software project.

## Repository Structure

- **`strategy/`** — The backbone. Contains the strategic preparation framework: goals, exam differences, prep philosophy, common subject base, exam-specific layers, timetable, readiness checkpoints. Always read relevant strategy files before making changes to understand context.
- **`plans/`** — Actionable study plans, schedules, and progress logs.
- **`notes/`** — Subject-wise study notes organized by topic (quantitative-aptitude, reasoning, english, general-awareness, banking-awareness, finance-and-economics, computer-knowledge).
- **`exams/`** — Exam-specific information (syllabus, pattern, cutoffs) per exam (ibps-po, ibps-clerk, sbi-po, sbi-clerk, rbi-grade-b, nabard, sebi).
- **`docs/`** — Interactive HTML study tools (multiplication tables, squares, cubes). Standalone HTML/CSS/JS.

## Working with Content

- All notes and strategy documents are Markdown (`.md`) with Jekyll front matter (title, parent, nav_order).
- HTML tools in `docs/` are pure HTML/CSS/JS with no build step. `docs/styles.css` is the shared stylesheet.
- When adding a new HTML tool: create a subfolder under `docs/`, add an `index.html`, link it from `docs/index.md`, and use the shared stylesheet.
- When adding notes for a new topic: place them in the appropriate `notes/<subject>/` folder with front matter (`title`, `parent: <Subject Title>`, `nav_order`).
- When adding a new markdown file: always include Jekyll front matter with `title`, `parent` (matching the section's index.md title), and `nav_order`.

## Jekyll & GitHub Pages

- The site uses the [Just the Docs](https://just-the-docs.com/) Jekyll theme (v0.10.1) via `remote_theme`.
- GitHub Pages source: **`/` (root)** on the `main` branch (NOT `docs/`).
- `_config.yml` at repo root controls theme, navigation, and excluded files.
- All `.md` files with front matter become navigable pages with sidebar and search.
- HTML tools in `docs/` are passed through as-is (no Jekyll layout wrapping).
