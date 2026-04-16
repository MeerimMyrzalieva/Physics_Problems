# Section 4: Electromagnetism I  

## 6. Field at a point from a system of charges

Two point charges are given:

+q at point (-a, 0)  
+2q at point (a, 0)  

---

### Step 1: General formula

Electric field of a point charge:

E = k q r / |r|^3

---

### Step 2: Position vectors

From charge +q:

r1 = (x + a, y)

From charge +2q:

r2 = (x - a, y)

---

### Step 3: Electric fields

E1 = kq (x + a, y) / [(x + a)^2 + y^2]^(3/2)

E2 = 2kq (x - a, y) / [(x - a)^2 + y^2]^(3/2)

---

### Step 4: Total field

E(x, y) = E1 + E2

Components:

Ex = kq (x + a)/[(x + a)^2 + y^2]^(3/2) 
   + 2kq (x - a)/[(x - a)^2 + y^2]^(3/2)

Ey = kq y/[(x + a)^2 + y^2]^(3/2) 
   + 2kq y/[(x - a)^2 + y^2]^(3/2)

---

### Step 5: Field at (0, y)

Ex = -kqa / (a^2 + y^2)^(3/2)

Ey = 3kqy / (a^2 + y^2)^(3/2)

E(0, y) = ( -kqa/(a^2+y^2)^(3/2) , 3kqy/(a^2+y^2)^(3/2) )

---

### Step 6: Field at (x, 0)

Ex = kq (x+a)/|x+a|^3 + 2kq (x-a)/|x-a|^3

Ey = 0

---

### Step 7: Conditions

Ey = 0  →  y = 0  

Ex = 0  → solve:
kq (x+a)/|x+a|^3 + 2kq (x-a)/|x-a|^3 = 0  

E = 0 → only on x-axis between charges

---

### Step 8: Numerical calculation

Given:

a = 0.2 m  
y = 0.3 m  
q = 2 × 10^-6 C  
k = 9 × 10^9  

a^2 + y^2 = 0.13  
(0.13)^(3/2) ≈ 0.0469  

Ex = -7.7 × 10^4 N/C  
Ey = 3.45 × 10^5 N/C  

E ≈ ( -7.7×10^4 , 3.45×10^5 ) N/C  

---

### Step 9: Limit y >> a

(a^2 + y^2)^(3/2) ≈ y^3  

Ex ≈ -kqa / y^3  (small)  

Ey ≈ 3kq / y^2  

---

### Final interpretation

At large distance → system behaves like a single charge 3q  
Field is mainly along y-axis
