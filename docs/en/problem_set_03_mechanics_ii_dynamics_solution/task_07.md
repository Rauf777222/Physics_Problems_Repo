# Problem 7 – Vertical throw with drag

Equation of motion:

$$
m\frac{dv}{dt}=-mg-kv
$$

Initial conditions:

$$
v(0)=v_0,\qquad x(0)=0
$$

---

## 1. Solve the equation

Divide by \(m\):

$$
\frac{dv}{dt}+\frac{k}{m}v=-g
$$

This is a linear first-order differential equation.

The standard solution is:

$$
v(t)=Ce^{-\frac{k}{m}t}-\frac{mg}{k}
$$

Apply the initial condition \(v(0)=v_0\):

$$
v_0=C-\frac{mg}{k}
$$

So:

$$
C=v_0+\frac{mg}{k}
$$

Thus:

$$
v(t)=\left(v_0+\frac{mg}{k}\right)e^{-\frac{k}{m}t}-\frac{mg}{k}
$$

---

## 2. Position \(x(t)\)

We integrate velocity:

$$
x(t)=\int_0^t v(\tau)\,d\tau
$$

Substitute \(v(\tau)\):

$$
x(t)=\int_0^t \left[\left(v_0+\frac{mg}{k}\right)e^{-\frac{k}{m}\tau}-\frac{mg}{k}\right]d\tau
$$

Integrating term by term:

$$
x(t)=\left(v_0+\frac{mg}{k}\right)\frac{m}{k}\left(1-e^{-\frac{k}{m}t}\right)-\frac{mg}{k}t
$$

So:

$$
x(t)=\frac{m}{k}\left(v_0+\frac{mg}{k}\right)\left(1-e^{-\frac{k}{m}t}\right)-\frac{mg}{k}t
$$

---

## 3. Maximum height

Maximum height is reached when velocity becomes zero:

$$
v(t)=0
$$

So:

$$
\left(v_0+\frac{mg}{k}\right)e^{-\frac{k}{m}t}-\frac{mg}{k}=0
$$

Hence:

$$
e^{-\frac{k}{m}t}=\frac{mg/k}{v_0+mg/k}
$$

Taking the logarithm:

$$
t_{\max}=\frac{m}{k}\ln\left(\frac{v_0+\frac{mg}{k}}{\frac{mg}{k}}\right)
$$

This can also be written as:

$$
t_{\max}=\frac{m}{k}\ln\left(1+\frac{k v_0}{mg}\right)
$$

The maximum height is obtained by substituting \(t_{\max}\) into \(x(t)\).

---

## 4. Comparison with motion without drag

Without drag:

$$
v(t)=v_0-gt
$$

$$
x(t)=v_0 t-\frac12 gt^2
$$

Maximum height without drag:

$$
H=\frac{v_0^2}{2g}
$$

With drag:

- velocity decreases faster,
- the maximum height is smaller,
- the upward motion lasts less time.

---

## 5. Analytical vs numerical solution

A numerical solution can be obtained by approximating:

$$
\frac{dv}{dt}\approx \frac{v_{n+1}-v_n}{\Delta t}
$$

and then computing position step by step.

The numerical results should approach the analytical formulas when \(\Delta t\) is small.

---

## Final results

Velocity:

$$
v(t)=\left(v_0+\frac{mg}{k}\right)e^{-\frac{k}{m}t}-\frac{mg}{k}
$$

Position:

$$
x(t)=\frac{m}{k}\left(v_0+\frac{mg}{k}\right)\left(1-e^{-\frac{k}{m}t}\right)-\frac{mg}{k}t
$$

Time to reach maximum height:

$$
t_{\max}=\frac{m}{k}\ln\left(1+\frac{k v_0}{mg}\right)
$$
