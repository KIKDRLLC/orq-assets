# orq-assets

Public static assets for **Orquídea** — logos and social icons served to HTML email
templates via the [jsDelivr](https://www.jsdelivr.com/) CDN.

Assets are grouped by **location** (mirroring the brand workspace layout):

```
honduras/   # Honduras-specific assets (wordmark with "Honduras" lockup)
universal/  # shared assets used across all locations
```

## Contents

| Path | Purpose |
| --- | --- |
| `honduras/logos/orquidea-honduras-logo.png` | Orquídea + Honduras wordmark (648×204, transparent) |
| `universal/social/linkedin.png` | LinkedIn glyph on brand-purple circle (96×96) |
| `universal/social/facebook.png` | Facebook glyph on brand-purple circle (96×96) |
| `universal/social/instagram.png` | Instagram glyph on brand-purple circle (96×96) |

`.svg` sources are kept alongside each `.png` for re-rendering.

## CDN usage

```
https://cdn.jsdelivr.net/gh/KIKDRLLC/orq-assets@main/honduras/logos/orquidea-honduras-logo.png
https://cdn.jsdelivr.net/gh/KIKDRLLC/orq-assets@main/universal/social/linkedin.png
https://cdn.jsdelivr.net/gh/KIKDRLLC/orq-assets@main/universal/social/facebook.png
https://cdn.jsdelivr.net/gh/KIKDRLLC/orq-assets@main/universal/social/instagram.png
```

Brand purple: `#8540b2` · Brand navy: `#002740`
