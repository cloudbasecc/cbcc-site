# Cloudbase Country Club Website

Static site for the Cloudbase Country Club (CBCC), a Pacific Northwest hang gliding and
paragliding club. Published via GitHub Pages.

Plain HTML/CSS, no build step. Pages live in their own folders (e.g. `membership/index.html`)
so GitHub Pages serves clean URLs like `/membership/`.

## Structure

- `index.html` — homepage
- `css/style.css` — shared stylesheet
- `images/` — page images, organized by section
- `docs/` — downloadable files (e.g. the Dog Mountain waiver)
- Each other top-level folder (`about-us/`, `by-laws/`, `membership/`, `flying-site-guides/`, etc.) is one page, as `index.html` inside it

## Editing

Each page is a self-contained HTML file — edit directly and commit. There's no build/generator
step; what you see in the file is what gets published.
