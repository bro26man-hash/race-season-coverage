# Data

Raw and processed datasets for race season coverage.

## Subdirectories

| Path | Purpose |
|---|---|
| `telemetry/` | GPS tracks, acceleration (g-load) data, braking points, throttle/brake traces |
| `race-results/` | Official classifications, sector times, pit stop data, DRS activation logs |
| `driver-metrics/` | Physical performance data, heart rate, g-tolerance assessments, reaction time tests |

## Data Dictionary

### Telemetry Files

| Field | Unit | Description |
|---|---|---|
| `lat_g` | g₀ | Lateral g-load (cornering) |
| `long_g` | g₀ | Longitudinal g-load (braking/acceleration) |
| `vert_g` | g₀ | Vertical g-load (downforce + road surface) |
| `speed` | km/h | Vehicle speed at sensor sample |
| `throttle_pos` | % | Throttle position (0–100) |
| `brake_pressure` | bar | Brake pedal pressure |
| `steering_angle` | degrees | Steering wheel angle |
| `lat_accel` | m/s² | Raw lateral acceleration (before g-conversion) |

### Race Results Files

| Field | Unit | Description |
|---|---|---|
| `sector_time` | seconds | Individual sector time |
| `gap_to_leader` | seconds | Gap to fastest time in session |
| `pit_stop_time` | seconds | Total pit stop duration (in/out + service) |
| `drs_activated` | bool | Whether DRS was deployed in sector |

### Driver Metrics Files

| Field | Unit | Description |
|---|---|---|
| `peak_lat_g` | g₀ | Maximum lateral g experienced |
| `sustained_lat_g_avg` | g₀ | Average lateral g over longest corner |
| `heart_rate_max` | bpm | Peak heart rate during race |
| `g_loc_events` | count | Number of g-induced awareness moments (if recorded) |

## Sources

- Team-issued telemetry (via official channels)
- FIA timing data
- Onboard camera g-logging systems
- Wearable driver biometric sensors (where permitted)

## Licensing

All telemetry data is subject to team and series regulations. Do not redistribute raw team telemetry without explicit permission. Processed/aggregated data may be published under **CC-BY-SA 4.0**.
