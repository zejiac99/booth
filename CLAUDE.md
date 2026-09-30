# Working in this repo

This repo holds coursework for Chicago Booth, organized as `<quarter>/<course>/`.

## Scope rule

Only use materials from the course or quarter I'm currently working on.

- Do not read, search, or reference files in other courses or other quarters unless I explicitly ask.
- When searching, restrict Glob/Grep to the relevant course folder, not the repo root.
- If something in another course looks relevant, mention that it exists and ask before opening it.
- If I do ask for a cross-reference, use it for that request only.

If it isn't clear which course I mean, ask.

## Conventions

- Quarter folders: `YYYY-season` (e.g. `2026-autumn`).
- Course folders: `BUSN ##### - Course Title` (e.g. `BUSN 30000 - Financial Accounting`). Quote paths in shell commands because of the spaces.
- There are no per-course `CLAUDE.md` files. This file is the only one; course-specific context comes from the syllabus in each course folder.
- Week folders: `Week N - Topic` (e.g. `Week 1 - The Power of the Situation`).
- Files: Title Case with spaces, no `(1)`-style download suffixes. Syllabi are named `BUSN ##### Syllabus.<ext>` when there's no official filename.
- Course documents (PDFs, slides, docx, readings) are committed to git on purpose. Only archives such as `.zip` are ignored; see `.gitignore`. Flag it if a single file gets very large (roughly 50 MB or more).
