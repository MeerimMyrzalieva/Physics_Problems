# Problem 7: Parametric Motion

We are given the parametric equations of motion:

$$
x(t)=2t^2, \qquad y(t)=3t^3
$$

We want:

1. Eliminate the parameter ( t ) and obtain the trajectory ( y(x) ).
2. Find the velocity vector ( \vec v(t) ) and its magnitude.
3. Find the acceleration vector ( \vec a(t) ) and its magnitude.
4. Determine whether the acceleration is constant.
5. Plot the trajectory.

---

## 1) Elimination of the parameter ( t )

From the equation for ( x(t) ):

$$
x = 2t^2
$$

Solve for ( t^2 ):

$$
t^2 = \frac{x}{2}
$$

For ( t \ge 0 ):

$$
t = \sqrt{\frac{x}{2}}
$$

Now substitute into ( y(t) ):

$$
y = 3t^3
$$

Write ( t^3 = t \cdot t^2 ):

$$
t^3 = \sqrt{\frac{x}{2}} \cdot \frac{x}{2}
$$

Therefore:

$$
y = 3\left(\frac{x}{2}\right)^{3/2}
$$

So the trajectory in Cartesian coordinates is:

$$
y(x) = 3\left(\frac{x}{2}\right)^{3/2}
$$

---

## 2) Velocity from position

Velocity is the derivative of position:

$$
\vec v(t) = \left(\frac{dx}{dt},;\frac{dy}{dt}\right)
$$

Differentiate each coordinate.

For ( x(t)=2t^2 ):

$$
\frac{dx}{dt} = 4t
$$

For ( y(t)=3t^3 ):

$$
\frac{dy}{dt} = 9t^2
$$

Thus:

$$
\vec v(t) = (4t,;9t^2)
$$

---

### Speed (magnitude of velocity)

$$
|\vec v(t)| =
\sqrt{(4t)^2 + (9t^2)^2}
$$

$$
|\vec v(t)| =
\sqrt{16t^2 + 81t^4}
$$

---

## 3) Acceleration from velocity

Acceleration is the derivative of velocity:

$$
\vec a(t) = \left(\frac{d^2x}{dt^2},;\frac{d^2y}{dt^2}\right)
$$

Differentiate again.

For the x-component:

$$
\frac{d^2x}{dt^2} = 4
$$

For the y-component:

$$
\frac{d^2y}{dt^2} = 18t
$$

Therefore:

$$
\vec a(t) = (4,;18t)
$$

---

### Magnitude of acceleration

$$
|\vec a(t)| =
\sqrt{4^2 + (18t)^2}
$$

$$
|\vec a(t)| =
\sqrt{16 + 324t^2}
$$

---

## 4) Is acceleration constant?

A constant acceleration would not depend on time.

Here:

$$
\vec a(t) = (4,;18t)
$$

The second component depends on ( t ).

Therefore:

$$
\text{Acceleration is NOT constant}
$$

---

## Final results

Trajectory:

$$
y = 3\left(\frac{x}{2}\right)^{3/2}
$$

Velocity:

$$
\vec v(t) = (4t,;9t^2)
$$

Acceleration:

$$
\vec a(t) = (4,;18t)
$$

Acceleration is time-dependent.

---

<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/4a5f088d-b0b2-40de-ab4b-091be9570031" />
