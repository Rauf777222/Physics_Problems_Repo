# Problem 2 – Inclined plane with friction

A body of mass \(m\) slides down an inclined plane of angle \(\alpha\).  
The coefficient of kinetic friction is \(\mu\).

---

## 1. Forces acting on the body

The forces are:

1. Gravitational force:

$$
\vec F_g = m\vec g
$$

2. Normal force:

$$
N = mg\cos\alpha
$$

3. Kinetic friction:

$$
F_f = \mu N = \mu mg\cos\alpha
$$

The component of gravity along the plane is:

$$
F_{\parallel}=mg\sin\alpha
$$

Thus the net force along the plane is:

$$
F_{\text{net}}=mg\sin\alpha-\mu mg\cos\alpha
$$

---

## 2. Acceleration

By Newton's second law:

$$
ma=mg\sin\alpha-\mu mg\cos\alpha
$$

Divide by \(m\):

$$
a=g(\sin\alpha-\mu\cos\alpha)
$$

---

## 3. Time of descent from height \(h\)

The length of the incline is:

$$
s=\frac{h}{\sin\alpha}
$$

Assuming the body starts from rest, the motion equation along the plane is:

$$
s=\frac12 at^2
$$

So:

$$
\frac{h}{\sin\alpha}=\frac12 g(\sin\alpha-\mu\cos\alpha)t^2
$$

Hence:

$$
t=\sqrt{\frac{2h}{g\sin\alpha(\sin\alpha-\mu\cos\alpha)}}
$$

---

## 4. Final velocity

Use the kinematic formula:

$$
v^2=2as
$$

Substitute \(a\) and \(s\):

$$
v^2=2g(\sin\alpha-\mu\cos\alpha)\cdot \frac{h}{\sin\alpha}
$$

Thus:

$$
v=\sqrt{\frac{2gh(\sin\alpha-\mu\cos\alpha)}{\sin\alpha}}
$$

---

## 5. Check with energy balance

Potential energy loss:

$$
\Delta U = mgh
$$

Work of friction:

$$
W_f = -F_f s=-\mu mg\cos\alpha\cdot \frac{h}{\sin\alpha}
$$

Final kinetic energy:

$$
\frac12 mv^2
$$

Energy balance:

$$
mgh-\mu mg\cos\alpha\cdot \frac{h}{\sin\alpha}=\frac12 mv^2
$$

Divide by \(m\):

$$
gh-\mu g h\frac{\cos\alpha}{\sin\alpha}=\frac12 v^2
$$

So:

$$
v^2=2gh\left(1-\mu\frac{\cos\alpha}{\sin\alpha}\right)
$$

This is equivalent to the result obtained above.

---

## Final results

Acceleration:

$$
a=g(\sin\alpha-\mu\cos\alpha)
$$

Time of descent:

$$
t=\sqrt{\frac{2h}{g\sin\alpha(\sin\alpha-\mu\cos\alpha)}}
$$

Final velocity:

$$
v=\sqrt{\frac{2gh(\sin\alpha-\mu\cos\alpha)}{\sin\alpha}}
$$
