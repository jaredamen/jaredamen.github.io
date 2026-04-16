# Claude Code Instructions

## Git Commit Guidelines
- DO NOT add Claude signature or Co-Authored-By lines to commits
- Keep commit messages focused and professional
- Follow conventional commit format when appropriate

## Project Reference
- Original prompt file: `12-personal-site-portfolio.md` (git-ignored, local reference only)
- Use this file to verify all requirements are met when working on this project

## Development Notes
- Static site with no build process
- Dark theme with gradient accents
- Mobile-first responsive design
- SEO optimized with proper meta tags

## Apps Page

The `/apps/` page lists projects. Each card should link out to where the app actually runs.

**Basecamp** is hosted on Vercel at `https://basecamp-pink.vercel.app` — it needs a backend (auth, Stripe, AI proxy) that GitHub Pages can't run. The `apps/index.html` Basecamp card links directly to the Vercel URL.

`apps/basecamp/index.html` is a minimal redirect page in case anyone has the old `/apps/basecamp/` URL bookmarked. It forwards to the Vercel deployment.

**Do not** restore a static build to `/apps/basecamp/` — the backend features (auth, payments, AI generation) won't work without Vercel's serverless functions.

## Deployment
- GitHub Pages serves automatically from main branch
- Site available at: jaredamen.github.io
- No Jekyll processing (`.nojekyll` file present)
