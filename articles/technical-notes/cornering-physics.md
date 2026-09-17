# Cornering Physics — Technical Reference Notes

> **Source:** Wikipedia articles on *G-force*, *Downforce*, and *Load factor (aeronautics)*  
> **Purpose:** Quick-reference facts for race-season cornering analysis journalism  
> **Last updated:** 2025 race season coverage

---

## 1. G-Force Fundamentals

- **G-force** (gravitational force equivalent) is a **mass-specific force** (force per unit mass), expressed in standard gravity units — symbol **g** or **g₀** (not to be confused with "g" for grams).
- **1 g** = the standard gravitational acceleration at Earth's surface = **9.80665 m/s²** (≈ 35 km/h of velocity change per second).
- G-force is technically a measure of **acceleration**, not force. It is produced only by **mechanical contact forces** — gravitation alone produces no g-force (free-fall = 0 g).
- The g-force felt by an object equals the **vector sum** of all gravitational and non-gravitational forces acting on it, divided by its mass.
- **Transient acceleration** accompanied by significant jerk is called **shock** — relevant for impacts and sudden direction changes.
- **Jerk** is the rate of change of acceleration (m/s³); it matters in racing because sudden g-load changes can be more dangerous than sustained loads.

### Key numbers for motorsport context

| Scenario | G-load |
|---|---|
| Stationary car / straight-line cruising at constant speed | 1 g (vertical) |
| Hard braking at 1 g from 100 km/h | ~1 g longitudinal (deceleration) |
| Dragster peak acceleration | **5.3 g** (horizontal) |
| Typical human horizontal tolerance (short burst, <10 s) | up to **20 g** |
| Trained driver/pilot with g-suit (sustained) | up to **9 g** |
| Peak recorded human survival (IndyCar crash, 2003) | **214 g** (Kenny Bräck catch-fence impact) |

---

## 2. Lateral G-Loads Through Corners

- When a vehicle **changes direction**, the occupants experience **lateral (side-to-side) forces** caused by the mechanical push of the seat. These are sustained g-loads that produce a perception of weight.
- **Centripetal acceleration** is the inward-directed acceleration that keeps the car moving through a curved path. In a corner, the car (and everything in it) is accelerating laterally toward the center of the turn arc.
- The g-force felt laterally is proportional to the **square of the speed** and inversely proportional to the **radius of the turn**:

  > **a = v² / r**

  This means **cornering speed is the dominant factor** — doubling speed quadruples the lateral g-load at the same radius.

- **Negative (downward) g-force** occurs when cresting a hill or at the top of a roller-coaster-like crest on a race track — the car accelerates downward faster than gravity alone, reducing or even reversing the normal load on the car and driver. This causes **redout** (blood rushes to head, vision reddens).
- **Positive (upward) g-force** occurs when the car is pushed up through a valley or bottom of a dip — the road surface pushes upward, adding to the felt weight.

### Driver experience through a corner sequence

1. **Entry braking** — longitudinal negative g (forward weight transfer, front axle load increase)
2. **Turn-in** — lateral positive g builds as centripetal acceleration begins
3. **Apex** — peak lateral g-load; the car's lateral acceleration is near maximum
4. **Exit** — lateral g decreases while longitudinal positive g builds (thrust forward out of the corner)

The **combined load vector** at any point is the vector sum of lateral and longitudinal g-components. A driver modulating both can sustain higher lateral commitments through the corner.

### Typical lateral g-values by category

| Vehicle type | Peak lateral g |
|---|---|
| Everyday road cars | ~0.7–0.9 g |
| Performance road cars | ~1.0–1.2 g |
| Racing cars (F1, IndyCar) | **4–6 g** |
| Rally cars | **3–5 g** (depending on surface) |

---

## 3. Centripetal Acceleration & Cornering Mechanics

