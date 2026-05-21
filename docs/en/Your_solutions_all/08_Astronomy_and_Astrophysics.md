## Section 9: Astronomy and Astrophysics Solutions

### 1. Rotational Velocity

To find the linear speed of a point on the Earth's equator, we use the formula for circular motion:
$$v = \frac{2\pi R}{T}$$

*   **Earth's radius ($R$):** $6378\,\text{km}$
*   **Time for one rotation ($T$):** 24 hours ($24 \times 3600 = 86,400\,\text{s}$) 
*(Note: A precise sidereal day is $86,164\,\text{s}$, but $86,400\,\text{s}$ is standard for this type of problem).*

$$v = \frac{2\pi \times 6378\,\text{km}}{86400\,\text{s}} \approx \frac{40074\,\text{km}}{86400\,\text{s}} \approx 0.464\,\text{km/s}$$

**Answer:** The linear speed at the equator is approximately **$0.464\,\text{km/s}$** (or $464\,\text{m/s}$).

---

### 2. Orbital Mechanics

**Part A: ISS Orbital Speed**
The formula for orbital speed is:
$$v = \sqrt{\frac{GM_E}{r}}$$
where $r$ is the distance from the center of the Earth.
*   $r = R_E + h = 6378\,\text{km} + 400\,\text{km} = 6778\,\text{km} = 6.778 \times 10^6\,\text{m}$
*   $G = 6.674 \times 10^{-11}\,\text{m}^3/\text{kg}\cdot\text{s}^2$
*   $M_E = 5.97 \times 10^{24}\,\text{kg}$

$$v_{ISS} = \sqrt{\frac{(6.674 \times 10^{-11})(5.97 \times 10^{24})}{6.778 \times 10^6}} \approx \sqrt{5.878 \times 10^7} \approx 7667\,\text{m/s} = \mathbf{7.67\,\text{km/s}}$$

**Part B: Earth's Orbital Speed Around the Sun**
Using the circumference of Earth's orbit and its period:
$$v_{Earth} = \frac{2\pi d}{T} = \frac{2\pi(150 \times 10^6\,\text{km})}{365.25 \times 24 \times 3600\,\text{s}} = \frac{942.5 \times 10^6\,\text{km}}{31,557,600\,\text{s}} \approx \mathbf{29.87\,\text{km/s}}$$

**Answer:** Earth's orbital speed around the Sun ($29.87\,\text{km/s}$) is nearly four times **faster** than the ISS orbiting the Earth ($7.67\,\text{km/s}$).

---

### 3. Microgravity

To find gravitational acceleration at the ISS altitude, we use Newton's law of universal gravitation:
$$g' = \frac{GM_E}{r^2}$$
*   $r = 6.778 \times 10^6\,\text{m}$ (from Task 2)

$$g' = \frac{(6.674 \times 10^{-11})(5.97 \times 10^{24})}{(6.778 \times 10^6)^2} = \frac{3.984 \times 10^{14}}{4.594 \times 10^{13}} \approx \mathbf{8.67\,\text{m/s}^2}$$

**Why astronauts feel weightless:** 
The gravity at that altitude is still about $88\%$ as strong as on Earth's surface. However, the ISS and the astronauts inside are in a continuous state of **free fall** toward Earth. Because they are moving forward so fast ($7.67\,\text{km/s}$), the Earth's surface curves away exactly as fast as they fall, creating a relative "zero-g" environment inside the station.

---

### 4. Geostationary Orbit

**Orbital Period:** To remain above the same point on Earth, the satellite's orbital period must exactly match Earth's rotational period. This is one sidereal day: **$23\,\text{hours}, 56\,\text{minutes}, \text{and } 4\,\text{seconds}$** ($86,164\,\text{s}$).

**Altitude Calculation:**
From Kepler's Third Law, derived from equating gravitational force to centripetal force:
$$r^3 = \frac{GM_E T^2}{4\pi^2}$$
$$r^3 = \frac{(3.984 \times 10^{14})(86164)^2}{4\pi^2} = \frac{(3.984 \times 10^{14})(7.424 \times 10^9)}{39.478} \approx 7.49 \times 10^{22}\,\text{m}^3$$
$$r \approx 42,164\,\text{km}$$

This is the distance from Earth's *center*. To find altitude ($h$):
$$h = r - R_E = 42164 - 6378 = \mathbf{35,786\,\text{km}}$$

---

### 5. Escape Velocity

The formula for escape velocity is:
$$v_e = \sqrt{\frac{2GM_M}{R_M}}$$
*   $M_M = 7.35 \times 10^{22}\,\text{kg}$
*   $R_M = 1737\,\text{km} = 1.737 \times 10^6\,\text{m}$

$$v_e = \sqrt{\frac{2(6.674 \times 10^{-11})(7.35 \times 10^{22})}{1.737 \times 10^6}} \approx \sqrt{5.647 \times 10^6} \approx 2376\,\text{m/s} = \mathbf{2.38\,\text{km/s}}$$

**Fraction of Earth's escape velocity:**
$$\frac{2.38\,\text{km/s}}{11.2\,\text{km/s}} \approx \mathbf{0.21}$$
The Moon's escape velocity is roughly **$21\%$** of Earth's.

---

### 6. Solar Gravity

