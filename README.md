# Wirtschaftsinformatik-Projekt I (Softwaretechnik) — WK_1106

**Sommersemester 2026 · B.Sc. Wirtschaftsinformatik · 6 CrP**
**Modulverantwortung:** Prof. Dr. Carsten Lucke
**Stand:** 2026-04-27

---

## 1. Worum es geht

Sie führen in einer Gruppe von **4–6 Personen** ein vollständiges Softwareentwicklungsprojekt von der Spezifikation bis zur lauffähigen, präsentierten Implementierung durch. Sie wenden die in *Softwaretechnik (WK_1208)* und den Grundlagen erlernten Konzepte praktisch an.

Das Projekt ist in vier Meilensteine gegliedert. An den Meilensteinen M1 und M2 finden Reviews mit dem Betreuer statt. M3 ist die finale Abgabe, M4 die Präsentation.

---

## 2. Zulassungsvoraussetzungen

**Notwendig:**
- WK_1201 Einführung in die Programmierung
- WK_1204 Algorithmen und Datenstrukturen

**Empfohlen:**
- WK_1208 Softwaretechnik

Fehlt einer der notwendigen Scheine, ist die Teilnahme nicht möglich.

---

## 3. Termine und Meilensteine für Durchführung in Sommersemester (SS) 2026

| Meilenstein | Inhalt | Termin |
|---|---|---|
| **M0** | Gruppeneinteilung abgeschlossen | **Fr, 8. Mai 2026** |
| **M0+** | Teaminfo & Projektidee im Repo + Mail an Betreuer | **Fr, 15. Mai 2026** (7 Tage nach M0) |
| **Kickoff** | Termin mit Betreuer | individuell ab KW 21 |
| **M1** | Spezifikation abgeschlossen + Review | **Fr, 3. Juli 2026** (empfohlen) |
| **M2** | SW-Architektur abgeschlossen + Review | **Fr, 7. August 2026** (empfohlen) |
| **M3** | Finale Abgabe (Doku + Code) | **Fr, 25. September 2026 — harte Deadline** |
| **M4** | Präsentation der Implementierung | **Oktober 2026** (Terminumfrage nach M3) |

Reviews zu M1/M2 finden in einem Meeting (vor Ort oder virtuell) mit der gesamten Gruppe statt. **Die Unterlagen liegen im Repository und werden nicht zusätzlich per Mail verschickt.** Spätestens 2 Tage vor dem Termin sollten alle Unterlagen im Repo aktualisiert sein; gerne mit einem Tag (`v0.1.0-spec` für M1, `v0.2.0-arch` für M2) markiert. Termine vereinbart der/die Projektleiter:in rechtzeitig per Mail mit dem Betreuer.

---

## 4. Teaminfo & Projektidee (M0+)

Bis zum **M0+-Termin (Fr, 15. Mai 2026)** legen Sie folgendes Dokument **im Wurzelverzeichnis Ihres Repositorys** an:

- **Dateiname:** `TEAMINFO.md`
- **Format:** Markdown, nach folgendem Template (Stub einfach übernehmen, ausfüllen, committen)

Zusätzlich schickt der/die Projektleiter:in eine Mail an den Betreuer mit:

- Repository-URL (HTTPS, klickbar)
- Bestätigung, dass die öffentliche `TEAMINFO.md` (nur Name/Studiengang/Rolle) im Repo eingecheckt ist
- **Vollständige Mitgliederliste** (Name, Matrikel-Nr., THM-E-Mail, Studiengang, Rolle) — als Tabelle im Mail-Body oder als angehängte ausgefüllte Variante der `TEAMINFO.md`. Diese gehört **nicht** ins öffentliche Repo.

Bei Änderungen am Team (Beitritt/Austritt) wird die Liste spätestens mit der M3-Abgabe-Mail aktualisiert.

### Template `TEAMINFO.md`

````markdown
# Teaminfo & Projektidee

## Projekttitel

<Kurzer, prägnanter Titel des Projekts>

## Kurzbeschreibung

