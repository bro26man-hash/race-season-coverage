# Data

This folder contains raw and processed datasets for race season coverage.

## Structure

```
data/
├── README.md              ← This file (data dictionary & sources)
├── telemetry/             ← GPS, acceleration, braking data
├── race-results/          ← Official results, sector times
└── driver-metrics/        ← Physical & performance data
```

## Data Dictionary

### Telemetry
| Field | Unit | Description |
|---|---|---|
| `lateral_g` | g | Lateral acceleration through corners |
| `longitudinal_g` | g | Braking/acceleration along the track axis |
| `speed` | km/h | Vehicle speed at sample point |
| `throttle_pos` | % | Throttle position |
| `brake_pressure` | bar | Brake apply pressure |

### Race Results
| Field | Unit | Description |
|---|---|---|
| `position` | — | Finishing position |
| `gap_winner` | s | Time gap to race winner |
| `sector_1_2_3` | s | Individual sector times |

### Driver Metrics
| Field | Unit | Description |
|---|---|---|
| `peak_lateral_g` | g | Highest lateral G-load recorded |
| `avg_lateral_g` | g | Average lateral G-load for the stint |
| `neck_strain` | N | Estimated neck muscle force (where available) |

## Sources

- Official FIA timing data
- Team telemetry (with permission)
- Wikipedia G-force article for physics constants

## Licensing

All datasets in this folder are for editorial use within the race season coverage project. Proper citation is required for any external data.
