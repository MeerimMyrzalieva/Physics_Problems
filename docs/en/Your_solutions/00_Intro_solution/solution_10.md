# Task 10 – Infinite Series (Ant’s Motion)

## Problem Statement

An ant moves starting at the origin in the following pattern:  

1 m east, 1/2 m north, 1/3 m west, 1/4 m south, 1/5 m east, …  

Determine the final position.

## Theory

- **Separate coordinates**: x-direction (east-west), y-direction (north-south)  
- Use **infinite series**:  

$$
x = 1 - \frac{1}{3} + \frac{1}{5} - \frac{1}{7} + \dots
$$

$$
y = \frac{1}{2} - \frac{1}{4} + \frac{1}{6} - \dots
$$

- Recognize as **alternating harmonic series**:  
$$
\sum_{n=0}^{\infty} \frac{(-1)^n}{2n + 1} = \frac{\pi}{4}, \quad
\sum_{n=1}^{\infty} \frac{(-1)^{n+1}}{2n} = \ln 2
$$

## Step-by-Step Solution

**Step 1: x-coordinate**

$$
x = 1 - \frac{1}{3} + \frac{1}{5} - \frac{1}{7} + \dots = \frac{\pi}{4}
$$

**Step 2: y-coordinate**

$$
y = \frac{1}{2} - \frac{1}{4} + \frac{1}{6} - \frac{1}{8} + \dots = \ln 2
$$

## Final Result

$$
(x, y) = \left(\frac{\pi}{4}, \ln 2\right)
$$

## Interpretation

- The ant converges to a fixed point in the plane.  
- Alternating series produce a finite sum despite infinite steps.  
- This problem demonstrates the connection between series and geometry.