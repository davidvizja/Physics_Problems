# Section 5: Electromagnetism II & Optics Solutions

## 1. Gauss's Law
**Problem:** A point charge of $+2 \text{ C}$ is located at the origin. Calculate the electric flux through a spherical surface of radius $1 \text{ m}$ centered at the origin.

**Solution:**
According to Gauss's Law, the total electric flux $\Phi_E$ through any closed surface is equal to the enclosed charge $Q_{\text{enc}}$ divided by the vacuum permittivity $\varepsilon_0$. The radius of the sphere is irrelevant as long as it encloses the charge.
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
The magnetic field $B$ produced by a long straight wire at a distance $r$ is given by Ampere's Law: $B = \frac{\mu_0 I}{2 \pi r}$.
Because the currents are in *opposite* directions, the right-hand rule dictates that their magnetic fields point in the *same* direction at the midpoint between them. Therefore, we add their magnitudes.
Given:
*   $I_1 = I_2 = 5 \text{ A}$
*   Total distance $d = 0.10 \text{ m}$
*   Distance to midpoint $r = 0.05 \text{ m}$
*   $\mu_0 = 4\pi \times 10^{-7} \text{ T}\cdot\text{m/A}$

$$ B_{\text{total}} = B_1 + B_2 = 2 \times \left( \frac{\mu_0 I}{2 \pi r} \right) = \frac{\mu_0 I}{\pi r} $$
$$ B_{\text{total}} = \frac{(4\pi \times 10^{-7})(5)}{\pi (0.05)} = \frac{20 \times 10^{-7}}{0.05} = 40 \times 10^{-6} \text{ T} $$
**Answer:** The magnitude of the magnetic field is $40 \text{ \mu T}$. The direction is perpendicular to the plane formed by the two wires (e.g., if the wires lie flat on a table, the field points directly into or out of the table).

---

## 3. Biot-Savart Law
**Problem:** A small segment of a line wire of length $0.1 \text{ m}$ carries a current of $3 \text{ A}$. The segment is located at a distance of $0.2 \text{ m}$ from a point $P$. Calculate the magnetic field at point $P$ (assume perpendicular).

**Solution:**
The Biot-Savart law for a small segment is $dB = \frac{\mu_0 I \Delta l \sin(\theta)}{4 \pi r^2}$.
Given:
*   $I = 3 \text{ A}$
*   $\Delta l = 0.1 \text{ m}$
*   $r = 0.2 \text{ m}$
*   $\theta = 90^\circ \implies \sin(90^\circ) = 1$

$$ B = \frac{(4\pi \times 10^{-7})(3)(0.1)(1)}{4 \pi (0.2)^2} = \frac{10^{-7} \times 0.3}{0.04} = 7.5 \times 10^{-7} \text{ T} $$
**Answer:** magnetic field at point $P$ is $7.5 \times 10^{-7} \text{ T}$ or $0.75 \mu\text{T}$.
---

## 4. Magnetic Torque
**Problem:** A rectangular loop $10 \text{ cm} \times 5 \text{ cm}$ carries $2 \text{ A}$. $B = 0.3 \text{ T}$ is parallel to the plane. What is the magnetic torque?

**Solution:**
The torque on a current loop is $\tau = I \cdot A \cdot B \cdot \sin(\theta)$, where $\theta$ is the angle between the magnetic field and the area vector (normal to the loop). Since the field is *parallel* to the plane, it is perpendicular to the area vector ($\theta = 90^\circ$).
*   Area $A = 0.10 \text{ m} \times 0.05 \text{ m} = 0.005 \text{ m}^2$
*   $I = 2 \text{ A}$
*   $B = 0.3 \text{ T}$

$$ \tau = (2)(0.005)(0.3)\sin(90^\circ) = 0.003 \text{ N}\cdot\text{m} $$
**Answer:** The magnetic torque is $0.003 \text{ N}\cdot\text{m}$.

---

## 5. Energy Stored by charge in a capacitor
**Problem:** Parallel-plate capacitor with $S = 0.02 \text{ m}^2$, $d = 5 \text{ mm}$, $U = 500 \text{ V}$. (Note: $U$ is used here as voltage $V$).

