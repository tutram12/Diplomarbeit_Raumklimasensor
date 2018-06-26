# Diplomarbeit - Raumklimasensor  
## Enzi, Martinak, Tuttner    
  
### Was soll das Objekt können?
Es soll die Lautstärke, den CO2-Gehalt und die Temperatur messen.  
Diese Werte sollen vor Ort verarbeitet und über ein Display am Gerät ausgegeben werden.  
  
### Wer übernimmt welchen Teilbereich und möchte welchen Betreuer?  
Projektkoordinator: AV-Stv. DI Peter Nöhrer  
  
Teilbereich      | Diplomant                                    |  Betreuer
-----------|:------------------------------------------------|:-------------------------------------|  
Mechanik & Zusammenbau | Enzi Gert                                    | Fachlehrer Wolfgang Sauer BEd
Elektronik | Martinak Moritz               | AV-Stv. DI Peter Nöhrer
Software | Tuttner Raphael                    | DI Manfred Steiner

  
### Aufbauart
wenn möglich Komplettaufbau, ansonsten Teilaufbau  

### Kostenübernahme
Die Kosten werden zwischen allen teilnehmenden Schülern gleichmäßig aufgeteilt.

### Meilensteine
Datum      | Beschreibung                                    |
-----------|:------------------------------------------------|  
04.01.2018 | Konzepfreeze                                    |
07.07.2018 | Fertigstellung Sensorausarbeitung               |
09.09.2018 | Fertigstellung µC - Software                    |
09.09.2018 | Fertigstellung Platinendesign                   |
23.09.2018 | Erster Test des Gesamtsystems                   |
23.09.2018 | Fertigstellung Gehäusedesign                    |
30.11.2018 | Fertigung von Gehäuse und Platinen              |
28.02.2019 | Fertigstellung der Dokumentation                |  

### Troubleshoting  
#### 21.06.2018
Die Ursprüngliche µC-Lösung wäre der Arduino Nano mit dem ATMEGA328P gewesen.  
Da dieser aber zu wenig Pins für unser Projekt vorweist, sind wir auf ein User-Board  
mit dem ATMEGA324P umgestiegen. Dieser besitzt 40 Pins, wo der ATMEGA328P nur 32 Pins besitzt.  
Zudem besitzt der ATMEGA324P über zwei USART-Schnittstellen. Der ATMEGA328P nur über eine.
