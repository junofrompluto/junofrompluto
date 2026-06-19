# LOU CASTRO — Studio Site

Source for **junofrompluto.com** — Lou Castro's studio / YouTube channel website.

A self-contained, single-file static site (`index.html`) with inline CSS and JS —
no build step and no external asset dependencies. Cinematic "cosmic" art
direction (red-desert / nebula mood, terracotta + amber + teal on ink-black).

## Contents

- **`index.html`** — the entire website (markup, styles, and scripts inline).
- **`studio-website-mood-prompts.md`** — the design brief: image-generation mood
  prompts for each section plus the locked color palette.

## Locked palette

| Token | Hex |
|---|---|
| Ink black | `#0A0A0F` |
| Deep indigo void | `#15172B` |
| Mars terracotta | `#C65A37` |
| Warm amber glow | `#E8A04C` |
| Teal accent | `#3FB6A8` |
| Pale cream | `#F3EAD8` |

## Run locally

It's a single static file — just open `index.html`, or serve it:

```bash
python3 -m http.server 8080
# visit http://localhost:8080
```

## Deploy

Static — host anywhere (Netlify, GitHub Pages, Vercel, S3). The live site is at
**junofrompluto.com**.
