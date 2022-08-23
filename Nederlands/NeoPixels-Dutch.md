# NeoPixel
Neopixels zijn reeksen verbonden RGB-LED's die kunnen worden geprogrammeerd met de micro:bit om leuke patronen te tonen.


## De NeoPixel-hardware aansluiten op de micro:bit
1. GND-draad naar micro:bit GND-aansluiting
2. VCC-draad naar micro: bit 3V-aansluiting
3. IN wit naar micro:bit P0 terminal

## NeoPixel-bibliotheek toevoegen aan de code-editor
1. Selecteer de "+Extensions" in de categorielijst met functieblokken
2. Typ "neopixel" in het vak "Search or enter project URL..."
3. Kies neopixel
4. Nu heb je een nieuwe functieblokcategorie "Neopixel"


## Je eerste Neopixel-code
Maak code die:
- Na het indrukken van schakelaar A: stel de eerste neopixel in op een kleur die (willekeurig) is geselecteerd uit een vooraf geconfigureerde lijst
- Nadat je op schakelaar B hebt gedrukt: Draai de neopixel-reeks met één pixel
- Na het indrukken van schakelaar A+B: start of stop het automatisch verschuiven ("rotate") van alle neopixelbits met een bepaalde snelheid
- verhoog de automatische verschuifsnelheid wanneer de micro:bit naar rechts wordt gekanteld
- verlaag de automatische verschuifsnelheid wanneer de micro:bit naar links wordt gekanteld

*TIP:*
- Configureer je neopixel op P0 met 8 LED's in GRB-formaat
- Gebruik Neopixel-functieblok "Range" om individuele LED's te selecteren
- Gebruik de "Strip Show" na een "shift" of "rotate" om het effect te zien
- Gebruik een array voor de vooraf geconfigureerde lijst
- Enkele hexadecimale waarden voor primaire kleuren:
  - Rood: 0xff0000 = 167111680
  - Groen: 0x00ff00 = 65280
  - Blauw: 0x0000ff = 255
- Voeg ook 0 toe aan de lijst zodat je gekleurde LED's kunt verwijderen met de A + B-schakelaars