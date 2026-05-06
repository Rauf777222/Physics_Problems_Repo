# Problem 3 – Field at a point from a system of charges

Two charges are given:

- \(+q\) at \((-a,0)\)
- \(+2q\) at \((a,0)\)

The electric field of a point charge is:

$$
\vec E=kq\frac{\vec r-\vec r_q}{|\vec r-\vec r_q|^3}
$$

---

## 1. Field at a general point \((x,y)\)

For charge \(+q\) at \((-a,0)\):

$$
\vec r-\vec r_1=(x+a,y)
$$

$$
\vec E_1=kq\frac{(x+a,y)}{\left((x+a)^2+y^2\right)^{3/2}}
$$

For charge \(+2q\) at \((a,0)\):

$$
\vec r-\vec r_2=(x-a,y)
$$

$$
\vec E_2=k(2q)\frac{(x-a,y)}{\left((x-a)^2+y^2\right)^{3/2}}
$$

Total field:

$$
\vec E(x,y)=\vec E_1+\vec E_2
$$

So:

$$
\vec E(x,y)=
kq\frac{(x+a,y)}{\left((x+a)^2+y^2\right)^{3/2}}
+
2kq\frac{(x-a,y)}{\left((x-a)^2+y^2\right)^{3/2}}
$$

---

## 2. Field at the origin \((0,0)\)

At \((0,0)\):

From \(+q\) at \((-a,0)\):

$$
\vec E_1=kq\frac{(a,0)}{a^3}
$$

$$
\vec E_1=\left(\frac{kq}{a^2},0\right)
$$

From \(+2q\) at \((a,0)\):

$$
\vec E_2=2kq\frac{(-a,0)}{a^3}
$$

$$
\vec E_2=\left(-\frac{2kq}{a^2},0\right)
$$

Total:

$$
\vec E(0,0)=\left(-\frac{kq}{a^2},0\right)
$$

---

## 3. Field on the \(x\)-axis

For \(y=0\), the field has only \(x\)-component.

Between the charges, fields have opposite directions.

A zero field point may exist between the charges, closer to the smaller charge \(+q\).

---

## 4. Numerical calculation

Given:

$$
a=0.2\,m,\qquad y=0.3\,m,\qquad q=2\,\mu C
$$

The field can be calculated by substituting these values into:

$$
\vec E(x,y)=
kq\frac{(x+a,y)}{\left((x+a)^2+y^2\right)^{3/2}}
+
2kq\frac{(x-a,y)}{\left((x-a)^2+y^2\right)^{3/2}}
$$

---

## 5. Limit \(y\gg a\)

If \(y\gg a\), the two charges look almost like one total charge:

$$
q_{\text{total}}=q+2q=3q
$$

So far away:

$$
E\approx k\frac{3q}{y^2}
$$

---

## 6. Zero field on the \(y\)-axis?

On the \(y\)-axis, \(x=0\).

The \(x\)-components do not cancel because the charges are not equal.

Therefore, a zero field point does not generally exist on the \(y\)-axis.

---

## Final results

General field:

$$
\vec E(x,y)=
kq\frac{(x+a,y)}{\left((x+a)^2+y^2\right)^{3/2}}
+
2kq\frac{(x-a,y)}{\left((x-a)^2+y^2\right)^{3/2}}
$$

At the origin:

$$
\vec E(0,0)=\left(-\frac{kq}{a^2},0\right)
$$

For \(y\gg a\):

$$
E\approx k\frac{3q}{y^2}
$$
