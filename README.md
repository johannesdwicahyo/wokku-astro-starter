# Wokku Astro Starter

Bare-bones [Astro](https://astro.build) SSR starter — one-click deployable from [Wokku](https://wokku.cloud), built automatically with nixpacks.

## Deploy on Wokku

Click **Deploy** in the Wokku dashboard, paste this repo URL, and your Astro app is live in minutes on your own server.

## Local development

```bash
npm install
npm run dev
```

## How it works

- Astro SSR via `@astrojs/node` adapter in `standalone` mode
- `Procfile` starts the Node server on `$PORT` with `HOST=0.0.0.0`
- `npm run build` (run automatically by heroku-nodejs buildpack) outputs to `dist/server/entry.mjs`
