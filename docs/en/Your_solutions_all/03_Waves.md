# Section 3: Waves - Detailed Solutions

## 1. Wave Properties

**Problem:** A sound wave in air has a frequency of 440 Hz. If the speed of sound in air is 343 m/s, what is its wavelength? What is its wavelength in water, where the speed of sound is 1482 m/s?

**Solution:**
The relationship between wave speed ($v$), frequency ($f$), and wavelength ($\lambda$) is given by the formula:
$$v=\lambda f$$
Rearranging for wavelength gives:
$$\lambda=\frac{v}{f}$$

**In air:**
* $v=343$ m/s
* $f=440$ Hz
$$\lambda_{\text{air}}=\frac{343}{440}\approx0.78\text{ m}$$

**In water:**
* $v=1482$ m/s
* $f=440$ Hz
$$\lambda_{\text{water}}=\frac{1482}{440}\approx3.37\text{ m}$$

---

## 2. String Harmonics

**Problem:** A guitar string is 64 cm long and has a fundamental frequency (one antinode) of 330 Hz. What is the speed of the wave on this string?

**Solution:**
For a fundamental frequency (the first harmonic), the string forms a standing wave with nodes at both ends and one antinode in the middle. The length of the string ($L$) equals exactly half a wavelength:
$$L=\frac{\lambda}{2} \implies \lambda=2L$$

Given $L=64$ cm (which is 0.64 m):
$$\lambda=2(0.64)=1.28\text{ m}$$

Now, using the wave speed formula:
$$v=\lambda f$$
$$v=1.28\times330=422.4\text{ m/s}$$

---

## 3. Superposition Principle

**Problem:** Two waves are described by the equations $y_1(x,t)=A\sin(kx-\omega t)$ and $y_2(x,t)=A\sin(kx+\omega t)$. What is the equation of the resulting standing wave? Identify the positions of the nodes.

**Solution:**
According to the principle of superposition, the resulting wave $y(x,t)$ is the sum of the two individual waves:
$$y(x,t)=y_1(x,t)+y_2(x,t)$$
$$y(x,t)=A\sin(kx-\omega t)+A\sin(kx+\omega t)$$

Using the sum-to-product trigonometric identity: 
$$\sin(\alpha)+\sin(\beta)=2\sin\left(\frac{\alpha+\beta}{2}\right)\cos\left(\frac{\alpha-\beta}{2}\right)$$

Let $\alpha=kx-\omega t$ and $\beta=kx+\omega t$:
$$y(x,t)=2A\sin\left(\frac{2kx}{2}\right)\cos\left(\frac{-2\omega t}{2}\right)$$
$$y(x,t)=2A\sin(kx)\cos(\omega t)$$
*(Note: $\cos(-\theta)=\cos(\theta)$)*

**Positions of the nodes:**
Nodes occur where the amplitude of the standing wave is permanently zero.
$$\sin(kx)=0$$
$$kx=n\pi\quad\text{for } n=0, 1, 2, 3, \dots$$

Since $k=\frac{2\pi}{\lambda}$:
$$\frac{2\pi}{\lambda}x=n\pi \implies x=\frac{n\lambda}{2}$$
The nodes are located at integer multiples of half a wavelength.

---

## 4. Phase Difference

**Problem:** What is the phase difference in radians between two points on a wave that are separated by a distance of $\lambda/3$?

**Solution:**
The phase difference ($\Delta\phi$) relates to the path difference ($\Delta x$) by the proportion:
$$\frac{\Delta\phi}{2\pi}=\frac{\Delta x}{\lambda}$$
$$\Delta\phi=\frac{2\pi}{\lambda}\Delta x$$

Given $\Delta x=\frac{\lambda}{3}$:
$$\Delta\phi=\frac{2\pi}{\lambda}\left(\frac{\lambda}{3}\right)=\frac{2\pi}{3}\text{ radians}$$

---

## 5. Echo Ranging

**Problem:** A person shouts towards a cliff and hears the echo 1 seconds later. How far away is the cliff? (Speed of sound in air is 343 m/s).

**Solution:**
The sound wave must travel to the cliff and back to the person. Let $d$ be the distance to the cliff. The total distance traveled is $2d$.
$$2d=v\times t$$
$$2d=343\times1$$
$$d=\frac{343}{2}=171.5\text{ m}$$

---

## 6. Wave Equation

**Problem:** A wave is described by the equation $y(x,t)=0.05\sin(2\pi x-50\pi t)$, where x and y are in meters and t is in seconds. Determine the wave's Amplitude, Wavelength, Frequency, and Wave speed.

**Solution:**
The standard form of a 1D traveling wave equation is:
$$y(x,t)=A\sin(kx-\omega t)$$
By comparing the given equation to the standard form:

**a) Amplitude $A$:**
$$A=0.05\text{ m}$$

**b) Wavelength $\lambda$:**
The wave number $k=2\pi$.
$$k=\frac{2\pi}{\lambda} \implies 2\pi=\frac{2\pi}{\lambda} \implies \lambda=1\text{ m}$$

