# Genossenschafts-Mietindex Zürich (CSV)

Quartalszahlen zu ausgeschriebenen Wohnungen von Genossenschaften, Stiftungen und Gemeinden, erfasst von
[Genossenschaftsscout](https://www.genossenschaftsscout.ch/genossenschafts-mietindex). Eine Datei pro Gebiet, jedes Quartal neu.

| Datei | Gebiet | Seite |
|---|---|---|
| [`stadt-zuerich.csv`](stadt-zuerich.csv) | Stadt Zürich | [https://www.genossenschaftsscout.ch/mietindex/stadt-zuerich](https://www.genossenschaftsscout.ch/mietindex/stadt-zuerich) |
| [`winterthur.csv`](winterthur.csv) | Winterthur | [https://www.genossenschaftsscout.ch/mietindex/winterthur](https://www.genossenschaftsscout.ch/mietindex/winterthur) |

## Spalten

| Spalte | Bedeutung |
|---|---|
| `quartal`, `von`, `bis` | Kalenderquartal (z. B. `2026-Q3`, 2026-07-01 bis 2026-09-30) |
| `inserate` | ausgeschriebene Wohnungen im Quartal, jede Wohnung einmal gezählt |
| `mieten` | davon mit plausibler Monatsmiete (CHF 200 bis 6'500) |
| `median_miete_chf` | mittlere Monatsmiete (Median) laut Inserat, leer bei weniger als 10 Mieten |
| `median_1_bis_2_5_zimmer_chf` … `median_ab_5_zimmer_chf` | Median je Zimmerklasse, leer bei weniger als 10 Mieten |
| `median_chf_pro_m2` | Median der Monatsmiete pro m² Wohnfläche, leer bei weniger als 20 Inseraten mit Fläche |
| `inserate_mit_flaeche` | Inserate mit Flächenangabe (Grundlage für pro m²) |

Die Zahlen zeigen das öffentlich ausgeschriebene Angebot, nicht den ganzen Bestand: Viele Genossenschaften vergeben
Wohnungen auch über Wartelisten oder an ihre Mitglieder. Die Mieten hängen stark davon ab, welche Siedlungen gerade
frei werden; Veränderungen zwischen Quartalen zeigen darum auch einen anderen Mix der Vermieterinnen.

## Lizenz

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/): frei verwendbar mit der Quellenangabe „Genossenschaftsscout“ und einem Link auf
https://www.genossenschaftsscout.ch/genossenschafts-mietindex.
