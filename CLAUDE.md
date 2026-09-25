# Project memory for Claude Code

You are working inside an MK-680 marketing agency repository. The agency runs one Instagram account for a fictional brand the team created and controls. Read this file before doing anything else.

## Brand voice

Miles After Five is a social run club speaking to 21–35-year-olds scrolling around 5pm who want to stay active, meet people, and have something to look forward to after work. The voice is active, motivational, and fun: it pushes people out the door with energy, never with guilt, and never shames anyone's pace, body, or fitness level. Before writing or reviewing any caption, read brand/voice.md for the full audience, phrases, hard rules, and checklist.

## Standards for all produced content

- Every draft goes in `content/` as a markdown file with a YAML header: `channel`, `date`, `status: draft | approved | published`, `author-agent`.
- Captions include a suggested image description, hashtags on a separate line, and a character count.
- Never invent facts about the brand: prices, hours, ingredients, awards, statistics. If it is not written down in `brand/` or `strategy/`, write `[NEEDS TEAM CONFIRMATION]` inline.
- Never write anything that reads as a health, financial, or legal claim.
- The account bio identifies it as a student project for a fictional brand; label AI-generated media where Instagram's tools ask (see `brand/agency-charter.md` once it exists).

## Rules of engagement

- Do not publish anything. Your job ends when a draft is committed on a branch and a pull request is opened. A human approves and publishes.
- Do not store or process personal data (email lists, follower names, DM contents). Work from aggregated exports only.
- Do not use browser automation or unofficial APIs for any platform.
- When you use web search or fetch a page, cite the URL in your output.
- Log every run: append one line to `ops/run-log.md` with the date, agent, task, outcome, and any human intervention.

## Working style

- Prefer small, reviewable pull requests: one content package or one report per PR.
- Write commit messages a marketing manager can read.
- When you are unsure, stop and ask rather than guess.
