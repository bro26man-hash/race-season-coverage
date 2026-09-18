# Cornering Physics — Technical Reference Notes

> **Source:** Wikipedia — [G-force](https://en.wikipedia.org/wiki/G-force)
> **Purpose:** Ready-reference facts for race season cornering analysis writing.
> **Last updated:** 2025 race season coverage.

---

## 1. G-Force Fundamentals

- **Definition:** G-force (gravitational force equivalent) is a **mass-specific force** — force per unit mass — expressed in units of standard gravity (symbol *g* or *g₀*). It is **not** actually a force in the traditional sense; it is a measure of **acceleration** that produces the perception of weight.
- **Standard gravity:** 1 *g* = **9.80665 m/s²** — the acceleration due to gravity at Earth's surface. This value does not vary by location; the *g*-force on the Moon is roughly 1/6 of Earth's.
- **Key distinction:** *g* (lowercase) is the unit; *G* (uppercase) is the gravitational constant. Don't confuse them in copy.
- **G-force vs. gravity:** An object in free fall (e.g., a car airborne over a crest) experiences **0 g** — true weightlessness — because gravity is the only force acting on it. G-force only arises from **mechanical contact forces** (seat, floor, track surface pushing back).

## 2. Lateral G-Loads Through Corners

- **What they are:** When a race car changes direction, the occupants experience **lateral (side-to-side) acceleration**. This is the G-force pushing the driver and car sideways through a corner.
- **The physics:** Per Newton's second law, *F = ma*. The lateral G-load is the centripetal acceleration required to keep the car moving along a curved path, expressed as a fraction of standard gravity.
- **Formula:** For constant cornering speed, lateral acceleration = *v² / r* (velocity squared divided by corner radius). Doubling speed **quadruples** the lateral G-load; tightening the radius (smaller *r*) increases it proportionally.
- **Measured values:** A dragster can exert a horizontal G-force of **5.3 *g*** during acceleration. In race cornering, peak lateral G-loads typically range from **2–6 *g*** depending on the series and corner type.
- **Vector nature:** G-force is a vector. Positive G-points generally describe compression (into the seat/cockpit); lateral G describes side loading. The total G experienced by the driver is the **vector sum** of all gravitational and non-gravitational forces.

## 3. Centripetal Acceleration

- **Definition:** Centripetal acceleration is the inward-directed acceleration required to keep an object moving in a circular path. It is always perpendicular to the object's velocity and directed toward the center of curvature.
- **In cornering:** The tires provide the centripetal force via friction with the track surface. The driver feels this as a lateral push pressing them toward the outside of the corner.
- **Relationship to G-load:** Centripetal acceleration (*aₐ* = *v²/r*) expressed in G-units is simply *v² / (r × g)*, where *g* = 9.80665 m/s².
- **Trade-off:** A driver can carry more speed through a corner (higher *v*) or hit a tighter line (smaller *r*), but both increase centripetal force demand on the tires. There is a **limit** — beyond which the tires exceed their grip envelope and the car slides.

## 4. The Role of Downforce

- **How it works:** Downforce is an **aerodynamic load** pushing the car downward into the track. It effectively increases the normal force between tires and surface without addingmass.
- **Why it matters:** The maximum friction force (grip) is proportional to the normal force: *F_friction = μ × N*. By increasing *N* via downforce, the car can sustain **higher lateral G-loads** without exceeding the tire's friction limit.
- **Speed dependency:** Downforce scales with the **square of speed** — at twice the speed, four times the downforce. This is why high-speed corners (e.g., 130R at Suzuka) generate extreme lateral G-loads that would be impossible at lower speeds.
- **Balance trade-offs:** Front and rear downforce distribution affects cornering balance understeer/oversteer. Engineers tune wing angles and diffuser profiles to achieve the desired G-load distribution.
- **Energy cost:** Generating downforce creates **aerodynamic drag**, which costs straight-line speed. Teams constantly balance downforce levels against drag for each circuit's layout.

## 5. Physical Demands on Drivers

### G-Tolerance
- **Human tolerance** depends on: **magnitude** of the force, **duration** of exposure, **direction** relative to the body, **location** of application on the body, and **posture**.
- The body is **more tolerant of horizontal G-forces** (perpendicular to the spine — "eyeballs in") than vertical forces. Untrained humans can withstand approximately:
  - **20 *g*** for less than 10 seconds
  - **10 *g*** for 1 minute
  - **6 *g*** for 10 minutes
- **Trained drivers and pilots** can push these limits further through physical conditioning, awareness of anti-G straining maneuvers, and in some cases, G-suits.

### Vision Impacts (Positive Vertical G)
As positive G-force increases (blood driven toward the feet):
1. **Grey-out** — vision loses hue; reversible upon straightening
2. **Tunnel vision** — peripheral vision progressively lost
3. **Blackout** — vision lost while consciousness is maintained (dangerous!)
4. **G-LOC** — g-induced loss of consciousness
5. **Death** — if G-forces are not quickly reduced

### Negative G-Force (Red-Out)
- **Downward** G-force drives blood toward the head
- Tolerance is **much lower**: typically **−2 to −3 *g*** before injury
- Causes **red out** — blood-laden lower eyelid pulled into the visual field
- Can cause retinal or brain vessel swelling/rupture

### Neck & Core Strain
- At 4–5 *g* lateral, a driver's head (approximately 5 kg) effectively weighs **20–25 kg** laterally. The neck muscles must hold the head against this load through every corner.
- A full race involves **thousands of cornering inputs** — cumulative strain is immense.
- Core stability iscritical for maintaining pedal control and breathing efficiency under sustained G-loads.

### Record-Breaking G-Forces
- **Highest recorded human-survived G-force:** **214 *g*** — IndyCar driver Kenny Bräck, 2003 Chevy 500 at Texas Motor Speedway. Wheel-to-wheel contact sent his car into the catch fence at extreme speed.
- **John Stapp's rocket-sled experiments:** Survived **46.2 *g*** peak "eyeballs-out" and **25+ *g*** for 1.1 seconds in 1954, proving human limits far exceed everyday expectations.

## 6. Measurement & Technology

- **Accelerometers** are the primary tool for measuring G-force in racing. Multi-axis units capture lateral, longitudinal, and vertical G-loads simultaneously.
- In-vehicle **G-loggers** record data at high sample rates for post-race analysis.
- Engineers use this data to **correlate driver feedback** with objective measurements — essential for setup optimization.

## 7. Quick-Reference Formulae

| Quantity | Formula | Notes |
|---|---|---|
| Standard gravity | *g* = 9.80665 m/s² | Constant |
| Lateral (centripetal) acceleration | *a* = *v² / r* | *v* in m/s, *r* in meters |
| G-load conversion | G = *a* / *g* | Divide m/s² by 9.80665 |
| Speed from G & radius | *v* = √(G × *g* × *r*) | Useful for corner entry speed estimates |
| Braking distance at 1 *g* | *s* = *v² / (2 × g)* | ≈ 20 m from 20 m/s; scales with *v²* |

---

## Editorial Notes

- Use **"G"** for racing context (e.g., "5 *g* lateral"), not to be confused with grams (g).
- Always specify **direction** when discussing G-loads: lateral, longitudinal (braking/acceleration), or vertical.
- When quoting cornering speeds, remember that **G-load scales with the square of speed** — small speed changes have outsized effects.
- Downforce-to-drag ratios vary by series: F1 generates enormous downforce (~3–5 *g* in high-speed corners); lower-formula cars rely more on mechanical grip from tire compounds and suspension geometry.

## Sources

1. Wikipedia, "G-force" — https://en.wikipedia.org/wiki/G-force
2. Wikipedia, "Centripetal acceleration"
3. NASA human centrifuge research & High-G training literature
4. 2003 Chevy 500 incident data (IndyCar Series, Texas Motor Speedway)