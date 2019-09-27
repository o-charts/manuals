---
layout: default_sv_SE
---

# Användarvillkor för oeRNC Sjökort

- oeSENC-sjökort kan bara användas med OpenCPN.

- Generellt kan du för en köpt licens installera sjökorten på två eller fler olika enheter. (Se detaljer för varje licens). Varje sådan enhetsinstallation kallar vi en "tilldelning".

- Dina tilldelningar kan alla användas samtidigt på olika enheter eller du kan spara en för framtida bruk om din "huvudenhet"/Navdator går sönder eller operativsystemet installeras om vilket gör en tidigare tilldelning obrukbar.

- *Enhet* är kombinationen av hårdvara och operativ. Om någon av dessa ändras eller byts ut ändras din "enhet" och licensen för den tilldelningen är förbrukad. Då behövs en oförbrukad tilldelning för att kunna använda din licens.

- Tilldelningen av en licens skall överleva en uppdatering av operativsystemet, OS, eller OpenCPN. Men en ominstallation av ditt OS, även på samma hårdvara, innebär en ny enhet och kommer att kräva en ny tilldelning.

- Om alla dina tilldelningar för en licens är förbrukade och du vill använda dessa sjökort på fler enheter behöver du köpa ytterligare en licens.

- En *USB nyckel-Dongel* är dock att betrakta som ett eget system. USB dongeln gör det möjligt att använda samma oeRNC-kort på flera enheter, dock inte samtidigt. Bara i den enheten, PCn, där dongeln är ansluten när OpenCPN startas kommer licensen att vara aktiv och sjökorten att visas.

- Efter att du har laddad hem dina kort till ett system kan avgiften inte återbetalas. Om du har tilldelat ett set av kort till en enhet men inte laddat hem kan återbetalning fortfarande ske.

- Efter nedladdning av sjökort till en enhet går det inte att flytta licensen till en annat enhet.

- Du kommer att kunna uppdatera dina sjökort under ett år från inköpsdatum. Sjökortsleverantörerna har olika uppdateringsperiodicitet:
    
    - Kvartalsvis: Imray Charts Eastern Caribbean, Imray Adriatic och Ionian, Imray Aegean och Mediterranean East.
    - Ej fastlagt: Explorer Charts (Bahamas).
- Dina kortlicenser upphör efter ett år från inköpsdatum. Efter förfallodatum, kommer sjökorten fortfarande att fungera på datorn men du kan inte längre ladda hem uppdateringar.

- Under det år som licensen för uppdatering löper kan du hela tiden fritt tilldela ledig(a) kopia. När licensieringsperioden är över, kan inte heller oanvända tilldelningar längre användas.

# Installation av sjökorten

Om enheten (PC/Platta/Mobil) du skall installera dina sjökort på **är ansluten till Internet** så följ instruktionerna i **Ladda hem sjökort med Internetanslutning**. Det är den lättaste och rekommenderade metoden.

Om enheten du skall installera dina sjökort på **inte är ansluten till Internet** så följ instruktionerna i **Ladda hem sjökort utan Internetanslutning**.

För att installera sjökort på en **Android** följ instruktionerna i **Ladda hem sjökort med Internetanslutning**.

## Ladda hem sjökort med Internetanslutning

