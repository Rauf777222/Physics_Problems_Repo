# Problem 1 – Newton's second law (constant force)

A constant force acts on a body of mass

$$
m=2\ \text{kg}
$$

The force is

$$
\vec F=(6,2)\ \text{N}
$$

Initial conditions:

$$
\vec v(0)=(1,-1)\ \text{m/s}, \qquad \vec r(0)=(0,0)\ \text{m}
$$

---

## 1. Determine the acceleration \( \vec a(t) \)

By Newton's second law:

$$
\vec F=m\vec a
$$

So:

$$
\vec a=\frac{\vec F}{m}
$$

Substitute the data:

$$
\vec a=\frac{(6,2)}{2}=(3,1)\ \text{m/s}^2
$$

Thus:

$$
\vec a(t)=(3,1)
$$

The acceleration is constant.

---

## 2. Determine the velocity \( \vec v(t) \)

Velocity is obtained by integrating acceleration:

$$
\vec v(t)=\vec v(0)+\vec a\,t
$$

So:

$$
\vec v(t)=(1,-1)+(3,1)t
$$

Therefore:

$$
\vec v(t)=(1+3t,\,-1+t)
$$

---

## 3. Determine the position \( \vec r(t) \)

Position is obtained by integrating velocity:

$$
\vec r(t)=\vec r(0)+\vec v(0)t+\frac12\vec a\,t^2
$$

Since \( \vec r(0)=(0,0) \), we get:

$$
\vec r(t)=(1,-1)t+\frac12(3,1)t^2
$$

Thus:

$$
\vec r(t)=\left(t+\frac32 t^2,\,-t+\frac12 t^2\right)
$$

---

## 4. Trajectory of motion

The trajectory is given parametrically by:

$$
x(t)=t+\frac32 t^2
$$

$$
y(t)=-t+\frac12 t^2
$$

This is a parabolic-type trajectory in the plane.

---

## 5. Work done by the force up to time \( t=3\ \text{s} \)

The displacement after 3 seconds is:

$$
\vec r(3)=\left(3+\frac32\cdot 9,\,-3+\frac12\cdot 9\right)
$$

$$
\vec r(3)=\left(3+13.5,\,-3+4.5\right)
$$

$$
\vec r(3)=(16.5,1.5)
$$

Since \( \vec r(0)=(0,0) \), the displacement is:

$$
\Delta \vec r=(16.5,1.5)
$$

The work done by a constant force is:

$$
W=\vec F\cdot \Delta \vec r
$$

So:

$$
W=(6,2)\cdot(16.5,1.5)
$$

$$
W=6\cdot 16.5+2\cdot 1.5
$$

$$
W=99+3=102\ \text{J}
$$

---

## 6. Check consistency with the work-energy theorem

Initial kinetic energy:

$$
T_0=\frac12 m |\vec v(0)|^2
$$

$$
|\vec v(0)|^2=1^2+(-1)^2=2
$$

$$
T_0=\frac12 \cdot 2 \cdot 2=2\ \text{J}
$$

Velocity at \(t=3\):

$$
\vec v(3)=(1+9,\,-1+3)=(10,2)
$$

So:

$$
|\vec v(3)|^2=10^2+2^2=104
$$

Final kinetic energy:

$$
T_3=\frac12 \cdot 2 \cdot 104=104\ \text{J}
$$

Thus:

$$
\Delta T=T_3-T_0=104-2=102\ \text{J}
$$

This is equal to the work:

$$
W=102\ \text{J}
$$

So the work-energy theorem is satisfied.

---

## Final results

Acceleration:

$$
\vec a(t)=(3,1)
$$

Velocity:

$$
\vec v(t)=(1+3t,\,-1+t)
$$

Position:

$$
\vec r(t)=\left(t+\frac32 t^2,\,-t+\frac12 t^2\right)
$$

Work up to \(t=3\):

$$
W=102\ \text{J}
$$

The work-energy theorem is consistent.
