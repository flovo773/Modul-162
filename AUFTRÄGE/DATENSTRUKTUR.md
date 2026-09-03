
# Fragestellung 1
Sie müssen eine Adressliste verwalten mit mehreren 100 Datensätzen. Welche Strukturen kommen in Frage und warum?
## ANTWORT:
Für eine Adressliste mit mehreren hundert Datensätzen eignet sich ein Datensatz / Record zusammen mit einer Tabelle bzw. einem Array.

Ein Datensatz kann zum Beispiel Vorname, Nachname, Telefonnummer und Adresse enthalten. Mehrere Datensätze können danach gemeinsam gespeichert werden.

Eine Hashtabelle wäre ebenfalls sinnvoll, wenn man Adressen schnell über einen bestimmten Schlüssel, zum Beispiel eine ID, suchen möchte.

# Fragestellung 2
Sie müssen viele Werte speichern und mit wenig Zeitverlust darauf zugreifen können. Welche Strukturen kommen in Frage und warum?
ANTWORT: Hier eignet sich eine Hashtabelle, weil die Speicherposition eines Wertes direkt berechnet werden kann. Dadurch kann sehr schnell auf die gespeicherten Daten zugegriffen werden.

Auch ein Array ist geeignet, wenn der Index des gesuchten Wertes bekannt ist, weil direkt über diesen Index auf das Element zugegriffen werden kann.

# Fragestellung 3
Sie müssen einen Sortieralgorithmus für Zahlen programmieren. Welche Strukturen kommen in Frage und warum?
ANTWORT: In einem Array können viele Zahlen gespeichert werden. Über den Index kann man einfach auf einzelne Zahlen zugreifen, sie vergleichen und ihre Position verändern.

# Fragestellung 4
Die Universität Zürich hatte in jedem Semester das Problem, dass ihre Server überlastet waren während der Modulregistrierung in neuen Semestern. Jeder Student wollte so schnell als möglich einen Platz für spezifische Vorlesungen reservieren, weil die Plätze jeweils limitiert sind. Dabei mussten die offenen Modulregistrierungs-Anfragen geschickt gespeichert werden.
ANTWORT: Hier eignet sich eine Warteschlange / Queue.

Die Registrierungsanfragen werden in der Reihenfolge verarbeitet, in der sie eintreffen. Das nennt man das FIFO-Prinzip: First In – First Out.

Mit enqueue wird eine neue Anfrage hinten angefügt und mit dequeue wird die älteste Anfrage zuerst verarbeitet.

Dadurch müssen nicht alle Anfragen gleichzeitig verarbeitet werden und der Server wird weniger stark belastet.
