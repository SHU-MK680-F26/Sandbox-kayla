# ops

Operational evidence for the graded analysis deliverables.

- `run-log.md` — one line per agent run (date, agent, task, outcome, minutes of human intervention). Agents append to this automatically per CLAUDE.md.
- `intervention-log.md` — Thanksgiving Autonomy Stress Test: every human touch, logged to the minute. Hard cap 30 minutes.
- `cost-log.md` — Week 10: per-run token counts and estimated cost. Paste `/usage` attribution output and `total_cost_usd` from headless runs; label all figures as estimates unless they come from a Console invoice.
- `incidents/` — one file per agent failure worth a post-mortem: what happened, root cause, fix, prevention.
