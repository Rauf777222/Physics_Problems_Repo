# Problem 4 – Wave equation

Given:

$$
y(x,t)=A\cos(kx-\omega t)
$$

We verify that it satisfies the wave equation

$$
\frac{\partial^2 y}{\partial t^2}=v^2\frac{\partial^2 y}{\partial x^2}
$$

---

## 1. Second derivative with respect to time

First derivative:

$$
\frac{\partial y}{\partial t}
=
-A\sin(kx-\omega t)(-\omega)
$$

$$
\frac{\partial y}{\partial t}
=
A\omega \sin(kx-\omega t)
$$

Second derivative:

$$
\frac{\partial^2 y}{\partial t^2}
=
A\omega\cos(kx-\omega t)(-\omega)
$$

$$
\frac{\partial^2 y}{\partial t^2}
=
-\omega^2 A\cos(kx-\omega t)
$$

Thus:

$$
\frac{\partial^2 y}{\partial t^2}
=
-\omega^2 y
$$

---

## 2. Second derivative with respect to position

First derivative:

$$
\frac{\partial y}{\partial x}
=
-A\sin(kx-\omega t)\cdot k
$$

$$
\frac{\partial y}{\partial x}
=
-kA\sin(kx-\omega t)
$$

Second derivative:

$$
\frac{\partial^2 y}{\partial x^2}
=
-kA\cos(kx-\omega t)\cdot k
$$

$$
\frac{\partial^2 y}{\partial x^2}
=
-k^2A\cos(kx-\omega t)
$$

Thus:

$$
\frac{\partial^2 y}{\partial x^2}
=
-k^2y
$$

---

## 3. Substitute into the wave equation

We need:

$$
\frac{\partial^2 y}{\partial t^2}=v^2\frac{\partial^2 y}{\partial x^2}
$$

Substitute both expressions:

$$
-\omega^2 y=v^2(-k^2 y)
$$

Cancel \(-y\):

$$
\omega^2=v^2k^2
$$

Thus:

$$
v=\frac{\omega}{k}
$$

---

## Final results

The function satisfies the wave equation provided that

$$
\omega^2=v^2k^2
$$

or equivalently

$$
v=\frac{\omega}{k}
$$
