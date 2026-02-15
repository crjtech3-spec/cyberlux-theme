# Theme Store submission checklist

This checklist helps you prepare Cyber Lux for Shopify Theme Store submission.

## Required (must pass)
- Zero `theme-check` **errors** (suggestions are OK). Run: `shopify theme check`
- 25+ homepage-eligible sections (Cyber Lux provides 59)
- Required templates present (`theme.liquid`, `404.json`, `product`, `collection`, `index`, `cart`, `password`, `gift_card`, etc.)
- No external developer/support URLs in theme content (use the `theme_info` fields only)
- Demo stores for each preset with real content and correct industry tagging
- No visible developer credits in storefront content

## Recommended (fix before submission)
- Fix all `LiquidTag` suggestions (use `{% liquid %}` where possible)
- Resolve color contrast failures highlighted by Lighthouse
- Optimize mobile homepage (lowest Lighthouse mobile run may need improvement)

## How to run Lighthouse locally (developer)
- Use the provided `lighthouse_audit.py` script: `python lighthouse_audit.py`
- Verify average Performance ≥ 60 and Accessibility ≥ 90 across home/product/collection (desktop & mobile)

## Final steps before submit
1. Publish a demo store for each preset.
2. Populate `listings/` content and double-check `settings_data.json` for placeholders.
3. Update your Theme Store listing metadata and screenshots.
4. Submit to Theme Store and monitor the review feedback.