# 🏆 FIFA WM 2026 Live App

Eine moderne, inoffizielle Web-Anwendung zur Verfolgung der FIFA Fußball-Weltmeisterschaft 2026 in Kanada, Mexiko und den USA. Die App ist als **Single-Page Application (SPA)** gebaut und läuft komplett im Browser. 

Dank des **PWA-Supports** kann die App direkt aus dem Browser heraus wie eine native App auf dem Smartphone installiert werden.

## ✨ Features

- **📡 Live-Daten-Anbindung:** Bezieht Spielstände, Tabellen, Spielminuten und Spielereignisse (Tore, Karten) live über die offizielle ESPN-Sport-API.
- **📱 PWA (Progressive Web App):** Offline-fähig (Basis-Dateien) und nativ auf dem Homescreen von iOS und Android installierbar.
- **🎨 Dynamisches Theme-System:** Wähle zwischen Dark- und Lightmode sowie aus 5 kuratierten Farb-Themes (z.B. Obsidian, Cyberpunk, Nord).
- **⚽ Live-Tor-Animationen:** Fällt im Auto-Modus ein Tor, blinkt die entsprechende Zahl rot auf und pulsiert, sodass kein wichtiges Ereignis verpasst wird.
- **🎯 Team-Zentrale:** Detail-Ansicht für alle 48 Nationen inklusive Übersicht des nächsten Spiels und gefiltertem Spielplan.
- **🏟️ Stadion-Modal:** Ein Klick auf ein Spiel öffnet erweiterte Details mit Stadion-Foto, Head-to-Head-Stats, Live-Spielverlauf und (simulierten) Aufstellungen.
- **🌳 Automatischer K.o.-Baum:** Der Turnierbaum füllt sich anhand der Gruppen-Ergebnisse komplett automatisch.

## 🚀 Installation

### Auf dem Smartphone installieren
Rufe den generierten GitHub-Pages-Link auf dem Handy auf:
- **iPhone (Safari):** Unten auf das "Teilen"-Symbol (Viereck mit Pfeil) tippen -> "Zum Home-Bildschirm".
- **Android (Chrome):** Entweder auf das eingeblendete Banner "Zum Startbildschirm hinzufügen" tippen, oder oben rechts ins Menü gehen und dort auswählen.

## 🛠️ Technologien
- **HTML5 & CSS3** (Komplett responsives Glassmorphism-UI ohne externe CSS-Frameworks)
- **React 18** (Wird direkt über CDN geladen, kein Node/NPM/Webpack Build-Step nötig)
- **Babel Standalone** (Kompiliert JSX im Browser für maximale Einfachheit)
- **ESPN World Cup API** (Für Live-Polling im Hintergrund)

## ⚠️ Disclaimer
Dies ist ein inoffizielles Fan-Projekt. Alle Rechte an den Logos, Markennamen und offiziellen Bezeichnungen der FIFA Weltmeisterschaft liegen bei der FIFA. Die API-Daten werden lediglich für Darstellungszwecke aus frei verfügbaren Quellen der ESPN-API bezogen.
