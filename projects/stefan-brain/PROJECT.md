# Stefan Brain

> Personal knowledge-base and AI workflow project.

## Status
**Status:** Active  
**Last updated:** 2026-09-28

## Goal
Provide reliable cross-device context while minimizing repeated context reconstruction, tool calls, and token usage.

## Architecture
- GitHub repository: `stebbidadi/stefan-brain`
- ChatGPT: reasoning and conversation layer
- GitHub connector: cross-device knowledge access
- Obsidian: planned local editing interface
- Weekly automation: maintain durable project context

## Core Files
- `AI_MASTER_RULES.md` — operating and context-efficiency rules
- `PROJECTS.md` — routing index, used only when project routing is unclear
- `USER_PROFILE.md` — stable general context, loaded only when needed
- `INBOX.md` — unsorted durable information
- `projects/<name>/PROJECT.md` — project-specific source of truth

## Context Strategy
- Skip Stefan Brain entirely for generic questions.
- When a project is obvious, read `AI_MASTER_RULES.md` then that project directly.
- Skip `PROJECTS.md` when routing is already obvious.
- Load one project by default.
- Do not re-read unchanged files in the same conversation.
- Keep project files compact.
- Only add a short current-state snapshot if a `PROJECT.md` grows beyond roughly 4 KB; move deep history into supporting notes.

## Work Strategy
- Prefer normal ChatGPT + connectors when that can reliably complete the task.
- Use Work for genuinely multi-step agentic tasks.
- In Work, recommend the least resource-intensive suitable model and thinking level before acting.

## Next Actions
- Set up Obsidian on the main computer.
- Review usage after the weekly automation has run a few times.
- Split project files only when growth makes targeted retrieval worthwhile.

## Notes for ChatGPT
Optimize for the smallest reliable context set, not maximum context loading.
