# Cornering Physics: G-Force Technical Reference

> Source: Wikipedia — [G-force](https://en.wikipedia.org/wiki/G-force), [Centripetal acceleration](https://en.wikipedia.org/wiki/Centripetal_acceleration), [Downforce](https://en.wikipedia.org/wiki/Downforce)
>
> Prepared for race season coverage — cornering analysis series

---

## 1. G-Force Fundamentals

- **Definition:** G-force (gravitational force equivalent) is a **mass-specific force** (force per unit mass), expressed in units of standard gravity (symbol **g** or **g₀**). One g = 9.80665 m/s² — the acceleration due to gravity at Earth's surface.
- **Not to be confused:** "g" (lowercase) is the symbol for grams in SI; "G" (uppercase) is the gravitational constant. G-force is technically a measure of **acceleration**, not force.
- **Key principle:** G-force is only produced by **mechanical pushes and pulls** — not by gravitation alone. An object in free fall experiences 0 g (weightlessness).
- **Directionality:** Positive g-forces point downward (producing upward acceleration); negative g-forces point upward (producing downward acceleration). In racing, lateral and longitudinal axes matter most.
- **Equation:** Weight = mass × (−g-force). The minus sign means the actual reaction force opposes the direction of the g-force acceleration.

---

## 2. Lateral G-Loads Through Corners

- **What they are:** Lateral g-forces are the side-to-side accelerations experienced when a car changes direction through a corner. They are a form of **coordinate acceleration** produced by mechanical friction between tires and track.
- **How they feel:** Every vehicle change of direction produces lateral forces felt by the driver, transmitted through the seat and harness. These are **sustained accelerations** that cause a perception of weight pushing the driver sideways.
- **Measurement:** Lateral g-loads are captured using a **three-axis accelerometer** mounted in the car. When the car corners, the accelerometer registers positive or negative acceleration on the lateral axis.
- **Typical racing values:** While dragsters can exert **5.3 g horizontal** during straight-line acceleration, cornering g-loads in high-speed series (F1, IndyCar) regularly reach **4–6 g lateral** in fast corners and can spike higher in tight sections.
- **Formula context:** For constant acceleration over a distance: `a = v² / (2s)`. For cornering, centripetal acceleration = `v² / r` (velocity squared divided by corner radius). Faster speed or tighter radius = higher lateral g.

---

## 3. Centripetal Acceleration in Cornering

- **Definition:** Centripetal (radial/normal) acceleration is the component of acceleration that **changes the direction** of an object's velocity — it points toward the center of the curved path.
- **Role in racing:** When a car navigates a corner, centripetal acceleration is provided by the **lateral friction force** between the tires and the track surface. Without it, the car would continue in a straight line (Newton's first law).
- **Key relationship:** Centripetal acceleration = `v² / r`. This means:
  - Doubling speed **quadruples** the lateral g-load
  - Halving the corner radius **doubles** the lateral g-load
- **Tangential vs. radial:** Racing corners involve both — tangential acceleration (speeding up or braking along the arc) and radial acceleration (changing direction). The combination determines the total g-vector the driver experiences.
- **Practical impact:** The g-force equation `a = v² / (2s)` shows that at 35 km/h, a 1 g braking stops you in 1 second. Scale that to cornering speeds of 300+ km/h and tight radiuses, and lateral loads become extreme.

---

## 4. The Role of Downforce

- **Definition:** Downforce is a **downwards lift force** created by aerodynamic features (wings, diffusers, sidepods, floor). Its purpose: **increase the vertical load on the tires**, creating more grip.
- **How it works:** Unlike aircraft lift (which pushes up), downforce pushes the car harder into the track. This increases the **maximum lateral friction force** available, allowing higher cornering speeds at the same g-level — or the same cornering speed at lower g-levels.
- **Speed dependency:** Downforce scales with **velocity squared**. Double the speed → four times the downforce → four times the potential lateral grip. This is why high-speed corners (Monza, Silverstone) are where aero packages pay off most.
- **Trade-offs:** Downforce creates **drag**, which penalizes straight-line speed. Teams balance high-downforce setups (slow, twisty circuits) vs. low-downforce runs (high-speed ovals and power circuits).
- **Driver feel:** From the driver's perspective, increased downforce means the car "sits" more planted through corners. The g-loads they experience are higher, but the car remains可控 because the additional grip keeps tire slip angles within the optimal window.
- **Without downforce:** A car relying only on mechanical grip (friction coefficient × normal force from weight) would be limited to much slower cornering speeds. Downforce effectively multiplies the "weight" pushing the tires into the track at high speed.

---

## 5. Physical Demands on Drivers

### 5.1 G-Tolerance by Direction

- **Eyeballs-in (forward/longitudinal):** The body is most tolerant when acceleration is **perpendicular to the spine** (driver lying on their back, force pushing from behind). Untrained humans can withstand **20 g for <10 seconds**, **10 g for 1 minute**, or **6 g for 10 minutes**.
- **Eyeballs-out (rearward):** Tolerance is significantly lower. Blood vessels in the retina are more vulnerable in this direction.
- **Vertical (up/down along spine):** A typical person can handle about **5 g** before losing consciousness. With g-suits and muscle straining, modern pilots sustain **9 g**.
- **Negative g (downward):** Tolerance is much lower: **−2 to −3 g**. Causes "red out" — blood vessels in eyes/brain swell or burst, potentially causing degraded sight or blindness.

### 5.2 What Happens in the Body During High-Speed Cornering

- **Blood redistribution:** Lateral g-forces drive blood toward the outside of the turn. The driver's body must resist this through **core and neck muscle tension** to maintain blood flow to the brain.
- **Vision effects:** Sustained lateral g can cause **grey-out** (loss of color hue), **tunnel vision** (peripheral vision loss), and potentially **blackout** — the same progression as vertical g, but oriented sideways.
- **Respiratory impact:** Deep lateral g-loads make it harder to breathe. Drivers report **shallow breathing** and reduced oxygen intake through sustained high-speed corners.
- **Neck strain:** The driver's head and helmet (~5–7 kg) effectively becomes heavier under g-loading. At 5 g lateral, the neck supports the equivalent of **25–35 kg** — sustained over a stint is a major physical demand.
- **G-hardening:** Preparing the body to withstand high g-forces without damage is called **g-hardening**. This includes physical training (neck strengthening, core work), g-suit usage, and hydration protocols.

### 5.3 Extreme Cases

- **Record survival:** The highest recorded g-force survived by a human was **214 g** during the 2003 IndyCar Series finale at Texas Motor Speedway (Kenny Bräck's car hit the catch fence after wheel-to-wheel contact).
- **Dragster reference:** A top fuel dragster can exert **5.3 g horizontal** during acceleration — sustained for seconds.
- **Thermal compounding:** In a race car, drivers face simultaneous g-loading **and** high cockpit temperatures (often 50°C+), compounding dehydration and fatigue.

---

## 6. Measurement & Reporting Tips

- **Accelerometers** are the primary tool — calibrated to measure g-force along one or more axes. A three-axis unit captures lateral, longitudinal, and vertical g simultaneously.
- **Report convention:** Always specify the **axis** and **duration** alongside g-values (e.g., "5.2 g lateral for 3.2 seconds through Turn 7").
- **Jerk matters:** The rate of change of acceleration (g/s) affects how sudden the load feels. A sharp takeover might spike to 6 g in 0.5 s, while a gradual corner builds more gently — both produce the same peak but very different driver experiences.
- **Data-to-narrative:** Pair telemetry g-plots with sector times and driver quotes to make the physics tangible for readers.

---

## Quick Reference Card

| Parameter | Value | Context |
|---|---|---|
| 1 g | 9.80665 m/s² | Earth surface gravity |
| Horizontal (eyeballs-in) max | 20 g | <10 seconds, untrained human |
| Horizontal sustained | 6 g | 10 minutes, untrained human |
| Vertical positive max | ~5 g | Untrained; 9 g with g-suit |
| Vertical negative limit | −2 to −3 g | Red out risk |
| Dragster horizontal | 5.3 g | Sustained acceleration |
| Racing car cornering | 4–6 g lateral | Fast corners, F1/IndyCar |
| Highest survived | 214 g | 2003 IndyCar, Bräck |
| Downforce scaling | ∝ v² | Double speed = 4× downforce |
| Neck load at 5 g | ~25–35 kg | Head + helmet effective weight |

---

*Last updated: Race season coverage setup. Next step: populate with season-specific telemetry data and driver physical profiles.*