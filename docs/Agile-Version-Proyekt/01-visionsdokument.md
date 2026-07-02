# Visionsdokument

| Feld | Wert |
|---|---|
| Projekt | Bookfly B2C E-Commerce System |
| Verfasser/in | Sandra Mazo |
| Kunde | Bookfly AS GmbH |

---

## 1. Problem und Kontext
Das Vertriebsunternehmen AS GmbH betreibt eine stationäre Buchhandlung (Bookfly) für den Buchverkauf im Einzelhandel, verfügt jedoch noch nicht über eine Online-Präsenz und möchte diese Lücke durch eine Website schließen, die als Online-Shop, offener Katalog seines Bestands  und Kommunikationskanal für seine  bestehenden sowie potenziellen und zukünftigen Kunden dient, die dort neben dem Katalog auch Öffnungszeiten, die Unternehmensphilosophie  sowie die Allgemeinen Geschäftsbedingungen einsehen können.



## 2. Projektziele
_Messbare Ziele (SMART). Was wird mit dem System erreicht (Soll-Zustand)._

- Z1: Die Website soll die digitale Präsenz des Buchladens sicherstellen und dabei ein Image vermitteln, das der Philosophie, Ästhetik, den Grundsätzen und Dienstleistungen der Marke entspricht.
- Z2: Es muss der Öffentlichkeit den Zugriff auf den Buchkatalog ermöglichen und eine Filterung nach Titel, Autor und Sprache bieten;
- Z3: Der Online-Katalog des Shops muss sicher und einfach aktualisiert werden können.
- Z4: Es soll den Kunden ermöglichen, Bücher auf sichere und intuitive Weise in wenigen Schritten zu kaufen.
- Z5: . Die Grundfunktionen der Website müssen bis zum 28. August 2026 einsatzbereit sein. Das Unternehmen strebt damit eine größere Kundennähe und die Erweiterung seines potenziellen Marktes an.
- Z6: Der Kunde möchte Verkaufsstatistiken einsehen können.

## 3. Umfang (Scope)

**Im Umfang enthalten (In Scope)**
- Visuelles Design im Enklang mit der Markenidentität
- Seite mit Unternehmenphilosophie, Öffnungszeiten und   Allgemeine Geschäftsbedingungen (AGB).
- Öffentlicher Katalog mit Filtern nach Titel, Autor und Sparache
- Administrationsbereich zur Aktualisierung des Katalogs
- Einfache Registrierung mit Benutzername und Passwort
- Warenkorb und  und Simulator für die Zahlungsplattform
- Einführung der Grundfunktionen bis zum 28.08.2026
- Dashboard zur Anzeige von Verkaufsstatistiken
- API zur Anbindung an externe Plattformen (vorläufig)


**Nicht im Umfang enthalten (Out of Scope)**
- Versand einer Bestätigungs-E-Mail für die Registrierung
- Echte Zahlungsplattform
- System für Nutzerbewertungen/-kommentare
- Native mobile App
- Zahlreiche Zahlungsmethoden
- System für personalisierte Empfehlungen
- Treueprogramm/Punkte 


## 4. Benutzer und Rollen

| Rolle | Beschreibung | Hauptbedürfnis |
|---|---|---|
| Kunde (Käufer) | Externe Nutzer der Website | den Online-Katalog einsehen,  die Richtlinien und Öffnungszeiten einsehen,  Bücher in den Warenkorb legen und  Online-Einkäufe tätigen|
| Administrator_| interner Benutzer | Aktualisierung der Informationen auf der Website, Aktualisierung des Katalogs, Automatisierung des Online-Vertriebs |

## 5. Rahmenbedingungen / Einschränkungen

- Der Stack ist auf PHP (ohne Framework), HTML, CSS und Vanilla JavaScript beschränkt — Frameworks wie Laravel oder React sind im Rahmen dieser Übung nicht vorgesehen.
- Als Webserver wird Apache eingesetzt, als Datenbank MariaDB.
- Die Entwicklungsumgebung läuft unter WSL (Windows Subsystem for Linux) mit nativ installiertem Apache und MariaDB.
- Die Anbindung an die Datenbank erfolgt direkt über PHP (z. B. PDO/MySQLi), ohne ORM(Objekt relational mapping).
- Deployment erfolgt über einen kostenlosen Hosting-Anbieter  mit PHP- und MySQL/MariaDB-Unterstützung.
- Website muss bis 28.08.2026 live sein


## 6. Erfolgskriterien

- Die Website ist termingerecht (28.08.2026) live und funktionsfähig.
- Mindestens 90% der Katalogeinträge sind nach Titel, Autor und - Sprache filterbar fehlerfrei.
- Der Checkout-Prozess umfasst maximal 3 Schritte.
- Der Administrator kann neue Bücher in unter 5 Minuten ohne technische Vorkenntnisse hinzufügen.
- Online-Einkäufe und -Zahlungen sind in maximal 4 Schritten erledigt.

## 7. Risiken 
| Risiko | Wahrscheinlichkeit | Auswirkung | Gegenmaßnahme |
|---|---|---|---|
|  | Hoch/Mittel/Gering | Hoch/Mittel/Gering |  |
|Gibt es im Falle eines Fehlers keinen technischen Support für das Hosting. | Mittel | Mittel | noch festzulegen
|Aufgrund der minimalen Leistungsmerkmale des kostenlosen Hostings gibt es keine Garantie für die Ladegeschwindigkeit der Website | Mittel | Mittel | noch festzulegen
|Das kostenlose Hosting könnte ohne Vorankündigung plötzlich eingestellt werden. | Mittel | Hoch| noch festzulegen
