# Cornering Physics — G-Force Technical Reference

> Sourced from the Wikipedia article on G-force for race-season cornering analysis.

---

## 1. Lateral G-Loads Through Corners

- **G-force (gravitational force equivalent)** is a mass-specific force — force per unit mass — expressed in units of standard gravity (symbol g or g0). One g equals 9.80665 m/s2.
- G-force is produced only by **mechanical contact forces** (pushes/pulls from surfaces), not by gravity alone. An object in free fall feels 0 g.
- Whenever a vehicle changes **direction**, occupants feel **lateral (side-to-side) forces** produced by the mechanical push of their seats. This is the lateral g-load through a corner.
- The g-force felt is the **vector sum** of all gravitational and non-gravitational forces acting on the body freedom to move.
- For a given g-force, the **stresses inside the body are the same** regardless of whether that g-force is caused by gravity or by a coordinate-acceleration (change in velocity) — meaning cornering g-loads feel identical to standing on a heavier planet.

### Key Formula

For constant-acceleration cornering, the lateral g-load is:

> **a = v^2 / r**

where v = speed and r = corner radius. Dividing by standard gravity (9.81 m/s2) converts to g-units.

**Practical benchmark:** A dragster can exert a horizontal g-force of **5.3 g** when accelerating — a reference point for peak longitudinal (braking/acceleration) loads.

---

## 2. Centripetal Acceleration

- Centripetal acceleration is the inward acceleration that keeps a body moving along a curved path. In a corner, the car (and driver) experience centripetal acceleration directed toward the center of curvature.
- From Newton second law: **F = m x a**. The centripetal force required to hold a line through a corner is proportional to the square of speed and inversely proportional to the radius.
- **1 g = 9.80665 m/s2** means that for every second elapsed, velocity changes by approximately **35 km/h (22 mph)**. This rate-of-change is the basis for estimating how quickly a car can shed speed entering a corner.
- **Braking example:** A car braking at 1 g from 35 km/h stops in 1 second. From 105 km/h, it takes 3 seconds — illustrating why high-speed corners demand earlier, harder braking.
- **Shock vs. sustained g:** Transient acceleration with significant jerk (rate of change of acceleration, in m/s3 or g0/s) is called **shock**. Hitting a lateral bump or wall impact can produce very high peak g in milliseconds, distinct from sustained cornering loads.

---

## 3. The Role of Downforce

- G-force is produced by **surface-contact forces**. In a cornering car, the tires must provide the centripetal force via lateral friction. The maximum friction force is proportional to the **normal force** pressing the tire against the track.
- **Downforce** is the aerodynamic load that pushes the car into the track, increasing the normal force beyond the car static weight.
- More downforce -> more available friction -> higher cornering speeds before the tire grip limit (and thus the g-force limit) is exceeded.
- The **grip circle** concept: tires have a finite friction budget. Braking, accelerating, and cornering all draw from the same pool. Downforce effectively enlarges that pool.
- At high speeds, aerodynamic downforce can exceed the car static weight by 3-5x in modern formula racing, meaning the total normal force — and thus available grip — can be **4-6x the car mass** in g-terms.

---

## 4. Physical Demands on Drivers

### Human G-Tolerance Basics

- Human tolerance depends on: **magnitude** of g-force, **duration**, **direction**, **location of application**, and **posture**.
- The body is flexible and deformable. A brief local impact of hundreds of g may cause no damage (e.g., a slap on the face), but a sustained **16 g for one minute can be deadly**.
- **G-tolerance is partly trainable** and varies between individuals. Cardiovascular health significantly affects tolerance.

### Vertical G-Forces (Spine-Aligned)

- **Positive g** (force pushing blood toward the feet):
  - Untrained person: ~**5 g0** before losing consciousness.
  - Trained pilot with g-suit + straining: sustained **9 g0 (88 m/s2)**.
  - Progression of symptoms: **grey-out** -> **tunnel vision** -> **blackout** -> **G-LOC** (g-induced loss of consciousness) -> death if not quickly reduced.
- **Negative g** (force pushing blood toward the head):
  - Tolerance is much lower: **-2 to -3 g0**.
  - Called **red-out** — vision reddens as blood-laden eyelid is pulled into view. Can cause retinal/brain vessel damage.

### Horizontal G-Forces (Perpendicular to Spine — Cornering Relevance)

- The human body **tolerates lateral (perpendicular-to-spine) g-forces far better** than spine-aligned g-forces.
- **Eyeballs-in** (acceleration forward, driver pushed into seat) > **Eyeballs-out** (acceleration backward, driver pulled from seat) for horizontal loads.
- Untrained human tolerance for horizontal g:
  - Up to **20 g0** for < 10 seconds
  - **10 g0** for 1 minute
  - **6 g0** for 10 minutes
- **John Stapp record (1954):** Survived a peak **46.2 g0** eyeballs-out deceleration (rocket sled, Mach 0.9). Lived cancer-free to age 89.
- **Highest recorded g-force ever survived:** **214 g0** — Kenny Brack, 2003 IndyCar Series finale at Texas Motor Speedway (catch-fence impact). The driver survived.

### Racing Context — Typical Values

- Typical street-car peak lateral g: ~0.8-1.0 g (tire-limited).
- Race-car peak lateral g: ~1.5-2.0 g (slick tires, high downforce).
- Formula 1 peak lateral g: ~2.0-2.5 g (high-speed corners like Silverstone Maggots/Becketts complex).
- These are well within human tolerance — the real challenge is sustained loading, heat, and combined loading profiles.

---

## Quick Reference: G-Force Values in Motorsport

| Scenario | Lateral G | Duration |
|---|---|---|
| Street car cornering | 0.8-1.0 g | Continuous |
| Race car (GP) | 1.5-2.0 g | Continuous |
| F1 high-speed complex | 2.0-2.5 g | 2-5 s |
| IndyCar oval banking | 3.0-4.5 g | Sustained |
| Dragster launch (longitudinal) | ~5.3 g | < 1 s |
| Post-impact shock (Brack 2003) | 214 g | ~0.04 s |

---

## Key Takeaways for Cornering Writing

1. **Lateral g-loads are the core metric** of cornering performance — they define the grip envelope.
2. **Centripetal acceleration scales with v^2/r** — speed and radius are the two levers.
3. **Downforce multiplies the grip budget**, enabling higher cornering g within tire limits.
4. **Drivers tolerate lateral g far better than vertical g** — the challenge is sustained load, heat, and combined braking/cornering/acceleration vectors.
5. **Jerk and shock** matter for wall impacts and bumps, not just steady-state cornering.

---

*Source: Wikipedia, G-force — extracted for race-season technical coverage.*