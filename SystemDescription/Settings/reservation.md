---
layout: default
title: Foglalás
nav_order: 3
parent: Beállítások
grand_parent: NeerY Rendszer
---
# Foglalás
Itt állíthatsz be minden foglaláshoz köthető információt és szabályt.

### Értesítő e-mail
Erre az e-mail címre küldünk értesítést, ha bármilyen változás történt a foglalásokban.
### Foglalás időpont-granularitás
A foglalások ilyen időközökkel hozhatóak létre a nyitástól kezdődően.
Példa: a granularitás 15 percre van állítva, ekkor a vedégek a widgeten keresztül minden óra 00, 15, 30 és 45 percére foglalhatnak.
### Foglalás időpont-határidő
Ez az érték a helység nyitvatartásában beállított aznapi zárás előtti engedélyezett utolsó foglalási időpont.
Példa: ha egy hely 23:00-kor zár és ez az érték 120 perc, akkor a vendég 21:00 után kezdődő foglalást nem tud létrehozni az adott napra.
### Maximum létszám
Egy foglalás esetében a maximum megengedett létszám.
### Alapértelmezett foglalás hossz
A foglalás alapértelmezetten ilyen hosszú lesz.
### Maximum foglalási távolság
Az adott időpillanatban a vendég ilyen "messzire" tud foglalást létrehozni.
Példa: az érték 10 nap, 2022.05.01-én a vendég nem tud 2022.05.11. utánra foglalásokat létrehozni az online widgeten keresztül.
### Autotable
Két lehetséges opció létezik: "_Manual_" és "_Automatic_".
**Manuális** esetében a beérkező foglalások mindig bekerülnek a "_Függőben_" menüsorba és a helynek kell gondoskodnia arról, hogy ezeket egyenként elfogadja.
**Automatikus szabályok** esetében a rendszer
* elutasítja a foglalást, ha az adott időpontra nem található szabad asztal
* manuálissá teszi a foglalást és beteszi a "_Függőben_" menüsorba, majd erről értesítést küld, ha
*   - található szabad asztal, de foglalás létszáma nagyobb mint bármelyik üres asztal létszáma
*   - amennyiben található szabad asztal, de a foglalás létszáma kisebb, mint bármelyik (szabad asztal létszáma - 2) vagy bármelyik (szabad asztal létszáma / 2).
* minden más esetben elfogadja a foglalást.

Példák:

A helynek van
* 1 db 2 fős
* 1 db 5 fős és
* 1 db 9 fős asztala

_1. példa_

A következő foglalások jönnek be, mindegyik teljesen üres asztalok esetében értendő külön példa:
* Beérkezik egy 10 fős foglalás, mivel nincs ilyen asztal, így a rendszer ezt manuális foglalássá nyílvánítja és a helyre bízza, hogy hogyan kezeli ezt le.
* Beérkezik egy 1 fős foglalás. A rendszer ezt a 2 fős asztalra teszi automatikusan.
* Beérkezik egy 5 fős foglalás. A rendszer ezt a 5 fős asztalra teszi automatikusan.
* Beérkezik egy 6 fős foglalás. A rendszer ezt manuális foglalássá nílvánítja, mivel nincs olyan asztal, ami csak "kicsit" nagyobb (lásd "_Full-auto szabályok_")

_2. példa_

A következő foglalások jönnek be egy adott időpontban úgy, hogy a 2 fős és a 9 fős asztal tele van.
* Először jön egy 6 fős foglalás, ezt a rendszer automatikusan manuálissá teszi. A hely viszont, amikor átnézi elutasítja.
* Ezután jön egy 5 fős foglalás ugyanarra az időpontra, az 5 fős asztal még szabad, így a rendszer azt automatikusan elfogadja.
* majd ezután jönne ugyanazon időpontra egy 4 fős foglalás, de a rendszer ezt automatikusna elutasítja, hiszen az összes asztal foglalt.