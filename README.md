# Growth Audit — The Body Coach

**Live:** https://plykhvar-glitch.github.io/thebodycoach-flow-rebuild/

Five ranked ideas plus a clickable prototype of The Body Coach's iOS onboarding and paywall, rebuilt in The Body Coach's own design. Only the order of the screens changed, not the art direction. Prepared by Adapty, November 2026.

## The five ideas

| # | Idea | Screen | Potential outcome |
| :-- | :-- | :-- | :-- |
| 01 | Let people in before you ask for an email | Welcome → Account | CR +8% · ARPU +17% |
| 02 | Build the plan before the paywall | Loader → Plan ready | CR +10–15% |
| 03 | Name their plan on the paywall | Paywall | CR +15–20% |
| 04 | Offer one month when they close | Offer on close | ARPU +10–15% |
| 05 | Ask about tracking once they subscribe | Data & tracking | CR +10–15% |

## Grounding

Every price, rating, quote, photo and feature line comes from The Body Coach's own published material: the App Store listing (Editors' Choice, the auto-renewing monthly and annual plans), thebodycoach.com (4.8 stars from 44,000 reviews, 2.7 million downloads, Nathan's quote and transformation), and the in-app screens (Annual $119.99 with a 7-day free trial, Monthly $19.99, the Lisa and Nathan testimonials, every question and option).

Impact ranges are Adapty's expected effect from teardowns and A/B tests across subscription apps — not measured lift for The Body Coach.

## Run locally

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000. Add `?open=proto` to land on the prototype.
