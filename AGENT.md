<!-- uv:START -->
 Use `uv` as the primary Python command; fallback to `python` or `python3` if `uv` is unavailable.
 Run Python code with `uv run` instead of `uv python`.
 Install packages using `uv add` instead of `uv pip install` or `pip install`.
<!-- uv:END -->

<!-- Chrome-DevTools-mcp:START -->
 Utilize default web search tools and Chrome DevTools for researching external references.
<!-- Chrome-DevTools-mcp:END -->

<!-- interactive-feeback-mcp:START -->
 Verify all file paths before creating or editing files to ensure accuracy.
 Use the `interactive_feedback` MCP command to request clarification from the user when instructions are unclear or incomplete.
 Pose specific followup questions via `interactive_feedback` to resolve unclear requirements, avoiding assumptions.
 Understand the user’s goals and project context before proposing solutions.
 Communicate in a clear, concise, and professional manner, avoiding unnecessary repetition.
 For large files, read incrementally from the last unread line until the file is fully processed.
 Restrict edits to the relevant context, adhering to applicable specification documents.
 Before finalizing a task, use `interactive_feedback` to solicit user feedback. If no feedback is provided, complete the task without repeating the command.
 For recommendations or task summaries, invoke `interactive_feedback`. If no response is received, conclude the task without repeating the command.
 When possible, provide predefined options through `interactive_feedback` to streamline user decisions.
<!-- interactive-feeback-mcp:END -->

<!-- OPENSPEC extra:START -->
 Drive development using OpenSpec documentation stored in the `openspec` folder.
 Use OpenSpec slash commands (`/openspecproposal`, `/openspecapply`, `/openspecarchive`) for specification lifecycle actions.
 Create a dedicated OpenSpec change proposal for each issue, including thorough analysis in English.
 After issuing `openspec list`, wait 20 seconds before proceeding.
 Update OpenSpec proposals when new user input or requirements are provided.
 Open `@/openspec/AGENTS.md` when the request involves:
   Planning, proposals, or terms like "spec," "change," or "plan."
   New capabilities, breaking changes, architecture shifts, or significant performance/security work.
   Unclear requirements needing authoritative specification before coding.
 Use `@/openspec/AGENTS.md` to understand:
   Creating and applying change proposals.
   Specification format and conventions.
   Project structure and guidelines.
<!-- OPENSPEC extra:END -->

<!-- git:START -->
 Do not execute `git commit` or `git push`.
<!-- git:END -->
