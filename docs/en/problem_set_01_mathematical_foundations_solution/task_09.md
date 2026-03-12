# Problem 9 – Harmonic oscillator

We solve the differential equation

$$
\frac{d^2x}{dt^2}+\omega^2 x=0
$$

find the general solution, express the solution for given initial conditions, and describe how to visualize \(x(t)\), \(\dot x(t)\), and \(\ddot x(t)\) in an HTML/JS application.

---

# 1. General solution

We start with the equation

$$
\frac{d^2x}{dt^2}+\omega^2 x=0
$$

This is a linear second-order differential equation with constant coefficients.

We use the trial solution

$$
x(t)=e^{rt}
$$

Then

$$
\dot x(t)=re^{rt}, \qquad \ddot x(t)=r^2 e^{rt}
$$

Substitute into the differential equation:

$$
r^2 e^{rt}+\omega^2 e^{rt}=0
$$

Factor out \(e^{rt}\neq 0\):

$$
r^2+\omega^2=0
$$

So the characteristic equation is

$$
r^2+\omega^2=0
$$

Its roots are

$$
r=\pm i\omega
$$

Therefore the general real solution is

$$
x(t)=A\cos(\omega t)+B\sin(\omega t)
$$

where \(A\) and \(B\) are constants.

---

# 2. Velocity and acceleration

Differentiate the general solution.

Velocity:

$$
\dot x(t)=\frac{dx}{dt}
$$

$$
\dot x(t)=-A\omega \sin(\omega t)+B\omega \cos(\omega t)
$$

Acceleration:

$$
\ddot x(t)=\frac{d^2x}{dt^2}
$$

$$
\ddot x(t)=-A\omega^2 \cos(\omega t)-B\omega^2 \sin(\omega t)
$$

We can factor this as

$$
\ddot x(t)=-\omega^2\big(A\cos(\omega t)+B\sin(\omega t)\big)
$$

Since

$$
x(t)=A\cos(\omega t)+B\sin(\omega t)
$$

we obtain

$$
\ddot x(t)=-\omega^2 x(t)
$$

which confirms the equation.

---

# 3. Solution for given initial conditions

Let the initial conditions be

$$
x(0)=x_0, \qquad \dot x(0)=v_0
$$

We use them to determine \(A\) and \(B\).

---

## Step 1: Use \(x(0)=x_0\)

From

$$
x(t)=A\cos(\omega t)+B\sin(\omega t)
$$

set \(t=0\):

$$
x(0)=A\cos 0 + B\sin 0
$$

$$
x(0)=A
$$

So

$$
A=x_0
$$

---

## Step 2: Use \(\dot x(0)=v_0\)

Velocity is

$$
\dot x(t)=-A\omega \sin(\omega t)+B\omega \cos(\omega t)
$$

Set \(t=0\):

$$
\dot x(0)=-A\omega \sin 0 + B\omega \cos 0
$$

$$
\dot x(0)=B\omega
$$

So

$$
B=\frac{v_0}{\omega}
$$

---

## Final solution with initial conditions

Substitute \(A=x_0\) and \(B=\frac{v_0}{\omega}\):

$$
x(t)=x_0\cos(\omega t)+\frac{v_0}{\omega}\sin(\omega t)
$$

Velocity:

$$
\dot x(t)=-x_0\omega \sin(\omega t)+v_0\cos(\omega t)
$$

Acceleration:

$$
\ddot x(t)=-\omega^2 x(t)
$$

or explicitly

$$
\ddot x(t)=
-\omega^2 x_0\cos(\omega t)-\omega v_0\sin(\omega t)
$$

---

# 4. Amplitude-phase form

The general solution can also be written as

$$
x(t)=C\cos(\omega t-\phi)
$$

where

$$
C=\sqrt{A^2+B^2}
$$

and the phase \(\phi\) is chosen so that

$$
A=C\cos\phi, \qquad B=C\sin\phi
$$

This form shows that the motion is periodic with angular frequency \(\omega\).

---

# 5. Period of oscillation

Since the solution contains \(\cos(\omega t)\) and \(\sin(\omega t)\), the period is

$$
T=\frac{2\pi}{\omega}
$$

So larger \(\omega\) means faster oscillation and smaller period.

---

# 6. Physical interpretation

The equation

$$
\ddot x+\omega^2 x=0
$$

describes simple harmonic motion.

The acceleration is proportional to displacement and points in the opposite direction:

$$
\ddot x=-\omega^2 x
$$

This means:

- when \(x>0\), acceleration is negative,
- when \(x<0\), acceleration is positive,
- the system is always pulled back toward equilibrium.

That is why the motion oscillates.

---

# 7. HTML/JS visualization idea

The application can visualize:

1. the displacement
   $$
   x(t)
   $$

2. the velocity
   $$
   \dot x(t)
   $$

3. the acceleration
   $$
   \ddot x(t)
   $$

for selected values of:

- \( \omega \),
- \( x_0 \),
- \( v_0 \).

The application can include:

- sliders for \( \omega \), \(x_0\), and \(v_0\),
- a graph of \(x(t)\),
- a graph of \(\dot x(t)\),
- a graph of \(\ddot x(t)\),
- an animation of a mass-spring system.

A good visualization should clearly show that:

- \(x(t)\) is sinusoidal,
- velocity is phase-shifted relative to displacement,
- acceleration is opposite to displacement.

---

# Final results

Differential equation:

$$
\ddot x+\omega^2 x=0
$$

General solution:

$$
x(t)=A\cos(\omega t)+B\sin(\omega t)
$$

Velocity:

$$
\dot x(t)=-A\omega \sin(\omega t)+B\omega \cos(\omega t)
$$

Acceleration:

$$
\ddot x(t)=-A\omega^2 \cos(\omega t)-B\omega^2 \sin(\omega t)
$$

With initial conditions \(x(0)=x_0\), \(\dot x(0)=v_0\):

$$
x(t)=x_0\cos(\omega t)+\frac{v_0}{\omega}\sin(\omega t)
$$

$$
\dot x(t)=-x_0\omega \sin(\omega t)+v_0\cos(\omega t)
$$

$$
\ddot x(t)=-\omega^2 x(t)
$$

Period:

$$
T=\frac{2\pi}{\omega}
$$
