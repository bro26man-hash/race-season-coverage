# Cornering Physics — Technical Reference Notes

> Source: Wikipedia — [G-force](https://en.wikipedia.org/wiki/G-force)
>
> These notes provide the physics foundations for cornering analysis in race season coverage. Reference them when writing about lateral G-loads, centripetal acceleration, downforce, and driver physical demands.

---

## 1. G-Force Fundamentals

- **Definition:** G-force (gravitational force equivalent) is a **mass-specific force** (force per unit mass), expressed in units of standard gravity (symbol *g* or *g₀*). One *g* equals the standard gravitational acceleration on Earth's surface: **9.80665 m/s²**.
- **Not just gravity:** G-force is produced by **mechanical contact forces** — the push of a seat, the grip of tires on asphalt, the downforce of wings. Objects in free fall experience **0 g** (weightlessness).
- **Vectors matter:** G-force is a vector. Positive g pushes the driver into the seat (downward); negative g pulls them upward (e.g., cresting a hill or pulling out of a dive). **Lateral g** acts side-to-side through corners.
- **Newton's second law in play:** *F = ma*. The force the driver feels is proportional to both the car's acceleration and the driver's mass. A 75 kg driver at 4 g lateral experiences a **~2,940 N lateral force** — equivalent to hoisting a 300 kg weight sideways.

## 2. Lateral G-Loads Through Corners

- **What they are:** Lateral g-forces are the **side-to-side accelerations** a car (and driver) experiences when changing direction through a corner. They are the horizontal component of the total g-vector.
- **How they arise:** Any vehicle change in direction produces lateral forces via **mechanical push** — tire friction, aerodynamic downforce, and road surface reaction. The driver feels these as a sideways lean, resisted by the seat, harness, and their own body tension.
- **Magnitude in racing:** A typical high-performance corner may subject the car and driver to **2–4 g** of lateral acceleration. In extreme cases (e.g., high-speed sweepers like Copse at Silverstone or 130R at Suzuka), lateral g can spike above **5 g**.
- **Combined loading:** Real corners mix lateral, longitudinal (braking/acceleration), and vertical g. The total g-vector is the magnitude of all three components. A driver braking at 1.3 g while carrying 3.5 g lateral is experiencing a combined load of approximately **3.7 g**.

## 3. Centripetal Acceleration

- **The physics:** Circular motion requires a **centripetal acceleration** directed toward the center of the curve: *a_c = v² / r*, where *v* is speed and *r* is the corner radius. This is the acceleration the driver and car must sustain.
- **Speed is squared:** Doubling entry speed **quadruples** the centripetal acceleration required. This is why braking before the apex is critical — carrying too much speed into a corner demands impossible tire grip.
- **Radius matters:** Tight hairpins (small *r*) demand enormous centripetal acceleration even at modest speed. Fast sweepers (large *r*) allow higher speeds with the same g-load.
- **G-force connection:** The lateral g a driver feels IS the centripetal acceleration expressed in g-units. A 150 km/h (41.7 m/s) corner with a 100 m radius produces *a_c = v²/r = 17.4 m/s² ≈ 1.77 g* lateral.

## 4. The Role of Downforce

- **What it does:** Downforce is the **aerodynamic load** pushing the car into the track. It increases the total vertical force on the tires, which in turn increases the **maximum lateral friction force** available for cornering.
- **Direct g-impact:** More downforce = more grip = higher achievable lateral g before the tires saturate. A downforce level equivalent to **3x the car's static weight** at high speed means the tires can generate up to **~3× the cornering g** compared to a low-downforce setup.
- **Trade-off — drag vs. downforce:** Wings and aerodynamic devices that generate downforce also create **drag** (resisting forward motion). Circuits with heavy braking zones (e.g., Monaco) favor lower downforce settings; high-speed circuits with fast corners (e.g., Spa, Monza) favor maximum downforce.
- **Ground effect:** Venturi tunnels under the car generate low pressure beneath the floor, sucking the car toward the track. This is especially efficient because it adds downforce **without proportionally increasing drag**, allowing higher cornering g with less speed loss on straights.
- **Driver feel:** Downforce builds with speed, so the car feels progressively more "stuck" as velocity increases. The driver must adapt throttle application and steering input as aero loads change through a corner — especially on partial-throttle corners where downforce is still building.

## 5. Physical Demands on Drivers

### G-Tolerance and Orientation

- **Horizontal (lateral) g is best-tolerated:** The human body survives lateral acceleration far better than vertical. Untrained humans can withstand **~20 g for <10 seconds** or **~10 g for 1 minute** in the "eyeballs in" direction (chest-to-back, typical of lateral cornering loads).
- **Vertical g is the limit:** Sustained positive vertical g (>~5 g for a typical person) drives blood toward the feet, causing **grey-out → tunnel vision → blackout → g-LOC**. F1 drivers experience vertical g on curb strikes and major bumps, but sustained high vertical g is rare in cornering.
- **Negative g is dangerous:** Downward acceleration (e.g., unloading off a curb or bouncing) can push blood to the head, causing **red-out** and potential retinal damage. Limits are roughly **−2 to −3 g**.

### Circulatory and Vision Effects

- **Grey-out:** Loss of color vision — early warning sign of incipient g-LOC.
- **Tunnel vision:** Peripheral vision closes in as blood drains from the retina.
- **Blackout:** Complete vision loss while consciousness is maintained.
- **G-LOC:** Loss of consciousness — functionally catastrophic for a driver at 300+ km/h.
- **Red-out:** Vision reddens due to blood engorgement in retinal vessels under negative g.

### Musculoskeletal Load

- **Neck strain:** The driver's head (~5 kg) at 4 g lateral becomes an effective **20 kg lateral load** on the neck vertebrae and muscles. Core and neck conditioning is essential for a full season.
- **Upper body:** The driver must resist the lateral force through the seat, harness, and their own forearm/shoulder strength on the wheel. Sustained cornering at 3–4 g is essentially **holding a heavy lateral plank** for the duration of the corner.
- **Legs and feet:** Brake pedal operation at high g requires significant leg strength, especially with carbon-carbon brakes that demand **130–150 kg of pedal force** at max.

### Record-Breaking Human Tolerance

- **John Stapp (1954):** Survived **46.2 g eyeballs-out** deceleration (rocket sled) and **25+ g for 1.1 seconds** — proving the human body's remarkable short-duration tolerance.
- **Kenny Bräck (2003 IndyCar, Texas):** Survived a peak **214 g** impact after wheel-to-wheel contact and catch fence strike — the highest recorded g-force experienced by a surviving human.

---

## Quick Reference — Cornering G-Load Equation

**Total g = √(lateral² + longitudinal² + vertical²)**

| Component | Typical F1 Range | Notes |
|---|---|---|
| Lateral | 2–5 g | Cornering force; depends on speed² / radius |
| Longitudinal (braking) | 1–2 g | Deceleration under braking |
| Longitudinal (acceleration) | 1.5–3 g | Traction out of corner |
| Vertical | 1–2+ g | Curb strikes, bumps, aero downforce |

**Centripetal acceleration:** *a_c = v² / r*  (lateral g = a_c / 9.80665)
**Maximum cornering speed:** *v_max = √(μ × g × r)*  (μ = tire friction coefficient)
**Downforce-enhanced grip:** Effective μ increases with downforce → higher v_max for the same radius

---

*These notes are a starting reference. Supplement with telemetry data from `data/telemetry/` and circuit-specific analysis for each article.*