**1. Capacitance ($C$):**
$$ C = \frac{\varepsilon_0 S}{d} = \frac{(8.854 \times 10^{-12})(0.02)}{0.005} = 3.54 \times 10^{-11} \text{ F} = 35.4 \text{ pF} $$

**2. Energy Stored ($W$ or $E$):**
$$ W = \frac{1}{2} C U^2 = \frac{1}{2} (3.54 \times 10^{-11})(500)^2 \approx 4.43 \times 10^{-6} \text{ J} = 4.43 \text{ \mu J} $$

**3. Electric Field Intensity ($E$):**
$$ E = \frac{U}{d} = \frac{500}{0.005} = 100,000 \text{ V/m} = 1.0 \times 10^5 \text{ V/m} $$

**4. Force of Attraction ($F$):**
$$ F = \frac{1}{2} \varepsilon_0 E^2 S = \frac{1}{2}(8.854 \times 10^{-12})(1.0 \times 10^5)^2(0.02) = 8.85 \times 10^{-4} \text{ N} $$

---

## 6. EM Wave Analysis
**Problem:** $E_y(x,t) = 100 \sin(10^7 x - \omega t) \text{ V/m}$.

**Solution:**
Comparing this to the standard wave equation $E(x,t) = E_0 \sin(kx - \omega t)$:
*   **Direction:** The $(kx - \omega t)$ phase indicates propagation in the **$+x$ direction**.
*   **Wavelength ($\lambda$):** Wavenumber $k = 10^7 \text{ rad/m}$. $\lambda = \frac{2\pi}{k} = \frac{2\pi}{10^7} \approx 6.28 \times 10^{-7} \text{ m} = 628 \text{ nm}$.
*   **Angular frequency ($\omega$):** $\omega = c \cdot k = (3 \times 10^8)(10^7) = 3 \times 10^{15} \text{ rad/s}$.
*   **Magnetic field equation:** Amplitude $B_0 = E_0 / c = 100 / (3 \times 10^8) \approx 3.33 \times 10^{-7} \text{ T}$. Since $\vec{E}$ is in the $\hat{y}$ direction and propagation is in $\hat{x}$, $\vec{B}$ must be in the $\hat{z}$ direction ($\vec{E} \times \vec{B}$ points in the direction of propagation).
    $$ B_z(x,t) = 3.33 \times 10^{-7} \sin(10^7 x - 3 \times 10^{15} t) \text{ T} $$

---

## 7. Wavelength and Frequency
**Problem:** Light with wavelength $550 \text{ nm}$. Color and frequency?

**Solution:**
*   **Color:** $550 \text{ nm}$ sits in the middle of the visible spectrum, corresponding to **Green** (specifically, a yellowish-green).
*   **Frequency ($f$):** $f = \frac{c}{\lambda} = \frac{3 \times 10^8}{550 \times 10^{-9}} \approx 5.45 \times 10^{14} \text{ Hz}$.

---

## 8. EM Spectrum
**Problem:** Order by increasing wavelength: Infrared, Ultraviolet, Microwaves, X-rays, Radio waves, Gamma rays.

**Answer:**
1.  Gamma rays (shortest wavelength)
2.  X-rays
3.  Ultraviolet
4.  Infrared
5.  Microwaves
6.  Radio waves (longest wavelength)

---

## 9. Refraction (Snell's Law)
**Problem:** Air ($n=1.00$) into glass ($n=1.50$). Angle of incidence is $30^\circ$.

**Solution:**
Snell's Law: $n_1 \sin(\theta_1) = n_2 \sin(\theta_2)$
$$ 1.00 \cdot \sin(30^\circ) = 1.50 \cdot \sin(\theta_2) $$
$$ 0.5 = 1.50 \cdot \sin(\theta_2) \implies \sin(\theta_2) = \frac{0.5}{1.50} = \frac{1}{3} \approx 0.333 $$
$$ \theta_2 = \arcsin(0.333) \approx 19.47^\circ $$
**Answer:** The angle of refraction is $19.47^\circ$.

---

## 10. Speed of Light in Media
**Problem:** Speed of light in diamond ($n = 2.42$).

**Solution:**
$$ v = \frac{c}{n} = \frac{3 \times 10^8 \text{ m/s}}{2.42} \approx 1.24 \times 10^8 \text{ m/s} $$
**Answer:** The speed of light in a diamond is $1.24 \times 10^8 \text{ m/s}$.
