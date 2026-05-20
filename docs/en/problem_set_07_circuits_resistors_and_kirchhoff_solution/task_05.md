# Problem 5 – Equivalent resistance and ammeter current

The circuit contains resistors:

$$
5\Omega,\quad 10\Omega,\quad 10\Omega,\quad 10\Omega
$$

The voltage source is denoted by:

$$
U
$$

---

## 1. Simplify the middle-bottom part

The two \(10\Omega\) resistors connected from the middle node to the right side are in parallel:

$$
R_p=\frac{10\cdot 10}{10+10}
$$

$$
R_p=5\Omega
$$

This parallel part is in series with the \(5\Omega\) resistor:

$$
R_{\text{middle}}=5+5=10\Omega
$$

---

## 2. Parallel with the top branch

The top branch is:

$$
R_{\text{top}}=10\Omega
$$

So the total circuit is:

$$
10\Omega \parallel 10\Omega
$$

Therefore:

$$
R_{\text{eq}}=\frac{10\cdot 10}{10+10}
$$

$$
R_{\text{eq}}=5\Omega
$$

---

## 3. Total current

Using Ohm's law:

$$
I_{\text{total}}=\frac{U}{R_{\text{eq}}}
$$

$$
I_{\text{total}}=\frac{U}{5}
$$

---

## 4. Ammeter current

The ammeter measures the current flowing through the right vertical branch.

The current through the top \(10\Omega\) branch is:

$$
I_{\text{top}}=\frac{U}{10}
$$

The current through the middle branch is:

$$
I_{\text{middle}}=\frac{U}{10}
$$

After the \(5\Omega\) resistor, this current splits equally between two equal \(10\Omega\) resistors.

So the part flowing through the upper right branch is:

$$
\frac{1}{2}I_{\text{middle}}=\frac{U}{20}
$$

Thus the ammeter current is:

$$
I_A=I_{\text{top}}+\frac{U}{20}
$$

$$
I_A=\frac{U}{10}+\frac{U}{20}
$$

$$
I_A=\frac{3U}{20}
$$

---

## Final results

Equivalent resistance:

$$
R_{\text{eq}}=5\Omega
$$

Total current:

$$
I_{\text{total}}=\frac{U}{5}
$$

Ammeter current:

$$
I_A=\frac{3U}{20}
$$