Using the gravity formula $g = \frac{GM}{R^2}$:
*   $M_S = 2 \times 10^{30}\,\text{kg}$
*   $R_S = 6.96 \times 10^8\,\text{m}$

$$g_S = \frac{(6.674 \times 10^{-11})(2 \times 10^{30})}{(6.96 \times 10^8)^2} = \frac{1.335 \times 10^{20}}{4.844 \times 10^{17}} \approx \mathbf{275.6\,\text{m/s}^2}$$

**Weight Increase Factor:**
$$\frac{g_S}{g_{Earth}} = \frac{275.6}{9.8} \approx \mathbf{28.1}$$
Your weight would increase by a factor of roughly **28**.

---

### 7. Megastructures (Dyson Sphere)

First, determine the total surface area ($A$) we can build with Mercury's mass given the density $\sigma = 10\,\text{kg/m}^2$.
$$A = \frac{M}{\sigma} = \frac{3.3 \times 10^{23}\,\text{kg}}{10\,\text{kg/m}^2} = 3.3 \times 10^{22}\,\text{m}^2$$

Next, use the surface area of a sphere formula ($A = 4\pi R^2$) to find the radius $R$:
$$R = \sqrt{\frac{A}{4\pi}} = \sqrt{\frac{3.3 \times 10^{22}}{4\pi}} \approx \sqrt{2.626 \times 10^{21}} \approx 5.12 \times 10^{10}\,\text{m}$$

Converting to kilometers:
$$R \approx \mathbf{51.2\,\text{million km}}$$
*(Context: This is roughly 34% of the Earth-Sun distance, placing the sphere near Mercury's actual orbit).*

---

### 8. Interplanetary Travel

Distance to Mars: $d = 55,000,000\,\text{km}$. Speed formula: $t = d/v$.

**a) Speed of light ($c = 300,000\,\text{km/s}$)**
$$t = \frac{55,000,000}{300,000} = 183.3\,\text{seconds} \approx \mathbf{3\,\text{minutes and } 3\,\text{seconds}}$$

**b) Spacecraft ($v = 40,000\,\text{km/h}$)**
$$t = \frac{55,000,000}{40,000} = 1375\,\text{hours} \approx \mathbf{57.3\,\text{days}}$$

**c) Commercial Airplane ($v = 900\,\text{km/h}$)**
$$t = \frac{55,000,000}{900} \approx 61,111\,\text{hours} \approx 2546\,\text{days} \approx \mathbf{6.97\,\text{years}}$$

---

### 9. Aristarchus’ Method

**1. Earth-Sun Distance ($d_{ES}$)**
In the right triangle, $\cos(\theta) = \frac{\text{adjacent}}{\text{hypotenuse}} = \frac{d_{EM}}{d_{ES}}$.
$$d_{ES} = \frac{d_{EM}}{\cos(89.85^\circ)} = \frac{3.84 \times 10^5\,\text{km}}{0.002618} \approx \mathbf{1.467 \times 10^8\,\text{km}}$$
*(This is 146.7 million km, very close to the true value of 150 million km).*

**2. True Diameter of the Sun ($D_S$)**
Using the small-angle approximation: $\alpha$ in radians is $0.53 \times (\pi / 180) \approx 0.00925\,\text{rad}$.
$$D_S = \alpha \cdot d_{ES} = 0.00925 \times 1.467 \times 10^8\,\text{km} \approx \mathbf{1.357 \times 10^6\,\text{km}}$$

**3. Ratio of True Diameters**
Because both objects have the same apparent angular diameter ($\alpha$), their true diameter ratio equals their distance ratio:
$$\frac{D_M}{D_S} = \frac{d_{EM}}{d_{ES}} = \cos(89.85^\circ) \approx \mathbf{0.002618}$$
*(The Moon's diameter is roughly 1/382 that of the Sun).*

**4. Using $\theta = 89.75^\circ$**
$$d_{ES} = \frac{3.84 \times 10^5\,\text{km}}{\cos(89.75^\circ)} = \frac{3.84 \times 10^5\,\text{km}}{0.004363} \approx \mathbf{8.80 \times 10^7\,\text{km}}$$
**Comment:** A tiny measurement error of just $0.1^\circ$ changes the resulting distance by nearly **60 million kilometers**. Because the cosine of an angle near $90^\circ$ approaches zero very rapidly, the method is hypersensitive to the slightest observational error. This is why Aristarchus' original calculation (using $87^\circ$) severely underestimated the distance.

---

### 10. Measuring the Height of the Atmosphere

**1. Solar Depression Angle ($\phi$)**
The Earth rotates $360^\circ$ in 24 hours ($1440$ minutes). We set up a ratio to find the angle rotated in 40 minutes:
$$\phi = \frac{40\,\text{min}}{1440\,\text{min}} \times 360^\circ = \mathbf{10^\circ}$$

**2. Atmospheric Height ($h$)**
Rearranging the grazing ray formula $\cos\phi = \frac{R_E}{R_E+h}$:
$$R_E + h = \frac{R_E}{\cos\phi}$$
$$h = R_E \left(\frac{1}{\cos(10^\circ)} - 1\right)$$
$$h = 6370 \left(\frac{1}{0.9848} - 1\right) = 6370 (1.01543 - 1) = 6370(0.01543) \approx \mathbf{98.3\,\text{km}}$$
*(Fascinatingly, this medieval estimate is incredibly close to the modern Kármán line at 100 km!)*

***

