# Abschlusspräsentation 

![](assets/images/02_png_background/CowTracking-DAT-Projekt.png)

Note:

Zur Wiederholung -  was ist Cowtracking?

---

### Cowtracking?
![](https://media.giphy.com/media/h55EUEsTG9224/giphy.gif)

Note:

Bauer sucht Kuh.  
Cowtracking ist die Lösung.

---

## Agenda

@ul
- Rückblick: Beginn und Zwischenpräsentation
- Verlauf und Stand
- Demo
- Fragen
@ulend

Note:

Anforderungen, MVP, Feedback Zwischenpräsi  
Für Device, Server, WebInterface, Tests  
(live-)Demo  
Zeit -> Fragen am Schluss

---

## Anforderungen

+++

### [Überschrift Folie 1]
[ Text ]  
[Wenn Bild: Hier einfügen oder Link reinschreiben]

Note:

[unsichtbare Notizzeile 1]  
[unsichtbare Notizzeile 2]

---

### [Überschrift Folie 2]

@ul
- [Listenpunkt 1]
- [der hier kommt erst nach weiterklicken]
- [der noch eins danach usw...]
@ulend

---

[Folie 3]
...

---

### Anforderungen
@ul
- Device
- LoRa
- Standorte anzeigen
@ulend

Note:

Gerät an Kuh  
LoRa für comm Device<->Infra
Standorte für Landwirt

---

### Minimum Viable Produkt

+++

### MVP
@ul
- Device: GNSS, LoRa
- über Brocaar...
- an Server...
- in Datenbank...
- auf Webseite!
@ulend

Note:

Dev: ergonomie, auto-send, akku  
Srv: in DB, an Front, in cloud  
DB: persistent  
Front: Darstellen, mobil+Desktop

---

## Komponenten

---

## CowTrackingDevice

![](assets/images/02_png_background/CowTracking-Device.png)

+++

Folie 1

Note:

Notizzeile 1  
2

---

## CowTrackingServer

### CowTrackingServer
![](assets/images/02_png_background/CowTracking-Server.png)

+++

### CowTrackingServer
![](assets/images/server_01.png)

+++

@snap[north]
### Cloud
@snapend

@snap[west sidebar]
![](assets/images/server_02_west.png)
@snapend

@snap[east sidebar]
![](assets/images/server_02_east.png)
@snapend


@snap[south]
![](assets/images/server_02_south.png)
@snapend

+++

@snap[midpoint]
### Frameworks
![](assets/images/server_03_01.png)  
![](assets/images/server_03_02.png)  
![](assets/images/server_03_03.png)  
@snapend

+++


### Pakete und Module

@ul
- JWT
- API-KEY
- CORS
- SSL
@ulend

+++

### Code-Ausschnitt
![](assets/images/server_04.png)  

---

## CowTrackingDatabase

![](assets/images/02_png_background/CowTracking-Database.png)

+++

@snap[midpoint]
### CowTrackingDatabase
![](assets/images/database_01.png)
@snapend

+++

### Technologie
![](assets/images/database_02.png)

+++

@snap[midpoint]
### Technologie
![](assets/images/database_03.png)

@ul
- Schnellere und einfachere Einarbeitung und Nutzung
- Ausführlichere Dokumentation
@ulend
@snapend

+++

### Datenbankmodell
![](assets/images/database_04.png)

---

## CowTrackingWebInterface

![](assets/images/02_png_background/CowTracking-WebInterface.png)

+++

### Umsetzung

![](assets/images/CowTrackingWebInterface.png)


Note:

Material Design!

+++

### Ergebnis

![](assets/images/gui_3_menu.JPG)

+++

### ToDo

@ul
- Bugfix
- Refactoring
- Kuh & Feld-Management
- Websockets
- Progressive Web App
@ulend

Note:

Marker auf Mobile  
Fertig -> will neu machen  
CUD cow + Field  
polling weg, sockets her  

---

## Tests

+++

Folie 1

Note:

Notizzeile 1  
2

---

## Demo!
![](https://media.giphy.com/media/l0NwNrl4BtDD7JCx2/giphy.gif)

Note:  

http://52.57.81.14

---

@snap[midpoint span-30]
## Fragen?
![](assets/images/thinking_face.png)
@snapend
