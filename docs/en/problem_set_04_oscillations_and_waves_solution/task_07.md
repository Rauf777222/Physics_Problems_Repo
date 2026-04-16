# Problem 7 – Forced oscillator and resonance

Equation:

$$
m\frac{d^2x}{dt^2}+b\frac{dx}{dt}+kx=F_0\cos(\Omega t)
$$

---

## 1. Analytical steady-state solution

We seek a steady-state solution of the form:

$$
x_s(t)=A(\Omega)\cos(\Omega t-\delta)
$$

The amplitude is:

$$
A(\Omega)=
\frac{F_0}{\sqrt{(k-m\Omega^2)^2+(b\Omega)^2}}
$$

The phase shift is:

$$
\tan\delta=\frac{b\Omega}{k-m\Omega^2}
$$

---

## 2. Resonance

The oscillation amplitude becomes large when the driving frequency \(\Omega\) is close to the natural frequency.

For weak damping, resonance occurs near:

$$
\Omega_0\approx \sqrt{\frac{k}{m}}
$$

---

## 3. Numerical solution

Introduce

$$
v=\dot x
$$

Then:

$$
\dot x=v
$$

$$
\dot v=\frac{1}{m}\big(F_0\cos(\Omega t)-bv-kx\big)
$$

This system can be solved numerically.

---

## 4. Resonance curve

The resonance curve is the graph of

$$
A(\Omega)
$$

as a function of the forcing frequency \(\Omega\).

It shows a peak near resonance.

---

## Final results

Steady-state amplitude:

$$
A(\Omega)=
\frac{F_0}{\sqrt{(k-m\Omega^2)^2+(b\Omega)^2}}
$$

Phase shift:

$$
\tan\delta=\frac{b\Omega}{k-m\Omega^2}
$$

Resonance occurs near:

$$
\Omega_0\approx \sqrt{\frac{k}{m}}
$$
