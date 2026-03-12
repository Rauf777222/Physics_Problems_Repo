# Problem 8 – First-order differential equation

We solve the differential equation

$$
\frac{dy}{dt}=-ky
$$

and discuss how to visualize the solution in an HTML/JS application for different values of \(k\) and different initial conditions \(y(0)\).

---

# 1. Solving the equation

We start with

$$
\frac{dy}{dt}=-ky
$$

This is a first-order separable differential equation.

We separate variables:

$$
\frac{dy}{y}=-k\,dt
$$

Now integrate both sides:

$$
\int \frac{1}{y}\,dy=\int -k\,dt
$$

This gives

$$
\ln|y|=-kt+C
$$

where \(C\) is the integration constant.

Exponentiate both sides:

$$
|y|=e^{-kt+C}
$$

We can write \(e^C=C_1\), where \(C_1>0\), so the general solution becomes

$$
y(t)=Ce^{-kt}
$$

where \(C\) is an arbitrary constant.

---

# 2. Solution for a given initial condition \( y(0)=y_0 \)

Let

$$
y(0)=y_0
$$

Substitute \(t=0\) into the general solution:

$$
y(0)=Ce^{-k\cdot 0}=C
$$

So

$$
C=y_0
$$

Therefore the solution satisfying the initial condition is

$$
y(t)=y_0 e^{-kt}
$$

---

# 3. Interpretation of the solution

The function

$$
y(t)=y_0 e^{-kt}
$$

describes exponential behavior.

## Case 1: \(k>0\)

If \(k>0\), then the solution decreases exponentially as \(t\) increases.

So the function represents **exponential decay**.

## Case 2: \(k=0\)

If \(k=0\), then

$$
y(t)=y_0
$$

So the solution is constant.

## Case 3: \(k<0\)

If \(k<0\), then \(-kt\) becomes positive, so the solution grows exponentially.

So the function represents **exponential growth**.

---

# 4. Check that the solution is correct

Take the derivative of

$$
y(t)=y_0 e^{-kt}
$$

Then

$$
\frac{dy}{dt}=y_0(-k)e^{-kt}
$$

$$
\frac{dy}{dt}=-k y_0 e^{-kt}
$$

Since

$$
y(t)=y_0 e^{-kt}
$$

we get

$$
\frac{dy}{dt}=-k y
$$

So the solution satisfies the differential equation.

---

# 5. HTML/JS visualization idea

In an HTML/JS application, we can visualize the solution

$$
y(t)=y_0 e^{-kt}
$$

for different values of:

- the parameter \(k\),
- the initial condition \(y_0\).

The application can include:

1. a slider or input for \(k\),
2. a slider or input for \(y_0\),
3. a plot of \(y(t)\) versus \(t\),
4. comparison of multiple curves for different values,
5. labels showing whether the solution decays, stays constant, or grows.

---

# 6. What changes when parameters change?

## Changing \(k\)

- larger positive \(k\) → faster decay,
- \(k=0\) → constant solution,
- negative \(k\) → exponential growth.

## Changing \(y_0\)

- \(y_0\) changes the initial value of the solution,
- if \(y_0>0\), the graph starts above the axis,
- if \(y_0<0\), the graph starts below the axis,
- if \(y_0=0\), then the solution is identically zero.

---

# Final results

Differential equation:

$$
\frac{dy}{dt}=-ky
$$

General solution:

$$
y(t)=Ce^{-kt}
$$

Solution with initial condition \(y(0)=y_0\):

$$
y(t)=y_0 e^{-kt}
$$
