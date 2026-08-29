# bama-alumni-grail

A hunt dossier for one specific sweatshirt: an early-90s **University of Alabama
Alumni** crewneck (outline ALABAMA + university seal + ALUMNI ribbon banner, ash
gray) on a made-in-USA **Jerzees Super Sweats** blank, size 42-44.

- `index.html` — the dossier: target spec (photos in `img/`), current verdict,
  ranked live near-misses, modern fallbacks, sold comps, and the standing watch.
- `data/seen.json` — machine-readable registry of every listing already
  evaluated, so recurring hunts don't re-surface known misses. Update it (and
  the page) each hunt.

The recurring hunt protocol lives in the `bama-grail-hunt` skill
(`~/Projects/skill-bama-grail-hunt`). Deploys to GitHub Pages via Actions once
the repo exists on GitHub (`drewhoover.com/bama-alumni-grail/`).
