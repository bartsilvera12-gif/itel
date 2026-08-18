# Referencia externa (no es el repo de este proyecto)

repo: bartsilvera12-gif/Tio-CR
branch: main
role: reference-only

Leído como referencia de patrones para la home de I-TEL. No se copió código ni assets:
las piezas se re-escribieron desde cero sobre el sistema Industry y la marca I-TEL.

## Last sync
date: 2026-08-18T13:29:14Z
tree: af0e4f50d4d3

### Updated in this project
- Hero rehecho al patrón de Tio-CR: media a pantalla completa con capas de velo, logo centrado, indicador de scroll en SVG.
- Copy del hero (kicker, titular, párrafo, CTAs) movido a una sección "Propuesta" bajo el hero, como el Intro de Tio-CR.
- Topografía luminosa reubicada como fondo de esa sección.
- `<video>` listo en el hero apuntando a `hero.mp4` (lo provee el cliente).

## Screen map
| Pantalla | Referencia leída |
| --- | --- |
| Hero (`ITEL Home v2.dc.html`) | `components/Hero.tsx` — capas de overlay, indicador de scroll |
| Propuesta (`ITEL Home v2.dc.html`) | `components/Intro.tsx` — orden kicker / titular / CTAs |
| Reveals y parallax | `components/Reveal.tsx`, `components/GlowBlob.tsx`, `components/SpotlightPointer.tsx` |
