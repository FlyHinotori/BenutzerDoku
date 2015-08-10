Flughäfen
====================================================

Diese Tabelle dient zur Pflege von Flughäfen. Zur Anzeige werden gebracht:

::

	ID - technischer Schlüssel
	Name - Bezeichnung des Flughafens
	Stadt
	Land
	IATA Code
	ICAO Code
	Altitude - Höhe
	Latitude - Längengrad
	Longitude - Breitengrad
	Daylight Saving Time
	Zeitzone
	Zeitzonenbasis
	
.. note::
	Die Spalte "ID" bezeichnet einen technischen Schlüssel und kann daher nicht verändert werden. Die Einträge werden durch das System verwaltet.
	
Import
----------------------------------------------------

.. note::
	
	Aus Sicherheitsgründen wurde der Massenimport von Flughäfen derzeit deaktiviert.

Das Feld "Datenquelle" beschreibt die Datenherkunft des Importes. Über die Schaltfläche "Import" kann dieser ausgeführt werden.
	
Zufügen
----------------------------------------------------

.. warning::
	Das Zufügen einer Zeile sollte mit Bedacht erfolgen, da das Entfernen einer Zeile über die normale Programmoberfläche nicht möglich ist.

Um die Tabelle mit einem neuen Eintrag zu erweitern, sind folgende Schritte notwendig:

1. Zur untersten Zeile scrollen (leere Zeile)
2. Die einzelnen Spalten (außer ID) mit dem entsprechenden Inhalt befüllen
3. Die Eingabe mit der Taste <<ENTER>> beenden
4. Die Sicherheitsabfrage beantworten

::
	
	Ja - Neue Zeile einfügen
	Nein - Abbruch, Zeile wird nicht zugefügt
	
5. Die Hinweismeldung mit "OK" beantworten. (erscheint nur nach den Zufügen)

Die neue Zeile erscheint nun in der Tabelle.

Bearbeiten
----------------------------------------------------

.. warning::
	Änderugen an Datensätzen werden sofort durchgeführt. 
	Es erfolgt keine Sicherheitsabfrage. 
	Änderungen können nicht rückgängig gemacht werden.

Um einen Tabelleneintrag zu bearbeiten, sind folgende Schritte notwendig:

1. Tabelleneintrag per Mausklick selektieren
2. Durch das Drücken der Taste <<F2>> wird der Bearbeiten-Modus aktiviert
3. Das Ändern des Eintrages ist nun möglich
4. Die Änderung mit der Taste <<ENTER>> beenden 

Löschen
----------------------------------------------------

Das Löschen von Zeilen ist nicht möglich.