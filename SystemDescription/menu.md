---
layout: default
title: Étlap
nav_order: 3
parent: NeerY Rendszer
---
# Étlap szerkesztő

Az _"Étlap szerkesztő"_ menüpont esetében a saját menüdet töltheted fel hozzánk és innen egyszerűen frissítheted a különböző futár oldalakon található megjelenésedet és árazásodat, illetve az étlap megjelenik a "_Digitális Névjegykártyán"_ is, így azt bárki könnyen elérheti.

**Fejlesztés alatt, jelenleg csak manuális szerkesztés illetve a _Wolt_ menü _NeerY-be_ történő átmásolása működik, folyamatosan frissül!**

# Manuális szerkesztés
A menu feltoltese a kovetkezo gombokkal tortenik:
![](../../assets/images/menu_upload.png)
* Tetel hozzaadasa: Tetel alatt az etelt/italt ertjuk a NeerY rendszerben
* Kategoria hozzaadasa: A tetelek kategoriakba csoportosithatoak (pl: Levesek), kategoriaknak leirasuk es nevuk van
* File feltoltese: Bovebben a "Wolt menü szinkronizálása a NeerY rendszerbe" pont alatt olvashatsz rola

![](../../assets/images/menu_example.png)
Pelda egy Kategoriar (Levesek), ami 2 Tetelt tartalmaz

## Kategória hozzáadása/szerkesztése/törlése
Az elem hozzaadasa a "_Tetel hozzaadasa_" gombbal tortenik. Ekkor a kovetkezo ablak jelenik meg
![](../../assets/images/menu_add_category.png)

Itt a kategoria pont alatt rendelhetjuk az etelt egy mar letezo kategoriahoz. 
Az arazas eseteben jelenelg 3 kulonbozo arat lehet megadni, a rendszer online a "_Helybeni arat_" jeleniti meg, amennyiban van. Ha nincs "_Helybeni ar_", akkor az elso valos arat a masik ket mezo kozul (He;ybeni -> Wolt -> Foodpanda).

Torolni vagy szerkeszteni kategoria tartalmat a kategoriara kattintva lehet, mig a sorrend a kategoria vegen talalhato fol-le nyilakkal tortenhet.

## Tetel hozzáadása/szerkesztése/törlése
A tetel eseteben hasonloan tortnik minden mint a kategorianal taglaltak eseteben.
![](../../assets/images/menu_add_item.png)

## Sorrend megváltoztatása/kategória váltás
Amennyiben kategoria sorrendet valtoztatsz, az magaval viszi a kategoria alelemeit is (tetelek), mig a tetelek sorrendje csak kategorian belul tortenhet meg a nyilak segitsegevel. Tetel masik kategoriaba torteno atmozgatasahoz a

# Wolt menü szinkronizálása a NeerY rendszerbe
Először is jelentkezz be a _"Wolt"_ admin oldalára és navigélj el a _"Menu editor"_ részre. Itt a jobb fölső sarokban találhatő "..."-ra kattintva az _"Export entire menu as JSON"_ opciót válaszd.

![](../../assets/images/download_wolt.png)

Ez egy szöveges file-t fog lementeni az eszközödre.

Következő lépésként kattints "_File feltöltése"_ gombra, majd tallózd be az előzőleg letöltött file-t.

Ezzel készen is vagy, feltöltötted az étlapod. Hogy megbizonyosodj róla, hogy minden a legnagyobb rendben működik nézz rá a "_Digitális Névjegykártáyra"_ és ha ott megjelent az _"Étlap"_ opció, akkor minden rendben ment.

**A menüdet hamarosan innen töltheted fel egy kattintással a Wolt vagy Foodpanda oldalára, illetve a jövőben a vendégek itt is rendelhetnek tőled akár elvitelre is!**