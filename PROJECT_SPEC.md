# Project Spec

## Purpose
A community-maintained knowledge vault of manuals, lists, cheatsheets, and tools for DevOps, security, sysadmins, and power users. The canonical content lives in `README.legacy.md`, while `README.md` serves as a high-level launch pad.

## Current Maintenance Posture
Community-fork maintenance. Open PRs are periodically merged on the fork to keep the knowledge index fresh. Conflicts are resolved deterministically to keep momentum moving.

## Merged PR Summary (This Run)
- Total open PRs processed: 101
- Merged cleanly: 57
- Merged with deterministic conflict resolution: 44 (used `-X theirs` strategy on conflicts)
- Skipped: 0

## Unresolved Risks
- Deterministic conflict resolution may have accepted upstream changes that need manual review for correctness or duplication.
- README-heavy merges can reorder or overwrite list items; content may need spot checks in key sections.
- Some new files (workflows, security policy, devcontainer) were added by PRs and may need policy alignment.

## Setup Instructions
- Clone the repo: `git clone https://github.com/friuns2/the-book-of-secret-knowledge.git`
- Open the full index: `README.legacy.md`
- Review contribution rules: `.github/CONTRIBUTING.md`

## Next Maintenance Actions
- Spot-check recent README sections for duplicates or broken links.
- Validate new workflow and security policy files match desired governance.
- Periodically rerun PR sweep and update README.legacy.md if reorganizing.
