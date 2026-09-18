# Data

Raw and processed datasets for race season coverage.

## Subdirectories

| Path | Contents |
|---|---|
| `telemetry/` | GPS traces, acceleration data (lateral/longitudinal/vertical g), braking & throttle traces |
| `race-results/` | Official finishing order, sector times, gap charts, lap-by-lap data |
| `driver-metrics/` | Driver physical performance data — neck strength, HR, core fatigue indices, reaction time tests |

## Data Dictionary

### Telemetry Fields

| Field | Unit | Description |
|---|---|---|
| `lat_g` | g | Lateral acceleration (positive = right, negative = left) |
| `long_g` | g | Longitudinal acceleration (positive = acceleration, negative = braking) |
| `vert_g` | g | Vertical acceleration (positive = compression, negative = extension) |
| `speed_kmh` | km/h | Vehicle speed |
| `throttle_pct` | % | Throttle position (0–100) |
| `brake_pct` | % | Brake pressure (0–100) |
| `steering_angle` | degrees | Front wheel angle |
| `lap_time` | s | Sector or lap time |

### Driver Metrics Fields

| Field | Unit | Description |
|---|---|---|
| `neck_flex_strength` | N | Maximum sustainable neck flexion force |
| `heart_rate_max` | bpm | Peak heart rate during race segment |
| `core_fatigue_index` | 0–100 | Perceived core exertion scale |
| `reaction_time` | ms | Brake reaction from signal to application |

## Sources & Licensing

- **Telemetry:** Supplied by teams under editorial agreement; not for redistribution
- **Race results:** Official series data, licensed for editorial use
- **Driver metrics:** Medical/fitness data obtained with driver consent
- **G-force reference:** Wikipedia / NASA human tolerance studies

## Processing Notes

- Telemetry files are CSVs with 100 Hz sample rate
- G-values are raw accelerometer output, already filtered for noise
- Sector times are GPS-validated to ±0.01s
- All datasets include a `metadata.json` with collection date, source, and methodology
