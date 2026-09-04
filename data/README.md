# Data

Structured datasets, telemetry extracts, and analytics for race-season coverage.

## Structure

- `telemetry/` — Lap-by-lap timing, sector splits, speed trap data
- `analytics/` — Cornering-g profiles, tire-degradation models, fuel-consumption analysis
- `references/` — Bibliography, source links, fact-check logs

## Guidelines

- All datasets should include a `README.md` describing fields, units, and collection methodology.
- Prefer open formats: CSV, JSON, Parquet.
- Telemetry data should be time-synced and labeled with track sector boundaries.
- Statistical summaries should include sample sizes and confidence intervals where applicable.