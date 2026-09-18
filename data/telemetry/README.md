# Telemetry Data

GPS and acceleration data per lap per driver.

## Files

- `*.gpx` — GPS traces
- `*.csv` — Channel data (lateral G, longitudinal G, brake pressure, throttle %)
- `*.json` — Lap metadata (driver, car, session, date)

## Key Columns

| Column | Unit | Description |
|---|---|---|
| time | s | Timestamp |
| lat_g | g | Lateral G-load |
| lon_g | g | Longitudinal G-load |
| speed | km/h | Vehicle speed |
| brake | % | Brake pressure |
| throttle | % | Throttle position |
