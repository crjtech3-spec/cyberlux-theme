# Getting started

## Requirements
- Shopify CLI (latest)
- Node + npm (for Lighthouse if you run audits locally)
- A Shopify partner account or store for previewing the theme

## Install & preview
1. From theme folder: `shopify theme serve` (local preview)
2. To check Theme Health: `shopify theme check`
3. To push a theme to a partner/dev store: `shopify theme push --theme <theme_id>`

## Recommended workflow
- Use `shopify theme serve` during development.
- Run `shopify theme check` and `python lighthouse_audit.py` (this repo includes `lighthouse_audit.py`) before submission.

## Presets & demo content
- Prebuilt presets are available under `listings/` for each demo preset (Cyberluxe, Luxe, Minimal, Noir, Sunset).
- Use the Theme Editor to load a preset and verify content.