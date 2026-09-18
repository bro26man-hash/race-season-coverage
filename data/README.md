# Data

Raw and processed datasets for race season coverage.

## Subdirectories

| Path | Purpose |
|---|---|
| `telemetry/` | GPS traces, acceleration (longitudinal & lateral), braking and throttle traces |
| `race-results/` | Official classifications, sector times, gap charts |
| `driver-metrics/` | Physical & performance data — heart rate, neck strain estimates, reaction times |

## Data Dictionary

### Telemetry Files

| Column | Unit | Description |
|---|---|---|
| `timestamp` | ms | Lap-clock relative time |
| `speed` | km/h | Vehicle speed |
| `lat_accel` | g | Lateral acceleration (cornering G-load) |
| `lon_accel` | g | Longitudinal acceleration (braking/throttle) |
| ` throttle_pos` | % | Throttle opening |
| `brake_pressure` | bar | Brake pedal pressure |
| `steering_angle` | degrees | Front wheel angle |

### Key Formulas

- **Centripetal acceleration:** a = v² / r (where v = speed, r = corner radius)
- **Braking G-force:** a = v² / (2 × s) (constant deceleration over distance s)
- **Total G-load:** √(lat² + lon² + 1²) — vector sum including gravity

## Sources & Licensing

- Telemetry: Official FIA/F1 broadcasts, team data (subject to NDA)
- Race results: Official timing provider publications
- Driver metrics: Published interviews, physiological studies, team communications
