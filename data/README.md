# Data

Raw and processed datasets for race season coverage.

## Structure

```
data/
├── telemetry/      ← GPS, acceleration, braking data
├── race-results/   ← Official results, sector times
└── driver-metrics/ ← Physical & performance data
```

## Data Dictionary

### Telemetry
| Field | Unit | Description |
|---|---|---|
| `lat_g` | g | Lateral G-load at each sampling point |
| `lon_g` | g | Longitudinal G-load (brake/accel) |
| `speed_kmh` | km/h | Instantaneous speed |
| `brake_pressure` | bar | Brake pedal pressure |
| `throttle_pos` | % | Throttle position |
| `steering_angle` | deg | Steering wheel angle |

### Race Results
| Field | Unit | Description |
|---|---|---|
| `position` | — | Finishing position |
| `gap_to_p1` | s | Gap to pole position |
| `sector_times` | s | Split times per sector |
| `pit_loss` | s | Total pit stop time loss |

### Driver Metrics
| Field | Unit | Description |
|---|---|---|
| `peak_lat_g` | g | Peak lateral G-load for session |
| `avg_brake_g` | g | Average braking G-force |
| `neck_strain` | N Estimated cervical spine load |
| `heart_rate_max` | bpm Peak heart rate |

## Sources

- FIA timing & scoring data
- Onboard camera telemetry (OEM-provided)
- GPS data from Team GPS loggers
- Driver biometric data (where available)

## Licensing

All data is used under FIA rights holder agreements. Redistribution prohibited without written consent.
