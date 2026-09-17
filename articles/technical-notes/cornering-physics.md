# Cornering Physics — Technical Reference Notes

> Source: Wikipedia articles on **G-force** and **Downforce**. Extracted for race season coverage.

---

## 1. G-Force Fundamentals

**G-force (gravitational force equivalent)** is a mass-specific force — force per unit mass — expressed in units of standard gravity (symbol **g** or **g₀**). It is *not* a force in the strict physics sense but rather an acceleration that must be produced by a mechanical contact force.

- **1 g** = standard gravitational acceleration at Earth's surface = **9.80665 m/s²** (≈ 35.3 km/h per second of velocity change)
- An object at rest on Earth's surface experiences **1 g** upward (the resisting reaction of the surface)
- An object in **free fall** (e.g., orbit, ballistic trajectory) experiences **0 g** — weightlessness
- G-force cannot be produced by gravitation alone; it requires mechanical pushes or pulls

**Key equation (Newton's Second Law):**

```
F = m × a
```

A force *F* acting on a body of mass *m* produces acceleration *a*. In racing, every cornering, braking, and accelerating event is governed by this relationship — the car's mass and the driver's mass both respond to the same fundamental forces.

**Example:** A dragster accelerating horizontally can produce **5.3 g** — meaning the driver experiences a force over five times their body weight, directed rearward into the seat.

---

## 2. Lateral G-Loads Through Corners

When a vehicle changes direction, occupants experience **lateral G-forces** (side-to-side) produced by the mechanical push of the seat and the tire contact patches on the road surface.

- Lateral G is the **centripetal acceleration** directed toward the center of the turn's radius
- The faster the car or the tighter the corner, the higher the lateral G-load
- **Typical racing lateral G-loads:**
  - Town circuits / slow corners: **2–3 g**
  - High-speed sweepers (e.g., Spa, Suzuka): **4–5 g**
  - Maximum lateral G in F1: **~6 g** under extreme conditions

**The physics of cornering:**

```
Centripetal acceleration  a_c = v² / r

Where:
  v = speed of the car (m/s)
  r = radius of the corner (m)

The G-load felt by the driver = a_c / g₀ = v² / (r × 9.80665)
```

This means that **doubling speed quadruples the cornering G-load** for the same radius — which is why late-apex lines and throttle application are so critical. A car entering a corner at 2 km/h higher than its apex speed may see cornering G rise by 1–2 g, pushing the tires closer to their grip limit.

---

## 3. Centripetal Acceleration and Tire Grip

Centripetal force is the **net force** acting on the car directing it toward the center of the turn. In a race car, this force is provided entirely by **tire grip** — the friction between the tire contact patch and the track surface.

- The maximum available grip is determined by the **coefficient of friction (μ)** between tire and track, and the **vertical load** on the tires
- **Maximum lateral G ≈ μ × (vertical load / weight)**
- On dry asphalt, μ ≈ 1.0–1.4 for racing slicks; wet surfaces drop to μ ≈ 0.3–0.5

**The downforce feedback loop:**

```
Higher speed → More aerodynamic downforce → Greater vertical load on tires → More available grip → Higher possible cornering G → Faster corner exit speed → Even more downforce on exit
```

This positive feedback loop is why high-downforce architectures (F1, IndyCar) can corner at sustained **5–6 g**, while low-downforce disciplines (IndyCar ovals, some GT series) are limited to **2–3 g** laterally.

---

## 4. The Role of Downforce

**Downforce** is a *downwards* aerodynamic lift force created by wings, diffusers, and underbody channels. Unlike aircraft lift (which acts upward), downforce pushes the car *into* the track:

- **Purpose:** Increase vertical force on tires → more mechanical grip → faster cornering and braking
- **Drag trade-off:** Downforce generates **induced drag**, which slows the car on straights. Teams balance **high-downforce** (slow speed circuits like Monaco) vs. **low-downforce** (high-speed circuits like Monza) setup configurations
- **Ground effect:** Underbody venturi tunnels generate downforce via the **Bernoulli principle** — accelerated airflow under the car lowers pressure, sucking it toward the track. F1 banned ground effect in 1982 and reintroduced it in 2022 with regenerated ground effect floors

**Quantifying downforce in cornering:**

```
Total vertical load = static weight + aerodynamic downforce
Max cornering G = μ × (static weight + downforce) / total mass

Example:
  Car mass: 750 kg
  Static weight: 750 × 9.81 = 7,358 N
  Downforce at 250 km/h: 5,000 N (≈ 680 kg equivalent)
  Total vertical load: 12,358 N
  μ (slick on dry asphalt): 1.2
  Max lateral G = 1.2 × 12,358 / (750 × 9.81) = 2.0 g aerodynamic + 1.2 g static ≈ 3.2 g combined
```

*Note: This is a simplified model. Real-world aerodynamics are direction-dependent — downforce behaves differently in yaw (when the car is rotating through a corner), and floor/g浦区 interactions change with ride height.*

---

## 5. Physical Demands on Drivers

### 5A. Horizontal G-Force Tolerance (Lateral & Longitudinal)

The human body tolerates **perpendicular-to-the-spine** G-forces far better than **along-the-spine** forces:

| Exposure Duration | Horizontal G-Tolerance (eyeballs-in / forward) | Horizontal G-Tolerance (eyeballs-out / rearward) |
|---|---|---|
| < 10 seconds | ~20 g | ~20 g |
| 1 minute | ~10 g | ~10 g |
| 10 minutes | ~6 g | ~6 g |

- **"Eyeballs in"** (forward, driver's back against seat): Blood vessels in the retina are less stressed; highest tolerance
- **"Eyeballs out"** (rearward, driver pushed forward by harness): Blood vessels in the retina are more vulnerable; lower tolerance

**Record for peak experimental horizontal G-force:**

- **John Stapp**, 1954 rocket sled experiments: survived **46.2 g** peak (eyeballs-out) for **1.1 seconds** — still alive 45 years later with no ill effects

### 5B. Vertical G-Force Tolerance (Up & Down)

Vertical G-forces along the spine are the most dangerous:

| G-Level | Effect |
|---|---|
| **+1 g** (normal standing) | Normal blood circulation |
| **+4 to +5 g** | Peak for untrained humans — **grey-out** (vision loses color), then **tunnel vision** |
| **+6 to +9 g** | Trained pilots with **g-suits** and anti-G straining can sustain briefly; risk of **blackout** |
| **+9+ g** | **G-LOC** (g-force induced loss of consciousness) — blood pools in lower body, brain starved of oxygen |
| **−2 to −3 g** (negative / downward) | **Red-out** — blood rushes to head, vision reddens; blood vessels in eyes/brain can swell or burst |

### 5C. Real-World Racing Incidents

- **Highest recorded G-force survived by a driver:** 214 g₀ — **Kenny Bräck**, 2003 Chevy 500 at Texas Motor Speedway. Wheel-to-wheel contact → impact catch fence. Peak recorded at **214 g**, crushing the car's monocoque. Bräck survived.
- **Regular racecornering loads:** Drivers routinely experience **3–5 g** lateral through high-speed corners, sustained for **1–5 seconds** per corner
- **Braking zones:** Longitudinal deceleration of **4–5 g** under braking from high speed

### 5D. Physiological Demands During a Race

- **Neck strain:** At 5 g lateral, a driver's head (approx. 5 kg) effectively weighs **25 kg** — the neck must resist this moment for each corner
- **Cardiovascular stress:** Sustained +Gz loads (vertical, eyeballs-in during braking) drive blood toward feet; heart must work harder to maintain brain perfusion
- **Heat stress:** Cockpit temperatures exceed 50°C; drivers can lose **2–3 kg** (4–6 lbs) of body weight per race through sweat
- **Reaction time:** At 300 km/h, a 0.1 second reaction delay means the car travels **8.3 meters** — every millisecond of cognitive sharpness matters
- **Muscular endurance:** Drivers must maintain firm, precise inputs on the steering wheel and pedals for 1.5–2+ hours.core

---

## 6. Summary: The Core Physics Triangle

For your cornering analysis, the three interlocking principles are:

1. **G-Force = Mass × Acceleration** — Every cornering event is a force balance between the car's inertia and the tire-road interface
2. **Downforce multiplies grip** — Aerodynamic downforce adds to the vertical load budget, directly increasing maximum cornering G
3. **The driver is the limiting factor** — Even with infinite grip, the human body has hard limits on tolerable G-magnitude and duration

These three factors define the **cornering speed envelope**: the maximum speed at which a car can navigate a given turn without exceeding tire grip, aerodynamic limits, or human tolerance.

---

*Notes compiled from Wikipedia: "G-force" and "Downforce." For deeper analysis, consult FIA technical regulations, team telemetry data, and biomechanical literature on driver g-tolerance.*
