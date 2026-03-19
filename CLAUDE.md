# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

College coursework for Ruppin Academic Center, organized by academic year.

| Directory | Semester | Notes |
|-----------|----------|-------|
| `Ruppin-Assignments-2025/` | 2025 (Year 1) | Solo work |
| `Ruppin-Assignments-2026A/` | 2026A (Year 2, Sem 1) | Paired with Aviv Itzhak. Has its own CLAUDE.md |
| `Ruppin-Assignments-2026B/` | 2026B (Year 2, Sem 2) | **Public** portfolio repo. Curated finished work only |

## 2026B Structure

Unlike previous semesters, 2026B has different teammates for different courses.

### How it works

- **Private course repos** (`WebDev-Server-Side/`, `Software-Systems-Engineering/`) — live as siblings in `Ruppin/`. This is where actual development happens with teammates. May contain sensitive data, drafts, credentials, etc.
- **Public portfolio** (`Ruppin-Assignments-2026B/`) — a curated showcase. Only **selected, finished, cleaned** work gets copied here. Credit teammates and link their GitHub profiles. Never auto-sync or bulk-copy from private repos.

### Private Course Repos (sibling directories)

| Directory | Course | Teammate(s) |
|-----------|--------|-------------|
| `WebDev-Server-Side/` | Web Development - Server Side (.NET 6/C#) | TBD |
| `Software-Systems-Engineering/` | Software Systems Engineering | TBD |

### Portfolio Structure (Ruppin-Assignments-2026B)

| Folder | Course | Type |
|--------|--------|------|
| `WebDev-Server-Side/` | Web Dev Server Side | Selective showcase from private repo |
| `Software-Systems-Engineering/` | Software Systems Engineering | Selective showcase from private repo |
| `Calculus-2/` | Calculus 2 | Solo |
| `Computational-Models/` | Computational Models | Solo |
| `Entrepreneurship/` | Advanced Entrepreneurship Skills | Solo |
| `personal/` | Misc personal work | Solo |

## Conventions

- Assignment folders: `{N}A-{CourseName}/` (e.g., `1A-WebDev/`)
- Each course repo should have its own README.md with syllabus and setup info
- File names in English only
- When publishing to the portfolio: remove credentials, API keys, .env files, and any sensitive data before copying
- Credit teammates in the portfolio README with name and GitHub link
