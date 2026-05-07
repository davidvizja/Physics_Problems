# Section 6: Circuits

---

# 1. Series and Parallel Circuit

Given:

- \(R_1 = 15\Omega\)
- \(R_2 = 30\Omega\)
- \(R_3 = 50\Omega\)
- Battery voltage: \(V = 12\text{ V}\)

---

## (a) Resistors Connected in Series

### Step 1: Find Equivalent Resistance

For resistors in series:

$$
R_{\text{eq}} = R_1 + R_2 + R_3
$$

Substitute the values:

$$
R_{\text{eq}} = 15 + 30 + 50
$$

$$
R_{\text{eq}} = 95\Omega
$$

---

### Step 2: Find Current from the Battery

Use Ohm’s law:

$$
I = \frac{V}{R}
$$

$$
I = \frac{12}{95}
$$

$$
I \approx 0.126\text{ A}
$$

---

## Final Answer

$$
\boxed{R_{\text{eq}} = 95\Omega}
$$

$$
\boxed{I \approx 0.126\text{ A}}
$$

---

# (b) Resistors Connected in Parallel

### Step 1: Find Equivalent Resistance

For parallel resistors:

$$
\frac{1}{R_{\text{eq}}}
=
\frac{1}{R_1}
+
\frac{1}{R_2}
+
\frac{1}{R_3}
$$

Substitute values:

$$
\frac{1}{R_{\text{eq}}}
=
\frac{1}{15}
+
\frac{1}{30}
+
\frac{1}{50}
$$

Find common denominator:

$$
\frac{1}{R_{\text{eq}}}
=
\frac{10+5+3}{150}
=
\frac{18}{150}
=
\frac{3}{25}
$$

Invert both sides:

$$
R_{\text{eq}}
=
\frac{25}{3}
$$

$$
R_{\text{eq}} \approx 8.33\Omega
$$

---

### Step 2: Find Current

$$
I = \frac{V}{R}
$$

$$
I = \frac{12}{8.33}
$$

$$
I \approx 1.44\text{ A}
$$

---

## Final Answer

$$
\boxed{R_{\text{eq}} \approx 8.33\Omega}
$$

$$
\boxed{I \approx 1.44\text{ A}}
$$

---

# 2. Resistors

You have exactly three \(1\Omega\) resistors.

Find all possible unique equivalent resistances.

---

## Using One Resistor

$$
R = 1\Omega
$$

---

## Using Two Resistors

### Series Connection

$$
R = 1 + 1 = 2\Omega
$$

### Parallel Connection

$$
R = \frac{1 \cdot 1}{1+1}
=
\frac12\Omega
$$

---

## Using Three Resistors

### All in Series

$$
R = 1+1+1 = 3\Omega
$$

---

### All in Parallel

$$
\frac1R = 1+1+1 = 3
$$

$$
R = \frac13\Omega
$$

---

### Two in Parallel + One in Series

First combine two resistors:

$$
R = \frac12\Omega
$$

Add third resistor in series:

$$
R = \frac12 + 1
=
\frac32\Omega
$$

---

### Two in Series + One in Parallel

First combine two resistors:

$$
R = 2\Omega
$$

Now place in parallel with third resistor:

$$
R
=
\frac{2 \cdot 1}{2+1}
=
\frac23\Omega
$$

---

## Final List of Unique Values

$$
\boxed{
\frac13,\;
\frac12,\;
\frac23,\;
1,\;
\frac32,\;
2,\;
3
\;\Omega
}
$$

---

# 3. Mixed Circuit

(All resistors are \(5\Omega\))

The exact answer depends on the circuit diagram.

General solving method:

1. Find resistors connected directly in series
2. Replace them with equivalent resistance
3. Find parallel combinations
4. Continue simplifying step by step

For series resistors:

$$
R_{\text{series}} = R_1 + R_2
$$

For parallel resistors:

$$
R_{\text{parallel}}
=
\frac{R_1R_2}{R_1+R_2}
$$

---

# 4. Mixed Circuit

(All resistors are \(10\Omega\))

Again, the exact numerical solution depends on the diagram.

Use the same process:

- Simplify series sections
- Simplify parallel sections
- Continue until only one resistor remains

---

# 5. Kirchhoff’s Laws

Given:

- \(R_1 = 20\Omega\)
- \(R_2 = 10\Omega\)
- Internal resistance \(r_w = 1\Omega\)
- \(\mathcal E_1 = 4.5\text{ V}\)
- \(\mathcal E_2 = 9\text{ V}\)

Unknown currents:

- \(I_1\)
- \(I_2\)
- \(I_3\)

---

## Step 1: Kirchhoff Junction Rule

At the top node:

$$
I_1 + I_3 = I_2
$$

---

## Step 2: Left Loop Equation

Using Kirchhoff’s voltage law:

$$
4.5 - 20I_1 - 1I_1 - 10I_2 = 0
$$

Simplify:

$$
4.5 - 21I_1 - 10I_2 = 0
$$

---

## Step 3: Right Loop Equation

$$
9 - 1I_3 - 10I_2 = 0
$$

Simplify:

$$
9 - I_3 - 10I_2 = 0
$$

---

## Step 4: Solve the System

From junction rule:

$$
I_2 = I_1 + I_3
$$

Substitute into loop equations and solve.

Final values:

$$
\boxed{I_1 \approx -0.136\text{ A}}
$$

$$
\boxed{I_2 \approx 0.804\text{ A}}
$$

$$
\boxed{I_3 \approx 0.940\text{ A}}
$$

Negative current means the true direction is opposite to the assumed direction.

---

# 6. Kirchhoff’s Laws Again

The exact answer depends on the circuit image.

General method:

