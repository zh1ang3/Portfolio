# Zi Yang Zhang — portfolio site

Plain HTML/CSS/JS, no build step. Upload this whole folder to any static host
(GitHub Pages, Netlify, Vercel, Cloudflare Pages) and `index.html` is the site.

## Videos
- `assets/video/panty-stocking.mp4` is the Panty & Stocking title sequence (re-encoded to ~5MB, same 1080p).
  It autoplays when you open the project in the portfolio, and sits paused on the title card
  (`assets/video/ps-poster.jpg`) on the case study until you press play.
- To add the Gentle Monster video, put it in `assets/video/` and set `video:` for `gm` in `const PROJECTS` in `index.html`.

## Pages
- `#home` — window card with the typewriter ticker
- `#portfolio` — the portfolio panel (click a card to expand it)
- `#panty-stocking` — the case study
- `#about`, `#b-sides`, `#resume`, `#contact` — "coming soon" placeholders (empty in Figma)

## The duckling
Sprites live in `assets/duckling/` (1px = 1 pixel; the page scales them up 3–4x).
Any element with a `data-perch` attribute is a surface the duckling can be dropped on and walk along.
