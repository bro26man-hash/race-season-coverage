# Multimedia

All visual and audio assets for race season coverage.

## Subdirectories

| Path | Contents |
|---|---|
| `images/` | Photography, technical diagrams, telemetry screenshots, cornering sequence shots |
| `video/` | Interview clips, onboard footage references, highlight reels |
| `graphics/` | Data visualizations, G-load plots, circuit maps, speed traces |

## Asset Naming Convention

```
[season]-[round]-[subject]_[variant].[ext]
Example: 2026-r3-monza-cornering-gload-v2.jpg
```

## Technical Overlays

When annotating images or video, include:
- **G-values** at key moments (e.g., "4.2 g lateral at apex")
- **Speed** at entry, apex, and exit
- **Throttle/brake percentages** whereavailable
- **Driver line** with apex and track limits marked

## Data Visualization Standards

- G-load plots: Y-axis in g, X-axis in time or distance
- Color-code: lateral (blue), longitudinal (red), vertical (green)
- Always annotate peak values and their location on track
- Cite data source from `data/telemetry/`

## Licensing & Credits

- Original photography: © Race Season Coverage / [your byline]
- Telemetry data: Provided by series organizers / team partnerships
- Derived graphics: Credit the dataset in `data/`
