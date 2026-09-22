# Helia Mozony — personal site

A single-page bilingual (Persian / English) personal site for **Helia Mozony**,
Business Data Analyst at SnappMarket.

**Live:** https://helmofski.github.io/helia-mozony-landing/

## What is here

- `index.html` — the whole site: markup, styles and script in one self-contained file.
  No build step, no dependencies. Fonts come from Google Fonts.

## Sections

| Section | Content |
| --- | --- |
| Hero | Name, role, one-paragraph positioning, HM monogram |
| The path | Vertical timeline of roles, research and teaching, filled as you scroll |
| Expertise | Analysis & modelling, dashboards & visualisation, automation |
| Day to day | The four things the work comes down to |
| Contact | Email (click to copy), LinkedIn, location |

## Editing

Open `index.html` in any editor.

- **Text** lives twice, once per language: `<span class="fa">…</span>` for Persian and
  `<span class="en">…</span>` for English. Edit both so the toggle stays in sync.
- **Colours** are CSS custom properties in the `:root` block at the top —
  `--ground`, `--ink`, `--a1`, `--a2` and the `--grad` gradient.
- **The logo** is the `<symbol id="hm">` SVG near the top of `<body>`.

Commit and push to `main`; GitHub Pages redeploys automatically.
