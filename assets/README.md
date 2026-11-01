# Manhaj Atlas logo set

Logo and icon files for the Manhaj-e-Inqilab-e-Nabawi Interactive Atlas website.

The mark is an eight pointed star (two squares rotated 45 degrees, the khatam geometry) with a balance scale, al-Mizan, cut out of its centre. The scale stands for justice (Nizam-e-Adl). The cut out scale lets the mark work on any background.

## Files

| File | Size | Use |
|---|---|---|
| `logo-mark.svg` | 512 x 512 viewBox | The symbol alone, gold on transparent |
| `logo-mark-mono.svg` | 512 x 512 viewBox | Single colour version, `fill="currentColor"` |
| `app-icon.svg` | 512 x 512 viewBox | Mark on a navy rounded square (rx 113, about 22%) with a safe margin of about 13% |
| `logo-horizontal.svg` | 1661 x 200 viewBox | Mark plus wordmark; text converted to outlines, no font needed |
| `favicon-16.png` | 16 x 16 | Browser tab icon (simplified, heavier variant of `app-icon.svg` for small sizes) |
| `favicon-32.png` | 32 x 32 | Browser tab icon (same simplified variant) |
| `apple-touch-icon.png` | 180 x 180 | iOS home screen; opaque navy, no transparent corners |
| `icon-192.png` | 192 x 192 | Web app manifest icon |
| `icon-512.png` | 512 x 512 | Web app manifest icon |
| `og-image.png` | 1200 x 630 | Social share image (link previews) |
| `site.webmanifest` | | Web app manifest (name, icons, colours, standalone display) |

## Colours

| Name | Hex | Use |
|---|---|---|
| Navy | `#06101e` | Background, app icon |
| Navy secondary | `#0b1b2f` | Panels, raised surfaces |
| Gold | `#e8c26a` | Mark, main wordmark, accents |
| Soft gold | `#f3dca0` | Highlights |
| Cream | `#f4ecdb` | Body text on navy |
| Teal | `#3fc1b0` | Wordmark second line, accent |

## Usage rules

- Clear space: keep a margin around the logo equal to one quarter of the height of the star's inner square. The inner square is 283 units high in the 512 unit grid, so the margin is about 71 units, which is about 18% of the star's width (400 units) and about 14% of the full 512 grid. Keep the same margin around the horizontal logo, measured from the height of its mark.
- Minimum size: 16 px for the mark (favicon, simplified variant). Use the full mark from 32 px upwards. Use the horizontal logo at no less than 400 px wide.
- Do not stretch, skew or rotate the logos. Scale them proportionally only.
- Do not recolour the logos, except with the mono version for single colour printing or CSS theming. Do not add effects, outlines or shadows.
- Do not place the gold logo on a light background without a navy panel behind it.
- Do not add lettering, calligraphy or figures inside the mark.

## Notes

- The mark contains no Arabic calligraphy, and no person or animal is depicted.
- The wordmark letters are Cinzel Bold, converted to outlines from `video/public/fonts/Cinzel.ttf`.
- The mark has no embedded raster images, no external references and no font dependency.
