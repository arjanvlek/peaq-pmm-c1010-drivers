Op deze site kun je de drivers voor de Peaq PMM C1010 kosteloos downloaden. Handig, wanneer je bijvoorbeeld Windows opnieuw wilt installeren. Of wanneer er na een update van Windows iets het niet meer doet.

![Peaq PMM C1010](peaq-laptop.jpeg)
*Peaq PMM C1010*

Hieronder staan de links naar de installatiebestanden van de drivers. Deze kun je direct vanaf deze site downloaden (originele links van Peaq zijn er niet meer). Vervolgens moet je ze alleen nog even installeren. Hoe? Dat lees je verderop.

# Download de drivers

## Chipset
Een basisdriver waarmee o.a. de helderheid van het scherm geregeld kan worden. Installatie via Setup (2x)

[Download](https://storage.googleapis.com/peaq-pmm-c1010-drivers/01_Chipset.zip)

## Wi-Fi: 
Drivers voor draadloos netwerk. Installatie via Setup. Meestal zijn deze al vanzelf geïnstalleerd en heb je deze dus niet nodig.

*Download niet beschikbaar. Het bestand is helaas beschadigd geraakt en kan niet meer worden gebruikt.*

## Bluetooth

Drivers voor de Bluetooth. Installatie via Setup.
Meestal zijn deze al vanzelf geïnstalleerd en heb je deze dus niet nodig.

[Download](https://storage.googleapis.com/peaq-pmm-c1010-drivers/03_Bluetooth.zip)

## Realtek

Software voor het regelen van het geluid. Installatie via Apparaatbeheer

[Download](https://storage.googleapis.com/peaq-pmm-c1010-drivers/04_Realtek.zip)

## Audio

Drivers voor de geluidskaart. Installatie via Apparaatbeheer

[Download](https://storage.googleapis.com/peaq-pmm-c1010-drivers/05_Audio.zip)

## Dolby

Drivers voor Dolby Digital-geluidseffecten. Installatie via Setup (deel 1) en Batchbestand (deel 2)

[Download](https://storage.googleapis.com/peaq-pmm-c1010-drivers/06_Dolby.zip)

## Camera’s

Drivers voor de camera’s van de 2-in-1. Installatie via Batchbestand of Apparaatbeheer

[Download](https://storage.googleapis.com/peaq-pmm-c1010-drivers/07_Camera.zip)

## Geheugenkaartlezer

Drivers voor de geheugenkaartlezers (zowel tablet als dock). Installatie via Setup.

[Download](https://storage.googleapis.com/peaq-pmm-c1010-drivers/08_Cardreader.zip)

## G-Sensor

Driver voor het automatisch draaien van het scherm bij het kantelen van de tablet. Installatie via autorun-bestand.

[Download](https://storage.googleapis.com/peaq-pmm-c1010-drivers/09_G-Sensor.zip)

## Dolby On-Screen Display

Driver voor wisselen van Dolby-stand bij drukken op het knopje aan de zijkant van het apparaat (toont dan een pop-up). Installatie via Setup

[Download](https://storage.googleapis.com/peaq-pmm-c1010-drivers/10_OSD.zip)

## Trackpad

Driver voor het muispad / trackpad. Installatie via Setup

[Download](https://storage.googleapis.com/peaq-pmm-c1010-drivers/Touchpad-driver.zip)

## Trackpad – alternatief

Gebruik deze wanneer de eerste trackpad-driver niet werkt. Installatie via Setup.

[Download](https://storage.googleapis.com/peaq-pmm-c1010-drivers/11_Touchpad.zip)

## Continuum Mode
Driver voor automatisch wisselen tussen tablet en laptopmodus van Windows. Uniek op deze website! Vereist aangepaste installatie (zie hieronder).!

[Download](https://storage.googleapis.com/peaq-pmm-c1010-drivers/ContinuumMode-driver.zip)

# Installeren van de drivers

Hoe je de drivers moet installeren, verschilt per driver. Er zijn ruwweg drie categorieën drivers, waarvoor de instructies hieronder staan. Het kan wel zo zijn dat de naamgeving van de configuratie-schermen net iets anders is. Deze wil per Windows 10-versie nog wel eens verschillen. De drie types zijn:

- Installatie via setup
- Installatie via batchbestand
- Installatie via apparaatbeheer.

## Installatie via setup
De drivers waarbij “Installatie via Setup” staat, kun je installeren door ze uit te pakken en dan op setup.exe te klikken. De mappenstructuur wijst erop in welke volgorde je eventuele sub-onderdelen moet installeren.

## Installatie via batchbestand
De drivers waarbij “Installatie via batchbestand” staat, kun je installeren door dubbel op het batchbestand te klikken.

## Installatie via Apparaatbeheer
De drivers waarbij “Installatie via Apparaatbeheer” staat, kun je als volgt installeren:

- Open Apparaatbeheer (rechts-klikken op het Start-icoon)
- Ga naar het apparaat wat met een geel uitroepteken staat (vb geluid: High definition audio codec staat geel).
- Klik hier rechts op en kies “Stuurprogramma bijwerken”
- Selecteer in de wizard “Op mijn computer naar een stuurprogramma zoeken”
- Kies vervolgens “Ik wil kiezen uit een lijst met stuurprogramma’s op mijn computer
- Kies “Bladeren” en ga naar de gedownloade map
- Selecteer het bestand (inf-bestand) wat als enige wordt getoond.
- De installatie wijst zichzelf

## Installatie van de Continuum Mode drivers (uitzondering)

De continuum mode drivers moet je in `c:\program files` zetten, waardoor deze in de map `C:\Program Files\OEM\ContinuumMode` komen te staan. Dit kan door ze met de Verkenner te kopiëren.
Vervolgens moet je een snelkoppeling in de map “Opstarten” van het startmenu zetten
Deze moet wijzen naar: `C:\Program Files\OEM\ContinuumMode\APPServ.exe`


Ik hoop dat deze site je heeft geholpen om jouw Peaq C1010 weer werkend te krijgen! 

Arjan
