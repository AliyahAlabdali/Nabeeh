# Nabeeh brand assets

The artwork follows the approved identity: the original bilingual wordmark,
the approved lowercase a, and the SMS symbol with a selected pink phrase.
SVG lettering is outlined. No external fonts or embedded raster images are used.
The image-based source letterforms were converted to vector contours without
font substitution. The icon and refined a retain their approved path geometry.

## Files

| Asset | SVG canvas | PNG export |
| --- | --- | --- |
| `nabeeh-logo-dark` | 1240 × 540 | 4960 × 2160 |
| `nabeeh-logo-transparent` | 1240 × 540 | 4960 × 2160 |
| `nabeeh-logo-light` | 1240 × 540 | 4960 × 2160 |
| `nabeeh-symbol-dark` | 512 × 512 | 2048 × 2048 |
| `nabeeh-symbol-transparent` | 512 × 512 | 2048 × 2048 |

The `icons/` directory contains dark and transparent PNGs at 32, 64, 128,
256, 512, and 1024 pixels. The square composition provides avatar-safe margins.
PNG masters include 300 ppi metadata. Their pixel dimensions determine digital
resolution; SVGs can scale without a fixed resolution.

The README uses GitHub-compatible `<picture>` sources with
`prefers-color-scheme`: `nabeeh-logo-light.svg` for light mode and
`nabeeh-logo-transparent.svg` for dark mode. Both are transparent, so they
blend into the page. The light variant changes only the lettering to the
approved dark color `#0B101B`; the symbol is identical. The light version is
also the fallback for environments without media-query support.

Use `nabeeh-logo-dark` when a fixed dark background is needed. Other transparent
exports use light lettering and suit dark surfaces. Keep the symbol, internal
spacing, colors, and bilingual lettering together. Do not retype the names in
another font.

## Palette

| Role | Color |
| --- | --- |
| Background | `#0B101B` |
| Wordmark | `#F5F5FA` |
| Light-theme wordmark | `#0B101B` |
| Message outline | `#626A82` |
| Message content | `#80879D` |
| Suspicious phrase and selection | `#FF3B8D` |
