# WAFLO Landing Page

Public marketing site for WAFLO — AI Sales Assistant for WhatsApp.

## Tech Stack

- React 19 + TypeScript
- Vite 6
- Tailwind CSS 4
- React Router DOM 7

## Development

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
```

## Deploy

This project is configured for Vercel deployment.

```bash
vercel --prod
```

## Structure

```
src/
  pages/
    LandingPage.tsx   # Main landing page component
  main.tsx            # React entry point
  App.tsx             # Root component
  index.css           # Global styles + Tailwind
```

## Configuration

- `vercel.json` — Vercel deployment config
- `vite.config.ts` — Vite + React + Tailwind plugins
- `tsconfig.json` — TypeScript config
