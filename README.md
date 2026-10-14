# Syed Jowher Zathiq — Portfolio

Static site: one `index.html` plus `assets/`. No build step.

## Run locally
    npx serve .        # or: python3 -m http.server 8080

## Deploy
- Vercel: `npx vercel` from this folder (framework preset: Other), or drag the folder into vercel.com/new.
- Netlify / GitHub Pages / any static host: upload the folder as-is.

## Dependencies (loaded from CDN)
- three.js r128 (cdnjs) for the particle scene
- Google Fonts: Syne, Albert Sans, IBM Plex Mono

## Assets
- assets/portrait.webp, portrait-600.webp — hero portrait (background removed)
- assets/desk.webp — contact portrait (background removed)
- assets/speaking.webp, speaking-900.webp — events collage
- assets/logos/*.webp — 23 client logos extracted from the résumé (white by default, colour on hover)
- assets/resume-enterprise-sales.pdf, resume-xr-production.pdf — downloadable résumés

To replace an illustrative project visual, swap the inline <svg> inside that project's `.viz` block for an <img>.
