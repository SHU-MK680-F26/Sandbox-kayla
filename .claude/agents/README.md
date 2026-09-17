# Agents

Each markdown file in this folder is one agent. Claude Code discovers them automatically and can delegate to them as subagents.

Minimum roster by Week 3: `strategist.md`, `content-creator.md`, `analytics.md`, `engagement.md`, `qa-governance.md`. A `lead.md` orchestrator is added in Week 10.

## File format

```markdown
---
name: content-creator
description: Drafts channel-ready social posts and captions in the brand voice. Use when the task is producing or revising content.
tools: Read, Write, Edit, Grep, Glob, WebSearch, WebFetch
model: inherit
---

(The system prompt / job description goes here, in plain English.)
```

Field notes:

- `name` is lowercase with hyphens and must match how other agents refer to it.
- `description` is what the lead agent reads when deciding whom to delegate to — make it specific.
- `tools` limits what the agent may do. A QA agent that only reads and reports should not have `Write` or `Bash`.
- `model` can be `inherit`, `sonnet`, `opus`, or `haiku`. Use `haiku` for cheap, repetitive checks.

Three starter agents ship in this folder (`strategist.md`, `content-creator.md`, `qa-governance.md`); add `analytics.md`, `engagement.md`, and later `lead.md` yourself. See `content-creator.md` for the pattern, and the Claude Code subagent documentation: https://code.claude.com/docs/en/sub-agents
