# Problem 3 – Work of a variable force

Given a one-dimensional force:

$$
F(x)=-kx
$$

---

## 1. Equation of motion

By Newton's second law:

$$
m\ddot x = F(x)
$$

Thus:

$$
m\ddot x=-kx
$$

or

$$
\ddot x+\frac{k}{m}x=0
$$

This is the equation of a harmonic oscillator.

---

## 2. General solution

Define:

$$
\omega=\sqrt{\frac{k}{m}}
$$

Then the equation becomes:

$$
\ddot x+\omega^2 x=0
$$

Its general solution is:

$$
x(t)=A\cos(\omega t)+B\sin(\omega t)
$$

where \(A\) and \(B\) are constants.

---

## 3. Work done during displacement from \(0\) to \(x_0\)

The work of a variable force is:

$$
W=\int_0^{x_0} F(x)\,dx
$$

Substitute \(F(x)=-kx\):

$$
W=\int_0^{x_0} (-kx)\,dx
$$

$$
W=-k\int_0^{x_0} x\,dx
$$

$$
W=-k\left[\frac{x^2}{2}\right]_0^{x_0}
$$

$$
W=-\frac12 kx_0^2
$$

---

## 4. Interpretation as potential energy

For a conservative force:

$$
F(x)=-\frac{dU}{dx}
$$

Given:

$$
F(x)=-kx
$$

we get:

$$
-\frac{dU}{dx}=-kx
$$

Thus:

$$
\frac{dU}{dx}=kx
$$

Integrate:

$$
U(x)=\int kx\,dx
$$

$$
U(x)=\frac12 kx^2 + C
$$

Choosing \(U(0)=0\), we set \(C=0\), so:

$$
U(x)=\frac12 kx^2
$$

This is the potential energy of a spring.

---

## 5. Verification of \( F=-\frac{dU}{dx} \)

Differentiate \(U(x)\):

$$
\frac{dU}{dx}=kx
$$

Therefore:

$$
-\frac{dU}{dx}=-kx
$$

which is exactly the given force.

---

## 6. Graphs of \(F(x)\) and \(U(x)\)

- \(F(x)=-kx\) is a straight line through the origin with negative slope.
- \(U(x)=\frac12 kx^2\) is a parabola opening upward.

---

## Final results

Equation of motion:

$$
m\ddot x=-kx
$$

General solution:

$$
x(t)=A\cos(\omega t)+B\sin(\omega t),\qquad \omega=\sqrt{\frac{k}{m}}
$$

Work from \(0\) to \(x_0\):

$$
W=-\frac12 kx_0^2
$$

Potential energy:

$$
U(x)=\frac12 kx^2
$$
