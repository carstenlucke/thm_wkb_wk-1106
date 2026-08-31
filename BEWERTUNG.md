# Bewertung — WK_1106 SS 2026

> Vorlage für die individuelle Projektbewertung. 

**Projekt:** _<Projekttitel eintragen>_
**Gruppe:** _<Gruppen-Bezeichnung>_
**Repository:** _<URL>_
**Tag (M3):** _<v1.0.0>_  ·  **Commit-SHA:** _<a1b2c3d>_
**Bewertungsdatum:** _<YYYY-MM-DD>_

> **Bewertungsgegenstand.** Maßgeblich ist der Stand des getaggten Commits auf dem **Hauptbranch** (Default-Branch, `main` bzw. `master`). Inhalte, die zum Abgabezeitpunkt allein auf einem Nebenbranch liegen, werden nicht bewertet — das gilt für Spezifikation, Architektur und Code gleichermaßen (siehe README, Abschnitte 5.2 und 8.3).

---

## 1. Säulen-Übersicht

| Säule | Gewicht | Punkte (von 100) | Hürde ≥ 50 |
|---|---|---|---|
| 1. Spezifikation (SPEC) | 1/3 | _____ | ☐ OK · ☐ FEHLT |
| 2. Architektur (ARCH) | 1/3 | _____ | ☐ OK · ☐ FEHLT |
| 3. Implementierung & Präsentation (IMPL/PRÄS) | 1/3 | _____ | ☐ OK · ☐ FEHLT |

## 2. Ergebnis

- **Hürde gesamt:** ☐ BESTANDEN · ☐ NICHT BESTANDEN
  *(Eine Säule mit < 50 Pkt → automatisch nicht bestanden, Modulnote 5,0)*
- **Gewichtete Gesamtpunkte (∅ der drei Säulen):** _____ %
- **Modulnote:** _____
- **HISPOS-Eintrag erfolgt am:** _<YYYY-MM-DD>_

> **Notenschlüssel:** gemäß § 9 der *Allgemeinen Bestimmungen für Bachelorprüfungsordnungen der THM* (Teil I der Prüfungsordnung). Bei verletzter Hürde (eine Säule < 50 Pkt) → Modulnote 5,0.

---

## 3. Säule 1 — Spezifikation (SPEC)

| Kriterium | Max | Erreicht | Bemerkung |
|---|---:|---:|---|
| Grundlagen (Ziele, Kontextüberblick, Stakeholder) | 10 |  |  |
| Abläufe und Funktionen (Use Cases, Geschäftsprozesse) | 25 |  |  |
| Daten (Datenmodell, Datentypenverzeichnis) | 15 |  |  |
| Benutzerschnittstelle | 15 |  |  |
| Nichtfunktionale Anforderungen | 5 |  |  |
| Testbarkeit / Akzeptanzkriterien | 5 |  |  |
| Glossar | 5 |  |  |
| Formale Aspekte (Verzeichnisse, Quellen, etc.) | 10 |  |  |
| Aufbau / roter Faden | 10 |  |  |
| **Summe SPEC** | **100** | **____** |  |
| Korrektur: ungeprüfte KI-Generierung erkennbar (0 / −10 / −20) | −20 |  |  |
| **Summe SPEC inkl. Korrektur** |  | **____** |  |

> Hinweis ungeprüfte KI-Generierung: Abzug, wenn das Dokument offensichtlich KI-generiert ist und keine erkennbare Sorgfalt, Prüfung oder Überarbeitung erfolgt ist. Typische Symptome:
> - Halluzinationen, generische Floskeln ohne Projektbezug, Widersprüche zur eigenen Projektidee
> - Tabellen, die Offensichtliches wiederholen oder Inhalte aus dem Fließtext nochmal in Spalten zerlegen, ohne Mehrwert — bläht das Dokument unnötig auf
> - Diagramme, die mit minimalem Zusatzaufwand sauber lesbar wären, aber unbearbeitet im Default-Layout (überlappende Kanten, Beschriftungen quer durchs Bild, willkürliche Anordnung) abgeliefert werden
> - durchgängige Boilerplate-Strukturen ohne inhaltliche Substanz
>
> Skala: 0 = unauffällig, −10 = deutliche Anzeichen, −20 = durchgängig ohne Eigenleistung. Greift unabhängig von der Disclosure-Pflicht (Abschnitt 9.1 README).

## 4. Säule 2 — Architektur (ARCH)

| Kriterium | Max | Erreicht | Bemerkung |
|---|---:|---:|---|
| Grundlagen (Ziele, Überblick) | 5 |  |  |
| Randbedingungen | 5 |  |  |
| Systemkontext / Abgrenzung | 5 |  |  |
| Lösungsstrategie | 5 |  |  |
| Komponentendarlegung | 15 |  |  |
| Laufzeitverhalten | 10 |  |  |
| Verteilung / Deployment | 10 |  |  |
| Querschnittliche Konzepte | 15 |  |  |
| Architekturentscheidungen (ADRs) | 10 |  |  |
| Formale Aspekte (Verzeichnisse, Quellen, etc.) | 10 |  |  |
| Aufbau / roter Faden | 10 |  |  |
| **Summe ARCH** | **100** | **____** |  |
| Korrektur: ungeprüfte KI-Generierung erkennbar (0 / −10 / −20) | −20 |  |  |
| **Summe ARCH inkl. Korrektur** |  | **____** |  |

