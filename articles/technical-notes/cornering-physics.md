# Cornering Physics — Technical Reference Notes

> **Source:** Wikipedia, "G-force" — extracted for race-season cornering analysis
> **Last updated:** 2025 season coverage

---

## 1. G-Force Fundamentals

- **Definition:** G-force (gravitational force equivalent) is a **mass-specific force** (force per unit mass), expressed in units of standard gravity (symbol **g** or **g₀**). One standard gravity is defined as **9.80665 m/s²** (≈ 35.3 km/h per second of velocity change).
- **Perception of weight:** G-force is used for *sustained accelerations* that cause a perception of weight. An object at rest on Earth's surface experiences 1 g — the reaction force from the ground pushing upward.
- **It's acceleration, not force:** The term "g-force" is technically a measure of **acceleration**, not force. However, when multiplied by a mass, it produces a mechanical force (F = ma) that results in compressive and tensile stress within objects.
- **Direction matters:** Positive g-force points downward (upward acceleration), producing a downward weight-force. Negative g-force points upward (downward acceleration), producing an upward weight-force — this is the principle behind negative-g cornering and aerobatics.

---

## 2. Lateral G-Loads Through Corners

- **Lateral (side-to-side) forces** are produced whenever a vehicle changes direction. These are the g-loads drivers experience through corners — perpendicular to the direction of travel.
- **Mechanism:** The seat pushes the driver laterally to change their velocity vector. This mechanical push produces a **proper acceleration** (coordinate acceleration) that the driver feels as a lateral g-force pressing them into the seat.
- **Magnitude examples:**
  - A dragster can exert a **horizontal g-force of 5.3 g** during acceleration — similar principles apply to lateral loading through corners at racing speed.
  - Road cars cornering aggressively may see 0.9–1.2 g lateral; race cars routinely exceed **4–6 g** in high-speed corners depending on speed, radius, and surface.
- **Formula context:** For constant acceleration over a distance, acceleration = v² / (2s). For cornering, centripetal acceleration = v² / r (velocity squared divided by corner radius). This means **speed doubles → lateral G-load quadruples**, and a **tighter radius → higher G-load** at the same speed.

---

## 3. Centripetal Acceleration

- **Centripetal force** is the inward force required to keep an object moving along a curved path. It is always directed perpendicular to the velocity vector, toward the center of curvature.
- **In cornering:** The tires provide the centripetal friction force that changes the car's direction. Without sufficient centripetal force, the car continues in a straight line (Newton's First Law).
- **G-force relation:** The centripetal acceleration experienced is directly the lateral g-load. At 1 g of lateral acceleration, the net inward force equals the car's weight. At 4 g, the inward force is four times the car's weight.
- **Driver perception:** The driver feels this as a sideways "weight" pressing against the seat. The faster the change in direction (higher speed or tighter radius), the greater the g-force and the greater the physical demand.
- **Newton's Second Law in action:** F_centripetal = m × a_centripetal. For a given car mass, doubling the speed requires four times the centripetal force (and thus four times the lateral g-load), which is why corner-entry speed is so critical.

---

## 4. Downforce & Aerodynamic Grip

- **Downforce** is the aerodynamic force pushing the car downward into the track, increasing the normal force on all four tires.
- **How it increases cornering grip:** More normal force → more available friction → more centripetal force possible → higher lateral g-loads before the tires saturate. This is why F1 cars can pull **5–6 g laterally** while a road car tops out around 1–1.2 g.
- **The g-force connection:** Downforce essentially multiplies the "effective weight" of the car. A car generating 3 times its own weight in downforce at high speed behaves, from a cornering-g perspective, as if it weighs four times more — allowing proportionally higher lateral g-loads for the same tire coefficient of friction.
- **Trade-offs:** Downforce increases with speed squared, but so does drag. Teams balance high-downforce (slow-speed circuits like Monaco, where lateral g-loads build gradually through tight corners) vs. low-drag (speed circuits like Monza, where top speed matters more than peak cornering g).
- **Ground effect:** Underbody aerodynamics (venturi tunnels) generate especially efficient downforce with lower drag. Modern F1 cars use this to achieve massive total downforce — contributing to the record lateral accelerations seen in recent seasons.

---

## 5. Physical Demands on Drivers

### 5.1 Human Tolerance to G-Forces

