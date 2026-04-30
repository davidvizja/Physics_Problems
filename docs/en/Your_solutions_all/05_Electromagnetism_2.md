# Section 5: Electromagnetism II & Optics — Annotated Solutions

## 1. Gauss's Law
**Problem:** A point charge of $+2 \text{ C}$ is located at the origin. Calculate the electric flux through a spherical surface of radius $1 \text{ m}$ centered at the origin.

**Explanation:** Gauss's Law states that the total electric flux through a closed surface depends only on the total charge enclosed, not the shape or size of the surface.
**Calculation:** $\Phi_E = \frac{Q_{\text{enc}}}{\varepsilon_0} = \frac{2}{8.854 \times 10^{-12}} \approx 2.26 \times 10^{11} \text{ V}\cdot\text{m}$
**Answer:** $2.26 \times 10^{11} \text{ V}\cdot\text{m}$

---

## 2. Ampere's Law
**Problem:** Two parallel wires $10 \text{ cm}$ apart carry $5 \text{ A}$ in opposite directions. Calculate the magnetic field ($B$) midway between them.

**Explanation:** Each wire creates a circular magnetic field. Using the Right-Hand Rule, we find that for opposite currents, both fields point in the same direction at the midpoint. Thus, the total field is the sum of the two ($B_1 + B_2$).
**Calculation:** $B_{\text{total}} = \frac{\mu_0 I}{\pi r} = \frac{(4\pi \times 10^{-7})(5)}{\pi (0.05)} = 4 \times 10^{-5} \text{ T}$
**Answer:** $40 \mu\text{T}$

---

## 3. Biot-Savart Law
**Problem:** Small segment ($0.1 \text{ m}$) carries $3 \text{ A}$, located $0.2 \text{ m}$ from point $P$.

**Explanation:** The Biot-Savart law calculates the magnetic field contribution from a specific current element. Since the segment is perpendicular to the point, $\sin(\theta) = 1$, simplifying the formula.
**Calculation:** $B = \frac{\mu_0 I \Delta l}{4 \pi r^2} = \frac{(4\pi \times 10^{-7})(3)(0.1)}{4 \pi (0.2)^2} = 7.5 \times 10^{-7} \text{ T}$
**Answer:** $0.75 \mu\text{T}$

---

## 4. Magnetic Torque
**Problem:** Rectangular loop ($0.1 \times 0.05 \text{ m}$) carries $2 \text{ A}$ in a $0.3 \text{ T}$ field.

**Explanation:** Torque occurs because the magnetic field exerts a force on the moving charges in the wire. When the field is parallel to the loop's plane, the torque is at its maximum.
**Calculation:** $\tau = I \cdot A \cdot B = (2)(0.005)(0.3) = 0.003 \text{ N}\cdot\text{m}$
**Answer:** $3 \text{ mN}\cdot\text{m}$

---

## 5. Capacitor Energy
**Given:** $S = 0.02 \text{ m}^2, d = 5 \text{ mm}, V = 500 \text{ V}$.

1. **Capacitance ($C$):** Measures the ability to store charge. $C = \frac{\varepsilon_0 S}{d} = 35.4 \text{ pF}$
2. **Energy ($W$):** Work done to move charges onto the plates. $W = \frac{1}{2} C V^2 = 4.43 \mu\text{J}$
3. **Electric Field ($E$):** The force per unit charge between the plates. $E = \frac{V}{d} = 10^5 \text{ V/m}$
4. **Force ($F$):** The mechanical attraction between the oppositely charged plates. $F = \frac{1}{2} \varepsilon_0 E^2 S = 0.885 \text{ mN}$

---

## 6. EM Wave Analysis
**Wave Equation:** $E_y(x,t) = 100 \sin(10^7 x - \omega t) \text{ V/m}$.

**Explanation:** The wave values are extracted by comparing the equation to the standard form $A \sin(kx - \omega t)$.
* **Direction:** The minus sign in $(kx - \omega t)$ confirms motion in the **$+x$** direction.
* **Wavelength:** Derived from the wave number $k=10^7$. $\lambda = \frac{2\pi}{k} \approx 628 \text{ nm}$.
* **Frequency:** Light speed $c$ is the ratio of $\omega$ to $k$. $\omega = c \cdot k = 3 \times 10^{15} \text{ rad/s}$.
* **Magnetic Field:** $B$ and $E$ are always in phase and perpendicular. $B_0 = \frac{E_0}{c} = 3.33 \times 10^{-7} \text{ T}$.

---

## 7. Light Properties
**Explanation:** Wavelength determines color. $550 \text{ nm}$ is the peak sensitivity for human vision.
* **Color:** **Green**.
* **Frequency:** Calculated using $f = \frac{c}{\lambda} \approx 5.45 \times 10^{14} \text{ Hz}$.

---

## 8. EM Spectrum
**Logic:** Wavelength is inversely proportional to energy.
1. **Gamma rays** (Highest energy, shortest $\lambda$)
2. **X-rays**
3. **Ultraviolet**
4. **Infrared**
5. **Microwaves**
6. **Radio waves** (Lowest energy, longest $\lambda$)

---

## 9. Snell's Law
**Problem:** Air ($n=1$) to Glass ($n=1.5$), $30^\circ$ incidence.

**Explanation:** Light bends toward the normal line when entering a "slower" medium (higher $n$).
**Calculation:** $1 \cdot \sin(30^\circ) = 1.5 \cdot \sin(\theta_2) \implies \sin(\theta_2) = 0.333$
**Answer:** $\theta_2 \approx 19.47^\circ$

---

## 10. Speed of Light in Media
**Explanation:** The index of refraction ($n$) is the ratio of the speed of light in a vacuum ($c$) to its speed in the material ($v$).
**Calculation:** $v = \frac{c}{n} = \frac{3 \times 10^8}{2.42} \approx 1.24 \times 10^8 \text{ m/s}$
**Answer:** $1.24 \times 10^8 \text{ m/s}$
