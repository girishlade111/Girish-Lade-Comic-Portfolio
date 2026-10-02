# Girish Lade | Comic Portfolio

A bold, comic-book-style personal portfolio website for **Girish Lade** — software engineer, UI/UX designer, and founder of LadeStack. Single-file, zero-dependency, client-side only: just open `index.html` in a browser and it works.

## Features

- **Comic-book aesthetic** — halftone dot backgrounds, chunky black borders, hard offset shadows, skewed "Bangers" display type over clean "Nunito" body text
- **Hero section** — punchy intro with comic panel styling and call-to-action panels
- **About section** — profile, skills and background in comic-panel cards
- **Projects showcase** — featured builds laid out as comic panels
- **Contact section** — links to GitHub, LinkedIn and email
- **Responsive layout** — works on mobile, tablet and desktop
- **No build step, no dependencies** — pure HTML + CSS in one file; Google Fonts loaded from CDN (gracefully degrades offline)

## Tech stack

- HTML5 + CSS3 (custom properties, flex/grid, keyframe-free static design)
- Google Fonts: Bangers (display), Nunito (body)
- 100% client-side — no JavaScript framework, no server, no tracking

## Quick start

No install needed. Any of these works:

```bash
# Just open the file
xdg-open index.html

# Or serve locally
python3 -m http.server 8000
# -> http://localhost:8000
```

## Project structure

```
.
├── index.html   # entire site: markup + styles (single file)
└── README.md
```

## Deploy notes

- Static site — deploys anywhere: GitHub Pages, Cloudflare Pages, Netlify, Vercel, any static host
- GitHub Pages: enable from `main` branch, `/` (root) — the site is live at `https://girishlade111.github.io/Girish-Lade-Comic-Portfolio/`

## Author

Built by **Girish Lade** — https://ladestack.in
