# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Quarto-based static site for a professional knowledge base published at [lopes.id](https://lopes.id). Content covers information security, detection engineering, and automation.

## Build Commands

| Command | Purpose |
| ------- | ------- |
| `quarto render --output-dir _site` | Build the full static site |
| `quarto preview` | Local dev server with live reload |
| `./scripts/setup.sh` | Install git pre-commit hooks |

There are no tests or linters beyond the pre-commit hook validation.

## Architecture

- **Static site generator**: Quarto with Python 3.14 (Jupyter kernel)
- **Content**: Quarto Markdown (`.qmd`) files in `log/<post-slug>/index.qmd`
- **Styling**: Custom "Vigil" theme in `static/styles/` (SCSS), dual dark/light mode
- **CI/CD**: GitHub Actions (`deploy.yml` for Cloudflare Pages, `integration.yml` for PR validation)
- **Validation**: `scripts/pre-commit.sh` enforces content rules at commit time

## Content Structure

Each post lives in its own directory under `log/`:

```text
log/post-slug/
  index.qmd      # Post content with YAML frontmatter
  og-*.webp      # Open Graph image
```

Required frontmatter fields: `title`, `description`, `image`. Image must be `.webp`.

## Validation Rules (pre-commit hook)

- Post filename: max 50 chars
- Title: max 60 chars
- Description: max 160 chars
- Images: WebP/JPG/PNG/GIF/SVG/ICO, max 300 KB, filename max 70 chars

## Branch Naming

`<namespace>/<short-description>` where namespace is one of: `post`, `revise`, `typo`, `bugfix`, `design`, `infra`, `docs`, `release`.

## Key Config Files

- `_quarto.yml` — Site-wide Quarto configuration (navigation, themes, listing)
- `log/_metadata.yml` — Default metadata for all posts (author, license, freeze)
- `scripts/pre-commit.sh` — Single source of truth for validation logic
