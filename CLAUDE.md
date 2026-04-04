# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Overview

This is a static HTML portfolio website for Philipp Bobek, deployed via GitHub Pages at `philipp-bobek.de`.
There is no build process, package manager, or framework — just plain HTML files served directly.

## Development

Open HTML files directly in a browser, or use any static file server:

```bash
python3 -m http.server 8080
```

No build, lint, or test commands exist.

## Architecture

**Stack:**
Pure HTML + Bootstrap 5.0.1 (CDN) + Bootstrap Icons 1.5.0 + Font Awesome 4.7.0 (CDN).
No JavaScript beyond Bootstrap's bundle for navbar toggle.

**Pages:**

- `index.html` — Main portfolio page (bio + project grid)
- `compass-privacy.html` — Privacy policy for the Compass Android app (linked from Google Play Store, unrelated to the
  portfolio)
- `metronome-privacy.html` — Privacy policy for the Metronome Android app (linked from Google Play Store, unrelated to
  the portfolio)

**Assets:**

- `img/` — Project screenshots and profile portrait
- `data/` — Bachelor's thesis PDF (excluded from search crawlers via `robots.txt`)
- Favicons and `site.webmanifest` at root

## Code Style

Follow `.editorconfig`: UTF-8, 2-space indentation, LF line endings, trailing newline, no trailing whitespace.
