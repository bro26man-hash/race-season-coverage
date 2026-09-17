# Cornering Physics — G-Force Technical Reference

> Source: Wikipedia, "G-force" — extracted for race-season cornering analysis.
> Last updated: 2025 racing season coverage.

---

## 1. G-Force Fundamentals

- **G-force** (gravitational force equivalent) is a mass-specific force — force per unit mass — expressed in units of standard gravity (**g** or **g₀**), where **1 g = 9.80665 m/s²**.
- Technically, g-force is an **acceleration**, not a force. It arises whenever a mechanical force pushes or pulls on an object, producing compressive and tensile stresses within it.
- An object in **freefall** (e.g., orbiting spacecraft) experiences **0 g** — weightlessness — because only gravity acts on it, with no mechanical contact force.
- **Key racing implication:** Every time a car changes direction or speed, the occupants feel **lateral** (side-to-side) or **longitudinal** (forward/backward) forces produced by the mechanical push of the seat and restraints.

## 2. Lateral G-Loads Through Corners

- Cornering generates **centripetal acceleration** directed toward the center of the turn. The required inward force is provided by tire grip (friction between tire and track surface).
- The magnitude of lateral g-load depends on:
  - **Speed²** — doubling corner speed quadruples the lateral G-load (since acceleration ∝ v²).
  - **Radius of curvature** — tighter corners (smaller radius) demand higher G-forces for the same speed.
  - Relationship: for constant acceleration over distance **s**, `a = v² / (2s)`.
- A **dragster** accelerating horizontally can exert approximately **5.3 g** — a benchmark for high-performance lateral/longitudinal loading.
- In a corner, the driver feels a **lateral G-load** pushing them outward (away from the turn center). The seat and restraints must provide an equal and opposite inward force to keep the car on its curved path.
- **Downforce's role:** Aerodynamic downforce increases the **normal force** pressing the tires into the track. Since maximum friction force = μ × Normal force, more downforce directly increases the maximum lateral G-load the tires can generate before sliding. This is why F1 and other downforce-dependent series can sustain cornering G-loads of **5–6 g** or higher, while limited-grip disciplines (e.g., rally on low-g surfaces) see much lower values.

## 3. Centripetal Acceleration & The Physics of Turning

- **Newton's Second Law** applies directly: **F = ma**. The net force on the car (and driver) during cornering is the centripetal force directed toward the turn center.
- **Newton's Third Law** applies equally: the tires push the road surface outward; the road pushes the tires inward with an equal and opposite force — this is what actually changes the car's direction.
- **1 g = 9.80665 m/s²** means velocity changes by ~35.3 km/h (22 mph) per second. A car braking at 1 g from 35 km/h stops in 1 second; from 105 km/h, it takes 3 seconds.
- For cornering, the same relationship holds: a car entering a 50 m radius turn at 27 m/s (≈97 km/h) experiences approximately **1.5 g** of lateral acceleration (`a = v²/r = 27²/50 = 14.6 m/s² ≈ 1.5 g`).

## 4. Human Tolerance to G-Forces — Driver Physical Demands

### Direction Matters
- The human body tolerates G-forces **perpendicular to the spine** far better than those aligned with the spine.
- **"Eyeballs-in"** (acceleration pushing the driver back into the seat — typical for braking and forward faces): much higher tolerance.
- **"Eyeballs-out"** (acceleration pushing the driver forward — typical for cornering lateral loads and during a frontal impact): lower tolerance because retinal blood vessels are more sensitive in this direction.

### Sustained G-Loads
- Untrained humans can tolerate approximately:
  - **20 g** for less than 10 seconds
  - **10 g** for 1 minute
  - **6 g** for 10 minutes
- These levels were endured with cognitive facilities intact in early experiments, though tolerance is subjective and varies considerably between individuals.

### Racing-Specific Tolerance
- **Positive vertical g** (force blood toward feet, away from head): typical person loses consciousness around **5 g**; modern pilots using **g-suits** and muscle-straining techniques can sustain **9 g**.
- **Negative g** (force blood toward head): tolerance is only **−2 to −3 g**. This causes "red-out" (vision reddened), and can lead to swelling or bursting of blood vessels in the eyes and brain.
- Cornering lateral G-loads in **eyeballs-out** orientation are therefore particularly demanding on the visual system and cerebral blood flow.

### Symptom Progression Under Increasing G
As positive vertical g increases (analogous to increasing lateral g in cornering):
1. **Grey-out** — vision loses hue (reversible when g is reduced)
2. **Tunnel vision** — peripheral vision progressively lost
3. **Blackout** — loss of vision while consciousness is maintained (caused by reduced blood flow to the head)
4. **G-LOC** — g-force-induced loss of consciousness
5. **Death** — if g-forces are not quickly reduced

### Record-Holding Tolerance
- **John Stapp** (1954 rocket-sled experiments): survived **46.2 g** eyeballs-out and **25 g** for 1.1 seconds — living to age 89 with no ill effects.
- **Highest recorded g-force survived in a crash**: **214 g** — Kenny Bräck, 2003 IndyCar Series finale at Texas Motor Speedway (car impacted catch fence after wheel-to-wheel contact).

### Trainability
- **G-tolerance is partially trainable.** Physical conditioning, g-suit utilization, and repeated exposure can improve a driver's ability to sustain higher cornering G-loads for longer periods without degradation of coordination or consciousness.

## 5. Practical Implications for Cornering Analysis

| Factor | Effect on Cornering G-Load |
|---|---|
| Speed increase | Squared relationship — G-load rises with v² |
| Tighter radius | G-load inversely proportional to radius |
| Downforce increase | Raises maximum sustainable lateral G before tire slip |
| Tire grip (μ) | Directly proportional to maximum lateral force |
| Driver posture | Lateral G in "eyeballs-out" is harder to tolerate than longitudinal "eyeballs-in" |
| G-training | Extends sustainable cornering duration at high G-levels |
| Surface conditions | Low-g surfaces (rain, marbles) drastically reduce achievable lateral G |

## 6. Key Equations

| Equation | Description |
|---|---|
| `a = v² / r` | Centripetal acceleration (cornering G) |
| `a = v² / (2s)` | Constant acceleration over distance |
| `F = ma` | Newton's Second Law — force = mass × acceleration |
| `F_friction = μ × N` | Maximum lateral friction force (tire grip) |
| `1 g = 9.80665 m/s²` | Standard gravity = 9.80665 m/s² = 35.3 km/h per second |

---

*This reference is derived from the Wikipedia article on "G-force" and is intended for editorial use in race-season technical coverage. For more detailed aerodynamics and vehicle dynamics, consult FIA technical regulations and motorsport engineering texts.*
