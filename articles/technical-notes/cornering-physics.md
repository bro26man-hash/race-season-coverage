# Cornering Physics: Technical Reference Notes

> Source: Wikipedia — [G-force](https://en.wikipedia.org/wiki/G-force), [Centripetal force](https://en.wikipedia.org/wiki/Centripetal_force), [Downforce](https://en.wikipedia.org/wiki/Downforce)
>
> Prepared for race season coverage — cornering analysis section.

---

## 1. Core Concepts

### What Is G-Force?

G-force (gravitational force equivalent) is a **mass-specific force** — force per unit mass — expressed in units of standard gravity (symbol **g** or **g₀**, not to be confused with "g" for grams). It is used for **sustained accelerations** that cause a perception of weight.

- **1 g** = standard gravitational acceleration at Earth's surface = **9.80665 m/s²** (≈ 9.8 m/s²)
- 1 g equates to a velocity change of approximately **35 km/h (22 mph) per second**
- An object at rest on Earth's surface is subject to 1 g upward (the ground pushing up, preventing free fall)
- An object in free fall experiences **0 g** (weightlessness)

> **Note:** The term "g-force" is technically a measure of *acceleration*, not force. It is an acceleration that must be produced by a **mechanical force** — it cannot be produced by gravitation alone. Objects acted upon only by gravitation feel weightless.

### Lateral G-Loads Through Corners

Whenever a vehicle changes **direction** (not just speed), occupants experience **lateral (side-to-side)** forces produced by the mechanical push of their seats. These are the lateral G-loads that define cornering performance.

- Lateral G-loads are **perpendicular to the direction of travel**
- They are felt as a sideways push into the car seat or door
- The magnitude depends on corner speed and radius: **a = v² / r** (centripetal acceleration)
- In a corners, the tires must generate enough lateral friction force to provide the required centripetal acceleration

**Key distinction:**
- **Longitudinal G-loads** = forward/backward (acceleration, braking, traction)
- **Lateral G-loads** = side-to-side (cornering, direction changes)

Both are mechanical forces transmitted through the driver's seat and harness, producing compressive and tensile stresses throughout the body.

---

## 2. Centripetal Acceleration in Cornering

### The Physics

**Centripetal force** (from Latin *centrum* "center" + *petere* "to seek") is the force that makes a body follow a curved path. Its direction is always **orthogonal to the motion** and指向 towards the instantaneous center of curvature.

For a car cornering on a circular arc:

- **Centripetal acceleration:** a_c = v² / r
  - v = cornering speed (m/s)
  - r = radius of the corner (m)
- **Centripetal force required:** F_c = m · v² / r
  - m = mass of car + driver (kg)

This is the **net lateral force** that must be supplied by tire grip. If the required centripetal force exceeds what the tires can provide (μ · N, where μ is the friction coefficient and N is the normal force), the car slides off line.

### Real-World Cornering Numbers

| Scenario | Typical Lateral G | Notes |
|----------|------------------|-------|
| Gentle road corner | 0.3 – 0.5 g | Everyday driving |
| Moderate speed circuit corner | 1.0 – 1.5 g | Enjoyable but firm |
| High-speed racing corner | 2.0 – 3.0 g | Professional level |
| Extreme brakes + corner combo | up to 4 – 5 g | Combined loading |
| Dragster straight (longitudinal) | 5.3 g | Reference from Wikipedia |

### The v²/r Relationship

The critical insight for writers: **doubling corner speed quadruples the lateral G-load** (since a = v²/r). A 150 km/h corner that produces 2 g becomes a **4 g** challenge at 210 km/h — the same radius. This is why racing lines, apex precision, and bravery are so visually dramatic.

**Stopping distance at 1 g braking:**
- At 35 km/h → stops in **1 second**
- At 105 km/h → stops in **3 seconds** (same deceleration)
- Formula for constant acceleration over distance s: **a = v² / (2s)**

---

## 3. The Role of Downforce

### What Is Downforce?

Downforce is a **downwards lift force** created by aerodynamic features (wings, diffusers, bodywork) designed to do the *opposite* of aircraft lift — push the car into the track.

**Purpose:** Increase the **vertical load** on the tire contact patches, which directly increases the **maximum friction force** (grip) available:

> Maximum lateral force = μ × N
> 
> Where N = weight + downforce

### Why It Matters for Cornering

- More downforce → more normal force on tires → more grip → **higher possible lateral G-loads** before sliding
- Downforce allows cars to maintain grip at speeds that would be impossible without it
- At high speed, aerodynamic downforce can be **several times the car's static weight** (F1 cars can generate ~5 g of aerodynamic load at top speed)
- This is why straights are slower in F1 than some road-course sections — the sacrifice in straight-line speed buys enormous cornering grip

### The Trade-Off

- **More downforce** = better cornering grip, but more aerodynamic drag (slower straights)
- **Less downforce** = less drag (faster straights), but less cornering grip
- Teams fine-tune **wing angles** and **diffuser profiles** to balance this for each circuit
- This is why setups differ drastically between, say, Monaco (max downforce) and Monza (min downforce)

---

## 4. Physical Demands on Drivers

### Human Tolerance — Horizontal (Lateral) G-Forces

The human body tolerates lateral G-forces **far better** than vertical ones (perpendicular to the spine). Key data:

| Exposure Duration | Untrained Human | Notes |
|-------------------|----------------|-------|
| < 10 seconds | ~20 g | Cognitive function intact |
| 1 minute | ~10 g | Can perform simple tasks |
| 10 minutes | ~6 g | Sustained watch |

- **"Eyeballs in"** (acceleration forwards, driver lying back): higher tolerance
- **"Eyeballs out"** (acceleration backwards, driver pushed into harness): lower tolerance — retinal blood vessels are more sensitive

### The Danger Zone — Vertical G-Forces

For comparison, **vertical** G-forces (along the spine) are far more dangerous:

- **Typical person:** ~5 g before losing consciousness
- **Trained pilot with g-suit + straining:** ~9 g sustained
- **Negative g (downward):** tolerance is only **−2 to −3 g** — called "red out" (blood rushes to head, vision reddens)
- Progression: **Grey-out** → **Tunnel vision** → **Blackout** → **G-LOC** (g-force induced loss of consciousness) → Death

### Record-Breaking G-Forces

- **John Stapp (1954):** Survived **46.2 g** peak "eyeballs-out" deceleration and **25 g for 1.1 seconds** in rocket sled experiments. Lived to age 89 with no ill effects.
- **Kenny Bräck (2003 IndyCar, Texas):** Survived a peak of **214 g** during a crash — the **highest recorded G-force experienced by a human who survived**. Wheel-to-wheel contact → catch fence impact.

### What This Means for Race Coverage

- Drivers experience **sustained 2–4 g** through technical corners on a typical lap
- **Braking zones** combine longitudinal (backward) and lateral G-loads simultaneously
- **Cognitive performance** matters: at 5+ g, reaction times degrade; at G-LOC, the driver is unconscious
- **g-hardening** (preparing equipment to withstand high G) relevant to onboard cameras, sensors, and telemetry hardware
- **Jerk** (rate of change of acceleration, measured in g₀/s) matters for driver comfort and mechanical feed-down — sudden G-spikes are more punishing than gradual ones

---

## 5. Measurement & Instrumentation

- **Accelerometers** measure g-force along one or more axes — three-axis units are standard in modern racing
- A three-axis accelerometer outputs **0 g on all axes** in free fall (ballistic trajectory)
- Racings' **impact data recorders** (IDRs) and **accelerometer systems** log lateral and longitudinal G-loads for post-crash analysis
- Telemetry systems transmit real-time G-load data to engineers for setup decisions

---

## 6. Key Formulas Summary

| Concept | Formula | Variables |
|---------|---------|----------|
| Standard gravity | g₀ = 9.80665 m/s² | — |
| Velocity change per second at 1 g | ≈ 35.3 km/h per second | — |
| Centripetal acceleration | a_c = v² / r | v = speed, r = radius |
| Centripetal force | F_c = m · v² / r | m = mass |
| Constant acceleration (distance) | a = v² / (2s) | s = distance |
| Maximum friction (grip) | F_max = μ × N | μ = friction coeff, N = normal force |
| Normal force with downforce | N = mg + F_downforce | — |
| Jerk (rate of G-change) | j = da/dt | units: g₀/s or m/s³ |

---

## 7. Narrative Hooks for Race Writing

1. **"The 4-second rule"** — At 1 g braking, a car at 105 km/h needs 3 seconds to stop. In a 2 g combined corner-brake zone, the driver is managing 4+ g of total acceleration vector — and making split-second calls.

2. **"Why the apex is everything"** — A tighter radius (later apex) means higher v²/r = more G required. Drivers minimize this by maximizing radius through the corner — the difference between a good and great line is often 0.5–1 g.

3. **"Downforce is free speed"** — Every extra kilogram of downforce is like adding weight that presses the tires sideways. But it costs drag. The setup conference call between engineer and driver is a constant negotiation: "How much downforce can we run without killing us on the straights?"

4. **"The 214-G man"** — Kenny Bräck's 2003 crash is a textbook case: the human body survived over 200 g. It contextualizes just how extreme the physical toll of a speared can be — and how remarkable elite drivers are at tolerating sustained loads.

5. **"Grey-out at 5 g"** — When a driver reports "I'm seeing grey" after a brutal corner, that's not a figure of speech. It's the beginning of G-LOC. Understanding this makes your commentary more vivid and informed.

---

*All facts sourced from Wikipedia articles on G-force, Centripetal force, and Downforce. For updated data, re-extract from the latest article revisions.*