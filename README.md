# Portfolio: Projekte mit KI

[![Qualitätsprüfung](https://github.com/guenter-kohlhofer/portfolio/actions/workflows/qualitaet.yml/badge.svg)](https://github.com/guenter-kohlhofer/portfolio/actions/workflows/qualitaet.yml)

**👉 Zur Seite: https://guenter-kohlhofer.github.io/portfolio/**

Übersicht über Projekte, die ich mit KI (vor allem Claude) spezifiziert, gebaut und im Alltag eingesetzt habe.

## Was auf der Seite zu sehen ist

| Bereich | Beispiele |
|---|---|
| Fünf Projekte zum Einstieg | Willhaben-Inserate aus Handyfotos mit [inserat-mcp](https://github.com/guenter-kohlhofer/inserat-mcp), lokale KI-Box für Kleinbetriebe, [KI im Betrieb einführen](ki-im-betrieb/) (Richtlinie, Schulung, Rollout), [AI Trading Workbench](https://github.com/guenter-kohlhofer/ai-trading-workbench), Café-Kassa (mit Demo) |
| Praxis & Automatisierung | Ordnung in Cloud und Laptop, digitalisierte Gesundheitsakte (ohne Daten), Fahrtenbuch für ein geteiltes Auto |
| Trading-System im Detail | Tägliche Aufrufkette mit rund 50 Python-Skripten, geplante KI-Aufgaben, Studien mit Gegenproben |
| KI-Skills | Homepage-Pipeline auf GitHub Pages, drei Skills für den Trading-Alltag, Instagram-Export, Projektsicherung, Artikel-Archiv |
| Konzepte & Analysen | Arbeitsmarkt IT & KI Steiermark, M365 & KI-Governance, Website-Sicherheitscheck |
| Social Media | Beitrag mit großer Reichweite, Trading Radar Austria: Design-System, Faktenchecks |
| Webseiten | Geli's Holzwerkstatt, PC-Lernseite |
| Werdegang & Kontakt | Kurz-Lebenslauf, Werkzeuge, Kontakt per E-Mail |

## Technik

- Eine einzige `index.html`, CSS eingebettet, kein JavaScript nötig
- Schriften Archivo und IBM Plex Sans lokal im Ordner `fonts/` (SIL Open Font License, Lizenztexte liegen bei)
- Eigene Druckansicht für den Ausdruck oder das Speichern als PDF
- Veröffentlicht über GitHub Pages
- Automatische Qualitätsprüfung per GitHub Action bei jedem Push und jeden Montag: HTML-Validierung (html-validate), Link-Prüfung (lychee) und Lighthouse mit Mindestwert 90 % bei Barrierefreiheit

## Datenschutz

- Keine Cookies, kein Tracking, keine externen Schriften oder Skripte (Schriften liegen lokal)
- `noindex, nofollow`: Die Seite wird gezielt per Link weitergegeben, nicht über Suchmaschinen gefunden
- Keine privaten Daten im Code
- GitHub protokolliert laut eigener Dokumentation die IP-Adressen der Besucher

## Hinweis

Der Code der beschriebenen Projekte entstand mit KI-Unterstützung (Claude). Aufgabenstellung, Spezifikation, Tests und Betrieb liegen bei mir.
