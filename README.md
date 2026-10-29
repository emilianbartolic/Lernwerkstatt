# KI-Lernwerkstatt

Eine eigenständige Progressive Web App (PWA) für BWL- und KI-Lernen. Sie funktioniert ohne externe Bibliotheken, Tracker oder Cloud-Speicherung und speichert Lernstand, eigene Karteikarten und Notizen ausschließlich lokal im Browser.

## Live-App

Nach Aktivierung von GitHub Pages ist die App hier erreichbar:

https://emilianbartolic.github.io/Lernwerkstatt/

## Funktionen

- **Karteikarten-Trainer:** Zehn vorbefüllte Karten zu LLM, RAG, Harness, Memory, Prompt Injection, Token-Ökonomie und EU AI Act; eigene Karten können ergänzt werden.
- **ROI- & Token-Kostenrechner:** Vergleich zwischen Frontier-, Mini- und Lokalmodellen inklusive monatlicher Ersparnis und Amortisationsdauer.
- **Lokale Lernverwaltung:** Fortschritt und Notizen per `localStorage`; Daten als JSON exportieren und importieren.
- **Offline & installierbar:** Service Worker mit versioniertem Cache und PWA-Manifest für Smartphone und Desktop.
- **Barrierearm & responsiv:** Große Touch-Ziele, Dark Mode und keine externen Abhängigkeiten.

## Lokal starten

Für die reine Ansicht genügt ein Browser. Für Installation und Offline-Cache muss die App über HTTPS, GitHub Pages oder einen lokalen HTTP-Server geöffnet werden.

```bash
python3 -m http.server 8080
```

Dann `http://localhost:8080` öffnen.

## Installation

- **iPhone/iPad:** In Safari öffnen → Teilen → **Zum Home-Bildschirm**.
- **Android:** In Chrome → Menü → **App installieren** oder **Zum Startbildschirm hinzufügen**.
- **macOS/Windows:** In Chrome oder Edge das Installationssymbol in der Adressleiste verwenden.

## GitHub Pages

In den Repository-Einstellungen unter **Settings → Pages** als Quelle `Deploy from a branch`, Branch `main` und Ordner `/(root)` wählen.
