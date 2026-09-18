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

- **Official timing data**: FIA / series organizer provided
- **Telemetry**: Team-authorized, credited per dataset
- **Wikipedia reference (G-force)**: For physics constants and background, see `../articles/technical-notes/cornering-physics.md`
  - Key constants: 1 g = 9.80665 m/s²; ~35 km/h per second velocity change
  - Human tolerance: 5 g₀ untrained threshold; 9 g₀ trained sustained; 214 g₀ record (Bräck, 2003)
  - Cornering physics: a = v²/r; F_friction = μ × N; Downforce ∝ v²

## Connection to Articles

- `../articles/technical-notes/cornering-physics.md` — Full G-force reference covering lateral loads, centripetal acceleration, downforce, and driver demands
- `../articles/technical-breakdowns/` — Use telemetry traces for strategy analysis
- `../multimedia/graphics/` — Visualize data from this folder as charts & maps
