# Claude Code Instructions

## Git Commit Guidelines
- DO NOT add Claude signature or Co-Authored-By lines to commits
- Keep commit messages focused and professional
- Follow conventional commit format when appropriate

## Project Reference
- Original prompt file: `12-personal-site-portfolio.md` (git-ignored, local reference only)
- Use this file to verify all requirements are met when working on this project

## Development Notes
- Static site with no build process (except basecamp PWA)
- Dark theme with gradient accents
- Mobile-first responsive design
- SEO optimized with proper meta tags
- PWA properly configured for /apps/basecamp/ path

## Basecamp PWA Updates
When updating the Basecamp PWA:
1. Clone: `git clone https://github.com/jaredamen/basecamp.git`
2. Build: `cd basecamp && npm install && npm run build`  
3. Copy: `cp -r dist/* /path/to/jaredamen.github.io/apps/basecamp/`
4. Update paths in copied files to work from `/apps/basecamp/` (already configured)

## Deployment
- GitHub Pages serves automatically from main branch
- Site available at: jaredamen.github.io
- No Jekyll processing (`.nojekyll` file present)