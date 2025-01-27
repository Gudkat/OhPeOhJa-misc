# Questions used in OhJa exams

## Autumn 2021 exam 4

- Muusikko
- VertailtavaPiste
- Kirjat ja kirjailijat

## Spring 2022 exam 1 07.05.2022

- VertailtavaPiste
- Ralliautot ja kuljettajat
- Pelikortti ja korttipakka

## Spring 2022 exam 2

- Kysymys ja tentti
- Sanageneraattori
- Kirjat ja kirjailijat

## Summer 2022 exam 1 02.07.2022

- Muusikko ja orkesteri
- Luottotili
- Varastonhallinta

## Summer 2022 exam 2 13.08.2022

- VertailtavaPiste
- Ralliautot ja kuljettajat
- Nelilaskin

## Autumn 2022 exam 1 08.10.2022

- Kysymys ja tentti
- Luottotili
- Sanageneraattori

## Autumn 2022 exam 2 15.12.2022

- Muusikko ja orkesteri (luokat)
- Varastonhallinta (tiedostonkäsittely) EI TESTEJÄ VALMIINA
- Pelikortti ja korttipakka (generaattori + luokat)

## Autumn 2022 exam 3 21.1.2023

- VertailtavaPiste (luokat)
- Sanageneraattori (generaattori)
- Nelilaskin (tiedostonkäsittely)

## Autumn 2022 exam 4 25.02.2023

- Kysymys ja tentti
- Ralliautot ja kuljettajat
- Pelikortti ja korttipakka

## Spring 2023 exam 1 13.5.2023

- Muusikko ja orkesteri (luokat)
- Sanageneraattori (generaattori)
- Nelilaskin (tiedostonkäsittely)

## Summer 2023 exam 1 10.06.2023

- Noppa ja noppapeli 
    - selvennä Noppapelin str metodin rivivaihtoja (riviltä loppui tila). Porukka vastasi rivijaolla paljon ja se olikin parempi. Ota käyttöön ens kerralla.
    - Tee testit sille, että heitetään alle kuusisivuista noppaa (varmistaa ettei ole käytetty nopan sivuja heittojen lukumääränä)
    - Huonosti muotoiltu tehtävänanto "meni 1 heittoa saada viisi samaa"-erityistapausta ei tarvitse huomioida VOI ymmärtää että ei tarvitse tulostaa mitään, vaikka tarkoitus on että tulostetaan "1 heittoa"
- Luottotili
    - Liian helppo
- Kirja ja kirjailija
    - Ei yhtä helppo mutta myös liian helppo

## Summer 2023 exam 2 08.07.2023

- Resepti
    - esimerkki siitä, että jos uusi nimi ei ole merkkijono, nimi ei vaihdu
    - tästä testi on kommentoitu pois englanninkielisessä versiossa. 
- ReseptiKirja
    - voisi tehdä lisäyksen, että kaikki reseptit palautusta muokkaamalla ei voi muokata (tai poistaa) reseptiä, joka on ReseptiKirja olioon tallennettu
    - poista resepti selityksessä resepti -> reseptiolion, että varmasti ymmärtää ettei tarkoitus ole antaa nimeä vaan olio
    - puuttuu testi __str__ metodille
- reseptiohjelman käyttöliittymä ja tallennus
    - tehtävänantoon lisäys siitä, mitä ohjelma tulostaa jos ei löydy yhtään reseptiä kun palautetaan kaikki reseptit (esimerkissä on jo)
    - viestit reseptien löytymiselle valinnalla 4 ja 6 ovat epäjohdonmukaisia. KORJAA
    - ei oo testiä sille, että printit oikein jos määrittelemätön valinta
    - resepti nimellä löytyi resepti: on rivinvaihdolla englanniksi ja ilman rivinvaihtoa suomeksi. KORJAA
    - no recicpe with name vs no recipe with the name. PUUTTUU 'THE' (monesta kohtaa) (eng)
    - vois muuttaa noi testit semmosiksi, että löydettyjen reseptien järjestyksellä ei ole väliä

