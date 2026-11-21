# mohtasib.github.io

Personal site of Abdalkarim (Karim) Mohtasib, served by GitHub Pages at <https://mohtasib.github.io>.

Plain HTML and CSS with no build step: edit a file, commit, push, and the site updates.

| File | What it holds |
|---|---|
| `index.html` | All page content: bio, research themes, publications (with BibTeX), code, background |
| `style.css` | All styling. Colours are CSS variables at the top; dark mode redefines them |
| `404.html` | Page shown for broken or old links |
| `images/` | Profile photo at two sizes (JPEG + WebP) |
| `favicon.svg` | Browser tab icon |
| `.nojekyll` | Tells GitHub Pages to serve files as-is instead of running Jekyll |

## Adding a publication

Copy one `<li class="pub">` block in `index.html`, give it the next id (`p6`, `bib6`, …), and update the
title, authors, venue, DOI and BibTeX. Newest papers go first.

## Preview locally

```bash
python3 -m http.server 8000
```

Then open <http://localhost:8000>.
