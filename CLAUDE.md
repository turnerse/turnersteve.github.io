# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Overview

This is a static personal website for Steve Turner, hosted on GitHub Pages at `turnersteve.com`. It is a single-page site with no build step, framework, or package manager — just plain HTML and CSS.

## Structure

- `index.html` — the entire page content
- `styles.css` — all styles, using CSS custom properties defined in `:root`
- `CNAME` — GitHub Pages custom domain (`turnersteve.com`)

## Design

The page uses a glassmorphism card layout centered on a dark (`#0f172a`) background with three animated gradient blobs. All color values are CSS variables in `:root` within `styles.css`. The font is `Outfit` from Google Fonts.

## Deployment

Pushing to `main` deploys automatically via GitHub Pages. No CI or build pipeline.
