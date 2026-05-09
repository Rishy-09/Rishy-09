# Setup

Copy these files into your profile repository: `Rishy-09/Rishy-09`.

```bash
git add .
git commit -m "polish profile layout and generated activity cards"
git push origin main
```

Then open GitHub Actions and run:

`Generate profile summary cards` → `Run workflow`

## Stats behavior

The custom SVG sections such as hero, system-flow, proof-matrix, tech-orbit, project cards, signals, and operating-loop are static design assets. Their text is manually written.

The Activity Console uses `github-profile-summary-cards`. Those cards are real GitHub-derived stats, but the generated SVG files are static snapshots. They refresh when the scheduled workflow runs or when you manually run the workflow.

## Important

If `AI-Voice-Calling-Assistant` stays private or the org blocks access, visitors will see a 404 from that card link.
