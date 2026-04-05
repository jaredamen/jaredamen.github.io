# Jared (Yusef) Amen - Personal Portfolio

Personal portfolio and app hub for Jared (Yusef) Amen, SRE & Platform Engineering Consultant.

**Live at:** [jaredamen.github.io](https://jaredamen.github.io)

## Overview

This site serves multiple purposes:

1. **Portfolio** — Professional engineering identity and project showcase
2. **Consulting Landing Page** — Information for potential SRE/platform engineering consulting clients  
3. **App Hub** — Hosts web applications and tools at `/apps/`
4. **Project Showcase** — Links to open source projects and commercial products

## Structure

```
├── index.html              # Main portfolio page
├── style.css               # Site styles (dark theme)
├── apps/
│   ├── index.html          # Apps directory page
│   └── basecamp/           # Basecamp PWA (pre-built)
├── assets/
│   └── favicon.svg         # Site favicon
├── .nojekyll               # Disable Jekyll processing
└── README.md               # This file
```

## Basecamp PWA Updates

The Basecamp PWA is hosted at `/apps/basecamp/` and is built from a separate repository.

To update the Basecamp PWA:

1. Clone the basecamp repository: `git clone https://github.com/jaredamen/basecamp.git`
2. Build the PWA: `cd basecamp && npm install && npm run build`
3. Copy build output: `cp -r dist/* /path/to/jaredamen.github.io/apps/basecamp/`
4. Update paths in the copied files to work from `/apps/basecamp/` (already configured in current build)

## Development

This is a static site built with vanilla HTML/CSS/JS. No build process required for the main site.

- Responsive design for mobile compatibility
- Dark theme with gradient accents
- SEO optimized with proper meta tags
- Print-friendly styles included

## Git Workflow

This repository follows a branch + PR workflow. Never commit directly to main.

## Contact

- **Email:** jared.yusef@gmail.com
- **GitHub:** github.com/jaredamen
- **LinkedIn:** www.linkedin.com/in/jaredev

Built by hand with care. © 2026 Jared (Yusef) Amen