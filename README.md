# Shefa Website

Public marketing site for Shefa Group — parent entity, Shefa Investment Group, and Shefa Advisory Group.

## Commands

| Command         | Action                                      |
| :-------------- | :------------------------------------------ |
| `npm install`   | Install dependencies                        |
| `npm run dev`   | Start dev server at `localhost:4321`        |
| `npm run build` | Build production site to `./dist/`          |
| `npm run preview` | Preview production build locally          |

## Deploy

GitHub Pages via `.github/workflows/deploy.yml`. Push to `main` to trigger.

Before deploying:
1. Update `site` in `astro.config.mjs` with your GitHub username or custom domain
2. Add Web3Forms `access_key` in `src/components/IntakeForm.astro`
3. Drop team photos into `public/images/team/`
