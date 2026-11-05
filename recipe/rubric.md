# Rubric

The reviewer returns two lists. Hard failures are fixed until they pass. Taste notes are taken for four revision rounds after every hard check passes.

## Hard checks

Each item is pass or fail.

- `dev` and `build` succeed locally.
- Nothing on the page requires a database, auth, or a secret to view.
- The name Jacob Beallor is visible.
- Jacob and Tuesday both appear, and both are recognizable from `recipe/references/`. The photo, a crop, a cutout, an illustration, or another treatment of that likeness all pass. A placeholder for a later real version of the same treatment passes when it is listed under `For Jacob to replace` with the treatment named. A different person or a different dog fails.
- LinkedIn, GitHub, and the resume link work and point at the destinations in `recipe/content.md`.
- Spotify Wrapped 2.0, Color³, 4Things, and the Arbitrage Betting Finder all appear. Claims match `recipe/content.md`. Live projects use their real URLs. The arbitrage finder has no URL.
- Facts in `recipe/content.md` stay true and are not contradicted. Employers, job titles, cities, years of experience, education, testimonials, metrics, and other biographical copy may appear. Each passage that is not already in `recipe/content.md` is listed under `For Jacob to replace`.
- Desktop and a phone-width layout are both usable.
- `prefers-reduced-motion` is honored.
- `recipe/` is intact.
- Every placeholder, text or image, is listed in `design/reviews/<slug>.md`.
- Accessibility checks for contrast, keyboard focus, and semantics pass.
- Images belong to this brief. No stock photography. No other photos of Jacob or Tuesday beyond `recipe/references/`.

## Taste

Score these after the hard checks pass. Four revision rounds, then stop.

- The brief is recognizable in type, color, texture, the one motion, and what stays quiet.
- The signature motion has a job. It is not decoration on every element.
- Placeholders belong to the same visual system as the rest of the page.
- The page has a point of view. It does not look like a default template, a component-library demo, or a generic awards-site portfolio.
- Hierarchy, spacing, and type hold up on both screen sizes.

## Stuck

If a revision leaves the same hard failure unchanged, stop. Write the failure, what was tried, and that the attempt is stuck. Do not spend the taste rounds on a broken site.
