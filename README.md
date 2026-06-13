# CM Oxhorn — Website Concepts

Sample website concepts for **CM Oxhorn Construction Company**, a general contractor. This repo contains a catalog landing page plus three full website directions that share the same brand and palette.

## Live site

Once GitHub Pages is enabled, the catalog is served at the repository's Pages URL (e.g. `https://<username>.github.io/cmoxhorn/`).

## Structure

```
index.html        Catalog landing page linking to all three concepts
site1/            Concept 01 — "Heritage" (classic serif, charcoal/ochre/bone/slate)
site2/            Concept 02 — "Ironworks" (bold industrial, iron black + safety orange)
site3/            Concept 03 — "Drafting Room" (quiet editorial, ink + blueprint blue)
brand/            Logo files and brand sheet (SVG + PNG)
.nojekyll         Tells GitHub Pages to serve all files as-is (no Jekyll build)
```

Each `siteN/` folder contains its own `index.html`, `privacy.html`, `terms.html`, and `cookies.html`, plus an `img/` folder of project illustrations and (sites 1–2) a `hero.png`.

## Palettes

The brand palette anchors all three concepts; sites 2 and 3 shift the accent and surface colors to suit their style.

### Concept 01 — Heritage (`site1/`)

The core CM Oxhorn brand palette.

| Name | Hex | Role |
|------|-----|------|
| Charcoal | `#3B3936` | Text, dark sections, footer |
| Ochre Gold | `#D89C2A` | Accent, CTAs, logo star |
| Bone White | `#F2EFE9` | Page background, light text |
| Slate | `#8E8C88` | Muted details, illustrations |

### Concept 02 — Ironworks (`site2/`)

Industrial variant — iron black with a safety-orange accent.

| Name | Hex | Role |
|------|-----|------|
| Iron Black | `#232120` | Page background |
| Gunmetal | `#37342F` | Panels, secondary surfaces |
| Safety Orange | `#E8662C` | Accent, headlines, CTA band |
| Steel | `#9AA0A3` | Muted details, illustrations |
| Off-White | `#EFEDE8` | Light text |

### Concept 03 — Drafting Room (`site3/`)

Editorial variant — ink and paper with a blueprint-blue accent.

| Name | Hex | Role |
|------|-----|------|
| Ink | `#2C3640` | Text, dark contact section |
| Blueprint Blue | `#56789B` | Accent, hairline rules, logo star |
| Paper White | `#F7F5EF` | Page background |
| Graphite | `#8C8E94` | Muted details, illustrations |
| Drafting Tan | `#E9E6DD` | Alternating section background |

## Notes

All content, contact details, statistics, and legal pages are **placeholder boilerplate** for demonstration and should be reviewed before production use.
