---
layout: default
title: Naptár
nav_order: 1
parent: NeerY Rendszer
---
# Naptár
A naptár nézetben jelennek meg a foglalások és majd a rendelések is (Wolt, Foodpanda integráció folyamatban). A "Függőben" menüsorban az el nem fogadott foglalások találhatóak (lásd Üzemmód). Itt lehet létrehozni asztalt vagy Manuális foglalást (Walk in, telefon, stb) is. Ahhoz, hogy a foglalási rendszer működjön minimum 1 asztal szükséges és a nyitvatartást meg kell határozni. A rendszer nem mutatja a nyitvatartáson kívüli időket/foglalásokat, igaz ezek csak és kizárólag az étterem által hozhatóak létre, vendég által nem!

![](../../assets/images/calendar_detailed.png)

## Nap váltás
Napot vagy a dátum melletti nyilakkal, vagy a naptár ikonnal lehet váltani.

## Asztal létrehozása
Ahhoz, hogy foglalások megvalósulhassanak létre kell hozni (legalább) 1 asztalt. Ezt az "Asztal létrehozása" gombra kattintva tehetjük meg. Ekkor felugrik egy új ablak, ahol az asztal elnevezését és a férőhelyek számát lehet megadni. Ezen információ a vendég számára nem publikus.
A létrehozott asztal utólag szerkeszthető/törölhető.

## Manuális foglalás
Manuális  azok a foglalások, amiket a hely maga ad hozzá (jellemzően walk-in, telefonos foglalás stb). Ekkor a kötelezően kitöltendő mezők az időpont és az asztal. Ha ez megtörténik a rendszer automatikusan felhelyezi a foglalást a kiválasztott asztalra. Amennyiben a "Név" és "E-mail" cím is kitöltésre kerül, akkor a vendégnek egy üzenetet is küldünk a foglalás megerősítéséről.

## Üzemmód
A foglalási rendszer használható "Full-Auto" és "Manual" üzemmódokban (A "Manual" nem összekeverendő az előző "Manuális foglalás" menüponttal. Beállítása: "Profil" menüpont, "Információ" almenü "Autotable" szekció). Amennyiben az Autotable "Manual" üzemmódban van, akkor az összes beérkező foglalás a "Függőben" menüsorba kerül és a helynek egyenként kell ezeket elfogadnia/elutasítania. Erre a foglalás távolságától függően van ideje.
Ha az Autotable "Full-Auto" üzemmódban van, akkor a rendszer a bejövő foglalásokat megpróbálja elhelyezni az asztalokon. Ha ez nem sikerül, akkor azt a foglalást átrakja "Manuális"-ra és erről üzenetet küld a helynek.