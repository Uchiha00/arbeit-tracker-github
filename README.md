# Job & Ausbildung Application Tracker

A lightweight, single-file web application for tracking full-time job and vocational training (*Ausbildung*) applications in Germany, featuring automated status synchronization with Gmail.

## Key Features
- **Dual-Column Board:** Separate views for **Jobs · Full-Time** and **Ausbildung** applications with real-time search and counters.
- **Automated Gmail Sync:** Connects to a custom Google Apps Script Web App endpoint to automatically detect HR replies, automated receipt confirmations, rejections, and scheduled emails (`in:scheduled`).
- **7-Stage Visual Pipeline:** Interactive pastel progress bars (`15%` to `100%`) plus smart follow-up timers indicating when an application needs a polite check-in.
- **Built-in Cover Letter & Notes Editor:** Store and copy tailored subjects (*Betreff*) and cover letters (*Anschreiben*) per application.
- **Privacy-First & Portable:** Zero external dependencies, local storage persistence, JSON import/export, and multilingual UI (**EN / DE / UA**).

---

## Bewerbungs-Tracker für Jobs & Ausbildung (Deutsch)

Eine schlanke Single-File-Webanwendung zur Verwaltung von Bewerbungen für Vollzeitstellen und Ausbildungsplätze mit automatischer Gmail-Synchronisation.

### Hauptfunktionen
- **Zweispaltige Übersicht:** Getrennte Spalten für **Vollzeit-Jobs** und **Ausbildung** inklusive Live-Suche und Statuszählern.
- **Automatische Gmail-Synchronisation:** Verbindung über einen eigenen Google Apps Script Web-App-Endpunkt zur automatischen Erkennung von HR-Rückmeldungen, Eingangsbestätigungen, Absagen und geplanten E-Mails.
- **7-Stufen-Fortschrittsanzeige:** Interaktive Statusleiste (`15 %` bis `100 %`) sowie intelligente Erinnerungs-Badges bei längerer Wartezeit.
- **Integrierter Anschreiben- & Notiz-Editor:** Schnelles Bearbeiten und Kopieren von Betreffzeilen und Anschreiben direkt in der Bewerbungskarte.
- **Datenschutzfreundlich & portabel:** Keine externen Frameworks, lokale Speicherung im Browser (`localStorage`), JSON-Import/Export und mehrsprachige Oberfläche (**EN / DE / UA**).

## Quick Start
1. Open `dresden-tracker-github.html` in any modern browser or host it directly via **GitHub Pages** (rename to `index.html` if used as the repository root).
2. *(Optional)* Click the gear icon (**Settings**) to connect your own Google Apps Script Web App URL and API key for live Gmail synchronization.
