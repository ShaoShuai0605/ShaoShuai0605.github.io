# Mintlify-Inspired Academic Homepage

This repository uses a Mintlify-inspired design language adapted for an academic personal site.

## Visual direction

- Clean, reading-first, and structured.
- Bright white backgrounds with very light neutral section bands.
- A single vivid green accent reserved for links, tags, and focused actions.
- Sharp, compact interface shapes with a maximum radius of 8px.
- Editorial pacing: generous whitespace, clear hierarchy, and fast scanning for publications.

## Color tokens

- `--ink`: `#0d0d0d` for primary text and headings
- `--paper`: `#ffffff` for page background
- `--mist`: `#fafafa` for light section backgrounds
- `--line`: `rgba(13, 13, 13, 0.10)` for borders
- `--line-strong`: `rgba(13, 13, 13, 0.18)` for stronger dividers
- `--muted`: `#666666` for secondary text
- `--soft`: `#888888` for tertiary text
- `--accent`: `#18e299` for key actions and highlights
- `--accent-deep`: `#0fa76e` for active states
- `--accent-wash`: `#d4fae8` for subtle highlight backgrounds
- `--info`: `#3772cf` for metadata links
- `--warn`: `#c37d0d` for timeline and status accents

## Typography

- Sans: `Inter`, `system-ui`, `-apple-system`, `BlinkMacSystemFont`, `Segoe UI`, `sans-serif`
- Mono: `IBM Plex Mono`, `ui-monospace`, `SFMono-Regular`, `Menlo`, `monospace`

Hierarchy:

- Hero title: 56px / 600 / 1.05 on desktop, 40px on mobile
- Section title: 34px / 600 / 1.12
- Card title: 20px / 600 / 1.25
- Body: 16px / 400 / 1.65
- Small labels: 12-13px mono uppercase

## Layout

- Full-width bands with constrained inner content (`max-width: 1180px`).
- Hero uses a real photographic background with text directly on top, never inside a card.
- Publication and project sections use stable grid/list layouts.
- The first content band should remain partially visible below the hero on common laptop and mobile viewports.

## Components

- Header: translucent white, thin border, compact mono navigation accents.
- Buttons: solid dark primary, white secondary, both 8px radius.
- Tags: 8px radius with accent-wash background.
- Cards: white or mist background, 8px radius, low-contrast border, soft shadow only when needed.
- Publication rows: year rail + content column + compact link cluster.

## Guardrails

- Do not let the accent green dominate large surfaces.
- Avoid gradient-only sections; imagery should come from real photos.
- Keep copy direct and user-facing.
- Prioritize legibility for long paper titles and dense metadata.
