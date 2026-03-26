# Problem 7 – 2D motion with a given acceleration

Given:

$$
\vec a=(2,-3),\qquad \vec v(0)=(1,0),\qquad \vec r(0)=(0,0)
$$

---

## 1. Determine \( \vec v(t) \)

Velocity is obtained by integrating acceleration:

$$
\vec v(t)=\vec v(0)+\int_0^t \vec a\,d\tau
$$

Since acceleration is constant:

$$
\vec v(t)=(1,0)+(2t,-3t)
$$

Thus:

$$
\vec v(t)=(1+2t,\,-3t)
$$

---

## 2. Determine \( \vec r(t) \)

Position is obtained by integrating velocity:

$$
\vec r(t)=\vec r(0)+\int_0^t \vec v(\tau)\,d\tau
$$

Substitute:

$$
\vec r(t)=\int_0^t (1+2\tau,-3\tau)\,d\tau
$$

Integrate componentwise:

$$
x(t)=\int_0^t (1+2\tau)\,d\tau
$$

$$
x(t)=\left[\tau+\tau^2\right]_0^t=t+t^2
$$

and

$$
y(t)=\int_0^t (-3\tau)\,d\tau
$$

$$
y(t)=\left[-\frac32\tau^2\right]_0^t=-\frac32 t^2
$$

Therefore:

$$
\vec r(t)=\left(t+t^2,\,-\frac32 t^2\right)
$$

---

## 3. Trajectory

We eliminate \(t\).

From

$$
x=t+t^2
$$

and

$$
y=-\frac32 t^2
$$

we get:

$$
t^2=-\frac{2}{3}y
$$

Substitute into the first equation:

$$
x=t-\frac{2}{3}y
$$

The trajectory is parabolic in nature.

---

## Final results

Velocity:

$$
\vec v(t)=(1+2t,\,-3t)
$$

Position:

$$
\vec r(t)=\left(t+t^2,\,-\frac32 t^2\right)
$$

Acceleration:

$$
\vec a=(2,-3)
$$
