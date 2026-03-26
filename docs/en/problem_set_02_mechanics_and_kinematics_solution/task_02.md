# Problem 2 – Projectile motion

A body moves in the Earth's gravitational field without air resistance.

Let the initial velocity be \(v_0\) and the launch angle be \(\alpha\).

---

## 1. Equations of motion

We decompose the initial velocity into components:

$$
v_{0x}=v_0\cos\alpha,\qquad v_{0y}=v_0\sin\alpha
$$

In the horizontal direction there is no acceleration:

$$
a_x=0
$$

So:

$$
x(t)=v_0\cos\alpha\; t
$$

In the vertical direction the acceleration is:

$$
a_y=-g
$$

So:

$$
y(t)=v_0\sin\alpha\; t-\frac12 gt^2
$$

---

## 2. Time of flight

The projectile lands when:

$$
y(t)=0
$$

Thus:

$$
v_0\sin\alpha\; t-\frac12 gt^2=0
$$

Factor out \(t\):

$$
t\left(v_0\sin\alpha-\frac12 gt\right)=0
$$

Ignoring \(t=0\), we get:

$$
v_0\sin\alpha-\frac12 gt=0
$$

$$
t=\frac{2v_0\sin\alpha}{g}
$$

So the time of flight is:

$$
T=\frac{2v_0\sin\alpha}{g}
$$

---

## 3. Maximum height

Maximum height occurs when vertical velocity is zero:

$$
v_y(t)=v_0\sin\alpha-gt
$$

Set \(v_y=0\):

$$
v_0\sin\alpha-gt=0
$$

$$
t_H=\frac{v_0\sin\alpha}{g}
$$

Now substitute into \(y(t)\):

$$
H_{\max}=v_0\sin\alpha\cdot \frac{v_0\sin\alpha}{g}-\frac12 g\left(\frac{v_0\sin\alpha}{g}\right)^2
$$

$$
H_{\max}=\frac{v_0^2\sin^2\alpha}{g}-\frac12\frac{v_0^2\sin^2\alpha}{g}
$$

$$
H_{\max}=\frac{v_0^2\sin^2\alpha}{2g}
$$

---

## 4. Range

Range is the horizontal distance at landing time \(T\):

$$
R=x(T)=v_0\cos\alpha\cdot T
$$

Substitute \(T=\frac{2v_0\sin\alpha}{g}\):

$$
R=v_0\cos\alpha\cdot \frac{2v_0\sin\alpha}{g}
$$

$$
R=\frac{2v_0^2\sin\alpha\cos\alpha}{g}
$$

Using

$$
2\sin\alpha\cos\alpha=\sin 2\alpha
$$

we obtain:

$$
R=\frac{v_0^2\sin 2\alpha}{g}
$$

---

## 5. Angle for maximum range

The range is maximal when \(\sin 2\alpha=1\).

This happens when:

$$
2\alpha=90^\circ
$$

So:

$$
\alpha=45^\circ
$$

---

## Final results

Horizontal motion:

$$
x(t)=v_0\cos\alpha\; t
$$

Vertical motion:

$$
y(t)=v_0\sin\alpha\; t-\frac12 gt^2
$$

Time of flight:

$$
T=\frac{2v_0\sin\alpha}{g}
$$

Maximum height:

$$
H_{\max}=\frac{v_0^2\sin^2\alpha}{2g}
$$

Range:

$$
R=\frac{v_0^2\sin 2\alpha}{g}
$$

Maximum range occurs for:

$$
\alpha=45^\circ
$$
