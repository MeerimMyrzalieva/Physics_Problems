# Task 08 – Definite Integrals

## Problem Statement

Calculate the area under the curve:

$$
f(x) = \sin(x)
$$

from $x=0$ to $x=\pi$.

## Theory

- **Definite integral**: area under curve  
$$
A = \int_{a}^{b} f(x) dx
$$

- Integral of sine function:  
$$
\int \sin(x) dx = -\cos(x) + C
$$

## Step-by-Step Solution

**Step 1: Write the integral**

$$
A = \int_0^\pi \sin(x) dx
$$

**Step 2: Compute the antiderivative**

$$
\int \sin(x) dx = -\cos(x)
$$

**Step 3: Evaluate definite integral**

$$
A = [-\cos(x)]_0^\pi = -\cos(\pi) + \cos(0)
$$

$$
A = -(-1) + 1 = 2
$$

## Final Result

$$
A = 2
$$

## Interpretation

- The area under one full sine wave from $0$ to $\pi$ is positive.  
- Definite integrals capture net “signed area” under a curve.