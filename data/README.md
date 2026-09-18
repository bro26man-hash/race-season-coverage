# Data

Raw and processed datasets for race season analysis.

## Subdirectories

- **`telemetry/`** — GPS traces, acceleration (longitudinal & lateral g), braking and throttle traces
- **`race-results/`** — Official results, sector times, pit stop data
- **`driver-metrics/`** — Physical & performance data (heart rate, neck strain estimates, reaction times)

## Data Dictionary

| Field | Unit | Description |
|---|---|---|
| `lateral_g` | g₀ | Peak/corner lateral acceleration |
| `longitudinal_g` | g₀ | Braking/acceleration along the track axis |
| `speed` | km/h | Vehicle speed at telemetry sample point |
| `throttle_pos` | % | Throttle opening percentage |
| `brake_pressure` | bar | Brake pedal pressure |
| `steering_angle` | degrees | Steering wheel angle |

## Sources & Licensing

- **Official timing data**: FIA / series organizerprovided
- **Telemetry**: Team-authorized, credited per dataset
- **Wikipedia reference**: For physics constants and background, see `articles/technical-notes/cornering-physics.md`
