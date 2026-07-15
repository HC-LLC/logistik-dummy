# Projekt Logistik – Cube-Testumgebung (fiktive Dummy-Daten)

Vollständig fiktive Daten eines Logistikunternehmens (22 Fahrzeuge, davon 3 e-LKW,
10 Kunden, Touren 01.04.–14.07.2026). Kein Bezug zu realen Unternehmen.

## Inhalt
- `data/` – 5 CSV-Dateien (kunden, fahrzeuge, touren, offene_posten, werkstatt)
- `model/` – Cube-Datenmodell (YAML): 5 Cubes + 2 Views

## Abgedeckte KPIs
Cockpit: Umsatz/Tag · km/Tag · Eingesetzte Fahrzeuge · Offene Positionen · Fahrzeugverfügbarkeit
Detail: Umsatz pro Kunde (A/B/C)

## Wichtig vor Nutzung
In allen Dateien unter `model/cubes/` den Platzhalter
`DEIN_GITHUB_NAME` in den read_csv_auto-URLs durch den echten
GitHub-Benutzernamen/Repo-Pfad ersetzen.
