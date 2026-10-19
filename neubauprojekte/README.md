# Neubauprojekte Kanton Zürich (CSV)

Wie viele Wohnungen im Kanton Zürich geplant, bewilligt und im Bau sind, pro Gemeinde und pro Stadtkreis der Stadt
Zürich. Aufbereitet von [Genossenschaftsscout](https://www.genossenschaftsscout.ch/neubauten-zuerich), jeden Monat neu.

| Datei | Inhalt |
|---|---|
| [`gemeinden.csv`](gemeinden.csv) | eine Zeile pro Gemeinde mit mindestens einem Projekt |
| [`stadt-zuerich-kreise.csv`](stadt-zuerich-kreise.csv) | eine Zeile pro Stadtkreis der Stadt Zürich |
| [`verlauf-kanton.csv`](verlauf-kanton.csv) | Kantonssumme, eine Zeile pro Monat (ab Oktober 2026) |

## Spalten

| Spalte | Bedeutung |
|---|---|
| `stand` | Stand des Gebäude- und Wohnungsregisters (JJJJ-MM-TT) |
| `bfs_nr`, `gemeinde` / `kreis` / `monat` | Gebiet bzw. Monat |
| `projekte`, `wohnungen` | Wohnbauprojekte ab 10 Wohnungen, die geplant, bewilligt oder im Bau sind, und ihre Wohnungen |
| `projekte_geplant`, `wohnungen_geplant` | Baugesuch eingereicht (Register: projektiert) |
| `projekte_bewilligt`, `wohnungen_bewilligt` | Baubewilligung erteilt, noch nicht im Bau |
| `projekte_im_bau`, `wohnungen_im_bau` | im Bau |

Ein Projekt fasst Gebäude zusammen, die zusammengehören (gleiche Parzelle oder direkt nebeneinander). Fertige Häuser
zählen nicht mehr.

## Quelle und Lizenz

Grundlage: Bundesamt für Statistik, Eidgenössisches Gebäude- und Wohnungsregister (GWR), https://www.housing-stat.ch/.
Aufbereitung: Genossenschaftsscout, [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Bei Verwendung bitte beide nennen: „Quelle: BFS, GWR;
Aufbereitung: Genossenschaftsscout (https://www.genossenschaftsscout.ch/neubauten-zuerich)“.
