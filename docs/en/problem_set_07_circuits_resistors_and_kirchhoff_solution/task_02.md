# Problem 2 – Equivalent resistance

All resistors have resistance:

$$
R=3\Omega
$$

There is one resistor in series at the input, and the remaining network is a bridge-like circuit.

---

## 1. Equivalent resistance of the inner network

To simplify the bridge, we use nodal analysis.

Let the voltage between the two main bottom nodes be:

$$
V=1V
$$

After solving the node equations for the bridge network, the total current is:

$$
I=\frac{5}{11}A
$$

Therefore the equivalent resistance of the inner network is:

$$
R_{\text{inner}}=\frac{V}{I}
$$

$$
R_{\text{inner}}=\frac{1}{5/11}
$$

$$
R_{\text{inner}}=\frac{11}{5}\Omega
$$

$$
R_{\text{inner}}=2.2\Omega
$$

---

## 2. Add the input series resistor

The input resistor is in series with the bridge network:

$$
R_{\text{eq}}=3+\frac{11}{5}
$$

$$
R_{\text{eq}}=\frac{15}{5}+\frac{11}{5}
$$

$$
R_{\text{eq}}=\frac{26}{5}\Omega
$$

---

## Final result

$$
R_{\text{eq}}=\frac{26}{5}\Omega=5.2\Omega
$$
