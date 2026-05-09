# README.source.md

This profile is built as a local-SVG profile system instead of a plain Markdown file.

The design direction is **mad-systems lab**: dark, animated, technical, and product-focused — not random badges or generic cyberpunk decoration.

## Asset model

- `.github/assets/hero-lab.svg` — animated hero
- `.github/assets/system-flow.svg` — animated build map
- `.github/assets/project-cards/*.svg` — clickable flagship project cards
- `.github/assets/tech-orbit.svg` — animated tech-stack orbit
- `.github/assets/signals-v2.svg` — proof/achievement strip

## Important

GitHub README files cannot run React or JavaScript directly. This uses static SVGs with internal SVG/CSS animation. That gives motion without requiring JS.

If you later want readme-aura, this can be converted into `aura` blocks, but this version is safer because it needs no rendering pipeline to work.
