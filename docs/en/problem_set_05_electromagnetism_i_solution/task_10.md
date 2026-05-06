# Problem 10 – Field flux (verification of Gauss's law)

---

## 1. Electric flux

Electric flux through a surface is defined as:

$$
\Phi_E=\int \vec E\cdot d\vec A
$$

For a closed surface:

$$
\Phi_E=\oint \vec E\cdot d\vec A
$$

---

## 2. Sphere around a point charge

For a point charge \(q\), the electric field is radial:

$$
E(r)=k\frac{q}{r^2}
$$

On a sphere of radius \(r\), the field magnitude is constant and parallel to \(d\vec A\).

Thus:

$$
\Phi_E=E\cdot 4\pi r^2
$$

Substitute:

$$
\Phi_E=k\frac{q}{r^2}\cdot 4\pi r^2
$$

$$
\Phi_E=4\pi kq
$$

Since

$$
k=\frac{1}{4\pi\varepsilon_0}
$$

we get:

$$
\Phi_E=\frac{q}{\varepsilon_0}
$$

This is Gauss's law.

---

## 3. Discrete approximation of flux

To approximate flux numerically:

1. divide the sphere into small surface elements,
2. calculate \(\vec E\) at each element,
3. calculate \(\vec E\cdot \Delta \vec A\),
4. sum over all elements.

So:

$$
\Phi_E\approx \sum_i \vec E_i\cdot \Delta \vec A_i
$$

---

## 4. Dependence on number of grid points

If the number of grid points increases:

- the approximation becomes more accurate,
- the numerical result approaches \(q/\varepsilon_0\).

If the number of grid points is small:

- the error is larger.

---

## 5. Comparison with analytical result

The analytical result is:

$$
\Phi_E=\frac{q}{\varepsilon_0}
$$

The numerical result should converge to this value when the discretization becomes finer.

---

## Final results

Electric flux:

$$
\Phi_E=\oint \vec E\cdot d\vec A
$$

Gauss's law:

$$
\Phi_E=\frac{q}{\varepsilon_0}
$$

Discrete approximation:

$$
\Phi_E\approx \sum_i \vec E_i\cdot \Delta \vec A_i
$$
