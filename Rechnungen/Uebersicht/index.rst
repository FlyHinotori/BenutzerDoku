Rechnungsübersicht
====================================================

Die Maske der Rechnungsübersicht gliedert sich in drei Bereiche.

Suchfeld
----------------------------------------------------

Das Suchfeld befindet sich ganz oben und ist nach dem Starten der Anwendung leer. Bei einer Eingabe erfolgt eine sofortige Filterung der angezeigten Rechnungen in der Übersicht. Es werden folgende Spalten durchsucht:

::
	
	Auftrag
	Kunde
	Flughafen Abflug
	Flughafen Ziel
	
.. note::
	Eine Eingabe im Suchfeld hat eine sofortige Auswirkung auf die Anzahl der angezeigten Rechnungen in der Übersicht.	

Rechnungsübersicht
----------------------------------------------------

Direkt unter dem Suchfeld werden die Rechnungen tabellarisch dargestellt. Zur Anzeige werden gebracht:

::
	
	Auftrag - Auftragsnummer, technischer Schlüssel
	fällig am - Datum der Fälligkeit
	Status
	Mahnstufe
	Saldo
	Auftragsart
	vom - Beginn des Auftrages
	bis - Ende des Auftrages
	Kunde - Name des Kunden
	Flughafen Abflug
	Flughafen Ziel
	
.. note::
	Die Anzahl der angezeigten Rechnungen ist abhängig von den Eingaben im Suchfeld. 
	
Die Auswahl einer Rechnung erfolgt über den Mausklick. Danach können Details sowie eine Kontenübersicht zur Rechnung angezeigt und Buchungen zur gewählten Rechnung vorgenommen werden.

**Details**

Der Reiter "Details" beinhaltet zusätzliche Informationen zu einer Rechnung. Derzeit werden dort abgebildet:

::
	
	Preis
	Zusatzkosten
	fällig am
	
**Kontenübersicht**

Im Reiter "Kontenübersicht" kommt es zu einer tabellarischen Darstellung einzelner Buchungen zur gewählten Rechnung. Angezeigt wird:

::
	
	Buchnungsdatum
	Haben - Eurobetrag im Haben
	Soll - Eurobetrag im Soll
	Buchungstext

**Buchen**

Über den Reiter "Buchen" lassen sich diverse Buchungen für eine Rechnung durchführen, z.B. Einzahlungen durch den Kunden, Guthabenüberweisungen an den Kunden.

.. warning::
	Buchungen können nicht rückgängig gemacht werden.

Nachdem in der Rechnungsübersicht eine Rechnung per Mausklick ausgewählt wurde, können dazu Buchungen wie folgt erfasst werden:

1. Betrag in Euro eintragen
2. Buchungstext eintragen
3. *haben* oder *soll* festlegen
4. Die Sicherheitsabfrage beantworten

::
	
	Ja - Buchung durchführung
	Nein - Abbruch, keine Buchung 
	
Sobald eine Buchung vorgenommen wurde, ändert sich automatisch der Saldo der Rechnung und die soeben vorgenommene Buchnung ist unter dem Reiter "Kontenübersicht" sichtbar.