# Pruebas-workflows

Prueba del workflow de monitoreo de estabilidad de data-api.binance.vision (ticket #2).

- `scripts/monitor_binance_stability.py` — un chequeo por corrida, apenda a `data/binance_stability_log.csv`
- `scripts/analyze_binance_stability.py` — analiza el log acumulado y da el veredicto de estabilidad
- `.github/workflows/monitor-binance-stability.yml` — corre el chequeo cada 2hs
- `.github/workflows/binance-stability-report.yml` — dispara el análisis a mano desde Actions
