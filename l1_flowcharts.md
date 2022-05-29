# Programmablaufplan (_Flowchart_)

Um Programmflüsse darzustellen, müssen Kontrollstrukturen in leicht verständlicher Form vermittelt werden.  
 
Ein intuitives, wenn auch schnell an Komplexität zunehmendes Instrument, kann hier der Programmablaufplan (auch: _Programmstrukturplan_ oder _Flowchart_/ _Flussdiagramm_) liefern.

## Elemente
### Terminator
![Terminator](bilder/pap_terminator.png)

* Oval 
* Beginn und Ende des Programms. 

### Operation
![Operation](bilder/pap_operation.png)

* Quader
* Anweisung/ Operation (Bsp.: __x:=42__)

### Benutzereingabe/ Bildschirmausgabe
![Input/Output](bilder/pap_io.png)

* Parallelogramm
* Liest bei __Eingabe__ ein
* Gibt bei __Ausgabe__ aus

### Verzweigung
![Verzweigung](bilder/pap_verzweigung.png)

* Raute
* Ja/ Nein-Entscheidung
* __2__ abgehende Verbindungen

### Verbindung
![Verbindung](bilder/pap_verbindung.png)

* Pfeil
* verbindet zwei Elemente
  
## Vorteile
* Gutes Planungsinstrument für Grobübersichten
* Von Laien leicht verständlich

## Nachteile
* GoTo-Abkürzungen verleiten zu Unachtsamkeiten.
* Schleifen müssen aus kleineren Elementen gebaut werden.

>## Beispiel
> Das Programm soll nur bei Eingabe einer geraden Zahl beendet werden. Bei Eingabe einer ungeraden Zahl, soll es wiederholt werden.  
> 
> ![Beispiel](bilder/pap_beispiel.png)