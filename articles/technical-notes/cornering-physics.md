# Cornering Physics — G-Force Technical Reference

> Source: Wikipedia — [G-force](https://en.wikipedia.org/wiki/G-force) | Supplemental: NASA human tolerance studies, military aviation research
>
> **Purpose:** Ready-reference facts for writing technical cornering analysis with accurate physics.

---

## 1. G-Force Fundamentals

- **Definition:** G-force (gravitational force equivalent) is a **mass-specific force** — force per unit mass — expressed in units of standard gravity (symbol **g** or **g₀**). It is *not* a true force but an acceleration that must be produced by a mechanical contact force.
- **Standard gravity:** 1 g = **9.80665 m/s²** (≈ 35.3 km/h of velocity change per second).
- **Key insight:** G-force is only produced by **mechanical pushes and pulls** — gravitation alone produces weightlessness (0 g). A driver feels g-forces because the seat, harness, and ground are pushing back on the car and body.
- **Directionality:** Positive g points downward (upward acceleration → compressive force into the seat). Negative g points upward → the body feels pulled out of the seat. In cornering, the critical axis is **lateral** (side-to-side).

## 2. Lateral G-Loads Through Corners

- **What they are:** Lateral g-load is the **side-to-side acceleration** experienced when a car changes direction through a corner. It is the horizontal component of the total g-vector.
- **How they arise:** The tires generate a lateral (cornering) force at the contact patch. This force pushes the car inward along the curve. By Newton's second law (F = ma), the magnitude of lateral g is directly proportional to the cornering force and inversely proportional to the car's mass.
- **Typical magnitudes in motorsport:**
  - Passenger cars: 0.7–1.0 g lateral
  - Formula cars / high-downforce machines: **1.5–3.0+ g lateral**
  - IndyCar / GTP prototypes: up to **4–5 g** in high-speed corners
  - Record: the highest *survived* horizontal g was **46.2 g** (John Stapp, rocket sled, 1954, "eyeballs-out")
- **Vector composition:** Total g experienced by the driver is the **vector sum** of lateral, longitudinal (braking/acceleration), and vertical components. At the apex of a corner, a driver might experience 3.0 g lateral + 0.5 g braking + 1.0 g vertical = ~3.2 g combined.

## 3. Centripetal Acceleration

- **The physics:** A car turning through a corner undergoes **centripetal acceleration** directed toward the center of curvature. This acceleration is what keeps the car on its curved path rather than continuing in a straight line (Newton's first law / inertia).
- **Formula:** a_c = v² / r  — where *v* is speed and *r* is the radius of curvature.
  - **Implication:** Doubling speed **quadruples** the required centripetal force (and thus the lateral g-load).
  - **Implication:** A tighter radius (smaller *r*) at the same speed requires **more** lateral g.
- **Flat vs. banked corners:** On a flat surface, lateral friction alone provides the centripetal force. On a **banked** corner, the normal force from the track surface has a horizontal component that contributes to centripetal acceleration, reducing the reliance on tire friction and allowing higher cornering speeds.
- **Driver perception:** The driver feels the centripetal acceleration as a lateral push into the seat (positive lateral g) or a pull toward the door (negative lateral g, depending on corner direction and convention).

## 4. The Role of Downforce

- **What it is:** Downforce is the **aerodynamic load** that presses the car into the track surface. It acts as an additional "weight" force, increasing the normal force between tires and track.
- **How it increases grip:** The maximum lateral (cornering) force a tire can generate is proportional to the **normal load** on it (F_lateral_max = μ × N, where μ is the coefficient of friction and N is the normal force). Downforce increases N, which increases the available cornering force, which allows **higher lateral g** at the same speed — or the same lateral g at a higher speed.
- **Downforce vs. drag trade-off:** Wings and aerodynamic devices that generate downforce also produce **aerodynamic drag** (opposing forward motion). Teams must balance downforce levels:
  - **High downforce** (e.g., Monaco, twisty circuits): More grip through corners, slower straights
  - **Low downforce** (e.g., Monza, high-speed ovals): Less cornering grip, faster straights
- **Ground effect:** Venturi channels under the car create a low-pressure area that "sucks" the car toward the track. This generates downforce with comparatively low drag — highly efficient for high-speed corners.
- **Speed dependency:** Aerodynamic downforce scales with the **square of velocity** (F_downforce ∝ v²). At 300 km/h, downforce can be **3–5× the car's static weight** in a Formula car, meaning the effective "gravitational" loading are dramatically higher than static.

## 5. Physical Demands on Drivers

### G-Tolerance by Direction

- **Vertical (spine-aligned):** A typical person can handle about **5 g** before losing consciousness. With g-suits and muscle straining (to force blood back to the brain), modern pilots can sustain **9 g**.
  - **Progression of symptoms:** Grey-out (loss of color vision) → Tunnel vision (peripheral loss) → Blackout (vision lost but consciousness maintained) → **G-LOC** (full loss of consciousness) → Death if not quickly reduced.
- **Horizontal (perpendicular to spine — "eyeballs in"):** Much higher tolerance — up to **20 g** for < 10 seconds, **10 g** for 1 minute, **6 g** for 10 minutes.
  - "Eyeballs out" (acceleration toward the front of the helmet) is significantly worse due to retinal blood vessel sensitivity.

### Specific Demands in Motorsport

- **Neck strain:** Lateral g-loads flex the neck sideways. At 3.0 g lateral, the effective head weight is ~3× its normal ~5 kg → **~15 kg of lateral force** on the cervical spine. Neck muscles must constantly contract to keep the head stable and eyes on track.
- **Core & upper body:** The harness restrains the torso, but the driver's core must brace against the lateral push to maintain driving precision. Sustained 2–3 g lateral for minutes causes significant **core fatigue**.
- **Blood circulation:** Lateral g shifts blood toward the outside (door) side of the body. This can reduce perfusion to the brain on the inside (central) side, contributing to **grey-out** symptoms even at moderate lateral g levels.
- **Vision impacts:** Lateral g can cause a **horizontal grey-out** — a band of dimming across the field of view. This is distinct from vertical g grey-out but has the same physiological cause (retinal blood flow disturbance).
- **Reaction time degradation:** At high lateral g, cognitive processing slows. Studies show a measurable increase in **brake reaction time** (from ~200 ms baseline to 250+ ms under high g), which is critical for safety-critical decisions.
- **Heat & dehydration:** Cockpit temperatures can exceed 50°C. Combined with the intense physical effort of managing high g-loads, drivers lose significant fluid through sweat, further degrading g-tolerance and cognitive function.

### Record-Breaking Gloads in Racing

- **Highest survived g in autosport:** **214 g** — Kenny Bräck, 2003 Chevy 500 at Texas Motor Speedway (IndyCar crash into catch fence). This was an extreme impact (short-duration shock), not sustained cornering.
- **Sustained cornering in race conditions:** Drivers regularly experience **3–5 g lateral** through high-speed corners (e.g., Eau Rouge in F1, Turn 1 in IndyCar) for **2–5 seconds** per corner — a genuine physical challenge.

---

## Quick Reference: Cornering G-Load Equation

```
Lateral g = v² / (r × g₀)

Where:
  v  = speed (m/s)
  r  = radius of curvature (m)
  g₀ = 9.80665 m/s² (standard gravity)

Plus downforce contribution:
  Effective lateral g = (v² / (r × g₀)) × (1 + Downforce / (m × g₀))
```

---

*Last updated: 2026 race season. Review before each season for updated vehicle and circuit data.*