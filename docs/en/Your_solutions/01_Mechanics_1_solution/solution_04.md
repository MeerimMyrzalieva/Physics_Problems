## Task 4 — Vector Calculus (Velocity and Acceleration)

### Given

The position vector of the object is:

$$
\vec{r}(t) = (3t^2),\hat{i} + (5t - 8t^2),\hat{j}
$$

---

## 1. Understanding the Position Vector

A position vector in 2D has the form:

$$
\vec{r}(t) = x(t),\hat{i} + y(t),\hat{j}
$$

Thus, the coordinate functions are:

$$
x(t) = 3t^2, \qquad y(t) = 5t - 8t^2
$$

---

## 2. Velocity Vector

Velocity is the time derivative of position:

$$
\vec{v}(t) = \frac{d\vec{r}(t)}{dt}
$$

Differentiate each component separately.

### x-component:

$$
v_x = \frac{d}{dt}(3t^2) = 6t
$$

### y-component:

$$
v_y = \frac{d}{dt}(5t - 8t^2) = 5 - 16t
$$

---

### Velocity Vector Result

$$
\vec{v}(t) = (6t),\hat{i} + (5 - 16t),\hat{j}
$$

---

## 3. Acceleration Vector

Acceleration is the derivative of velocity:

$$
\vec{a}(t) = \frac{d\vec{v}(t)}{dt}
$$

Again differentiate component-wise.

### x-component:

$$
a_x = \frac{d}{dt}(6t) = 6
$$

### y-component:

$$
a_y = \frac{d}{dt}(5 - 16t) = -16
$$

---

### Acceleration Vector Result

$$
\vec{a}(t) = 6,\hat{i} - 16,\hat{j}
$$

---

## 4. Interpretation

The acceleration vector is constant:

$$
\vec{a} = (6,,-16)
$$

This means:

* The object experiences uniform acceleration
* Motion is similar to projectile motion with constant force components
* The trajectory is a parabola in the plane

---

## Final Answer

Velocity:

$$
\boxed{\vec{v}(t) = (6t),\hat{i} + (5 - 16t),\hat{j}}
$$

Acceleration:

$$
\boxed{\vec{a}(t) = 6,\hat{i} - 16,\hat{j}}
$$

---
