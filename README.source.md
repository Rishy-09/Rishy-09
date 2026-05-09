# README.source.md

This profile is built as a local-SVG profile system instead of a plain Markdown file.

Design direction: **dark systems lab / mad engineer control room** — animated, technical, and product-focused, without fake lab props or random badge noise.

## Asset model

- `.github/assets/hero-lab.svg` — animated hero
- `.github/assets/system-flow.svg` — animated build map
- `.github/assets/project-cards/*.svg` — clickable flagship project cards
- `.github/assets/proof-matrix.svg` — colored project-proof matrix
- `.github/assets/tech-orbit.svg` — animated tech-stack orbit
- `.github/assets/signals-v2.svg` — proof/achievement strip
- `.github/assets/operating-loop.svg` — animated engineering loop

## Important

GitHub README files cannot run React or JavaScript directly. This uses static SVGs with internal SVG/CSS animation. That gives motion without requiring JS.
