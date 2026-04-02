# Problem 9 – Potential and conservative field

Given potential energy:

$$
U(x,y)=\frac{k}{2}(x^2+y^2)
$$

---

## 1. Determine the force as the gradient of the potential

The force is:

$$
\vec F=-\nabla U
$$

Compute the partial derivatives:

$$
\frac{\partial U}{\partial x}=kx
$$

$$
\frac{\partial U}{\partial y}=ky
$$

Thus:

$$
\nabla U=(kx,ky)
$$

So the force is:

$$
\vec F(x,y)=(-kx,-ky)
$$

---

## 2. Equations of motion

By Newton's second law:

$$
m\ddot x=-kx
$$

$$
m\ddot y=-ky
$$

These are two independent harmonic oscillator equations.

---

## 3. Type of motion

Both coordinates perform harmonic motion:

$$
x(t)=A\cos(\omega t)+B\sin(\omega t)
$$

$$
y(t)=C\cos(\omega t)+D\sin(\omega t)
$$

with

$$
\omega=\sqrt{\frac{k}{m}}
$$

So the motion is oscillatory in two dimensions.

Depending on the initial conditions, the trajectory can be:

- a straight line,
- an ellipse,
- a circle.

---

## 4. Total energy

The kinetic energy is:

$$
T=\frac12 m(\dot x^2+\dot y^2)
$$

The potential energy is:

$$
U=\frac{k}{2}(x^2+y^2)
$$

So total energy is:

$$
E=\frac12 m(\dot x^2+\dot y^2)+\frac{k}{2}(x^2+y^2)
$$

Since the force is conservative, total energy is constant.

---

## 5. Geometrical interpretation of the trajectory

The potential depends only on

$$
x^2+y^2
$$

so it is radially symmetric.

This means the force always points toward the origin.

Thus the system behaves like a two-dimensional isotropic harmonic oscillator.

---

## Final results

Potential:

$$
U(x,y)=\frac{k}{2}(x^2+y^2)
$$

Force:

$$
\vec F(x,y)=(-kx,-ky)
$$

Equations of motion:

$$
m\ddot x=-kx,\qquad m\ddot y=-ky
$$

Total energy:

$$
E=\frac12 m(\dot x^2+\dot y^2)+\frac{k}{2}(x^2+y^2)
$$