<2–4 Sätze: Was soll die Software leisten? Für wen? Welches Problem löst sie?>

## Team

| Name | Studiengang | Rolle | Git-Handle (optional) |
|---|---|---|---|
| Max Mustermann | WI B.Sc. | Projektleiter:in | — |
| Erika Musterfrau | WI B.Sc. | Software Architect | GitHub: `erika-m` |
| … | … | … | … |

> **Spalte „Git-Handle" (optional):** Nur ausfüllen, wenn die Git-Commit-Identität nicht auf den Klarnamen gesetzt ist und Commits unter einem Plattform-Username (GitHub/GitLab) laufen. Damit bleibt die Zuordnung Commit → Person nachvollziehbar. Details und Alternativen: [`tutorials/git-identity.md`](tutorials/git-identity.md).

> **Datenschutz-Hinweis:** Im öffentlichen Repository erscheinen hier ausschließlich Name, Studiengang, Rolle und (optional) der ohnehin öffentliche Git-Plattform-Handle. **Keine** Matrikel-Nummern, **keine** privaten Telefonnummern, **keine** individuellen E-Mail-Adressen. Die **vollständige Mitgliederliste** mit Matrikel-Nummern und THM-E-Mails wird durch die/den Projektleiter:in **per Mail** an den Betreuer übermittelt — spätestens zu **M0+**, bei Änderungen aktualisiert spätestens zur **M3**-Abgabe.

**Rollen-Empfehlung (frei änderbar):** Projektleiter:in, Software Architect, Spec/Requirements Lead, Implementation Lead, QA/Test Lead, DevOps/Build Lead.

## Technologien (voraussichtlich)

- **Sprache(n):** z.B. Java 21, TypeScript 5
- **Frameworks:** z.B. Spring Boot, React, Vue
- **Persistenz:** z.B. PostgreSQL, SQLite
- **Build/Tooling:** z.B. Maven, Gradle, Vite
- **Sonstiges:** z.B. Docker, Auth-Provider, externe APIs

> Diese Liste ist eine Momentaufnahme — Änderungen im Projektverlauf sind erlaubt und in der Architekturbeschreibung (M2) endgültig festzulegen.

## Repository

- **URL:** <https://github.com/…  bzw.  https://git.thm.de/…>
- **Sichtbarkeit:** öffentlich · privat (Betreuer als Member: `carstenlucke` / `clucke`)

## Eingesetzte KI-Werkzeuge (vorläufige Planung)

- z.B. GitHub Copilot für Code-Vervollständigung
- z.B. Claude Code / ChatGPT für Refactoring und Doku-Entwürfe
- …
````

---

## 5. Abzugebende Ergebnisartefakte (M3)

### 5.1 Inhalte

1. **Spezifikationsdokument** (Markdown)
2. **SW-Architekturbeschreibung** (Markdown)
3. **Installations- und Inbetriebnahmeanweisung** (Markdown im Repo, z.B. als Top-Level `INSTALL.md` oder unter `docs/install.md`)
4. **Quellcode** der lauffähigen Endversion im Repository (siehe Abschnitt 8)

**Hinweise zum Format:**
- Spezifikation und Architektur sind als **Markdown** im Repository abzulegen (z.B. `docs/spec/`, `docs/arch/`) — kein PDF. Markdown ist diff-bar, review-fähig und versionierbar; PDF ist es nicht.
- Eingebettete Diagramme als PNG/SVG **mit Quelltext** (PlantUML, Mermaid) im Repo, sodass Diagramme reproduzierbar bleiben.
- Mermaid-Diagramme können direkt in Markdown-Codeblöcken stehen und werden von GitHub/GitLab gerendert.

### 5.2 Abgabe per Git-Tag (verbindlich)

Die Abgabe erfolgt **nicht** durch Mail-Anhang oder ZIP-Upload, sondern über einen **annotated Git-Tag** auf dem Abgabe-Commit:

```bash
git tag -a v1.0.0 -m "Final submission M3"
git push origin v1.0.0
```

