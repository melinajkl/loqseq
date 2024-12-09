Verantwortliche:r: Melina Klein

- Wofür werden Operatoren in Python genutzt?
    - zur Zuweisung von Variablen
    - zum Vergleich von Werten
    - zur Berechnung mathematischer Ausdrücke
    - für logische Ausdrücke
    - für Mengenoperationen
- Wie werden Vorzeichen geschrieben?
    
    +  oder - vor einer Zahl
    
- Wie werden die Grundrechenarten verdeutlicht?
    - + für Addition
    - - für Subtraktion
    - /  für Division
    - * für Multiplikation
- Welches Zeichen wird für die ganzzahlige Division benötigt?
    
    //  
    
- Wie rechnet man Modulo?
    
    Man berechnet was bei einer ganzzahligen Division als rest übrig bleibt 
    
    → Operator: %
    
- Exponentialfunktion
    
    **
    
- Wie verbindet man Strings? Wie vervielfacht man diese? Wann braucht man es?
    - Verbindung mit +
    - Vervielfachung mit *
    - z.B. in print-Befehlen
- Wie weist man einer Variable einen Wert zu?
    
    =
    
- Wie kombiniert man eine Zuweisung mit einer Rechenoperation?
    
    Zuerst der Rechenoperator, dann ohne Leerzeichen ein Ist-gleich.
    
    → +=, -=, *=, /=, %=
    
- Wie testet man auf (Un-)Gleichheit?
    - == für Gleichheit
    - ! = für Ungleichheit (ohne Leerzeichen)
- Wie vergleicht man Werte (4 Operationen)?
    
    <, >, < =, > = (ohne Leerzeichen)
    
- Wie funktioniert ein binäres Und? Schreibweise?
    
    Ein binäres Und ist ein binärer Operator. Es wird auf Bitebene verknüpft:
    
    - 0 und 1 = 0
    - 1 und 0 = 0
    - 0 und 0 = 0
    - 1 und 1 = 1
    
    → Operator: &
    
- Wie funktioniert ein binäres Oder? Schreibweise?
    
    Ein binäres Oder ist ein binärer operator. Es wird auf Bitebene verknüpft. 
    
    - 0 und 1 = 1
    - 1 und  0 = 1
    - 1 und 1 = 1
    - 0 und 0 = 0
    
    → Operator: |
    
- Wie funktioniert ein binäres Exklusiv-Oder? Schreibweise?
    
    Vergleich auf Bitebene:
    
    - 1 und 0 = 1
    - 0 und 1 = 1
    - 0 und 0 = 0
    - 1 und 1 = 0
- Wie funktioniert ein binäres Not? Schreibweise?
    
    ^ ist ein unärer Operator, d.h. er braucht nur eine Zahl. Er arbeitet auf Bitebene:
    
    - 0 wird zu 1
    - 1 wird 0
- Wie funktioniert ein Logisches Oder? Schreibweise?
    
    
    |  | wahr | falsch |
    | --- | --- | --- |
    | wahr | wahr | wahr |
    | falsch | wahr | falsch |
    
    → Schreibweise: or
    
- Wie funktioniert ein Logisches Und? Schreibweise?
    
    
    |  | wahr | falsch |
    | --- | --- | --- |
    | wahr | wahr | falsch |
    | falsch | falsch | falsch |
    
    → Schreibweise: and
    
- Wie funktioniert ein Logisches Nicht? Schreibweise?
    
    wird bei Aussagen genutzt, z.B. in einem Schleifenkopf
    
    → Schreibweise: not
    
- Bringe die Operatoren in die hierarchische Reihenfolge.
    1. Exponentialoperator
    2. Vorzeichen und binäres nicht
    3. Multiplikation und Division
    4. Addition und Subtraktion
    5. Binäres und
    6. Binäres Exklusiv-Oder
    7. Binäres Oder
    8. Vergleichsoperatoren
    9. Logisches Nicht
    10. Logisches und
    11. Logisches Oder
    
    → kein Anspruch auf Vollständigkeit, weiteres in Python Dokumentation