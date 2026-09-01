# Devfolio — Chezhil's Portfolio

A single-page personal portfolio, hand-written in semantic HTML and CSS. No framework,
no build step, no dependencies — open the file and it runs.

**Live site:** https://chezhil.github.io/devfolio/

## What's in it

- Semantic landmarks: `<header>`, `<main>` (with `#about` and `#projects` sections), `<footer id="contact">`
- A colour + type system built on CSS custom properties (`--brand`, `--ink`, `--paper`)
- Flexbox for the header/nav row, CSS Grid for the projects section
- A `@media (min-width: 640px)` breakpoint that takes the projects grid from 1 column to 2
- Flexible images (`max-width: 100%; height: auto`) so nothing overflows on a phone

## Run it locally

Clone the repo and open the page — that's the whole setup:

```bash
git clone https://github.com/chezhil/devfolio.git
cd devfolio
open index.html
```

Or serve it over HTTP if you prefer:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000.

## Structure

```
index.html        the page
styles.css        colour/type system, layout, breakpoint
assets/           favicon and portrait mark (SVG)
```

## Deployment

Deployed with GitHub Pages from the `main` branch, `/ (root)`.

## Contact

- Email: shirs.chezhils@gmail.com
- GitHub: https://github.com/chezhil
- LinkedIn: https://www.linkedin.com/in/chezhil-s/
