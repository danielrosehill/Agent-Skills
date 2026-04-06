---
description: Convert a candidate idea or existing repo into a SKILL.md under skills/
---

Convert the target into a proper Claude Code skill in this repo.

Target: $ARGUMENTS

Steps:
1. If the target references an existing repo, fetch its README (via `gh api repos/<owner>/<repo>/contents/README.md -q .content | base64 -d`) to understand scope.
2. Run `format-evaluator` first (read `skills/format-evaluator/SKILL.md` + `docs/format-rubric.md`). If the verdict is NOT `GOOD_FIT` as a skill, stop and report the recommended format instead.
3. If skill-shaped, scaffold `skills/<kebab-name>/SKILL.md` with YAML frontmatter (`name`, `description`) + body sections: When to use, Procedure, Reference (link upstream repo if any).
4. Keep the description specific and trigger-oriented so the model knows when to invoke it.
5. If the candidate lives in `candidates/*.md`, move/strike it from there and mention the conversion in the commit message.
6. Report the new skill path and a one-line summary. Do not commit unless explicitly asked.
