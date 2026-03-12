# Task 03 – Proportionality in Gravitation

## Problem Statement

Universal Law of Gravitation:

$$
F = G \frac{m_1 m_2}{r^2}
$$

Determine the factor by which the gravitational force $F$ changes if:

- $r$ is doubled  
- $m_1$ and $m_2$ are halved  

## Theory

- **Inverse-square law**: $F \propto \frac{1}{r^2}$  
- **Direct proportionality**: $F \propto m_1 m_2$  
- Total scaling factor:

$$
F_{\text{new}} = G \frac{(m_1/2)(m_2/2)}{(2r)^2} = G \frac{m_1 m_2}{16 r^2} = \frac{1}{16} F
$$

## Step-by-Step Solution

**Step 1: Scale the masses**

$$
m_1 \to \frac{m_1}{2}, \quad m_2 \to \frac{m_2}{2}
$$

$$
m_1 m_2 \to \frac{m_1 m_2}{4}
$$

**Step 2: Scale the distance**

$$
r \to 2r \implies r^2 \to 4 r^2
$$

**Step 3: Compute the new force**

$$
F_{\text{new}} = G \frac{m_1 m_2 / 4}{4 r^2} = \frac{1}{16} G \frac{m_1 m_2}{r^2} = \frac{1}{16} F
$$

## Final Result

$$
F_{\text{new}} = \frac{F}{16}
$$

## Interpretation

- Halving both masses reduces the force by a factor of $1/4$.  
- Doubling the distance reduces the force by an additional factor of $1/4$.  
- Overall, the force becomes $1/16$ of its original value.