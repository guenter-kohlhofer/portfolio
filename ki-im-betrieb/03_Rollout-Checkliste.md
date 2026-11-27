# Rollout-Checkliste: KI im Betrieb einführen

> Für die fiktive Musterbetrieb Haustechnik GmbH (38 Mitarbeitende, Graz, Microsoft 365, Betriebsrat). Zeitrahmen: 12 Wochen von der Entscheidung bis zum Regelbetrieb.
> Rechtliche Punkte sind mit Paragraf bzw. Artikel belegt, siehe [04_Quellen-und-Rechtsstand.md](04_Quellen-und-Rechtsstand.md). **[unsicher]** markiert Stellen, die im Einzelfall rechtlich zu prüfen sind.

## Phase 0: Entscheidung (Woche 1)

- [ ] Geschäftsführung benennt eine **KI-Ansprechperson** (z. B. IT) und eine Vertretung. Kein gesetzlich vorgeschriebener „KI-Beauftragter“, aber ein klarer Kontakt.
- [ ] Ziel in einem Satz festhalten, z. B. „Weniger Schreibarbeit im Büro, ohne Kundendaten zu gefährden.“
- [ ] Budget grob klären: Lizenzen pro Person und Monat, Schulungszeit (30 Min. × Anzahl Personen), externe Rechtsprüfung.

## Phase 1: Bestandsaufnahme (Woche 1–2)

- [ ] **Schatten-KI erheben:** anonyme Kurzumfrage (3 Fragen): Welche KI-Werkzeuge nutzt du schon? Wofür? Mit welchen Daten?
- [ ] **KI-Inventar** anlegen (Tabelle): Werkzeug, Anbieter, Zweck, Abteilung, Datenstufe, Rolle nach KI-Verordnung (fast immer „Betreiber“), Risikoklasse.
- [ ] **Risikoklassen prüfen** je Einsatz:
  - [ ] Verbotene Praktiken ausgeschlossen (Art. 5, z. B. Emotionserkennung am Arbeitsplatz)
  - [ ] Hochrisiko ausgeschlossen (Anhang III, v. a. Nr. 4 Beschäftigung: Bewerberauswahl, Leistungsbewertung). Falls doch: eigenes Projekt, Pflichten nach Art. 26 gelten nach Digital-Omnibus ab 02.12.2027 **[Datum im Amtsblatt bestätigen]**
  - [ ] Transparenzfälle markiert (Art. 50: Chatbot nach außen, KI-Bilder/-Videos)
- [ ] **Use-Cases sammeln und reihen:** Nutzen (Zeit pro Woche, geschätzt von den Betroffenen) × Machbarkeit ÷ Risiko. Die drei besten kommen in den Pilot.

## Phase 2: Werkzeuge und Verträge (Woche 2–4)

- [ ] Je Werkzeug geprüft und dokumentiert:
  - [ ] **Auftragsverarbeitungsvertrag** (Art. 28 DSGVO) liegt vor
  - [ ] **Serverstandort** und Drittlandübermittlung (EU-US Data Privacy Framework oder Standardvertragsklauseln, Art. 44 ff. DSGVO)
  - [ ] **Training auf Eingaben** vertraglich ausgeschlossen
  - [ ] Aufbewahrung und Löschung von Chatverläufen einstellbar
  - [ ] Anmeldung nur mit Firmenkonto, Mehrfaktor-Anmeldung aktiv
- [ ] **Microsoft 365 vorbereiten** (falls Copilot):
  - [ ] Berechtigungen in SharePoint/OneDrive/Teams aufräumen. Copilot findet alles, worauf jemand Zugriff hat, auch zu großzügig freigegebene Gehaltslisten.
  - [ ] Vertraulichkeitsbezeichnungen (Sensitivity Labels) für Rot-Dokumente, soweit die Lizenz es hergibt **[lizenzabhängig]**
  - [ ] Copilot Chat nur mit Firmenanmeldung erlauben, private Konten im Browser sperren (Richtlinie/Intune)
- [ ] **Verzeichnis der Verarbeitungstätigkeiten** ergänzen (Art. 30 DSGVO).
- [ ] **Datenschutz-Folgenabschätzung** nötig? (Art. 35 DSGVO). Für reine Textassistenz ohne Personendaten meist nein; bei Personendaten in größerem Umfang, Mitarbeiterdaten oder neuen Technologien prüfen. DSB-Liste der DSFA-pflichtigen Verarbeitungen (DSFA-V) beachten **[unsicher, Einzelfall]**
- [ ] **Datenschutzerklärung** der Website anpassen, falls ein Chatbot kommt (Art. 13 DSGVO).

