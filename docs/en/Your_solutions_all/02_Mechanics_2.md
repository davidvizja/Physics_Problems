# Section 2: Mechanics II - Solutions & Explanations

---

## 1. Gravitational Dependence

**Problem:** A pendulum has a period of 4s on Earth. Find its period on the Moon ($g_m \approx g/6$) and find the length required for a 1s period on Earth.

**Explanation:**
The period $T$ of a simple pendulum is given by:
$$T = 2\pi\sqrt{\frac{L}{g}}$$

* **Period on the Moon:**
    Since $g_{moon} = \frac{g_{earth}}{6}$, the period is proportional to $1/\sqrt{g}$.
    $$T_{moon} = T_{earth} \times \sqrt{6} = 4 \times \sqrt{6} \approx 9.80\text{ s}$$
* **Length for 1s Period on Earth:**
    Rearranging for $L$: $L = \frac{g T^2}{4\pi^2}$.
    $$L = \frac{9.81 \times 1^2}{4\pi^2} \approx 0.248\text{ m (or 24.8 cm)}$$

---

## 2. Harmonic Motion

**Problem:** $m = 10\text{ kg}$, $x(t) = 0.2 \cos(10\pi t)$. Find $k$ and total energy.

**Explanation:**
The standard form is $x(t) = A \cos(\omega t)$.
From the equation: $A = 0.2\text{ m}$ and $\omega = 10\pi\text{ rad/s}$.

* **Spring Constant ($k$):**
    Using $\omega^2 = \frac{k}{m}$:
    $$k = m\omega^2 = 10 \times (10\pi)^2 = 1000\pi^2 \approx 9869.6\text{ N/m}$$
* **Total Mechanical Energy ($E$):**
    $$E = \frac{1}{2} k A^2 = \frac{1}{2} (1000\pi^2) (0.2)^2 = 20\pi^2 \approx 197.4\text{ J}$$

---

## 3. Conservation of Energy

**Problem:** $L = 1.0\text{ m}$, $\theta = 15^\circ$. Find speed at the bottom.

**Explanation:**
Using Conservation of Energy: $mgh = \frac{1}{2}mv^2 \implies v = \sqrt{2gh}$.
The height $h$ dropped is $L - L\cos\theta$:
$$h = 1.0(1 - \cos 15^\circ) \approx 0.0341\text{ m}$$
$$v = \sqrt{2 \times 9.81 \times 0.0341} \approx 0.818\text{ m/s}$$

---

## 4. Energy & Momentum

**Problem:** $0.5\text{ kg}$ block falls $3.0\text{ m}$ and hits a resting $1.5\text{ kg}$ block (sticks). Find final speed.

**Explanation:**
1.  **Speed before collision ($v_1$):** $v_1 = \sqrt{2gh} = \sqrt{2 \times 9.81 \times 3} \approx 7.67\text{ m/s}$.
2.  **Conservation of Momentum:** $m_1 v_1 = (m_1 + m_2) v_f$.
    $$(0.5)(7.67) = (0.5 + 1.5) v_f \implies 3.835 = 2 v_f \implies v_f \approx 1.92\text{ m/s}$$

---

## 5. Inelastic Collision

**Problem:** $70\text{ kg}$ runner ($3\text{ m/s}$) jumps on $140\text{ kg}$ cart. Final speed? Is $K$ conserved?

**Explanation:**
* **Final Speed:** $m_1 v_1 = (m_1 + m_2) v_f$.
    $$70 \times 3 = (70 + 140) v_f \implies 210 = 210 v_f \implies v_f = 1\text{ m/s}$$
* **Conservation of Energy:** No, kinetic energy is not conserved in a perfectly inelastic collision. It is lost to heat and deformation.
    $$K_i = \frac{1}{2}(70)(3^2) = 315\text{ J} \quad \text{vs} \quad K_f = \frac{1}{2}(210)(1^2) = 105\text{ J}$$

---

## 6. Energy Dissipation

**Problem:** Drop height $2.0\text{ m}$. Loses 30% energy per bounce. Height after 2nd bounce?

**Explanation:**
Energy is proportional to height ($E = mgh$). If it loses 30%, it retains 70% ($0.7$).
* Height 1: $h_1 = 2.0 \times 0.7 = 1.4\text{ m}$
* Height 2: $h_2 = 1.4 \times 0.7 = 0.98\text{ m}$

---

## 7. Dynamics with Friction

**Problem:** $m_1=5\text{ kg}$ (top, tied), $m_2=10\text{ kg}$ (bottom, pulled $45\text{ N}$). $\mu_k = 0.2$. Find $a$ of $m_2$.

