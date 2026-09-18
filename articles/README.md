# Articles Directory 📝

This folder contains all editorial content for the race season coverage, from weekend previews to deep-dive technical analysis.

## Structure

```
articles/
├── README.md                     # This file — editorial index & style guide
├── previews/                     # Grand Prix & race weekend previews
│   └── (preview markdown files)
├── race-reports/                 # Post-race debriefs, strategic breakdowns, classifications
│   └── (race report markdown files)
├── driver-profiles/              # In-depth driver & team profiles
│   └── (profile markdown files)
├── season-summaries/             # Mid-season & end-of-season retrospectives
│   └── (summary markdown files)
└── technical-notes/              # Deep dives into vehicle dynamics, aerodynamics & physics
    └── cornering-physics.md      # Lateral G-loads, centripetal acceleration, downforce & driver physiology
```

## Content Types

| Type | Description | Length |
|------|-------------|--------|
| Race Reports | Lap-by-lap narratives, finishers, key moments | 500–1,000 words |
| Technical Breakdowns | Car performance, strategy, engineering analysis | 600–1,200 words |
| Driver Profiles | Career overview, physical & mental demands | 600–1,200 words |
| Season Summaries | Championship battles, trends, statistics | 800–1,500 words |
| Previews | Weekend outlook, circuit guide, setup analysis | 400–800 words |
| Technical Notes | Physics & engineering deep-dives (see `technical-notes/`) | 800–1,500 words |

## Style Guide

- **Lead with the human story; anchor with technical facts** — start with what fans saw, then explain the physics behind it.
- **Define technical terms on first use** — e.g., "lateral G-load (the side-to-side acceleration experienced through a corner)".
- **Use metric units (G, m/s²) alongside imperial** where relevant for a global audience.
- **Contextualize every number** — pair a G-force figure with a relatable comparison (fighter pilot, roller coaster, etc.).
- **Reference `technical-notes/cornering-physics.md`** for cornering physics definitions, equations, and historical records.
- **Separate observation from analysis** — describe what happened, then explain why using physics principles.
- **Include a `Sources` section** at the end of every article, citing Wikipedia references, FIA data, and team sources.
- **Use inline math** with `$` signs for equations (e.g., `$a_c = v^2/r$`).

## Workflow

1. **Draft** → Write in the appropriate subfolder (previews, race-reports, technical-notes, etc.).
2. **Review** → Cross-check data against `../data/` telemetry and lap-time sheets.
3. **Fact-check** → Verify G-force values against Wikipedia and FIA sources; confirm sector times.
4. **Peer review** → Send technical notes to the engineering columnist for verification.
5. **Publish** → Move to final location and link from root README.
