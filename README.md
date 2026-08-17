# PKV-Beitragsrechner für Beamte (Thüringen)

Interaktiver Vergleich von vier privaten Krankenversicherungsangeboten für einen
beihilfeberechtigten Beamten in Thüringen — Bemessungssatz 50 %, Eintrittsalter 37,
Versicherungsbeginn Oktober 2026.

**→ [Rechner öffnen](https://stephanteege.github.io/PKV/)** (nach Aktivierung von GitHub Pages)

## Was der Rechner kann

- **Bausteine an- und abwählen** — stationäre Wahlleistungen, Beihilfeergänzung,
  Krankenhaus- und Kurtagegeld, Selbstbehalt. Die Beiträge rechnen live mit.
- **Risikozuschlag ein- und ausblenden.** Das ist der eigentliche Befund: Ohne Zuschlag
  liegen drei der vier Angebote innerhalb von 6,16 €, mit Zuschlag klaffen sie um 96,82 €
  auseinander. Der Preisunterschied ist fast vollständig die Risikobewertung, nicht der Tarif.
- **Langfristrechnung** mit frei einstellbarer Beitragsanpassung je Anbieter. Rechnet aus,
  wie viel schneller der heute günstigere Tarif steigen darf, bevor er den Vorsprung verliert.
- **Leistungsvergleich** über 19 Kriterien, alle vier Anbieter benotet.

## Verglichene Angebote

| Anbieter | Tarife | Beitrag* | Risikozuschlag |
|---|---|---|---|
| Bayerische Beamtenkrankenkasse | BeihilfeCOMFORT 30 / 20k SB | 398,12 € | 4,4 % |
| Signal Iduna | EXKLUSIV-B 30 / 20V | 414,11 € | 10,0 % |
| Debeka | B30 / B20K / WL / BC | 494,94 € | 30,0 % |
| Allianz | BHA51 / BHK51 / BHZ51 / BHEB | 512,58 € | 19,2 % |

\* mit stationären Wahlleistungen und Beihilfeergänzung, ohne Krankenhaus- und Kurtagegeld,
bei der Bayerischen mit Selbstbehalt. Alle Werte im Rechner einstellbar.

## Leistungsnoten (19 Kriterien, Skala 0–5)

Bayerische 3,9 · Signal Iduna 3,8 · Allianz 3,8 · Debeka 3,1

Die Skala ist kalibriert: Über dieselben 19 Kriterien gemittelt kommt Signal Iduna auf 3,81 —
exakt die Gesamtnote aus dem zugrundeliegenden Maklervergleich.

## Technisches

Eine einzelne, in sich geschlossene HTML-Datei. Kein Build, keine Abhängigkeiten, kein
Tracking, keine externen Requests. Läuft genauso per Doppelklick wie über GitHub Pages.
Hell- und Dunkelmodus, responsiv.

### GitHub Pages aktivieren

Settings → Pages → Source: *Deploy from a branch* → Branch: `main`, Ordner `/ (root)` → Save.
Die Datei `.nojekyll` sorgt dafür, dass GitHub die Seite unverändert ausliefert.

## Hinweis

Aufbereitung konkreter Angebotsunterlagen, keine Versicherungsberatung. Beiträge, Zuschläge
und Leistungsangaben gelten für dieses eine Profil und lassen sich nicht auf andere Personen
übertragen. Die Leistungsnoten für die Bayerische und Debeka sind eine eigene Einschätzung
auf Basis der Tarifbedingungen bzw. öffentlicher Bedingungsanalysen.

Stand: August 2026
