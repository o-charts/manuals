---
layout: default_fi_FI
---

# S-63 -käyttäjäluvan (UserPermit) ehdot

- S-63 -lisäosa ei ole saatavana Androidiin eikä iOS:ään.

- Emme myy S-63 karttoja. Tarjoamme vain S-63 *-käyttäjälupaa*, joka vaaditaan S-63 -karttojen lisensoimiseksi jälleenmyyjiltä, kuten [Chartworld](https://www.chartworld.com/shop/off_enc).

- Tarvitset käyttäjäluvan ostaaksesi S-63 -karttoja miltä tahansa jälleenmyyjältä. OpenCPN S-63 -käyttäjäluvalla lisensoituja karttoja voidaan käyttää vain OpenCPN:n kanssa, kuten S-63 standardi vaatii.

- Voit käyttää hankkimiasi karttoja 5 *järjestelmässä* yhtäaikaa tai voit säästää oikeuksia siltä varalta että järjestelmäsi lakkaa toimimasta. Generoimme OpenCPN:ään S-63 -asennusluvan (InstallPermit) jokaiselle järjestelmälle erikseen. Asennuslupa liittää S-63 -kartat tiettyyn OpenCPN -järjestelmään. Älä sekoita OpenCPN S-63 -asennuslupaa ja S-63 -solulupaa (cell permit) keskenään.

- *Järjestelmä* tarkoittaa tietokoneen ja käyttöjärjestelmän yhdistelmää. Jos jokin näistä muuttuu, järjestelmä tulkitaan uudeksi, menetät käyttöoikeuden ja sinun täytyy luoda uusi asennuslupa.

- Jos olet jo käyttänyt kaikki 5 asennuslupaa, sinun täytyy ostaa uusi käyttäjälupa ja lisensoida kartat uudelle käyttäjäluvalle. Uudella käyttäjäluvalla voit jälleen luoda 5 asennuslupaa.

- Asennusluvan pitäisi säilyä OS, OpenCPN tai lisäosan päivityksessä, mutta jos asennat käyttöjärjestelmän uudelleen menetät asennusluvan.

- Kun olet lisensoinut käyttäjäluvan, emme voi palauttaa rahojasi.

- Kun olet luonut asennusluvan yhdelle järjestelmälle, emme voi peruuttaa tai siirtää sitä toiseen järjestelmään.

- Tarkista S-63 -karttojen toimittajalta päivitysten ja vanhenemisen ehdot.

# Käyttäjäluvan, asennusluvan ja S-63 -karttojen asentaminen.

![steps](./assets/images/s63.png)

1. *Järjestelmä* tarkoittaa konetta, jossa käytät OpenCPN:ää. VAR:lta (S-63 chart Value Added Reseller = hyväksytty jälleenmyyjä) tiettyyn järjestelmään lisensoidut kartat toimivat ainoastaan siinä. Lataa ja asenna [S-63 -lisäosa](https://opencpn.org/OpenCPN/plugins/s63.html) (vain OpenCPN 4.6 ja uudemmat versiot).
    
    1. OpenCPN:ssä valitse: *Asetukset → Lisäosat → S63* ja ota se käyttöön valitsemalla "Käytä". Valitse OpenCPN:ssä seuraavaksi: *Asetukset → Kartat→ S63 -kartat→ Avaimet/luvat* välilehti ja klikkaa "Luo järjestelmän tunnistetiedosto...".
    
    2. Mene [o-charts -kauppaan](https://o-charts.org/shop) ja osta käyttäjälupa (UserPermit).
    
    3. Mene [My S-63 UserPermits](https://o-charts.org/shop/index.php?fc=module&module=ocpermits&controller=ocpermits) sivulle ja luo asennuslupa (InstallPermit) lataamalla edellä luomasi järjestelmäntunnistetiedosto ja liittämällä se ostamaasi S-63 -käyttäjälupaan.
    
    4. Mene valitsemasi VAR:n verkkokauppaan ja lisensoi tarvitsemasi S-63 -kartat käyttämällä ostamaasi OpenCPN S-63 -käyttäjälupaa. Jos VAR pyytää sinulta "HW-ID":tä, voit ohittaa kysymyksen.
    
    5. Lataa ja pura ostamasi S-63 -karttatiedostot valitsemaasi hakemistoon (esim. C:\Kartat\S63). Tiedostojen pitäisi sisältää hakemisto ROOT-ENC, joka sisältää karttasolut sekä PERMIT.txt tiedoston ja soluluvat.
    
    6. OpenCPN:ssä valitse: *Asetukset → Kartat→ S63 -kartat→ Avaimet/luvat* välilehti. Klikkaa *Uusi käyttäjälupa...* -painiketta ja syötä ostamasi käyttäjälupa. Klikkaa *Uusi asennuslupa...* -painiketta ja syötä luomasi asennuslupa.
    
    7. OpenCPN:ssä valitse: *Asetukset → Kartat→ S63 -kartat→ karttasolut* välilehti. Asenna soluluvat klikkaamalla *Tuo soluluvat...* -painiketta ja valitse Permit.txt tiedosto hakemistosta, minne purit ostamasi kartat. Lisää OpenCPN:ään S63 -kartat klikkaamalla *Tuo kartat/päivitykset...* -painiketta ja valitsemalla ENC_ROOT hakemisto.
    
    8. OpenCPN luo tarvittavat eSENC tiedostot, minkä jälkeen kartat ovat käytettävissä.

# Usein kysyttyjä kysymyksiä

> **Miksi S-63 -karttoja?**
> 
> S-63 -kartat ovat virallisia ja yleisesti parhaiten päivitettyjä karttoja. Huviveneilymarkkinoilla tarjolla olevien karttaplottereiden vektorikartat ovat näiden johdannaisia (jotkut saattavat sisältää joitain lisäominaisuuksia).
> 
> **Miksi minun täytyy maksaa käyttäjäluvasta (UserPermit)?**
> 
> Joudumme ylläpitämään järjestelmää ja vastaamaan IHO:lle pysyvästä kulusta. Kulut pyritään pitämään mahdollisimman alhaisina. Jos alamme tuotamaan voittoa, suorituksia palautetaan OpenCPN:lle.
> 
> **Kuinka moneksi järjestelmäksi "dual boot"-järjestelmä lasketaan?**
> 
> Kukin hw/sw-yhdistelmä on yksi järjestelmä ja vaatii oman asennusluvan (InstallPermit).
> 
> **Entä jos asennan ohjelman virtuaalikoneeseen?**
> 
> Se ei toimi. Olemme estäneet järjestelmän kloonaamiselta.
> 
> **Jouduin asentamaan käyttöjärjestelmäni uudelleen. Nyt asennuslupa ei ole enää voimassa.**
> 
> Luo uusi asennuslupa.
> 
> **PC:ni lakkasi toimimasta. Voinko asentaa karttani uuteen koneeseen?**
> 
> Kyllä, ja tässä tapauksessa se "maksaa" sinulle asennusluvan uuteen koneeseesi.
> 
> **Mitä S-63 -kartat maksavat (ja miksi ne ovat joskus todella kalliita)?**
> 
> Paikalliset HO:t ovat määritelleet karttojen vähittäismyyntihinnan. Heidän asiakkaitaan ovat kuljetusteollisuus ja viralliset tahot kuten hallinto - ei vapaa-ajan markkinat. Em. syistä harvat huviveneilijät käyttävät S-63 -karttoja. Meidän täytyy tehdä paljon lobbausta saadaksemme paremmat ratkaisut ja halvemmat hinnat. Apu henkilöiltä, joilla on sopivat kontaktit, on tervetullutta.
> 
> **Tilapäinen lisenssini vanhenee. Mitä sitten tapahtuu?**
> 
> Kartat eivät katoa, mutta näytölle ilmestyy varoitus vanhentuneista kartoista.
> 
> **OpenCPN on avoimen lähdekoodin sovellus. Missä on lisäosan lähdekoodit?**
> 
> S-63 -karttoja käytettäessä joudumme varmistamaan että salaamattomista karttasoluista ei ole kopioita ohjelman suorituksen aikana. Tämän vuoksi lisäosa koostuu avoimesta lähdekoodista ja binääriosasta. Vastaavia ovat kaupalliset BSB4- tai nv-chart -lisäosat.