## Summer 2023 exam 3 12.8.2023

- VertailtavaPiste
  - selkeytys tehtävänantoon, että VertailtavaPiste + VertailtavaPiste palauttaa VertailtavanPisteen ei tuplea.
  - esimerkki luokkien käytöstä
- Auto
  - luokan yhteinen vuosiluku ei saa olla globaali muuttuja
  - arvo_nyt ja €/km metodeille testit missä niitä kutsutaan 2 kertaa peräkkäin ja verrataan tuloksia, jotta varmistetaan että niissä ei muuteta attribuutteihin tallennettuja arvoja
  - testi että auton arvon muutokset toimii oikein jos nykyvuotta muutetta toisen auton kautta useammin kuin kerran peräkkäin (jotta ei lasketa auton arvoa viimeisen muutoksen perusteella)
- Pelikortti ja korttipakka

## Autumn 2023 exam 1 28.10.2023

- Muusikko ja orkesteri
    - str tarkastukset käyttämään str() tyyppimuunnosta, ei tarkastamaan mitä ohjelma tulostaa.
- Sanageneraattori (generaattori)
- Ralliautot ja kuljettajat 
    - Tehtävänantoon selkeytystä. Mainitse että kyseessä on Auto-olio ei Auton merkki jne jne

## Autumn 2023 exam 2 16.12.2023

- Noppa ja noppapeli
- Auto
  - test_e2_cost_per_kilometer_ja_vuoden_vaihtuminen huono virheviesti ainakin kun b kämmää.
- Nelilaskin
  - eri tapa kirjoittaa alku printti ja väli printti. '4 calculations stored in history' vs '4 calculations in history:'. Ei mitään järkeä.

## Autumn 2023 exam 3 20.1.2024

- Resepti
- ReseptiKirja
  - selkeytä kysymystä saatavilla olevista ainesosista ja reseptin sisältämistä ainesosista
- reseptiohjelman käyttöliittymä ja tallennus

## Autumn 2023 exam 4 24.2.2024

- Tuote
- Ostoslista
- Ostosten_muokkaus_ja_tallennus

## Spring 2024 exam 1 23.3.2024

- Muusikko ja orkesteri
- Auto
- Nelilaskin

## Spring 2024 exam 2 11.5.2024

- Kysymys ja tentti
- Aamupala_generaattori
- Pelikortti ja korttipakka

## Summer 2024 exam 1 15.6.2024

- Resepti
- ReseptiKirja
- reseptiohjelman käyttöliittymä ja tallennus

## Summer 2024 exam 2 17.8.2024

- VertailtavaPiste
- Noppa ja noppapeli
- Nelilaskin

## Autumn 2024 exam 1 26.10.2024

- Resepti
- ReseptiKirja
- reseptiohjelman käyttöliittymä ja tallennus (muutettu)

## Autumn 2024 exam 2 14.12.2024

- Tuote
  - Lisää testi sille, ettei yksikkö ole kovakoodattu str metodiin
- Ostoslista
  - Lisää testi sille, että olemassa olevaa lisätään uudestaan
  - tehtävänannossa oli paluta_kaikki_tuotteet (TYPO)!. Korjasin normikokeen versiosta sen, toivottavasti ei päädy myöhempiin kokeisiin. Testeri asetettu toimimana molemmilla. Sen voi varmaan poistaa enskerralla kunhan tuo typo ei livahda uudestaan.
- Ostosten_muokkaus_ja_tallennus

## Autumn 2024 exam 3 17.12.2024

- Muusikko ja orkesteri
- Aamupala_generaattori
- Nelilaskin

## Autumn 2024 exam 4 18.1.2025

- VertailtavaPiste
- Aamupala_generaattori
- Noppa ja noppapeli