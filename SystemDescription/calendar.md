---
layout: default
title: Naptár
nav_order: 1
parent: NeerY Rendszer
---
# Naptár
A naptár nézetben jelennek meg a foglalások. A "_Függőben_" menüsorban ("Példa Foglalás") az automatikus üzemmód által el nem fogadott foglalások találhatóak (lásd "_todo_"). Illetve itt lehet létrehozni "Manuális foglalást" (Walk in, telefon, stb) és "Rendezvényt" is. Ahhoz, hogy a foglalási rendszer működjön minimum 1 asztal szükséges ("_Beállítások/Asztalok_") és a nyitvatartást ("_Beállítások/Foglalás_") meg kell határozni. A rendszer nem mutatja a nyitvatartáson kívüli időket/foglalásokat, igaz ezek csak és kizárólag az étterem által hozhatóak létre, vendég által nem!

## Teljes naptár nézet

![](../../assets/images/calendar/calendardefaultview.png)

## Foglalás kártya

A függőben levő foglalás kezelése a kártyára kattintva történik meg.

![](../../assets/images/calendar/reservationcard.png)

A kártya fejlécében a foglaló neve található.
A középső szekcióban kis ikonok jelzik, hogy milyen információ áll rendelkezése.
Ezek sorban: Van-e allergiája?, Van-e egyébb szükséglete? Fűzött-e kommentet a foglaláshoz? Visszatérő vendég-e? Fűzött-e a hely kommentet a vendéghez?
Míg a legalsó sorban a foglalás további adatai találhatóak: Létszám, nap, időpont.

A foglalás kártyára kattintva egy kifejtett leírást találhatunk, illetve itt lehet elfogdani vagy visszautasítani magát a foglalást is.

![](../../assets/images/calendar/reservationcarddetailed.png)

Az elfogadás gombra kattintva a rendszer felajánlja a szabad szatalokat a foglalás időszakában.

![](../../assets/images/calendar/reservationcardtables.png)

A megfelelő asztal(ok) kiválasztása után a foglalás felkerül a naptárba.

![](../../assets/images/calendar/reservationacceptedgrid.png)

## Naptár funkciók
![](../../assets/images/calendar/switchviews.png)

### Nap váltása
Napot vagy a dátum melletti nyilakkal vagy a naptár ikonnal lehet váltani.

### Nézet váltása, adott nap nyomtatása
Lehetőség van arra, hogy kinyomtassuk az adott napi foglalásokat illetbe a naptár és a lista nézet között váltsunk.

Ezeket a dátum melleti gombokkal tehetjük meg rendre a "Nyomtatás", "Lista nézet" és "Naptár nézet" gombokkal.

Alant a "Lista nézet"" látható, funkcionalitását tekintve az időpont módosításában tér el a "Naptár nézettől" ez itt ugyanis jelenlg nem lehetséges.

![](../../assets/images/calendar/calendarlistview.png)

## Asztal létrehozása
Ahhoz, hogy foglalások megvalósulhassanak létre kell hozni (legalább) 1 asztalt. Ezt a "_Beállítások/Asztalok_" menüpontban tehetjük meg. Részletes leírést lásd ott.

## Manuális foglalás
"_Manuálisak_" azok a foglalások, amiket a hely maga ad hozzá (jellemzően walk-in, telefonos foglalás stb). Ekkor a kötelezően kitöltendő mezők az időpont és az asztal. Ha ez megtörténik a rendszer automatikusan felhelyezi a foglalást a kiválasztott asztalra. Amennyiben a "_Név_" és "_E-mail_" mezők is kitöltésre kerülnek, akkor a vendégnek egy üzenetet is küldünk a foglalás megerősítéséről.
Manuális foglalás esetén egy foglalást bármennyi asztalon el lehet helyezni.

## Rendezvény létrehozása
A rendezvények olyan elemek jelenleg, melyek az adott időtartamra az összes eérhető asztalt lefoglalják, ezáltal vendégek által nem lesznek foglalhatóak. 
Rendezvényeknek kezdő és végső időpontjuk van csak.

## Üzemmód
A foglalási rendszer használható "_Automatikus_" és "_Manuális_" üzemmódokban (A "_Manuális_" nem összekeverendő az előző "_Manuális foglalás_" menüponttal. Beállítása és további információ a "_Beállítások_" menüpont,"_Foglalások_" almenü alatt található). Amennyiben az "_Autotable_" "_Manuális_" üzemmódban van, akkor az összes beérkező foglalás a "_Függőben_" menüsorba kerül és a helynek egyenként kell ezeket elfogadnia/elutasítania.
Ha az "_Autotable_" "_Automatikus_" üzemmódban van, akkor a rendszer a bejövő foglalásokat megpróbálja elhelyezni az asztalokon. Ha ez nem sikerül, akkor azt a foglalást átrakja "_Manuális_"-ra és erről üzenetet küld a helynek, illetve ha egyáltalán nincs szabad hely, akkor a foglalást elutasítja.