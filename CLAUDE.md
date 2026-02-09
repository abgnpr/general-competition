# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Purpose

Personal "second brain" for Indian banking exam preparation — IBPS PO/Clerk, SBI PO/Clerk, RBI Grade B, NABARD, SEBI, and related exams. This is a content-and-tools repo, not a software project.

## Repository Structure

- **`strategy/`** — The backbone. Contains the strategic preparation framework: goals, exam differences, prep philosophy, common subject base, exam-specific layers, timetable, readiness checkpoints. Always read relevant strategy files before making changes to understand context.
- **`plans/`** — Actionable study plans, schedules, and progress logs.
- **`notes/`** — Subject-wise study notes organized by topic (quantitative-aptitude, reasoning, english, general-awareness, banking-awareness, finance-and-economics, computer-knowledge).
- **`exams/`** — Exam-specific information (syllabus, pattern, cutoffs) per exam (ibps-po, ibps-clerk, sbi-po, sbi-clerk, rbi-grade-b, nabard, sebi).
- **`docs/`** — GitHub Pages site with interactive HTML study tools (multiplication tables, squares, cubes). Deployed from `docs/` folder on `main` branch.

## Working with Content

- All notes and strategy documents are Markdown (`.md`).
- HTML tools in `docs/` are pure HTML/CSS/JS with no build step. `docs/styles.css` is the shared stylesheet.
- When adding a new HTML tool: create a subfolder under `docs/`, add an `index.html`, link it from `docs/index.html`, and use the shared stylesheet.
- When adding notes for a new topic: place them in the appropriate `notes/<subject>/` folder.

## GitHub Pages

The site is served from the `docs/` directory on the `main` branch. No build step required — just push and it's live.
