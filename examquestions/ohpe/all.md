# Questions used in OhPe exams

## Kesä 2020 exam 1

- merkkijonot
- jaa_lista
- tulokset

## Kesä 2020 exam 2

- luvut
- listat_sanakirjoiksi

## Kevät 2022 exam 1

- merkkijonot
- jaa_lista
- tilastot

## Kevät 2022 exam 2 14.05.2022

- laskut
- lukutilasto
- funktiot1

## Kesä 2022 exam 1 02.07.2022

- luvut (sama kuin lukutilasto)
- erottele_sanakirja
- funktiot2

## Kesä 2022 exam 2 06.08.2022

- merkkijonot
- toistetuin_palindromi
- tilastot

## Syksy 2022 exam 1 01.10.2022

- laskut
  - esimerkin lukuja vaihdettu
  - `lopeta` komento -> `seis`
- jaa_lista
  - vaihdettu pos ja neg listojen järjestys
- funktiot1
  - vaihdettu esimerkki

## Syksy 2022 exam 2 29.10.2022

- luvut
  - vaihdettu isoin ja pienin järjestys
- erottele_sanakirja
  - poistettu a)-kohta
  - note: liian helppo
- tilastot
  - parannus: määritä nostettava error tarkemmin, esim. tietyllä tekstillä

## Syksy 2022 exam 3

- merkkijonot
  - muutettu keskiarvopituus pisimmän pituudeksi
- toistetuin_palindromi
- funktiot2

## Syksy 2022 exam 4 14.01.2023

- laskut
- erottele_sanakirja
- tilastot
  - tarkka teksti errorille lisätty

## Kevät 2023 exam 1 11.03.2023

- luvut
- jaa_lista
  - lisätty alkuperäisen listan muuttamisen kielto
- funktiot1

## Kevät 2023 exam 2 06.05.2023

- merkkijonot
- erottele_sanakirja
  - engl. b) kohta back
- tilastot

## Kevät 2023 exam 3 13.05.2023

- merkkijonot
- erottele_sanakirja
- funktiot2

## Kesä 2023 Extra exam 17.06.2023

- luvut
  - lisää tekstimuodossa maininta, että jos monta kertaa sama luku, tulostetaan ensimmäinen esiintymä
- jaa_lista
- murtolukulaskuri
  - lisää esimerkki negatiivisesta murtoluvusta
  - lisää testi sille, että murtoluku muunnetaan muunna_murtolukufunktiolla (esim testi että mockataan muunna_murtoluku funktio vääräksi ja sillon saadaan ei sama kuin oikea vastaus)

## Kesä 2023 exam 1 01.07.2023

  - laskut
  - etsi_geenin_sijainnit
  - lottosimulaattori
    - testejä pitää parantaa
      - testien nimet pitää fiksata
      - try - except on parempi jos self.fail(e) eikä nykyinen
      - pelaa_lottoa testi houno. Side_effect voittojen laskusta naamioi virheellisen rivien osumien laskemisen.
    - tehtävänannnossa pitää selkeyttää, että oikeassa rivissä kohdan ei tarvitse olla sama kuin omassa kupongissa

## Kesä 2023 exam 2 05.08.2023

  - merkkijonot
  - kopioi_ja_kaanna
  - funktiot1
    - huono kysymys. Joko oikein tai väärin. Jos ei ymmärrä mitä siinä neuvotaan, tulee tosi iso vähennys, jos ymmärtää esimerkit, liian helppo.
    
## Syksy 2023 exam 1 21.10.2023

- luvut
  - muokkaa testeriä ignoraamaan ":" puuttumiset printeistä
  - lisää maininta tehtävänantoon, että nollaa ei lasketa käyttäjän syöttämäksi luvuksi. Tämä näkyy jo esimerkistä mutta tuntuu olevan vaikeaa
- toistetuin palindromi
  - palindromit testi ei tarkitsa että palauttaako listan, jossa on monta kopiota samasta palindromista
  - korjaa tehtävänannossa Palindromi -> Palindromit (Otsikko)
  - sanamaarat itkee jos alkuperäistä listaa muutaa. Muuta testi tai kiellä muokkaus.
  - testit ei testaa isoja kirjaimia erikseen. Joko kirjoita tehtävänanto siten, että ei tarvitse huomioida, tai lisää testi tälle
- erottele_sanakirja

## Syksy 2023 exam 2 25.11.2023

- merkkijonot
  - enkunkieliseen kokeeseen pitää tarkentaa character määritelmää (ehkä suomen myös)
  - molempiin pitäisi voisi tarkentaa, että kyseessä on mitä tahansa merkkejä
- jaa_lista
  - lisätty mukaan nolla
- murtolukulaskuri
  - kannattaa mokkaa muunna murtoluku funktio Fractioniks ja sit vaan eri testissä tarkastaa että sitä kutsutaan. noilla on ylimääräsiä kutsuja mukana ja se heittää side-efektit pieleen

## Syksy 2023 exam 3 13.01.2024

- Kirjainten_esiintyminen
- vokaalit_funktio
- lottosimulaattori

## Kevät 2024 exam 1 9.3.2024

- laskut
- etsi_geenin_sijainnit
- funktiot2

## Kevät 2024 exam 2 4.5.2024

- luvut
- kopioi_ja_kaanna
  - selkeytä tehtävänantoa: "tulee muokata suoraan alkuperäistä matriisia." -> "tulee muokata suoraan alkuperäistä matriisia ja sen alkuperäisiä rivejä."
  - erota kopio ja käännä funktion käyttämisen testit. Nyt tulee hassuja tuloksia.
  - lisää testeja eripituisille matriiseille, ettei kovakoodaamalla voi saada vahingossa oikein
  - pitäisi hieman uudelleen nimetä asioita. copy niminen funktio on hieman kiusallinen, koska se on myös pythonin sisäinen funktio. 
- tilastot

## Kesä 2024 exam 1 8.6.2024

- merkkijonot
- funktiot1 (muunnettu ehdolliset_funktiot)
- murtolukulaskuri

## Kesä 2024 exam 2 20.7.2024

- kirjainten_esiintyminen
- jaa_lista
 - tää tehtävä roskiin. ihan liian helppo (.?)
- lottosimulaattori
  - testi joka testaa ettei arvonta voi arpoa nollaa

## Syksy 2024 exam 1 7.9.2024

- laskut
- etsi_geenin_sijainnit
- tilastot

## Syksy 2024 exam 2 19.10.2024

- merkkijonot
- caesar-salaus
- murtolukulaskuri

## Syksy 2024 exam 3 24.10.2024

- luvut
- kopioi_ja_kaanna
- funktiot2

## Syksy 2024 exam 4 23.11.202

- kirjainten_esiintyminen
- etsi_geenin_sijainnit
- lottosimulaattori

## Syksy 2024 exam 5 11.01.2025

- merkkijonot
- vokaalit_funktio
- tilastot