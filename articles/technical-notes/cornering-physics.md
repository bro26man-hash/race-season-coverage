# Cornering Physics — G-Force Technical Reference

> Source: Wikipedia — [G-force](https://en.wikipedia.org/wiki/G-force)
> Retrieved for race season cornering analysis coverage.

---

## 1. What Is G-Force?

G-force (gravitational force equivalent) is a **mass-specific force** — force per unit mass — expressed in units of standard gravity (symbol **g** or **g₀**, where 1 g₀ = 9.80665 m/s²). It describes sustained accelerations that cause a perception of weight. Despite the name, g-force is technically a measure of **acceleration**, not force; the actual force arises when a surface pushes on a mass to produce that acceleration.

**Key point for racing:** A driver at rest on Earth's surface experiences 1 g upward from the seat. During cornering, lateral G-loads add a horizontal component, so the total felt g is the vector sum of all forces.

---

## 2. Lateral G-Loads Through Corners

When a car changes direction (cornering), the occupants feel **lateral (side-to-side) forces** produced by the mechanical push of the seat. These are lateral G-loads:

- ** Direction:** Perpendicular to the car's longitudinal axis
- **Magnitude in racing:** Depending on the corner and speed, lateral G-loads inFormula 1 can reach **4–6 g** in high-speed corners; in IndyCar they can exceed **5 g**
- **The physics:** From Newton's second law, the centripetal force required to keep the car on a curved path is F = ma, where a is the centripetal acceleration. The g-load is this acceleration divided by g₀.
- **Load transfer:** Lateral G-loads cause weight transfer to the outside wheels, reducing grip on the inside wheels — a critical factor in cornering behavior and understeer/oversteer balance.

**Key point:** The human body is **better at surviving g-forces perpendicular to the spine** (eyeballs-inForwards) than eyeballs-out (backwards). Racing drivers sit upright, so lateral G-loads are roughly perpendicular to the spine — tolerable to higher levels than rearward-facing g.

---

## 3. Centripetal Acceleration

Centripetal acceleration is the core physics of cornering:

- **Formula:** a_c = v² / r, where v = speed and r = radius of curvature
- **G-load equivalent:** g-load = a_c / g₀ = v² / (r × g₀)
- **Implication:** Doubling speed quadruples the centripetal acceleration (and thus the lateral G-load), while a tighter radius (smaller r) increases it linearly.
- **Practical example:** A car taking a 200 m radius corner at 300 km/h (83.3 m/s) experiences: a_c = (83.3)² / 200 ≈ 34.7 m/s² ≈ **3.5 g** lateral.
- **Combined loads:** In real corners, drivers experience lateral G combined with longitudinal G (braking on entry, accelerating on exit). The total felt g is the vector magnitude: √(a_lat² + a_lon²) / g₀.

**Key point for writers:** The v² relationship means speed is the dominant variable — small increases in entry speed demand大幅 increases in G-load, putting enormous stress on tires and drivers.

---

## 4. The Role of Downforce

Downforce is the aerodynamic force that pushes the car into the track, increasing tire grip and enabling higher cornering speeds:

- **Mechanism:** Airflow over wings, diffusers, and underbody tunnels generates a net downward force — effectively increasing the "weight" of the car without adding mass.
- **G-load amplification:** A car producing 3× its own weight in downforce at high speed can generate **3× the lateral G-load** for a given corner radius, or equivalently, take the corner at **√3 × the speed** with the same G-load.
- **Trade-off:** Downforce increases with speed squared, but so does drag. Teams balance high-downforce (slow, twisty circuits) vs. low-downforce (high-speed ovals / fast circuits) setups.
- **Driver feel:** Drivers sense downforce as increased grip and higher cornering speeds. The transition from low to high downforce (e.g., braking before a high-speed corner) is a key skill — the car's limit shifts dramatically.
- **Stall risk:** If angle of attack exceeds critical, airflow separates and downforce collapses suddenly — a violent loss of grip.

**Key point:** Downforce is what allows modern F1 cars to corner at 5+ g. Without it, the same speed would produce far lower G-loads but also far higher speeds — the fundamental aero trade-off shapes every circuit strategy.

---

## 5. Physical Demands on Drivers

### 5.1 G-Tolerance by Direction

| Direction | Description | Tolerance Limit |
|---|---|---|
| **Eyeballs-in (forwards, chest-to-seat)** | Lateral G perpendicular to spine (racing position) | Up to **20 g** for <10 s; **10 g** for 1 min; **6 g** for 10 min |
| **Eyeballs-out (backwards)** | Lateral G rearward (much rarer) | Significantly lower — retinal blood vessels more vulnerable |
| **Positive vertical (upward, feet-to-head)** | Braking or cornering load vector upward component | ~**5 g** before grey-out; **9 g** sustained with g-suit + straining |
| **Negative vertical (downward, head-to-feet)** | Coasting or slight negative-G moments | **−2 to −3 g** — red-out risk; generally unpleasant |

### 5.2 Physiological Effects of Sustained Lateral G

- **Blood circulation:** Lateral G shifts blood toward the outside (far side) of the body. The heart must work harder to maintain cerebral perfusion on the near side. Prolonged high lateral G can cause **grey-out** (vision losing hue), **tunnel vision** (peripheral loss), and potentially **blackout**.
- **Neck strain:** The driver's head (≈5 kg) effectively becomes 5× heavier at 5 g lateral. Neck muscles must resist this moment continuously — core strength is essential.
- **Breathing:** High G compresses the thorax and makes breathing more difficult. Drivers use specific breathing techniques to maintain oxygenation.
- **Vision:** Even brief grey-out or tunnel vision at corner entry is dangerous. Drivers train to recognize onset and manage it.
- **G-LOC (G-induced Loss of Consciousness):** The ultimate risk — blood drains from the brain, consciousness is lost. In a racing context, this is catastrophic. A ballast + physical conditioning is baseline protection.

### 5.3 Training and Mitigation

- **Physical conditioning:** Neck strengthening, core stability, cardiovascular fitness
- **g-Suits:** Comp Crew suits that apply pressure to legs/abdomen to resist blood shift
- **Straining maneuvers:** Gripping the wheel, tensing legs, controlled breathing
- **Hydration & nutrition:** Dehydration reduces g-tolerance significantly
- **Seat design:** Custom seats support the body and optimize g-force distribution

---

## 6. Record-Breaking G-Forces in Motorsport

- **Highest survived G in racing:** 214 g peak — Kenny Bräck, 2003 Chevy 500 at Texas Motor Speedway, after wheel-to-wheel contact and catch-fence impact.
- **Human horizontal G record:** John Stapp, 46.2 g peak (eyeballs-out, deceleration) in 1954 rocket-sled experiments.

---

## 7. Quick-Reference Formulae

| Quantity | Formula | Notes |
|---|---|---|
| Standard gravity | g₀ = 9.80665 m/s² | Earth surface |
| Centripetal accel. | a_c = v² / r | v in m/s, r in m |
| Lateral G-load | g_lat = v² / (r × g₀) | Direct from speed & radius |
| Total felt G | g_total = √(g_lat² + g_lon²) | Vector magnitude |
| Downforce effect | v_new = v_old × √(DF_ratio) | Speed multiplier for same G with more downforce |
| Braking distance | s = v² / (2 × a_brake) | a_brake in m/s² |

---

## 8. Writing Tips for Cornering Pieces

1. **Lead with the human story** — "At 5 g, driver X's head weighs 25 kg and blood is shifted to one side" is more vivid than "centripetal acceleration of 35 m/s²."
2. **Use the v² relationship** — "Doubling entry speed means quadrupling the G-load on the tires" is intuitive and dramatic.
3. **Contextualize downforce** — "With 3× downforce, the car can take this corner at √3 × the speed with the same G — that's why high-speed circuits demand such different setups than twisty ones."
4. **Reference the tolerance table** — When writing about driver limits, pull from Section 5.
5. **Connect to data** — Cross-reference `data/telemetry/` for lateral G traces and `data/driver-metrics/` for personal tolerance records.

---

*This reference was compiled from the Wikipedia G-force article (https://en.wikipedia.org/wiki/G-force) and adapted for race season cornering analysis. All facts are traceable to the source article; modifications are editorial adaptations for a motorsport audience.*