# Cornering Physics: Technical Reference Notes

> Source: Wikipedia — [G-force](https://en.wikipedia.org/wiki/G-force)
> Purpose: Ready reference for race season cornering analysis articles

---

## 1. What Is G-Force?

- **G-force (gravitational force equivalent)** is a **mass-specific force** — force per unit mass — expressed in units of **standard gravity** (symbol: g or g₀).
- **1 g = 9.80665 m/s²** — the acceleration due to gravity at Earth's surface. This is the baseline: a car sitting on the grid experiences 1 g straight down.
- G-force is **not** a force in the pure sense — it is an **acceleration** that must be produced by a **mechanical push or pull** (a surface-contact force). Gravitation alone does not produce g-force; objects in free fall experience 0 g.
- The direction matters: **positive g** points downward (upward acceleration), producing compressive stress through the body. **Negative g** points upward, producing tensile stress — this is the "red-out" regime.

## 2. Lateral G-Loads Through Corners

- When a car changes **direction** (not just speed), the occupants experience **lateral (side-to-side) g-forces** produced by the mechanical push of the seat and tires against the road surface.
- Lateral g-load is the **centripetal acceleration** required to keep the car moving along a curved path. It is governed by:  
  **a = v² / r**  
  where *v* is speed and *r* is the radius of curvature. Double the speed → four times the lateral g. Half the radius → double the g.
- In a front-wheel-drive car under braking, you can hit roughly **1.0–1.2 g** longitudinally; racing cars can sustain much higher.
- A dragster accelerating horizontally can exert **~5.3 g** — a reference point for peak longitudinal loads.
- **Lateral g in F1 corners**: Through high-speed corners like Copse or新兴产业, cars can experience **4–6 g** of lateral load. This is the dominant physical force the driver must manage.

## 3. Centripetal Acceleration & The Physics of Turning

- **Centripetal acceleration** is always directed toward the center of the curve. It is what allows the car to change direction rather than continuing in a straight line (Newton's first law / inertia).
- The **source** of centripetal force in a racing car is the **friction between tires and track surface** — but this is dramatically amplified by **aerodynamic downforce** (see below).
- The equation **a = v² / (2s)** also applies to constant-acceleration scenarios over a distance *s* — useful for calculating g-loads through corner entry where braking and turning overlap.
- **Newton's second law (F = ma)** is the governing principle: the net force on the car equals its mass times the centripetal acceleration. The reaction force (Newton's third law) is the tire pushing laterally on the track surface.
- **Jerk** (rate of change of acceleration, measured in g₀/s) matters in cornering: sudden application of lateral load causes transient shock loads that affect tire grip and driver comfort.

## 4. The Role of Downforce

- **Downforce** is an aerodynamic force pushing the car **into the track**, effectively increasing the **normal force** on the tires.
- Higher normal force → **higher maximum friction force** → the tires can generate more lateral grip before sliding.
- Downforce allows racing cars to take corners at **much higher speeds** than would be possible with gravity alone. Without downforce, a Formula 1 car would slide off course at relatively modest speeds.
- Downforce scales with **speed squared**: double the speed → four times the aerodynamic load. This means high-speed corners generate dramatically more grip — but also demand dramatically more driver effort.
- The balance between **downforce** and **drag** is a key engineering trade-off: more downforce means faster cornering but more aerodynamic resistance on straights.
- **Ground effect** (underbody aerodynamics) generates additional downforce via the **venturi effect** — accelerated airflow under the car creates a low-pressure region that sucks the car toward the track.

## 5. Physical Demands on Drivers

### G-Tolerance

- Human tolerance to g-forces depends on: **magnitude**, **duration**, **direction**, **point of application**, and **body posture**.
- **Horizontal g-forces** (perpendicular to the spine — "eyeballs in") are **far better tolerated** than vertical g-forces. A driver's body is roughly horizontal in the cockpit, so lateral cornering g-loads are managed more effectively than vertical braking g-loads.
- Untrained humans can tolerate approximately:
  - **20 g** for less than 10 seconds
  - **10 g** for about 1 minute
  - **6 g** for about 10 minutes
- These thresholds are for **cognitive integrity** — drivers must perform complex tasks (steering, braking, throttle modulation) under load.

### Vertical G-Loads (Braking & Kerbs)
- **Positive vertical g** (braking, hitting kerbs) drives **blood downward toward the feet**.
- Progression of symptoms under increasing positive g:
  1. **Grey-out** — vision loses hue (reversible)
  2. **Tunnel vision** — peripheral vision lost
  3. **Blackout** — vision lost but consciousness maintained
  4. **G-LOC** — g-induced loss of consciousness
  5. **Death** — if g-forces are not promptly reduced
- A typical person can handle about **5 g** before losing consciousness; trained individuals with **g-suits** and active straining can sustain **~9 g**.
- **Negative vertical g** ( cresting hills, decompression) drives blood **toward the head** — "red-out." Tolerance is much lower: **−2 to −3 g**.

### Lateral G-Loads (Cornering)
- Lateral g-loads push the driver **against the seat** and strain the **neck, core, and shoulder** muscles.
- The driver must **counter-steer** and **brake** simultaneously while under lateral load — a significant multitasking challenge.
- Sustained lateral loading over a full lap can produce **cumulative fatigue**, especially in the trapezius and cervical muscles.
- **Vision impact**: Under combined lateral + vertical g-loads, the driver's ability to fixate on turning points and braking markers is degraded.
- The neck must support the **effective weight of the head multiplied by the g-load**. At 5 g lateral, a 5 kg head effectively weighs 25 kg and must be controlled by muscular effort alone.

### Record-Breaking G-Forces
- The **highest recorded g-force survived by a human**: **214 g₀** — IndyCar driver Kenny Bräck, 2003 Chevy 500, Texas Motor Speedway (wheel-to-wheel collision with catch fence impact).
- **John Stapp's rocket sled experiments** (1954): survived **46.2 g₀** "eyeballs-out" and **25+ g₀** for 1.1 second — proving the human body's remarkable tolerance to horizontal acceleration.

## 6. Practical Implications for Race Coverage

- When describing a corner, reference the **type of g-load** (lateral, longitudinal, or combined) and the **approximate magnitude** (in g).
- Use the **v²/r relationship** to explain why a driver lifted off throttle mid-corner: reducing speed reduces the required centripetal force, freeing grip reserve for trajectory adjustments.
- Mention **downforce diagnostics**: if a car appears fast in low-speed corners but slow on straights, it may be running a **high-downforce setup**; the reverse suggests a **low-drag, high-speed configuration**.
- Driver physical comments are grounded in real physiology: references to **neck strain, peripheral vision loss, and g-LOC risk** are all supported by aerospace and military research.
- **Telemetry data** (lateral g-plots, speed traces) can be animated to visualize the g-actinée cycle through a corner — brake commit, turn-in, apex, and traction-out.

---

## Key Equations Quick Reference

| Equation | Meaning |
|---|---|
| **a = v² / r** | Centripetal acceleration through a corner |
| **a = v² / (2s)** | Constant acceleration over distance s (corner entry) |
| **F = ma** | Net force = mass × acceleration (Newton's 2nd Law) |
| **F_friction = μ × N** | Maximum grip force = friction coeff. × normal force |
| **Downforce ∝ v²** | Aerodynamic load scales with speed squared |
| **Effective weight = m × (1 + g_load)** | Apparent weight under acceleration |

---

*Last updated: Race season coverage setup. Adapt and expand as telemetry data becomes available.*
