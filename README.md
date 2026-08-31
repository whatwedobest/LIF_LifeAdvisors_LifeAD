# Life Advisors — Homepage Wireframe (Client Review)

Client-review presentation of the proposed Life Advisors **homepage layout** and **site navigation structure**. This is a site plan for review, not the production website.

Interior pages are named and mapped but **not wireframed** at this stage. Homepage approval comes first; interior page designs follow.

## Live preview

https://whatwedobest.github.io/LIF_LifeAdvisors_LifeAD/

## What’s included

### Homepage wireframe (9 sections + nav + footer)

1. Hero — brand positioning and primary CTA
2. Problem recognition — three pain points
3. MCA Lifeline™ introduction — solution teaser with link to interior page
4. How It Works preview — four-step process with link to interior page
5. Why Life Advisors preview — two differentiation highlights with link to interior page
6. Social proof — testimonials and verified stats
7. Timothy Shaw authority teaser — link to full bio page
8. Resources preview — two featured articles with link to hub
9. Final consultation CTA

### Proposed primary navigation

| Nav item | Purpose |
|---|---|
| **Home** | Homepage (wireframed) |
| **MCA Solutions** | Solutions hub → The MCA Lifeline™, Multiple MCAs, How It Works |
| **Why Life Advisors** | Differentiation → full approach, Life After Debt |
| **Resources** | Education hub → articles, videos, FAQs |
| **About** | Company hub → About Life Advisors, Timothy Shaw, Contact |
| **Talk With a Life Advisor** | Persistent CTA button (consultation) |

### Also documented (not wireframed)

- Interior page names and content mapping
- Meta campaign landing page outlines (separate from main nav)
- Wireframe legend

## Local preview

Open `index.html` in a browser, or from this folder:

```bash
python3 -m http.server 8080
```

Then visit http://localhost:8080

## Responsive behavior

The wireframe is optimized for all common screen sizes:

| Breakpoint | Layout behavior |
|---|---|
| **1600px+** | Max content width capped for comfortable reading on ultra-wide displays |
| **901–1200px** | Two-column grids where appropriate; footer and sitemap reflow |
| **≤900px** | Slide-out navigation menu; single-column sections; stacked stats |
| **≤768px** | Full-width CTAs; centered mobile typography |
| **≤480px** | Compact spacing; single-column footer and process steps |

Mobile navigation uses a hamburger menu with overlay, escape-to-close, and 48px minimum touch targets.
