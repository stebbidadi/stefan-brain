# Stefan Brain

> Personal knowledge-base and AI workflow maintenance project.

## Status
**Status:** Active  
**Last updated:** 2026-09-30

## Goal
Provide reliable cross-device context while minimizing repeated context reconstruction, tool calls, token usage, and workflow friction.

## Project Scope
This is the default project for general fixes and improvements to Stefan Brain and the surrounding ChatGPT workflow.

Use it for:
- Knowledge-base structure, routing, cleanup, and repository hygiene
- Context retrieval reliability and cross-device consistency
- Token-efficiency and unnecessary-tool-call reduction
- ChatGPT workflow, Work/Codex/plugin/connector integration, and automation improvements
- Audits for duplicate, stale, conflicting, or missing guidance
- Improvements to `AI_MASTER_RULES.md`, `PROJECTS.md`, project conventions, and maintenance processes

Do not route normal domain work here just because Stefan Brain is being used for context. Keep domain work in its own project unless the task is specifically about improving how the brain/workflow handles that domain.

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

For maintenance work:
1. Prefer fixing the smallest relevant source-of-truth file rather than adding new guidance elsewhere.
2. Avoid duplicate rules across files unless duplication materially improves routing.
3. Preserve working behavior and important context when simplifying.
4. Treat reliability and token efficiency as joint goals; do not reduce context so aggressively that answers become less accurate.
5. Record durable workflow decisions here; keep temporary experiments out unless they become part of the standard workflow.

## Codex Cloud Status
- **2026-09-30:** Environment published with GitHub read access verified during setup and reusable startup guidance saved. No dependencies or services are required.
- New-task submission currently returns `Unable to determine project root for task` in both the user's browser and the cloud browser. The cause is unconfirmed.
- Continue maintenance through the GitHub connector while troubleshooting. Retry from the main computer and verify a task can access the repository before treating Cloud as operational.

## Current Focus
- Improve reliability, routing, and token efficiency without adding unnecessary complexity.
- Keep project files compact and current.
- Use this project as the home for future brain/workflow audits and maintenance changes.

## Next Actions
- Verify the published Codex Cloud environment can launch a repository task.
- Set up Obsidian on the main computer.
- Review usage after the weekly automation has run a few times.
- Split project files only when growth makes targeted retrieval worthwhile.
