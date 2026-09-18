# Cornering Physics — Technical Reference Notes

> Source: Wikipedia — [G-force](https://en.wikipedia.org/wiki/G-force)
> Purpose: Ready-reference physics facts for race season cornering analysis.

---

## 1. G-Force Fundamentals

- **Definition:** G-force (gravitational force equivalent) is a **mass-specific force** — force per unit mass — expressed in units of standard gravity (symbol **g** or **g₀**, not to be confused with "g" for grams).
- **Standard gravity:** 1 g = **9.80665 m/s²** (≈ 35.3 km/h of velocity change per second).
- **Key distinction:** G-force is technically a measure of **acceleration**, not force. It is produced only by **mechanical pushes and pulls** — gravitation alone (free fall) produces 0 g.
- **Directionality:** Positive g-force points downward (upward acceleration); negative g-force points upward (downward acceleration). In a car, lateral (side-to-side) and longitudinal (forward/backward) g-forces are both felt by the driver.

## 2. Lateral G-Loads Through Corners

- **Origin:** Whenever a vehicle changes direction, the occupants feel **lateral forces** produced by the mechanical push of the seat (or seatbelt). This is the lateral G-load.
- **Physics:** For constant acceleration over a distance *s*, the acceleration is **v² / (2s)**. This means cornering G-load scales with the **square of speed** — doubling speed quadruples the lateral G-demand for the same radius.
- **Measurement:** A three-axis accelerometer mounted in the car registers lateral G-load as the component perpendicular to the direction of travel. When the car is cornering, the accelerometer's horizontal axis (rotated 90° from vertical) reads the lateral g-level.
- **Real-world context:** A dragster accelerating horizontally can exert **5.3 g** — showing that sustained accelerations well above 1 g are routine in motorsport.

## 3. Centripetal Acceleration & the Cornering Equation

- **Centripetal acceleration** is the inward acceleration required to keep the car moving along a curved path: **a = v² / r**, where *v* is speed and *r* is the radius of curvature.
- **Lateral g-load** is the centripetal acceleration expressed in g-units: **lat_g = v² / (r × g₀)**.
- **Implication for racing:** Elite drivers operate close to the **friction limit** — the maximum lateral G the tires can provide. This limit depends on:
  - **Tire grip coefficient** (μ) — affected by compound, temperature, and degradation.
  - **Vertical load** — the force pressing the tire into the track, which includes the car's weight **plus aerodynamic downforce**.
  - The relationship: **Max lateral G ≈ μ × (static weight + downforce) / mass**.

## 4. The Role of Downforce

- **Downforce** is an aerodynamic force pushing the car into the track, increasing the **vertical load** on the tires.
- **Effect on cornering:** More downforce → more vertical load → more available grip → higher achievable lateral G-load before tire slip.
- **Trade-off:** Downforce generation also creates **aerodynamic drag**, which costs straight-line speed. Circuits with slow corners (e.g., Monaco) favor high-downforce setups; fast circuits with long straights (e.g., Monza) favor low-downforce.
- **Speed dependency:** Downforce scales approximately with the **square of speed** (like lift, but in reverse). This means cornering grip is **non-linear with speed** — a car feels dramatically faster and more planted at 300 km/h than at 150 km/h on the same corner.
- **Front vs. rear balance:** Downforce distribution between front and rear axles affects **corner entry vs. corner exit** characteristics. Too much rear downforce causes oversteer; too much front downforce causes understeer.

## 5. Physical Demands on Drivers

### G-Tolerance

- **Vertical g-forces** (along the spine) are the most dangerous. A typical person loses consciousness (**g-LOC**) at ~**5 g**. With g-suits and muscle straining, modern pilots can sustain **~9 g**.
- **Horizontal g-forces** (perpendicular to the spine — "eyeballs in/out") are better tolerated. Untrained humans can handle:
  - **20 g** for < 10 seconds
  - **10 g** for ~1 minute
  - **6 g** for ~10 minutes
- **Record:** The highest G-force ever survived by a human was **214 g** — set by Kenny Bräck in a 2003 IndyCar crash at Texas Motor Speedway.

### Specific Driver Challenges in Cornering

- **Blood circulation:** Lateral g-forces drive blood toward the outside of the corner, reducing flow to the brain andEyes. Drivers risk **grey-out** (vision loses hue), **tunnel vision**, and **blackout** under sustained lateral loading.
- **Neck strain:** The head weighs ~5 kg; under 4 g lateral loading, the neck must support an equivalent of **~20 kg** of lateral force. Core and neck conditioning is essential.
- **Vision impact:** Peripheral vision degrades first under g-loading. Drivers must learn to **fixate centrally** and rely on spatial awareness developed through experience.
- **Breathing:** High lateral g makes it difficult to take deep breaths. Driver fitness programs emphasize **diaphragmatic breathing** under load.
- **G-substance (g-taking):** Skilled drivers use specific body movements — tightening the core, rolling the shoulders into the seat — to distribute the g-force over a larger body area and delay localized fatigue.

### Training & Adaptation

- **G-suits:** Compressive garments that squeeze the extremities, preventing blood pooling.
- **Centrifuge training:** Repeated exposure to elevated g-levels to build tolerance.
- **Strain maneuver:** Voluntary muscle tension (especially legs and core) to raise blood pressure and maintain cerebral perfusion.
- **Progressive overload:** Similar to strength training, g-tolerance improves with gradual, repeated exposure.

---

## Quick-Reference Formulae

| Quantity | Formula | Units |
|---|---|---|
| Standard gravity | g₀ = 9.80665 | m/s² |
| Acceleration (constant, over distance) | a = v² / (2s) | m/s² |
| Centripetal acceleration | a = v² / r | m/s² |
| Lateral g-load | lat_g = v² / (r × g₀) | g |
| Max lateral G (friction limit) | ≈ μ × (W + Downforce) / m | g |
| Downforce scaling | F_down ∝ v² | N |

---

*These notes are compiled from the Wikipedia article on [G-force](https://en.wikipedia.org/wiki/G-force) and general motorsport physics principles. For detailed telemetry data, see `data/telemetry/`. For circuit-specific G-load plots, see `multimedia/graphics/`.*