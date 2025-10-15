### Solutions to be mixed:

1.  **Solution 'A' (Strong Acid):**
    * Substance: **$\text{HCl}$** (Hydrochloric acid)
    * Volume $(\mathbf{V}_{\text{A}})$: **$10\ \text{mL}$**
    * Concentration $(\mathbf{C}_{\text{A}})$: **$10^{-2}\ \text{M}$**

2.  **Solution 'B' (Weak Acid):**
    * Substance: **$\text{CH}_3\text{COOH}$** (Acetic acid)
    * Volume $(\mathbf{V}_{\text{B}})$: **$20\ \text{mL}$**
    * Concentration $(\mathbf{C}_{\text{B}})$: **$0.002\ \text{M}$**
    * Acid dissociation constant $(\mathbf{K}_{\text{a}})$: **$1.8 \times 10^{-5}$**

**Goal:** Find the $\text{pH}$ of the mixture.

---

## Solution Steps

The mixture contains a **strong acid** ($\text{HCl}$) and a **weak acid** ($\text{CH}_3\text{COOH}$). Since both contribute $\text{H}^{+}$ ions, the final $\text{pH}$ depends on the **total** concentration of $\text{H}^{+}$ ions ($[\text{H}^+]_{\text{Total}}$) from both sources.

### 1. Calculate the initial moles of each acid

First, we find the moles ($\text{n}$) of each acid before mixing. ($\text{n} = \text{C} \times \text{V}$ in Liters).

* **Moles of $\text{HCl}$ ($\text{n}_{\text{HCl}}$):**
    $$\text{n}_{\text{HCl}} = (10^{-2}\ \text{M}) \times \left(\frac{10}{1000}\ \text{L}\right) = 10^{-4}\ \text{moles}$$

* **Moles of $\text{CH}_3\text{COOH}$ ($\text{n}_{\text{CH}_3\text{COOH}}$):**
    $$\text{n}_{\text{CH}_3\text{COOH}} = (0.002\ \text{M}) \times \left(\frac{20}{1000}\ \text{L}\right) = 4 \times 10^{-5}\ \text{moles}$$

### 2. Calculate the total volume of the mixture

The total volume ($\mathbf{V}_{\text{Total}}$) is the sum of the volumes:
$$\mathbf{V}_{\text{Total}} = 10\ \text{mL} + 20\ \text{mL} = 30\ \text{mL} = 0.03\ \text{L}$$

### 3. Determine the total $\text{H}^{+}$ concentration

The total $\text{H}^{+}$ concentration is the sum of the $\text{H}^{+}$ contributions from the strong acid ($\text{HCl}$) and the weak acid ($\text{CH}_3\text{COOH}$) in the mixture.

$$\mathbf{[H^+]_{\text{Total}}} = \mathbf{[H^+]_{\text{HCl}}} + \mathbf{[H^+]_{\text{CH}_3\text{COOH}}}$$

#### a. $\text{H}^{+}$ from the Strong Acid ($\text{HCl}$)

$\text{HCl}$ completely dissociates. Its final concentration in the mixture is:
$$\mathbf{[H^+]_{\text{HCl}}} = [\text{HCl}]_{\text{final}} = \frac{\text{n}_{\text{HCl}}}{\mathbf{V}_{\text{Total}}} = \frac{10^{-4}\ \text{moles}}{0.03\ \text{L}} = \mathbf{3.333 \times 10^{-3}\ \text{M}}$$

#### b. $\text{H}^{+}$ from the Weak Acid ($\text{CH}_3\text{COOH}$)

$\text{CH}_3\text{COOH}$ dissociates according to its $K_{\text{a}}$:
$$\text{CH}_3\text{COOH} \rightleftharpoons \text{CH}_3\text{COO}^{-} + \text{H}^{+}$$
The dissociation is suppressed by the $\text{H}^{+}$ from the strong acid (common ion effect).

