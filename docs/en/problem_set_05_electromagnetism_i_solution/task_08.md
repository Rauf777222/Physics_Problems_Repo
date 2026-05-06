# Problem 8 – Energy of a three-charge system

A system of three charges is considered.

---

## 1. Total potential energy of the system

The potential energy of two point charges is:

$$
U_{ij}=k\frac{q_iq_j}{r_{ij}}
$$

where \(r_{ij}\) is the distance between charges \(q_i\) and \(q_j\).

For three charges, the total energy is the sum over all pairs:

$$
U_{\text{total}}
=
k\left(
\frac{q_1q_2}{r_{12}}
+
\frac{q_1q_3}{r_{13}}
+
\frac{q_2q_3}{r_{23}}
\right)
$$

---

## 2. Equilateral triangle configuration

If the charges form an equilateral triangle with side length \(a\), then:

$$
r_{12}=r_{13}=r_{23}=a
$$

So:

$$
U_{\text{total}}
=
\frac{k}{a}
\left(
q_1q_2+q_1q_3+q_2q_3
\right)
$$

If the charges are equal, \(q_1=q_2=q_3=q\), then:

$$
U_{\text{total}}
=
\frac{k}{a}(q^2+q^2+q^2)
$$

$$
U_{\text{total}}=
\frac{3kq^2}{a}
$$

---

## 3. Energy change when one charge is moved

If one charge is moved, then the distances involving that charge change.

For example, if \(q_3\) is moved, then \(r_{13}\) and \(r_{23}\) change.

The energy change is:

$$
\Delta U=U_{\text{final}}-U_{\text{initial}}
$$

---

## 4. Minimum energy configuration

To find the minimum energy configuration numerically:

1. choose initial positions of charges,
2. calculate total potential energy,
3. move charges slightly,
4. recalculate energy,
5. search for the configuration with the smallest energy.

---

## 5. Stability interpretation

A stable configuration corresponds to a local minimum of potential energy.

If a small displacement increases the energy, the system tends to return.

If a small displacement decreases the energy, the configuration is unstable.

---

## Final results

Total energy:

$$
U_{\text{total}}
=
k\left(
\frac{q_1q_2}{r_{12}}
+
\frac{q_1q_3}{r_{13}}
+
\frac{q_2q_3}{r_{23}}
\right)
$$

Equilateral triangle:

$$
U_{\text{total}}
=
\frac{k}{a}
\left(
q_1q_2+q_1q_3+q_2q_3
\right)
$$

For equal charges:

$$
U_{\text{total}}=
\frac{3kq^2}{a}
$$
