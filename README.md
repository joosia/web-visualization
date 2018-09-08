# TTMS0400 Web-ohjelmointi
Esa-Pekka Autio, L3005@student.jamk.fi

![lol](img/kuva1.jpg)

Web-visualisointi -kurssin viikkoharjoitukset ja loppuharkka

## Harkka40 – CSS-kirjastot ja Frameworkit
### 1. Bootstrap 4  
Kirjasto sisältää helppokäyttöisen gridin lisäksi myös paljon muita ominaisuuksia kuten javascript-toiminnallisuuksia sekä valmiita tyylittelyjä.  

<b>Hyvää</b>:
+ Helppokäyttöinen grid-järjestelmä
+ Hyvät dokumentaatiot verkkosivuilla
+ Paljon erilaisia valmiita komponentteja (nav-valikko jne)
+ Sivut saa kasaan nopeasti

<b>Huonoa</b>:
- Kyseessä laaja FW, joten mukana tulee myös paljon ylimääräistä, vaikkakin Bootstrapita voi valita melko hyvin vain halutut osat käyttöön.
- BS:n CSS-määrityksiä ja JS-scriptjeä on välillä työlästä löytää edes selaimen web-kehitystyökalun avulla. Tämä hankaloittaa omien custom CSS-määritysten ja scriptien tekoja ja usein voi joutua käyttämään "rumia" korjauskeinoja, kuten CSS-tyylin yliajamista !important attribuutin avulla.
- Mikäli sivustolla on tavanomaisesta poikkea layout tai gridi, niin Bootstrap taipuu siihen melko huonosti. Tällöin nopeampaa on tehdä gridi itse.

### 2. Font-awesome  
Voitanee lukea CSS-kirjastoksi, sillä sisältää ikonipaketin lisäksi valmiita CSS-määrityksiä niiden käyttöön.  

<b>Hyvää</b>:
+ Paljon erilaisia ja hyvälaatuisia ikoneja.
+ Myös .SVG versiot perinteisen fonttiformaatin lisäksi.
+ Helppo käyttää

<b>Huonoa</b>:
- CDN toimii välillä melko hitaasti, tosin Font Awesome voidaan asentaa myös suoraan sivun palvelimelle.

### 3. Semantic UI
Ei kokemusta tästä, mutta vaikuttaa erittäin hyvältä kirjastolta web-sovelluksille. Pienemmille projekteille turhan laaja.

### 4. Foundation  
Ilmeisesti melko suosittu framework, ei omaa kokemusta tästä.

<b>Hyvää</b>:
+ Motion UI animointiin
+ Vaikuttaa todella laajalta  

<b>Huonoa</b>:
- Tuskin hyvä vaihtoehto pienempiin projekteihin
- Sen verran paljon sisältöä, että haluttuja asioita voi olla hankala löytää

### 5. Spectre
Ei kokemusta, mutta vaikuttaa kevyeltä ja eikä sisällä juuri ylimääräistä gridin ja perus UI-elementtien lisäksi. Käyttö vaikuttaa myös hyvin selkeältä ja helpolta. 