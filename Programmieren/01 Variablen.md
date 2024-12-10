Verantwortliche:r: Mona Ittlinger

- Was sind Eigenschaften von Variablen?
	- sind "Platzhalter" für einen Wert
	- speichern Werte vorübergehened
	- können im weiteren Programmablauf verwendet und verändert werden
- Was ist die Lebensdauer von Variablen
	nur bis zum Programmende
- Wie erhält die Variable einen Wert?
	mittels Zuweisung
	![[Pasted image 20241210143930.png]]
- Wie müssen Variablennamen aussehen?
	- müssen immer mit einem Buchstaben beginnen
	- restliche Stellen dürfen auch Ziffern und Unterstriche enthalten
	- Leerzeichen und Bindestriche sind nicht erlaubt
	- in der Regel nur Kleinbuchstaben verwenden, camelCase ist erlaubt
- Nenne Datentypen in Python.
	in der Regel erkennt Python den Datentyp einer Variablen automatisch
	![[Pasted image 20241210144248.png]]
- Warum ist es wichtig, sich über Datentypen Gedanken zu machen?
	- in einer Berechnung mit mehreren Variablen müssen dieser immer vom selben Typ sein
	-  Programmierer müssen dafür sorgen, dass die Typen zueinander passen
	- mittels Typumwandlung kann man Variablen konvertieren → dafür den gewünschten Datentyp vor die zu konvertierende Variable schreiben: float(123)
	- bei Einzelfällen übernimmt Python eine Konvertierung automatisch (z.B. Multiplikation int und float)
- Wie ließt man Eingaben vom Nutzer ein?
	input('Geben Sie Ihren Namen ein: ')
- - Wie speichert man eine Eingabe in eine Variable?
    name = input(’Geben Sie Ihren Namen an: ‘)
- Wie ließt man eine Zahl ein?
    alter = int(input(’Geben Sie Ihr Alter an: ‘))