Verantwortliche:r: Mona Ittlinger

- Nenne Eigenschaften von Datum und Zeit in Python.
    - Umgang mit Datum und Zeit ist in allen Programmiersprachen schwierig
    - Grund: große Anzahl an Sonderfällen
        - Zeitzonen
        - Schaltjahre und -sekunden
        - Sommer- und Winterzeit
        - Unterschiedliche Darstellung je nach Landessprache
    - speichern von Datum und Zeit durch bisher bekannte Datentypen nur umständlich möglich
    - Module datetime und time bieten vordefinierte Funktionen
- Wie wird die Zeit ermittelt und dargestellt?
    - Funktion zum Ermitteln der aktuellen Zeit: now()
    - Liegt im Modul datetime in der Klasse datetime
    ![[Pasted image 20241210144828.png]]
	- einzelne Zeitkomponenten können mit Eigenschaften year, month, day, hour, minute, second, microsecond ausgegeben werden
	    ![[Pasted image 20241210144915.png]]
-  Wie kann man das Datum und die Zeit formatieren?
    - Datum und Zeit kann auch formatiert ausgegeben werden
    - hierfür Methoden isoformat und strftime nutzen
    - strftime benötigt Formatierungscodes für Jahr, Monat etc.
    ![[Pasted image 20241210144958.png]]
- Wie kann man das Datum parsen?
	- ein Datum kann auch aus Zeichenketten herausgeparst werden
	- Methoden strptime (p steht für parsen, f für formatieren)
	- Angabe der Formatierungscodes notwendig
	![[Pasted image 20241210145332.png]]
- Wie kann man das Datum ohne Zeit ausgeben?
	- Datum gibt es auch als alleinstehendes Objekt
	- Modul datetime mit Klasse date
	- Das aktuelle Datum kann today() entnommen werden
	![[Pasted image 20241210145555.png]]
- Wie kann man die Zeit ohne Datum ausgeben?
	- eigene Methode nur für Zeit vergleichbar mit today() für Datum gibt es nicht
	- Umweg über datetime mit Methoden now() und time()
	![[Pasted image 20241210145736.png]]
- Wie kann man mit Zeiten rechnen?
	- ausgehend von Zeitpunkt kann Zeit oder Datum durch Angabe einer Zeitspanne errechnet werden: Klasse timedelta
	![[Pasted image 20241210145853.png]]
- Wie kann man Zeiten subtrahieren?
	- um Zeitspanne zu berechnen können zwei Zeitangaben voneinander subtrahiert werden
	- Klassen: date, datetime, time
	- Ergebnis ist immer Objekt vom Typ timedelta, dessen Eigenschaften zur Weiterverwendung bereitstehen
	![[Pasted image 20241210150126.png]]

