# Sensus Penduduk 2010 — Interactive Dashboard

An interactive dashboard summarizing Indonesia's **2010 Population Census (Sensus Penduduk 2010 / SP2010)** full-count microdata — ~237.6 million person records across all 33 provinces.

🔗 **Live:** https://hengkykurniawan.github.io/sp2010-dashboard/

## What's inside

- **Population pyramid** — age × sex, 5-year bands
- **Religion** composition
- **Education** — highest certificate (age 15+)
- **Employment** — main-job industry sector
- **Urban vs rural** by island group
- **Province table** — population, % urban, mean age, sex ratio (sortable)

## Data

Aggregated from the SP2010 person-level microdata (questionnaire C1) using [DuckDB](https://duckdb.org). Only small pre-computed aggregate JSON files are published here — no individual records. Figures validate against published BPS totals (national 237.6M; e.g. Jawa Barat 43,053,732).

Source: Badan Pusat Statistik (BPS). Built with DuckDB + Chart.js.