- **Tag-Typ:** annotated (`-a`), nicht lightweight.
- **Naming:** empfohlen `v1.0.0` (Semantic Versioning); andere Namen erlaubt, müssen aber in der Abgabe-Mail eindeutig benannt sein.
- **GitHub-Release** auf Basis des Tags ist optional, aber willkommen (Release-Notes als Changelog).
- **Bewertet wird der Stand des getaggten Commits.** Spätere Commits oder verschobene Tags fließen nicht in die Bewertung ein.
- Der Tag muss **vor Ablauf der M3-Deadline** gesetzt und gepusht sein (geprüft wird Tagger-Date und Commit-Date).

### 5.3 Abgabe-Mail (durch Projektleiter:in)

Mail an den Betreuer **bis zur M3-Deadline** mit folgenden Angaben:

- Projektname und Gruppe
- Repository-URL (HTTPS, klickbar)
- Tag-Name (z.B. `v1.0.0`)
- Commit-SHA (7 Zeichen reichen, z.B. `a1b2c3d`)
- **Mitgliederliste** (Name, Matrikel-Nr., THM-E-Mail, Studiengang, Rolle) — entweder erstmalige Übermittlung oder, falls bereits zu M0+ geschickt und seitdem unverändert, kurze Bestätigung „Liste vom <Datum> weiterhin gültig". Bei Änderungen: aktualisierte Version. **Niemals** ins öffentliche Repo.
- Optional: Link zum GitHub-/GitLab-Release

### 5.4 Tagging der Meilensteine M1 und M2 (empfohlen)

Auch zu M1 und M2 darf gerne getaggt werden, z.B. `v0.1.0-spec` und `v0.2.0-arch`. Das schafft saubere Bezugspunkte für Reviews und ist gute Berufspraxis. Pflicht ist nur der M3-Tag.

---

## 6. Empfohlene Strukturen für die Dokumente

Die Dokument-Strukturen sind **Empfehlungen, keine Pflicht**. Wer mit guter Begründung anders strukturiert, darf das. Wer ohne Struktur dokumentiert, riskiert Punktabzug bei „Aufbau / roter Faden".

### 6.1 Spezifikation — Siedersleben-Bausteine

Empfohlen: die Bausteine nach **Siedersleben** (in *Softwaretechnik — Praxiswissen für Softwareingenieure*, Hanser, Kapitel 4):

| Block | Bausteine |
|---|---|
| 1. Projektgrundlagen | P1 Ziele und Rahmenbedingungen · P2 Architekturüberblick |
| 2. Abläufe und Funktionen | F1 Geschäftsprozesse · F2 Anwendungsfälle · F3 Anwendungsfunktionen |
| 3. Daten | D1 Datenmodell · D2 Datentypenverzeichnis |
| 4. Benutzerschnittstelle | B1 Dialogspezifikation · B2 Batch · B3 Druckausgaben |
| 5. Schnittstellen | S1 Nachbarsysteme · S2 Datenmigration · S3 Inbetriebnahme |
| 6. Übergreifendes | N1 Nichtfunktionale Anforderungen · N2 Querschnittskonzepte |
| 7. Ergänzendes | E1 Leseanleitung · E2 Glossar |

Nicht jeder Baustein ist für jedes Projekt relevant. Nicht relevante Bausteine **explizit als „nicht anwendbar" markieren**, mit kurzer Begründung — nicht weglassen.

### 6.2 Architektur — arc42

