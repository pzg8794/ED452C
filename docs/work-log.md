# ED452C Work Log

## 2026-06-03 - Sync remote posts and local June materials

### Work completed

- Removed stray zero-byte Finder `Icon` metadata files from `.git`, `sessions/`, and `transcripts/` after they broke Git ref/history commands.
- Pulled the latest `origin/main` into local `main`, bringing in Session 4 and Session 5 discussion posts and reading-summary updates.
- Added local Wehmeyer/Kurth reading PDFs for pages 41-46 and 47-56.
- Added local May 26 course transcript files under `transcripts/`.
- Normalized the untracked local `Wehymeyer` filename to `Wehmeyer` before staging.
- Updated `README.md`, `docs/course-map.md`, `docs/discussion-log.md`, and `docs/source-map.md` so repository documentation matches the current file tree.

### Decisions made

- Keep new course transcripts in `transcripts/` and track their provenance in `docs/source-map.md`.
- Continue marking Blackboard submission status only when independently verified.

## 2026-05-26 - Sync remote posts and local reading materials

### Work completed

- Pulled the latest `origin/main` commits into local `main`.
- Brought in remote documentation/discussion updates, including `discussions/session-03-discussion-post.md` and `docs/readings-summary-discussions-1-3.md`.
- Added local Session 3-12 reading packets and supplemental transition/self-determination PDFs under `sessions/`.
- Normalized untracked local filenames before committing by removing extra spaces before `.pdf` and correcting `Wehymeyer` to `Wehmeyer` in the Session 3 Wehmeyer/Kurth file.
- Updated `docs/course-map.md`, `docs/discussion-log.md`, and `docs/source-map.md` so the repository documentation matches the current file tree.

### Decisions made

- Preserve the actual reading PDFs in `sessions/` and keep interpretation/summaries in `docs/`.
- Mark discussion posts as present/finalized only when visible in the repo; do not mark Blackboard submission as verified without direct evidence.

## 2026-05-21 - Session 2 discussion and repo documentation

### Work completed

- Created a local Git repository for ED452C and pushed it to GitHub as `pzg8794/ED452C`.
- Reviewed the ED452C repository structure.
- Identified visible session materials and assignment PDFs.
- Verified that Session 2 materials include the Session 2 slide deck, Session 2 readings, and Wehmeyer & Kurth 2021 pages 1-6.
- Used authenticated GitHub access to confirm `pzg8794/teaching-placement` is private and available on default branch `teaching_placement_shared`.
- Used TeachingPlacement, EDE498C, ED452B, EDU442, and ED400 repository context to personalize the Session 2 discussion post and documentation.
- Drafted a Blackboard-ready Session 2 discussion post.
- Replaced the first draft with the finalized Blackboard-ready version, including the equity framing about digital tools, Tier 1 noticing routines, and the final discussion question.
- Created documentation files for future portfolio tracking.

### Decisions made

- Keep weekly discussion posts in `discussions/`.
- Track every discussion post in `docs/discussion-log.md`.
- Track external/source provenance in `docs/source-map.md`.
- Use `portfolio/puzzle-plan-evidence-map.md` to connect course work to the larger portfolio puzzle plan.
- Do not publish raw student work or private placement records.
- Use de-identified placement patterns and public-safe source summaries instead.

### Current open items

- Mark the Session 2 discussion as submitted in `docs/discussion-log.md` after it is posted to Blackboard.
- Add future sessions to the discussion log as they are drafted.
