# Cornering Physics: Technical Reference Notes

> Source: Wikipedia — "G-force" (https://en.wikipedia.org/wiki/G-force)
> Compiled for race season cornering analysis coverage.

---

## 1. G-Force Fundamentals

- **Definition**: G-force (gravitational force equivalent) is a **mass-specific force** (force per unit mass), expressed in units of standard gravity (symbol **g** or **g₀**). It is *not* actually a force — it is a measure of **acceleration** that causes a perception of weight.
- **Standard gravity**: 1 g₀ = **9.80665 m/s²** (≈ 35.3 km/h of velocity change per second).
- **Key distinction**: G-force is produced only by **mechanical surface-contact forces** (pushes and pulls). Gravitation alone does *not* produce g-force — an object in free fall experiences 0 g.
- **Newton's second law in action**: F = ma. The g-force on any object is the vector sum of all gravitational and non-gravitational forces acting on it, divided by its mass.

## 2. Lateral G-Loads Through Corners

- When a vehicle **changes direction**, occupants experience **lateral (side-to-side) g-forces** produced by the mechanical push of the seat against the body.
- Lateral g-forces are **perpendicular to the spine** for a driver seated in a reclined position — this is the "eyeballs in" orientation, where the body is essentially lying on its back.
- The human body is **significantly more tolerant** of lateral/perpendicular g-forces than vertical g-forces along the spine.
- **Cornering g-force magnitude** depends on:
  - Speed² (doubling speed quadruples the lateral g-load)
  - Radius of curvature (tighter corners = higher g-forces at the same speed)
  - The formula for constant acceleration over a curved path: **a = v² / r** (centripetal acceleration)
- In a racing context, lateral g-forces through corners typically range from **4–6 g** for Formula-level cars, and can spike higher in IndyCar and other open-wheel categories.

## 3. Centripetal Acceleration

- **Centripetal acceleration** is the inward-directed acceleration required to keep a body moving along a curved path. It is always perpendicular to the velocity vector and directed toward the center of curvature.
- Magnitude: **a_c = v² / r**, where *v* is speed and *r* is the radius of the turn.
- In cornering, the **lateral g-force** felt by the driver and car is the centripetal acceleration expressed in g-units.
- The mechanical force providing centripetal acceleration is the **friction between tires and track surface** — this is the *only* horizontal force available to change the car's direction.
- **Critical implication**: Since friction has a finite limit (μ × N, where N is the normal force), there is a maximum cornering speed for any given turn radius and surface condition.
- **Downforce increases the normal force (N)**, which increases the maximum available friction force, allowing higher cornering speeds before tire slip occurs.

## 4. Downforce and Its Role in Cornering G-Loads

- **Downforce** is the aerodynamic force that pushes the car **downward** into the track, opposite to the direction of positive vertical g-force.
- Downforce **increases the effective weight** of the car, which directly increases:
  - The **maximum lateral friction force** available for cornering (F_lateral_max = μ × (mg + F_downforce))
  - The **braking and acceleration grip limits**
- With downforce, a car can sustain **higher lateral g-loads** through corners without exceeding the tire's friction envelope.
- Downforce is **speed-dependent** — it scales roughly with the square of velocity, meaning cornering grip increases dramatically at high speeds.
- **Trade-off**: Downforce generates **aerodynamic drag**, which sacrifices straight-line speed. Teams balance downforce levels for track-specific cornering demands.
- In sustained cornering, the **total g-force vector** on the car is the combination of:
  - 1 g₀ (gravity, vertically downward)
  - Lateral cornering g (horizontal, toward the center of the turn)
  - Any vertical aerodynamic g (downforce adds to the effective vertical load)
- The **resultant g-force** is the vector sum: √(1² + lateral²) for a level road, or higher if significant aero downforce is present.

## 5. Physical Demands on Drivers

### G-Tolerance by Direction
- **Horizontal (perpendicular to spine — "eyeballs in")**: Much better tolerated.
  - Untrained humans: up to **20 g** for < 10 seconds
  - **10 g** for 1 minute
  - **6 g** for 10 minutes
  - Cognitive function remained intact in test subjects performing tasks at these levels.
- **Vertical (along spine — positive g, force blood toward feet)**: Significantly lower tolerance.
  - Typical person: ~**5 g** before losing consciousness
  - Modern F1 pilots with g-suits and straining maneuvers: sustained **9 g**
  - Progressive symptoms: **Grey-out** → **Tunnel vision** → **Blackout** → **G-LOC** (g-induced loss of consciousness) → Death if not reduced
- **Negative vertical g ("-g", force blood toward head)**: Even lower tolerance, typically **−2 to −3 g**.
  - Condition: **Red out** — vision reddens due to blood-laden eyelid being pulled into field of view.
  - Can cause retinal/brain vessel swelling or bursting.

### Racing-Specific Physical Demands
- **Lateral g-forces** during cornering are the primary sustained load on F1 drivers.
- A driver's **neck muscles** must support the head against lateral inertial forces — at 5 g lateral, a 5 kg helmet effectively weighs 25 kg.
- **Cardiovascular fitness** is critical: drivers must maintain blood flow to the brain under sustained lateral loading, and extraordinary core/neck strength prevents "head変" (lateral head movement) that impairs vision.
- **G-tolerance is trainable**: Extensive physical preparation (High-G training, centrifugal exposure) can raise individual thresholds.
- **Individual variation**: Innate g-tolerance varies considerably between athletes; some drivers naturally handle higher loads.
- **Cardiovascular conditions** reduce g-tolerance — a key reason driver fitness screening is rigorous.

### Record-Breaking G-Forces
- **Highest recorded g-force survived by a human**: **214 g₀** — IndyCar driver Kenny Bräck, 2003 Chevy 500 at Texas Motor Speedway (wheel-to-wheel collision, impact with catch fence).
- **Rocket sled record**: John Stapp survived **46.2 g₀** peak (eyeballs-out) and **25+ g₀** for 1.1 seconds in 1954 — proving the human body's remarkable tolerance to perpendicular acceleration.

## 6. Practical Implications for Cornering Analysis

| Parameter | Typical F1 Range | Notes |
|-----------|-----------------|-------|
| Lateral cornering g | 4–6 g | Sustained through medium–fast corners |
| Peak lateral g | 6–7+ g | Lowest-radius hairpins or chicanes |
| Braking g (longitudinal) | 5–6 g | Heavy braking zones |
| Acceleration g (longitudinal) | 4–5 g | Exit acceleration, limited by traction |
| Vertical g (with aero) | 3–5+ g | Under braking/downforce; "eyeballs out" |
| Driver neck load | Equivalent to 20–30 kg lateral head force | At 5–6 g lateral with helmet mass |

## 7. Key Equations for Writing Reference

| Equation | Meaning |
|----------|--------|
| **a_c = v² / r** | Centripetal acceleration = velocity² / turn radius |
| **F_friction = μ × N** | Maximum lateral friction force = coefficient × normal force |
| **N_total = mg + F_downforce** | Total normal force = gravity + aerodynamic downforce |
| **g_perceived = a_c / g₀** | Perceived cornering g = centripetal acceleration / standard gravity |
| **v_max = √(μ × g₀ × r)** | Maximum cornering speed for given radius and friction |

---

*Notes compiled from Wikipedia's "G-force" article. All values are representative estimates for reporting purposes — verify against season-specific telemetry data for precise figures.*