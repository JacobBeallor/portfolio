# Constraints

- The site must be deployable on Vercel with no database, no auth, and no secrets required to view the page. The attempt does not have to actually deploy. `dev` and `build` must succeed locally.
- Framework, language, and styling are the implementer's choice.
- Desktop and a phone-width layout both work.
- Honor `prefers-reduced-motion`.
- `recipe/` stays put. Do not delete or rewrite it to fit the design.
- Extra skills install at project scope, inside this worktree, and are recorded in `design/reviews/<slug>.md`. Do not install a skill whose job is to choose a different art direction than the brief.
- Do not install skills at user scope.

## Hard checks loop

Hard checks in `recipe/rubric.md` loop until they pass. If the same hard failure comes back unchanged after a revision, stop and write that the attempt is stuck.

## Taste

After the hard checks pass, run four taste revisions from the brief, the critique, and the motion review. Then stop and write the score.
