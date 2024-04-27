# Táborhelyadatbázis
    
    Informatika 2 Házi feladat
    
# Specifikáció
## Feladat Informális leírása
  A feladat célja egy táborhelyeket nyílvántartó adatbázis létrehozása és karbantartása. Az adatbázisban tárolni szeretnénk Magyarország táborhelyeit ahol tudunk táborozni, illetve a táborozó csapatokat. Cél, hogy lehessen foglalni és nyílvántartsuk ezeket és, hogy tájékozódni tudjunk, hogy hová tudunk menni táborozni továbbá értékelni tudjuk a táborhelyeket.

## Elérhető funkciók
Az alkalmazás a következő funkciókat biztosítja:
* Táborhelyek:
  * Új táborhely létrehozása
  * Meglévő táborhelyek adatainak módosítása
  * Táborhely törlése
  * Táborhelyek listázása, keresés tájegység, név, és fajta alapján
  * Táborhelyek megjelenítése a térképen
  * Táborhely értékelése 0-5 skálán és rövid szöveggel
* Csapatok:
  * Új csapat létrehozása
  * Csapatadatok módosítása
  * Csapatok törlése
* Táborozás:
  * Táborhely foglalása
  * Foglalás törlése
  * Adott táborhely táborozási előzményének listázása
  
## Adatbázis séma
Az adatbáziban a következő entitásokat és attribútumokat tároljuk:
* Táborhely: név, tályegység, koordináták, fentartó, elérhetőség, rövid leírás, képek
* Csapat: név, közösség (például cserkészet, egyházközség), vezető neve, vezető telefonszáma, csapatlétszáma
* Táborozás: Csapat, táborhely, táborozás kezdete, táborozás vége

Név: Kolok Miklós Keve

Neptun-kód: CWGMHG
