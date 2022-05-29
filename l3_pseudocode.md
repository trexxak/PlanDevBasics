# Pseudocode

Pseudocode ist nicht ausführbarer "Stift- und Papier"-Code.
Wieso aber Code schreiben der nicht ausführbar ist? Während Programmiersprachen sehr unterschiedlich sein können, sind die Probleme, die mit ihnen gelöst werden als auch die Lösungen selber universell. Um also mit Peers einer anderen Programmiersprache diskutieren und planen zu können, bietet sich der Pseudocode als universelle Sprache für Programmiererdiskussionen an.  

Es gibt keine klaren Standarts für Pseudocode, jedoch hat sich die Notation, die im Folgenden gewählt wird, bewährt.

## Elemente

### Programmanfang und Ende

>ANFANG  
>...  
>ENDE  

### Variablendeklaration und Initialisierung
>zahl : INTEGER = 0  
>satz : STRING = ""  
>kondition : BOOL = FALSCH  

### Funktionen
>PROZEDUR funktion()  
>...  
>ENDE PROZEDUR funktion  

### Konditionen
>WENN ... DANN  
>...  
>SONST WENN ...  
>...  
>SONST  
>...  
>ENDE WENN

### "for-Schleife" _(zählergesteuerte Schleife)_
>FUER i BIS n  
>...  
>ENDE FUER  

### "foreach-Schleife"
>FUERJEDEN x IN y  
>...  
>ENDE FUERJEDEN  

### "while-Schleife" _(kopfgesteuerte Schleife)_
>SOLANGE i KLEINER 0  
>...  
>ENDE SOLANGE  

## Vorteile
* ermöglicht sprachenunabhägiges Diskutieren von Programmkonzepten.

## Nachteile
* Zielgruppe auf Programmierer beschränkt.
* Potential unübersichtlich zu werden.

## Beispiel
> Ein Programm welches zwei eingegebene Zahlen zusammenzählt und anschließend ausgibt. Es fragt nach Wiederholung, und wenn "n" eingegeben wird, wiederholt es sich nicht weiter.

> ### ANFANG  
>
> zahl_1 : INTEGER = 0  
> zahl_2 : INTEGER = 0  
> resultat : INTEGER = 0  
> wdh : BOOL = WAHR  
> auswahl : CHAR = 'y'
> 
> ### SOLANGE wdh IST WAHR
> 
> AUSGABE "1. Zahl?"  
> EINGABE zahl_1  
> 
> AUSGABE "2. ZAHL?"  
> EINGABE zahl_2
>
> resultat = zahl_1 + zahl_2  
> AUSGABE resultat
> 
> AUSGABE "Noch mal? (y/n)"  
> 
> ### SOLANGE auswahl IST NICHT 'y' UND auswahl IST NICHT 'n'  
> EINGABE auswahl  
> ### SOLANGE ENDE
> 
> ### WENN auswahl IST 'n' DANN  
> wdh = FALSCH  
> ### ENDE WENN  
> 
> ### ENDE SOLANGE
>
> ### ENDE
