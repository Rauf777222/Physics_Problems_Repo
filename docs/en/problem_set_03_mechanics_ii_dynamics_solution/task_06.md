# Problem 6 – Motion with linear drag

The drag force is

$$
F=-kv
$$

Initial conditions:

$$
v(0)=v_0,\qquad x(0)=0
$$

---

## 1. Equation of motion

By Newton's second law:

$$
m\frac{dv}{dt}=F
$$

Thus:

$$
m\frac{dv}{dt}=-kv
$$

Divide by \(m\):

$$
\frac{dv}{dt}=-\frac{k}{m}v
$$

This is a first-order separable differential equation.

---

## 2. Solve for velocity \(v(t)\)

Separate variables:

$$
\frac{dv}{v}=-\frac{k}{m}\,dt
$$

Integrate both sides:

$$
\int \frac{1}{v}\,dv=\int -\frac{k}{m}\,dt
$$

$$
\ln|v|=-\frac{k}{m}t+C
$$

Exponentiate:

$$
v(t)=Ce^{-\frac{k}{m}t}
$$

Use the initial condition \(v(0)=v_0\):

$$
v_0=C
$$

So:

$$
v(t)=v_0e^{-\frac{k}{m}t}
$$

---

## 3. Position \(x(t)\)

Velocity is the derivative of position:

$$
\frac{dx}{dt}=v_0e^{-\frac{k}{m}t}
$$

Integrate:

$$
x(t)=\int_0^t v_0e^{-\frac{k}{m}\tau}\,d\tau
$$

$$
x(t)=v_0\int_0^t e^{-\frac{k}{m}\tau}\,d\tau
$$

The integral gives:

$$
x(t)=v_0\left[-\frac{m}{k}e^{-\frac{k}{m}\tau}\right]_0^t
$$

$$
x(t)=\frac{mv_0}{k}\left(1-e^{-\frac{k}{m}t}\right)
$$

---

## 4. Limit \( t\to\infty \)

For velocity:

$$
\lim_{t\to\infty} v(t)=\lim_{t\to\infty} v_0e^{-\frac{k}{m}t}=0
$$

So the body eventually stops.

For position:

$$
\lim_{t\to\infty} x(t)=\frac{mv_0}{k}
$$

So the body approaches a finite limiting distance.

---

## 5. Comparison with motion without drag

Without drag, the velocity remains constant:

$$
v(t)=v_0
$$

and position is:

$$
x(t)=v_0 t
$$

With drag:

- velocity decreases exponentially,
- the body eventually stops,
- the position approaches a finite limit.

Without drag:

- velocity stays constant,
- position grows linearly without bound.

---

## Final results

Equation of motion:

$$
m\frac{dv}{dt}=-kv
$$

Velocity:

$$
v(t)=v_0e^{-\frac{k}{m}t}
$$

Position:

$$
x(t)=\frac{mv_0}{k}\left(1-e^{-\frac{k}{m}t}\right)
$$

Limits:

$$
\lim_{t\to\infty}v(t)=0
$$

$$
\lim_{t\to\infty}x(t)=\frac{mv_0}{k}
$$
