# Shoyab Ali — Backend Engineer Portfolio

A responsive React + TypeScript + Vite portfolio with a dark technical design system, custom CSS/SVG-inspired project visuals, interactive experience timeline, filterable skills, architecture flow, and case-study modals.

## Requirements
- Node.js 18+ (Node.js 20+ recommended)
- npm

## Run locally
```bash
npm install
npm run dev
```

## Production build
```bash
npm run build
npm run preview
```

## Personalize before publishing
1. Open `src/data.ts`.
2. Add your real `email`, `linkedin`, and `github` URLs to `profile`. They are blank intentionally because the supplied resume has placeholder labels for these links.
3. Review all project details and metrics before publication.
4. Replace `public/Shoyab-Ali-Resume.pdf` if you update your resume.
5. Update the page description and social preview if your positioning changes.

## Deploy
Works on Netlify, Vercel, or any static host that supports Vite builds. Build command: `npm run build`. Publish directory: `dist`.

## Notes
- Project thumbnails are custom CSS-based portfolio illustrations, not screenshots of employer products.
- Case-study metrics are based on the supplied resume. Do not present project work as an employer production system.
- No contact form pretends to send messages; the contact area uses configurable email and profile links.
- Reduced-motion preferences are respected. Navigation, project details, experience expand/collapse, and skill category selection are interactive.
