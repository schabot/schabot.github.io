# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Overview

This is a Jekyll-based GitHub Pages site using the `minima` theme and the `github-pages` gem.

## Commands

```bash
# Install dependencies
bundle install

# Serve locally with live reload
bundle exec jekyll serve

# Build static site (output to _site/)
bundle exec jekyll build
```

The local server runs at `http://localhost:4000` by default. Changes to `_config.yml` require a server restart.

## Structure

- `_config.yml` — site-wide settings (title, URL, theme, plugins)
- `_posts/` — blog posts, named `YYYY-MM-DD-title.markdown` with front matter
- `index.markdown` — home page (uses `layout: home`)
- `about.markdown` — about page
- `_site/` — generated output, not committed (git-ignored)
- `Gemfile` — uses `github-pages` gem to match GitHub Pages build environment

## Content Conventions

- Posts go in `_posts/` with filename format `YYYY-MM-DD-slug.markdown`
- Front matter fields: `layout`, `title`, `date`, `categories`
- New pages can be added as `.markdown` or `.html` files at the root with appropriate front matter
