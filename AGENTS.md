# Agent instructions

Write concise, plain-language responses. Lead with the answer or outcome, then give the details needed to understand it or take action.

Use short sentences and familiar words. Explain technical terms when needed. Avoid repetition, filler, and unnecessary formatting. Use lists only when they make the information easier to scan.

## Project structure

<!-- fill in as the project grows -->

## Rules

- Read README.md and docs/DESIGN.md before making changes.
- Document setup, development, and verification commands once the stack is selected.
- Verify changed behavior with appropriate checks; report what passed and what could not run.
- Preserve unrelated work and keep credentials out of tracked files.
- Update affected documentation before declaring the work done.
- Read PROGRESS.md before starting. Update current work, blockers, and next steps at handoff.
- Ask if uncertain

## Style and preferences

- Optimize the repository for legibility
- Keep changes bounded and reviewable
- For changes to architecture, public interfaces, data models, or major dependencies, share a plan and wait for feedback before implementation. Proceed independently with routine changes within the agreed scope.
- Record consequential design choices with alternatives or tradeoffs in "./docs/decisions" and link to them in ./docs/DESIGN.md.
- Treat agreed requirements as intended behavior. When design, tests, and implementation conflict, identify the mismatch before changing them.
