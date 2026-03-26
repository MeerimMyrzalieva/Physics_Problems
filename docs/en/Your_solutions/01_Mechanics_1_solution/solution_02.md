## Task 2 — Range Optimization

### Given

For projectile motion (without air resistance), the horizontal range is:

$$
R(\theta) = \frac{v_0^2 \sin(2\theta)}{g}
$$

where:

* ( v_0 ) — initial velocity (constant)
* ( g ) — gravitational acceleration (constant)
* ( \theta ) — launch angle (variable)

Goal:

👉 Show analytically that the range is maximal at ( \theta = 45^\circ )

---

## 1. Identify Constants and Variable

Since ( v_0 ) and ( g ) are constants, the only variable affecting the range is:

$$
\sin(2\theta)
$$

Rewrite the range as:

$$
R(\theta) = C \cdot \sin(2\theta),
\quad \text{where } C = \frac{v_0^2}{g}
$$

---

## 2. Find the Maximum Using Calculus

To maximize a function, take the derivative with respect to ( \theta ) and set it equal to zero.

Differentiate:

$$
\frac{dR}{d\theta}
= C \cdot \frac{d}{d\theta}[\sin(2\theta)]
$$

Using the chain rule:

$$
\frac{d}{d\theta}[\sin(2\theta)] = 2\cos(2\theta)
$$

Therefore:

$$
\frac{dR}{d\theta} = 2C \cos(2\theta)
$$

---

## 3. Critical Point

Set derivative equal to zero:

$$
2C \cos(2\theta) = 0
$$

Since ( C \neq 0 ), divide both sides by ( 2C ):

$$
\cos(2\theta) = 0
$$

Solve:

$$
2\theta = 90^\circ
$$

$$
\theta = 45^\circ
$$

---

## 4. Verify That This Is a Maximum

The sine function reaches its maximum value of 1 when its argument is ( 90^\circ ):

$$
\sin(2\theta) \le 1
$$

At ( \theta = 45^\circ ):

$$
\sin(2\theta) = \sin(90^\circ) = 1
$$

Thus the range becomes:

$$
R_{\max} = \frac{v_0^2}{g}
$$

---

## Final Result

The projectile range is maximized when:

$$
\boxed{\theta = 45^\circ}
$$

Maximum range:

$$
R_{\max} = \frac{v_0^2}{g}
$$
