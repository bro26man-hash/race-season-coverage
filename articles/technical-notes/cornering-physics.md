# Cornering Physics — Technical Reference Notes

> Source: Wikipedia — [G-force](https://en.wikipedia.org/wiki/G-force)
> Purpose: Ready-reference for race season cornering analysis articles.

---

## 1. G-Force Fundamentals

- **Definition:** G-force (gravitational force equivalent) is a **mass-specific force** — force per unit mass — expressed in units of standard gravity (symbol **g** or **g₀**).
- **Standard gravity:** 1 g = **9.80665 m/s²** (≈ 35.3 km/h or 22 mph of velocity change per second).
- **Key澄清:** The term "g-force" is technically a measure of **acceleration**, not force. It is an acceleration that must be produced by a **mechanical force** — gravity alone does not produce g-force.
- **Newton's Second Law:** F = ma — the force felt in a corner is directly proportional to both the mass of the car + driver and the acceleration (G-load) experienced.
- **Newton's Third Law:** Every force has an equal and opposite reaction. The tire pushes laterally on the track surface; the track pushes back, generating the centripetal force that turns the car.

## 2. Lateral G-Loads Through Corners

- **What they are:** Lateral G-loads are the **side-to-side** accelerations experienced when a car changes direction. They are the primary metric for cornering performance.
- **How they arise:** Whenever a vehicle changes direction or speed, occupants feel **lateral** (side-to-side) or **longitudinal** (forward/backward) forces produced by the mechanical push of seats / tires.
- **Formula (constant acceleration over distance):** a = v² / (2s), where *v* is velocity and *s* is the distance over which the acceleration occurs.
- **Formula (centripetal):** a = v² / r, where *r* is the radius of curvature of the corner.
- **Practical example:** A dragster can exert a **horizontal g-force of 5.3** when accelerating — similarly, high-speed corners can generate equivalent lateral G-readings.
- **Measurement:** Use a **three-axis accelerometer** calibrated in g. Mount it transverse (left-right) to capture lateral G-loads directly. Data stored in `data/telemetry/`.

## 3. Centripetal Acceleration in Cornering

- **Role:** Centripetal acceleration is the **inward acceleration** directed toward the center of the corner's curve. It is what keeps the car turning rather than continuing in a straight line (Newton's First Law / inertia).
- **Source of force:** The **lateral friction force** between tires and track surface provides the centripetal force. Aerodynamic downforce increases this available friction.
- **Speed dependence:** Centripetal acceleration scales with the **square of speed** — doubling entry speed quadruples the G-load required for the same radius. This is why cornering limits are so speed-sensitive.
- **Radius dependence:** Tight corners (small *r*) produce higher G-loads at the same speed. This is why drivers "aim wide" — increasing the effective radius reduces peak lateral G.
- **Total G-load vector:** The combined magnitude is **√(lat² + lon² + 1²)**, accounting for lateral cornering, longitudinal braking/throttle, and the constant 1 g of gravity.

## 4. The Role of Downforce

- **Basic principle:** Downforce is an **aerodynamic load** pushing the car into the track, effectively increasing the car's weight without adding mass.
- **How it helps cornering:** By increasing the vertical load on the tires, downforce increases the **maximum lateral friction force** available (F_friction = μ × N, where N increases with downforce). This allows higher cornering speeds before the tires saturate.
- **G-force connection:** Downforce doesn't change the G-force *felt* by the driver directly — what matters is the **total lateral acceleration**. But it allows the car to *achieve* higher lateral G-loads without sliding, because the tire-to-track grip limit is raised.
- **Trade-off:** Downforce generation creates **aerodynamic drag**, which costs straight-line speed. Teams balance this via **wing angles** and **ride height** settings.
- **At speed:** Formula One cars can generate downforces exceeding **5g** at high speed — meaning the total vertical load on the car can be **6 times** its static weight (1 g gravity + 5 g aero).

## 5. Physical Demands on Drivers

### G-Tolerance Fundamentals

- **Dependencies:** Human tolerance depends on **magnitude** of G-force, **duration** of exposure, **direction** of application, **location** on the body, and **posture**.
- **The body is flexible:** Soft tissues deform under load. A brief localised impact of hundreds of g may cause no damage, but a **sustained 16 g for a minute** can be deadly.
- **Trainable:** G-tolerance can be improved through training (High-G training, straining maneuvers, g-suits), with significant individual variation.

### Lateral G-Loads (Cornering Direction)

- **"Eyeballs in" (forward/longitudinal):** The body is best at surviving G-forces **perpendicular to the spine**. Acceleration forwards (driver pushed back into seat) tolerates **~20 g₀ for <10 seconds**, **10 g₀ for 1 minute**, or **6 g₀ for 10 minutes**.
- **Lateral cornering G:** Side-to-side loads create **compressive stress** across the ribcage and **tensile stress** on the opposite side. These are transmitted through the body from the seat and harness.
- **Neck strain:** The driver's head (approximately 5 kg) effectively becomes much heavier under lateral G. At 4 g lateral, the head weighs ~20 kg laterally — the neck muscles must resist this moment continuously through the corner.

### Vision Effects Under G

- **Grey-out:** Vision loses hue — reversible on levelling out.
- **Tunnel vision:** Peripheral vision progressively lost.
- **Blackout:** Vision lost while consciousness is maintained — caused by reduced blood flow to the head.
- **G-LOC:** G-induced Loss Of Consciousness — a serious safety event.
- **Cause:** Positive (upward) G-forces drive blood **downward** toward the feet, starving the brain and eyes of oxygen.

### record Limits

- **Highest recorded surviving G-force:** **214 g₀** — Kenny Bräck, 2003 IndyCar Series finale, Texas Motor Speedway, after wheel-to-wheel contact and catch fence impact.
- **Human experimentation record:** John Stapp survived **46.2 g₀** "eyeballs-out" deceleration in 1954 rocket sled tests.

---

## Quick-Reference Table

| Metric | Value | Context |
|---|---|---|
| 1 g (standard gravity) | 9.80665 m/s² | Earth surface baseline |
| Dragster horizontal G | 5.3 g | Acceleration example |
| Untrained human, <10 s | ~20 g₀ | Horizontal, eyeballs in |
| Untrained human, 1 min | ~10 g₀ | Horizontal, eyeballs in |
| Modern pilot (with g-suit), sustained | ~9 g₀ | Vertical, positive |
| F1 car downforce at speed | ~5 g (aero) | Vertical load multiplier |
| Highest surviving human G | 214 g₀ | 2003 IndyCar, Bräck |
| Negative G limit (redout) | −2 to −3 g₀ | Blood driven to head |

---

## Writing Prompts

Use these facts as starting points for sidebars, explainer paragraphs, or data-driven narratives:

1. **"Why does cornering feel so heavy?"** — Explain lateral G-loads via Newton's laws and the v²/r relationship.
2. **"The invisible force that keeps them on track"** — How downforce multiplies tire grip and enables higher lateral G.
3. **"What happens to a driver's body in a 6-G corner"** — Blood displacement, neck strain, vision tunnel.
4. **"From 214 G to 5 G: The range of human experience"** — Contextualise racing G-loads against survival records.

---

*Last updated: Race season coverage setup. Source: Wikipedia G-force article.*
