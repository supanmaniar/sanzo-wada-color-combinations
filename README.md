# Sanzo Wada — A Dictionary of Color Combinations

An interactive, searchable web edition of all **348 colour combinations** and **159 named colours** from Sanzo Wada's *A Dictionary of Color Combinations* (Seigensha).

**Live site:** https://supanmaniar.github.io/sanzo-wada-color-combinations/

---

## Features

- All 348 combinations, filterable by number of colours (2, 3, or 4)
- Full-text search across colour names, hex values, and combination numbers
- Hex, RGB, CMYK, and vec3 value formats
- Light and dark themes, following system preference — both built from swatches in the dictionary (Nile Blue, Deep Indigo, Dark Tyrian Blue, Black, White), with every text/background pairing verified at AA or better
- Related-combination links with hover and keyboard-focus previews
- Sort by number, colour count, book, or most-used colours
- Browse-by-colour index covering all 159 named colours
- Export the current selection as CSS variables, JSON, or a Tailwind colour map
- Export any single combination from its own card — the same copy and download formats, scoped to just that swatch
- Download swatch files: Adobe `.ase`, Photoshop `.aco`, GIMP/Inkscape `.gpl`, and Figma Tokens Studio JSON
- WCAG contrast checker — every combination carries its minimum contrast grade, with the full pairwise breakdown inside each card, graded AAA / AA / AA Large / Low
- Filter by contrast grade, multi-select — combine AAA, AA, AA Large and Low to narrow the grid
- Empty state offers a one-click "Clear all filters" reset
- `<noscript>` fallback — all 348 combinations remain readable without JavaScript
- Shareable URLs — filters, sort, and value format are stored in the query string
- Apple-inspired interface: SF-style typography, translucent sticky toolbar, soft depth and shadow, refined motion, and full `prefers-reduced-motion` support
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
