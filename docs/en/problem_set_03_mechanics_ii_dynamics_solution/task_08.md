# Problem 8 – Harmonic oscillator (formal dynamics)

Equation of motion:

$$
m\ddot x+kx=0
$$

---

## 1. Solve the equation

Divide by \(m\):

$$
\ddot x+\frac{k}{m}x=0
$$

Define:

$$
\omega=\sqrt{\frac{k}{m}}
$$

Then:

$$
\ddot x+\omega^2 x=0
$$

The general solution is:

$$
x(t)=A\cos(\omega t)+B\sin(\omega t)
$$

where \(A\) and \(B\) are constants.

---

## 2. Natural frequency

The natural angular frequency is:

$$
\omega=\sqrt{\frac{k}{m}}
$$

The ordinary frequency is:

$$
f=\frac{\omega}{2\pi}=\frac{1}{2\pi}\sqrt{\frac{k}{m}}
$$

---

## 3. Energy as a function of time

The kinetic energy is:

$$
T=\frac12 m\dot x^2
$$

The potential energy is:

$$
U=\frac12 kx^2
$$

So the total energy is:

$$
E=\frac12 m\dot x^2+\frac12 kx^2
$$

---

## 4. Show that energy is conserved

Differentiate total energy:

$$
\frac{dE}{dt}=m\dot x\ddot x+kx\dot x
$$

Factor out \(\dot x\):

$$
\frac{dE}{dt}=\dot x(m\ddot x+kx)
$$

But from the equation of motion:

$$
m\ddot x+kx=0
$$

So:

$$
\frac{dE}{dt}=0
$$

Thus the total energy is constant.

---

## 5. Interpretation in phase space

Phase space is the plane \((x,\dot x)\).

For harmonic motion:

- the motion is periodic,
- the trajectory in phase space is a closed curve,
- energy conservation means the motion stays on the same curve.

In suitable scaled variables, the phase trajectory is an ellipse.

---

## Final results

Equation:

$$
m\ddot x+kx=0
$$

General solution:

$$
x(t)=A\cos(\omega t)+B\sin(\omega t)
$$

Natural frequency:

$$
\omega=\sqrt{\frac{k}{m}}
$$

Total energy:

$$
E=\frac12 m\dot x^2+\frac12 kx^2
$$

Energy is conserved.
