# Problem 6 – Equivalent resistance and currents

The circuit contains resistors:

$$
R_1=r
$$

$$
R_2=2r
$$

$$
R_3=r
$$

$$
R_4=r
$$

$$
R_5=6r
$$

Let the voltage between points \(A\) and \(B\) be:

$$
U
$$

---

## 1. Use nodal analysis

Let the potentials of points \(C\) and \(D\) be \(V_C\) and \(V_D\).

Solving Kirchhoff's current equations for nodes \(C\) and \(D\), we get:

$$
V_C=\frac{28}{43}U
$$

$$
V_D=\frac{22}{43}U
$$

---

## 2. Currents through resistors

Current through resistor 1:

$$
I_1=\frac{U-V_C}{r}
$$

$$
I_1=\frac{15U}{43r}
$$

Current through resistor 2:

$$
I_2=\frac{V_C}{2r}
$$

$$
I_2=\frac{14U}{43r}
$$

Current through resistor 3:

$$
I_3=\frac{U-V_D}{r}
$$

$$
I_3=\frac{21U}{43r}
$$

Current through resistor 4:

$$
I_4=\frac{V_D}{r}
$$

$$
I_4=\frac{22U}{43r}
$$

Current through resistor 5:

$$
I_5=\frac{V_C-V_D}{6r}
$$

$$
I_5=\frac{U}{43r}
$$

The current through \(R_5\) flows from \(C\) to \(D\).

---

## 3. Total current

The total current entering from \(A\) is:

$$
I=I_1+I_3
$$

$$
I=\frac{15U}{43r}+\frac{21U}{43r}
$$

$$
I=\frac{36U}{43r}
$$

---

## 4. Equivalent resistance

$$
R_{\text{eq}}=\frac{U}{I}
$$

$$
R_{\text{eq}}=\frac{U}{36U/(43r)}
$$

$$
R_{\text{eq}}=\frac{43r}{36}
$$

---

## Final results

Equivalent resistance:

$$
R_{\text{eq}}=\frac{43r}{36}
$$

Currents:

$$
I_1=\frac{15U}{43r}
$$

$$
I_2=\frac{14U}{43r}
$$

$$
I_3=\frac{21U}{43r}
$$

$$
I_4=\frac{22U}{43r}
$$

$$
I_5=\frac{U}{43r}
$$
