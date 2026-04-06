---
description: Audit and improve documentation for an existing skill in skills/
---

Document or improve an existing skill's SKILL.md so it's discoverable and invocation-ready.

Target skill: $ARGUMENTS  (path under `skills/` or skill name)

Steps:
1. Read the existing `skills/<name>/SKILL.md`.
2. Check the YAML frontmatter — `name` must match the folder; `description` must be specific, trigger-oriented (mention the user signals that should invoke it), and under ~500 chars.
3. Ensure the body has: **When to use**, **Procedure**, **Reference** (upstream repos, docs). Add examples if missing.
4. If the skill bundles multiple steps, verify they're numbered and concrete.
5. Cross-link to `docs/format-rubric.md` if relevant.
6. Report what you changed. Do not commit unless asked.
