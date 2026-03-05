# Problem Set 01 – Solutions

---

# Task 01 – Vector Algebra

## Problem Statement

Given two vectors in three-dimensional space

$$
\vec{a} = (2,1,-3), \qquad \vec{b} = (4,-2,1)
$$

Determine

1. The magnitude of each vector  
2. The dot product $ \vec{a} \cdot \vec{b} $  
3. The cross product $ \vec{a} \times \vec{b} $  
4. The angle between the vectors

---

## Theory

### Vector Magnitude

The magnitude (length) of a vector in three dimensions is defined as

$$
|\vec{v}| = \sqrt{v_x^2 + v_y^2 + v_z^2}
$$

### Dot Product

The dot product of two vectors is

$$
\vec{a} \cdot \vec{b} = a_x b_x + a_y b_y + a_z b_z
$$

It is also related to the angle between the vectors

$$
\vec{a} \cdot \vec{b} = |\vec{a}| |\vec{b}| \cos \theta
$$

### Cross Product

The cross product of two vectors in three dimensions can be written as a determinant

$$
\vec{a} \times \vec{b} =
\begin{pmatrix}
a_y b_z - a_z b_y \\
a_z b_x - a_x b_z \\
a_x b_y - a_y b_x
\end{pmatrix}
$$

### Angle Between Vectors

The angle between vectors follows from the dot product relation

$$
\cos \theta =
\frac{\vec{a} \cdot \vec{b}}{|\vec{a}| |\vec{b}|}
$$

---

## Step-by-Step Solution

### Magnitudes

For vector $ \vec{a} $

$$
|\vec{a}| = \sqrt{2^2 + 1^2 + (-3)^2}
$$

$$
|\vec{a}| = \sqrt{4 + 1 + 9}
$$

$$
|\vec{a}| = \sqrt{14}
$$

For vector $ \vec{b} $

$$
|\vec{b}| = \sqrt{4^2 + (-2)^2 + 1^2}
$$

$$
|\vec{b}| = \sqrt{16 + 4 + 1}
$$

$$
|\vec{b}| = \sqrt{21}
$$

---

### Dot Product

$$
\vec{a} \cdot \vec{b} =
(2)(4) + (1)(-2) + (-3)(1)
$$

$$
\vec{a} \cdot \vec{b} = 8 - 2 - 3
$$

$$
\vec{a} \cdot \vec{b} = 3
$$

---

### Cross Product

Using the determinant expression

$$
\vec{a} \times \vec{b} =
\begin{pmatrix}
1\cdot1 - (-3)(-2) \\
(-3)(4) - (2)(1) \\
(2)(-2) - (1)(4)
\end{pmatrix}
$$

$$
\vec{a} \times \vec{b} =
\begin{pmatrix}
-5 \\
-14 \\
-8
\end{pmatrix}
$$

---

### Angle Between Vectors

First compute the cosine of the angle

$$
\cos \theta =
\frac{3}{\sqrt{14}\sqrt{21}}
$$

$$
\cos \theta =
\frac{3}{\sqrt{294}}
$$

---

## Final Result

Magnitudes

$$
|\vec{a}| = \sqrt{14}, \qquad |\vec{b}| = \sqrt{21}
$$

Dot product

$$
\vec{a} \cdot \vec{b} = 3
$$

Cross product

$$
\vec{a} \times \vec{b} =
\begin{pmatrix}
-5 \\
-14 \\
-8
\end{pmatrix}
$$

Angle

$$
\theta = \cos^{-1}\left(\frac{3}{\sqrt{294}}\right)
$$

---

## Interpretation

The positive dot product indicates that the angle between the vectors is less than $90^\circ$. The cross product produces a vector perpendicular to both original vectors.

---

# Task 02 – System of Equations

## Problem Statement

Solve the system

$$
2x + 3y = 12
$$

$$
x - y = 1
$$

---

## Theory

A system of linear equations can be solved using substitution or elimination. Substitution expresses one variable in terms of the other and replaces it in the remaining equation.

---

## Step-by-Step Solution

From the second equation

$$
x - y = 1
$$

Solve for $x$

$$
x = y + 1
$$

Substitute into the first equation

$$
2(y + 1) + 3y = 12
$$

