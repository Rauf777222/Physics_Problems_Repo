# Problem 1 – Equivalent resistance

All resistors have resistance:

$$
R=5\Omega
$$

---

## 1. Top branch

The top branch has two resistors in series:

$$
R_{\text{top}}=5+5=10\Omega
$$

---

## 2. Bottom branch

The bottom branch first has one resistor:

$$
5\Omega
$$

Then there are two resistors in parallel:

$$
R_p=\frac{5\cdot 5}{5+5}=\frac{25}{10}=2.5\Omega
$$

So the bottom branch is:

$$
R_{\text{bottom}}=5+2.5=7.5\Omega
$$

---

## 3. Parallel connection of top and bottom branches

$$
R_{ab}=\frac{R_{\text{top}}R_{\text{bottom}}}{R_{\text{top}}+R_{\text{bottom}}}
$$

$$
R_{ab}=\frac{10\cdot 7.5}{10+7.5}
$$

$$
R_{ab}=\frac{75}{17.5}=\frac{30}{7}\Omega
$$

---

## 4. Final series resistor

There is one more resistor in series at the output:

$$
R_{\text{eq}}=R_{ab}+5
$$

$$
R_{\text{eq}}=\frac{30}{7}+5
$$

$$
R_{\text{eq}}=\frac{65}{7}\Omega
$$

---

## Final result

$$
R_{\text{eq}}=\frac{65}{7}\Omega\approx 9.29\Omega
$$
