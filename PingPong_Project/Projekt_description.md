# **Projekt Q-TTR**

---

## Fragestellung: Worauf lassen sich (besonders) starke Veränderungen der QTTR-Werte zurückzuführen?

#### **Projekt Aufbau:**

**Daten:** 
- Vergleiche zwischen einem Quartal nach hinten oder Quartal 1 Jahr nach hinten. 
    - Daten bekommen wir gestellt, hierbei muss kontrolliert werden wo es *starke* Veränderungen gibt und was überhaut eine starke Veränderung ist.
    - Sommer Stichtag start zu Sommer Stichtag ende
- Kontreter Spielverlauf zwischen den bei den identifizierten starken Quartal Differnz.

**Vorgehen:** 

**Vorstellen der Fragestellung:**
- ⁠Was genau ist unsere Fragestellung? (Große QTTR-Veränderungen und deren Ursachen)
- ⁠⁠Was wollen wir damit erreichen? (Soll der QTTR wert anders berechnet werden? Warum gibt es große Veränderungen?)

**Vorstellung der Verwendeten Daten:**
- ⁠Welche Daten benötigen wir überhaupt?
- ⁠⁠Können wir ein Clustering der Veränderungen machen?
	- Gibt es auf Basis der Vorhandenen Daten von Klemm schon erste Rückschlüsse die wir ziehen können?
- Benötigen wir weitere Informationen zum detaillierten Spielverlauf für unsere Analyse?

**Angestrebte Analyse Methoden:**
- ⁠Theoretischer Hintergrund: Wie kann es zu (größeren) Veränderungen kommen?
	- Echte Veränderungen der Spielstärke, konzeptionelle Aspekte der Berechnung (Inaktivitätsabzug), Datenfehler, …
	-> Wie wird die Veränderung überhaupt berechnet bzw. wie kommen die QTTR Werte überhaupt zu stande?
- ⁠Was sind große QTTR-Veränderungen: Detaillierte Beschreibung
	- von Veränderungen von einem zum nächsten Quartals-Stichtag, von Jahr zu Jahr
	- mit verschiedenen Eingrenzungen (TTR-Bereiche/Ligen, Regionen, Alter, Geschlecht, …)
	- Eingrenzung auf jüngere Vergangenheit (z.B. seit Q4 2022), ggf. spätere Erweiterung

**Ausblick auf das Finale Ergebniss:**
- ⁠Was wollen wir erreichen? 
    - eine Veränderung der Berechnung? Passt die Art und weise wie Berechnet wird? Warum gibt es große Veränderungen?

**Bedeutung der Abkürzungen im Datensatz:**
- **2J** Beschreibt ob eine Lizenz für 2 Jahre vorhanden ist
- **MM** Beschriebt ob der Spieler/ die Spielerin in einer Manschaft gemeldet ist
- **SPB** Bestimmt ob der Spieler / die Spielerin spielberechtigt ist - also offiziell gemeldet ist
- **10e** Sagt an ob der Spieler / die Spielerin 10 einsätze in der laufenden Saison hatte
- **Typ** Beschriebt die Spielerklassen wie *Schüler C(u11)* oder auch *Senioren +40*