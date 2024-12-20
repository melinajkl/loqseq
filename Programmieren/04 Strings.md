Verantwortliche:r: Melina Klein

- Wie werden Zeichenketten im Programmcode dargestellt?
    
    Entweder in ‘einfachen Anführungszeichen’ oder in “doppelten Anführungszeichen”
    
- Wie werden Zeichenketten aneinandergefügt und vervielfacht?
    
    Aneinanderfügen mit +
    
    Vervielfachen mit *
    
- Wie werden Zeichenketten intern dargestellt?
    
    In Form von Unicode
    
- Welche Sonderzeichen gibt es? (Beispiel, nicht vollständig)
    
    
    |  |  |
    | --- | --- |
    | \n | Zeilenumbruch |
    | \t | Tabulator |
    | \r | Wagenrücklauf(Windows-Textdateien) → kommt von Schreibmaschinen und stellt das Zurücksetzen des Schreibkopfes auf Zeilenanfang dar |
    | \’ | das Zeichen ‘ |
    | \” | das Zeichen “ |
- Wie erstellt mein ein raw-Zeichenkette?
    
    Man erstellt einen raw-String emöglicht es, dass \ nicht als Sonderzeichen interpretiert wird. 
    
    → r”\r” gibt \r aus
    
- Erkläre die Slicing-Syntax?
    
    ![image.png](image.png)
    
- Welche wichtigen Funktionen gibt es bei Strings?
    
    
    | Methode | Beschreibung |
    | --- | --- |
    | len(s) | Anzahl der Zeichen |
    | str(x) | wandelt x in einen String um |
    | sub in s | Testet ob sub in s vorkommt |
    | s.find(sub) | Sucht ob sub in s vorkommt und gibt Startposition zurück |
    | s.join(x) | verbindet Zeichenketten in x |
    | s.lower() | liefert s in Kleinbuchstaben |
    | s.upper() | liefert s in Großbuchstaben |
    | s.replace(old, new)  | Liefert s zurück, wo old durch new ersetzt wurde |
- Wie formatiert man Zeichenketten mit %?
    
    In Strings kann man mit dem % und einem angehängten Datentyp (d → ganze Zahl, f → float, s → Zeichenkette) weitere Werte einfügen.
    
    Beispiel: 
    
    ![image.png](image%201.png)
    
- Wie funktioniert die .format-Funktion?
    
    ![image.png](image%202.png)
    
- Wie formatiert man Strings mit f?
    
    ![image.png](image%203.png)
    
- Was sind reguläre Ausdrücke? Wie benutzt man sie? Was muss man importieren?
    
    Reguläre Ausdrucke werden in einer eigenen Sprache geschrieben und werden dazu genutzt  Suchmuster in Zeichenketten zu definieren.
    
    In Python kann man diese über das Modul re importiert werden.
    
    Wichtige Funktionen sind: 
    
    ![image.png](image%204.png)
    
- Wie definiert man Muster für Regex (=regular expressions/reguläre Ausdrücke)?
    
    ![image.png](image%205.png)