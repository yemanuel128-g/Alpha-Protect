# Alpha Protect · vastgelegde ontwerpkeuzes

## Kleur

Vastgelegd door Mike, 2026-08-14: donkerblauwe achtergrond met witte letters.

```css
:root {
  --bg:      #02006c;  /* achtergrond, vastgelegd */
  --ink:     #ffffff;  /* bodytekst en koppen */
  --surface: #01004a;  /* kaarten en secties, iets dieper dan bg */
  --line:    #3d3a99;  /* randen en scheidingslijnen */
  --muted:   #b9b7e8;  /* labels en bijschriften, nooit voor lopende tekst */
  --accent:  #ffb800;  /* enige accentkleur: knoppen, telefoonnummer */
}
```

Wit op `#02006c` haalt 17.2:1. Ruim boven de WCAG AAA-eis van 7:1, dus leesbaarheid is geen probleem.

`--muted` is bedoeld voor korte labels. Nooit voor hele zinnen: dan zakt het contrast door de AA-grens.

## Openstaand op deze kleur

- Het logo op de huidige holdingpagina staat in een bijna-zwart marineblauw vierkant. Op `#02006c` wordt dat een zichtbaar donker blok. Nodig: het logo als SVG of PNG met transparante achtergrond, in wit. Staat als vraag 4 in `vragen-alpha-protect.md`.
- `#02006c` is een zeer verzadigd blauw. Grote vlakken werken, foto's erop niet: elke foto met een warme tint gaat vloeken. Als er wel foto's komen (vraag 31), krijgen die een eigen donkere sectie in plaats van dat ze op het blauw drijven.