Empfohlen: das **arc42-Template** (https://arc42.org/). Standard-Gliederung:

1. Einführung und Ziele
2. Randbedingungen
3. Kontextabgrenzung
4. Lösungsstrategie
5. Bausteinsicht (Komponenten)
6. Laufzeitsicht
7. Verteilungssicht
8. Querschnittliche Konzepte
9. **Architekturentscheidungen (ADRs)** — siehe unten
10. ~~Qualitätsanforderungen~~ — **entfällt**
11. ~~Risiken und technische Schulden~~ — **entfällt**
12. Glossar

> **Änderung vom 31.08.2026:** Die Kapitel **10 (Qualitätsanforderungen)** und **11 (Risiken und technische Schulden)** entfallen und müssen nicht angefertigt werden. Beide entfalten ihren Nutzen vor allem in Vorhaben, die über eine Laufzeit von einem Semester hinausgehen und in denen sich Qualitätsziele und technische Schulden über mehrere Ausbaustufen hinweg fortschreiben lassen. Die Qualitätsziele des Systems werden ohnehin in Kapitel 1 benannt. Wer die Kapitel bereits geschrieben hat, muss nichts löschen — sie werden weder positiv noch negativ gewertet. Damit umfasst die Architekturdokumentation die Kapitel **1 bis 9 sowie 12**.

#### Architekturentscheidungen (ADRs) — Pflicht

Dokumentieren Sie **jede wesentliche Architekturentscheidung** als ADR (Architecture Decision Record). Format frei wählbar (MADR, Y-Statement etc.), aber jede Entscheidung muss enthalten:

- **Kontext:** Was war das Problem, welche Randbedingungen?
- **Alternativen:** Welche Optionen wurden geprüft?
- **Entscheidung:** Was wurde gewählt?
- **Begründung:** Warum diese Option?
- **Konsequenzen:** Was bedeutet die Wahl, auch negativ?

Mindestens 3–5 ADRs werden erwartet (z.B. Programmiersprache, Persistenz, Frontend-Framework, Authentifizierung, Deployment). Generische Floskeln ohne echten Trade-off zählen nicht.

### 6.3 Beispiel-Projekt zur Orientierung

Als laufendes Beispiel dafür, **wie eine Spec nach Siedersleben und eine Architektur nach arc42 in einem realen Projekt aussehen können**, dient das Repository **Herold**:

- Repository: <https://github.com/carstenlucke/herold>
- Spezifikation (Siedersleben-Bausteine): `docs/spec/`
- Architektur (arc42 + ADRs): `docs/arch/`

> **Disclaimer:** Herold ist ein laufendes Projekt und **noch nicht abgeschlossen**. Die Dokumente entwickeln sich weiter und sind nicht in jedem Detail eine perfekte Vorlage. Sie zeigen aber den Stil, die Granularität und die Verzahnung von Spec, Architektur, ADRs und Code, die hier erwartet wird. Nicht 1:1 kopieren — als Inspiration nutzen.

**Wichtigster Bewertungsaspekt.** Die drei Artefakte müssen aufeinander aufbauen:

- Anwendungsfälle aus der Spec sind in der Architektur als Komponenten/Sequenzen wiederfindbar.
- Komponenten der Architektur entsprechen Modulen/Paketen im Code.
- Datentypen aus D2 sind im Datenmodell und im Code identisch benannt.
- ADRs erklären, warum die Architektur so aussieht, wie sie aussieht — und der Code folgt der Entscheidung.

Im Review wird stichprobenartig geprüft: *Zeigen Sie mir Use Case UC-X in der Architektur. Zeigen Sie mir das im Code.*

---

## 8. Git-Repository — Anforderungen

### 8.1 Sichtbarkeit ab Tag 1

- Das Repository muss **ab Beginn des Projekts** für den Betreuer einsehbar sein.
- **Standard:** öffentliches Repository auf GitHub oder THM-GitLab.
- **Ausnahme erlaubt** (z.B. wegen sensibler Daten, IP-Bedenken): privates Repository, in dem der Betreuer als Member/Reporter eingetragen ist.

**Zugänge des Betreuers:**
- **GitHub:** `carstenlucke`
- **GitLab THM:** `clucke`

Bei Beginn des Projekts den Repository-Link per Mail an den Betreuer senden — spätestens mit der Teaminfo (M0+).

### 8.2 Conventional Commits

Verbindlich für alle Commit-Messages: **Conventional Commits** (https://www.conventionalcommits.org/de/v1.0.0/).

Einsteiger-Guide in diesem Repo: [tutorials/conventional-commits.md](tutorials/conventional-commits.md).

Cheatsheet: https://gist.github.com/qoomon/5dfcdf8eec66a051ecd85625518cfd13

Beispiele:

```
feat(auth): add password reset flow
fix(ui): correct button alignment in dashboard
docs(spec): add use case UC-12
refactor(api): extract validation into middleware
```

### 8.3 Kontinuierliche Historie

- Commits über die gesamte Projektlaufzeit verteilt — **nicht ein Big-Bang-Push am Abgabetag**.
- Mehrere Autoren in der Historie sichtbar — jedes Gruppenmitglied committet unter einem **konsistenten, eindeutig zuordenbaren Git-Namen**, sodass Beiträge zugeordnet werden können. Welche E-Mail-Adresse Sie als Commit-Autor:in hinterlegen, bleibt Ihnen überlassen. Anleitung zum Einrichten: [tutorials/git-identity.md](tutorials/git-identity.md).
- Branches und Pull/Merge Requests sind willkommen, aber nicht zwingend.

Eine Abgabe mit nur wenigen Commits oder nur einem Autor wird als **Indiz für externe Komplettentwicklung (z.B. Bolt, Lovable, v0)** gewertet und führt zu deutlichem Punktabzug in Säule 3 — bis hin zum Nicht-Bestehen, wenn der Code-Walkthrough zeigt, dass die Gruppe das System nicht selbst verstanden und gebaut hat.

### 8.4 Was nicht ins Repo gehört

- API-Keys, Tokens, Passwörter, `.env`-Dateien mit Geheimnissen
- Personenbezogene Daten Dritter
- **Personenbezogene Daten der eigenen Gruppenmitglieder über das Notwendige hinaus** — keine Matrikel-Nummern, keine privaten Telefonnummern. E-Mail-Adressen einzelner Mitglieder sind nicht erforderlich; eine Team-Kontakt-Adresse genügt.
- Große Binärdateien ohne Notwendigkeit

Geeignete `.gitignore` von Anfang an verwenden.

---

## 9. Einsatz von KI-Werkzeugen

KI-Coding-Werkzeuge (Claude, Copilot, ChatGPT, Cursor, v0, Bolt, Lovable etc.) sind **erlaubt und realistisch** — Sie werden im Berufsalltag damit arbeiten.

### 9.1 Disclosure-Pflicht

In der Spezifikation und im Architekturdokument je ein kurzer Abschnitt **„Eingesetzte KI-Werkzeuge"**:

- Welche Werkzeuge wurden genutzt?
- Wofür (Code-Generierung, Refactoring, Doku-Erzeugung, Diagramme, Recherche)?
- Wie wurden Ergebnisse geprüft und ggf. überarbeitet?

Ehrliche Auflistung führt **nicht** zu Abzug. Verschwiegene KI-Nutzung, die im Walkthrough offenkundig wird, dagegen schon.

### 9.2 Eigenes Verständnis ist Pflicht

Sie dürfen sich von KI helfen lassen — Sie müssen aber **jeden Teil Ihres Codes und Ihrer Dokumente erklären können**. Im Code-Walkthrough (Teil der Präsentation, siehe Abschnitt 10.4) wird das individuell geprüft.

---

## 10. Bewertung

### 10.1 Gewichtung

Die Modulnote setzt sich aus drei gleichgewichteten Säulen zusammen:

| Säule | Gewicht |
|---|---|
| Spezifikation | **1/3** |
| Architektur | **1/3** |
| Implementierung & Präsentation | **1/3** |

### 10.2 Bestehensregel — Hürde pro Säule

**Jede Säule muss einzeln bestanden werden** (mind. 50 von 100 Punkten, entspricht Note 4,0).

> Wird auch nur **eine** Säule mit weniger als 50 Punkten bewertet, gilt das **gesamte Modul als nicht bestanden** (Note 5,0) — unabhängig vom rechnerischen Mittel.

Das soll verhindern, dass eine sehr gute Spec eine fehlende Implementierung kompensiert (oder umgekehrt).

### 10.3 Bewertungskriterien je Säule (Übersicht)

Die detaillierte Punktverteilung steht im **Bewertungs-Template** ([`BEWERTUNG.md`](BEWERTUNG.md)). Hier die wichtigsten Kriterien:

**Säule 1: Spezifikation (100 Punkte)**
- Grundlagen (Ziele, Kontext, Stakeholder)
- Abläufe und Funktionen (Use Cases, Geschäftsprozesse)
- Daten (Datenmodell, Datentypen)
- Benutzerschnittstelle
- Nichtfunktionale Anforderungen
- Testbarkeit / Akzeptanzkriterien
- Glossar
- Formale Aspekte und roter Faden
- *Korrektur: ungeprüfte KI-Generierung erkennbar (0 / −10 / −20, additiv)*

**Säule 2: Architektur (100 Punkte)**
- Grundlagen, Randbedingungen, Systemkontext / Abgrenzung, Lösungsstrategie
- Komponentendarlegung
- Laufzeitverhalten
- Verteilung / Deployment
- Querschnittliche Konzepte
- **Architekturentscheidungen (ADRs)**
- Formale Aspekte und roter Faden
- *Korrektur: ungeprüfte KI-Generierung erkennbar (0 / −10 / −20, additiv)*

**Säule 3: Implementierung & Präsentation (100 Punkte)**
- Konformität zur Spezifikation
- Konformität zur Architektur
- **Git-Hygiene** (Conventional Commits, kontinuierliche Historie, Autoren-Diversität)
- Dokumentation (Inbetriebnahme, Code)
- Präsentation (Gruppenvortrag)
- **Code-Walkthrough (individuelle Verständnisfragen)**
- *Korrektur: ungeprüfte KI-Generierung erkennbar (0 / −10 / −20, additiv)*
- *Korrektur Schwierigkeitsgrad (±5 Punkte, additiv)*

### 10.4 Code-Walkthrough

Im Anschluss an die Gruppenpräsentation (M4) findet ein **Code-Walkthrough im Gruppenkreis** mit dem Betreuer statt:

- Der Betreuer wählt **zufällig** Codestellen oder Architekturkomponenten.
- Pro Person mind. **eine Frage**: 2–3 Minuten Erläuterung.
- Bewertet wird: Verständnis der Funktionsweise, der getroffenen Entscheidungen und des Zusammenspiels mit Spec/Architektur.

### 10.5 Individuelle Note

Standardmäßig erhält die Gruppe eine **gemeinsame Note**.

Wenn der Code-Walkthrough oder die Git-Historie deutlich machen, dass ein einzelnes Mitglied **nicht ausreichend zur Gruppenleistung beigetragen hat**, behält sich der Betreuer eine **individuelle Abweichung** dieser Person nach unten vor. Diese Möglichkeit wird hier explizit angekündigt und gilt für alle Gruppen.

---

## 11. Präsentation (M4)

- Format: **45–60 Minuten** (30 Min. Vortrag + 15–30 Min. Fragerunde inkl. Code-Walkthrough)
- Inhalte: wichtigste Aspekte aus Spezifikation, Architektur und Implementierung
- Ort: virtuell via Zoom (Zugangsdaten und Termine in Moodle)
- Vorträge sind öffentlich für Kommiliton:innen; Code-Walkthrough nur im Gruppenkreis

---

## 12. Kontakt und Kommunikation

- Hauptkommunikation: per Mail durch die/den Projektleiter:in
- Inhaltliche Rückfragen: in Moodle oder per Mail
- Repository-Link: per Mail spätestens mit Teaminfo (M0+)

---

## 13. Hinweise

- **Abweichungen vom skizzierten Vorgehen** werden zeitnah über Moodle bekannt gegeben.
- **Frühere Fertigstellung** ist möglich — Absprache mit dem Betreuer.
- **Diese Bewertungsregeln gelten verbindlich ab Veranstaltungsbeginn**, sind in Moodle hinterlegt und ersetzen frühere Fassungen.
