# Echo Brand Family — Logo Guide

All echo* brand logos share a unified visual language: a primary icon with circuit-trace background lines and colored glow, on a dark (#0D1117) background.

## Logos

| Brand | Icon | Color | Glow | File |
|---|---|---|---|---|
| **echomodel** | Orb + ring | Blue (#58A6FF) | No | `echomodel-logo-512.png` |
| **echoskill** | Wrench (Lucide, MIT) | Cyan (#5ED4E6 → #1F8494) | Yes | `echoskill-logo-512.png` |
| **echofit** | Heart (Lucide, MIT) | Pink (#F0A0E0 → #8B2F8B) | Yes | `echofit-logo-512.png` |
| **echosphere** | Concentric rings | Blue→Purple→Pink gradient | N/A | `echosphere-logo-512-dark.png` |

## Where logos live

Each brand's logo is in its org's `.github` repo under `brand/`:

- `echomodel/.github/brand/echomodel-logo-512.png` → served at `https://echomodel.ai/brand/echomodel-logo-512.png`
- `echo-skill/.github/brand/echo-skill-logo-512.png` → served at `https://echoskill.ai/brand/echo-skill-logo-512.png`
- `echofit/.github/brand/echofit-logo-512.png` → served at `https://echofit.ai/brand/echofit-logo-512.png`
- `echomodel/echosphere/brand/` → echosphere portal assets

## Shared visual elements

**Circuit traces** — asymmetric horizontal and vertical lines with dot endpoints. Some traces cross through the icon area. No diagonals. Not mirrored. Suggests "neural network" without being literal.

**Glow** — soft radial gradient behind the icon (echoskill, echofit). echomodel omits glow since the orb itself is luminous.

**Dark background** — all logos use #0D1117 (GitHub dark theme).

## Editing logos

The file `logo-generator.html` in this directory is the source for all three logos. Open it in a browser to render and download PNGs at 512px. Edit the JavaScript to change colors, sizes, line positions, or icon paths.

The wrench and heart icons are from [Lucide](https://github.com/lucide-icons/lucide) (MIT license). Free to use commercially, no attribution required.

## Color palette

| Brand | Primary | Dark | Light |
|---|---|---|---|
| echomodel | #58A6FF | #1A4F8A | #A5D6FF |
| echoskill | #3FB9CF | #1F8494 | #5ED4E6 |
| echofit | #DA70D6 | #8B2F8B | #F0A0E0 |
| echosphere | gradient: #58A6FF → #A371F7 → #F778BA | | |
