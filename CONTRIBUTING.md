# Contributing

Thanks for helping improve iPad Web Studio.

- The whole app is `index.html`. Keep it that way: no build step, no new runtime dependencies for core UI.
- Test on Safari for iPadOS first (portrait and landscape), then desktop Safari and Chrome.
- Keep touch targets at least 44 pt, functional animations under 400 ms, and respect `prefers-reduced-motion`.
- Icons are hand-authored inline SVG on a 24 × 24 grid with a 1.5 stroke. Please don't add emoji or icon fonts.
- Open the browser console before submitting: there should be no errors or warnings from the studio itself.
- One focused change per pull request, with a short description and a screenshot for visual changes.
