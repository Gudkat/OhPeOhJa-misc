Kirjoita funktio listat_sanakirjaksi(lista1: list, lista2: list), joka saa paramerikseen kaksi listaa.

Jos listat ovat yhtä pitkiä, funktio palauttaa uuden sanakirjan (eli dict-olion), jossa avaimet on poimittu järjestyksessä ensimmäiseltä listalta ja arvot toiselta.

Jos listat eivät ole yhtä pitkiä, funktio palauttaa arvon None.

Koodiesimerkki:

```python
l1 = [1,2,3,4]
l2 = [500,400,300,200]
print(listat_sanakirjaksi(l1, l2))
```

Esimerkkituloste:

`{1: 500, 2:400, 3:300, 4:200}`
