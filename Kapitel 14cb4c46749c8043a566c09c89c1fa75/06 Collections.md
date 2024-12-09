# 06 Collections

Status: Done
: No
Verantwortliche:r: Melina Klein
- Liste
	- Was ist eine Liste?
	    
	    Listen ermöglichen es mehrere Elemente von unterschiedlichen Datentypen in einer Variable zu speichern. Dabei können diese mehrfach vorkommen. Listen haben keine feste Größe.
	- Wie deklariert man eine Liste?
	    
	    mylist = [] oder myliste = list(element1, …)
	- Welche Eigenschaften hat eine Liste?
	  collapsed:: true
		- veränderlich
		- sortierbar
		- Duplikate erlaubt
		- mehrere Datentypen erlaubt
		- Elemente müssen nicht sortiert sein
	- Welche wichtigen von Funktionen gibt es?
	    
	    
	    | Funktion | Beschreibung |
	    | --- | --- |
	    | append(x) | fügt Element x an Ende der Liste hinzu |
	    | clear() | löscht alle Elemente der Liste |
	    | copy() | gibt eine Kopie der Liste zurück |
	    | count(x) | gibt zurück wie oft x in der Liste vor kommt |
	    | extend() | adds the elements of a list or any iterable to the end of the current list |
	    | index(x) | returns the index of the first element with value x |
	    | insert() | adds an element to specified position |
	    | pop()  | removes element at specified position |
	    | remove() | removes the item with specified value |
	    | reverse() | reverses the order of the list |
	    | sort() | sorts the list |
	- Was sind die Vorteile von Listen?
		- Listen sind dynamisch, da sie leicht veränderbar sind
		- Man kann mit Index auf Inhalte zugreifen
		- verschiedene Datentypen sind möglich
	- Was sind die Nachteile von Listen?
	    
	    → schlechtere Performance als Tupels
- Tupel
	- Was ist ein Tupel?
	    
	    Tupel sind nicht veränderliche Listen, welche schneller ist und durch ihre Hashbarkeit als Key in Dict verwendet werden kann.
	- Wie deklariert man ein Tupel?
		- namensListe = (”Andreas”, 2, “Tom”)
		- namensListe = “Andreas”, 2, “Tom”
		- bei einzelnen Elementen → namensListe = (”Andreas”,)
		- als Funktion → namensListe = tupel[”Andreas”, 2, “Tom”])
	- Welche Eigenschaften hat ein Tupel?
		- unveränderlich
		- nicht homogen
		- geordnet → können als keys in Dictionaries genutzt werden
	- Welche wichtigen von Funktionen gibt es?
	    
	    
	    | Methode | Beschreibung |
	    | --- | --- |
	    | count(x) | gibt zurück wie oft x im Tupel vorkommt |
	    | index(x) | gibt den Index von erstem Element x zurück |
	    | len(tupel) | gibt Länge des Tupels zurück |
	    | sort() | Sortiert das Tupel |
	    | min(), max(), sum() | mathematische Funktionen |
	- Was sind die Vorteile von Tupeln?
		- schneller
		- unveränderbar
		- erlaubt mehrere return werte
	- Was sind die Nachteile von Tupeln?
	    
	    unveränderbar
- Set
	- Was ist ein Set?
	    
	    Sets werden verwendet, m mehrere Werte zu speichern. Diese Werte haben keinen Index, sind nicht geordnet und unveränderlich (sie können auch nicht aus veränderlichen Datentypen bestehen). Sie können Werte von unterschiedlichen Datentypen enthalten. Es ist nicht möglich zwei identische Werte zu speichern.
	- Wie deklariert man ein Set?
	    
	    set = {wert1, wert2, …}
	- Welche Eigenschaften hat ein Set?
		- nicht veränderlich
		- kann unterschiedliche Datentypen enthalten
		- kann mit einer Schleife durchlaufen werden
	- Welche wichtigen von Funktionen gibt es?
	    
	    
	    | Methode | Beschreibung |
	    | --- | --- |
	    | pop() | entfernt ein Element |
	    | add(x) | fügt ein Element hinzu |
	    | update() | verändert werte |
	    | clear() | entfernt alle Werte |
	    | len(set) | gibt die Länge des Sets zurück |
	- Was sind die Vorteile von Sets?
		- keine Duplikate
		- schnellere Suche als in Listen
	- Was sind die Nachteile von Sets?
		- kein Index
		- nur unveränderbare Datentypen
		- kein Zugriff auf Daten, nur prüfen ob vorhanden
		- weniger funktionen als bei anderen Collections
- Dictionary
	- Was ist ein Dictionary?
	    
	    Dictionaries sind Collections die Key-Value-Paare enthalten. Seit Python 3.7 sidn diese geordnet-
	- Wie deklariert man ein Dictionary?
		- dictionary = { key1 : value1, key2 : value2,…}
	- Welche Eigenschaften hat ein Dictionary?
		- Keys sind unique
		- geordnet
		- müssen nicht homogen sein
		- veränderbar
		- sortierbar
	- Welche wichtigen von Funktionen gibt es?
	    | Methode | Beschreibung |
	    | --- | --- |
	    | dict()  | Konstruktor |
	    | pop() | entfernt Wert |
	    | dict[”key”] | entnimmt Value |
	- Was sind die Vorteile von Dictionaries?
		- benannte Keys sind einfacher zu finden
		- funktionaler Programmierstil
	- Was sind die Nachteile von Dictionaries?
		- bei Vielverwendung schwer lesbar
		- schlechte Leistung
		- nicht speichereffizient