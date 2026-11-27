# KI im Betrieb einführen: ein Paket für KMU

**Richtlinie, Schulung und Rollout-Plan, mit denen ein österreichischer Kleinbetrieb KI-Werkzeuge rechtskonform und ohne Datenpannen einführt.**

[Zurück zum Portfolio](https://guenter-kohlhofer.github.io/portfolio/)

## Problem

In vielen Betrieben nutzen Mitarbeitende längst ChatGPT, Copilot oder ähnliche Werkzeuge, oft mit Gratiskonten und ohne Regeln. Gleichzeitig verlangt die EU-KI-Verordnung seit 02.02.2025, dass Firmen ihre Leute im Umgang mit KI schulen (Art. 4), und die DSGVO gilt sowieso. Kleine Betriebe haben dafür weder Rechtsabteilung noch Zeit für 40-seitige Konzepte.

## Lösung

Ein Paket am Beispiel eines **fiktiven Grazer Installationsbetriebs** (38 Mitarbeitende, Microsoft 365, Betriebsrat), das sich in einem Nachmittag anpassen lässt:

| Datei | Inhalt | Umfang |
|---|---|---|
| [01_KI-Nutzungsrichtlinie.md](01_KI-Nutzungsrichtlinie.md) | Fünf Grundregeln, freigegebene Werkzeuge, **Daten-Ampel** (Grün/Gelb/Rot), Verbote, Kennzeichnung, Meldeweg | ca. 2 Seiten |
| [02_Schulung_KI-Kompetenz.md](02_Schulung_KI-Kompetenz.md) | **30-Minuten-Grundschulung** als Foliensatz mit Sprechernotizen, drei Praxisfällen aus dem Handwerk, Quiz und Teilnahmeliste | 17 Folien |
| [03_Rollout-Checkliste.md](03_Rollout-Checkliste.md) | **12-Wochen-Plan** von der Bestandsaufnahme über Verträge, Betriebsrat und Pilot bis zum Regelbetrieb, mit Kennzahlen | 6 Phasen |
| [04_Quellen-und-Rechtsstand.md](04_Quellen-und-Rechtsstand.md) | Rechtsstand 27.11.2026 inkl. Digital-Omnibus, jede Aussage mit Quelle und Sicherheitsgrad | |

**Grundsätze:**

- **Österreichisches Recht:** KI-Verordnung, DSGVO, ArbVG (§§ 96, 96a), AVRAG, Hinweise von RTR-KI-Servicestelle und WKO. Keine deutschen Rechtsquellen.
- **Ehrlich markiert:** Was rechtlich nicht geklärt ist, steht als **[unsicher]** im Text, statt geraten zu werden.
- **Kurz und praxisnah:** Beispiele aus dem Betrieb (Angebotstext, Baustellenfoto, Bewerbungen) statt Paragrafenlisten.
- **Messen statt behaupten:** Der Pilot misst Zeitaufwand vorher und nachher, keine erfundenen Einsparversprechen.

## Folien ansehen

Die Schulung ist im [Marp](https://marp.app)-Format geschrieben: lesbar als normales Markdown, und mit einem Befehl als PDF oder PowerPoint exportierbar:

```bash
npx @marp-team/marp-cli 02_Schulung_KI-Kompetenz.md --pdf
npx @marp-team/marp-cli 02_Schulung_KI-Kompetenz.md --pptx
```

## Anpassen für den eigenen Betrieb

1. Firmenname, Werkzeugliste und KI-Ansprechperson in der Richtlinie ersetzen
2. Praxisfälle in der Schulung durch eigene Alltagsaufgaben tauschen
3. Offene Punkte in [04_Quellen-und-Rechtsstand.md](04_Quellen-und-Rechtsstand.md) mit Rechtsberatung klären

## Hinweis

Keine Rechtsberatung. Das Unternehmen ist erfunden. Die Unterlagen entstanden mit KI-Unterstützung (Claude); Recherche der Rechtslage, Prüfung der Quellen und Aufbereitung liegen bei mir.

Günter Kohlhofer, Graz · [Portfolio](https://guenter-kohlhofer.github.io/portfolio/) · [GitHub](https://github.com/guenter-kohlhofer)
