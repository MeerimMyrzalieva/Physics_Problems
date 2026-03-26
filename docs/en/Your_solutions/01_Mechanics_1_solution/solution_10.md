# Problem 10: 3D Motion

The position vector of a point is:

$$
\vec r(t) = (a\cos(\omega t),; b\sin(\omega t),; bt),
$$

where (a), (b), and (\omega) are positive constants.

We want:

a) The trajectory equation
b) The path length from (t=0) to (t=t_0)
c) A description (and visualization) of the motion

---

## a) Equation of the Trajectory

From the x- and y-components:

$$
x = a\cos(\omega t), \qquad
y = b\sin(\omega t)
$$

Divide by (a) and (b):

$$
\frac{x}{a} = \cos(\omega t), \qquad
\frac{y}{b} = \sin(\omega t)
$$

Use the identity:

$$
\cos^2(\theta) + \sin^2(\theta) = 1
$$

Therefore:

$$
\frac{x^2}{a^2} + \frac{y^2}{b^2} = 1
$$

This is an ellipse in the (xy)-plane.

Since

$$
z = bt
$$

increases linearly with time, the point moves upward while circling the ellipse.

👉 The trajectory is an **elliptical helix**.

---

## b) Path Length from (0) to (t_0)

Speed is the magnitude of velocity:

$$
\vec v(t) = \frac{d\vec r}{dt}
$$

Differentiate components:

$$
\frac{dx}{dt} = -a\omega \sin(\omega t)
$$

$$
\frac{dy}{dt} = b\omega \cos(\omega t)
$$

$$
\frac{dz}{dt} = b
$$

Speed:

$$
|\vec v| =
\sqrt{a^2\omega^2\sin^2(\omega t)

* b^2\omega^2\cos^2(\omega t)
* b^2}
  $$

Path length:

$$
L = \int_0^{t_0} |\vec v(t)|,dt
$$

(For general (a\neq b), this integral does not simplify to an elementary formula.)

---

## c) Description of Motion

* The projection on the (xy)-plane is an ellipse
* The point rotates with angular speed (\omega)
* The height increases linearly
* Motion is a spiral rising upward

---

## Final Answer

Trajectory:

$$
\frac{x^2}{a^2} + \frac{y^2}{b^2} = 1, \quad z = bt
$$

Type of motion:

$$
\boxed{\text{Elliptical helix}}
$$

---

## Illustration of the Motion

![Image](https://www.researchgate.net/publication/232705350/figure/fig5/AS%3A667935861374994%401536259727871/a-A-helix-defined-by-the-parametric-equation-r-cost-r-sint-pt-b-A-set-of.jpg)

![Image](https://www.researchgate.net/publication/384299251/figure/fig3/AS%3A11431281375187540%401744639642434/A-3D-representation-of-a-helix-curve-shown-in-blue-The-radial-coordinate-th-is.tif)

![Image](https://i.sstatic.net/Ut9UM.png)

![Image](https://i.sstatic.net/i533L.png)

The point moves around an ellipse while steadily rising, forming a three-dimensional spiral.
