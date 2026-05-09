# Product Requirements — Shefa Website v1

## Purpose

Public marketing site for Shefa Group. Establishes Shefa as a premium, purpose-driven operating company. Gives each entity a clear intake path. Serves as credibility anchor for 1:1 outreach.

## Information architecture

| Route | Page | Layout |
|-------|------|--------|
| `/` | Home | BaseLayout |
| `/about` | About Shefa | BaseLayout |
| `/team` | Team (Nathan + Robin) | BaseLayout |
| `/investment` | Investment landing | EntityLayout |
| `/investment/approach` | Investment approach | EntityLayout |
| `/investment/partner-with-us` | Partner intake form | EntityLayout |
| `/advisory` | Advisory landing | EntityLayout |
| `/advisory/approach` | Advisory approach | EntityLayout |
| `/advisory/discovery-call` | Discovery call CTA | EntityLayout |
| `/contact` | Intent-tabbed contact form | BaseLayout |
| `/marketing` | Coming soon | BaseLayout |
| `/privacy` | Privacy policy | BaseLayout |

## What is NOT in v1

- Camp, equine therapy, or any mission-project-specific pages
- Ecosystem page, partner directory, operator directory
- Blog, CMS, newsletter, podcast embed
- Community tiers, accounts, auth, gated content
- E-commerce, payments, booking widgets (Cal.com deferred)
- Live Marketing entity content
- Analytics (Plausible deferred)

## Forms

Web3Forms static endpoint. Hidden `access_key` field in `IntakeForm.astro`.
Replace `YOUR_WEB3FORMS_ACCESS_KEY` with real key before go-live.

## Open items for go-live

1. Web3Forms `access_key` → replace placeholder in `src/components/IntakeForm.astro`
2. Custom domain → update `site` in `astro.config.mjs`, add CNAME record
3. Team photos → drop `nathan.jpg` and `robin.jpg` into `public/images/team/`
4. Robin's final "What is Shefa" copy → replace placeholder in `src/pages/about.astro`
5. Advisory discovery call booking URL → upgrade from email CTA to Cal.com embed

## Deploy

GitHub Pages via `.github/workflows/deploy.yml`. Push to `main` triggers auto-deploy.
Requires GitHub Pages enabled in repo settings with "GitHub Actions" as source.
