# Superare Racing — superare.cc

Portland-based bike racing team. Cat 2 & 3, road and gravel, 11 riders.
Instagram: @superare.cc | Email: SuperareRacing@gmail.com

See `.claude/docs/` for detailed notes.

## Stack
- Hugo static site (no theme, custom layouts)
- Deployed to GitHub Pages via GitHub Actions on push to `main`
- Custom domain: superare.cc (CNAME in static/)
- No npm/node — Hugo only

## Key commands
- `hugo server` — local preview
- `hugo --minify` — production build to public/
- Branch `site-redesign` has current work (not yet merged to main)

## Conventions
- All CSS in `static/css/style.css`
- Shared nav/footer in `layouts/partials/`
- Sponsor logos in `static/images/sponsors/`
- Content pages use frontmatter `layout:` to select layout from `layouts/_default/`
- Colors: green `#325C26`, dark green `#1D3A14`, blue `#4DC4F0`, cream `#DDD5B8`
