# Schach Lern-App

Vollstaendige statische PWA ohne Build-Schritt. Enthalten: Schachregeln, Zuganzeige, Schach/Schachmatt/Patt, Rochade, en passant, Damenumwandlung, drei Computerstufen, 10 interaktive Aufgaben, Lernkarten, XP und lokaler Fortschritt.

## GitHub Pages
1. Neues GitHub-Repository erstellen, z. B. `schach-lern-app`.
2. Den INHALT dieser ZIP ins Root des Repository hochladen. `index.html` muss direkt im Root liegen.
3. GitHub: Settings > Pages > Build and deployment > Source: Deploy from a branch.
4. Branch `main`, Ordner `/(root)` waehlen und Save.
5. Nach der Veroeffentlichung die GitHub-Pages-Adresse aufrufen.

Alle Asset-Pfade sind relativ, damit die App auch unter `/schach-lern-app/` funktioniert. Service Worker und Manifest benutzen ebenfalls relative Pfade.
