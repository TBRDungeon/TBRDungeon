# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

TBR Games — a Jekyll static site at `tbr.games` serving as the landing page for two Phaser 3 board games: **The TBR Dungeon** and **The Dark TBR**.

## Build & Deploy

- **Framework:** Jekyll (static site generator)
- **Deployment:** GitHub Pages via GitHub Actions (auto-deploys on push to `main`)
- **Custom domain:** `tbr.games` (configured via `CNAME` file)
- **Build output:** `./_site`
- **Local preview:**
  ```
  bundle install
  bundle exec jekyll serve
  ```

## Architecture

```
_config.yml          # Jekyll config (title, url, plugins)
Gemfile              # github-pages gem
CNAME                # Custom domain for GitHub Pages
index.md             # Landing page with game cards grid
games/
  tbr-dungeon.md     # Game detail page (layout: game)
  the-dark-tbr.md    # Game detail page (layout: game)
_layouts/
  default.html       # Base HTML shell
  game.html          # Game detail page (extends default)
_includes/
  head.html          # Meta tags, SEO, stylesheet
  header.html        # Site title/nav
  footer.html        # Copyright
assets/
  css/style.scss     # Single stylesheet (compiled by Jekyll)
  images/            # Game thumbnails
```

## Key Patterns

- **No theme gem** — fully custom layouts in `_layouts/`
- **No JavaScript** — pure HTML/CSS site
- **Per-game theming** — game pages pass `accent_color` and `bg_color` via front matter, applied as CSS custom properties
- **Single SCSS file** — Jekyll compiles `assets/css/style.scss` (requires empty front matter `---` block)
- **Dark TBR placeholder** — the card thumbnail is a CSS-only placeholder; swap in a real image when available
