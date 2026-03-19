# Changelog

## 2026-03-19 (evening)

### Merge-With-Ruppin-repo list cleanup

- Verified and deleted 3 duplicate GitHub repos: `C-practice`, `Python-Matala-Final`, `Pr` — all content already existed in `Ruppin-Assignments-2025/`
- Pushed Year 1 coursework (531 source files) to `Ruppin-Assignments-2025` remote (was empty since creation)
- Updated `Ruppin-Assignments-2025/.gitignore`: replaced blanket `pr/` ignore with targeted excludes for PDFs, exams, build artifacts, and binaries
- Removed 17 nested `.git` directories from `courses2025/` subfolders (former standalone repos)
- Skipped `AI-pr` merge (private, contains exam/slide materials) — added to BACKLOG.md
- Created `BACKLOG.md` for pending repo tasks

## 2026-03-19

### Repo Organization (2026B semester setup)

- Created `Ruppin/` as public meta-repo with timeline README
- Established 2026B structure: private repos for shared courses, public portfolio for curated work
- Created `WebDev-Server-Side/` repo (private) — tidied files: renamed Hebrew filenames to English, extracted links into README, added .gitignore
- Created `Software-Systems-Engineering/` repo (private) — initialized with syllabus, README, .gitignore
- Set up `Ruppin-Assignments-2026B/` portfolio with 5 course folders (WebDev Server Side, SSE, Calculus 2, Computational Models, Entrepreneurship), each with syllabus and README
- Initially tried git submodules to link shared repos into portfolio — reverted after realizing private repos can't be viewed through submodules in a public repo

### Older Repo Cleanup

- Updated `Ruppin-Assignments-2025/` README to uniform format (added partner credits: Maayan Retter for C# and Python)
- Updated `Ruppin-Assignments-2026A/` README to uniform format (removed emojis, consistent table style, renamed "Client-Side Web Development" to "Web Dev — Client Side")
- Removed 81 junk files from 2026A git tracking: 18 `.class` files, 55 `desktop.ini`, 8 Word temp `~$` files
- Updated 2026A `.gitignore` to block `.class`, `desktop.ini`, `Thumbs.db`, `~$*`
- Fixed 2026A remote URL from `WebDev-Assignments` to `Ruppin-Assignments-2026A`

### Security

- Ran sensitive data scan across all public repos
- All clean — student IDs and personal data only exist in gitignored local directories
- Briefly redacted a course-provided API key in 2026A, then restored it (shared key, not a personal secret)

### Files Created

- `Ruppin/README.md` — timeline view of CS degree
- `Ruppin/CLAUDE.md` — project guide for Claude Code
- `Ruppin/CHANGELOG.md` — this file
- `Ruppin/PROGRESS.md` — academic progress tracker
