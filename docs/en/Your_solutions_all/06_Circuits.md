# Section 6: Circuits - Solutions

## 1. Series and Parallel Circuit
**Given:** $R_1 = 15\,\Omega$, $R_2 = 30\,\Omega$, $R_3 = 50\,\Omega$, $V = 12\,\text{V}$.

### Case A: Series Connection
*   **Equivalent Resistance ($R_{eq}$):**
    $$R_{eq} = R_1 + R_2 + R_3 = 15 + 30 + 50 = 95\,\Omega$$
*   **Total Current ($I$):**
    $$I = \frac{V}{R_{eq}} = \frac{12}{95} \approx 0.126\,\text{A}$$

### Case B: Parallel Connection
*   **Equivalent Resistance ($R_{eq}$):**
    $$\frac{1}{R_{eq}} = \frac{1}{R_1} + \frac{1}{R_2} + \frac{1}{R_3} = \frac{1}{15} + \frac{1}{30} + \frac{1}{50} = \frac{10+5+3}{150} = \frac{18}{150}$$
    $$R_{eq} = \frac{150}{18} \approx 8.33\,\Omega$$
*   **Total Current ($I$):**
    $$I = \frac{V}{R_{eq}} = \frac{12}{8.33} \approx 1.44\,\text{A}$$

---

## 2. Resistors
Using exactly three $1\,\Omega$ resistors, the unique equivalent resistances are:
1.  **All in Series:** $1 + 1 + 1 = \mathbf{3\,\Omega}$
2.  **All in Parallel:** $1 / (\frac{1}{1} + \frac{1}{1} + \frac{1}{1}) = \mathbf{1/3\,\Omega \approx 0.33\,\Omega}$
3.  **Series-Parallel (Two parallel, one series):** $(\frac{1 \times 1}{1 + 1}) + 1 = 0.5 + 1 = \mathbf{1.5\,\Omega}$
4.  **Parallel-Series (Two series, one parallel):** $\frac{(1 + 1) \times 1}{(1 + 1) + 1} = \frac{2}{3} \approx \mathbf{0.67\,\Omega}$

---

## 3. Mixed Circuit (Figure R1)
For a standard bridge or ladder where two $5\,\Omega$ resistors are in parallel, and that combination is in series with a third $5\,\Omega$ resistor:
*   $R_{parallel} = \frac{5 \times 5}{5 + 5} = 2.5\,\Omega$
*   $R_{eq} = 2.5 + 5 = \mathbf{7.5\,\Omega}$

---

## 4. Mixed Circuit (Figure R2)
In a symmetric bridge circuit where all resistors are $10\,\Omega$:
*   By symmetry, if it is a balanced Wheatstone bridge, the central branch carries no current.
*   The circuit simplifies to two parallel branches, each containing two $10\,\Omega$ resistors in series.
*   $R_{branch} = 10 + 10 = 20\,\Omega$
*   $R_{eq} = \frac{20 \times 20}{20 + 20} = \mathbf{10\,\Omega}$

---

## 5. Kirchhoff's Laws
**Equations based on clockwise loops:**
1.  **Loop 1 (Left):** $\mathcal{E}_1 - I_1(R_1 + r_w) - I_2(R_2) = 0 \Rightarrow 4.5 - 21I_1 - 10I_2 = 0$
2.  **Loop 2 (Right):** $\mathcal{E}_2 - I_3(r_w) - I_2(R_2) = 0 \Rightarrow 9 - 1I_3 - 10I_2 = 0$
3.  **Junction Rule:** $I_3 = I_1 + I_2$

**Solving:**
*   From (2) and (3): $9 - (I_1 + I_2) - 10I_2 = 0 \Rightarrow 9 - I_1 - 11I_2 = 0 \Rightarrow I_1 = 9 - 11I_2$
*   Substitute into (1): $4.5 - 21(9 - 11I_2) - 10I_2 = 0$
*   $4.5 - 189 + 231I_2 - 10I_2 = 0 \Rightarrow 221I_2 = 184.5$
*   **$I_2 \approx 0.835\,\text{A}$**
*   **$I_1 = 9 - 11(0.835) \approx -0.185\,\text{A}$**
*   **$I_3 = I_1 + I_2 \approx 0.650\,\text{A}$**

---

## 6. Kirchhoff's Laws again
*Note: Calculation depends on specific bridge topology in image-k2. If it is a balanced bridge, the ammeter reads $0\,\text{A}$. If unbalanced, apply Mesh analysis.*

---

## 7. Capacitors in Parallel
*   **Total Capacitance ($C_{tot}$):** $C_1 + C_2 = 4\,\mu\text{F} + 6\,\mu\text{F} = 10\,\mu\text{F}$
*   **Total Charge ($Q$):** $Q = C_{tot} \times V = 10\,\mu\text{F} \times 10\,\text{V} = \mathbf{100\,\mu\text{C}}$
*   **Total Energy ($U$):** $U = \frac{1}{2} C_{tot} V^2 = \frac{1}{2} (10 \times 10^{-6}) (10)^2 = \mathbf{5 \times 10^{-4}\,\text{J}}$

