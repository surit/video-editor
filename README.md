# SURIT STUDIO — Browser Video Editor

A zero-backend, single-file browser video editor hosted at **[editor.surit.com.np](https://editor.surit.com.np)**.

## Project Structure
- `index.html` — Complete application (UI, styles, canvas renderer, timeline, and media exporter).
- `netlify.toml` — Netlify static hosting, security headers, and SPA fallback rules.

## Deployment
1. Push `index.html` and `netlify.toml` to the `main` branch on GitHub.
2. Netlify deploys the root directory (`.`) automatically with zero build step.
3. Live at `https://editor.surit.com.np`.
