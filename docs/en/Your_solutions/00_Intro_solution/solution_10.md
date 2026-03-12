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
