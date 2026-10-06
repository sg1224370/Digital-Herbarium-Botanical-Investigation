# Botanical Case Files

An interactive digital herbarium and botanical investigation archive built with React, TypeScript, and Vite.

## Run locally

**Requirements:** Node.js 22.12 or newer and npm.

```bash
npm ci
npm run dev
```

Vite prints the local address when the development server starts.

## Build

```bash
npm run build
npm run preview
```

The production-ready static site is generated in `dist/`. The `dist/` folder is build output and is intentionally excluded from Git; deployment rebuilds it from the source.

## Deploy with GitHub Pages

1. Upload or push the contents of this folder to a GitHub repository. Keep `package.json`, `package-lock.json`, `index.html`, `src/`, and `.github/` at the repository root.
2. In the repository, open **Settings → Pages** and set the build and deployment source to **GitHub Actions**.
3. Push to the `main` or `master` branch, or run the **Deploy to GitHub Pages** workflow manually from the **Actions** tab.
4. When the workflow completes, open the URL shown in the workflow's deployment summary.

The workflow installs the locked dependencies, builds the app, and publishes `dist/`. No server or environment secrets are required for the current static app.
