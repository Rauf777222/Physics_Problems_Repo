# Problem 9 – Current through the ammeter

Assume the source polarities are taken as shown in the figure.

Given:

$$
\mathcal E_1=9V
$$

$$
\mathcal E_2=4.5V
$$

$$
r_w=1\Omega
$$

$$
R_1=10\Omega
$$

$$
R_2=20\Omega
$$

---

## 1. Choose two main nodes

The circuit can be treated as three branches between the same two main nodes:

1. top branch: source \(\mathcal E_2\) and internal resistance \(1\Omega\),
2. middle branch: resistor \(R_2=20\Omega\),
3. bottom-right branch: source \(\mathcal E_1\), internal resistance \(1\Omega\), and resistor \(R_1=10\Omega\).

Let the voltage of the right node relative to the left node be:

$$
V
$$

---

## 2. Kirchhoff current equation

Using branch currents and applying Kirchhoff's current law:

$$
\frac{-V-\mathcal E_2}{1}
+
\frac{-V}{20}
+
\frac{-V-\mathcal E_1}{11}
=0
$$

Substitute:

$$
\frac{-V-4.5}{1}
+
\frac{-V}{20}
+
\frac{-V-9}{11}
=0
$$

Solving gives:

$$
V=-\frac{1170}{251}
$$

$$
V\approx -4.66V
$$

---

## 3. Ammeter current

The ammeter is in the middle branch with \(R_2\).

Therefore:

$$
I_A=\frac{0-V}{20}
$$

$$
I_A=\frac{4.66}{20}
$$

$$
I_A\approx 0.233A
$$

---

## Final result

Current through the ammeter:

$$
I_A\approx 0.233A
$$
