# Wallis 1:1

Kaart om de echte wereld te vergelijken met de Minecraft-wereld **Wallis**: de Matterhorn en omgeving
1 op 1 (1 blok = 1 meter), gebouwd uit de echte kaart van Zwitserland, met grotten, ertsen, dorpen en dieren.

**Bekijken:** https://wesselaerts.github.io/wallis-kaart/

- Schuif tussen de echte luchtfoto en Minecraft, of kies *Echt* / *Minecraft*.
- Rode lijn: de wereld Wallis nu (9,7 × 6,1 km). Gele lijn: de oude Alpen-kaart van Cwlty.
  Gestippeld: ideeën voor de volgende stukken (zoom ver uit).
- Onder de muis: Minecraft-coördinaat, hoogte (y + 2610 = meter boven zee) en de Zwitserse coördinaat.

## Bronnen

Luchtfoto (SWISSIMAGE), Landeskarte, hoogtemodel (swissALTI3D, swissSURFACE3D) en landschapsmodel
(swissTLM3D): © swisstopo, open data. Kaartbibliotheek: Leaflet. Minecraft-ondergrond: Minecraft 26.3.

## Bijwerken

De tegels en `index.html` maakt het bouwprogramma van de wereld (op Wescloud:
`dev/kamers-ontwerp/kamer wessel/pc-server/minecraft/wallis/`, zie `LEESMIJ.md` daar):

```
draai.sh kaartlagen.py matterhorn <deze map>
draai.sh kaartpagina.py matterhorn <deze map> leaflet.css --los
git add -A && git commit -m "Kaart bijgewerkt" && git push
```
