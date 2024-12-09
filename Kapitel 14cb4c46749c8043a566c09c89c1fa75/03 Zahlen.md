Verantwortliche:r: Melina Klein

- Wie kommt man an die größte ganze Zahl in python ermittelt werden?
    
    import sys
    
    print(sys.max_size)
    
- Welcher Zahlenraum ist in Python effizient?
    
    Alle Zahlen, die sich mit 64 Bit darstellen lassen.
    
- Wie werden Binär- und Hexadezimalzahlen dargestellt?
    
    
    | Auruf | Ausgabe |
    | --- | --- |
    | hex(10) | 0xA |
    | bin 3 | 0b11 |
- Wie generiert man ganzzahlige Zufallszahlen
    
    Importieren durch ‘from random import randint’
    
    Aufruf: randint(start(inklusive), ende(exklusive)
    
- Wie werden Fließkommazahlen dargestellt und wo findet man zugehörige Funktionen?
    
    Floats werden mit 64 Bit gespeichert. Zugehöroge Funktionen werden im Math-Module gespeichert. In math gibt es Funktionen wie sqrt, sin, cos, tan.
    
- Worauf muss man beim Rechnen mit Floats achten? Was ist die Alternative?
    
    Da binäre Darstellung keine Kommazahlen erlaubt, müssen diese explizit in Programmiersprachen bereot gestellt werden. In Python ist dies nicht fehlerfrei und führt so zu Rundungsfehlern
    
- Wie erstellt man zufällige Zufallszahlen?
    
    Mit Modul random (random, uniform)
    
    | Aufruf | Beschreibung |
    | --- | --- |
    | random() | generiert eine zufällige Kommazahl zwischen 0 (inkl.) und 1 (exklusive) |
    | uniform(Zahl1, Zahl2) | generiert eine Zufallszahl zwischen Zahl1 (inkl.) und Zahl2 (inkl.) |
- Welche weitere Zahlen gibt es? Wie lassen sich diese importieren?
    
    Komplexe Zahlen (i = 2+i), rationale Zahlen oder Brüche durch ‘import fraction’ und Dezimalzahlen → besser als float, da Rundungsfehler erst ab 28 Stellen (import decimal)
    
- Was sind boolsche Werte? Welche Zahlenwerte haben diese?
    
    Boolsche Werte sind Wahrheitswerte, die True (0) oder False (1) sein können.