Let **$\mathbf{x}$** be the concentration of $\text{H}^{+}$ contributed by the $\text{CH}_3\text{COOH}$.
The initial concentration of $\text{CH}_3\text{COOH}$ in the mixture ($\mathbf{C}_{\text{WA}}$) is:
$$\mathbf{C}_{\text{WA}} = [\text{CH}_3\text{COOH}]_{\text{initial}} = \frac{\text{n}_{\text{CH}_3\text{COOH}}}{\mathbf{V}_{\text{Total}}} = \frac{4 \times 10^{-5}\ \text{moles}}{0.03\ \text{L}} = 1.333 \times 10^{-3}\ \text{M}$$

The concentrations at equilibrium are:
| Species | Initial (M) | Change (M) | Equilibrium (M) |
| :---: | :---: | :---: | :---: |
| $\text{CH}_3\text{COOH}$ | $\text{C}_{\text{WA}}$ | $-x$ | $\text{C}_{\text{WA}} - x$ |
| $\text{CH}_3\text{COO}^{-}$ | $0$ | $+x$ | $x$ |
| $\text{H}^{+}$ | $[\text{H}^+]_{\text{HCl}}$ | $+x$ | $[\text{H}^+]_{\text{HCl}} + x$ |

Applying the $K_{\text{a}}$ expression:
$$K_{\text{a}} = \frac{[\text{CH}_3\text{COO}^{-}][\text{H}^{+}]}{[\text{CH}_3\text{COOH}]}$$
$$1.8 \times 10^{-5} = \frac{(x) \times ([\text{H}^+]_{\text{HCl}} + x)}{(\text{C}_{\text{WA}} - x)}$$

Since the strong acid's concentration ($3.333 \times 10^{-3}\ \text{M}$) is much greater than $K_{\text{a}}$ and $C_{\text{WA}}$ is small, we can make the following approximations:
1.  $[\text{H}^+]_{\text{HCl}} + x \approx [\text{H}^+]_{\text{HCl}}$ (The $\text{H}^{+}$ from $\text{CH}_3\text{COOH}$ is negligible compared to $\text{H}^{+}$ from $\text{HCl}$)
2.  $\text{C}_{\text{WA}} - x \approx \text{C}_{\text{WA}}$ (The amount of $\text{CH}_3\text{COOH}$ that dissociates is negligible)

The equation simplifies to:
$$K_{\text{a}} \approx \frac{(x) \times [\text{H}^+]_{\text{HCl}}}{\text{C}_{\text{WA}}}$$
$$1.8 \times 10^{-5} \approx \frac{(x) \times (3.333 \times 10^{-3})}{1.333 \times 10^{-3}}$$
Solving for $\mathbf{x}$ (which is $\mathbf{[H^+]_{\text{CH}_3\text{COOH}}}$):
$$x = \frac{K_{\text{a}} \times \text{C}_{\text{WA}}}{[\text{H}^+]_{\text{HCl}}} = \frac{(1.8 \times 10^{-5}) \times (1.333 \times 10^{-3})}{3.333 \times 10^{-3}}$$
$$\mathbf{[H^+]_{\text{CH}_3\text{COOH}}} = x \approx 7.2 \times 10^{-6}\ \text{M}$$

#### c. Calculate $[\text{H}^+]_{\text{Total}}$

$$\mathbf{[H^+]_{\text{Total}}} = [\text{H}^+]_{\text{HCl}} + [\text{H}^+]_{\text{CH}_3\text{COOH}}$$
$$\mathbf{[H^+]_{\text{Total}}} = (3.333 \times 10^{-3}) + (7.2 \times 10^{-6})$$
$$\mathbf{[H^+]_{\text{Total}}} \approx 0.003333 + 0.0000072 = \mathbf{0.0033402\ \text{M}}$$

*Note: Since the contribution from the weak acid ($7.2 \times 10^{-6}\ \text{M}$) is very small compared to the strong acid ($3.333 \times 10^{-3}\ \text{M}$), the $\text{pH}$ will be very close to the $\text{pH}$ calculated from $\text{HCl}$ alone.*

### 4. Calculate the final $\text{pH}$

$$\text{pH} = -\log_{10} [\text{H}^+]_{\text{Total}}$$
$$\text{pH} = -\log_{10} (0.0033402)$$
$$\mathbf{\text{pH} \approx 2.476}$$

---

## Final Answer

The $\text{pH}$ of the mixture of the two solutions is approximately **$2.48$**.
