# GeoThai Assets

Brand assets for GeoThai. `raw/` holds the source-of-truth files; everything else is generated/exported.

## icons/

Browser, PWA, and OS iconography.

| File                         | Format | Size    | Use                      |
| ---------------------------- | ------ | ------- | ------------------------ |
| `favicon.ico`                | ICO    | 15 KB   | Browser tab icon (root)  |
| `favicon-16x16.png`          | PNG    | 16x16   | Browser tab fallback     |
| `favicon-32x32.png`          | PNG    | 32x32   | Browser tab fallback     |
| `apple-touch-icon.png`       | PNG    | 180x180 | iOS home screen          |
| `android-chrome-192x192.png` | PNG    | 192x192 | Android home screen, PWA |
| `android-chrome-512x512.png` | PNG    | 512x512 | Android splash, PWA      |

## logo/

Brand logo by theme. `default/` is for light/dark agnostic contexts; pick `dark/` or `light/` based on background.

| Theme      | SVG                      | PNG                      | WebP                      |
| ---------- | ------------------------ | ------------------------ | ------------------------- |
| `default/` | `GeoThai-logo.svg`       | `GeoThai-logo.png`       | `GeoThai-logo.webp`       |
| `dark/`    | `GeoThai-logo-dark.svg`  | `GeoThai-logo-dark.png`  | `GeoThai-logo-dark.webp`  |
| `light/`   | `GeoThai-logo-light.svg` | `GeoThai-logo-light.png` | `GeoThai-logo-light.webp` |

- Use `svg` for web (README, docs, site) — scales clean.
- Use `webp` for web where SVG is overkill — smaller than PNG.
- Use `png` only for legacy/email clients that can't render SVG or WebP.

## raw/

Source-of-truth logo files. Treat as upstream; regenerate exports from these.

| File                    | Format | Role                    |
| ----------------------- | ------ | ----------------------- |
| `GeoThai-logo-raw.svg`  | SVG    | Canonical vector source |
| `GeoThai-logo-raw.png`  | PNG    | Raster reference        |
| `GeoThai-logo-raw.webp` | WebP   | Raster reference (web)  |
