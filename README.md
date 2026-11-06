# Portfolio — Ahmed Dorra

A modern, creative personal-site rebuild. Pure HTML/CSS/JS (no build step), deployable directly to GitHub Pages.

## What it is

A single-page portfolio with a "Neural Engineer" theme:
- Terminal-inspired hero with rotating-title typing animation
- Animated neural-network canvas background (respects `prefers-reduced-motion`)
- Bento grid for the flagship projects (Shopping Assistant, Arabic Banking Intent, Research Assistant, VISIONEER), with mouse-tracked glow
- Visualized skills (categorized cards with animated bars)
- Vertical timeline for experience and education
- Highlighted research/publication section
- Glassmorphism contact cards

## Live demo

After deployment: **https://ahmedmostafa167.github.io/**

## Local preview

```bash
python -m http.server 8000
# Visit http://localhost:8000
```

Any static server works — there's no build step.

## Deploying

This repository is the site. Pushing to `master` publishes it through GitHub Pages at
https://ahmedmostafa167.github.io/ (no build step, no workflow).
