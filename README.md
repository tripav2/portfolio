# portfolio

Personal portfolio website of **Viha Tripathi** — Electrical Engineering student at McMaster University.

A hand-coded static site (HTML + CSS + vanilla JS, no frameworks, no build step), showcasing hardware and embedded projects: a 360° spatial mapping sensor, a robotic waste-sorting system, analog circuit designs, and more.

## Live site

Hosted with GitHub Pages: `https://tripav2.github.io/portfolio/`

## Run locally

Just open `index.html` in a browser — that's it. (Or serve the folder with any static server, e.g. `python3 -m http.server`.)

## Structure

```
index.html    — all page content
styles.css    — the whole design system (dark engineering theme)
script.js     — mobile nav, scroll reveals, hero canvas animation
```

## Editing

- **Add a project:** copy one `<article class="project-card">` block in `index.html`, swap the icon/title/tags/description.
- **Colors:** all theme colors live in the `:root` block at the top of `styles.css` — change `--accent` to re-theme the whole site.
