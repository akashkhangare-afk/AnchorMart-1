# AnchorMart Admin Demo — Agent Instructions

This is a static admin dashboard demo. There is no frontend build system or backend service.

## Key facts
- Entry point: `anchormart-admin-light.html`
- Main UI logic: `js/app.js`
- Styling: `css/style.css`
- Static assets under `assets/`
- Local preview can run with `node serve.js` or `python -m http.server 8000`

## What to do
- Treat this as a plain HTML/CSS/JavaScript project.
- Do not add React, Svelte, or other framework scaffolding unless the user explicitly asks.
- Keep changes limited to the static files and the existing `serve.js` server if asked to modify project behavior.

## Useful references
- `README.md` for run instructions and project overview
- `serve.js` for local server behavior

## Suggested agent behavior
- When editing the dashboard, prefer `js/app.js` for logic and `anchormart-admin-light.html` for static markup.
- For preview-related questions, mention `Live Server` or `Live Preview` in VS Code and `node serve.js` for local hosting.
- Preserve the static/site-demo nature of the repo and do not introduce unnecessary package tooling.
