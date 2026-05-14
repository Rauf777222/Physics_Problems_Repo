# Problem 8 – Self-induction

RL circuit data:

$$
L=0.20\,H
$$

$$
R=5.0\,\Omega
$$

$$
U=12\,V
$$

---

## 1. Steady current before disconnecting

In steady state, the inductor acts like a short circuit.

So the current is:

$$
I_0=\frac{U}{R}
$$

Substitute:

$$
I_0=\frac{12}{5}
$$

$$
I_0=2.4\,A
$$

---

## 2. Current after disconnection

After the power supply is disconnected, current decays exponentially:

$$
I(t)=I_0e^{-t/\tau}
$$

where the time constant is:

$$
\tau=\frac{L}{R}
$$

Substitute:

$$
\tau=\frac{0.20}{5.0}
$$

$$
\tau=0.04\,s
$$

Therefore:

$$
I(t)=2.4e^{-t/0.04}
$$

---

## 3. Voltage across the coil

For an inductor:

$$
U_L(t)=-L\frac{dI}{dt}
$$

Since:

$$
I(t)=I_0e^{-t/\tau}
$$

we have:

$$
\frac{dI}{dt}=-\frac{I_0}{\tau}e^{-t/\tau}
$$

Thus:

$$
U_L(t)=L\frac{I_0}{\tau}e^{-t/\tau}
$$

Using \(\tau=L/R\):

$$
U_L(t)=RI_0e^{-t/\tau}
$$

At \(t=0\):

$$
U_L(0)=RI_0=5\cdot 2.4=12\,V
$$

---

## 4. Energy stored in the coil before disconnection

Energy stored in magnetic field:

$$
W=\frac12LI_0^2
$$

Substitute:

$$
W=\frac12(0.20)(2.4)^2
$$

$$
W=0.1\cdot 5.76
$$

$$
W=0.576\,J
$$

---

## 5. Energy converted into Joule heat

Thermal energy in resistor:

$$
Q=\int_0^\infty I^2R\,dt
$$

With

$$
I(t)=I_0e^{-t/\tau}
$$

this gives:

$$
Q=\frac12LI_0^2
$$

So all the magnetic energy stored in the inductor is converted into Joule heat:

$$
Q=0.576\,J
$$

---

## 6. Why overvoltage can appear?

An inductor resists sudden changes in current.

When the circuit is disconnected, the inductor tries to keep the current flowing.

This can create a large voltage spike, called overvoltage.

---

## Final results

Initial current:

$$
I_0=2.4\,A
$$

Time constant:

$$
\tau=0.04\,s
$$

Current decay:

$$
I(t)=2.4e^{-t/0.04}
$$

Stored energy:

$$
W=0.576\,J
$$

Thermal energy:

$$
Q=0.576\,J
