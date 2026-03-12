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
