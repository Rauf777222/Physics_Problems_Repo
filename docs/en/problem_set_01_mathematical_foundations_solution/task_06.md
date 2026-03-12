# Problem 6 – Curve length and numerical integration

A parametric trajectory in 2D is given by:

$$
x(t)=t, \qquad y(t)=t^2, \qquad t\in[0,1]
$$

We determine the velocity, its magnitude, the arc length, and the trapezoidal numerical approximation.

---

# 1. Velocity vector

The position vector is

$$
\vec r(t)=(x(t),y(t))=(t,t^2)
$$

The velocity vector is the derivative of the position vector:

$$
\vec v(t)=\frac{d\vec r(t)}{dt}
$$

Differentiate each component:

$$
\vec v(t)=\left(\frac{d}{dt}t,\frac{d}{dt}t^2\right)
$$

$$
\vec v(t)=(1,2t)
$$

---

# 2. Magnitude of velocity

The magnitude of the velocity vector is

$$
|\vec v(t)|=\sqrt{1^2+(2t)^2}
$$

$$
|\vec v(t)|=\sqrt{1+4t^2}
$$

---

# 3. Arc length as an integral

The arc length of a parametric curve is

$$
s=\int_0^1 |\vec v(t)|\,dt
$$

Substitute the magnitude:

$$
s=\int_0^1 \sqrt{1+4t^2}\,dt
$$

---

# 4. Analytical calculation of the integral

We compute

$$
I=\int_0^1 \sqrt{1+4t^2}\,dt
$$

Let

$$
u=2t \qquad \Rightarrow \qquad du=2\,dt \qquad \Rightarrow \qquad dt=\frac{du}{2}
$$

When \(t=0\), then \(u=0\).  
When \(t=1\), then \(u=2\).

So the integral becomes:

$$
I=\frac12\int_0^2 \sqrt{1+u^2}\,du
$$

We use the standard formula:

$$
\int \sqrt{1+u^2}\,du
=
\frac12\left(u\sqrt{1+u^2}+\ln\left|u+\sqrt{1+u^2}\right|\right)+C
$$

Therefore

$$
I=
\frac12\cdot
\frac12\left(u\sqrt{1+u^2}+\ln\left|u+\sqrt{1+u^2}\right|\right)\Bigg|_0^2
$$

$$
I=
\frac14\left(u\sqrt{1+u^2}+\ln\left|u+\sqrt{1+u^2}\right|\right)\Bigg|_0^2
$$

Evaluate at the bounds:

$$
I=
\frac14\left(2\sqrt5+\ln(2+\sqrt5)-0\right)
$$

So the exact arc length is

$$
s=\frac{1}{2}\sqrt5+\frac14\ln(2+\sqrt5)
$$

Approximate value:

$$
\sqrt5\approx 2.2361
$$

$$
\ln(2+\sqrt5)\approx \ln(4.2361)\approx 1.4436
$$

$$
s\approx \frac12(2.2361)+\frac14(1.4436)
$$

$$
s\approx 1.1180+0.3609
$$

$$
s\approx 1.4789
$$

---

# 5. Trapezoidal rule in HTML/JS

We approximate

$$
s=\int_0^1 \sqrt{1+4t^2}\,dt
$$

using the trapezoidal rule.

Let

$$
f(t)=\sqrt{1+4t^2}
$$

Divide the interval \([0,1]\) into \(N\) equal parts:

$$
h=\frac{1-0}{N}=\frac{1}{N}
$$

The nodes are:

$$
t_i=\frac{i}{N}, \qquad i=0,1,2,\dots,N
$$

Then the trapezoidal approximation is

$$
T_N=\frac{h}{2}\left[f(t_0)+2\sum_{i=1}^{N-1}f(t_i)+f(t_N)\right]
$$

So in our case:

$$
T_N=\frac{1}{2N}\left[f(0)+2\sum_{i=1}^{N-1}f\left(\frac{i}{N}\right)+f(1)\right]
$$

where

$$
f(t)=\sqrt{1+4t^2}
$$

As \(N\) increases, the numerical result converges to the exact value

$$
s\approx 1.4789
$$

---

# 6. Error analysis

The numerical error can be defined as

$$
\text{Error}(N)=|T_N-s|
$$

where:

- \(T_N\) is the trapezoidal approximation,
- \(s\) is the exact analytical value.

As \(N\) grows, the error decreases.

---

# 7. What should the HTML/JS application do?

The application should:

1. draw the trajectory
   $$
   x=t,\quad y=t^2,\quad t\in[0,1]
   $$

2. allow changing the number of trapezoids \(N\),

3. compute the numerical arc length \(T_N\),

4. compare it with the exact value

$$
s=\frac{1}{2}\sqrt5+\frac14\ln(2+\sqrt5)
$$

5. plot the error as a function of \(N\).

---

# Final results

Position vector:

$$
\vec r(t)=(t,t^2)
$$

Velocity vector:

$$
\vec v(t)=(1,2t)
$$

Velocity magnitude:

$$
|\vec v(t)|=\sqrt{1+4t^2}
$$

Arc length integral:

$$
s=\int_0^1 \sqrt{1+4t^2}\,dt
$$

Exact arc length:

$$
s=\frac{1}{2}\sqrt5+\frac14\ln(2+\sqrt5)
$$

Approximate value:

$$
s\approx 1.4789
$$

Trapezoidal approximation:

$$
T_N=\frac{h}{2}\left[f(t_0)+2\sum_{i=1}^{N-1}f(t_i)+f(t_N)\right]
$$

with

$$
h=\frac1N, \qquad f(t)=\sqrt{1+4t^2}
$$
