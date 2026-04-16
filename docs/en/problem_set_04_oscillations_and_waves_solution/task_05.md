# Problem 5 – Superposition of waves, beats, and group velocity

Given two waves:

$$
y_1(x,t)=A\sin(kx-\omega t)
$$

$$
y_2(x,t)=A\sin(kx-(\omega+\Delta\omega)t)
$$

---

## 1. Resultant wave \(y=y_1+y_2\)

Using the identity

$$
\sin \alpha+\sin \beta=2\sin\left(\frac{\alpha+\beta}{2}\right)\cos\left(\frac{\alpha-\beta}{2}\right)
$$

let

$$
\alpha=kx-\omega t
$$

$$
\beta=kx-(\omega+\Delta\omega)t
$$

Then:

$$
y=y_1+y_2
=2A\sin\left(\frac{\alpha+\beta}{2}\right)\cos\left(\frac{\alpha-\beta}{2}\right)
$$

Now compute:

$$
\frac{\alpha+\beta}{2}
=
\frac{2kx-(2\omega+\Delta\omega)t}{2}
=
kx-\left(\omega+\frac{\Delta\omega}{2}\right)t
$$

and

$$
\frac{\alpha-\beta}{2}
=
\frac{\Delta\omega\, t}{2}
$$

Thus:

$$
y(x,t)=
2A\sin\left(kx-\left(\omega+\frac{\Delta\omega}{2}\right)t\right)
\cos\left(\frac{\Delta\omega\, t}{2}\right)
$$

This is the product form: carrier \(\times\) envelope.

---

## 2. Beat frequency and beat period at \(x=0\)

At a fixed position, the envelope is governed by

$$
\cos\left(\frac{\Delta\omega\, t}{2}\right)
$$

The beat angular frequency is:

$$
\omega_b=\Delta\omega
$$

So beat frequency is:

$$
f_b=\frac{\Delta\omega}{2\pi}
$$

and beat period is:

$$
T_b=\frac{1}{f_b}=\frac{2\pi}{\Delta\omega}
$$

---

## 3. Physical interpretation

- The **carrier wave** describes the fast oscillation.
- The **envelope** describes the slow modulation of amplitude.
- The beat phenomenon appears because two close frequencies interfere.

---

## 4. Group velocity

In general:

$$
v_g=\frac{\Delta\omega}{\Delta k}
$$

If the two waves have the same \(k\), then there is no spatial envelope motion, only temporal beating at a fixed point.

---

## Final results

Resultant wave:

$$
y(x,t)=
2A\sin\left(kx-\left(\omega+\frac{\Delta\omega}{2}\right)t\right)
\cos\left(\frac{\Delta\omega\, t}{2}\right)
$$

Beat frequency:

$$
f_b=\frac{\Delta\omega}{2\pi}
$$

Beat period:

$$
T_b=\frac{2\pi}{\Delta\omega}
$$
