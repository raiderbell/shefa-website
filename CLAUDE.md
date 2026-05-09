# Shefa Website

> Astro static site. GitHub Pages deploy. Nathan + Robin maintain with Claude Code.

## Purpose
Public marketing site for Shefa Group — parent, Investment, Advisory. Premium, purpose-driven.

## Deploy
GitHub Pages. Push to `main` → auto-deploy via `.github/workflows/deploy.yml`.
Before first deploy: update `site` in `astro.config.mjs` and add Web3Forms `access_key`.

## Design Tokens
`src/styles/tokens.css` — all values sourced from brand kit.
Navy holds structure. Gold signals importance. Never swap them. Never hardcode hex.

## Voice & Brand
- Voice rules: `C:\Users\natha\OneDrive\Desktop\Shefa\about-me\Voice-Rules_Nathan_v1.md`
- Brand posture: `C:\Users\natha\OneDrive\Desktop\Shefa\Shefa-Brand-Posture_v1.md`
- Non-negotiables: `C:\Users\natha\OneDrive\Desktop\Shefa\Shefa-Non-Negotiables_v1.md`
- Design philosophy: `C:\Users\natha\OneDrive\Desktop\Shefa\brand-assets\Shefa-BioPDF-Design-Philosophy_v1.md`
- Mockups (approved): `C:\Users\natha\OneDrive\Desktop\Shefa\claude-outputs\Shefa-Website\mockups\`

## Content
Markdown in `src/content/` — edit copy without touching components.

## What NOT To Build (v1)
- No camp, equine therapy, or specific mission-project pages
- No ecosystem directory or partner application
- No blog, CMS, newsletter, podcast embed
- No community tiers, accounts, auth, gated content
- No e-commerce, payments, booking widgets
- No live Marketing entity content — "coming soon" route only
- No analytics yet

## Hard Rules
- Mission tone stays sincere. Premium without bragging. Name no projects we haven't shipped.
- Run external-facing copy through `/brand-guardian` skill before shipping.
- Gold appears once per composition. Navy is structure. Never use inflated language.
- No emojis. No "kindly." No "visionary," "innovative," "thought leader."