> Hinweis ungeprüfte KI-Generierung: Abzug, wenn das Dokument offensichtlich KI-generiert ist und keine erkennbare Sorgfalt, Prüfung oder Überarbeitung erfolgt ist. Typische Symptome:
> - Halluzinationen, generische Floskeln ohne Projektbezug, Widersprüche zur eigenen Projektidee
> - ADRs ohne echten Trade-off (Standard-Begründungen ohne Bezug zur konkreten Entscheidung)
> - Komponenten-, Sequenz- oder Verteilungsdiagramme, die mit minimalem Zusatzaufwand sauber lesbar wären, aber unbearbeitet im Default-Layout (überlappende Kanten, Beschriftungen quer durchs Bild, willkürliche Anordnung) abgeliefert werden
> - Diagramme, die nicht zum Code oder zur Spec passen
> - Tabellen, die Offensichtliches wiederholen oder Inhalte aus dem Fließtext nochmal in Spalten zerlegen, ohne Mehrwert — bläht das Dokument unnötig auf
>
> Skala: 0 = unauffällig, −10 = deutliche Anzeichen, −20 = durchgängig ohne Eigenleistung. Greift unabhängig von der Disclosure-Pflicht (Abschnitt 9.1 README).

## 5. Säule 3 — Implementierung & Präsentation (IMPL/PRÄS)

| Kriterium | Max | Erreicht | Bemerkung |
|---|---:|---:|---|
| Konformität zu SPEC | 10 |  |  |
| Konformität zu ARCH | 10 |  |  |
| Git-Hygiene (Conventional Commits, kontinuierliche Historie, Autoren-Diversität) | 10 |  |  |
| Dokumentation (Inbetriebnahme, Code) | 10 |  |  |
| Präsentation (Gruppenvortrag) | 20 |  |  |
| Code-Walkthrough (individuelle Verständnisfragen) | 40 |  |  |
| **Summe IMPL/PRÄS** | **100** | **____** |  |
| Korrektur: ungeprüfte KI-Generierung erkennbar (0 / −10 / −20) | −20 |  |  |
| Korrektur Schwierigkeitsgrad (−5 / 0 / +5) | ±5 |  |  |
| **Summe IMPL/PRÄS inkl. Korrekturen** |  | **____** |  |

> Hinweis ungeprüfte KI-Generierung: Abzug, wenn Code, Tests oder Dokumentation offensichtlich KI-generiert sind und keine erkennbare Sorgfalt, Prüfung oder Überarbeitung erfolgt ist. Typische Symptome:
> - **Code:** generische Variablennamen ohne Domänenbezug (`data`, `result`, `temp`); unbenutzte Imports oder unerreichbarer Code; halluzinierte API- oder Methodenaufrufe (existieren in der genutzten Library nicht); widersprüchliche Patterns innerhalb desselben Moduls (mal Stream, mal for-Loop, mal Recursion ohne Grund); duplizierte Hilfsfunktionen, die sich gegenseitig nicht kennen
> - **Tests:** Tests, die nichts Substanzielles prüfen (`assertTrue(true)`, `assertNotNull` bei Konstanten); Test-Namen ohne Bezug zu fachlichen Use Cases; Mocks, die das Mock selbst testen statt der Logik; durchgängig grüne Tests trotz offensichtlicher Bugs im Code
> - **Boilerplate-Kommentare:** Zeilen wie `// erhöht den Zähler` über `counter++`, oder Doc-Kommentare, die nur den Methodennamen wiederholen
> - **Doku/README:** generische Floskeln ohne Projektbezug; Inbetriebnahme-Anleitung passt nicht zum tatsächlichen Setup; widersprüchliche Befehle/Pfade
> - **Inkonsistenzen:** Sprache wechselt willkürlich zwischen Englisch und Deutsch; Code-Style-Brüche zwischen Modulen ohne Begründung
>
> Skala: 0 = unauffällig, −10 = deutliche Anzeichen in Teilen des Codes/der Tests/der Doku, −20 = durchgängig ohne Eigenleistung. Greift unabhängig von der Disclosure-Pflicht (Abschnitt 9.1 README) und unabhängig vom Code-Walkthrough (dort wird Verständnis individuell geprüft).

> Hinweis Schwierigkeitsgrad: additiv. −5 bei trivialer Aufgabe, 0 bei normalem Umfang, +5 bei überdurchschnittlicher Komplexität.

---

## 6. Studierende

| # | Name | Matrikel-Nr. | Beitrag (knapp) | Indiv. Note (falls Abweichung) |
|---|---|---|---|---|
| 1 |  |  |  |  |
| 2 |  |  |  |  |
| 3 |  |  |  |  |
| 4 |  |  |  |  |
| 5 |  |  |  |  |
| 6 |  |  |  |  |

> Standardmäßig erhält die Gruppe eine gemeinsame Note. Eine individuelle Abweichung nach unten ist möglich, wenn der Code-Walkthrough oder die Git-Historie erkennen lassen, dass eine Person nicht ausreichend zur Gesamtleistung beigetragen hat.

---

## 7. Zusammenfassende Bemerkungen

_<Kurzbegründung der Note, Stärken/Schwächen, Hinweise für Folgesemester>_

---

## 8. Berechnungs-Hinweis

```
S1 = Punkte SPEC inkl. Korrektur      (max. 100, Untergrenze 0)
S2 = Punkte ARCH inkl. Korrektur      (max. 100, Untergrenze 0)
S3 = Punkte IMPL/PRÄS inkl. Korrektur (max. 100, Untergrenze 0)

Hürde:    min(S1, S2, S3) >= 50    sonst: Modulnote = 5,0
∅ Punkte: (S1 + S2 + S3) / 3
Modulnote: gemäß § 9 PO (Allgemeine Bestimmungen Bachelor)
```
