# Articles

Written coverage for the race season — race reports, technical breakdowns, driver profiles, and season summaries.

## Subdirectories

- **`race-reports/`** — Weekend-by-weekend race coverage and analysis
- **`technical-breakdowns/`** — Engineering, strategy, and aero package deep-dives
- **`driver-profiles/`** — In-depth driver and team profiles
- **`season-summaries/`** — Mid-season and end-of-season reviews
- **`technical-notes/`** — Physics & engineering reference notes
  - **`cornering-physics.md`** — Comprehensive G-force reference covering:
    - Lateral G-loads through corners (a = v²/r, dragster 5.3 g reference)
    - Centripetal acceleration & cornering mechanics (Newton's laws, friction model)
    - Role of downforce (normal force amplification, v² scaling, ground effect)
    - Physical demands on drivers (G-tolerance, grey-out progression, neck loads)
    - Key data table: 1 g = 9.80665 m/s², 5 g₀ untrained threshold, 214 g₀ record

## Style Guide

- **Tone**: Authoritative but accessible — technical depth for engaged readers
- **Define terms** on first use: e.g., "lateral G-load (side-to-side acceleration measured in g)"
- **Cite sources**: Link to `../data/` for telemetry and `../multimedia/` for visual references
- **Equations**: Present key formulas (v²/r, F = ma, F_friction = μN) in context
- **Length**: Race reports 800–1,200 words; technical deep-dives 1,500–2,500 words

## Key Topics Coverage

| Topic | File | Key Facts |
|---|---|---|
| Cornering physics | `technical-notes/cornering-physics.md` | Lateral g, centripetal accel, downforce, driver tolerance |
| Race strategy | `technical-breakdowns/` | — |
| Driver fitness | `technical-notes/cornering-physics.md` | G-LOC, grey-out, neck strain, blood circulation effects |
| Aerodynamic packages | `technical-breakdowns/` | Downforce vs. drag trade-offs, ground effect |
| Season narrative | `season-summaries/` | — |
