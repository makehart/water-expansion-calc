# water-expansion-calc
Expansion Tank Pressure Calculation

# Paisuntasäiliön paineen laskenta
Tämä yksinkertainen HTML-sivu laskee paisuntasäiliön lopullisen paineen suljetussajärjestelmässä, kun järjestelmän veden lämpötila nousee ja vesi laajenee. Laskenta perustuu yksinkertaistettuun malliin, jossa käytetään Boylen lakia (ideaali kaasu) ja veden tiheyden muutosta lämpötilan funktiona.   

## Ominaisuudet

- Käyttäjä voi syöttää:
  - Veden alkutilavuuden (litraa)
  - Veden alku- ja loppulämpötilan (°C)
  - Paisuntasäiliön koon (litraa)
  - Paisuntasäiliön esipaineen (bar)
  - Huomioidaanko kaasun lämpeneminen vai ei

- Sivulla lasketaan:
  - Veden laajeneminen litroina
  - Lopullinen paine paisuntasäiliössä
  - Veteen varastoitunut lämpöenergia (kWh)

## Käyttö

1. Avaa `index.html` (tai vastaava tiedosto) suoraan selaimessa.
2. Syötä haluamasi arvot tai käytä oletusarvoja.
3. Paina **"Laske"**-painiketta.
4. Tulos näytetään sivulla.

## Huomioitavaa

- Laskenta on yksinkertaistettu. Oletukset:
  - Paisuntasäiliö sisältää esipaineistetun kaasun (esim. typen tai ilman), joka käyttäytyy ideaalikaan mukaisesti.
  - Veden ominaisuudet noudattavat valittua approksimaatiota lämpötilan ja tiheyden suhteen.
  - Paisuntasäiliön ja muun suljetun järjestelmän tilavuus ei muutu lämpötilan tai paineen takia.

