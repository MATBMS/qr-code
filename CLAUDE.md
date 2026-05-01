# CLAUDE.md

Guidance for Claude Code when working in this repository.

## Project

Frontend Mentor **QR code component** challenge — a single static card showing a QR code image, a headline, and a short paragraph. Built as the first project of a Claude Code bootcamp.

The user is an IT Product Owner pivoting to Agentic AI Engineer, at the **early stage** of a structured frontend learning path. Treat this as a learning exercise as much as a delivery exercise.

## Tech constraints (hard rule)

- **Pure HTML, CSS, and vanilla JavaScript only.**
- **No libraries, frameworks, build tools, or dependencies.** No npm, no CDN scripts, no preprocessors (Sass/Less), no Tailwind, no React/Vue/etc.
- Only use web-platform features and techniques the user has already been taught. If a task seems to require something outside that, flag it and ask before introducing it.

## Where things live

- `index.html` — entry point; starter markup (currently mostly empty; needs to be structured).
- `images/` — raster assets (jpg, png, webp) used at runtime: `image-qr-code.png`, `preview.jpg`.
- `icons/` — SVG icons and other icon files. Favicons always live here (e.g. `favicon-32x32.png`), even when they are raster PNGs.
- `fonts/` — local font files (currently empty).
- `design/` — **git-ignored** Frontend Mentor source assets, local reference only:
  - `desktop-design.jpg`, `mobile-design.jpg` — visual targets.
  - `style-guide.md` — colors, typography, breakpoints (Outfit font, Slate palette, 375px mobile / 1440px desktop).
  - `figma/` — Figma source file.
- `README.md` — Frontend Mentor boilerplate, not user-authored (to be rewritten later).

No CSS or JS files exist yet — create `style.css` (and `script.js` if/when needed) at the project root and link them from `index.html`.

## How to collaborate

- **Explain as you go.** Before non-trivial edits, briefly say *what* you're going to change and *why*. The user wants to learn both frontend and how to drive a coding agent.
- **Small steps.** Prefer one focused change at a time over large multi-file rewrites. The user should be able to follow every diff.
- **Teach the why.** When choosing between approaches (e.g., Flexbox vs Grid, `rem` vs `px`, semantic tags vs `<div>`), name the trade-off in one or two sentences.
- **Don't over-engineer.** This is a static card — no JS framework patterns, no CSS architectures (BEM/ITCSS) unless the user asks. Plain, readable code wins.
- **Accessibility matters from day one.** Use semantic HTML, meaningful `alt` text, and respect WCAG basics (contrast, focus states). Mention these as you make them, so they become habit.
- **Responsive baseline.** Mobile-first CSS, test from 320px upward as `style-guide.md` requires.

## Workflow

1. When asked to implement something, restate the goal in one line, then propose the approach before writing code.
2. Keep `index.html`, `style.css`, and (eventually) `script.js` the only files at the project root that you author. Don't add config files, package.json, or tooling.
3. After a change, point out what to look for visually so the user can verify it in a browser.

## Out of scope

- Build pipelines, bundlers, transpilers.
- TypeScript, JSX, CSS-in-JS.
- Hosting/deployment setup (handled separately when the user is ready).
- Tests — not part of the learning path yet.
