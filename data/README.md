# Data

This folder stores raw and processed datasets supporting technical analysis.

## Structure

```
data/
├── README.md                  ← Data dictionary & sources
├── telemetry/
│   ├── gps-tracks/            ← GPS position logs (circuit tracing)
│   ├── acceleration/          ← 3-axis accelerometer data (x, y, z)
│   ├── braking/               ← Brake pressure, deceleration rates
│   └── throttle/              ← Throttle application maps
├── race-results/
│   ├── sector-times/          ← Sector splits per driver per session
│   ├── official-results/      ← FIA/series official classification
│   └── lap-charts/            ← Position-by-lap data
└── driver-metrics/
    ├── physical-fitness/      ← Neck strength, G-tolerance test results
    ├── reaction-time/         ← Cognitive response measurements
    └── biometrics/            ← Heart rate, core temperature (where available)
```

## Data Dictionary

| Field | Unit | Description |
|---|---|---|
| `lateral_g` | g | Side-to-side acceleration; positive = right, negative = left |
| `longitudinal_g` | g | Fore-aft acceleration; positive = braking, negative = acceleration |
| `vertical_g` | g | Up-down acceleration; always ~1 g at rest |
| `speed_kmh` | km/h | Instantaneous speed |
| `throttle_pct` | % | Throttle position (0–100) |
| `brake_pct` | % | Brake pedal pressure (0–100) |
| `lat_g_peak` | g | Maximum lateral g recorded for the lap |
| `sector_time` | s.mmm | Sector split time (minutes.seconds milliseconds) |

## Sources

- **Telemetry:** Provided by teams under embargoes; timing data from FIA stewards.
- **Public datasets:**可在F1官网, IndyCar data portal, and official series websites找到.
- **Research references:** NASA g-tolerance studies, military aviation human-factors literature.
- **Ethical use:** Driver biometrics are sensitive — handle in accordance with team privacy policies and GDPR where applicable.
