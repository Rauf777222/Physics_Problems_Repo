# Problem 6 – Rod on metal rails in a magnetic field

Given:

$$
m=0.20\,kg
$$

$$
L=0.30\,m
$$

$$
B=0.80\,T
$$

$$
R=0.50\,\Omega
$$

$$
\alpha=25^\circ
$$

$$
g=9.81\,m/s^2
$$

---

## 1. Motional EMF and current

A rod moving with velocity \(v\) in a magnetic field produces motional EMF:

$$
\mathcal E=B L v
$$

The current is:

$$
i=\frac{\mathcal E}{R}
$$

So:

$$
i=\frac{BLv}{R}
$$

---

## 2. Magnetic braking force

The magnetic force on a current-carrying rod is:

$$
F_B=iLB
$$

Substitute current:

$$
F_B=\frac{BLv}{R}LB
$$

$$
F_B=\frac{B^2L^2}{R}v
$$

This force acts opposite to the motion.

---

## 3. Equation of motion along the incline

The gravitational component along the incline is:

$$
mg\sin\alpha
$$

The magnetic force opposes the motion, so:

$$
m\frac{dv}{dt}=mg\sin\alpha-\frac{B^2L^2}{R}v
$$

Divide by \(m\):

$$
\frac{dv}{dt}=g\sin\alpha-\frac{B^2L^2}{mR}v
$$

This is a first-order equation with damping proportional to velocity.

---

## 4. Terminal velocity

Terminal velocity occurs when:

$$
\frac{dv}{dt}=0
$$

So:

$$
mg\sin\alpha=\frac{B^2L^2}{R}v_T
$$

Therefore:

$$
v_T=\frac{mgR\sin\alpha}{B^2L^2}
$$

Substitute values:

$$
v_T=
\frac{0.20\cdot 9.81\cdot 0.50\cdot \sin 25^\circ}
{(0.80)^2(0.30)^2}
$$

$$
v_T\approx 7.20\,m/s
$$

---

## 5. Power balance in steady state

Mechanical power from gravity:

$$
P_g=mg\sin\alpha\cdot v
$$

Electrical power dissipated as heat:

$$
P_R=i^2R
$$

Since

$$
i=\frac{BLv}{R}
$$

then

$$
P_R=\left(\frac{BLv}{R}\right)^2R
$$

$$
P_R=\frac{B^2L^2}{R}v^2
$$

In steady state:

$$
mg\sin\alpha=\frac{B^2L^2}{R}v
$$

Multiplying by \(v\):

$$
mg\sin\alpha\cdot v=\frac{B^2L^2}{R}v^2
$$

Thus:

$$
mg\sin\alpha\cdot v=i^2R
$$

This means gravitational energy is converted into Joule heat.

---

## Final results

Motional EMF:

$$
\mathcal E=BLv
$$

Current:

$$
i=\frac{BLv}{R}
$$

Equation of motion:

$$
m\frac{dv}{dt}=mg\sin\alpha-\frac{B^2L^2}{R}v
$$

Terminal velocity:

$$
v_T=\frac{mgR\sin\alpha}{B^2L^2}
$$

For the given values:

$$
v_T\approx 7.20\,m/s
$$
