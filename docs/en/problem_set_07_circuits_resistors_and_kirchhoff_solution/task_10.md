# Problem 10 – Current through the ammeter

Assume the source polarities are taken as shown in the figure.

Given:

$$
\mathcal E_1=4.5V
$$

$$
\mathcal E_2=9V
$$

$$
r_w=1\Omega
$$

$$
R_1=20\Omega
$$

$$
R_2=10\Omega
$$

---

## 1. Define the main nodes

Let the voltage between the upper and lower central nodes be:

$$
V
$$

There are three branches between these nodes:

1. branch with \(R_2=10\Omega\),
2. branch with \(\mathcal E_2=9V\) and internal resistance \(1\Omega\),
3. outer branch with \(R_1=20\Omega\), \(\mathcal E_1=4.5V\), and internal resistance \(1\Omega\).

---

## 2. Kirchhoff current equation

Using Kirchhoff's current law:

$$
\frac{V}{10}
+
\frac{V-9}{1}
+
\frac{V-4.5}{21}
=0
$$

Solving gives:

$$
V=\frac{1935}{241}
$$

$$
V\approx 8.03V
$$

---

## 3. Ammeter current

The ammeter is in the outer branch.

So:

$$
I_A=\frac{V-4.5}{21}
$$

Substitute:

$$
I_A=\frac{8.03-4.5}{21}
$$

$$
I_A\approx 0.168A
$$

---

## Final result

Current through the ammeter:

$$
I_A\approx 0.168A
$$