**c) Frequency $f$:**
The angular frequency $\omega=50\pi$.
$$\omega=2\pi f \implies 50\pi=2\pi f \implies f=25\text{ Hz}$$

**d) Wave speed $v$:**
$$v=\lambda f=1\times25=25\text{ m/s}$$
*(Alternatively: $v=\frac{\omega}{k}=\frac{50\pi}{2\pi}=25\text{ m/s}$)*

---

## 7. Standing Wave Modes

**Problem:** A standing wave with four antinodes is produced on a string of length $L=80$ cm. What is the wavelength of this wave?

**Solution:**
A standing wave fixed at both ends forms a harmonic series where the length $L$ accommodates an integer number $n$ of half-wavelengths. The number of antinodes corresponds to $n$.
$$L=n\left(\frac{\lambda}{2}\right)$$

Given $L=80$ cm and $n=4$ (four antinodes):
$$80=4\left(\frac{\lambda}{2}\right)$$
$$80=2\lambda$$
$$\lambda=40\text{ cm}\quad(\text{or } 0.4\text{ m})$$

---

## 8. Waves

**Problem:** Which of the following functions can describe a traveling wave?

**Solution:**
A function describes a traveling wave if it satisfies the linear 1D wave equation:
$$\frac{\partial^2 y}{\partial x^2}=\frac{1}{v^2}\frac{\partial^2 y}{\partial t^2}$$
Equivalently, thanks to d'Alembert's formula, any twice-differentiable function of the form $f(x-vt)$ or $f(x+vt)$ will satisfy this equation. Let's analyze the options:

**a) $y(x,t)=A\cos(kx^2-\omega t)$**
Taking the second derivatives yields extra terms due to the $x^2$ inside the argument (chain rule generates factors of $x$). $\frac{\partial^2 y}{\partial x^2}$ will not be directly proportional to $\frac{\partial^2 y}{\partial t^2}$. Thus, it **cannot** describe a standard traveling wave.

**b) $y(x,t)=A(x-vt)^2$**
Let $u=x-vt$. This function is of the form $f(u)=Au^2$. It depends strictly on $(x-vt)$. Let's check the derivatives:
$\frac{\partial^2 y}{\partial x^2}=2A$
$\frac{\partial^2 y}{\partial t^2}=2Av^2$
Substituting into the wave equation gives $2A=\frac{1}{v^2}(2Av^2) \implies 2A=2A$. This **is** a valid traveling wave (specifically, a parabolic pulse).

**c) $y(x,t)=A\log(x+vt)$**
Let $u=x+vt$. This function is of the form $f(u)=A\log(u)$. Because its argument is strictly a linear combination of $x$ and $t$ representing a phase velocity, it perfectly satisfies the wave equation. This **is** a valid traveling wave.

*Answer: Functions (b) and (c) describe traveling waves.*

---

## 9. Damped Oscillator

### 1. General Solution
For the damped harmonic oscillator described by:
$$m\frac{d^2 x}{dt^2}+b\frac{dx}{dt}+kx=0$$

Let $\gamma=\frac{b}{2m}$ (damping coefficient) and $\omega_0=\sqrt{\frac{k}{m}}$ (natural frequency). The general solution assumes the form $x(t)=Ce^{rt}$, leading to the characteristic equation:
$$r^2+2\gamma r+\omega_0^2=0$$
The roots are $r=-\gamma\pm\sqrt{\gamma^2-\omega_0^2}$.

### 2. Classification of Cases
Depending on the discriminant ($\gamma^2-\omega_0^2$), the system behaves in three distinct ways:

* **Underdamped ($b^2<4mk$ or $\gamma<\omega_0$):**
    The roots are complex. The system oscillates with exponentially decaying amplitude.
    $$x(t)=e^{-\gamma t}(C_1\cos(\omega_d t)+C_2\sin(\omega_d t))\quad\text{where }\omega_d=\sqrt{\omega_0^2-\gamma^2}$$
* **Critically Damped ($b^2=4mk$ or $\gamma=\omega_0$):**
    The roots are real and repeated. The system returns to equilibrium as fast as possible without oscillating.
    $$x(t)=(C_1+C_2 t)e^{-\gamma t}$$
* **Overdamped ($b^2>4mk$ or $\gamma>\omega_0$):**
    The roots are real and distinct. The system exponentially decays to equilibrium without oscillating, but slower than the critically damped case.
    $$x(t)=C_1 e^{r_1 t}+C_2 e^{r_2 t}$

---

## 10. Animation: Wave Sources

**Problem:** Create an HTML animation to place point sources of waves described by $u(\vec{r},t)=\frac{A}{|\vec{r}-\vec{r_0}|^\alpha} \sin(k |\vec{r} - \vec{r_0}| - \omega t)$ with an adjustable decay parameter $\alpha$.

---

## 11. Animation: Two-Slit Interference

**Problem:** Simulate Young's Double Slit experiment visualizing the real-time superposition equation given. Allow adjustment of distance $d$ and wavelength $\lambda$.
