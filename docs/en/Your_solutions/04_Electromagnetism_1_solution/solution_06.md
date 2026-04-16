# Section 4 — Electromagnetism I  
## 6. Field at a point from a system of charges  

Two point charges are given:

$$
+q \text{ at point } (-a,0), \qquad +2q \text{ at point } (a,0)
$$

---

## Necessary formulas

### Electric field of a point charge

$$
\vec{E} = k q \frac{\vec{r}}{|\vec{r}|^3}
$$

---

## (a) General expression $\vec{E}(x,y)$

### Position vectors

$$
\vec{r}_1 = (x+a,\,y), \qquad \vec{r}_2 = (x-a,\,y)
$$

---

### Electric fields

$$
\vec{E}_1 = kq \frac{(x+a,\,y)}{\left[(x+a)^2 + y^2\right]^{3/2}}
$$

$$
\vec{E}_2 = 2kq \frac{(x-a,\,y)}{\left[(x-a)^2 + y^2\right]^{3/2}}
$$

---

### Total field

$$
\vec{E}(x,y) = \vec{E}_1 + \vec{E}_2
$$

---

### 5) Components

Ex = kq * (x + a)/[(x + a)^2 + y^2]^(3/2)
   + 2kq * (x - a)/[(x - a)^2 + y^2]^(3/2)

Ey = kq * y/[(x + a)^2 + y^2]^(3/2)
   + 2kq * y/[(x - a)^2 + y^2]^(3/2)


---

## (b) Field at $(0,y)$

$$
E_x = -\frac{kqa}{(a^2+y^2)^{3/2}}, \qquad
E_y = \frac{3kqy}{(a^2+y^2)^{3/2}}
$$

$$
\vec{E}(0,y) =
\left(
-\frac{kqa}{(a^2+y^2)^{3/2}},\;
\frac{3kqy}{(a^2+y^2)^{3/2}}
\right)
$$

---

## (c) Field at $(x,0)$

$$
E_x = kq \frac{x+a}{|x+a|^3} + 2kq \frac{x-a}{|x-a|^3}, \qquad E_y = 0
$$

---

## (d) Conditions

$$
E_y = 0 \Rightarrow y = 0
$$

$$
E_x = 0 \Rightarrow 
kq \frac{x+a}{|x+a|^3} + 2kq \frac{x-a}{|x-a|^3} = 0
$$

$$
\vec{E} = 0 \text{ only on the x-axis between the charges}
$$

---

## (e) Numerical calculation

$$
a = 0.2\,\text{m}, \quad y = 0.3\,\text{m}, \quad q = 2\times10^{-6}\,\text{C}
$$

$$
a^2 + y^2 = 0.13, \qquad (0.13)^{3/2} \approx 0.0469
$$

$$
E_x \approx -7.7 \times 10^4 \,\text{N/C}, \qquad
E_y \approx 3.45 \times 10^5 \,\text{N/C}
$$

$$
\vec{E} \approx (-7.7\times10^4,\; 3.45\times10^5)\,\text{N/C}
$$

---

## (f) Limit $y \gg a$

$$
(a^2 + y^2)^{3/2} \approx y^3
$$

$$
E_x \approx -\frac{kqa}{y^3}, \qquad
E_y \approx \frac{3kq}{y^2}
$$

---

## Final interpretation

$$
\vec{E} \approx \frac{3kq}{y^2}
$$

The system behaves like a single charge $3q$.
