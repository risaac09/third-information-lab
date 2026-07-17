# CLAUDE.md

## What this repo is
The public single-page site for the Third Information Lab, the AI iteration of the Material & Meaning institute. Vanilla HTML + CSS, no build step, GitHub Pages from the repository root. The institute's substance lives in `material-and-meaning-institute` (private); this repo is only the public face.

## The one guardrail
Keep claims honest for funders: a project, not a mega-institute; public clinical evidence only for the current audit phase; fiscal sponsor status accurate. Never copy anything from material-and-meaning-institute's `org/` into this repo, a commit message, or PR text.

## Routing
- Tier: none, a public-facing site, not a stack-data consumer. The spine is stack-data, Tier 1, the operational source of truth, a sibling clone (`../stack-data`).
- The six phase-zero trigger phrases work here through the deployed `.claude/` kit: "activate all agents", "engage global awareness", "refresh global awareness", "delegate to your orchestrator", "engage the orchestrator", "engage your orchestrator".
- Route research, citation, and lineage tasks to stack-data and its `research-bibliographer` agent.
- Session close is "log learnings"; it runs the retrospective from the kit.
