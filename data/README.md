# Data & Telemetry 📊

This directory stores raw and processed datasets supporting technical analysis for race season coverage — including G-force references for cornering physics articles.

## Structure

```
data/
├── README.md                      # This file — data dictionary, sources & licensing
├── telemetry/                     # High-frequency raw sensor data
│   ├── gps-tracks/                # GPS position logs (circuit tracing)
│   ├── acceleration/              # 3-axis accelerometer data (x, y, z channels)
│   │   └── lat-g/                 # Lateral G-channel (cornering loads)
│   │   └── long-g/                # Longitudinal G-channel (braking/accel)
│   │   └── vert-g/                # Vertical G-channel (curb strikes, jumps)
│   ├── braking/                   # Brake pressure, deceleration rates
│   └── throttle/                  # Throttle application maps
├── race-results/                  # Official and provisional classifications
│   ├── sector-times/              # Sector splits per driver per session
│   ├── official-results/          # FIA/series official classification sheets
│   └── lap-charts/                # Position-by-lap data, pit stop windows
└── driver-metrics/                # Physical & performance data
    ├── physical-fitness/          # Neck strength, G-tolerance test results
    ├── reaction-time/             # Cognitive response measurements
    └── biometrics/                # Heart rate, core temperature (where available)
```

## Data Dictionary

### Telemetry Channels
| Field | Unit | Description | Notes |
|-------|------|-------------|-------|
| `lateral_g` | g | **Lateral acceleration through corners** | Key channel for cornering physics article |
| `longitudinal_g` | g | Braking/acceleration along track axis | Positive = braking; negative = accel |
| `vertical_g` | g | Up-down acceleration | ~1 g at rest; spikes from curbs/jumps |
| `speed` | km/h | Vehicle speed at sample point | GPS-derived |
| `throttle_pos` | % | Throttle position | 0–100 |
| `brake_pressure` | bar | Brake apply pressure | Not % of max |
| `lat_g_peak` | g | **Highest lateral G-load recorded** | Reference for cornering-physics md |
| `avg_lateral_g` | g | Average lateral G-load for stint | Useful for race debriefs |

### Race Results
| Field | Unit | Description |
|-------|------|-------------|
| `position` | — | Finishing position |
| `gap_winner` | s | Time gap to race winner |
| `sector_1_2_3` | s | Individual sector times |

### Driver Physiological Metrics
| Field | Unit | Description |
|-------|------|-------------|
| `peak_lateral_g` | g | Highest lateral G-load recorded |
| `avg_lateral_g` | g | Average lateral G-load for the stint |
| `neck_strain` | N | Estimated neck muscle force (where available) |
| `g_tolerance_sustained` | g | Practical sustained limit per driver |
| `reaction_time_ms` | ms | Brake reaction latency |
| `heart_rate_bpm` | bpm | Peak race heart rate (typically 160+) |

## Key Physics Constants (from Wikipedia — G-force)

| Constant | Value | Usage |
|----------|-------|-------|
| Standard gravity (*g₀*) | **9.80665 m/s²** | Convert G-force to m/s² |
| 1 g in km/h per second | **≈ 35.3 km/h** | Quick mental math for braking/accel |
| Negative g tolerance | **−2 to −3 g₀** | Red-out threshold |
| Human g-LOC threshold | **~5 g₀** (untrained, vertical) | Vision loss risk |
| Sustained limit (trained) | **9 g₀** with g-suits | Pilot/racing reference |
| Record crash survival | **214 g₀** peak | Bräck, 2003 IndyCar Texas |

## Sources

- **Official FIA timing data** — Timing & Scoring, sector times
- **Team telemetry** (with permission) — Under embargo agreements
- **Wikipedia G-force article** — Physics constants, human tolerance data, historical records
- **NASA g-tolerance research** — Human centrifuge studies & High-G training literature
- **FIA-mandated ADRs** — Accident data recorder channels

## Licensing

All datasets in this folder are for editorial use within the race season coverage project. Proper citation is required for any external data. Driver biometrics are sensitive — handle in accordance with team privacy policies and GDPR where applicable.

## Quality Control Checklist

- [ ] Validate all CSV files have **consistent column headers** across sessions
- [ ] Cross-reference Lap 1 times against **official flags and penalties**
- [ ] **Flag any `lateral_g` readings above 5 g** or below **−3 g** for manual review
- [ ] Resolve **timestamp discrepancies** against official timing feeds
- [ ] Verify **biometric data** handling per GDPR and team policies
- [ ] Cross-reference peak lateral-g values against `articles/technical-notes/cornering-physics.md`
