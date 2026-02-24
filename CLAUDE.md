# CLAUDE.md

This file provides guidance to Claude Code when working in this specific repo.

## What This Repo Is

This is the brand identity and guidelines repository for **Manzanita Research** — an independent AI lab building tools for musicians and producers. There is no build system, no tests, no application code.

## Repo Structure

- `README.md` — Full brand guide (voice, values, visual direction, cultural references)
- `chaparral.json` — Manifest for [chaparral](https://github.com/manzanita-research/chaparral), declaring shared skills and org config
- `org/CLAUDE.md` — Org-wide Claude Code instructions (symlinked to parent directory by chaparral)
- `org/skills/` — Shared Claude Code skills (symlinked into sibling repos by chaparral)
  - `frontend-design/` — Manzanita's frontend design system and aesthetic for React + Tailwind interfaces

## How Sharing Works

This repo is the source of truth for org-wide Claude Code configuration. Run `chaparral sync` from any Manzanita project to link the org CLAUDE.md and shared skills into all sibling repos. See the [chaparral README](https://github.com/manzanita-research/chaparral) for details.
