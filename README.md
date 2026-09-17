# MK-680 Agent Workgroup Repository

This repository is the "office" for one MK-680 team (or one student's sandbox). Everything the team produces lives here: the agents themselves, brand guidance, strategy, content awaiting approval, reports, and operations logs.

## Team roster

| Role | Name | GitHub username |
|---|---|---|
| Production operator (runs Claude Code) | | |
| Team member | | |
| Team member | | |
| Team member | | |

## Brand

Your team's fictional brand and its Instagram account (finalized in Week 4). Do not put follower lists, email lists, or any personal data in this repository.

## How to run the workgroup

1. Pull the latest `main`.
2. Open Claude Code in this folder (`claude`). It reads `CLAUDE.md` automatically and discovers agents in `.claude/agents/`.
3. Ask the lead agent to run the weekly cycle, e.g. `Run this week's production cycle: calendar → drafts → QA → queue for approval.`
4. Everything that will be published is committed on a branch and opened as a pull request. A teammate reviews against the PR checklist and merges. Nothing is posted without a merged PR.

## Folder map

| Path | Purpose |
|---|---|
| `CLAUDE.md` | Project memory Claude Code reads every session: brand voice, standards, rules of engagement |
| `.claude/agents/` | One markdown file per agent (job description, tools, handoffs) — the workgroup itself |
| `.claude/settings.json` | Shared Claude Code permissions for this project (web access pre-approved) |
| `brand/` | Brand voice guide, compliance checklist, agency charter (Week 4) |
| `strategy/` | Strategy documents, sprint roadmaps |
| `content/` | Produced content packages, calendars, drafts awaiting approval |
| `reports/` | Analytics agent outputs, weekly reports, GEO audit |
| `ops/` | Ops logs, intervention logs, cost tracking, incident reports |
| `.github/PULL_REQUEST_TEMPLATE.md` | The approval-gate checklist every PR must complete |

## Ground rules

- No secrets in this repository — no passwords, API keys, tokens, or data exports containing personal information. `.gitignore` blocks the usual suspects, but it is your responsibility.
- No login sharing. Claude and GitHub accounts are individual.
- Nothing gets published without passing the pull-request approval gate.
- Agents touch the team's channels only through official APIs or vendor-supported integrations (Buffer, Meta Business Suite, Brevo). No browser automation, session cookies, or unofficial libraries.
- Honest logs. Fabricating ops data is academic dishonesty; reporting a failure is rewarded.
