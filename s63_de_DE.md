---
layout: default_de_DE
---
# Nutzungsbedingungen für S-63 UserPermits

- Das S-63-Plugin ist nicht für Android oder iOS verfügbar.

- Wir verkaufen keine S-63 Karten, wir bieten nur den zur Lizenzierung von S-63 Karten bei Anbietern wie z.B. [Chartworld](https://www.chartworld.com/shop/off_enc) notwendigen *UserPermit* an.

- Um eine S-63 Karte von einem Anbieter zu kaufen, benötigen Sie einen UserPermit. Der S-63-Standard etabliert, dass mit OpenCPN S-63 UserPermit lizenzierte Karten nur in Verbindung mit OpenCPN verwendet werden können.

- Sie sind berechtigt, jede gekaufte Karte in 5 verschiedenen*Systemen* gleichzeitig zu verwenden, oder Sie können Sicherungskopien aufbewahren, für den Fall, dass Ihr *Hauptsystem* abstürzt. Wir generieren einen OpenCPN *InstallPermit* für jedes einzelne System. Der InstallPermit verknüpft einen S-63-Kartensatz für OpenCPN mit einem System. Verwechseln Sie OpenCPN InstallPermit nicht mit dem S-63-ZellenPermit.

- *System* bedeutet die Kombination aus Gerät und Betriebssystem. Wenn sich eines dieser Elemente ändert, wird Ihr System als neu erkannt, wobei Sie Ihre Lizenz verlieren und Ihre Sicherungskopie verwenden müssen.

- Wenn Sie Ihre Karten bereits fünfmal installiert haben, müssen Sie einen neuen UserPermit erwerben, um Karten erneut lizenzieren zu können. Da dies dann ein neuer Zyklus ist, verfügen Sie wieder über 5 Installations-Möglichkeiten (InstallPermits).

- Ihre Lizenz sollte jede Aktualisierung von OS, OpenCPN oder Plugins schadlos überstehen, aber bei einer Neuinstallierung Ihres Betriebssystem verlieren Sie Ihre Lizenz.

- Sobald Sie ein UserPermit lizenziert haben, können wir keine Rückerstattungen leisten.

- Sobald Sie einen InstallPermit für ein System erstellt haben, können wir diesen nicht mehr anulieren oder auf eine andere Gerät/Betriebssystem-Kombination übertragen.

- Überprüfen Sie Laufzeiten und Aktualisierungsmöglichkeiten bei den jeweiligen Anbietern von S-63 Karten.

# Installieren von UserPermits / InstallPermits- und S-63 Karten

![Schritte](./assets/images/s63.png)

1. *System* ist der Computer, auf dem Sie OpenCPN nutzen. Die Lizenz, die Sie von einem Anbieter für dieses System erwerben, kann nur auf diesem System verwendet werden. Laden Sie das [S-63 Plugin](https://opencpn.org/OpenCPN/plugins/s63.html) herunter und installieren es (erfordert OpenCPN 4.6 oder höḧer).
    
2. Öffnen Sie OpenCPN und aktivieren Sie das Plugin unter *Optionen → Plugins → S63*. Öffnen Sie danach *Optionen → Seekarten → S63 Karten → Schlüssel/Permits* und erstellen Sie eine Datei zur Identifikation des Systems (*Fingerprint*).
    
3. Gehen Sie auf [o-charts shop](https://o-charts.org/shop) und erwerben einen UserPermit.
    
4. Klicken Sie auf [Meine S-63 UserPermits](https://o-charts.org/shop/index.php?fc=module&module=ocpermits&controller=ocpermits) und erstellen Sie einen InstallPermit, indem Sie die zuvo erstellte Fingerprint-Datei hochladen und verknüpfen sie mit Ihrem S-63 UserPermit.
    
5. Besuchen Sie den Shop Ihres S-63-Karten-Anbieters und lizenzieren Sie alle benötigten S-63 Karten mit Ihrem OpenCPN S-63-UserPermit. Einzelne Anbieter fragen nach einer einen "HW-ID", was sie beruhigt ignorieren können.
    
6. Laden Sie Ihre S-63 Kartensätze herunter und entpacken Sie die Dateien. Sie enthalten sowohl ein Verzeichnis "ROOT_ENC" (mit den Karten-Zellen) als auch eine Datei "PERMIT.txt".
    
7. Gehen Sie in OpenCPN zu *Optionen →Karten → S63 Karten → Schlüssel/Permits*. Klicken Sie auf *Neuer UserPermit*, geben Sie Ihren UserPermit ein und testen ihn. Klicken Sie nun auf *Neuer InstallPermit*, geben Sie Ihren InstallPermit ein und testen ihn ebenfalls.
    
8. Gehen Sie in OpenCPN zu *Optionen →Karten → S63 Karten → S63 Karten*. Klicken Sie auf *Importiere Zellenfreigabe*und finden Sie die Datei PERMIT.txt in Ihren S-63-Kartensätzen. Klicken Sie auf *Importiere Karten/Updates* um den Ordner ENC_ROOT zu finden und importieren Sie Ihre S-63-Kartensätze.
    
9. OpenCPN erstellt die notwendigen eSENC-Dateien. Und schon sind Sie fertig!

# Häufig gestellte Fragen

> **Warum s-63 Karten?**
> 
> Sie sind das offizielle und aktuellste erhältliche Kartenmaterial. Die auf dem Freizeitmarkt erhältlichen Vektorkarten für Kartenplotte sind bestenfalls Derivate (auch wenn einige über zusätzliche Funktionen verfügen).
> 
> **Warum muss ich für den UserPermit zahlen?**
> 
> Wir haben sicherzustellen, daß das hier dauerhaft funktioniert und sind dem IHO gegenüber rechenschaftspflichtig. Der Aufwand wird so klein wie möglich gehalten. Wenn das Ganze wirtschaftlich gesehen ein großer Erfolg würde, gingen Überschüsse an OpenCPN zurück.
> 
> **Als wieviele Systeme zählt ein Dual-Boot-System?**
> 
> Jede HW/SW Kombination zählt als ein individuelles System und erfordert seinen eigenen InstallPermit.
> 
> **Und wenn ich die Software in einer virtuellen Maschine installiere?**
> 
> Das geht nicht. Das System darf nicht geklont werden.
> 
> **Ich musste mein OS neu installieren. Der InstallPermit ist nicht mehr gültig**
> 
> Bitte erstellen Sie einen neuen InstallPermit.
> 
> **Mein Computer ist abgestürzt. Kann ich meine Karten wiedererlangen?**
> 
> Ja, aber dies "kostet" Sie einen InstallPermit für Ihr neues System.
> 
> **Wieviel kosten S-63 Karten (und warum sind sie manchmal so teuer)?**
> 
> Der Verkaufspreis wird durch die einzelnen HOs fixiert. Ihre Kunden kommen aus der Schifffahrt-Industrie oder offiziellen Institutionen wie Regierungen, nicht vom Freizeitmarkt. Dies ist ein bekanntes Problem und der Grund, warum nur wenige aus dieser Gruppe S-63 Charts nutzen. Wir benötigen eine Menge von Lobbyarbeit, um bessere Lösungen und bessere Preise durchzusetzen. Daher würden wir Hilfe oder Unterstützung von menschen, die über die richtigen Kontakte verfügen sehr schätzen.
> 
> **Meine Lizenzdauer läuft ab. Was passiert jetzt?**
> 
> Die Karten werden nicht verschwinden, aber eine Warnung wird angezeigt.
> 
> **OpenCPN ist Open Source. Wo kann ich den Code für das Plug-in finden?**
> 
> Wir müssen sicherstellen, dass bei der Anwendung der Software keine Kopien von unverschlüsselten Zellen der oeSENC Karten zugänglich sind. Daher enthält das Plug-in einen Open-Source-Teil und eine Binärdatei, ähnlich wie bei kommerziellen BSB4 oder nv-Chart-Plug-ins.