**Explanation:**
Two friction forces act on the bottom block ($m_2$):
1.  Friction from top block: $f_1 = \mu_k m_1 g = 0.2 \times 5 \times 9.81 = 9.81\text{ N}$
2.  Friction from floor: $f_2 = \mu_k (m_1 + m_2) g = 0.2 \times 15 \times 9.81 = 29.43\text{ N}$
Net Force on $m_2$: $F_{net} = 45 - 9.81 - 29.43 = 5.76\text{ N}$.
$$a = \frac{F_{net}}{m_2} = \frac{5.76}{10} = 0.576\text{ m/s}^2$$

---

## 8. Work of a Variable Force ($F = -kx$)

**Explanation:**
* **Equation of Motion:** $m \frac{d^2x}{dt^2} = -kx \implies x(t) = A\cos(\omega t + \phi)$ where $\omega = \sqrt{k/m}$.
* **Work Done:** $W = \int_{0}^{x_0} -kx \, dx = [-\frac{1}{2}kx^2]_0^{x_0} = -\frac{1}{2}kx_0^2$.
* **Potential Energy:** Work done by a conservative force is $-\Delta U$, so $U(x) = \frac{1}{2}kx^2$.
* **Verification:** $-\frac{dU}{dx} = -\frac{d}{dx}(\frac{1}{2}kx^2) = -kx$, which equals $F$.

---

## 9. Vertical Throw with Drag

**Equation:** $m\frac{dv}{dt} = -mg - kv$

**Explanation:**
* **Solution:** Separating variables $\int \frac{dv}{g + \frac{k}{m}v} = -\int dt$ yields:
    $$v(t) = (v_0 + \frac{mg}{k})e^{-\frac{k}{m}t} - \frac{mg}{k}$$
* **Max Height:** Set $v(t) = 0$, solve for $t$, and integrate $v(t)$ to find $x(t_{max})$.
* **Comparison:** With drag, the ball reaches a lower maximum height and takes less time to reach it compared to the vacuum case ($h = \frac{v_0^2}{2g}$).

---

## 10. Force Field and Power

**Given:** $m = 0.5\text{ kg}$, $x = 5t^2 - t, y = 2t^3, z = -3t + 2$.

**Solution:**
1.  **Velocity ($v$):** $(\frac{dx}{dt}, \frac{dy}{dt}, \frac{dz}{dt}) = (10t - 1, 6t^2, -3)$
2.  **Momentum ($p$):** $mv = (5t - 0.5, 3t^2, -1.5)$
3.  **Acceleration ($a$):** $\frac{dv}{dt} = (10, 12t, 0)$
4.  **Force ($F$):** $ma = (5, 6t, 0)$
5.  **Power ($P$):** $F \cdot v = 5(10t-1) + 6t(6t^2) + 0 = 36t^3 + 50t - 5$

---

## 11. Time-Dependent Force

**Given:** $m=3\text{ kg}$, $F = (15t, 3t-12, -6t^2)$.

**Solution:**
1.  **Acceleration:** $a = F/m = (5t, t-4, -2t^2)$
2.  **Velocity:** $v(t) = \int a \, dt + v_0 = (\frac{5}{2}t^2+2, \frac{1}{2}t^2-4t, -\frac{2}{3}t^3+1)$
3.  **Position:** $r(t) = \int v \, dt + r_0 = (\frac{5}{6}t^3+2t+5, \frac{1}{6}t^3-2t^2+2, -\frac{1}{6}t^4+t-3)$

---

## 12. Work and Energy (Constant Force)

**Given:** $m=2\text{ kg}$, $F=[6,2]$, $v_0=(1,-1)$, $r_0=(0,0)$.

**Solution:**
* **Kinematics ($t=3$):**
    $a = (3, 1)$
    $v(3) = v_0 + at = (1+9, -1+3) = (10, 2)$
    $r(3) = r_0 + v_0t + \frac{1}{2}at^2 = (3+13.5, -3+4.5) = (16.5, 1.5)$
* **Work:** $W = F \cdot \Delta r = 6(16.5) + 2(1.5) = 99 + 3 = 102\text{ J}$.
* **Theorem Check:**
    $\Delta K = \frac{1}{2}m(v_f^2 - v_i^2) = \frac{1}{2}(2)[(10^2+2^2) - (1^2+(-1)^2)]$
    $\Delta K = 104 - 2 = 102\text{ J}$. (Consistent)
