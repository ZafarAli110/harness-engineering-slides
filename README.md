# Harness Engineering and AI SDLC with Claude Code

The slides of the Contour Software Engineering workshop **"Harness Engineering and AI SDLC with Claude Code: From
Ticket to Verified PR"** (November 2026): how an AI model becomes a coding agent, and how a coding agent fits into
software delivery.

**Open them:** https://zafarali110.github.io/harness-engineering-slides/

Arrow keys or Space to move, **N** for the speaker notes, **M** for the course map, **H** to hide the controls. Or download `index.html` and open
it in any browser: it works offline.

## What it covers, and what it leaves out

A focused workshop: two sessions of two hours, on one question, how to make a coding agent reliable in real software
delivery. It covers how a model becomes a coding agent (tokens, sampling, the agent loop, and the harness around it:
rules, tools, permissions, limits, verification), then how Claude Code fits a team's delivery: `CLAUDE.md`, MCP, hooks,
subagents, permissions, skills, verification, plans, QA, reviewers, ticket to pull request, and working within a token
budget.

It leaves out, on purpose, topics that deserve their own workshop: embeddings and vector databases, retrieval-augmented
generation (RAG), fine-tuning and training models, and building your own LLM applications on a model's API.

## The code

The code from the workshop:

- [tiny-harness](https://github.com/ZafarAli110/tiny-harness): Session 1's agent, built in six steps
- [acme-dms](https://github.com/ZafarAli110/acme-dms): Session 2's labs (`lab/00-start` to `lab/10-ticket-to-pr`)
- [acme-tracker](https://github.com/ZafarAli110/acme-tracker): the ticket board
- [claude-code-cost-meter](https://github.com/ZafarAli110/claude-code-cost-meter): the cost meter plugin
- [agent-slides](https://github.com/ZafarAli110/agent-slides): the engine these slides are built with