$$
2y + 2 + 3y = 12
$$

$$
5y + 2 = 12
$$

$$
5y = 10
$$

$$
y = 2
$$

Substitute into $x = y + 1$

$$
x = 3
$$

---

## Final Result

$$
x = 3, \qquad y = 2
$$

---

## Interpretation

The ordered pair $(3,2)$ satisfies both linear equations simultaneously.

---

# Task 03 – Gravitational Proportionality

## Problem Statement

The gravitational force between two masses is

$$
F = G \frac{m_1 m_2}{r^2}
$$

Determine how the force changes if

- both masses are halved  
- the distance between them is doubled

---

## Theory

Gravitational force is proportional to

$$
F \propto \frac{m_1 m_2}{r^2}
$$

Thus

- halving a mass multiplies the force by $1/2$
- doubling the distance multiplies the force by $1/4$

---

## Step-by-Step Solution

New masses

$$
m_1' = \frac{m_1}{2}, \qquad m_2' = \frac{m_2}{2}
$$

New distance

$$
r' = 2r
$$

Substitute into the formula

$$
F' =
G
\frac{(m_1/2)(m_2/2)}{(2r)^2}
$$

Simplify

$$
F' =
G
\frac{m_1 m_2}{4 \cdot 4 r^2}
$$

$$
F' = \frac{1}{16} F
$$

---

## Final Result

$$
F' = \frac{F}{16}
$$

---

## Interpretation

The gravitational force becomes sixteen times smaller because the reduced masses and increased distance both weaken the interaction.

---

# Task 04 – Pendulum Formula Rearrangement

## Problem Statement

The period of a simple pendulum is

$$
T = 2\pi \sqrt{\frac{L}{g}}
$$

Solve the equation for $g$.

---

## Theory

Rearranging formulas requires isolating the desired variable through algebraic operations.

---

## Step-by-Step Solution

Divide both sides by $2\pi$

$$
\frac{T}{2\pi} =
\sqrt{\frac{L}{g}}
$$

Square both sides

$$
\frac{T^2}{4\pi^2} =
\frac{L}{g}
$$

Solve for $g$

$$
g =
\frac{4\pi^2 L}{T^2}
$$

---

## Final Result

$$
g =
\frac{4\pi^2 L}{T^2}
$$

---

## Interpretation

The gravitational acceleration can be experimentally determined by measuring the pendulum length and oscillation period.

---

# Task 05 – Vector Components

## Problem Statement

A vector has magnitude $15$ and forms an angle of $60^\circ$ with the horizontal axis. Determine its horizontal and vertical components.

---

## Theory

For a vector with magnitude $A$ and angle $\theta$

$$
A_x = A \cos\theta
$$

$$
A_y = A \sin\theta
$$

---

## Step-by-Step Solution

Horizontal component

$$
A_x = 15 \cos 60^\circ
$$

Since

$$
\cos 60^\circ = \frac{1}{2}
$$

$$
A_x = 7.5
$$

Vertical component

$$
A_y = 15 \sin 60^\circ
$$

$$
A_y =
15 \left(\frac{\sqrt{3}}{2}\right)
$$

---

## Final Result

$$
A_x = 7.5
$$

$$
A_y =
\frac{15\sqrt{3}}{2}
$$

---

## Interpretation

The vector decomposes into orthogonal horizontal and vertical components used in mechanics problems.

---

# Task 06 – Function Analysis

## Problem Statement

Consider the function

$$
f(x) = 3x^2 - 12x + 7
$$

Determine whether the function has a local maximum or minimum.

---

## Theory

Extrema occur where the first derivative is zero

$$
f'(x) = 0
$$

The second derivative determines the type of extremum.

---

## Step-by-Step Solution

First derivative

$$
f'(x) = 6x - 12
$$

Set equal to zero

$$
6x - 12 = 0
$$

$$
x = 2
$$

Second derivative

$$
f''(x) = 6
$$

Since

$$
f''(x) > 0
$$

the point corresponds to a minimum.

Evaluate the function

$$
f(2) = 3(2)^2 - 12(2) + 7
$$

$$
f(2) = -5
$$

---

## Final Result

Minimum point

$$
(2,-5)
$$

---

## Interpretation

