---
layout: default
title: Widgetek
nav_order: 3
parent: NeerY Rendszer
---
A NeerY widgetekkel olyan könnyen integrálható megoldásokat nyújtunk, melyekkel a potenciális vagy már meglévő vásárlóid kiszolgálása válik egyszerűvé.

# Foglalás
Az itt található widgetek a foglalást segítik elő. Amennyiben franchise rendszerben gondolkozol és egy összesítő foglalási rendszert szeretnél, keress minket.

A widgeteknél található gombok funkciói:
- Link másolása/Másolás: a linket, vagy a beillesztendő kódot vágólapra másolja.
- Előnézet: megmutatja a működő, valós widgetet egy új ablakban.
- QR kód generálás: a linket QR kód formájában készíti el, így akár nyomtatott formában is könnyen terjeszthető (flyerek, matricák, poharak oldalán stb) 

## Beépülő NeerY Foglalási Widget
Erre akkor van szükséged, ha a foglalás widgetet a honlapod szerves részéve szeretnéd tenni. Itt egy egysoros scriptet generálunk, melyet a honlap kódjába kell beágyazni.

Az alapvető szabály, hogy a widgetet valahol a <body>-ban helyezd el, és ha szeretnéd, hogy magyar nyleven is működjön, akkor a UTF-8 karakter szetre is szükséged lesz.

```html
<head>
    <!--Insert the utf-8 meta tag for extended language functionality-->
    <meta charset="utf-8"/> 
</head>

<body>

    <!--The div is optional, the script can be placed anywhere within the <body>-->
    <div>
        <!--Insert here the script copied from the webpage-->
        <script src="this will be auto-generated in your profile page"></script>
    </div>
    
</body>
```

Technikai segítség esetén keress minket bizalommal!

## NeerY Foglalási Widget linkként
Ez egy általunk hostolt foglalási widget, így tulajdonképpen a kimásolt link bárhová elhelyezhető, legyen az egy e-mail aláírás, vagy egy automatikus Facebook Messenger üzenet szintúgy, mint egy gomb linkje a honlapodon.

# NeerY Digitális Névjegykártya
A névjegykártya egy olyan link összesítő, amely az "Információ" menüpontban található összes elemet gyűjti ki és generálja le egy interaktív digitálsi névjegykártyává illetve a "_NeerY Foglalási Widget linkként"_ widgetet is hozzáteszi. Tökéletes megoldás, ha csak egy linkre van lehetőséged (Instagram profil, Facebook "_További Információk"_ gomb, stb), de mindent el szeretnél mondani magadról.

![](../../assets/images/landing.png)

## Példa a Digitális Névjegykártya integrációjára
A Digitális Névjegykártya linkje a "_Widget_" menüpont alatt található. Itt a megfelelő menüpontnál "_Link másolása_" gombra kattintva a generált link vágólapra kerül. 

![](../../assets/images/copy_did.png)


Következő lépésként navigáljunk el oda, ahova be szeretnénk illeszteni a linket. Legyen ez most a Facebook profil tetején található gomb.
A Facebbok oldal tetején az "_Edit ..._" gombra kattintva válasszuk ki a megfelelő opciót, például jelen esetben a "_Contact Us_"-ra esett a választás, hiszen a Digitális Névjegykártyán az összes elérhetőségünk, a foglalás és az étlep is megjelenik, amennyiben azokat megadtuk.

![](../../assets/images/insert_did_1.png)
![](../../assets/images/insert_did_2.png)

Majd illesszük be az előzőleg vágólapra másolt linket és mentsük el a változtatást.

![](../../assets/images/insert_did_3.png)

Az oldalon található teszt widget mindig az adott helyhez van kötve, így itt akár egyből teszthelhed is a foglalási ciklust mielőtt kitennéd azt élesben bárhova.

**Megjegyzés:** a "_NeerY Widget Linkként_" és a "_NeerY Digitális Névyjegykártya_" opcióban található linkek bárhova elhelyezhetőek, akár egy e-mail aláírásba, akár az Instagram profilon vagy csak simán egy Facebook üzenetbe is válaszként, a widgetek úgy is működni fognak.