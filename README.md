# Silizium-Streifenzähler – Fortgeschrittenenpraktikum BUW

Dieses Repository enthält die Messdaten und Analyseskripte zum Versuch **„Siliziumstreifendetektor“** im Fortgeschrittenenpraktikum.

## Ordnerstruktur

- `analysis/`
  - `scripts/` → Python-Skripte (z. B. Charge_Analysis.py)
  - `notebooks/` → Platz für interaktive Jupyter-Notebooks
  - `plots/` → generierte Abbildungen
- `data/`
  - `pedestal/` → Noise-Messungen bei verschiedenen Spannungen
  - `latency/` → Latency-Scans mit unterschiedlichen Parametern
  - `mip/` → Runs zur Energie von Minimal Ionisierenden Teilchen
  - `depletion/` → Runs für Verarmungszonen-Messungen
  - `calib/`, `calib_charge/`, `delay_calib/`, `charge_*` → Kalibrationsdateien
- `doc/` → Versuchsanleitungen, Paper, Notizen
- `results/` → finale Plots und Tabellen

## Inhalt

- **Pedestal-Runs:** Rauschmessungen in Abhängigkeit von der Spannung
- **Latency:** Bestimmung der optimalen Latenz-Einstellung
- **MIP:** Energieverteilung von minimal ionisierenden Teilchen
- **Depletion:** Dicke der Verarmungszone in Abhängigkeit von der Spannung
- **Calibration:** Delay-Scan und Ladungskalibration

## Nutzung

```bash
git clone git@github.com:nanare-sudo/Silizium-Streifenzaehler.git