- **Tolerance depends on:** magnitude of force, duration, direction relative to the body, where the force is applied, and posture.
- **Horizontal g-forces (perpendicular to spine):** The human body tolerates these much better than vertical g-forces. "Eyeballs-in" (acceleration forwards, driver pressed back into seat) allows the highest tolerance.
  - Untrained humans: up to **20 g for < 10 seconds**, **10 g for 1 minute**, **6 g for 10 minutes**
  - Trained drivers/pilots: can sustain **4–6 g** for extended periods with cognitive function intact
- **Vertical g-forces (along spine):**
  - **Positive g (blood toward feet):** Typical person loses consciousness at ~5 g. Modern pilots with g-suits and straining maneuvers can sustain **9 g** briefly.
  - **Negative g (blood toward head):** Tolerance is only **−2 to −3 g**. Exceeding this causes "redout" — blood-laden eyelids pull into the visual field, risking retinal damage.

### 5.2 Progressive Symptoms of Vertical G-Exposure

| Stage | Symptom | Reversibility |
|-------|---------|---------------|
| Early | **Grey-out** — vision loses hue | Fully reversible on levelling out |
| Mid | **Tunnel vision** — peripheral vision lost | Reversible if g reduced quickly |
| Late | **Blackout** — vision lost, consciousness maintained | May progress to G-LOC |
| Critical | **G-LOC** — g-induced loss of consciousness | Requires immediate g reduction |

### 5.3 Real-World Racing Incidents

- **Highest recorded surviving g-force:** **214 g₀** — Kenny Bräck, 2003 Chevy 500 at Texas Motor Speedway. Wheel-to-wheel contact sent the car into the catch fence at extreme deceleration. He survived, though the event underscores the extreme ranges involved.
- **Routine racing loads:** Open-wheel and touring car drivers regularly experience **4–6 g lateral** through high-speed corners and **5–6 g longitudinal** under braking. Sustained for multiple laps, this creates significant fatigue.

### 5.4 Musculoskeletal & Cardiovascular Strain

- **Neck:** Lateral g-loads create enormous asymmetric loading on cervical muscles. Drivers must actively brace and stabilize the head against the seat/cockpit.
- **Core & upper body:** Sustained g-loading compresses the torso and strains the lower back. Core strength is essential to maintain driving precision under load.
- **Cardiovascular:** Lateral g-forces shift blood toward the outside of the turn, reducing cerebral perfusion and potentially causing momentary cognitive impairment. G-suits (inflatable bladders) and physical training help counteract this.
- **G-hardening:** Progressive training (centrifuge work, exposure research) can improve g-tolerance over time. Some individuals have innate advantages.

---

## 6. Key Formulas for Cornering Analysis

| Quantity | Formula | Notes |
|----------|---------|-------|
| Standard gravity | g₀ = 9.80665 m/s² | Constant at Earth's surface |
| Centripetal acceleration | a = v² / r | v = speed, r = corner radius |
| Centripetal force | F = m × v² / r | m = total car + driver mass |
| Lateral g-load | n = v² / (r × g₀) | Dimensionless; 1 g = 9.81 m/s² |
| Braking distance (at 1 g) | s = v² / (2 × g₀) | ≈ 156 m from 100 km/h at 1 g |
| Velocity change per second | Δv = g₀ × Δt | 1 g ≈ 35.3 km/h gained per second |

---

## 7. Writing Tips for Cornering Pieces

- **Anchor numbers to familiar references:** "4 g lateral is like having your entire body weight pressed sideways against the seat" makes the physics visceral.
- **Distinguish lateral vs. longitudinal:** Braking/acceleration g-forces are longitudinal; cornering g-forces are lateral. They compound in real corners (braking-entry + mid-corner lateral + traction-exit).
- **Contextualize downforce:** Explain *why* an F1 car can corner at 5 g while a road car cannot — it's not just tire grip, it's the aerodynamic downforce multiplying the effective weight.
- **Humanize the physics:** Reference driver symptoms (grey-out, peripheral vision loss, neck strain) to connect the numbers to the lived experience.
- **Cite the data:** Telemetry from data/loggers in the `data/sensors/` folder can show real g-traces from specific corners at specific circuits.

---

*This document is a living reference. Update as new season data and telemetry become available.*