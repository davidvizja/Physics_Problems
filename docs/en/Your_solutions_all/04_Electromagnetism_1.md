# Section 4: Electromagnetism I - Presentation Solutions

## 1. Coulomb's Law
**Problem:** Four point charges of +1.0 C each are placed at the corners of a square with sides of 1.0 m. Calculate the magnitude and direction of the electric force on a charge of -2.0 C placed at the center of the square.

**Solution:**
The distance $r$ from each corner to the center is identical. Each +1.0 C charge exerts an attractive force on the -2.0 C charge, directed toward the corner. For every force vector pointing toward one corner, there is an equal and opposite force vector pointing toward the diagonally opposite corner.
$$\sum \vec{F} = \vec{F}_1 + \vec{F}_2 + \vec{F}_3 + \vec{F}_4 = 0$$
* **Magnitude:** 0 N
* **Direction:** Undefined (net force is zero)

---

## 2. Electric Potential
**Problem:** Point charges of +1C, -2C, +3C, and -4C are placed at the corners of a square with sides of 1.0 m (in order). Calculate the electric potential at the center.

**Solution:**
Distance $r$ from corner to center: $r = \frac{a\sqrt{2}}{2} = \frac{1}{\sqrt{2}} \text{ m} \approx 0.707 \text{ m}$.
Potential $V$ is a scalar sum:
$$V = \frac{k}{r} \sum q_i = \frac{8.99 \times 10^9}{1/\sqrt{2}} (+1 - 2 + 3 - 4)$$
$$V = 8.99 \times 10^9 \cdot \sqrt{2} \cdot (-2)$$
**Answer:** $V \approx -2.54 \times 10^{10} \text{ V}$

---

## 3. Electrostatic Equilibrium
**Problem:** Find the equilibrium position for $q_3 = +1\text{C}$ between $q_1 = +4\text{C}$ and $q_2 = +9\text{C}$ (distance 2 m).

**Solution:**
Let $x$ be the distance from $q_1$. At equilibrium: $F_{13} = F_{23}$
$$\frac{k q_1 q_3}{x^2} = \frac{k q_2 q_3}{(2-x)^2} \implies \frac{4}{x^2} = \frac{9}{(2-x)^2}$$
Taking the square root:
$$\frac{2}{x} = \frac{3}{2-x} \implies 4 - 2x = 3x \implies 5x = 4$$
**Answer:** $x = 0.8 \text{ m}$ from the +4C charge.

---

## 4. Force Comparison
**Problem:** $F_e$ vs $F_g$ for electron/proton in hydrogen atom ($r \approx 5.3 \times 10^{-11} \text{ m}$).

**Solution:**
* $F_e = \frac{k e^2}{r^2} \approx 8.2 \times 10^{-8} \text{ N}$
* $F_g = \frac{G m_e m_p}{r^2} \approx 3.6 \times 10^{-47} \text{ N}$
**Ratio:** $\frac{F_e}{F_g} \approx 2.3 \times 10^{39}$

---

## 5. Field Levitation
**Problem:** Electric field $E$ to levitate a proton against Earth's gravity.

**Solution:**
$eE = m_p g \implies E = \frac{m_p g}{e}$
$$E = \frac{(1.67 \times 10^{-27})(9.8)}{1.6 \times 10^{-19}} \approx 1.02 \times 10^{-7} \text{ V/m}$$
**Direction:** Upward (to push the positive proton against gravity).

---

## 6. Field from a system of charges
**Problem:** $+q$ at $(-a, 0)$ and $+2q$ at $(a, 0)$.

**Solution:**
1. **General Vector:** $\vec E(x, y) = \frac{kq((x+a)\hat{i} + y\hat{j})}{((x+a)^2 + y^2)^{3/2}} + \frac{2kq((x-a)\hat{i} + y\hat{j})}{((x-a)^2 + y^2)^{3/2}}$
2. **Zero Field:** Occurs at $y=0$. Setting $E_x = 0$ between charges: $\sqrt{2}(x+a) = a-x \implies x = a(3-2\sqrt{2}) \approx -0.17a$.
3. **Calculation:** For $a=0.2, y=0.3, q=2\mu\text{C}$: $\vec{E} \approx (-7.67 \times 10^4 \hat{i} + 3.45 \times 10^5 \hat{j}) \text{ V/m}$.
4. **Limit $y \gg a$:** $\vec{E} \approx \frac{3kq}{y^2}\hat{j}$ (behaves like a single +3q charge).

---

## 7. Cyclotron Motion
**Problem:** Electron radius in $B = 0.1 \text{ T}$ after $V = 5000 \text{ V}$ acceleration.

**Solution:**
$R = \frac{mv}{qB}$ where $v = \sqrt{\frac{2eV}{m}}$
$$R = \frac{1}{B}\sqrt{\frac{2mV}{e}} = \frac{1}{0.1}\sqrt{\frac{2(9.11 \times 10^{-31})(5000)}{1.6 \times 10^{-19}}}$$
**Answer:** $R \approx 2.38 \times 10^{-3} \text{ m}$ (2.38 mm)

---

## 8. Lorentz Force
**Problem:** $F$ for $q=2 \times 10^{-19}\text{C}, v=10^6\text{m/s}, B=0.5\text{T}$ (perpendicular).

**Solution:**
$F = qvB = (2 \times 10^{-19})(10^6)(0.5)$
**Answer:** $F = 1.0 \times 10^{-13} \text{ N}$

---

## 9. Vector Lorentz Force
**Problem:** Proton $\vec{v} = (2, -4, 1)$, $\vec{B} = (1, 2, -1)$.

**Solution:**
$\vec{v} \times \vec{B} = ((-4)(-1) - (1)(2))\hat{i} - ((2)(-1) - (1)(1))\hat{j} + ((2)(2) - (-4)(1))\hat{k} = 2\hat{i} + 3\hat{j} + 8\hat{k}$
Magnitude $|\vec{v} \times \vec{B}| = \sqrt{2^2 + 3^2 + 8^2} = \sqrt{77}$
$F = e \sqrt{77} = (1.6 \times 10^{-19})(8.77)$
**Answer:** $F \approx 1.4 \times 10^{-18} \text{ N}$

---

## 10. Lorentz Force on Wire
**Problem:** $L=2\text{m}, I=10\text{A}, B=0.5\text{T}$.

**Solution:** $F = ILB \sin\theta$
* **a) $90^\circ$:** $10 \cdot 2 \cdot 0.5 \cdot 1 = \mathbf{10 \text{ N}}$
* **b) $45^\circ$:** $10 \cdot 2 \cdot 0.5 \cdot \frac{\sqrt{2}}{2} \approx \mathbf{7.07 \text{ N}}$
* **c) $0^\circ$:** $10 \cdot 2 \cdot 0.5 \cdot 0 = \mathbf{0 \text{ N}}$
