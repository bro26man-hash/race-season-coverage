# Multimedia Assets 🎥📷

This directory houses all visual and audio media content for race season coverage, organized by type and purpose.

## Structure

```
multimedia/
├── README.md                     # This file — asset catalog & usage notes
├── images/                       # Photography, diagrams, telemetry screenshots
│   ├── circuit-maps/             # Track layouts, satellite imagery, corner numbering
│   ├── telemetry-screenshots/    # Acceleration plots, g-load graphs, throttle traces
│   ├── photography/              # Race action, portraits, detail shots, livery captures
│   └── diagrams/                 # Technical illustrations, force diagrams, aero maps
├── video/                        # Interview clips, onboard footage, analysis pieces
│   ├── onboard/                  # Onboard camera references with timestamps
│   ├── interviews/               # Driver/team interview clips, press excerpts
│   └── analysis/                 # Telestrations, tweet-length breakdowns, corner walks
└── graphics/                     # Data visualizations, G-load plots, circuit maps
    ├── g-load-plots/             # Lateral/longitudinal g-over-time charts
    ├── sector-maps/              # Sector time comparisons, heat maps, apex tracking
    └── data-visualizations/      # Championship standings, trend lines, downforce vs drag
```

## Asset Categories

| Folder | Content | Examples |
|-------|---------|---------|
| `images/` | Photos, diagrams, screenshots | Driver portraits, car profiles, telemetry overlays |
| `video/` | Interview clips, onboard footage | Driver reactions, cornering onboard laps |
| `graphics/` | Data visualizations, maps | G-load plots through corners, speed maps, sector comparison charts |

## Naming Convention

Use the pattern: `[series]_[circuit]_[topic]_[version].[ext]`

- Example: `F1_Monaco_cornering-G-load_v2.png`
- Example: `INDY_T，兴ds上的_schumacher_onboard_v1.mp4`

## G-Force Graphics Standards

All g-load plots must:
- Clearly label axes: **g-force [g] vs. time [s]**
- Mark **corner entries and exits** with vertical guide lines
- Use **color coding**: green for sustainable loads, red for peak/breakaway thresholds
- Include **driver name, session, and circuit** in the chart title
- Reference the corresponding data file path in `../data/telemetry/acceleration/`

## File Formats & Resolution

| Type | Format | Resolution | Notes |
|------|--------|-----------|-------|
| Photos | JPEG/PNG/TIFF | Min 1920×1080 | Lossless (PNG/TIFF) for charts |
| Video | H.264 MP4 | 1080p minimum | Onboard: 60fps+ preferred |
| Diagrams | SVG preferred | 300 DPI min (PNG) | Scalable for print features |
| G-plots | PNG (transparent) | 1200×800 min | BBC/collection style |

## Credits & Licensing

- **Team-provided assets**: © respective teams — always credit.
- **Original work**: © Race Season Coverage publication.
- **Third-party**: Do not use without explicit written permission.
- **Telemetry screenshots**: Often embargoed — verify with the data provider before publishing.
- **Track all image sources and licensing** in file metadata.
- **For data visualizations**, cite the dataset source in the graphic footer.
- **Prefer original photography** where possible.
