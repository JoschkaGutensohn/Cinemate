# KinoInfo App 🍿

Eine React-App, die mit der [TheMovieDB API](https://www.themoviedb.org/) kommuniziert und die aktuellsten Kinofilme sowie deren Informationen anzeigt.

## Features ✨

- Anzeige der neuesten Kinofilme
- Detaillierte Informationen zu jedem Film (Titel, Beschreibung, Bewertung, Release-Datum etc.)
- Kommunikation mit der TheMovieDB API

## Voraussetzungen 📋

- [Node.js](https://nodejs.org/) (v12 oder höher)
- Ein [TheMovieDB API](https://www.themoviedb.org/) Konto und ein API-Key (kostenlos)

## Installation 🚀

1. **Abhängigkeiten installieren:**

   ```bash
   npm install
   ```

2. **TheMovieDB API-Key einrichten:**

   - Gehe zu [TheMovieDB](https://www.themoviedb.org/).
   - Erstelle ein kostenloses Konto und gehe zu den Einstellungen, um deinen API-Key zu generieren.

3. **Umgebungsvariablen konfigurieren:**

   Erstelle eine `.env`-Datei im Hauptverzeichnis der App und füge deinen API-Key hinzu:

   ```bash
   REACT_APP_API_KEY=dein-api-key
   ```

   - Ersetze `dein-api-key` mit dem API-Key, den du von TheMovieDB erhalten hast.

## Ausführung der App 🏃‍♂️

1. **App starten:**

   ```bash
   npm start
   ```

2. **App öffnen:**

   Öffne deinen Browser und gehe zu [http://localhost:3000](http://localhost:3000), um die App zu sehen.

## Technologien 🛠️

- **Frontend**: React, Axios, TailwindCSS
- **API**: [TheMovieDB API](https://www.themoviedb.org/documentation/api)
