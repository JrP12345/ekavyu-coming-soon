# Ekavyu — Coming Soon Landing Page

Official standalone Coming Soon landing page for [ekavyu.com](https://ekavyu.com).

## Overview
- **Brand**: Ekavyu (Integrated Digital Healthcare)
- **Target URL**: https://ekavyu.com
- **Full Application URL**: https://dev.ekavyu.com (developed separately)
- **Tech Stack**: Pure Semantic HTML5, CSS3, Minimal Vanilla JS (Zero external runtime dependencies)

## Assets
- `index.html`: Complete standalone landing page with responsive styling and accessibility.
- `ekavyu-leaf.png`: Brand identity mark.
- `favicon-32.png` / `favicon-16.png`: Favicon icons.

## Local Preview
Open `index.html` directly in any browser:
```bash
# Or start a local static server
npx serve .
# Or using Python
python -m http.server 3000
```

## Deployment
This is a lightweight static site ready for instant zero-config deployment on:
- **Vercel**: Import repository -> Framework Preset: `Other` -> Deploy.
- **Netlify**: Import repository -> Publish directory: `.` -> Deploy.
- **Cloudflare Pages**: Connect repository -> Build output directory: `.` -> Deploy.
- **GitHub Pages**: Repository Settings -> Pages -> Source: `Deploy from a branch` (`main` / root).
