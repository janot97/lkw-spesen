# Lkw Spesen & Arbeitszeit – Android-App

Die App wird als Android-WebView-App gebaut. Ihre Einträge liegen im lokalen, app-eigenen WebView-Speicher und sind unabhängig vom Chrome-Speicher.

## Build
GitHub Actions baut bei jedem Push auf `main` eine Debug-APK. Das APK-Artefakt heißt `Lkw-Spesen-APK`.

Die JSON-Sicherung wird in den Download-Ordner geschrieben; die Wiederherstellung öffnet die Android-Dateiauswahl.
