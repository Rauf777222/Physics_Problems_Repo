# Problem 4 – Motion of a particle in a uniform field

Given:

$$
m=0.02\,kg
$$

$$
q=1\,mC=10^{-3}C
$$

$$
\vec E=(30,100)\,N/C
$$

$$
\vec v(0)=(20,0)\,m/s
$$

$$
\vec r(0)=(0,0)
$$

---

## 1. Force and acceleration

Electric force:

$$
\vec F=q\vec E
$$

$$
\vec F=10^{-3}(30,100)
$$

$$
\vec F=(0.03,0.1)\,N
$$

Acceleration:

$$
\vec a=\frac{\vec F}{m}
$$

$$
\vec a=\frac{(0.03,0.1)}{0.02}
$$

$$
\vec a=(1.5,5)\,m/s^2
$$

---

## 2. Equations of motion

Velocity:

$$
\vec v(t)=\vec v(0)+\vec a t
$$

$$
\vec v(t)=(20,0)+(1.5,5)t
$$

$$
\vec v(t)=(20+1.5t,5t)
$$

Position:

$$
\vec r(t)=\vec r(0)+\vec v(0)t+\frac12\vec a t^2
$$

$$
\vec r(t)=(20t+0.75t^2,2.5t^2)
$$

---

## 3. Time to reach vertical velocity \(50\,m/s\)

Vertical velocity:

$$
v_y(t)=5t
$$

Set:

$$
5t=50
$$

$$
t=10\,s
$$

---

## 4. Kinetic energy after \(t=0.05\,s\)

Velocity at \(0.05\,s\):

$$
v_x=20+1.5(0.05)=20.075
$$

$$
v_y=5(0.05)=0.25
$$

Speed squared:

$$
v^2=20.075^2+0.25^2
$$

$$
v^2\approx 403.068
$$

Kinetic energy:

$$
K=\frac12mv^2
$$

$$
K=\frac12(0.02)(403.068)
$$

$$
K\approx 4.03\,J
$$

---

## 5. Energy balance

Work done by the electric field:

$$
W=q\vec E\cdot \Delta \vec r
$$

The change in kinetic energy should satisfy:

$$
\Delta K=W
$$

This confirms consistency with the work-energy theorem.

---

## Final results

Force:

$$
\vec F=(0.03,0.1)\,N
$$

Acceleration:

$$
\vec a=(1.5,5)\,m/s^2
$$

Velocity:

$$
\vec v(t)=(20+1.5t,5t)
$$

Position:

$$
\vec r(t)=(20t+0.75t^2,2.5t^2)
$$

Time for \(v_y=50\,m/s\):

$$
t=10\,s
$$

Kinetic energy at \(t=0.05s\):

$$
K\approx 4.03\,J
$$
