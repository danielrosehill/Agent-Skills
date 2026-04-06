---
description: Spin out a logical group of skills (or a single skill) into its own dedicated GitHub repo
---

Extract a skill or bundle of related skills from this repo into a new standalone GitHub repo (useful when a bundle outgrows the monorepo or warrants independent distribution as a plugin).

Target: $ARGUMENTS  (single skill name, comma-separated list, or category like `candidates/research-intelligence.md`)

Steps:
1. Identify the target skills under `skills/` (or candidates to promote).
2. Decide the new repo name (kebab-case, descriptive) and confirm with the user.
3. Create the repo: `gh repo create danielrosehill/<name> --private --description "<desc>"` (ask before making public).
4. Scaffold the new repo locally under `~/repos/github/<name>/` with:
   - `README.md` (purpose, install, list of skills)
   - `skills/<each>/SKILL.md` copied from this repo
   - `.claude-plugin/plugin.json` if it's a plugin bundle (see Claude Code plugin docs)
   - `LICENSE` if appropriate
5. Initial commit + push.
6. In THIS repo, replace the extracted skill folder(s) with a stub `README.md` pointing to the new repo, OR delete entirely if clean extraction — ask the user which.
7. Report both repo URLs.

Do not execute destructive steps (repo create, delete) without user confirmation.
