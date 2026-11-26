# Job & Ausbildung Application Tracker — v2.3 Alpha

A minimalist, zero-dependency single-file web application for tracking full-time job and vocational training (*Ausbildung*) applications in Germany, featuring fast parallel Gmail synchronization and built-in AI email classification.

## What's New in v2.3 Alpha
- **Minimalist Pastel Design (Light & Matte Dark):** Clean alabaster paper light theme by default with muted pastel status badges, zero neon colors or glowing shadows, and an optional matte dark mode toggle (`☾` / `☀`).
- **Fast Parallel Gmail Sync:** Syncs active applications in parallel chunks via POST (avoiding CORS preflight and timeout bottlenecks), with automatic retry/split recovery and a dismissible post-sync diff summary showing exactly what changed.
- **Built-in AI Email Check (Zero-Key + Optional APIs):**
  - Paste any email into **AI Email Check** to detect whether it is a rejection, automated receipt confirmation, personal HR reply, interview/assessment invitation, job offer, or non-application newsletter — and update or add cards in one click.
  - Works out of the box via free **Pollinations AI** (plus smart local heuristic fallback) or optionally with your own **Google Gemini Flash**, **Groq**, or custom OpenAI-compatible API key in Settings.
- **Status Filters & Empty-Start Onboarding:** Filter by `All`, `Active`, `Replied`, `Follow up`, or `Rejected`. Starts completely clean with zero personal data, with an optional **Load Demo (6)** button to preview sample cards.
- **Built-in Apps Script v3.0 Snippet:** Copy-ready Google Apps Script `Code.gs` directly inside **Settings** for live Gmail synchronization.

---

## Bewerbungs-Tracker für Jobs & Ausbildung — v2.3 Alpha (Deutsch)

Eine minimalistische Single-File-Webanwendung zur Verwaltung von Bewerbungen für Vollzeitstellen und Ausbildungsplätze mit schneller Gmail-Synchronisation und integrierter KI-E-Mail-Analyse.

### Hauptfunktionen
- **Minimalistisches Pastell-Design:** Ruhiges helles Papier-Theme (plus mattes Dark-Theme) ganz ohne grelle Neonfarben, mit Status-Filtern (`Alle`, `Aktiv`, `Antwort`, `Nachfassen`, `Absagen`) und Echtzeit-Suche.
- **Schneller paralleler Gmail-Sync:** Parallele POST-Abfragen über Ihren eigenen Google Apps Script Web-App-Endpunkt (`Code.gs` v3.0 direkt in den Einstellungen kopierbar).
- **KI-E-Mail-Analyse:** Kostenlose Analyse über Pollinations AI (oder optional eigenen Gemini-/Groq-Schlüssel) inkl. lokalem Fallback zur sicheren Erkennung von Absagen, Eingangsbestätigungen, HR-Antworten, Einladungen und Newslettern.
- **Datenschutzfreundlich & leer beim Start:** Keine persönlichen Daten enthalten — direkt eigene Bewerbungen anlegen oder optional per Klick 6 Demo-Einträge laden. Mehrsprachig (**EN / DE / UA**), JSON-Import/Export und Speicherung ausschließlich lokal im Browser (`localStorage`).

## Quick Start
1. Open `dresden-tracker-github.html` in any modern browser (or host via **GitHub Pages**).
2. Add your own applications or click **Load Demo (6)** to explore sample cards.
3. *(Optional)* Click the **Settings** gear icon to copy the included **Apps Script v3.0** snippet and connect your Gmail Web App URL, or configure an optional Gemini/Groq API key.