- **Centripetal acceleration** (aᶜ = v²/r) is always directed perpendicular to the velocity vector, toward the center of curvature. It does **no work** (it changes direction, not speed), but it is the physical basis of the lateral g-force felt by the driver.
- From the driver's non-inertial reference frame, the **centrifugal effect** appears to push them outward — this is not a real force but the body's inertia resisting the centripetal acceleration. The seat and harness provide the real inward force.
- **Load transfer** during cornering: lateral weight transfer shifts load to the outside tyres and unloads the inside tyres. This reduces total available cornering grip compared to a flat-load scenario, and is a key reason why **anti-roll bars** and **suspension stiffness** settings matter.

### Practical implications

- A car cornering at **3 g lateral** means the tyres must generate **3× the vehicle's weight** in frictional grip — this is why tyre temperature, compound, and inflation pressure are so critical.
- The **friction circle** (grip circle) concept: the total tyre force vector cannot exceed μ × N (coefficient of friction × normal load). Braking, acceleration, and cornering forces compete for the same grip budget. A driver who brakes and turns simultaneously must share the available grip between both tasks.

---

## 4. The Role of Aerodynamic Downforce

- **Downforce** is a **downwards aerodynamic lift force** created by the car's aerodynamic features (wings, diffuser, floor, body shape). Its purpose in a race car is to **increase the vertical load on the tyres**, thereby **increasing grip** and allowing **faster cornering speeds**.
- Downforce effectively increases the "weight" of the car without adding mass — the tyres experience higher normal forces, so they can generate higher friction forces before breaking traction.

### How downforce interacts with cornering g-loads

- A car producing **5,000 N of downforce** at high speed effectively adds that force to the car's weight on all four tyres, increasing the total normal force and thus the maximum lateral grip available.
- This is why **downforce-operating speed** matters enormously: a Formula 1 car may produce over **5× its own weight** in downforce at high speed, enabling lateral cornering accelerations of **5–6 g** or more.
- At **low speeds** (hairpins, pit lane), downforce is minimal, and the car relies almost entirely on **mechanical grip** (tyre friction, suspension geometry).

### Downforce vs. drag trade-off

- All downforce-generating devices (front wing, rear wing, diffuser, floor) also produce **aerodynamic drag**.
- **More downforce** → better cornering capability, but **more drag** → more straight-line speed deficit.
- Teams balance this trade-off by:
  - **High-downforce setups** for slow, twisty circuits (Monaco, Singapore)
  - **Low-downforce / low-drag setups** for high-speed circuits (Monza, Spa)
  - **Adjustable wings and flaps** to fine-tune the balance across different circuit sectors

### Key aerodynamic devices

| Device | Function |
|---|---|
| **Front wing** | Generates front-axle downforce; controls front axle balance; manages airflow underbody and over rear |
| **Rear wing** | Primary high-speed downforce source; adjustable angle of attack |
| **Diffuser** | Accelerates underbody airflow, reducing pressure beneath the car and sucking it toward the ground (ground effect) |
| **Floor / ground effect tunnels** | Uses Venturi effect to generate low pressure under the car; major source of total downforce in modern ground-effect cars |
| **DRS (Drag Reduction System)** | Adjustable rear-wing slot that opens to reduce drag on straights for overtaking |

### Load factor connection

- In aeronautics, **load factor** n = L/W (lift ÷ weight). A load factor of 1 g = straight and level flight. In racing, the equivalent is the **total acceleration load** experienced by the car relative to gravity. Cornering at 5 g lateral means the total load factor vector has a magnitude of approximately √(1² + 5²) ≈ **5.1 g**.

---

## 5. Physical Demands on the Driver

### G-tolerance and physiological limits

- Human tolerance to g-forces depends on **magnitude**, **duration**, **direction**, **application site**, and **posture**.
- **Lateral / "eyeballs-in" (forward, chest-to-seat) g**: best tolerated direction for humans.
  - Untrained subjects: ~**20 g** for <10 s, ~**10 g** for 1 min, ~**6 g** for 10 min.
- **Lateral / "eyeballs-out" (backward, head-to-headrest)**: much worse due to retinal blood vessel sensitivity.
- **Vertical +g (upward, feet-to-head)**: limiting for pilots and drivers.
  - Typical person: ~**5 g** before loss of consciousness (blackout).
  - Trained driver with g-suit + straining: ~**9 g** sustained.
