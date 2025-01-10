Kopioi tehtäväpohjaasi tiedosto tulokset.txt tästä linkistä: https://www.cs.helsinki.fi/u/santlemp/tulokset.txt

Voit esimerkiksi luoda uuden tiedoston src-kansioon ja kopioida sinne tulokset.txt sisällön.

Tiedostosta löytyy jalkapallo-otteluiden tuloksia seuraavassa formaatissa:

`joukkue1 - joukkue2: maalit1 - maalit2`

Esimerkiksi rivi

`TPS - HJK: 2 - 0`

tarkoittaisi, että TPS on voittanut HJK:n maalein 2 - 0. Vastaavasti rivi

`SJK - HIFK: 1 - 1`

tarkoittaisi, että joukkueet ovat pelanneet tasapelin.

Joukkue saa voitosta kolme pistettä, tasapelistä molemmat joukkueet saavat yhden pisteen. Ottelun hävinnyt joukkue ei saa pisteitä.

Kirjoita funktio

`tulokset()`

joka lukee tiedoston sisällön ja palauttaa sanakirjan, josta löytyy kaikki joukkueet ja niiden yhteispistemäärät. Sanakirjassa avain on joukkueen nimi ja arvo pistemäärä.
