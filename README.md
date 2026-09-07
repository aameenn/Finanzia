# Finanzia — Landingpage

Eigenständige, einzelne HTML-Datei (`index.html`) — keine Abhängigkeiten, kein Build-Schritt nötig. Alle Bilder sind direkt eingebettet.

## Veröffentlichen mit GitHub Pages (kostenlos)

1. Dieses Repository auf GitHub erstellen (z. B. `finanzia-landingpage`) und diese Dateien hochladen (`index.html` muss so heißen, damit GitHub Pages sie automatisch als Startseite erkennt).
2. Im Repository: **Settings → Pages**.
3. Unter "Branch" den Branch `main` und Ordner `/ (root)` auswählen, dann **Save**.
4. Nach ein paar Minuten ist die Seite live unter `https://<dein-github-name>.github.io/<repo-name>/`.

## Eigene Domain verbinden (z. B. finanzia.de)

1. Bei deinem Domain-Anbieter (z. B. Strato, IONOS) einen `CNAME`-Eintrag anlegen, der auf `<dein-github-name>.github.io` zeigt (bei einer Subdomain wie `www`) — für die nackte Domain (`finanzia.de` ohne www) stattdessen die von GitHub vorgegebenen `A`-Records eintragen (siehe [GitHub-Anleitung](https://docs.github.com/pages/configuring-a-custom-domain-for-your-github-pages-site)).
2. Im Repository unter **Settings → Pages → Custom domain** die Domain eintragen und speichern.
3. "Enforce HTTPS" aktivieren, sobald verfügbar (kann etwas dauern, bis das Zertifikat ausgestellt ist).

## Struktur

- `index.html` — die komplette Seite (HTML, CSS, JavaScript für den Sprachumschalter AR/DE, alle Bilder als Base64 eingebettet)