- **Vertical −g (downward, head-to-feet)**: very low tolerance — typically **−2 to −3 g** before **redout** (vision reddens due to blood-laden eyelids in visual field), cerebral oedema, or loss of consciousness.

### Acute g-LOC risk in racing

- **G-LOC** (g-induced loss of consciousness) is a critical hazard: if lateral g-loads drive blood away from the brain during sustained cornering, the driver loses consciousness and cannot steer or brake.
- **Progressive stages:**
  1. **Grey-out** — vision loses hue (easily reversible on levelling out)
  2. **Tunnel vision** — peripheral vision progressively lost
  3. **Blackout** — vision lost while consciousness is maintained (caused by lack of blood flow to head)
  4. **G-LOC** — full loss of consciousness
  5. **Death** — if g-forces are not quickly reduced

- Drivers train to **resist brain blood drain** using special **g-suits** (which compress legs and abdomen) and **straining exercises** (contracting abdominal and leg muscles to push blood back to the brain). Also called **High-G training**.

### Cardiovascular and muscular demands

- Sustained high lateral g-load in a corner sequence can last **multiple seconds** — the driver must maintain grip and concentration under physical stress.
- **Heart rate** during race corners can exceed **150–170 bpm**; the combination of physical exertion, thermal stress, and cognitive load is extreme.
- **Neck and upper-body strength** is essential: the driver's head is restrained by the helmet and HANS device, but lateral g-forces create enormous moment loads on the cervical spine.
- **Heat stress**: cockpit temperatures can exceed **50 °C** in some series, compounding cardiovascular strain and reducing g-tolerance.

### Historical incident reference

- **2003 IndyCar Series finale, Texas Motor Speedway (October 12)**: Kenny Bräck's car made wheel-to-wheel contact with Tomas Scheckter's car, resulting in a catch-fence impact that recorded a peak of **214 g₀** — the **highest g-force ever survived by a human** in a recorded incident. The short shock pulse (fraction of a second) made it survivable, unlike sustained loads at much lower magnitudes.

### g-Hardening

- Preparing an object for g-tolerance (not getting damaged when subjected to high g-force) is called **g-hardening**. This applies to vehicle components, data acquisition equipment, and safety systems in racing.

---

## 6. Quick-Reference Summary

| Concept | Key Fact |
|---|---|
| 1 g | 9.80665 m/s²; baseline gravitational pull at Earth's surface |
| Lateral cornering g | Proportional to v²/r — speed is the dominant variable |
| Centripetal acceleration | Perpendicular to motion; changes direction, not speed; no work done |
| Downforce purpose | Increases tyre normal load → more grip → faster corners |
| Downforce magnitude (F1) | Up to **5× car weight** at high speed |
| Downforce vs. drag | Trade-off: more downforce = more drag = less straight-line speed |
| Human lateral tolerance (trained) | ~20 g for <10 s; ~6 g for 10 min (eyeballs-in) |
| Human vertical +g tolerance (trained) | ~9 g sustained with g-suit |
| G-LOC risk | Sustained lateral g drains blood from brain → unconsciousness |
| Peak recorded g (survived) | 214 g (Bräck, 2003 IndyCar — short shock pulse) |
| Friction circle | Total tyre force ≤ μ × N; braking + cornering share same grip budget |
| Load transfer | Cornering loads outside tyres, unloads inside tyres → reduces total grip |

---

## 7. Suggested Angles for Cornering Analysis Journalism

- **"Why does cornering feel so heavy?"** — The v²/r relationship explains why speed amplifies g-loads non-linearly.
- **"How do drivers survive 5+ g corners?"** — G-suits, straining techniques, High-G training, and physiological adaptation.
- **"Downforce: the invisible tyre"** — How aerodynamic downforce multiplies grip beyond what friction alone can provide.
- **"The drag penalty"** — Why teams sacrifice straight-line speed for cornering grip, and how circuit layout dictates setup choices.
- **"When g-loads go wrong"** — G-LOC, redout, and the thin margin between performance and physiological failure.

---

*These notes are compiled from Wikipedia's* G-force, *Downforce*, *and* Load factor (aeronautics) *articles and are intended as reference material for race-season cornering analysis journalism.*
