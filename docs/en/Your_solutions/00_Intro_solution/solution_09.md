# Task 09 – Optimization Problem (Maximum Area Rectangle)

## Problem Statement

A rectangle is under the curve $y = 3 - x^2$ in the first quadrant.  
Find dimensions of the rectangle with maximum area.

## Theory

- **Area of rectangle**: $A = \text{width} \cdot \text{height} = x \cdot y$  
- **First quadrant restriction**: $x \ge 0, y \ge 0$  
- Use derivative to maximize area

## Step-by-Step Solution

**Step 1: Express area as a function of $x$**

$$
A(x) = x \cdot y = x (3 - x^2) = 3x - x^3
$$

**Step 2: Compute derivative**

$$
\frac{dA}{dx} = 3 - 3x^2
$$

**Step 3: Solve $dA/dx = 0$**

$$
3 - 3x^2 = 0 \implies x^2 = 1 \implies x = 1
$$

**Step 4: Compute corresponding $y$**

$$
y = 3 - x^2 = 3 - 1 = 2
$$

## Final Result

- Maximum area rectangle: width $x = 1$, height $y = 2$  
- Area: $A_{\max} = 1 \cdot 2 = 2$

## Interpretation

- The rectangle’s area is maximized where the curve slope equals rectangle slope condition ($dA/dx = 0$).  
- This is a standard calculus optimization problem.