---

## 8. AC Voltage Equation
By Ohm's Law: $V(t) = I(t) \times R$
*   $V(t) = (2 \sin(120\pi t)) \times 50$
*   **$V(t) = 100 \sin(120\pi t)\,\text{V}$**

---

## 9. Current
$I(t) = \frac{dQ}{dt}$. Given $Q(t) = 5t^2 + 5$:
*   $I(t) = 10t$
*   At $t=3\,\text{s}$: $I(3) = 10(3) = \mathbf{30\,\text{A}}$

---

## 10. Average Current
$I_{avg} = \frac{\Delta Q}{\Delta t}$
*   $I_{avg} = \frac{30\,\text{C}}{0.002\,\text{s}} = \mathbf{15,000\,\text{A}}$

---

## 11. Power & Energy
*   **Power ($P$):** $P = \frac{V^2}{R} = \frac{50^2}{100} = \frac{2500}{100} = \mathbf{25\,\text{W}}$
*   **Energy ($E$):** $E = P \times t = 25\,\text{W} \times (5 \times 60\,\text{s}) = 25 \times 300 = \mathbf{7,500\,\text{J}}$

---

## 12. Transformer Currents
*   **Secondary Voltage ($V_s$):** $V_s = V_p \times (\frac{N_s}{N_p}) = 120 \times (\frac{200}{1000}) = \mathbf{24\,\text{V}}$
*   **Primary Current ($I_p$):** $I_p = I_s \times (\frac{N_s}{N_p}) = 3 \times (\frac{200}{1000}) = \mathbf{0.6\,\text{A}}$

---

## 13. Transformer Ratio
$\frac{N_s}{N_p} = \frac{V_s}{V_p} \Rightarrow N_s = 400 \times (\frac{9}{120})$
*   **$N_s = 30\,\text{turns}$**

---

## 14. RLC Circuit
**Differential Equation:**
$$L \frac{d^2Q}{dt^2} + R \frac{dQ}{dt} + \frac{1}{C}Q = V(t)$$
**Analogies with Damped Harmonic Oscillator ($m\ddot{x} + b\dot{x} + kx = F$):**
*   **Inductance ($L$)** $\approx$ Mass ($m$)
*   **Resistance ($R$)** $\approx$ Damping Coefficient ($b$)
*   **Reciprocal Capacitance ($1/C$)** $\approx$ Spring Constant ($k$)
*   **Charge ($Q$)** $\approx$ Displacement ($x$)

---

## 15. Resistor Cube* (Detailed Symmetry Solution)

**Problem:** A cube is constructed from 12 identical resistors, each with resistance $R$. Calculate the equivalent resistance $R_{eq}$ between two opposite corners (e.g., from the bottom-front-left corner to the top-back-right corner).

### Step-by-Step Analysis using Symmetry:

To solve this, we imagine a total current $I$ entering the cube at one corner (Node A) and leaving from the opposite corner (Node B).

**1. The Entrance (3-way split):**
At the entry node, the current $I$ encounters **3 identical edges**. Since the cube is perfectly symmetrical relative to the exit point, the current must divide equally.
*   Current in each of the first 3 edges = $\frac{1}{3}I$
*   Voltage drop across these edges = $V_1 = (\frac{1}{3}I)R$

**2. The Middle (6-way split):**
Each of those 3 currents reaches a new node. From each of these nodes, there are **2 new paths** available (leading toward the exit). This creates a total of 6 paths in the middle "belt" of the cube.
*   Current in each of these 6 edges = $\frac{1}{2} \times (\frac{1}{3}I) = \frac{1}{6}I$
*   Voltage drop across these edges = $V_2 = (\frac{1}{6}I)R$

**3. The Exit (3-way merge):**
Finally, these 6 paths merge into **3 final edges** that meet at the exit node.
*   Current in each of the last 3 edges = $\frac{1}{3}I$
*   Voltage drop across these edges = $V_3 = (\frac{1}{3}I)R$

### Calculating Total Resistance:
The total voltage drop $V_{total}$ across the cube is the sum of the voltage drops along any single path from start to finish:
$$V_{total} = V_1 + V_2 + V_3$$
$$V_{total} = \frac{1}{3}IR + \frac{1}{6}IR + \frac{1}{3}IR$$

To add these, find a common denominator (6):
$$V_{total} = (\frac{2}{6} + \frac{1}{6} + \frac{2}{6})IR = \frac{5}{6}IR$$

According to Ohm's Law, $R_{eq} = \frac{V_{total}}{I}$. Therefore:
$$\mathbf{R_{eq} = \frac{5}{6}R}$$

**Conclusion:**
For a cube of $1\,\Omega$ resistors, the equivalent resistance is $0.833\,\Omega$. This result highlights how equipotential nodes (nodes at the same "distance" from the start) can be treated as being connected, simplifying a 3D network into a simple series of parallel groups.
