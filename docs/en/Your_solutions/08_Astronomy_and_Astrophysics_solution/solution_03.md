# Problem 3: Microgravity Analysis

This section provides the step-by-step mathematical derivation and physical explanation for the gravitational acceleration and the state of weightlessness experienced on the International Space Station (ISS).

---

## Part 1: Calculation of Gravitational Acceleration ($g$) at ISS Altitude

To find the acceleration due to gravity at the altitude of the ISS, we use Newton's Law of Universal Gravitation:

$$g = \frac{G \cdot M_E}{r^2}$$

### 1. Given Parameters:
* **Universal Gravitational Constant ($G$):** $6.674 \times 10^{-11} \text{ m}^3 \text{kg}^{-1} \text{s}^{-2}$
* **Mass of the Earth ($M_E$):** $5.97 \times 10^{24} \text{ kg}$
* **Mean Radius of the Earth ($R_E$):** $6378 \text{ km}$
* **Altitude of the ISS ($h$):** $400 \text{ km}$

### 2. Step-by-Step Calculation:

* **Step 1:** Calculate the total orbital radius ($r$) from the center of the Earth:
  $$r = R_E + h = 6378 \text{ km} + 400 \text{ km} = 6778 \text{ km} = 6.778 \times 10^6 \text{ m}$$

* **Step 2:** Substitute the values into the gravitational formula:
  $$g = \frac{(6.674 \times 10^{-11}) \cdot (5.97 \times 10^{24})}{(6.778 \times 10^6)^2}$$

* **Step 3:** Simplify the numerator and the denominator:
  $$G \cdot M_E = 3.98438 \times 10^{14}$$
  $$r^2 = (6.778 \times 10^6)^2 = 4.59413 \times 10^{13}$$

* **Step 4:** Compute the final value for $g$:
  $$g = \frac{3.98438 \times 10^{14}}{4.59413 \times 10^{13}} \approx \mathbf{8.69 \text{ m/s}^2}$$

### 3. Comparison with Surface Gravity:
$$\frac{g_{\text{orbital}}}{g_{\text{surface}}} = \frac{8.69 \text{ m/s}^2}{9.81 \text{ m/s}^2} \approx \mathbf{88.6\%}$$

**Result:** The acceleration due to gravity at the ISS altitude is approximately **$8.69 \text{ m/s}^2$**, which retains about **$89\%$** of Earth's surface gravity.

---

## Part 2: Physical Explanation of Apparent Weightlessness

Despite the presence of a strong gravitational field ($8.69 \text{ m/s}^2$), astronauts experience weightlessness due to the following mechanical principles:

1. **Definition of Weight:** Weight is fundamentally the normal force ($N$) exerted by a body against a supporting surface or scale. It is governed by the equation of motion in a moving reference frame:
   $$N = m(g - a)$$

2. **The Condition of Free Fall:** The ISS operates in a state of unconstrained orbital free fall. Because gravity is the only force acting on the system, the acceleration of the spacecraft ($a$) matches the local gravitational acceleration ($g$) exactly:
   $$a = g$$

3. **Vanishing Normal Force:** Substituting $a = g$ into the weight equation yields:
   $$N = m(g - g) = 0$$
   Since there is no supporting boundary resisting the gravitational pull, the normal force drops to zero, removing the physiological sensation of weight.

4. **Orbital Trajectory Mechanics:** The spacecraft avoids impacting the Earth due to its high tangential orbital velocity ($v \approx 7.67 \text{ km/s}$). At this velocity, the downward rate of the station's free fall matches the geometric curvature rate of the Earth's surface. Consequently, the ISS continuously falls toward the planet but perpetually misses the ground.
