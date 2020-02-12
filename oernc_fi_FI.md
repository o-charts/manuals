---
layout: default_fi_FI
---

# oeRNC-karttojen ehdot

- oeRNC-karttoja voi käyttää vain OpenCPN:ssä.

- Voit asentaa kunkin lisensoimasi karttasarjan kahteen tai useampaan järjestelmään (tarkista karttasarjan lisätiedot). Näitä kutsutaan järjestelmän "liitoksiksi".

- Voit tehdä kaikki liittoksesi heti tai säilyttää toisen siltä varalta että järjestelmäsi tuhoutuu tai tekemäsi järjestelmämuutokset aiheuttavat lisenssisi peruuntumisen.

- *Järjestelmä* on käyttöjärjestelmän ja laitteen kombinaatio. Jos jokin näistä muuttuu, järjestelmä tulkitaan uudeksi ja tarvitset siihen uuden liitoksen.

- Lisenssisi pitäisi pysyä voimassa käyttöjärjestelmän, OpenCPN:n tai lisäosien päivityksissä. Jos asennat käyttöjärjestelmäsi uudelleen samaan koneeseen, tarvitset uuden liitoksen.

- Kun olet käyttänyt kaikki liitoksesi ja haluat asentaa karttasarjasi uuteen järjestelmään, joudut hankkimaan karttasarjalle uuden lisenssin.

- *USB-avain* tulkitaan yhdeksi järjestelmäksi. USB-avain sallii karttasarjonen asentamisen niin moneen järjestelmään kuin haluat. Kartat toimivat kuitenkin vain siinä järjestelmässä, mihin USB-avain on liitetty.

- Kun olet tehnyt karttasarjallesi latauspyynnön (request) jollekin järjestelmälle, emme voi enää palauttaa rahojasi. Jos olet luonut järjestelmän ja liittänyt karttasarjasi siihen, mutta et ole tehnyt karttasarjallesi yhtään latauspyyntöä, voimme vielä palauttaa rahasi.

- Kun olet liittänyt karttasarjasi johonkin järjestelmään, emme voi peruuttaa liitosta tai siirtää sitä toiseen järjestelmään.

- Voit päivittää karttasarjasi vuoden ostopäivästä. Karttasarjoilla on vaihtelevat päivitysvälit:
    
    - Neljännesvuosittain: Imray Charts Eastern Caribbean, Imray Adriatic and Ionian, Imray Aegean and Mediterranean East.
    - Vaihtelevasti: Explorer Charts (Bahamas).
- Karttasarjasi päivitysoikeus päättyy vuoden kuluttua ostopäivästä. Päivitysoikeuden päättymisen jälkeen karttasarjasi toimivat edelleen järjestelmässäsi, mutta et voi enää päivittää niitä.

- Voit liittää karttasarjasi vuoden päivitysoikeuden aikana rinnakkaiseen tai varmuuskopiojärjestelmään. Vuoden päivitysoikeuden päätyttyä et voi enää liittää karttasarjaasi toiseen järjestelmään.

# Karttojen asennus

Jos järjestelmä, johon haluat asentaa kartat, **on kytketty verkkoon**, seuraa vaiheita **Hae kartat verkosta**. Tämä on yksinkertaisin ja suositeltavin menetelmä.

Jos järjestelmä, johon haluat asentaa kartat, **ei ole kytketty verkkoon**, seuraa vaiheita **Asenna kartat ilman verkkoa**.

Asentaaksesi kartat **Androidiin** seuraa ohjeita **Asenna kartat Androidiin**.

## Hae kartat verkosta

