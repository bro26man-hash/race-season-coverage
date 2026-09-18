# Multimedia

All visual and audio assets for race season coverage.

## Structure

```
multimedia/
├── images/      ← Photography, diagrams, telemetry screenshots
├── video/       ← Interview clips, onboard footage references
└── graphics/    ← Data visualizations, G-load plots, circuit maps
```

## Asset Catalog

### Images
- Circuit aerials and corner diagrams
- Telemetry screenshots (speed, braking points, G-load traces)
- Driver portraits and pit lane action

### Video
- Onboard footage references (file names and timestamps)
- Interview clips with drivers and engineers
- Broadcast highlight reel extracts

### Graphics
- G-load plots per corner (lateral & longitudinal)
- Speed delta charts vs. reference lap
- Circuit maps with braking/acceleration zones

## Naming Convention

`[season]_[round]_[circuit]_[type]_[description].[ext]`

Example: `2025_R06_Monaco_image_corner3_ng-force.png`

## Usage Notes

- Compress images to ≤ 2 MB for web use; keep originals in `images/raw/`.
- Video refs are pointer files only — actual media stored in cloud CDN.
- All graphics must include data source attribution.
