# Problem 3 – Equivalent resistance

All resistors have resistance:

$$
R=10\Omega
$$

---

## 1. Identify the lower direct branch

There is one direct bottom resistor between the terminals:

$$
R_{\text{bottom}}=10\Omega
$$

---

## 2. Upper part of the circuit

From the left terminal to the top node, there are two possible paths.

First path:

$$
10+10=20\Omega
$$

Second path:

$$
10+10+10=30\Omega
$$

These two paths are in parallel:

$$
R_L=\frac{20\cdot 30}{20+30}
$$

$$
R_L=\frac{600}{50}=12\Omega
$$

---

## 3. Right side of the circuit

From the top node to the right terminal, there are two resistors in series:

$$
R_R=10+10=20\Omega
$$

So the upper network becomes:

$$
R_{\text{upper}}=R_L+R_R
$$

$$
R_{\text{upper}}=12+20=32\Omega
$$

---

## 4. Final parallel connection

The upper network is in parallel with the bottom resistor:

$$
R_{\text{eq}}=\frac{10\cdot 32}{10+32}
$$

$$
R_{\text{eq}}=\frac{320}{42}
$$

$$
R_{\text{eq}}=\frac{160}{21}\Omega
$$

---

## Final result

$$
R_{\text{eq}}=\frac{160}{21}\Omega\approx 7.62\Omega
$$
