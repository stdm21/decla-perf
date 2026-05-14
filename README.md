# Decla — Perf acquisition client

Static dashboard published at <https://stdm21.github.io/decla-perf/>.

- `index.html` — Chart.js bar charts (8 dernières semaines + YTD vs budget +26,5%)
- `data.json` — données régénérées quotidiennement à 8:07 Paris par `~/.openclaw/workspace/scripts/decla-mtd/daily.py` puis poussées ici par `run_and_send.sh`
- Source des données : `lmnp.decla.fr/dashboard_lmnp_stats.php?mode=day&format=csv`

Métrique = `Premiers paiements LMNP` (1ers paiements clients).
