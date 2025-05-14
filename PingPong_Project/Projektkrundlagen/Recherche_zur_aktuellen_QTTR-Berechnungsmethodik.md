## Beschreibung

Führe eine umfassende Recherche zur aktuellen Methodik der QTTR-Berechnung durch.

**Aufgaben**

- Recherche offizieller Dokumente zur QTTR-Berechnung
- Zusammenstellung der mathematischen Formeln
- Klärung der verschiedenen Einflussfaktoren
- Dokumentation der Berechnungsregeln

**Erwartetes Ergebnis**

Ein detailliertes Dokument, das die aktuelle QTTR-Berechnungsmethodik vollständig beschreibt.

---

## Die Grundformel

Die TTR-Berechnung basiert auf einer einzigen zentralen Formel:

$TTR_{neu} = TTR_{alt} + \lfloor(Resultat - erwartetes\ Resultat) \times Änderungskonstante\rceil$


## Die drei Komponenten im Detail

### 1. Resultat
- Summe der Siege bei einer Veranstaltung
- Jeder Sieg = 1 Punkt, jede Niederlage = 0 Punkte

### 2. Erwartetes Resultat (Gewinnerwartung)
- Summe der Gewinnwahrscheinlichkeiten für alle Spiele des Spielers
- Formel für die Gewinnwahrscheinlichkeit eines einzelnen Spiels:
  $P(A \text{ gewinnt}) = \frac{1}{1 + 10^{\frac{TTR_B - TTR_A}{150}}}$
  
  wobei TTR_A und TTR_B die Ratings der beiden Spieler sind

### 3. Änderungskonstante
- Bestimmt, wie stark sich das Rating verändert
- Grundwert: 16
- Zusätzliche Faktoren:
  - +4 bei Inaktivität (keine bewertete Veranstaltung in den letzten 365 Tagen)
  - +4 bei wenig Erfahrung (< 30 bewertete Einzel)
  - +4 für Spieler unter 21 Jahren
  - +4 für Spieler unter 16 Jahren
- Die Änderungskonstante liegt also zwischen 16 und 32

## Besonderheiten für Nachwuchsspiele

- **Quartals-Nachwuchs-Spielstärkezuwachs (QNSZ)**: +6 TTR-Punkte pro Quartal für Spieler bis 17 Jahre
- **Internationaler Nachwuchs-Entwicklungsbonus (QNEB)**: Zusätzlich +10 TTR-Punkte pro Quartal für ausländische Spieler bis 16 Jahre

## Inaktivitätsabzug

- Nach 24 Monaten ohne Spiel: -80 Punkte
- Pro weitere 6 Monate: -20 Punkte
- Maximal -120 Punkte (nach 36 Monaten)
- Ausgenommen: Nachwuchsspieler und Spieler mit Spielberechtigung im Ausland

## Doppel und Mannschaftswettbewerbe

- **Doppel werden nicht in der TTR-Berechnung berücksichtigt**
- Die TTR-Berechnung basiert ausschließlich auf Einzelspielen
- Bei Mannschaftswettbewerben werden nur die individuellen Einzel eines Spielers für seinen TTR-Wert herangezogen
- Jedes Einzel wird als separates Spiel zwischen zwei Spielern betrachtet, unabhängig vom Mannschaftsergebnis
- Das Mannschaftsergebnis selbst (z.B. 9:5) hat keinen Einfluss auf die TTR-Berechnung der einzelnen Spieler

## Wichtige praktische Aspekte

- Der TTR-Wert liegt typischerweise zwischen ca. 500 (Anfänger) und 2.500 (internationale Spitzenspieler)
- Ein Unterschied von 150 Punkten entspricht einer Gewinnwahrscheinlichkeit von 80:20
- Ein Unterschied von 400 Punkten entspricht einer Gewinnwahrscheinlichkeit von 99:1
- Die Q-TTR-Werte werden viermal jährlich aktualisiert (11.2., 11.5., 11.8., 11.12.)
- Die aktuellen Q-TTR-Werte sind die Grundlage für Mannschaftsmeldungen und Turniereinteilungen