1. Ladda hem och installera [oeRNC plugin](https://opencpn.org/OpenCPN/plugins/oernc.html) (För OpenCPN version 5.0 eller senare). Om du redan har oeRNC plugin installerad kontrollera att det är senaste versionen.

2. I OpenCPN, öppna *Användarinställningar → Plugins → oeRNC * och aktivera den.

3. Om du inte tidigare köpt sjökortslicens så besök [o-charts shop](https://o-charts.org/shop/14-oernc) och köp licens för de set av sjökort du är intresserad av. Om du inte redan har en inloggning så skapa en ny. Kom ihåg inloggningsdata, (mejl och lösenord) du kommer att behöva dem igen när du laddar ned sjökorten från OpenCPN. Ignorera det här steget om du redan har köpt licens för dina sjökort.

4. Om du vill tilldela sjökort till en [USB Nyckeldongel](https://o-charts.org/shop/hardware/38-usb-key-dongle.html), montera den i en USB port. Den måste anslutas innan OpenCPN startas.

5. Öppna OpenCPN *Användarinställningar → Sjökort → fliken oeRNC Sjökort* och klicka på *Uppdatera listan*. Använd piltangenterna om fliken inte syns.

6. Logga in till O-Charts webhandel med dina användardata.

7. Om du använder en dongel kan du hoppa över detta steg. Din enhet skall identifieras med ett *Enhetsnamn*. Om det är första gången denna enhet används för oeRNC kort, välj *Ny* i pop-up-fönstret och skriv ett lämpligt namn. (Minimum 3 och maximum 15 tecken, inga symboler eller mellanslag). Om denna enhet har använts för oeRNC kort tidigare välj det *Enhetsnamn* i listan som passar. Skulle du välja fel *Enhetsnamn* för denna enhet kommer korten fortfarande att installeras men kommer inte att kunna öppnas. Om du skall installera korten på en annan enhet eller ditt system har ändrats i grunden väljer du alltså *Ny* för att skapa en ny tilldelning.

8. Följ instruktionerna på skärmen för att tilldela, ladda ned och installera korten på din enhet eller dongel. När alla tillgängliga tilldelningar har använts kan ytterligare enheter inte kopplas till aktuell licens.

### Uppdatering - med internetuppkoppling

Du bör besöka *Användarinställningar → Sjökort → fliken oeRNC Sjökort* och klicka på *Uppdatera listan* från tid till annan för att se om det finns en ny uppdatering. Välj i så fall att uppdatera valda sjökort. Uppdateringar kan gälla vissa eller alla filer som ingår i ett sjökortspaket. Vid varje internetansluten uppdatering kommer endast och alltid de delar som är föråldrade att ersättas.

## Installera sjökort på en Android

Kommer snart

## Ladda hem sjökort utan Internetanslutning

På en enhet utan internetanslutning får du först skapa en system-ID fil för den enheten och kopiera den till en PC med internetanslutning där du kan tilldela och ladda ned kort avsedda för målenheten. Vi förutsätter att målenheten har senaste versionen av både OpenCPN och oeRNC_pi plugin.

1. Om du vill tilldela sjökort till en [USB Nyckeldongel](https://o-charts.org/shop/hardware/38-usb-key-dongle.html), montera den i en USB port. Den måste anslutas innan OpenCPN startas.

2. I OpenCPN, öppna *Användarinställningar → Plugins → oeRNC * och aktivera den om det inte är gjort innan.

3. Öppna *Inställningar* och klicka antingen på *Skapa en system-ID fil med USB-nyckel..* om en dongel är ansluten eller på *Skapa system-ID fil..*. En *identifieringsfil* (fingerprint) kommer att skapas och sökvägen att rapporteras. För Windows och MacOS skapas också en kopia på skrivbordet. I Linux sparas filen i ~/.opencpn folder.

4. Kopiera *Fingerprint / Id-* filen till ex. vis en Usb-sticka och anslut den till en PC med Internet.

5. Om du inte tidigare köpt sjökortslicens så besök [o-charts shop](https://o-charts.org/shop/14-oernc) och köp licens för de set av sjökort du är intresserad av. Ignorera det här steget om du redan har köpt licens för dina sjökort.

6. Gå till sidan [My oeRNC Charts](https://o-charts.org/shop/module/occharts/occhartsOernc) och skapa en *System ID* genom uppladdning av *fingeravtryck-filen* som du skapade innan och länka den till detta System-ID. Lämna *System name* tomt om du använder en Dongel.

7. Välj det nya *System identifier* för varje sjökort-set du vill tilldela din enhet eller dongeln. Väl tilldelat, kan den inte ändras.

8. Klicka på *Request*. Du kommer att får två nedladdningslänkar. En för sjökortsfilerna och en för kryperingsnyckeln för dina filer. Kopiera bägge filerna till en sticka eller annan flyttbar enhet och flytta till mål-PCn.

9. Väl på mål-PCn så packa upp sjökortsfilerna till en lämplig folder/mapp utan andra kortfiler. Därefter kopierar du nyckelfilen till samma folder där sjökortsfilerna (.oernc) nu ligger. I OpenCPN lägger du till den nya mappen precis som vanligt om det inte är gjort förut. Om det går så markera "Sök efter nya sjökort och uppdatera databasen" och "Använd". Om korten är tilldelade en Dongle glöm inte att plugga in den innan OpenCPN startas.

### Uppdatering - utan internetuppkoppling

För att kontrollera och uppdatera dina sjökort besök [My oeRNC Charts](https://o-charts.org/shop/module/occharts/occhartsOernc). Kolumnen *Edition* visar dina senaste hämtningar. Kolumnen *Current edition* visar gällande version för respektive kortset. Om de skiljer sig åt kommer en *Request*-knapp att synas. En uppdatering på detta sätt är alltid helt fristående och innehållet alla filer som behövs, oroa dig alltså inte om mellanliggande uppdateringar du kanske har missat att installera. Tag bort eller flytta de gamla filerna från mål-PCn och packa upp de nedladdade uppdateringarna till rätt mapp. Öppna OpenCPN. Gå till *Användarinställningar → Sjökort→ Sjökortsfiler*. Markera sökvägen till det gamla kortsetet och *Ta bort markerade*. Klicka på *Lägg till mapp* och välj mappen där du packat upp den senaste nedladdningen. Klicka på *Använd*.

# Vanliga frågor (FAQ)

> **Vilka enheter/operativsystem kan använda oeSENC/oeRNC plugin?**
> 
> Sjökort i oeSENC/oeRNC-format kan användas på Windows, Mac, Linux system (ARM boards som RPi) och Android.
> 
> **Och om programmet körs på virtuell enhet (Virtual Machine)?**
> 
> Det kommer inte att fungera. Vårt avtal med leverantörer hindrar kloning av system.
> 
> **Kan oeSENC/oeRNC-kort användas på iPAD/iOS?**
> 
> Nej. OpenCPN är inte tillgängligt på Apple store.
> 
> **Hur räknas en dator med sk. dual boot?**
> 
> Varje operativsystem är en enskild enhet, alltså två system.
> 
> **OpenCPN är ett fritt program. Varför måste jag betala för oeSENC/oeRNC sjökort?**
> 
> Företaget eller myndigheten som producerar sjökorten anger licensavgift och villkor. Vår hantering och dess kostnader försöker vi göra så billigt som möjligt. Om vi skulle få stor framgång ekonomiskt sett, kommer det överskottet att gå tillbaka till OpenCPN.
> 
> **OpenCPN byggs med öppen källkod. Var finns programkoden för denna plugin?**
> 
> För att kunna hantera licenser för oeSENC/oeRNC-kort måste vi garantera att det inte kan finnas tillgång till okrypterade celler när programmet kör. Därför är pluginen uppdelad i en del med öppen källkod och en enbart binär del. Precis som kommersiella BSB4 eller NV-Charts plugin.
