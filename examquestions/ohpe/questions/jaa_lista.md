Kirjoita funktio jaa_lista(lista: list), joka saa paramterikseen kokonaisluvuista koostuvan listan. Funktio palauttaa kaksi listaa tuplessa: ensimmäisessä listassa on kaikki alkuperäisen listan negatiiviset alkiot ja toisessa listassa kaikki positiviiset. Alkioiden järjestyksen tulee noudattaa alkuperäisen listan järjestystä.

Esimerkki funktion kutsumisesta:

```python
lista = [1, -1, 2, -3, 5, -1, 1, 1, 9]
lista1, lista2 = jaa_lista(lista)
print(lista1)
print(lista2)
```

Esimerkkituloste:

```
[-1, -3, -1]

[1, 2, 5, 1, 1, 9]
```
