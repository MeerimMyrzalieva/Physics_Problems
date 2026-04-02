# 📘 Vertical Throw with Drag — Solution

## 🔹 Given

m dv/dt = -mg - kv  
v(0) = v₀  
x(0) = 10  

---

## 🔹 1. Analytical Solution

### Step 1: Divide by m

dv/dt = -g - (k/m)v  

---

### Step 2: Linear form

dv/dt + (k/m)v = -g  

---

### Step 3: Integrating factor

μ(t) = e^(k/m · t)

---

### Step 4: Multiply equation

d/dt (v e^(k/m t)) = -g e^(k/m t)

---

### Step 5: Integrate

v e^(k/m t) = -(mg/k)e^(k/m t) + C

---

### Step 6: Solve for v(t)

v(t) = -(mg/k) + C e^(-k/m t)

---

### Step 7: Apply v(0) = v₀

C = v₀ + mg/k

---

## ✅ Final velocity

v(t) = (v₀ + mg/k)e^(-k/m t) - mg/k

---

## 🔹 2. Position

x(t) = 10 + (m/k)(v₀ + mg/k)(1 - e^(-k/m t)) - (mg/k)t

---

## 🔹 3. Maximum Height

v(t) = 0

t_max = (m/k) ln((v₀ + mg/k)/(mg/k))

h_max = x(t_max)

---

## 🔹 4. Without Drag

v = v₀ - gt  

h = v₀² / (2g)

---

## 🔹 5. Comparison

With drag:
- exponential decay  
- lower height  
- asymmetric motion  

Without drag:
- linear velocity  
- symmetric motion  
- higher height  

---
<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/069d4246-9e14-4630-9e8d-582775730e73" />

