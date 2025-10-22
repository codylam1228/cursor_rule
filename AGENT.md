These instructions are for AI assistants working in this project.

<!-- OPENSPEC:START -->
# OpenSpec Instructions
open `@/openspec/AGENTS.md` when the request:
- Mentions planning or proposals (words like proposal, spec, change, plan)
- Introduces new capabilities, breaking changes, architecture shifts, or big performance/security work
- Sounds ambiguous and you need the authoritative spec before coding

Use `@/openspec/AGENTS.md` to learn:
- How to create and apply change proposals
- Spec format and conventions
- Project structure and guidelines

Keep this managed block so 'openspec update' can refresh the instructions.

<!-- OPENSPEC:END -->

<!-- uv:START -->
# uv Instructions
ALWAYS Utilize `uv` as the primary Python command; fallback to `python` or `python3` if `uv` is unavailable.
ALWAYS run Python code with `uv run` instead of `uv python`.
ALWAYS install packages using `uv add` instead of `uv pip install` or `pip install`.
<!-- uv:END -->

<!-- Chrome-DevTools-mcp:START -->
# Chrome DevTools Instructions
ALWAYS utilize default web search tools and Chrome DevTools for researching external references.
<!-- Chrome-DevTools-mcp:END -->

<!-- interactive-feeback-mcp:START -->
# Interactive feedback mcp Instructions
ALWAYS verify all file paths before creating or editing files to ensure accuracy.
ALWAYS use the `interactive_feedback` MCP command to request clarification from the user when instructions are unclear or incomplete.
ALWAYS pose specific followup questions via `interactive_feedback` to resolve unclear requirements, avoiding assumptions.
Understand the user’s goals and project context before proposing solutions.
Communicate in a clear, concise, and professional manner, avoiding unnecessary repetition.
For large files, read incrementally from the last unread line until the file is fully processed.
ALWAYS restrict edits to the relevant context, adhering to applicable specification documents.
Before finalizing a task, ALWAYS use `interactive_feedback` to solicit user feedback. If no feedback is provided, complete the task without repeating the command.
For recommendations or task summaries, invoke `interactive_feedback`. If no response is received, conclude the task without repeating the command.
When possible, provide predefined options through `interactive_feedback` to streamline user decisions.
<!-- interactive-feeback-mcp:END -->

<!-- OPENSPEC extra:START -->
# OPENSPEC extra Instructions
Drive development using OpenSpec documentation stored in the `openspec` folder.
Use OpenSpec slash commands (`/openspecproposal`, `/openspecapply`, `/openspecarchive`) for specification lifecycle actions.
Create a dedicated OpenSpec change proposal for each issue, including thorough analysis in English.
After issuing `openspec list`, wait 20 seconds before proceeding.
Update OpenSpec proposals when new user input or requirements are provided.
<!-- OPENSPEC extra:END -->

<!-- git:START -->
# git Instructions
NEVER execute `git commit` or `git push`.
<!-- git:END -->
