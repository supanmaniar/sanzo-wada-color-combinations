# Sanzo Wada — A Dictionary of Color Combinations

An interactive, searchable web edition of all **348 colour combinations** and **159 named colours** from Sanzo Wada's *A Dictionary of Color Combinations* (Seigensha).

**Live site:** https://supanmaniar.github.io/sanzo-wada-color-combinations/

---

## Why this edition

Other editions of this dataset present the colours. This one also tells you whether you can actually use them:

- **WCAG contrast grading on every combination** — each card carries its minimum contrast ratio, graded AAA / AA / AA Large / Low. A **Details** panel opens the full breakdown in a focused modal: the palette, every pair previewed in both directions as text-on-background, and every colour checked against black and white. Filter the whole grid by grade, multi-select.
- **Export from any swatch** — every combination exports directly to CSS variables, JSON, Tailwind, Adobe `.ase`, Photoshop `.aco`, GIMP `.gpl` or Figma Tokens Studio, scoped to just that swatch or to your current filters.
- **A palette drawn from the book itself** — the interface is coloured with Wada's own Nile Blue, Deep Indigo and Dark Tyrian Blue, with every text pairing verified at AA or better.

---

## Features

- All 348 combinations, filterable by number of colours (2, 3, or 4)
- Full-text search across colour names, hex values, and combination numbers
- Hex, RGB, CMYK, and vec3 value formats
- Light and dark themes, following system preference — both built from swatches in the dictionary (Nile Blue, Deep Indigo, Dark Tyrian Blue, Black, White), with every text/background pairing verified at AA or better
- Related-combination links grouped by the colour they share, each group headed by the colour's swatch and name, with hover and keyboard-focus previews
- Sort by number, colour count, book, or most-used colours
- Browse-by-colour index covering all 159 named colours
- Export the current selection as CSS variables, JSON, or a Tailwind colour map
- Export any single combination from its own card — the same copy and download formats, scoped to just that swatch
- Download swatch files: Adobe `.ase`, Photoshop `.aco`, GIMP/Inkscape `.gpl`, and Figma Tokens Studio JSON
- WCAG contrast checker — every combination carries its minimum contrast grade, graded AAA / AA / AA Large / Low
- Details panel — a **Details** button on each card opens a focused modal with the palette, the full contrast breakdown, and related combinations, so the grid stays compact and uniform instead of stretching to fit expanded content. The modal carries its own **Export** button, so you can export a combination without leaving it
- Colour-on-colour text check — each pair is previewed in both directions (A as text on B, and B as text on A) with real body and large-text samples rendered in the actual colours, alongside a verdict of AAA body / AA body / AA large / Not usable, so you can see at a glance whether a combination works as a text/background pairing rather than only against black or white
- Black and white check — every colour in a combination is also previewed against both black and white text, with the better of the two called out, so you can tell whether a colour needs light or dark text on it
- Filter by contrast grade, multi-select — combine AAA, AA, AA Large and Low to narrow the grid
- Empty state offers a one-click "Clear all filters" reset
- `<noscript>` fallback — all 348 combinations remain readable without JavaScript
- Shareable URLs — filters, sort, and value format are stored in the query string
- Apple-inspired interface: SF-style typography, translucent sticky toolbar, soft depth and shadow, refined motion, and full `prefers-reduced-motion` support
- Responsive down to small phones — the hero trims itself on narrow and short viewports, the details panel becomes a bottom sheet, and touch targets grow on coarse-pointer devices. Hover previews are suppressed where there is no hover, so a tap navigates straight to the combination instead of flashing a preview first
- Sectioned layout: hero with key figures, a two-row toolbar (search, then filters), and clearly headed Browse / Combinations / Export sections
- Accessible: skip link, visible focus rings, keyboard-operable previews, `aria-live` result counts
- Print stylesheet for clean paper output
- Fully self-contained single HTML file — no build step, no external assets, works offline

## Contents

| File | Description |
| --- | --- |
| [`index.html`](./index.html) | The interactive site (self-contained) |
| [`og-image.png`](./og-image.png) | Social preview image (1200×630) |
| [`PALETTE-INDEX.md`](./PALETTE-INDEX.md) | Complete palette index in Markdown — all 348 combinations, 159 colours, 6 swatch books |
| [`ATTRIBUTION.md`](./ATTRIBUTION.md) | Full credits and licensing detail |
| [`LICENSE`](./LICENSE) | MIT licence |
| [`robots.txt`](./robots.txt) | Crawler policy and sitemap pointer |
| [`sitemap.xml`](./sitemap.xml) | Sitemap for search engines |

## Data

| Metric | Value |
| --- | --- |
| Combinations | 348 |
| Unique named colours | 159 |
| Total swatches | 1032 |
| Two-colour combinations | 120 |
| Three-colour combinations | 120 |
| Four-colour combinations | 108 |

Colour names keep their source spellings, including historical forms such as *Cerulian Blue* and *Sulpher Yellow*, and the source's own inconsistency of *Gray* and *Grey*.

## Credits

This project is a presentation of data and code created by others. Full credit belongs to the original creators:

- **Supan Maniar** — webpage design and build (this repository)
- **Sanzo Wada** — original author of *A Dictionary of Color Combinations* (Seigensha, 2011; based on *Haishoku Soukan*, 1933–34)
- **[Matt DesLauriers](https://github.com/mattdesl/dictionary-of-colour-combinations)** — colour dataset (MIT)
- **[Dain M. Blodorn Kim](https://github.com/dblodorn/sanzo-wada)** — compilation of the dataset (MIT)
- **[ben elwyn](https://github.com/bravokiloecho/color-combinations-sanzo-wada-public)** — original interactive site design (MIT)

See [`ATTRIBUTION.md`](./ATTRIBUTION.md) for details.

## Licence

Code and data are released under the [MIT Licence](./LICENSE), preserving the terms of the upstream MIT-licensed sources. The underlying book and its colour names remain the work of Sanzo Wada and Seigensha.
