# Section 5: Electromagnetism II & Optics Solutions (Updated)

## 1. Gauss's Law
**Problem:** A point charge of $+2 \text{ C}$ is located at the origin. Calculate the electric flux through a spherical surface of radius $1 \text{ m}$ centered at the origin.

**Solution:**
According to Gauss's Law, the total electric flux $\Phi_E$ through any closed surface is equal to the enclosed charge $Q_{\text{enc}}$ divided by the vacuum permittivity $\varepsilon_0$.
$$ \Phi_E = \frac{Q_{\text{enc}}}{\varepsilon_0} $$
Given:
*   $Q_{\text{enc}} = +2 \text{ C}$
*   $\varepsilon_0 \approx 8.854 \times 10^{-12} \text{ C}^2/(\text{N}\cdot\text{m}^2)$

$$ \Phi_E = \frac{2}{8.854 \times 10^{-12}} \approx 2.26 \times 10^{11} \text{ N}\cdot\text{m}^2/\text{C} $$
**Answer:** The electric flux is $2.26 \times 10^{11} \text{ V}\cdot\text{m}$.

---

## 2. Ampere's Law
**Problem:** Two long, parallel wires are $10 \text{ cm}$ apart and carry currents of $5 \text{ A}$ in opposite directions. Calculate the magnitude and direction of the magnetic field at a point midway between the wires.

**Solution:**
The magnetic field $B$ produced by a long straight wire at distance $r$ is $B = \frac{\mu_0 I}{2 \pi r}$. Because the currents are in opposite directions, the fields add up at the midpoint.
Given:
*   $I = 5 \text{ A}$
*   $r = 0.05 \text{ m}$
*   $\mu_0 = 4\pi \times 10^{-7} \text{ T}\cdot\text{m/A}$

$$ B_{\text{total}} = 2 \times \left( \frac{\mu_0 I}{2 \pi r} \right) = \frac{\mu_0 I}{\pi r} $$
$$ B_{\text{total}} = \frac{(4\pi \times 10^{-7})(5)}{\pi (0.05)} = 4 \times 10^{-5} \text{ T} $$
**Answer:** The magnitude of the magnetic field is $40 \mu\text{T}$.

---

## 3. Biot-Savart Law
**Problem:** A small segment of a line wire of length $0.1 \text{ m}$ carries a current of $3 \text{ A}$. The segment is located at a distance of $0.2 \text{ m}$ from a point $P$. Calculate the magnetic field at point $P$ (assume perpendicular).

**Solution:**
Using the Biot-Savart law for a small segment: $dB = \frac{\mu_0 I \Delta l \sin(\theta)}{4 \pi r^2}$
*   $I = 3 \text{ A}$, $\Delta l = 0.1 \text{ m}$, $r = 0.2 \text{ m}$, $\theta = 90^\circ$

$$ B = \frac{(4\pi \times 10^{-7})(3)(0.1)}{4 \pi (0.2)^2} = 7.5 \times 10^{-7} \text{ T} $$
**Answer:** The magnetic field is $0.75 \mu\text{T}$.

---

## 4. Magnetic Torque
**Problem:** A rectangular loop $10 \text{ cm} \times 5 \text{ cm}$ carries $2 \text{ A}$. $B = 0.3 \text{ T}$ is parallel to the plane. What is the magnetic torque?

**Solution:**
$\tau = I \cdot A \cdot B \cdot \sin(\theta)$
*   $A = 0.10 \text{ m} \times 0.05 \text{ m} = 0.005 \text{ m}^2$
*   $\theta = 90^\circ$ (angle between $B$ and the normal vector)

$$ \tau = (2)(0.005)(0.3)(1) = 0.003 \text{ N}\cdot\text{m} $$
**Answer:** The magnetic torque is $3 \text{ mN}\cdot\text{m}$.

---

## 5. Capacitor Energy
**Problem:** $S = 0.02 \text{ m}^2$, $d = 5 \text{ mm}$, $V = 500 \text{ V}$.

1.  **Capacitance:** $C = \frac{\varepsilon_0 S}{d} = \frac{(8.854 \times 10^{-12})(0.02)}{0.005} = 35.4 \text{ pF}$
2.  **Energy:** $W = \frac{1}{2} C V^2 = \frac{1}{2} (3.54 \times 10^{-11})(500)^2 = 4.43 \mu\text{J}$
3.  **Electric Field:** $E = \frac{V}{d} = \frac{500}{0.005} = 10^5 \text{ V/m}$
4.  **Force:** $F = \frac{1}{2} \varepsilon_0 E^2 S = \frac{1}{2}(8.854 \times 10^{-12})(10^5)^2(0.02) = 0.885 \text{ mN}$

---

## 6. EM Wave Analysis
**Problem:** $E_y(x,t) = 100 \sin(10^7 x - \omega t) \text{ V/m}$.

*   **Direction:** Propagates in the $+x$ direction.
*   **Wavelength:** $\lambda = \frac{2\pi}{k} = \frac{2\pi}{10^7} \approx 628 \text{ nm}$.
*   **Angular frequency:** $\omega = c \cdot k = (3 \times 10^8)(10^7) = 3 \times 10^{15} \text{ rad/s}$.
*   **Magnetic Field:** $B_0 = \frac{E_0}{c} \approx 3.33 \times 10^{-7} \text{ T}$.
    $$ B_z(x,t) = 3.33 \times 10^{-7} \sin(10^7 x - 3 \times 10^{15} t) \text{ T} $$

---

## 7. Light Properties
**Problem:** Wavelength $550 \text{ nm}$.
*   **Color:** Green.
*   **Frequency:** $f = \frac{c}{\lambda} = \frac{3 \times 10^8}{550 \times 10^{-9}} \approx 5.45 \times 10^{14} \text{ Hz}$.

---

## 8. EM Spectrum (Increasing Wavelength)
1. Gamma rays
2. X-rays
3. Ultraviolet
4. Infrared
5. Microwaves
6. Radio waves

---

## 9. Snell's Law
**Problem:** $n_1=1.00$, $n_2=1.50$, $\theta_1=30^\circ$.
$$ 1.00 \sin(30^\circ) = 1.50 \sin(\theta_2) \implies \sin(\theta_2) = 0.333 $$
**Answer:** $\theta_2 = 19.47^\circ$.

---

## 10. Speed of Light in Diamond
**Problem:** $n = 2.42$.
$$ v = \frac{c}{n} = \frac{3 \times 10^8}{2.42} \approx 1.24 \times 10^8 \text{ m/s} $$
