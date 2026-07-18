# designMATTers — Portfolio of Matt McGlothlin

A static recreation of [designmatt-ers.com](https://designmatt-ers.com), the portfolio site of Matt McGlothlin.

## Structure

Plain HTML + a single shared stylesheet — no build step, no dependencies. URL slugs mirror the live site:

| Path | Page |
| --- | --- |
| `/` | Home — hero + selected work grid |
| `/about-1/` | About Me |
| `/digital-leadership-design-process/` | Digital Leadership |
| `/safety-suite-transformation/` | Safety Suite Transformation (Honeywell) |
| `/integrated-lifecare-platform/` | Integrated Lifecare Platform |
| `/topbid-design-system/` | TopBid Design System |
| `/top-bid-mobile-app/` | Top Bid Mobile App |
| `/reputation-management-mobile-app-reprevivecom/` | Reputation Management Mobile App (RepRevive) |
| `/eda-responsive-redesign/` | EDA Responsive Redesign |
| `/ecomdash-onboarding-design-system/` | Ecomdash — Onboarding & Design System |

## Running locally

Any static server works:

```sh
python3 -m http.server 8080
```

Then open http://localhost:8080.

## Deploying

The site is GitHub Pages–ready: enable Pages on this repository and serve from the root of the branch.

## Notes

Project thumbnails and case-study heroes currently use styled gradient placeholders — drop real imagery into the tiles/heroes to replace them.
