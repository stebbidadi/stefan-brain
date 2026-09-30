# Stefan Brain

> Personal knowledge-base and AI workflow project.

## Status
**Status:** Active  
**Last updated:** 2026-09-30

## Goal
Provide reliable cross-device context while minimizing repeated context reconstruction, tool calls, and token usage.

## Architecture
- GitHub repository: `stebbidadi/stefan-brain`
- ChatGPT: reasoning and conversation layer
- GitHub connector: cross-device knowledge access
- Codex Cloud: private `stefan-brain` environment for repository maintenance; published 2026-09-30, but task launch has not yet succeeded
- Obsidian: planned local editing interface
- Weekly automation: maintain durable project context

## Core Files
- [AI_MASTER_RULES.md](../../AI_MASTER_RULES.md) — canonical operating rules
- [PROJECTS.md](../../PROJECTS.md) — project routing index
- [USER_PROFILE.md](../../USER_PROFILE.md) — stable general context
- [INBOX.md](../../INBOX.md) — temporary staging area for durable information awaiting routing
- `projects/<name>/PROJECT.md` — project-specific source of truth

## Operating Rules
Use [AI_MASTER_RULES.md](../../AI_MASTER_RULES.md) as the canonical source for context retrieval, Work Mode decisions, and knowledge-base updates.

## Codex Cloud Status
- **2026-09-30:** Environment published with GitHub read access verified during setup and reusable startup guidance saved. No dependencies or services are required.
- New-task submission currently returns `Unable to determine project root for task` in both the user's browser and the cloud browser. The cause is unconfirmed.
- Continue maintenance through the GitHub connector while troubleshooting. Retry from the main computer and verify a task can access the repository before treating Cloud as operational.

## Next Actions
- Verify the published Codex Cloud environment can launch a repository task.
- Set up Obsidian on the main computer.
- Review usage after the weekly automation has run a few times.
- Split project files only when growth makes targeted retrieval worthwhile.