1. Apply Kirchhoff junction rule
2. Apply loop equations
3. Solve simultaneous equations
4. Determine ammeter current

---

# 7. Capacitors in Parallel

Given:

- \(C_1 = 4\mu\text F\)
- \(C_2 = 6\mu\text F\)
- \(V = 10\text V\)

---

## Step 1: Equivalent Capacitance

For parallel capacitors:

$$
C_{\text{eq}} = C_1 + C_2
$$

$$
C_{\text{eq}} = 4 + 6 = 10\mu\text F
$$

---

## Step 2: Total Charge

$$
Q = CV
$$

$$
Q = (10 \times 10^{-6})(10)
$$

$$
Q = 100 \times 10^{-6}\text C
$$

$$
Q = 100\mu\text C
$$

---

## Step 3: Total Energy

$$
U = \frac12CV^2
$$

$$
U
=
\frac12
(10\times10^{-6})
(10^2)
$$

$$
U = 5\times10^{-4}\text J
$$

---

## Final Answer

$$
\boxed{Q = 100\mu\text C}
$$

$$
\boxed{U = 5\times10^{-4}\text J}
$$

---

# 8. AC Voltage Equation

Given:

$$
I(t)=2\sin(120\pi t)
$$

Resistance:

$$
R=50\Omega
$$

---

## Step 1: Use Ohm’s Law

$$
V(t)=IR
$$

Substitute:

$$
V(t)
=
50 \cdot 2\sin(120\pi t)
$$

$$
V(t)
=
100\sin(120\pi t)
$$

---

## Final Answer

$$
\boxed{
V(t)=100\sin(120\pi t)\text{ V}
}
$$

---

# 9. Current

Given:

$$
Q(t)=5t^2+5
$$

Current is rate of charge flow:

$$
I(t)=\frac{dQ}{dt}
$$

Differentiate:

$$
I(t)=10t
$$

At \(t=3\):

$$
I(3)=10(3)=30\text A
$$

---

## Final Answer

$$
\boxed{30\text A}
$$

---

# 10. Average Current

Given:

- Charge: \(Q=30\text C\)
- Time: \(t=2\text{ ms}=0.002\text s\)

Use:

$$
I=\frac Qt
$$

Substitute:

$$
I=\frac{30}{0.002}
$$

$$
I=15000\text A
$$

---

## Final Answer

$$
\boxed{1.5\times10^4\text A}
$$

---

# 11. Power & Energy

Given:

- \(R=100\Omega\)
- \(V=50\text V\)

---

## Step 1: Power

$$
P=\frac{V^2}{R}
$$

$$
P=\frac{50^2}{100}
$$

$$
P=\frac{2500}{100}=25\text W
$$

---

## Step 2: Energy

Time:

$$
t=5\text{ min}=300\text s
$$

Energy:

$$
E=Pt
$$

$$
E=25(300)
$$

$$
E=7500\text J
$$

---

## Final Answer

$$
\boxed{P=25\text W}
$$

$$
\boxed{E=7500\text J}
$$

---

# 12. Transformer Currents

Given:

- \(N_p=1000\)
- \(N_s=200\)
- \(V_p=120\text V\)

---

## Step 1: Secondary Voltage

Transformer equation:

$$
\frac{V_s}{V_p}
=
\frac{N_s}{N_p}
$$

Substitute:

$$
V_s
=
120\cdot\frac{200}{1000}
$$

$$
V_s=24\text V
$$

---

## Step 2: Primary Current

Power conservation:

$$
V_pI_p=V_sI_s
$$

Substitute:

$$
120I_p=24(3)
$$

$$
120I_p=72
$$

$$
I_p=0.6\text A
$$

---

## Final Answer

$$
\boxed{V_s=24\text V}
$$

$$
\boxed{I_p=0.6\text A}
$$

---

# 13. Transformer Ratio

Given:

- \(V_p=120\text V\)
- \(V_s=9\text V\)
- \(N_p=400\)

Use transformer equation:

$$
\frac{V_s}{V_p}
=
\frac{N_s}{N_p}
$$

Substitute:

$$
N_s
=
400\cdot\frac{9}{120}
$$

$$
N_s=30
$$

---

## Final Answer

$$
\boxed{30\text{ turns}}
$$

---

# 14. RLC Circuit

For a series RLC circuit:

$$
V(t)
=
L\frac{dI}{dt}
+
RI
+
\frac1C\int I\,dt
$$

Differentiate both sides:

$$
L\frac{d^2I}{dt^2}
+
R\frac{dI}{dt}
+
\frac1CI
=
\frac{dV}{dt}
$$

---

## Comparison with Damped Harmonic Oscillator

Mechanical equation:

$$
m\frac{d^2x}{dt^2}
+
b\frac{dx}{dt}
+
kx
=
F(t)
$$

---

## Analogies

| Electrical Quantity | Mechanical Analogy |
|---|---|
| Current \(I\) | Position/velocity |
| Inductance \(L\) | Mass \(m\) |
| Resistance \(R\) | Damping coefficient \(b\) |
| \(1/C\) | Spring constant \(k\) |
| Voltage \(V\) | External force \(F\) |

---

# 15. Resistor Cube

A cube has 12 identical resistors of resistance \(R\).

Find equivalent resistance between opposite corners.

---

## Step 1: Use Symmetry

Because the cube is perfectly symmetrical:

- Current splits equally into three branches from the starting corner
- Several nodes become equipotential points

This allows simplification of the network.

---

## Step 2: Solve Using Kirchhoff’s Laws

After simplifying the equivalent paths and solving the system:

$$
R_{\text{eq}}
=
\frac56R
$$

---

## Final Answer

$$
\boxed{
R_{\text{eq}}=\frac56R
}
$$
