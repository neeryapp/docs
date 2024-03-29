---
layout: default
title: Widgetek
nav_order: 7
parent: Beállítások
grand_parent: NeerY Rendszer
---
# Widget
A NeerY widget olyan esztétikus és könnyen integrálható megoldást nyúj, mellyel a potenciális vagy már meglévő vásárlóid kiszolgálása és informálása válik egyszerűvé.
Amennyiben franchise rendszerben gondolkozol és egy összesítő foglalási rendszert szeretnél, keress minket bizalommal.

A widget a NeerY szerverein fut és neked ezzel nincs más dolgod, minthogy a legenerált linket elhelyezd bárhová. Legyen ez akár egy Facebook post, Instagram info oldal, levél aláírás. Amennyiben a meglevő honlapodba szeretnéd beágyazni keress minket további információkért.

Teszt widget példa
```html
https://places.neery.net/land/n666
```

A linkek mellett található "_Másolás_" ikonra kattintva a rendszer vágólapra másolj a linket.

A rendszer alapvetően egy abszolút, soha meg nem változó linket generál ("_Hosszú link"_), melyet alapvetően oda ajánlunk beillszteni, ahol maga a link "tartalma" nem látszik. Emellett lehetőség van egy link alias generálására (_"Rövid link"_), melyet a hely tetszőlegesen megválaszthat (pár szabályt betartva). Ez a link párhuzamosan működik a másikkal és funkcióját tekintve teljesen mindegy melyiket használjuk. Az egyetlen különbség, hogy mivel a "Rövid link" megváltoztatható, így a változtatás után a helynek mindenhol, ahol ezt használta le kell cserélnie az új linkre a régit.

## Példa a Digitális Névjegykártya integrációjára
Miután kimásoltad a Widget linkjét (kattints a link melletti gombra), már csak be kell illesztened a megfelelő helyre.

Legyen ez most a Facebook profil tetején található gomb.
A Facebbok oldal tetején az "_Edit ..._" gombra kattintva válasszuk ki a megfelelő opciót, például jelen esetben a "_Contact Us_"-ra esett a választás, hiszen a Widgeten az összes elérhetőségünk, a foglalás és az étlep is megjelenik, amennyiben azokat megadtuk.

![](../../assets/images/insert_did_1.png)
![](../../assets/images/insert_did_2.png)

Majd illesszük be az előzőleg vágólapra másolt linket és mentsük el a változtatást.

![](../../assets/images/insert_did_3.png)

Az oldalon található teszt widget mindig az adott helyhez van kötve, így itt akár egyből teszthelhed is a foglalási ciklust mielőtt kitennéd azt élesben bárhova.

### Csak a foglalási rész megjelenítése
Ha nem akarod a teljes interaktív widgetet kitenni, hanem csak a fogalásra van szükséged, akkor a link végére írd oda, hogy "/reserve".

A teljes widget linkje (példa)
```html
https://places.neery.net/land/n666
```

Csak a foglalásé (példa)
```html
https://places.neery.net/land/n666/reserve
```

## Rövid link
Lehetőség van arra, hogy a rendszer által generált hosszú (statikus és ezáltal soha meg nem változó ID) mellé, a hely egy rövidebb, vagy beszédesebb linket generáljon magának. <br>
**Fontos** Amennyiben ezt a linket a hely megváltoztatja, akkor ezt a változást minden beillesztett (pl, FB, insta stb) rövid link esetében el kell végezni.

A rövid/custom widget linkje (példa)
```html
https://places.neery.net/land/neery_etterem
```


## iframe komponens

Példa beillesztés egy "üres" html file esetében

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body, html {
            height: 100%;
            margin: 0;
        }

        .iframe-container {
            position: relative;
            width: 100%;
            height: 100%;
        }

        .responsive-iframe {
            width: 100%;
            height: 100%;
        }
    </style>
    <title>Embedded Iframe Example</title>
</head>
<body>
    <div class="iframe-container">
        <iframe class="responsive-iframe" src="paste-your-iframe-link-here" frameborder="0" allowfullscreen></iframe>
    </div>
</body>
</html>
```