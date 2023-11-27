# coding_workshop
kleines Projekt um objektorieniteries Programmieren zu üben im Rahmen der Weiterbildung von DataCraft.
Aufgabe A – Objektorientierte Programmierung neu orientiert
In dieser Aufgabe sollen über Klassen verschiede Eigenschaften und Funktionen eingestellt 
werden. Bitte bearbeite die Aufgabe vollständig. 

Teil 1: Person, Student und Dozent
Du gründest deine eigene Coding-Schule. 
Jeder, egal ob Student oder Dozent, ist eine Person: 
- Jede Person hat einen Namen
- Jeder Person sollte es möglich sein, sich vorstellen (zB: „Hallo, mein Name ist 
Pascal“)
Jede Person ist entweder ein Student oder ein Dozent: 
- Jeder Student hat einen Grund zur Teilnahme (zB: „Ich will coden lernen“)
- Jeder Dozent hat eine Biografie (zB: „Ich codiere mit R und Python und liebe die 
Lehre“)
- Jeder Dozent hat Fertigkeiten (zB: „Python“, „R“, „SAS“ …) 
- Jeder Dozent kann neue Fertigkeiten mit der Funktion „add_skill“ erlernen

Teil 2: Workshop
Deine neue Coding-Schule bietet natürlich Workshops an. Jeder Workshop hat: 
- Ein Start- und Enddatum
- Ein Thema
- Einen oder mehrere Dozenten
- Mehrere Studenten
- Eine Funktion „add_participants“, die nur Personen als Argument erlaubt. Ist die 
Person Dozent, wird sie der Liste der Dozenten hinzugefügt. Ist die Person Student, 
wird sie der Liste der Studenten hinzugefügt. 

Teil 3: Funktionen außerhalb der Klassen
Erstelle eine Funktion print_members, die die Informationen aller Studenten und aller 
Dozenten in einer sauber strukturierten JSON Datei speichert. 
Erstelle eine Funktion print_workshops, die alle Informationen eines Workshops (Start- und 
Enddatum, Thema) in einer sauber strukturierten JSON Datei speichert. 
Erstelle eine Funktion print_details, die beide obigen Funktionen zusammen durchführt. 
