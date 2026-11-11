# Momentum Studios — Website Development

Standalone Vite / plain HTML website. This repository does not modify Momentum OS or the live momentumstudios.us site.

## Local development

Use Node.js 20.19+ or 22.12+.

```bash
npm install
npm run dev
```

## Production verification

```bash
npm run build
npm run preview
```

The output is `dist/`. `vite.config.js` explicitly includes both `index.html` and `services.html`. Check both `/` and `/services.html` in the production preview.

## Structure

- `index.html`: short homepage, four core disciplines and email contact.
- `services.html`: production, photography, creative direction, design, plus supporting content and advertising services.
- `styles.css`: shared responsive styles, keyboard focus and reduced-motion support.
- `public/favicon.svg`: studio favicon.

The site uses system fonts and an original CSS graphic, with no third-party media requests. The former stock portfolio placeholders have been removed. Add approved Momentum footage, photography and project credits before introducing a selected-work section; do not present concept graphics as client work.

## Deployment boundary

Retain the existing development Vercel project and `.vercel.app` URL. Build command: `npm run build`; output: `dist`. Do not attach, reassign or modify momentumstudios.us. Pushing a branch may trigger Git-connected Vercel previews; changes are currently local until explicitly pushed.
