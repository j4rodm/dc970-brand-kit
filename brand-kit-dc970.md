# DC970 — Brand Kit v1.1
> Community Brand · High-Voltage Yellow Palette · May 2026

---

## Colors

### Core Palette

| Role | Name | Hex |
|---|---|---|
| Accent / Feature | Signal Yellow | `#F0C324` |
| Accent Highlight | Live Yellow | `#FCCA13` |
| Background (dark) | Hard Black | `#000000` |
| Background (mid) | Page Gray | `#F2F2F2` |
| Text (on dark) | White | `#FFFFFF` |
| Text (on light) | Hard Black | `#000000` |
| Link / Interactive | Electric Blue | `#7A82FF` |
| Muted / Subdued | Slate Gray | `#747989` |

### Color Roles

- **Signal Yellow (#F0C324)** — primary brand color; container backgrounds, section callouts, key UI accents; high-energy identifier for the brand
- **Live Yellow (#FCCA13)** — highlight and hover variant of Signal Yellow; use to show state changes or secondary emphasis
- **Hard Black (#000000)** — primary dark background; high-contrast canvas that makes yellow pop
- **Page Gray (#F2F2F2)** — neutral page background for light-mode surfaces; separates sections without visual noise
- **White (#FFFFFF)** — text on dark/black backgrounds; inverse surfaces
- **Electric Blue (#7A82FF)** — links and interactive elements only; not for general decoration
- **Slate Gray (#747989)** — captions, metadata, muted labels, secondary text on light backgrounds
- **Yellow is for accents, containers, and UI highlights — never use as text on white or light backgrounds**

### Tints (for backgrounds, cards, callout boxes)

- Signal Yellow 10–15% opacity — subtle highlight overlays on dark surfaces
- Hard Black 80% opacity — scrim overlays on images or video
- Electric Blue 15% opacity — hover/focus state backgrounds on interactive elements
- Page Gray at full opacity — card fills on white backgrounds for gentle separation

---

## WCAG 2.2 Contrast Reference

### Verified Safe Pairings (AA or better)

| Foreground | Background | Ratio | Level |
|---|---|---|---|
| Hard Black `#000000` | Signal Yellow `#F0C324` | ~12.6:1 | AAA |
| Hard Black `#000000` | Live Yellow `#FCCA13` | ~14.0:1 | AAA |
| Hard Black `#000000` | White `#FFFFFF` | 21.0:1 | AAA |
| Hard Black `#000000` | Page Gray `#F2F2F2` | 18.1:1 | AAA |
| White `#FFFFFF` | Hard Black `#000000` | 21.0:1 | AAA |
| Electric Blue `#7A82FF` | Hard Black `#000000` | ~5.5:1 | AAA |
| Slate Gray `#747989` | White `#FFFFFF` | ~4.6:1 | AA |
| Slate Gray `#747989` | Page Gray `#F2F2F2` | ~4.2:1 | AA |

### Forbidden Combinations (never use for text or meaningful content)

| Foreground | Background | Problem |
|---|---|---|
| White `#FFFFFF` | Signal Yellow `#F0C324` | ~1.7:1 — fails all levels |
| White `#FFFFFF` | Live Yellow `#FCCA13` | ~1.5:1 — fails all levels |
| Electric Blue `#7A82FF` | White `#FFFFFF` | ~2.9:1 — fails AA body text |
| Slate Gray `#747989` | Hard Black `#000000` | ~2.7:1 — fails AA body text |
| Signal Yellow `#F0C324` | Live Yellow `#FCCA13` | Near-identical; do not layer |

### Notes

- **Yellow backgrounds always require black text** — white on yellow fails at any size
- **Electric Blue links** are designed for use on dark (black) backgrounds where they pass AAA; avoid on white without underline or weight reinforcement
- Contrast ratios are calculated estimates based on hex values; verify with a contrast checker tool before final production use

---

## Typography

### Font Stack

| Role | Primary Font | Weight | Fallback Stack |
|---|---|---|---|
| Display / Heading | Sora | 800 (ExtraBold) | `'Trebuchet MS', 'Segoe UI', sans-serif` |
| Subheading | Sora | 600 (SemiBold) | `'Trebuchet MS', 'Segoe UI', sans-serif` |
| Body | Space Grotesk | 400 (Regular) | `'DM Sans', 'Helvetica Neue', Arial, sans-serif` |
| Light Body | Space Grotesk | 300 (Light) | `'DM Sans', 'Helvetica Neue', Arial, sans-serif` |
| Code / Mono | Lucida Console | 400 | `'Courier New', monospace` |

Sora and Space Grotesk are available on Google Fonts.

### Type Scale (Web)

| Element | Size | Weight | Color |
|---|---|---|---|
| Display heading | 4.5em | Sora 800 | White (on black) or Black (on yellow) |
| Section heading | 2–3em | Sora 800 | White or Signal Yellow |
| Subheading | 1.25–1.5em | Sora 600 | White or Black |
| Body text | 1em | Space Grotesk 400 | White (on dark) or Black (on light) |
| Light body / intro | 1em | Space Grotesk 300 | White (on dark) |
| Caption / metadata | 0.875em | Space Grotesk 400 | Slate Gray |
| Code block | 0.9em | Lucida Console 400 | White on semi-transparent gray (`rgba(144,144,144,0.2)`) |
| Button label | 0.9em, uppercase | Space Grotesk 500–600 | Black on Signal Yellow |

### Spacing

- Letter spacing (standard): `0.025rem`
- Letter spacing (buttons): `0.25rem`
- Button height: `4.25rem`; border-radius: `2.5rem`

---

## Layout & Structure

- Max content width: `80rem` with `5rem` horizontal padding
- Mobile-first responsive; minimum viewport: `320px`
- Layout engine: CSS Grid / Flexbox
- Sections use full-width containers with `overflow: hidden`
- Animated SVG particle background (organic, low-opacity) — decorative only, no contrast requirements

---

## Brand Voice

| Attribute | Description |
|---|---|
| Name | DC970 |
| Tone | Community-first; direct, technical, no fluff |
| Audience | Local tech community, hackers, builders, makers |
| Aesthetic | High-contrast, high-energy; black-and-yellow utility |
| Differentiator | Local roots, hands-on culture, real skills |

---

## Quick Reference — Copy/Paste Values

```
COLORS (High-Voltage Yellow — v1.0)
Signal Yellow:   #F0C324   primary brand accent
Live Yellow:     #FCCA13   highlight / hover variant
Hard Black:      #000000   primary dark background
Page Gray:       #F2F2F2   light-mode background
White:           #FFFFFF   text on dark backgrounds
Electric Blue:   #7A82FF   links and interactive (dark bg only)
Slate Gray:      #747989   muted / metadata text

FORBIDDEN COMBOS (never use for text)
White on #F0C324     (~1.7:1 — fail)
White on #FCCA13     (~1.5:1 — fail)
#7A82FF on #FFFFFF   (~2.9:1 — fail AA)
#747989 on #000000   (~2.7:1 — fail AA)

FONTS
Display/Heading: Sora 800         | fallback: Trebuchet MS, Segoe UI, sans-serif
Subheading:      Sora 600         | fallback: Trebuchet MS, Segoe UI, sans-serif
Body:            Space Grotesk 400/300  | fallback: DM Sans, Helvetica Neue, Arial, sans-serif
Code/Mono:       Lucida Console   | fallback: Courier New, monospace

BRAND NAME
Full:    DC970
Handle:  @dc970
URL:     dc970.org
Palette: High-Voltage Yellow v1.0
```

---

## Changelog

| Version | Date | Changes |
|---------|------|---------|
| v1.0 | 2026-05-15 | Initial brand kit — sourced from dc970.org live site |
| v1.1 | 2026-05-15 | Replaced Inter with Space Grotesk to eliminate overlap with template brand |
