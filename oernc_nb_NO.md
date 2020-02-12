---
layout: default_nb_NO
---

# oeRNC Kartvilkår

- oeRNC karter kan kun benyttes i OpenCPN.

- Generelt sett så kan du installere hvert kart i din lisens på 2 systemer eller mer (se kartdetaljer). Vi kaller disse aktiverte systemene "tildeling".

- Du kan bruke enten alle dine tildelinger samtidig eller du kan ha en i bakhånd om ditt hovedsystem skulle svikte eller du må gjøre endringer i systemet som gjør at lisensen din blir ugyldig.

- *System* er kombinasjonen av maskinvare og operativsystem. Hvis en av disse faktorene skulle bli endret, da vil ditt system bli presentert som et nytt og du vil miste din lisens og vil måtte benytte din gratis tildeling.

- Din lisens skal overleve alle OS, OpenCPN eller utvidelses oppdatering, men om du re-installerer ditt OS, selv med samme OS i samme maskinvare, så vil det kreve en ny tildeling.

- Hvis du har benyttet dine 2 tildelinger og du ønsker å bruke dine kart i flere systemer, da vil du måtte kjøpe flere kartlisenser.

- En *USB-nøkkel / USB-dungle* er sett på som et system. USB-nøkkelen tillater deg i å installere kartene på så mange enheter du måtte ønske. Men, kun i den enheten som USB-nøkkelen er plugget inn i vil lisensen være aktiv og kartene vil vises.

- Når du har bedt om karter til et system, så kan vi ikke refundere kjøpet. Hvis du har opprettet og tildelt et system til dine karter, men har ikke bedt om kartene enda, da kan vi fremdeles refundere kjøpet.

- Når du har etterspurt dine kart for et system så kan vi ikke avbryte eller flytte dine kart til en annen maskinvare/OS kombinasjon.

- Du vil kunne oppdatere dine kart i et år fra kjøps dato. Kartene har forskjellige oppdaterings tidspunkter:
    
    - Kvartalsvis: Imray karter for Øst-Karibien, Imray karter for Adriater og Joniske øyer, Imray karter for Egeerhavet og Middelhavet øst.
    - Ubestemt: Explorer karter (Bahamas).
- Dine karter utløper ett år fra kjøpsdatoen. Kartene vil fungere på systemet ditt etter utløpsdatoen, men du kan ikke be om flere oppdateringer til dem.

- I ett års perioden kan du tildele dine karter til hvilket som helst system. Etter at lisensierings perioden er over, så kan ingen nye system legges til.

# Installere karter

Hvis systemet du ønsker å installere kartene dine på **er tilkoblet Internett**, følg trinnene i **Hent kartene på nett**. Dette er den enkleste og anbefalte metoden.

Hvis systemet du ønsker å installere kartene dine på **IKKE er tilkoblet Internett** følg trinnene i **Hent kartene uten nett**.

For å installere karter på **Android** følg stegene i **Skaff karter for Android**.

## Hent kartene på nett

