# TYPO3-Projekt aus dem Zoominar am 06.08.2020

Die Sitepackage-Extension liegt im Verzeichnis Packages/

Sofern Du DDEV benutzt und das Projekt lokal starten willst, klone dir dieses Repository und führe ein

`ddev start`

aus, anschließend ein

`ddev composer install`

Um die Datenbank zu importieren:

`ddev import-db -f database.sql`

Backend starten:

`ddev launch /typo3`

Benutzername: admin
Passwort: password

Wenn du nur das Sitepackage möchtest, kannst Du dir entweder das Repository klonen oder als Zip runterladen:
https://github.com/wowaTYPO3/sitepackagezoominar/tags
