## Task 5 — Relative Velocity (Boat Crossing a River)

### Given

* River flows east with speed:
  $$
  v_r = 2 \text{ m/s}
  $$

* Boat speed relative to still water:
  $$
  v_b = 5 \text{ m/s}
  $$

* River width:
  $$
  W = 200 \text{ m}
  $$

Goal:

1. Determine the direction (angle) the boat must head to travel **directly north** across the river.
2. Find the time required to cross.

---

## 1. Physical Principle: Relative Velocity

The boat's velocity relative to the ground equals the vector sum of:

* Boat velocity relative to water
* Water velocity relative to ground

$$
\vec v_{\text{ground}} =
\vec v_{\text{boat/water}} + \vec v_{\text{river}}
$$

---

## 2. Condition for Straight North Motion

To move directly north relative to the ground:

👉 The east-west component of the total velocity must be zero.

The river pushes east at (2\text{ m/s}), so the boat must aim westward to cancel this drift.

---

## 3. Resolve Boat Velocity into Components

Let the boat head at an angle ( \theta ) west of north.

Boat speed magnitude:

$$
v_b = 5 \text{ m/s}
$$

West component:

$$
v_W = 5 \sin \theta
$$

North component:

$$
v_N = 5 \cos \theta
$$

---

## 4. Cancel the River Current

To eliminate eastward motion:

$$
v_W = v_r
$$

$$
5 \sin \theta = 2
$$

Solve:

$$
\sin \theta = 0.4
$$

$$
\theta = \sin^{-1}(0.4) \approx 23.6^\circ
$$

---

## 5. Northward Speed Across the River

Only the north component moves the boat across.

$$
v_{\text{north}} = 5 \cos \theta
$$

Using:

$$
\cos \theta = \sqrt{1 - \sin^2 \theta}
= \sqrt{1 - 0.4^2}
= \sqrt{0.84} \approx 0.9165
$$

$$
v_{\text{north}} \approx 5 \times 0.9165 \approx 4.58 \text{ m/s}
$$

---

## 6. Time to Cross the River

Time equals distance divided by speed:

$$
t = \frac{W}{v_{\text{north}}}
$$

$$
t = \frac{200}{4.58} \approx 43.7 \text{ s}
$$

---

## Final Answer

Direction:

$$
\boxed{\theta \approx 23.6^\circ \text{ west of north}}
$$

Time to cross:

$$
\boxed{t \approx 43.7 \text{ s}}
$$

The boat must aim upstream (toward the west) to counteract the river current and arrive directly opposite its starting point.

---
