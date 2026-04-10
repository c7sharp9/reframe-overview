# ReFrame Business Overview

Single-file static HTML page serving as the ReFrame company strategy and business overview document. Published via GitHub Pages.

## Links

- **Live:** https://c7sharp9.github.io/reframe-overview/
- **Repo:** github.com/c7sharp9/reframe-overview
- **iCloud source:** ~/Library/Mobile Documents/com~apple~CloudDocs/Projects/business/reframe/strategy/

## How It Works

This is a "quick-share page" pattern: one self-contained `index.html` with inline CSS, no build step, no dependencies. Push to `main` and GitHub Pages deploys automatically.

## Structure

```
index.html    The entire site (HTML + inline CSS)
```

## Editing

Edit `index.html` directly. The page uses CSS custom properties for theming (dark mode, GitHub-inspired palette). Layout is a sticky sidebar nav + scrollable main content area.

## Deployment

Push to `main` branch. GitHub Pages serves from the repo root automatically.

## Notes

- No JavaScript framework, no build tools, no npm.
- The same HTML file is also kept in iCloud for offline access and backup.
- Dark theme with accent colors defined as CSS custom properties in `:root`.
