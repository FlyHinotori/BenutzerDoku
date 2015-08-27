Einführung
====================================================

Systemanforderungen
----------------------------------------------------

**Betriebssystem:**

	- Microsoft Windows 7 oder höher
	- .NET Framework 4.5

**Hardware:**

	- Prozessor: 1 GHz oder schneller
	- RAM: 2 GB
	- freier Festplattenspeicher: 20 GB

Zusätzliche Standardperipheriegeräte wie Maus, Tastatur und Monitor werden vorausgesetzt.

Installation
----------------------------------------------------

IST NOCH OFFEN --> Installation oder Auslieferung als Ordner

Starten
----------------------------------------------------

Die Anwendung wird durch einen Doppelklick auf die Datei "Autopilot.exe" oder dessen Verknüpfung darauf geöffnet.

Oberfläche
----------------------------------------------------

Die Oberfläche der Anwendung gliedert sich in drei wesentliche Bereiche:

::
	
	Links - Hauptnavigation - Neuer Auftrag, Aufträge, Rechnungen, Kalender, Kunden, Stammdaten
	Rechts - Unternavigation - in Abhängigkeit des gewählten Programmteils in der Hauptnavigation
	Mitte - Arbeitsbereich
	
.. image :: Start.jpg



Sicherung
----------------------------------------------------

Da die komplette Datenhanltung in einer Datenbank erfolgt, sind nur die Datenbankdateien zur Herstellung notwendig:

::
	
	Autopilot.mdf
	Autopilot_log.mdf
	
Die Datenbankdateien befinden sich im Programmverzeichnis der Anwendung.

Wiederherstellung
----------------------------------------------------

Zur Wiederherstellung einer Sicherung ist es lediglich erforderlich, die Datenbankdateien aus einer Sicherung in das aktuelle Programmverzeichnis wieder herzustellen.