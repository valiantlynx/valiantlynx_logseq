#### R Pruim
#### October 19, 2016
## Math inside RMarkdown

In side a text chunk, you can use mathematical notation if you surround it by dollar signs `$` for “inline mathematics” and `$$` for “displayed equations”. **Do not leave a space between the `$` and your mathematical notation**.

Example: `$\sum_{n=1}^{10} n^2$` is rendered as ∑10n=1n2∑�=110�2.

Example: `$$\sum_{n=1}^{10} n^2$$` is rendered as

∑n=110n2∑�=110�2

.

The mathematical typesetting is based on LaTeX, so if you need to search for the way to make a particular symbol, include `latex` in your search. But note: Not all LaTeX macros are available without using additional packages, and those packages likely will only work if you are creating a PDF. On the plus side, if you are working in PDF, you can use additional packages that give much better control and/or easier syntax.

In LaTeX,
- macros begin with a backslash (`\`)
- curly braces (`{` and `}`) are used to surround items that are to be considered as one object from LaTeX’s perspective.
  Without them, usually the next letter or digit will be used, but that isn’t usually what you want. For example `$$\sum_x=1^10 x^2$$` produces
  
  ∑x=110x2∑�=110�2
### Mathematical Notation

Here are some common mathematical things you might use in statistics

| x=y�=� | `$x = y $` |
| x<y�<� | `$x < y $` |
| x>y�>� | `$x > y $` |
| x≤y�≤� | `$x \le y $` |
| x≥y�≥� | `$x \ge y $` |
| xn�� | `$x^{n}$` |
| xn�� | `$x_{n}$` |
| x¯¯¯�¯ | `$\overline{x}$` |
| x^�^ | `$\hat{x}$` |
| x~�~ | `$\tilde{x}$` |
| ab�� | `$\frac{a}{b}$` |
| ∂f∂x∂�∂� | `$\frac{\partial f}{\partial x}$` |
| ∂f∂x∂�∂� | `$\displaystyle \frac{\partial f}{\partial x}$` |
| (nk)(��) | `$\binom{n}{k}$` |
| x1+x2+⋯+xn�1+�2+⋯+�� | `$x_{1} + x_{2} + \cdots + x_{n}$` |
| x1,x2,…,xn�1,�2,…,�� | `$x_{1}, x_{2}, \dots, x_{n}$` |
| x=⟨x1,x2,…,xn⟩�=⟨�1,�2,…,��⟩ | `\mathbf{x} = \langle x_{1}, x_{2}, \dots, x_{n}\rangle$` (`\bm` from the `bm` pacakge would be better) |
| x∈A�∈� | `$x \in A$` |
| |A||�| | `$|A|$` |
| x∈A�∈� | `$x \in A$` |
| A⊂B�⊂� | `$x \subset B$` |
| A⊆B�⊆� | `$x \subseteq B$` |
| A∪B�∪� | `$A \cup B$` |
| A∩B�∩� | `$A \cap B$` |
| X∼Binom(n,π)�∼�����(�,�) | `$X \sim {\sf Binom}(n, \pi)$` (`sf` for “slide font”) |
| P(X≤x)=pbinom(x,n,π)P(�≤�)=������(�,�,�) | `$\mathrm{P}(X \le x) = {\tt pbinom}(x, n, \pi)$` (`tt` for “typewriter type”) |
| P(A∣B)�(�∣�) | `$P(A \mid B)$` |
| P(A∣B)P(�∣�) | `$\mathrm{P}(A \mid B)$` (`mathrm` for “math roman font” |
| {1,2,3}{1,2,3} | `$\{1, 2, 3\}$` |
| sin(x)sin⁡(�) | `$\sin(x)$` |
| log(x)log⁡(�) | `$\log(x)$` |
| ∫ba∫�� | `$\int_{a}^{b}$` |
| (∫baf(x)dx)(∫���(�)��) | `$\left(\int_{a}^{b} f(x) \; dx\right)$` |
| [∫∞−∞f(x)dx][∫−∞∞�(�)��] | `$\left[\int_{\-infty}^{\infty} f(x) \; dx\right]$` |
| F(x)|ba�(�)|�� | `$\left. F(x) \right|_{a}^{b}$` |
| ∑bx=af(x)∑�=���(�) | `$\sum_{x = a}^{b} f(x)$` |
| ∏bx=af(x)∏�=���(�) | `$\prod_{x = a}^{b} f(x)$` |
| limx→∞f(x)lim�→∞�(�) | `$\lim_{x \to \infty} f(x)$` |
| limx→∞f(x)lim�→∞�(�) | `$\displaystyle \lim_{x \to \infty} f(x)$` |
### Greek Letters

| αA�� | `$\alpha A$` | νN�� | `$\nu N$` |
| βB�� | `$\beta B$` | ξΞ�Ξ | `$\xi\Xi$` |
| γΓ�Γ | `$\gamma \Gamma$` | oO�� | `$o O$` (omicron) |
| δΔ�Δ | `$\delta \Delta$` | πΠ�Π | `$\pi \Pi$` |
| ϵεE��� | `$\epsilon \varepsilon E$` | ρϱP��� | `$\rho\varrho P$` |
| ζZ�� | `$\zeta Z \sigma \,\!$` | ΣΣ | `$\sigma \Sigma$` |
| ηH�� | `$\eta H$` | τT�� | `$\tau T$` |
| θϑΘ��Θ | `$\theta \vartheta \Theta$` | υΥ�Υ | `$\upsilon \Upsilon$` |
| ιI�� | `$\iota I$` | ϕφΦ��Φ | `$\phi \varphi \Phi$` |
| κK�� | `$\kappa K$` | χX�� | `$\chi X$` |
| λΛ�Λ | `$\lambda \Lambda$` | ψΨ�Ψ | `$\psi \Psi$` |
| μM�� | `$\mu M$` | ωΩ�Ω | `$\omega \Omega$` |
### Aligning equations

If you want a sequence of aligned equations (often very useful for demonstrating algebraic manipulation or for plugging values into equations), use `\begin{align*} ... \end{align*}`. Separate lines with `\\` and use `&` to mark where things should line up. Note: No dollar signs are needed when you use this method.
#### Example

This

```
\begin{align*}
a & = b \\
X &\sim {\sf Norm}(10, 3) \\
5 & \le 10
\end{align*}
```

produces

aX5=b∼Norm(10,3)≤10