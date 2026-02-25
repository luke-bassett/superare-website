# Progress & Session Notes

## Session 1 — 2026-02-24

### What was built
Starting from a Hugo "coming soon" placeholder, built a full site on branch `site-redesign`:

**Landing page (`/`)**
- Sticky nav: Superare Racing | About · Sponsors · Banana Belt
- Hero: big condensed type, forest green bg, Portland/Bike Racing tagline, blue CTA
- Race banner section (dark green): links to /race/
- Sponsors grid: 6 logo cards
- Footer: Instagram + email

**Race page (`/race/`)**
- Banana Belt Road Race — Sunday April 19, 2026
- Hosted by Superare Racing (took over from Valkyr Cycling)
- Course: Henry Hagg Lake, Scoggins Valley Road, Forest Grove OR (~40 min from Portland)
- 10.3-mile loop, ~750 ft elevation per lap
- Schedule table structure is in place — times/laps all TBD, needs filling in from official OBRA flier
- Practical info: registration (OBRA, TBD), getting there, requirements, contact

### Sponsors
| Name | URL | Logo file | Notes |
|------|-----|-----------|-------|
| Cyclepath PDX | cyclepathpdx.com | cyclepath.avif | Bike shop, Portland |
| Cafe Cinco Siete | cafecincosietepdx.com | cincosiete.gif | Coffee, Portland |
| Skratch Labs | skratchlabs.com | skratch.svg | White SVG — dark card bg |
| Primos Cycles | primoscycles.com | primos.avif | Bike maker (not shop) |
| Castelli | castelli-cycling.com | castelli.svg | Has white bg baked in |
| Ride HiFi | ridehifi.com | ridehifi.avif | Wheels (HiFi is just branding) |

### Still TODO
- Fill in race schedule (times, laps per field) once confirmed from OBRA
- Merge `site-redesign` → `main` to deploy
- Castelli SVG has a white bg rect baked in — could strip it for cleaner look
- No team photos yet — could add to hero or about section later
- May add Weekly Rides section eventually (nav slot reserved)
