# Problem 7 – Loop pulled into a magnetic field region

A rectangular conducting loop with resistance \(R\) has dimensions \(a\times b\).  
It is pulled with constant velocity \(v\) into a region of uniform magnetic field \(B\).

Given example data:

$$
a=0.20\,m
$$

$$
b=0.10\,m
$$

$$
B=0.60\,T
$$

$$
R=0.40\,\Omega
$$

$$
v=1.5\,m/s
$$

---

## 1. Magnetic flux during entering phase

During the entering phase, only part of the loop is inside the field.

If the inserted length is:

$$
x(t)=vt
$$

then the area inside the field is:

$$
A(t)=b x(t)=bvt
$$

The magnetic flux is:

$$
\Phi(t)=B A(t)
$$

Thus:

$$
\Phi(t)=Bbvt
$$

---

## 2. Induced EMF

By Faraday's law:

$$
\mathcal E=-\frac{d\Phi}{dt}
$$

Since:

$$
\Phi(t)=Bbvt
$$

then:

$$
\frac{d\Phi}{dt}=Bbv
$$

So:

$$
|\mathcal E|=Bbv
$$

Substitute:

$$
|\mathcal E|=0.60\cdot 0.10\cdot 1.5
$$

$$
|\mathcal E|=0.09\,V
$$

---

## 3. Induced current

Ohm's law:

$$
I=\frac{\mathcal E}{R}
$$

$$
I=\frac{0.09}{0.40}
$$

$$
I=0.225\,A
$$

---

## 4. Braking force

The magnetic braking force is:

$$
F=IBb
$$

Substitute:

$$
F=0.225\cdot 0.60\cdot 0.10
$$

$$
F=0.0135\,N
$$

The force acts opposite to the motion.

---

## 5. Power balance

Mechanical power required:

$$
P_{\text{mech}}=Fv
$$

$$
P_{\text{mech}}=0.0135\cdot 1.5
$$

$$
P_{\text{mech}}=0.02025\,W
$$

Thermal power:

$$
P_R=I^2R
$$

$$
P_R=(0.225)^2\cdot 0.40
$$

$$
P_R=0.02025\,W
$$

Thus:

$$
P_{\text{mech}}=P_R
$$

Mechanical work is converted into heat.

---

## 6. What happens when the loop is entirely in the uniform field?

When the whole loop is inside the uniform magnetic field, the flux is constant:

$$
\frac{d\Phi}{dt}=0
$$

So:

$$
\mathcal E=0
$$

Therefore:

$$
I=0
$$

There is no induced current.

---

## Final results

Flux:

$$
\Phi(t)=Bbvt
$$

Induced EMF:

$$
|\mathcal E|=Bbv=0.09\,V
$$

Current:

$$
I=0.225\,A
$$

Braking force:

$$
F=0.0135\,N
$$

Power balance:

$$
P_{\text{mech}}=P_R=0.02025\,W
$$
