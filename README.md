# Krankenhausatlas Bayern

**Version 0.05** – eigenständige, offlinefähige HTML-Anwendung für GitHub Pages.

## Daten

Quelle: öffentliches InEK/GKV-Standortverzeichnis, vollständiger XML-Abruf vom **17.07.2026**; Bundesland **09 (Bayern)**, Einrichtungstyp **00 (stationäre Behandlung)**. Berücksichtigt wurden zum Stichtag gültige Standort- und Einrichtungsdatensätze. Historische Versionen wurden je Kombination aus Haupt-IK, Standortnummer und Abrechnungs-IK zusammengeführt.

- **442** Standort-/Abrechnungs-Einträge
- **313** verschiedene Haupt-IK
- Betriebsstättennummer `999999999` wird als „nicht angegeben“ angezeigt; der Quellwert bleibt in den Daten enthalten.

## Bedienung

Suche, Filter nach Trägerart, Gruppierung nach Haupt-IK, Spaltensortierung und direktes Verschieben der Spaltenköpfe per Drag-and-drop (Touch/Maus). Unter „Spalten anpassen“ werden Spalten ein- oder ausgeblendet. CSV-Export und lokale Speicherung der Anzeigeeinstellungen.

## Veröffentlichung

GitHub → **Settings → Pages** → **Deploy from a branch** → **main** / **/(root)** → Save.

Die Seite benötigt keine externen Bibliotheken. Alle Daten sind in `index.html` enthalten.
