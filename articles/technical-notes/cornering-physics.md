# Cornering Physics — Technical Reference Notes

> Source: Wikipedia — [G-force](https://en.wikipedia.org/wiki/G-force)
> Context: Formula One, IndyCar, and general motorsport cornering dynamics

---

## 1. What Is G-Force?

- **G-force (gravitational force equivalent)** is a **mass-specific force** — force per unit mass — expressed in units of standard gravity (symbol **g** or **g₀**).
- **1 g = 9.80665 m/s²** (≈ 35.3 km/h of velocity change per second). This is the baseline acceleration felt by any object at rest on Earth's surface.
- Technically, g-force is **not a force** — it is an **acceleration** measured relative to free fall. It represents the vector sum of all gravitational and non-gravitational forces acting on an object's freedom to move.
- G-forces are produced only by **mechanical pushes and pulls** (surface-contact forces). Gravitation alone produces **zero g-force** — a condition known as weightlessness.
- When g-force acts on a body, it produces **compressive and tensile stresses** throughout the object. Because these stresses must be transmitted from the surface, large g-forces can be destructive.

**Racing implication:** Every corner, braking zone, and acceleration straight is a g-force event. The driver and car are constantly experiencing lateral, longitudinal, and vertical g-loads simultaneously.

---

## 2. Lateral G-Loads Through Corners

- Whenever a vehicle **changes direction**, occupants feel **lateral (side-to-side) forces** produced by the mechanical push of the seat and restraints.
- Lateral g-force is the **centripetal acceleration** directed toward the center of the turning arc. It is what pushes the driver (and everything loose) sideways.
- The magnitude of lateral g depends on **speed squared divided by the radius of curvature** (a = v²/r). Doubling speed quadruple the lateral g-load for the same corner.
- **Formula for constant acceleration over a distance s:** a = v² / (2s). This shows that tighter corners (smaller effective s) at the same entry speed produce dramatically higher g-loads.
- A **dragster** can exert a **horizontal g-force of 5.3** when accelerating — comparable numbers apply to high-speed oval cornering.

**Racing implication:** Cornering speed is directly limited by the lateral g the tires can generate. Drivers "feel" the limit as the point where tires break traction. Golden lines through corners are those that maximize the radius (and thus minimize required g for a given speed) or allow higher entry speeds within the g-limit.

---

## 3. Centripetal Acceleration

- Centripetal acceleration is the **inward acceleration** required to keep an object moving along a curved path. It is always directed perpendicular to the velocity vector, toward the center of curvature.
- In g-force terms: **lateral g = v² / (r × g₀)**, where v is speed, r is radius, and g₀ is standard gravity (9.80665 m/s²).
- A key insight from the Wikipedia article: **g-force is the vector sum of ALL forces**. In a cornering car, the driver experiences lateral g (from the seat pushing inward) PLUS vertical g (from gravity and aerodynamic downforce) simultaneously. The **resultant g-vector** is what the driver actually feels.
- **Jerk** (rate of change of acceleration, expressed in g₀/s) matters in racing: sudden application of lateral g (e.g., hitting a curbs or a slippery patch) can shock the system far more than sustained g. The article notes that **transient acceleration with significant jerk is called shock**.

**Racing implication:** Smoothness is everything. Drivers who minimize jerk — progressive steering inputs, gradual throttle application — maintain traction better and are faster. Telemetry data (available in `data/telemetry/`) lets us plot jerk curves alongside g-load traces to quantify driving style.

---

## 4. The Role of Downforce

- **Downforce** is the aerodynamic force pushing the car into the track. It acts as **additional normal force** on the tires.
- Since maximum friction (and thus maximum lateral g) is proportional to normal force (**F_friction = μ × F_normal**), downforce directly increases the **cornering g-limit**.
- An F1 car generates downforce levels that can exceed its own weight at high speed. At 200+ km/h, total downforce can be **3–5× the car's static weight**, meaning the car could theoretically hang upside down from the ceiling at sufficient speed.
- The Wikipedia G-force article links to **Formula One** and **Formula One car** as key context, confirming that g-force analysis is central to understanding F1 performance.
- **Ground effect** (used by modern F1 cars with venturi floors) generates especially powerful downforce by shaping airflow to create low pressure beneath the car.
- **Wing angles** (front and rear wings) are adjustable: higher angles produce more downforce but also more **drag**, creating a trade-off between cornering speed and straight-line speed.

**Racing implication:** Downforce is the invisible hand that sets cornering limits. On high-downforce circuits (Monaco, Hungary), cars are incredibly fast through corners but slow on straights. On low-downforce circuits (Monza, Spa), the balance flips. The **g-load a driver experiences in a corner is a direct product of the downforce setup** for that track.

---

## 5. Physical Demands on Drivers

### 5.1 G-Tolerance and Direction

- **Human tolerance depends on five factors:** magnitude of g, duration of application, direction of the force, location of application on the body, and body posture.
- The human body is **more resilient to g-forces perpendicular to the spine** ("eyeballs in" — acceleration from behind the seat, as in braking) than **along the spine** (vertical, "eyeballs out" — acceleration from the seat, as in cornering lateral loads transferred through the seat).
- **Horizontal (eyeballs-in) tolerance** for untrained humans:
  - Up to **20 g₀** for less than 10 seconds
  - **10 g₀** for 1 minute
  - **6 g₀** for 10 minutes (with cognitive facilities intact)
- **Vertical (eyeballs-out) tolerance** is much lower. A typical person loses consciousness around **5 g₀** sustained. Modern pilots using **g-suits and straining maneuvers** can sustain **9 g₀**.
- **Negative g-force** (downward, "red out") tolerance is only **−2 to −3 g₀**. This drives blood to the head and can cause vision reddening, swelling of blood vessels, and potential retinal damage.

### 5.2 The Cascade of Pressure-on-Body Effects ("Grey-Out → Blackout → G-LOC")

As positive vertical g increases progressively:
1. **Grey-out** — vision loses hue (reversible on levelling out)
2. **Tunnel vision** — peripheral vision progressively lost
3. **Blackout** — vision lost while consciousness is maintained (caused by lack of blood flow to the head)
4. **G-LOC** (g-induced loss of consciousness) — full unconsciousness
5. **Death** — if g-forces are not quickly reduced

**Racing implication:** While F1 drivers experience primarily lateral g in corners (which is better tolerated than vertical g), the **sustained lateral loads through long corners** (e.g., Copse at Silverstone, Eau Rouge at Spa) accumulate fatigue. Combined with vertical g from downforce and longitudinal g from braking, the total resultant g-vector is substantial.

### 5.3 record-Breaking G-Forces in Motorsport

- The **highest recorded g-force survived by a human** occurred during the **2003 IndyCar Series finale at Texas Motor Speedway** on October 12, 2003.
- Driver **Kenny Bräck** made wheel-to-wheel contact with **Tomas Scheckter**, resulting in Bräck's car impacting the catch fence.
- The peak g-force recorded was **214 g₀** — an extraordinary survival event.
- The previous record holder for experimental horizontal g-tolerance was **John Stapp**, who survived **46.2 g₀** eyeballs-out and **25+ g₀** for 1.1 seconds in 1954 rocket-sled experiments. He lived to age 89 with no ill effects.

### 5.4 Trainability and Individual Variation

- **G-tolerance is partially trainable.** Drivers can improve their tolerance through physical conditioning (neck strength, cardiovascular fitness, g-suit use).
- There is **considerable variation in innate ability** between individuals.
- **Cardiovascular problems reduce g-tolerance**, which is why driver fitness programs are so rigorous in top-tier motorsport.
- **Vibration at resonant frequencies** of organs or connective tissues can cause severe damage even at relatively low peak g levels — a concern for cars on bumpy circuits.

### 5.5 Measurement and Telemetry

- G-force is measured using **accelerometers** — damped masses on springs calibrated along one or more axes.
- Modern racing telemetry systems use **3-axis accelerometers** mounted in the car (typically near the driver's helmet and at the car's CG) to capture lateral, longitudinal, and vertical g separately.
- This data is what powers the **g-load plots** referenced in multimedia/graphics/ and the **telemetry datasets** in data/telemetry/.

---

## 6. Quick-Reference Formulae

| Concept | Formula | Notes |
|---|---|---|
| Standard gravity | 1 g₀ = 9.80665 m/s² | ≈ 35.3 km/h per second |
| Centripetal acceleration | a = v² / r | v = speed, r = corner radius |
| Lateral g-load | n_lat = v² / (r × g₀) | Dimensionless g |
| Braking g-load | n_brk = v² / (2 × s × g₀) | s = braking distance |
| Friction limit | F_max = μ × N | μ = tire coeff., N = normal force (weight + downforce) |
| Resultant g-vector | n_resultant = √(n_lat² + n_long² + n_vert²) | Combined loading |
| Velocity change | Δv = g₀ × t | Per second of 1 g acceleration |

---

## 7. Key Takeaways for Cornering Analysis

1. **Cornering speed is g-limited.** The driver can only go as fast as the tires allow, and that limit is set by lateral g-load.
2. **Downforce multiplies the limit.** More downforce = more normal force = more friction = higher cornering g before traction is exceeded.
3. **Lateral g is better tolerated than vertical g.** But sustained lateral loading through long corners still fatigues drivers.
4. **Jerk matters.** Sudden changes in lateral g (curb strikes, rain, surface transitions) can shock the system and break traction instantly.
5. **The 214 g₀ survival record** from IndyCar 2003 shows the extreme ranges involved — even routine cornering loads (4–6 g in F1) are significant physical events.
6. **Drivers are trainable** but have innate limits. Fitness programs, g-suits, and technique all play roles in managing g-loads.

---

## Sources

- Wikipedia: [G-force](https://en.wikipedia.org/wiki/G-force)
- Wikipedia: [Formula One car](https://en.wikipedia.org/wiki/Formula_One_car)
- Human tolerance data derived from NASA & military aviation research (as cited in Wikipedia)
- Record: 2003 IndyCar Series finale, Texas Motor Speedway (Kenny Bräck, 214 g₀ peak)