1. Lataa ja asenna [oeRNC-lisäosa](https://opencpn.org/OpenCPN/plugins/oernc.html) (OpenCPN 5.0 tai uudemmat versiot). Jos sinulla on jo oeRNC-lisäosa asennettuna, päivitä se uusimpaan versioon.

2. OpenCPN:ssä valitse: Asetukset → Lisäosat → oeRNC ja ota se käyttöön valitsemalla "Käytä".

3. Siirry [o-charts -kauppaan](https://o-charts.org/shop/14-oernc) ja osta lisenssi sille karttasarjalle, jota haluat käyttää. Tallenna kirjautumistietosi o-charts -kauppaan (sähköpostiosoite ja salasana), tarvitset niitä myöhemmin. Ohita tämä vaihe, jos olet jo ostanut karttasarjasi.

4. Jos haluat liittää karttasarjasi [USB-avaimeen](https://o-charts.org/shop/hardware/38-usb-key-dongle.html), liitä se laitteesi USB-porttiin. Ohita tämä vaihe, jos et käytä USB-avainta.

5. OpenCPN:ssä valitse: Asetukset → Kartat → oeRNC-kartat ja paina "Päivitä luettelo". Käytä nuolinäppäimiä nähdäksesi piilotetut välilehdet.

6. Kirjaudu käyttämällä o-charts -kaupan kirjautumistietoja.

7. Ohita tämä vaihe, jos käytät USB-avainta. Aluksi sinun täytyy yksilöidä järjestelmäsi *järjestelmänimellä*. Jos asennat oeRNC-karttoja ensimmäistä kertaa valitse *Uusi* popup-ikkunasta ja anna järjestelmänimi (vähintään 3 ja enintään 15 merkkiä, ei erikoismerrkejä tai välilyöntejä). Järjestelmänimenä voit käyttää esim. aluksesi nimeä. Jos olet jo luonut järjestelmänimen tälle järjestelmälle, valitse *Järjestelmänimi* luettelosta. Jos valitset väärän *Järjestelmänimen*, asennus saattaa onnistua, mutta kartat eivät toimi. Jos asennat karttoja toiseen järjestelmään tai olet asentanut käyttöjärjestelmäsi uudelleen, valitse *Uusi* ja luo uusi järjestelmänimi.

8. Seuraa ruudulle tulevia ohjeita liittäksesi, ladataksesi ja asentaaksesi o-charts -kaupasta ostamasi karttasarjat. Kun olet käyttänyt kaikki sallitut liitoksesi, karttasarja ei enää ole saatavilla.

### Päivitykset verkossa

Käy silloin tällöin *Asetukset → Kartat → oeRNC-kartat* ja tarkista onko karttasarjoillesi päivityksiä. oeRNC-lisäosa huolehtii kaikista mahdollisista lataamatta jääneistä välipäivityksistä automaattisesti.

## Asenna kartat Androidiin

1. Asenna uusin [OpenCPN app for Android 4.4 (or above)](https://play.google.com/store/apps/details?id=org.opencpn.opencpn) versio Play Store:sta. Varmista että käytät virallista OpenCPN appia.

2. Asenna [oeRNC plugin for OpenCPN app](https://play.google.com/store/apps/details?id=org.opencpn.oerncplugin) Play Store:sta. Avaa oeRNC-plugin äppi ja klikkaa "Asenna oeRNC-lisäosa".

3. Mene [o-charts -kauppaan](https://o-charts.org/shop/14-oernc) ja hankin lisenssit karttasarjoille, joita haluat käyttää. Ohita tämä vaihe, jos olet jo ostanut karttasarjasi. Tallenna kirjautumistietosi o-charts -kauppaan (sähköpostiosoite ja salasana), tarvitset niitä myöhemmin.

4. Siirry OpenCPN, *Optiot→ kartat → oeRNC* kartat välilehti ja paina *Päivitä karttaluettelo*. Käytä nuolinäppäimiä nähdäksesi piilotetut välilehdet.

5. Kirjaudu 3. kohdassa tallentamillasi o-charts kirjautumistiedoillasi.

6. Seuraa ruudulle tulevia ohjeita liittäksesi, ladataksesi ja asentaaksesi o-charts -kaupasta ostamasi karttasarjat. Käy silloin tällöin tällä välilehdellä tarkistamassa onko karttasarjoillesi saatavissa päivityksiä.

## Asenna kartat ilman verkkoa

Järjestelmissä, joissa ei ole internetyhteyttä, sinun täytyy luoda sille sormenjälkitiedosto ja ottaa se mukaan siirrettävällä medialla (esim. USB-tikulla) koneelle, jossa on internetyhteys. Internetyhteydellä voit tehdä karttasarjallesi latauspyynnön ja ladata ne USB-tikulle, mistä siirrät ne edelleen järjestelmääsi. Tarkistathan että sinulla on uusimmat versiot OpenCPN:stä ja oeRNC-lisäosasta asennettuna.

1. Jos haluat liittää karttasarjasi [USB-avaimeen](https://o-charts.org/shop/hardware/38-usb-key-dongle.html), liitä se laitteesi USB-porttiin. Ohita tämä vaihe, jos et käytä USB-avainta.

2. OpenCPN:ssä valitse: Asetukset → Lisäosat → oeRNC ja ota se käyttöön valitsemalla "Käytä".

3. Valitse *Ominaisuudet* ja klikkaa joko *Luo USB-avaimen järjestelmän tunnistetiedosto...*, jos käytät USB-avainta tai *Luo järjestelmän tunnistetiedosto...*, jos et käytä USB-avainta tässä järjestelmässä. Lisäosa näyttää polun *järjestelmäntunnistetiedostoon*. Windows- ja Mac-järjestelmissä tiedostosta luodaan kopio myös työpöydälle. Linux-järjestelmissä tiedosto luodaan hakemistoon ~/.opencpn.

4. Kopioi järjestelmäsi *Sormenjälkitiedosto* esim. USB-tikulle ja siirry koneelle, jossa on internetyhteys.

5. Siirry [o-charts -kauppaan](https://o-charts.org/shop/14-oernc) ja osta lisenssi sille karttasarjalle, jota haluat käyttää. Ohita tämä vaihe, jos olet jo ostanut karttasarjasi.

6. Mene [My oeRNC Charts](https://o-charts.org/shop/module/occharts/occhartsOernc) sivulle ja luo *System identifier* lataamalla *järjestelmäntunnistetiedosto*. Jätä *System name* tyhjäksi, jos käytät USB-avainta.

7. Valitse luotu *Järjestelmän tunniste* kullekin karttasarjalle, jonka haluat liittää järjestelmääsi. Kun karttasarja on liitetty, liitosta ei voi muuttaa.

8. Tee latauspyyntö klikkaamalla painiketta *Request*. Saat jonkin ajan kuluttua kaksi latauslinkkiä -yhden karttasarjaa ja toisen tiedostoon, joka sisältään karttasarjan salausavaimet. Kopioi molemmat tiedostot esim. USB-tikulle ja siirrä ne varsinaiseen järjestelmääsi.

9. Pura varsinaisessa järjestelmässäsi karttasarja haluamaasi hakemistoon ja kopioi salausavaimet sisältävä tiedosto samaan hakemistoon. Asenna karttasarja normaalisti. Jos olet liittänyt karttasarjasi USB-avaimeen, liitä se järjestelmääsi, jotta kartat toimivat.

### Päivitykset ilman verkkoa

Päivittääksesi karttasarjasi mene [My oeRNC Charts](https://o-charts.org/shop/module/occharts/occhartsOernc) sivulle. Sarake *Edition* näyttää viimeisimmän lataamasi version. Sarake *Current edition* näyttää karttasarjasi uusimman saatavissa olevan version. *Request* tulee näkyviin, jos karttasarjastasi on saatavilla uudempi kuin ladattu versio. Päivitykset ovat täydellisiä eikä sinun tarvitse huolehtia välipäivityksistä, jotka ovat jääneet huomaamatta. Poista vanha karttasarja OpenCPN:stä tai pidä se eri hakemistossa ja asenna uusi kuten edellä.

# Usein kysyttyjä kysymyksiä

> **Mihin käyttöjärjestelmiin oeSENC- ja oeRNC-lisäosat on saatavana?**
> 
> oeSENC- ja oeRNC-lisäosat ja -kartat toimivat Windows-, Mac- Android- ja Linux-järjestelmissä (myös ARM-korteilla)
> 
> **Entä jos asennan ohjelman virtuaalikoneeseen?**
> 
> Se ei toimi. Olemme estäneet järjestelmän kloonaamiselta.
> 
> **Voinko käyttää oeSENC- tai oeRNC-karttoja iOS-laitteissa?**
> 
> Et. OpenCPN:ää ei ole saatavana iOS-laitteille.
> 
> **Kuinka moneksi järjestelmäksi "dual boot"-järjestelmä lasketaan?**
> 
> Kukin hw/sw-yhdistelmä on yksi järjestelmä.
> 
> **Miksi minun täytyy maksaa oeSENC- tai oeRNC-kartoista?**
> 
> Joudumme ylläpitämään järjestelmää ja vastaamaan karttojen lisensoijille maksuista ja ehdoista. Kulut pyritään pitämään mahdollisimman alhaisina. Jos alamme tuotamaan voittoa, suorituksia palautetaan OpenCPN:lle.
> 
> **OpenCPN on avoimen lähdekoodin sovellus. Missä on lisäosan lähdekoodit?**
> 
> oeSENC- tai oeRNC-karttoja käytettäessä joudumme varmistamaan että salaamattomista karttasoluista ei ole kopioita ohjelman suorituksen aikana. Tämän vuoksi lisäosa koostuu avoimesta lähdekoodista ja binääriosasta. Vastaavia ovat kaupalliset BSB4- tai nv-chart -lisäosat.
