## Task 3 — Path Intersection

### Given

The positions of Alice and Bob are functions of time:

$$
A(t) = (2 + t,; 8 - 3t)
$$

$$
B(t) = (2t - 1,; 2t + 2)
$$

---

## 1. Condition for Collision

For a collision to occur, both objects must be at the **same position at the same time**:

$$
A(t) = B(t)
$$

This requires equality of both coordinates:

$$
2 + t = 2t - 1
$$

$$
8 - 3t = 2t + 2
$$

---

## 2. Solve Using the x-Coordinates

$$
2 + t = 2t - 1
$$

Rearrange:

$$
2 + t - 2t + 1 = 0
$$

$$
3 - t = 0
$$

$$
t = 3
$$

---

## 3. Check the y-Coordinates at ( t = 3 )

### Alice:

$$
y_A = 8 - 3(3) = 8 - 9 = -1
$$

### Bob:

$$
y_B = 2(3) + 2 = 6 + 2 = 8
$$

Since:

$$
y_A \ne y_B
$$

the objects are not at the same point.

---

## 4. Conclusion: No Collision

Although the x-coordinates coincide at ( t = 3 ), the y-coordinates differ. Therefore, Alice and Bob **do not collide**.

---

## 5. Minimum Distance Between the Paths

Distance between the two points at time ( t ):

$$
D(t) = \sqrt{(x_A - x_B)^2 + (y_A - y_B)^2}
$$

Compute coordinate differences:

$$
x_A - x_B = (2+t) - (2t-1) = 3 - t
$$

$$
y_A - y_B = (8-3t) - (2t+2) = 6 - 5t
$$

Thus:

$$
D(t) = \sqrt{(3 - t)^2 + (6 - 5t)^2}
$$

---

## 6. Minimize the Distance

Minimizing ( D(t) ) is equivalent to minimizing its square:

$$
D^2(t) = (3 - t)^2 + (6 - 5t)^2
$$

Expand:

$$
D^2(t) = (t^2 - 6t + 9) + (25t^2 - 60t + 36)
$$

$$
D^2(t) = 26t^2 - 66t + 45
$$

---

## 7. Find Critical Point

Differentiate:

$$
\frac{d}{dt}D^2(t) = 52t - 66
$$

Set to zero:

$$
52t - 66 = 0
$$

$$
t = \frac{66}{52} = \frac{33}{26} \approx 1.27
$$

---

## 8. Minimum Distance Value

Substitute ( t = \frac{33}{26} ):

$$
3 - t = \frac{45}{26}, \quad 6 - 5t = -\frac{9}{26}
$$

$$
D^2_{\min} = \frac{45^2 + 9^2}{26^2}
= \frac{2106}{676}
$$

$$
D_{\min} = \frac{\sqrt{2106}}{26} \approx 1.76
$$

---

## Final Answer

* The paths do **not intersect**, so no collision occurs.
* The minimum distance between Alice and Bob is:

$$
D_{\min} = \frac{\sqrt{2106}}{26} \approx 1.76
$$

* This occurs at time:

$$
t = \frac{33}{26} \approx 1.27
$$

---
