# Performance & Lighthouse

## Summary (current local audit)
- Average Performance (themes): 78–82 (all presets pass Theme Store threshold)
- Average Accessibility: 93–96 (passes)
- Known low area: mobile homepage (one run per preset can be 56–66)

## How to run
- `python lighthouse_audit.py` — runs Lighthouse against the store preview (`?preview_theme_id=`) and writes reports to `reports/`.
- Use `reports/lighthouse-*.report.json` to inspect audits and `reports/localhost_audit/localhost_audit_summary.md` for rollups.

## Tips to improve performance
- Lazy-load offscreen images and video placeholders
- Defer non-critical JavaScript
- Avoid large render-blocking CSS; use critical CSS
- Compress and optimize hero/product imagery

## Theme Store benchmark
Shopify uses an internal benchmark dataset for final review. Local Lighthouse is the best proxy pre-submission but Shopify may run their own tests during review.