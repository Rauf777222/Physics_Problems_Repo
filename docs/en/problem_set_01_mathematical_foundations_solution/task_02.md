# Problem 2 – Parametric trajectory, velocity, and acceleration

Given trajectory:

$$
\vec r(t) = (t^2,\sin t,5)
$$

---

## 1. Velocity vector

Velocity is the first derivative of position:

$$
\vec v(t)=\frac{d\vec r(t)}{dt}
$$

Differentiate each component:

$$
\vec v(t)=\left(\frac{d}{dt}t^2,\frac{d}{dt}\sin t,\frac{d}{dt}5\right)
$$

$$
\vec v(t)=(2t,\cos t,0)
$$

---

## 2. Acceleration vector

Acceleration is the derivative of velocity:

$$
\vec a(t)=\frac{d\vec v(t)}{dt}=\frac{d^2\vec r(t)}{dt^2}
$$

Differentiate each component:

$$
\vec a(t)=\left(\frac{d}{dt}2t,\frac{d}{dt}\cos t,\frac{d}{dt}0\right)
$$

$$
\vec a(t)=(2,-\sin t,0)
$$

---

## 3. Magnitude of the velocity at \( t=1 \)

First calculate:

$$
\vec v(1)=(2\cdot 1,\cos 1,0)=(2,\cos 1,0)
$$

The magnitude of a vector is:

$$
|\vec v(1)|=\sqrt{2^2+(\cos 1)^2+0^2}
$$

$$
|\vec v(1)|=\sqrt{4+\cos^2 1}
$$

Approximate value:

$$
\cos 1 \approx 0.5403
$$

$$
|\vec v(1)|\approx \sqrt{4+0.5403^2}
=\sqrt{4+0.2919}
=\sqrt{4.2919}
\approx 2.07
$$

---

## 4. Dot product \( \vec v \cdot \vec a \)

Using

$$
\vec v(t)=(2t,\cos t,0), \qquad \vec a(t)=(2,-\sin t,0)
$$

the dot product is:

$$
\vec v \cdot \vec a=(2t)(2)+(\cos t)(-\sin t)+0\cdot 0
$$

$$
\vec v \cdot \vec a=4t-\sin t \cos t
$$

---

## 5. Cross product \( \vec v \times \vec a \)

We compute:

$$
\vec v \times \vec a =
\begin{vmatrix}
\mathbf i & \mathbf j & \mathbf k \\
2t & \cos t & 0 \\
2 & -\sin t & 0
\end{vmatrix}
$$

Expanding the determinant:

$$
\vec v \times \vec a
=
\mathbf i(\cos t \cdot 0 - 0 \cdot (-\sin t))
-\mathbf j(2t \cdot 0 - 0 \cdot 2)
+\mathbf k(2t(-\sin t)-\cos t \cdot 2)
$$

$$
\vec v \times \vec a
=
(0,0,-2t\sin t-2\cos t)
$$

So:

$$
\vec v \times \vec a=(0,0,-2t\sin t-2\cos t)
$$

---

## Final answers

$$
\vec v(t)=(2t,\cos t,0)
$$

$$
\vec a(t)=(2,-\sin t,0)
$$

$$
|\vec v(1)|=\sqrt{4+\cos^2 1}\approx 2.07
$$

$$
\vec v \cdot \vec a=4t-\sin t\cos t
$$

$$
\vec v \times \vec a=(0,0,-2t\sin t-2\cos t)
$$
