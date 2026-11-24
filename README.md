# Anhörung: Wie erzeugen wir künftig unseren Strom?

Eine Unterrichtssimulation für die Oberstufe. Die Schülerinnen und Schüler sind Abgeordnete im Ausschuss für Wirtschaft und Energie. Sie befragen 13 erfundene Sachverständige aus Energiewirtschaft, Netzbetrieb, Gewerkschaften, Verbraucherschutz, Wissenschaft, Umweltverband und einer Bürgerinitiative. Am Ende schreiben sie eine Handlungsempfehlung für das Parlament.

## So funktioniert es

- Jede Person hat ein Eingangsstatement und 5 bis 8 Fragen mit vorbereiteten Antworten.
- Manche Antworten schalten eine **Nachfrage** frei. Nur über diese Nachfragen erfahren die Schüler, was eine Person nicht von selbst erzählt, zum Beispiel den CO2-Ausstoß der Kohle oder die Gewinne der Netzbetreiber.
- Zahlen zu Kosten pro kWh, CO2 pro kWh und Anfahrzeiten kennen nur einige Personen. Den neutralen Gesamtüberblick hat die Wissenschaftlerin.
- Die Schüler können Notizen festhalten und das Protokoll als Textdatei herunterladen oder kopieren.

## Auf GitHub Pages veröffentlichen

1. Auf GitHub ein neues Repository anlegen, z. B. `anhoerung-strom`, Sichtbarkeit „Public“.
2. Die Dateien `index.html` und `README.md` hochladen („Add file“ → „Upload files“).
3. Unter „Settings“ → „Pages“ bei „Source“ den Branch `main` und den Ordner `/ (root)` wählen und speichern.
4. Nach ein bis zwei Minuten ist die Seite erreichbar unter `https://<benutzername>.github.io/anhoerung-strom/`.

Die Seite funktioniert auch ohne GitHub: `index.html` einfach im Browser öffnen, zum Beispiel vom USB-Stick oder aus einem Lernmanagementsystem.

## Datenschutz

- Die Seite lädt keine externen Inhalte (keine Schriften, Skripte oder Bilder von anderen Servern) und verwendet keine Cookies.
- Der Fortschritt und die Notizen werden nur im `localStorage` des jeweiligen Browsers gespeichert und nirgendwohin übertragen. Mit „Befragung neu beginnen“ werden sie für die gewählte Person gelöscht.
- Hinweis: GitHub Pages selbst protokolliert als Hoster technische Zugriffsdaten (z. B. IP-Adressen). Ob das für Ihre Schule zulässig ist, klären Sie bitte mit der Schulleitung oder dem Datenschutzbeauftragten. Alternativ die Datei lokal oder über den Schulserver bereitstellen.

## Inhalte anpassen

Alle Personen, Fragen und Antworten stehen im Skript am Ende von `index.html` in der Liste `E`. Jede Frage hat eine `id`, den Fragetext `f` und die Antwort `a`. `u` nennt die Nachfragen, die eine Antwort freischaltet; Nachfragen sind mit `l:1` markiert.

## Quellen der Zahlen

- Fraunhofer ISE: Stromgestehungskosten erneuerbare Energien, Juli 2024
- Umweltbundesamt: Umweltkosten der Stromerzeugung, Methodenkonvention 4.0, 2026
- CO2-Werte pro kWh: gerundete Bandbreiten nach IPCC und Umweltbundesamt
- Anfahrzeiten von Kraftwerken: nach Agora Energiewende

Alle Personen und Verbände sind erfunden. Die Positionen sind vereinfacht und an reale Verbände angelehnt. Stand der politischen Lage: November 2026.
