# Repository Guidelines

This repository currently hosts the MVP product requirements for SipSession. Contributions should keep documentation clear, dated, and easy to scan.

## Project Structure & Module Organization
- `PRD/` contains product requirements and planning documents.
- Current primary document: `PRD/SipSession_PRD_MVP.md`.
- There is no source code, tests, or assets directory yet. If you add new areas, prefer descriptive top-level folders (e.g., `docs/`, `ios/`, `watchos/`) and update this guide accordingly.

## Build, Test, and Development Commands
- No build or test tooling is defined in this repo yet.
- If you introduce build or test scripts, document them here with one-line explanations (example format: `make test` — run unit tests).

## Coding Style & Naming Conventions
- Markdown only at present: use ATX headings (`#`, `##`), short paragraphs, and bullet lists.
- Keep dates in `YYYY-MM-DD` format to match existing docs.
- File naming: follow the established PRD pattern `SipSession_<TYPE>_<SCOPE>.md` (e.g., `SipSession_PRD_MVP.md`).
- Indentation: two spaces for nested lists.

## Testing Guidelines
- No test framework or coverage requirement is defined yet.
- When code is added, place tests alongside platform code or in a clearly named `tests/` directory and document the framework here.

## Commit & Pull Request Guidelines
- No Git history is available in this workspace, so there is no established commit convention.
- Recommended: use Conventional Commits for clarity (e.g., `docs: refine MVP success metrics`).
- PRs should include: a short summary, rationale for changes, and any affected PRD sections. Add screenshots only if you introduce UI mockups.

## Domain Constraints for Docs
- Do not introduce guidance that implies safety or medical conclusions; keep phrasing aligned with the MVP scope (tracking and reporting only).
- If you add new requirements, mark MVP boundaries explicitly (e.g., “out of scope for MVP”).
