# Momentum Studios — Website Development

Standalone website prototype. Does not modify the current momentumstudios.us site or Momentum OS.

## Local preview

Install Node.js 20+ then run:

```bash
npm install
npm run dev
```

Open the local URL shown in Terminal (usually http://localhost:5173).

## GitHub and Vercel

1. Create a **new** GitHub repository named `momentum-studios-website-dev`.
2. Upload the contents of this folder to the repository root (including `index.html`, `services.html`, `package.json`).
3. In Vercel, create a **new** project under your Momentum team, import this GitHub repository, select framework **Vite**, and use the defaults (`npm run build`, output `dist`).
4. Keep the generated `.vercel.app` domain for review. Do not attach momentumstudios.us until ready to launch.

Every subsequent push to GitHub will trigger a Vercel deployment once Git integration is connected.

## Editing

`index.html` = homepage; `services.html` = services. Replace placeholder images and content with approved Momentum assets before launch.