The parabola opens upward, therefore the extremum is a minimum.

---

# Task 07 – Fly and Bicycle Problem

## Problem Statement

A bicycle is 10 m from a wall and moves toward it at 1 m/s. A fly travels between the bicycle and the wall at 2 m/s until the bicycle reaches the wall.

Determine the total distance traveled by the fly.

---

## Theory

The key observation is that the fly travels for the entire time until the bicycle reaches the wall.

Distance traveled follows

$$
d = vt
$$

---

## Step-by-Step Solution

Time for the bicycle to reach the wall

$$
t = \frac{10}{1}
$$

$$
t = 10
$$

Fly speed

$$
v = 2
$$

Distance traveled

$$
d = vt
$$

$$
d = 2 \times 10
$$

---

## Final Result

$$
d = 20 \text{ m}
$$

---

## Interpretation

Although the fly changes direction infinitely many times, the total distance depends only on total travel time.

---

# Task 08 – Definite Integral

## Problem Statement

Evaluate the area under

$$
f(x) = \sin x
$$

from

$$
x = 0
$$

to

$$
x = \pi
$$

---

## Theory

The definite integral represents the signed area under a curve

$$
\int_a^b f(x)dx
$$

---

## Step-by-Step Solution

Antiderivative of $\sin x$

$$
\int \sin x dx = -\cos x
$$

Evaluate the definite integral

$$
\int_0^\pi \sin x dx
$$

$$
= [-\cos x]_0^\pi
$$

$$
= -\cos\pi + \cos0
$$

Since

$$
\cos\pi = -1
$$

$$
\cos0 = 1
$$

The result becomes

$$
2
$$

---

## Final Result

$$
\int_0^\pi \sin x dx = 2
$$

---

## Interpretation

The total area under one half-period of the sine function equals two square units.

---

# Task 09 – Optimization Problem

## Problem Statement

A rectangle is inscribed under the curve

$$
y = 3 - x^2
$$

in the first quadrant. Determine the rectangle with maximum area.

---

## Theory

The area of the rectangle is

$$
A = x y
$$

Since

$$
y = 3 - x^2
$$

the area becomes a function of $x$.

---

## Step-by-Step Solution

Area function

$$
A(x) = x(3 - x^2)
$$

$$
A(x) = 3x - x^3
$$

Derivative

$$
A'(x) = 3 - 3x^2
$$

Set derivative equal to zero

$$
3 - 3x^2 = 0
$$

$$
x^2 = 1
$$

$$
x = 1
$$

Height

$$
y = 3 - 1
$$

$$
y = 2
$$

---

## Final Result

Rectangle dimensions

$$
x = 1
$$

$$
y = 2
$$

---

## Interpretation

The rectangle with maximum area touches the curve at $x=1$.

---

# Task 10 – Infinite Series Motion

## Problem Statement

An ant moves according to the pattern

- $1$ m east  
- $1/2$ m north  
- $1/3$ m west  
- $1/4$ m south  
- $1/5$ m east  

and continues indefinitely.

Determine the final position.

---

## Theory

Alternating series frequently appear in mathematical physics.

The Leibniz series is

$$
1 - \frac{1}{3} + \frac{1}{5} - \frac{1}{7} + \dots =
\frac{\pi}{4}
$$

Another alternating series is

$$
1 - \frac{1}{2} + \frac{1}{3} - \frac{1}{4} + \dots =
\ln 2
$$

---

## Step-by-Step Solution

Horizontal motion

$$
x =
1 - \frac{1}{3} + \frac{1}{5} - \frac{1}{7} + \dots
$$

This converges to

$$
\frac{\pi}{4}
$$

Vertical motion

$$
y =
\frac{1}{2} - \frac{1}{4} + \frac{1}{6} - \frac{1}{8} + \dots
$$

Factor out $1/2$

$$
y =
\frac{1}{2}
\left(
1 - \frac{1}{2} + \frac{1}{3} - \frac{1}{4} + \dots
\right)
$$

The series equals $\ln 2$.

---

## Final Result

Final position

$$
\left(
\frac{\pi}{4},
\frac{\ln 2}{2}
\right)
$$

---

## Interpretation

Although the ant makes infinitely many moves, the alternating series converges to a finite displacement.