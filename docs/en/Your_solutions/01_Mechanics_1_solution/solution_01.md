## Task 1 — Projectile Motion

### Given

Initial velocity:
$$
v_0 = 100 \text{ m/s}
$$

Launch angle:
$$
\theta = 37^\circ
$$

Acceleration due to gravity:
$$
g = 9.8 \text{ m/s}^2
$$

No air resistance. Initial position is the ground:
$$
x(0) = 0, \quad y(0) = 0
$$

---

## 1. Differential Equations of Motion

### Horizontal Direction

No forces act horizontally ⇒ acceleration is zero:

$$
a_x = 0
$$

Using the definition of acceleration:

$$
\frac{d^2 x}{dt^2} = 0
$$

Integrate once to obtain velocity:

$$
\frac{dx}{dt} = C_1
$$

The constant equals the initial horizontal velocity:

$$
C_1 = v_0 \cos \theta
$$

Therefore:

$$
\frac{dx}{dt} = v_0 \cos \theta
$$

Integrate again to obtain position:

$$
x(t) = v_0 \cos \theta \cdot t
$$

---

### Vertical Direction

Gravity acts downward:

$$
a_y = -g
$$

$$
\frac{d^2 y}{dt^2} = -g
$$

Integrate once:

$$
\frac{dy}{dt} = -gt + C_2
$$

The constant equals the initial vertical velocity:

$$
C_2 = v_0 \sin \theta
$$

So:

$$
\frac{dy}{dt} = v_0 \sin \theta - gt
$$

Integrate again:

$$
y(t) = v_0 \sin \theta \cdot t - \frac{1}{2} g t^2
$$

---

## 2. Time of Flight

The projectile returns to the ground when:

$$
y(t) = 0
$$

Substitute the equation of motion:

$$
0 = v_0 \sin \theta \cdot t - \frac{1}{2} g t^2
$$

Factor out ( t ):

$$
t \left( v_0 \sin \theta - \frac{1}{2} g t \right) = 0
$$

Ignoring the trivial solution ( t = 0 ), solve:

$$
v_0 \sin \theta - \frac{1}{2} g t = 0
$$

$$
t = \frac{2 v_0 \sin \theta}{g}
$$

Substitute numerical values:

$$
t = \frac{2 \cdot 100 \cdot \sin 37^\circ}{9.8}
$$

Using:

$$
\sin 37^\circ \approx 0.6018
$$

$$
T \approx 12.3 \text{ s}
$$

---

## 3. Maximum Height

At the highest point, the vertical velocity is zero:

$$
v_y = v_0 \sin \theta - gt = 0
$$

Solve for time to reach the peak:

$$
t_{\text{max}} = \frac{v_0 \sin \theta}{g}
$$

Substitute into the height equation:

$$
H = v_0 \sin \theta \cdot t_{\text{max}} - \frac{1}{2} g t_{\text{max}}^2
$$

After simplification:

$$
H = \frac{(v_0 \sin \theta)^2}{2g}
$$

Substitute values:

$$
H = \frac{(100 \cdot 0.6018)^2}{2 \cdot 9.8}
$$

$$
H \approx 185 \text{ m}
$$

---

## 4. Range

Horizontal velocity is constant:

$$
v_x = v_0 \cos \theta
$$

Range equals horizontal speed multiplied by time of flight:

$$
R = v_x \cdot T
$$

$$
R = v_0 \cos \theta \cdot T
$$

Substitute values:

$$
R = 100 \cdot \cos 37^\circ \cdot 12.3
$$

Using:

$$
\cos 37^\circ \approx 0.7986
$$

$$
R \approx 981 \text{ m}
$$

---

## Final Results

Time of flight:
$$
T \approx 12.3 \text{ s}
$$

Maximum height:
$$
H \approx 185 \text{ m}
$$

Range:
$$
R \approx 981 \text{ m}
$$