1. Download and install the [oeRNC plugin](https://opencpn.org/OpenCPN/plugins/oernc.html) (only for OpenCPN 5.0 version and above). If you have already the oeRNC plugin installed, update to the latest version.

2. Go to OpenCPN, *Options → Plugins → oeRNC* and enable it.

3. Go to [o-charts shop](https://o-charts.org/shop/14-oernc) and license the chart sets you are interested in. Remember your access data to o-charts shop (email and password), you will need them later. Ignore this step if you have already bought your charts.

4. If you want to assign your charts to a [USB Key Dongle](https://o-charts.org/shop/hardware/38-usb-key-dongle.html), plug it into a USB port now. Ignore this step if you do not have a dongle.

5. Go to OpenCPN, *Options → Charts → oeRNC charts* tab and press *Refresh Chart List*. Use the arrows to show the hidden tabs.

6. Login with your o-charts shop access data.

7. If you are using a USB Dongle ignore this step. First you will need to identify your system with a *System Name*. If you install oeRNC charts the first time on this system, select *New* in the window that will pop-up and provide a name (3 characters minimum and 15 maximum, no symbols or spaces). If the system has been used already, select the *System Name* that corresponds to it from the list. In case you select a wrong *System Name*, the install of the charts may proceed but they will reject to work. If you are installing your chart in a second system or you have reinstalled your OS then select *New* to create a new assignment.

8. Follow on screen instructions to assign, download and install to your system or dongle the charts sets you licensed on the o-charts shop. Once you have consumed all your allowed assigments, the chart will not be available.

### Oppdateringer - på nett

You should visit *Options → Charts → oeRNC charts* from time to time to see if a new update is available. Online updates are incremental but do not worry, oeRNC plugin will do all the job and will download all the intermediate updates you might have missed to install.

## Skaff karter for Android

1. Install latest version of [OpenCPN app for Android 4.4 (or above)](https://play.google.com/store/apps/details?id=org.opencpn.opencpn) from the Play Store. Be sure you are using the official OpenCPN app.

2. Install [oeRNC plugin for OpenCPN app](https://play.google.com/store/apps/details?id=org.opencpn.oerncplugin) from the Play Store. Open oeRNC plugin app and click on "Install Plugin oeRNC".

3. Go to [o-charts shop](https://o-charts.org/shop/14-oernc) and license the chart sets you are interested in. Ignore this step if you have already bought your charts. Remember your access data to o-charts shop (email and password), you will need them later.

4. Go to OpenCPN, *Options → Charts → oeRNC charts* tab and press *Refresh Chart List*. Use the arrows to show the hidden tabs.

5. Login with your o-charts shop access data email and password.

6. Follow on screen instructions to assign, download and install to your device the charts sets you licensed on the o-charts shop. You should come back here from time to time to see if a new update is available


## Hent karter uten nett

For systems without Internet connection you will create a system identifier file to take it to another computer with Internet access and request and download the chart set for the target system. We assume that you have installed the latest versions of OpenCPN and oeRNC plugin in the target system.

1. If you want to assign your charts to a [USB Key Dongle](https://o-charts.org/shop/hardware/38-usb-key-dongle.html), plug it into a USB port now. Ignore this step if you do not have a dongle.

2. Go to OpenCPN, *Options → Plugins → oeRNC Charts* and enable it.

3. Enter into *Preferences* and click either on *Create USB Key Dongle System ID file...* if you have a dongle or on *Create System Identifier file...* if you do not have a dongle. The plugin will report the path to a *Fingerprint* file. For Windows and macOS systems a copy is created directly on the desktop. For Linux systems the file is created in ~/.opencpn folder.

4. Copy the *Fingerprint* file onto some portable device and look for a computer with an internet connection.

5. Go to the [o-charts shop](https://o-charts.org/shop/14-oernc) and license the oeRNC chart sets you are interested in. Ignore this step if you have already bought your charts.

6. Go to the [My oeRNC Charts](https://o-charts.org/shop/module/occharts/occhartsOernc) page and create a *System identifier* uploading the *Fingerprint*. Leave *System name* blank if you are using a dongle.

7. Select the new *System identifier* for each chart set you want to assign to your system. Once assigned, it can not be changed.

8. Make a Request clicking the button *Request*. After few seconds you will get 2 download links, one for the charts and another one for the file containing the keys to decrypt them. Copy both files onto the portable device and go back to the boat.

9. On your target system unzip the charts file into a directory of your choice and copy the keys file into the same folder where the unzipped charts are (.oernc). Install your charts as always and you are done. If you have assigned your charts to a dongle, plug it in before to see the charts.

### Oppdateringer - uten nett

To update your chart sets go to [My oeRNC Charts](https://o-charts.org/shop/module/occharts/occhartsOernc) page. Column *Edition* will show the last edition you requested. Column *Current edition* will show the current available edition for that chart set. If they do not match, a *Request* button will appear. Offline updates are self contained, do not worry about intermediate updates you might have missed to install. Remove the old chart set from OpenCPN or keep it in different directory and install the new one as usual.

# Ofte stilte spørsmål

> **Hva OS er oeSENC/oeRNC utvidelsene klar for?**
> 
> oeSENC/oeRNC karter vil fungere med Windows, Mac, Android og Linux systemer (inkludert ARM korter).
> 
> **Og hvis jeg installerer programvaren på en Virtuell Maskin?**
> 
> Da vil den ikke fungere. Vi må forhindre at systemene blir klonet.
> 
> **Kan jeg bruke oeSENC/oeRNC karter på iOS?**
> 
> Nei. Det er ingen versjon av OpenCPN for iOS.
> 
> **Hvor mange systemer teller et dual boot system?**
> 
> Hver maskinvare/OS kombinasjon teller som et system.
> 
> **Hvorfor må jeg betale for oeSENC/oeRNC karter?**
> 
> Vi må drifte denne organisasjonen og svare for kart lisensholdernes avgifter og krav. Strukturen og kostnader holdes til et minimum. Om vi skulle få stor suksess økonomisk sett, da vil overskudd gå tilbake til OpenCPN.
> 
> **OpenCPN er åpen kilde. Hvor er koden for utvidelsene?**
> 
> For å jobbe med oeSENC/oeRNC karter så må vi påse at ingen kopier av de ukrypterte kartcellene er tilgjengelige ved kjøring av programvaren. Derfor har utvidelsen en åpen-kilde del og en binær del. Til sammenligning med kommersielle BSB4 eller nv-kart utvidelsene.
