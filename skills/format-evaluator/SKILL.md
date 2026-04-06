---
name: format-evaluator
description: Evaluate whether a capability idea is best deployed as a Claude Code plugin, slash command, skill, subagent, or agent workspace. Use when the user describes an idea and asks "should this be a skill / slash command / plugin / agent?" or wants a recommendation on packaging format before building.
---

# Format Evaluator

Decide the best packaging format for a Claude Code capability idea.

## When to use

Invoke when the user:
- Describes a workflow/idea and asks how to package it
- Says things like "should this be a skill or a slash command", "is this a plugin", "where should this live"
- Wants to convert an existing repo/workspace into a lighter format

## Reference

Read [`docs/format-rubric.md`](../../docs/format-rubric.md) in this repo for the full decision guide. The quick comparison table and the per-format "Use when / Don't use when / Signal phrases" sections are the primary decision aids.

## Procedure

1. **Clarify the idea** (if ambiguous): invocation trigger, state needs, who uses it, whether it ships to others.
2. **Apply the rubric** — walk the five formats (Plugin, Slash Command, Skill, Subagent, Agent Workspace) and note fit/misfit signals from the rubric.
3. **Score**: give each format a verdict — `GOOD_FIT` / `PARTIAL` / `POOR_FIT` — with one sentence of reasoning.
4. **Recommend**: pick one primary format. If a hybrid makes sense (e.g. "slash command that invokes a skill", or "plugin bundling two skills + an agent"), state the bundle.
5. **Output** in this shape:

   ```
   Idea: <one-line restatement>

   Verdicts:
   - Plugin: <GOOD/PARTIAL/POOR> — <reason>
   - Slash Command: …
   - Skill: …
   - Subagent: …
   - Agent Workspace: …

   Recommendation: <format(s)>
   Why: <2-3 sentences>
   Next step: <concrete first action, e.g. "scaffold SKILL.md at skills/<name>/">
   ```

## Heuristics cheatsheet

- **Model should reach for it automatically** → Skill
- **User types `/name` to trigger** → Slash Command
- **Heavy context / parallelizable side-quest** → Subagent
- **Long-lived domain with accumulating files** → Agent Workspace
- **Ships to others as a bundle** → Plugin (wrapping the above)

Stateless + narrow + procedural = almost always a Skill.
Stateful + ongoing + file-backed = almost always a Workspace.
