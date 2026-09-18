# Race Season Coverage

Comprehensive race season coverage project — technical cornering analysis, driver insights, race data, and multimedia assets.

## 📁 Project Structure

```
race-season-coverage/
├── README.md                  # Project overview (this file)
├── articles/                  # Written coverage & technical notes
│   ├── race-reports/          # Race-by-race reports and summaries
│   ├── driver-profiles/       # Driver interviews, bios, and analysis
│   └── technical-notes/       # Deep-dive technical reference documents
│       └── cornering-physics.md
├── multimedia/                # Visual & audio assets
│   ├── photos/                # Race photography and stills
│   ├── videos/                # Highlight reels and analysis clips
│   └── audio/                 # Interviews and podcasts
└── data/                      # Raw & processed race data
    ├── telemetry/             # Car telemetry logs
    ├── timing-results/        # Sector times and race results
    └── g-force-data/          # Lateral & longitudinal G-load datasets
```

## 🏎️ Focus Areas

- **Cornering Physics** — Lateral G-loads, centripetal acceleration, and the role of aerodynamic downforce
- **Driver Demands** — Physical and cognitive requirements under high-G conditions
- **Technical Analysis** — Data-driven breakdowns of racing lines, braking zones, and apex precision
- **Multimedia Storytelling** — Photos, videos, and audio to complement written coverage

## 📝 Writing Notes

All technical reference documents live in `articles/technical-notes/`. Each file should:
1. Define the core physics concept clearly
2. Cite relevant formulas and real-world racing examples
3. Translate theory into practical narrative hooks for race coverage

## 🔬 Technical Reference Sources

- Wikipedia: [G-force](https://en.wikipedia.org/wiki/G-force)
- Wikipedia: [Centripetal force](https://en.wikipedia.org/wiki/Centripetal_force)
- Wikipedia: [Downforce](https://en.wikipedia.org/wiki/Downforce)

## 📊 Key Physics Quick Reference

| Concept | Value / Formula |
|---|---|
| Standard gravity (1 g) | 9.80665 m/s² ≈ 35.3 km/h velocity change per second |
| Dragster horizontal acceleration | ~5.3 g |
| Peak human horizontal tolerance (untrained) | 20 g (short burst) / 6 g (sustained) |
| Record peak g-force ever survived | 214 g (2003 IndyCar, Kenny Bräck) |
| Negative g-tolerance limit | −2 to −3 g₀ |
| Constant acceleration formula | a = v² / (2s) |

## ✍️ How to Use This Repo

1. **Research** — Read `articles/technical-notes/` for physics backgrounds
2. **Report** — Draft race coverage in `articles/race-reports/`
3. **Profile** — Document drivers in `articles/driver-profiles/`
4. **Multimedia** — Organize assets in `multimedia/{photos,videos,audio}/`
5. **Data** — Log raw numbers in `data/{telemetry,timing-results,g-force-data}/`
