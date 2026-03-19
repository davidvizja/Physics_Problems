# Section 1: Mechanics I Solutions

---

## 1. Projectile Motion

**Differential Equations of Motion**
Assuming $x$ is horizontal, $y$ is vertical, and $g$ is gravity:
* **Horizontal:** $m \frac{d^2x}{dt^2} = 0 \implies \frac{d^2x}{dt^2} = 0$
* **Vertical:** $m \frac{d^2y}{dt^2} = -mg \implies \frac{d^2y}{dt^2} = -g$

**Time of Flight ($T$)**
Using $v_0 = 100$ m/s and $\theta = 37^\circ$:
$$T = \frac{2v_0 \sin\theta}{g} = \frac{2(100) \sin(37^\circ)}{9.81} \approx 12.27 \text{ s}$$

**Maximum Height ($H$)**
$$H = \frac{v_0^2 \sin^2\theta}{2g} = \frac{100^2 \sin^2(37^\circ)}{2(9.81)} \approx 184.6 \text{ m}$$

**Range ($R$)**
$$R = \frac{v_0^2 \sin(2\theta)}{g} = \frac{100^2 \sin(74^\circ)}{9.81} \approx 979.9 \text{ m}$$

---

## 2. Range Optimization

To find the maximum of $R(\theta) = \frac{v_0^2 \sin(2\theta)}{g}$, we differentiate with respect to $\theta$:
$$\frac{dR}{d\theta} = \frac{v_0^2}{g} \cdot 2\cos(2\theta) = 0$$
$$\cos(2\theta) = 0 \implies 2\theta = 90^\circ \implies \theta = 45^\circ$$
The range is maximized at **45°**.

---

## 3. Path Intersection

**Spatial Intersection:**
Set $A(t_1) = B(t_2)$:
1. $2 + t_1 = 2t_2 - 1 \implies t_1 = 2t_2 - 3$
2. $8 - 3t_1 = 2t_2 + 2$

Substitute (1) into (2):
$8 - 3(2t_2 - 3) = 2t_2 + 2 \implies 17 - 6t_2 = 2t_2 + 2 \implies t_2 = 1.875 \text{ s}$
Then $t_1 = 0.75 \text{ s}$. 
The paths intersect at **(2.75, 5.75)**, but since $t_1 \neq t_2$, **they do not collide.**

**Minimum Distance:**
Minimize $D^2(t) = (x_A-x_B)^2 + (y_A-y_B)^2$:
$D^2(t) = (3-t)^2 + (6-5t)^2 = 26t^2 - 66t + 45$
Derivative: $52t - 66 = 0 \implies t \approx 1.27 \text{ s}$
Minimum distance $d = \sqrt{D^2(1.27)} \approx 1.76 \text{ units}$.

---

## 4. Vector Calculus

Given $\vec{r}(t) = (3t^2)\hat{i} + (5t - 8t^2)\hat{j}$:
* **Velocity:** $\vec{v}(t) = \frac{d\vec{r}}{dt} = (6t)\hat{i} + (5 - 16t)\hat{j}$
* **Acceleration:** $\vec{a}(t) = \frac{d\vec{v}}{dt} = 6\hat{i} - 16\hat{j}$

---

## 5. Relative Velocity

* **Direction:** $\sin\theta = \frac{v_{river}}{v_{boat}} = \frac{2}{5} \implies \theta \approx 23.6^\circ$ **West of North**.
* **Time:** $v_{resultant} = \sqrt{5^2 - 2^2} = \sqrt{21} \approx 4.58 \text{ m/s}$.
    $t = \frac{200}{4.58} \approx 43.6 \text{ s}$.

---

## 6. Variable Velocity

$v(t) = t^2 + 2t - 5$ with $x(0) = 4$.
* **Position at $t=3$:** $x(t) = \int v(t)dt = \frac{1}{3}t^3 + t^2 - 5t + 4$.
    $x(3) = 9 + 9 - 15 + 4 = 7$.
* **Acceleration at $t=3$:** $a(t) = \frac{dv}{dt} = 2t + 2 \implies a(3) = 8$.

---

## 7. Elimination of Time

Given $x=2t^2, y=3t^3$:
* **Equation:** $t = \sqrt{x/2} \implies y = 3(x/2)^{3/2}$.
* **Kinematics:**
    $\vec{v}(t) = (4t, 9t^2)$; $|\vec{v}(t)| = t\sqrt{16 + 81t^2}$
    $\vec{a}(t) = (4, 18t)$; $|\vec{a}(t)| = \sqrt{16 + 324t^2}$
* **Constant Acceleration?** No, the magnitude depends on $t$.

---

## 8. Circular Motion

$R = 6.378 \times 10^6 \text{ m}$, $T = 86400 \text{ s}$.
$\omega = \frac{2\pi}{T} \approx 7.27 \times 10^{-5} \text{ rad/s}$.
$a_c = R\omega^2 \approx 0.0337 \text{ m/s}^2$.

---

## 9. Momentum Comparison

* **Fly:** $p = (0.002)(10) = 0.02 \text{ kg}\cdot\text{m/s}$
* **Ball:** $p = (0.06)(1) = 0.06 \text{ kg}\cdot\text{m/s}$
The **tennis ball** has more momentum.

---

## 10. Kinematics of Point M

**a) Trajectory:**
$\frac{x^2}{a^2} + \frac{y^2}{b^2} = 1$. This is an **elliptical helix** moving along $z = bt$.

**b) Path Length ($L$):**
$L = \int_0^{t_0} \sqrt{a^2\omega^2\sin^2\omega t + b^2\omega^2\cos^2\omega t + b^2} dt$.
