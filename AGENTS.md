# AGENTS.md — Jayden Lee Portfolio

## About

Static personal portfolio website hosted on GitHub Pages. No build tools, tests, or linting.

## Structure

- `index.html` — Main site (edit directly)
- `projects/project-{1,2,3}/` — Project subdirectories
- `_config.yml` — Jekyll config (minimal, just title)

## Development

- No dev server — open `index.html` directly in browser
- No build step — pure static HTML/CSS
- No test/lint commands

## Deployment

Push to `main` branch — GitHub Pages auto-deploys. Domain: `jynlee7.github.io`

## Editing Notes

- CSS design tokens in `:root` block at top of `index.html` (lines 15-30)
- Font: Inter (Google Fonts)
- Favicon: `favicon.png` at root