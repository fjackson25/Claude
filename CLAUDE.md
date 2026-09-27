# CLAUDE.md — Project Memory

This file is Claude's persistent memory for this project. Claude Code loads it automatically at the start of every session, so anything recorded here carries forward.

**Maintenance rule:** Claude updates this file whenever something worth remembering comes up: decisions, conventions, preferences, setup steps, open questions. Keep entries short and current, and remove anything that goes stale.

## Project overview

- **Created:** 2026-09-27
- **Owner:** fjackson25
- **Repository:** fjackson25/claude
- **Purpose:** Currently a minimal "Hello" website, built as a first test of how Claude works.

## Tech stack

- Plain static HTML + inline CSS, no build step or dependencies.
- `index.html` at the repo root is the whole site.

## Commands

- **View locally:** open `index.html` in a browser, or run `python3 -m http.server 8000` and visit http://localhost:8000.

## Conventions & preferences

- Store project memory in this file (CLAUDE.md).

## Decisions log

| Date | Decision | Reason |
|------|----------|--------|
| 2026-09-27 | Created CLAUDE.md as the project's memory file | User request |
| 2026-09-27 | Built a single-page "Hello" site in plain HTML/CSS | User wanted a very simple site to see how Claude builds things; no framework needed |

## Open questions / next steps

- Define the real project's goal and scope beyond the Hello test page.
- Decide on hosting (e.g. GitHub Pages) if the site should be public.
