---
layout: default
title: Profil
nav_order: 2
parent: NeerY Rendszer
---
A profil menüpontban változtathatóak meg azok az információk, amik a vendég számára láthatóak vagy információ tartalommal bírnak (pl foglalás esetében).

# Információ
Itt az általános adatok és a foglalási szabályok találhatóak jelenleg.

### Név
A regisztrációkor megadott helység név. A honlapon keresztül nem módosítható, bármilyen elírás vagy változás esetén keress minket bizalommal.
### Leírás
Az applikációban fog megjelenni.
### E-mail
A helység e-mail elérhetősége, ez jelenik meg a foglalások esetében információként a vendég számára.
### Foglalás értesítő e-mail
Azon e-mail cím, ahova a helység értesítést kér a foglalásokról. A kettő e-mail cím megegyezhet.
### Nyitvatartás
A helység nyitvatartása. A foglalás widget ezt veszi figyelembe és ehhez képest lehet azt bekonfigurálni.
### Telefonszám
A helység telefonszáma, ez jelenik meg a foglalások esetében információként a vendég számára.
### Weboldal/Twitter/Facebook
A helység egyéb szociális/online megjelenései.
### Foglalás időpont-granularitás
A foglalások ilyen időközökkel hozhatóak létre a nyitástól kezdődően.
Példa: a granularitás 15 percre van állítva, ekkor a vedégek a widgeten keresztül minden óra 00, 15, 30 és 45 percére foglalhatnak.
### Foglalás időpont-határidő
Ez az érték a helység nyitvatartásában beállított aznapi zárás előtti engedélyezett utolsó foglalási időpont.
Példa: ha egy hely 23:00-kor zár és ez az érték 120 perc, akkor a vendég 21:00 után kezdődő foglalást nem tud létrehozni az adott napra.
### Maximum létszám
Egy foglalás esetében a maximum megengedett létszám.
### Alapértelmezett foglalás hossz
A foglalás alapértelmezetten ilyen hosszú lesz. A vendég képes ezt felülírni a foglaláskor, de nem lehet hosszabb mint a maximum foglalás hossz.
### Maximum foglalás hossz
Egy foglalás maximális hossza.
### Maximum foglalási távolság
Az adott időpillanatban a vendég ilyen "messzire" tud foglalást létrehozni.
Példa: az érték 10 nap, 2022.05.01-én a vendég nem tud 2022.05.11. utánra foglalásokat létrehozni az online widgeten keresztül.
### Autotable
Két lehetséges opció létezik: "_Manuális_" és "_Full-auto_".
**Manuális** esetében a beérkező foglalások mindig bekerülnek a "_Függőben_" menüsorba és a helynek kell gondoskodnia arról, hogy ezeket egyenként elfogadja.
**Full-auto szabályok** esetében a rendszer
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

_1.) példa_

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

# Widgetek
A widget integrációját segítő menüpont. Az elérhető lehetőségekről bővebben a "_Widgetek_" menüpontban olvashatsz. Amennyiben további technikai segítségre lenne szükséged keress minket bizalommal.

# Törlés
A hely végleges törlése. Nem visszavonható művelet, minden adatot törlünk a szervereinkről.