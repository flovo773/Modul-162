# Kurzfassung: Datenqualität

Datenqualität beschreibt, wie zuverlässig und brauchbar Daten sind. Gute Daten sollten vollständig, eindeutig, widerspruchsfrei und möglichst ohne unnötige Redundanzen sein.

Ursachen für schlechte Datenqualität

Typische Ursachen sind:

schlecht aufgebaute Eingabeformulare
unklare Feldbezeichnungen
unterschiedliche Schreibweisen
fehlende Pflichtfelder
Zusammenführen verschiedener Datenquellen
doppelte Datensätze

Beispiel:
„Bahnhofstrasse 10“ und „Bahnhofstr. 10“ können fälschlicherweise als zwei verschiedene Adressen erkannt werden.

Merkmale schlechter Datenqualität
Vollständigkeit: Sind alle benötigten Angaben vorhanden?
Eindeutigkeit: Existiert jeder Kunde nur einmal?
Redundanz: Sind gleiche Daten mehrfach vorhanden?
Widersprüchlichkeit: Gibt es unterschiedliche Angaben zum gleichen Sachverhalt?

Zusammenhang:

fehlende Eindeutigkeit → Redundanz → Widersprüche

Datenbereinigung

Bei der Bereinigung werden zum Beispiel:

Duplikate entfernt
fehlende Werte ergänzt
falsche Werte korrigiert
Schreibweisen vereinheitlicht
veraltete Daten gelöscht
Datenbereinigung mit Excel

Excel bietet unter Daten unter anderem:

Sortieren
Filtern
Duplikate entfernen
Text in Spalten aufteilen
Daten zusammenführen
Datenbereinigung mit SQL

Mit SQL kann man grosse Datenmengen automatisch prüfen und korrigieren.

Beispiele:

UPDATE Kunde
SET Ort = 'Zürich'
WHERE Ort = 'Zuerich';

→ vereinheitlicht Schreibweisen.

SELECT *
FROM Kunde
WHERE EMail IS NULL;

→ findet fehlende E-Mail-Adressen.

Merksatz:
Gute Daten sind vollständig, eindeutig, korrekt und widerspruchsfrei. Datenbereinigung verbessert bestehende Daten, langfristig müssen aber auch die Ursachen der Fehler behoben werden.
