# Project memory for Claude Code

You are working inside an MK-680 marketing agency repository. The agency runs one Instagram account for a fictional brand the team created and controls. Read this file before doing anything else.

## Brand voice

Major Motion Media speaks to small local business owners and startup founders in Hartford, CT who need marketing help but don't have an in-house team. It sounds innovative and knowledgeable — sharing real strategy and insight, not empty hype. It never condescends: no talking down to owners who are new to marketing, no jargon for jargon's sake, no assuming the audience doesn't already know their own business best.

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
