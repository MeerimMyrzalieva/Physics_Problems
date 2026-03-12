# Task 06 – Function Analysis

## Problem Statement

Consider the function:

$$
f(x) = 3x^2 - 12x + 7
$$

Identify any local maxima or minima.

## Theory

- Local extrema occur where the derivative is zero.  
- First derivative: $f'(x) = 0$  
- Second derivative test:  
  - $f''(x) > 0$ → local minimum  
  - $f''(x) < 0$ → local maximum

## Step-by-Step Solution

**Step 1: Compute the first derivative**

$$
f'(x) = \frac{d}{dx}(3x^2 - 12x + 7) = 6x - 12
$$

**Step 2: Solve $f'(x) = 0$**

$$
6x - 12 = 0
$$

$$
x = 2
$$

**Step 3: Compute the second derivative**

$$
f''(x) = \frac{d^2 f}{dx^2} = 6
$$

**Step 4: Apply the second derivative test**

$$
f''(2) = 6 > 0 \implies x = 2 \text{ is a local minimum}
$$

**Step 5: Compute function value at minimum**

$$
f(2) = 3(2)^2 - 12(2) + 7 = 12 - 24 + 7 = -5
$$

## Final Result

- Local minimum at $(x, f(x)) = (2, -5)$  
- No local maximum exists (parabola opens upwards)

## Interpretation

- The parabola opens upwards because $a = 3 > 0$  
- The vertex represents the lowest point on the graph.