## Phase 3: Betriebsrat und Regeln (Woche 3–6)

- [ ] **Betriebsrat früh informieren** (§ 91 ArbVG Informationsrecht), nicht erst bei fertiger Lösung.
- [ ] Prüfen, ob eine **Betriebsvereinbarung** nötig ist:
  - [ ] § 96 Abs. 1 Z 3 ArbVG: Kontrollmaßnahmen, die die Menschenwürde berühren (zustimmungspflichtig)
  - [ ] § 96a ArbVG: Systeme, die personenbezogene Daten von Mitarbeitenden automationsunterstützt verarbeiten (ersetzbare Zustimmung). Bei Copilot naheliegend, weil Nutzungsdaten anfallen **[unsicher, im Einzelfall prüfen]**
  - [ ] Ohne Betriebsrat: Zustimmung der einzelnen Mitarbeitenden nach § 10 AVRAG prüfen
- [ ] **KI-Nutzungsrichtlinie** fertigstellen ([01_KI-Nutzungsrichtlinie.md](01_KI-Nutzungsrichtlinie.md)), mit Betriebsrat abstimmen, Geschäftsführung unterschreibt.
- [ ] Inhalt der Betriebsvereinbarung mindestens: Zweck, erlaubte Werkzeuge, **keine Leistungs- und Verhaltenskontrolle aus KI-Nutzungsdaten**, Zugriff auf Protokolle nur bei Sicherheitsvorfällen, Schulung, Evaluierung.

## Phase 4: Schulung (Woche 5–7)

- [ ] **Grundschulung 30 Min.** für alle, die KI nutzen sollen ([02_Schulung_KI-Kompetenz.md](02_Schulung_KI-Kompetenz.md)). Für Monteure eventuell als Teil der Werkstattbesprechung.
- [ ] **Vertiefung 60 Min.** für Büro und Pilotgruppe: gute Anweisungen schreiben, Ergebnisse prüfen, eigene Vorlagen.
- [ ] **Dokumentation:** Teilnahmeliste mit Datum, Inhalten, Vortragender:m. Keine Formvorschrift, aber als Nachweis empfohlen (RTR).
- [ ] Lizenz erst **nach** der Schulung freischalten.
- [ ] Neue Mitarbeitende: Schulung in die Einschulungscheckliste aufnehmen.

## Phase 5: Pilot (Woche 6–10)

- [ ] Pilotgruppe 4–6 Personen, ausdrücklich gemischt (Büro, Technik, ein Lehrling).
- [ ] **Vorher messen** (eine Woche): Zeit für die drei Pilotaufgaben, z. B. Angebotstext, Wartungsbericht, Kundenmail. Selbstaufschreibung reicht.
- [ ] Wöchentlich 15 Min. Austausch: Was hat geholfen, wo lag die KI falsch?
- [ ] **Fehlerliste** führen (Beispiel, Werkzeug, Auswirkung), daraus Hinweise für die Schulung.
- [ ] **Nachher messen** (letzte Pilotwoche): dieselben Aufgaben, dieselbe Methode.

## Phase 6: Entscheidung und Regelbetrieb (Woche 10–12)

- [ ] Auswertung: gesparte Zeit (gemessen, nicht geschätzt), Fehler, Zufriedenheit (1–5), Kosten. Ehrlich auch ein „lohnt sich nicht“ zulassen.
- [ ] Ausrollen auf weitere Abteilungen oder Pilot beenden.
- [ ] **Überprüfungstermine** in den Kalender: Richtlinie halbjährlich, Inventar bei jedem neuen Werkzeug, Auffrischungsschulung jährlich.
- [ ] Rechtsstand beobachten: nationale Marktüberwachungsbehörde für die KI-Verordnung in Österreich (Stand 11/2026 noch nicht festgelegt), Leitlinien der Kommission zu Art. 4 und Art. 50.

## Kennzahlen für die Geschäftsführung

| Kennzahl | Wie gemessen | Ziel (Beispiel) |
|---|---|---|
| Geschulte Nutzer:innen | Teilnahmeliste ÷ Lizenzen | 100 % vor Freischaltung |
| Zeitersparnis Pilotaufgaben | Selbstaufschreibung vorher/nachher | wird im Pilot ermittelt, keine Vorgabe |
| Gemeldete Fehler/Pannen | Fehlerliste, Meldungen | jede Meldung ausgewertet |
| Schatten-KI | Umfrage nach 6 Monaten | weniger nicht freigegebene Werkzeuge |
| Kosten pro gesparter Stunde | Lizenzkosten ÷ gemessene Stunden | erst nach Pilot bewertbar |
