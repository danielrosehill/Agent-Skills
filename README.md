# Agent-Skills

Collections of agent skills I've created.

## North Star

Skills in this repo target the emerging open standard at **[agentskills/agentskills](https://github.com/agentskills/agentskills)** — the reference we're developing against.

## Related

- [Claude-Code-Projects-Index](https://github.com/danielrosehill/Claude-Code-Projects-Index) — source index of personal Claude Code repos that feed the candidate backlog.

## Structure

- [`skills/`](./skills) — Skills already created (first: [`format-evaluator`](./skills/format-evaluator/SKILL.md))
- [`docs/format-rubric.md`](./docs/format-rubric.md) — Decision guide: plugin vs slash command vs skill vs subagent vs workspace
- [`.claude/commands/`](./.claude/commands) — Slash commands: `/evaluate-format`, `/convert-to-skill`, `/document-skill`, `/bundle-skills`
- [`.claude/agents/`](./.claude/agents) — Subagents: `skill-converter`, `format-rubric-reviewer`
- [`candidates/`](./candidates) — Not-yet-planned skill ideas, split by category
- [`planned/`](./planned) — Skills planned / to be developed
