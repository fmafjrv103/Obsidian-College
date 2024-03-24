---
date: 2024-03-21 10:55:45
tags:
  - newNotes
  - inProgress
  - math
---
Links: [[Math MOC]]

---
# Getting Started
$\LaTeX$ – A TEX-Based typesetting system suitable for producing scientific, mathematical, and physical documents of high print quality.
- [LaTeX official website](latex-project.org)
- [KaTeX official website](katex.org)
And KaTeX handles only a smaller subset of LaTeX’s mathematical notation for display on the web.
# Example
$$
f(x)=\int_{-\infty}^{\infty}f\hat\xi\,e^{s\pi i \xi x}\,d\xi
$$
```latex
f(x)=\int_{-\infty}^{\infty}f\hat\xi\,e^{s\pi i \xi x}\,d\xi
```
# Inline
Based on KaTeX in one line 
Example: `KaTeX:\int_0^\infty x^2 dx`

Example based on KaTeX showing in one line: $\int_0^\infty x^2 dx$ 
# Supported Functions
## Accents
| $a'$`a'`                     | $\tilde{a}$`\tilde{a}`                               |
| ---------------------------- | ---------------------------------------------------- |
| $a''$`a''`                   | $\widetilde{ac}$`\widetilde{ac}`                     |
| $a^{\prime}$`a^{\prime}`     | $\mathring{g}$`\mathring{g}`                         |
| $\acute{a}$`\acute{a}`       | $\vec{F}$`\vec{F}`                                   |
| $\bar{y}$​`\bar{y}`          | $\overleftarrow{AB}$`\overleftarrow{AB}`             |
| $\breve{a}$`\breve{a}`       | $\underleftarrow{AB}$`\underleftarrow{AB}`           |
| $\check{a}$`\check{a}`       | $\overrightarrow{AB}$`\overrightarrow{AB}`           |
| $\dot{a}$`\dot{a}`           | $\underrightarrow{AB}$`\underrightarrow{AB}`         |
| $\ddot{a}$`\ddot{a}`         | $\overleftrightarrow{AB}$`\overleftrightarrow{AB}`   |
| $\grave{a}$`\grave{a}`       | $\underleftrightarrow{AB}$`\underleftrightarrow{AB}` |
| $\hat{\theta}$`\hat{\theta}` | $\overline{AB}$`\overline{AB}`                       |
| $\widehat{ac}$`\widehat{ac}` | $\underline{AB}$`\underline{AB}`                     |

## Delimiter Sizing
| $\left(\LARGE{AB}\right)$     | `\left(\LARGE{AB}\right)`     |
| ----------------------------- | ----------------------------- |
| $( \big( \Big( \bigg( \Bigg($ | `( \big( \Big( \bigg( \Bigg(` |


| `\left`   | `\big`  | `\bigl`  | `\bigm`  | `\bigr`  |
| --------- | ------- | -------- | -------- | -------- |
| `\middle` | `\Big`  | `\Bigl`  | `\Bigm`  | `\Bigr`  |
| `\right`  | `\bigg` | `\biggl` | `\biggm` | `\biggr` |
| `\`       | `\Bigg` | `\Biggl` | `\Biggm` | `\Biggr` |
## Greek and Hebrew Letters
|  $\alpha$  | `\alpha`   | $\kappa$   | `\kappa`   | $\psi$     | `\psi`     | $\digamma$    | `\digamma`    |
|:----------:| ---------- | ---------- | ---------- | ---------- | ---------- | ------------- | ------------- |
|  $\beta$   | `\beta`    | $\lambda$  | `\lambda`  | $\rho$     | `\rho`     | $\varepsilon$ | `\varepsilon` |
|   $\chi$   | `\chi`     | $\mu$      | `\mu`      | $\sigma$   | `\sigma`   | $\varkappa$   | `\varkappa`   |
|  $\delta$  | `\delta`   | $\nu$      | `\nu`      | $\tau$     | `\tau`     | $\varphi$     | `\varphi`     |
| $\epsilon$ | `\epsilon` | $o$        | `o`        | $\theta$   | `\theta`   | $\varpi$      | `\varpi`      |
|   $\eta$   | `\eta`     | $\omega$   | `\omega`   | $\upsilon$ | `\upsilon` | $\varrho$     | `\varrho`     |
|  $\gamma$  | `\gamma`   | $\phi$     | `\phi`     | $\xi$      | `\xi`      | $\varsigma$   | `\varsigma`   |
|  $\iota$   | `\iota`    | $\pi$      | `\pi`      | $\zeta$    | `\zeta`    | $\vartheta$   | `\vartheta`   |
|  $\Delta$  | `\Delta`   | $\Theta$   | `\Theta`   | $\Phi$     | `\Phi`     | $\aleph$      | `\aleph`      |
|  $\Gamma$  | `\Gamma`   | $\Upsilon$ | `\Upsilon` | $\Pi$      | `\Pi`      | $\beth$       | `\beth`       |
| $\lambda$  | `\Lambda`  | $\Xi$      | `\Xi`      | $\Psi$     | `\Psi`     | $\daleth$     | `\daleth`     |
|  $\Omega$  | `\Omega`   | $\gimel$   | `\gimel`   | $\Sigma$   | `\Sigma`   |               |               |

### Other letters

| $\imath$   | `\imath`   | $\Im$     | `\Im`     |
| ---------- | ---------- | --------- | --------- |
| $\jmath$   | `\jmath`   | $\wp$     | `\wp`     |
| $\aleph$   | `\aleph`   | $\Bbbk$   | `\Bbbk`   |
| $\nabla$   | `\nabla`   | $\Finv$   | `\Finv`   |
| $\partial$ | `\partial` | $\Re$     | `\Re`     |
| $\beth$    | `\beth`    | $\ell$    | `\ell`    |
| $\gimel$   | `\gimel`   | $\hbar$   | `\hbar`   |
| $\Game$    | `\Game`    | $\hslash$ | `\hslash` |
| $\eth$     | `\eth`     |           |           |
## Annotation
|                         |                         |                                    |                                    |
| ----------------------- | ----------------------- | ---------------------------------- | ---------------------------------- |
| $\cancel{5}$​           | `\cancel{5}`            | $\overbrace{a+b+c}^{\text{note}}$  | `\overbrace{a+b+c}^{\text{note}}`  |
| $\bcancel{5}$           | `\bcancel{5}`           | $\underbrace{a+b+c}^{\text{note}}$ | `\underbrace{a+b+c}_{\text{note}}` |
| $\xcancel{ABC}$         | `\xcancel{ABC}`         | $\not=$                            | `\not =`                           |
| $\boxed{\pi=\frac c d}$ | `\boxed{\pi=\frac c d}` |                                    |                                    |
`\tag{hi} x+y^{2x}`
$\tag{hi} x+y^{2x}$
`\tag*{hi} x+y^{2x}`
$\tag*{hi} x+y^{2x}$
# Vertical Layout
|                                  |                                  |                   |                   |
| -------------------------------- | -------------------------------- | ----------------- | ----------------- |
| $x_n$​                           | `x_n`                            | $a\atop b$        | `a \atop b`       |
| $e^x$                            | `e^x`                            | $\overset{!}{=}$  | `\overset{!}{=}`  |
| $_u^o$                           | `_u^o`                           | $\underset{!}{=}$ | `\underset{!}{=}` |
| $\sum_{\substack{0<i<m\\0<j<n}}$ | `\sum_{\substack{0<i<m\\0<j<n}}` |                   |                   |
# Overlap and Spacing
|                                     |                              |                            |
| ----------------------------------- | ---------------------------- | -------------------------- |
| ${=}\mathllap{/,}$ {=}\mathllap{/,} | $\left(x^{\smash{2}}\right)$ | \left(x^{\smash{2}}\right) |
| $\mathllap{,/}{=}$ \mathrlap{,/}{=} | $\sqrt{\smash[b]{y}}$        | \sqrt{\smash[b]{y}}        |
`\sum_{\mathclap{1\le i\le j\le n}} x_{ij}`
$\sum_{\mathclap{1\le i\le j\le n}} x_{ij}$
# LaTeX Math Constructs
|                    |                   |                   |                   |                        |                        |
| ------------------ | ----------------- | ----------------- | ----------------- | ---------------------- | ---------------------- |
| $\frac{abc}{xyz}$​ | `\frac{abc}{xyz}` | $\overline{abc}$  | `\overline{abc}`  | $\overrightarrow{abc}$ | `\overrightarrow{abc}` |
| $f'$               | `f'`              | $\underline{abc}$ | `\underline{abc}` | $\overleftarrow{abc}$  | `\overleftarrow{abc}`  |
| $\sqrt{abc}$       | `\sqrt{abc}`      | $\widehat{abc}$   | `\widehat{abc}`   | $\overbrace{abc}$      | `\overbrace{abc}`      |
| $\sqrt[n]{abc}$    | `\sqrt[n]{abc}`   | $\widetilde{abc}$ | `\widetilde{abc}` | $\underbrace{abc}$     | `\underbrace{abc}`     |
# Delimiter
| preview                | method                      | preview            | method              |
| ---------------------- | --------------------------- | ------------------ | ------------------- |
| $( )$                  | `()`                        | $\lparen{}\rparen$ | `\lparen` `\rparen` |
| $[ ]$                  | `[]`                        | $\lbrack{}\rbrack$ | `\lbrack` `\rbrack` |
| $\{ \}$                | `{}`                        | $\lbrace{}\rbrace$ | `\lbrace` `\rbrace` |
| $⟨⟩$                   | `⟨⟩`                        | $\langle{}\rangle$ | `\langle` `\rangle` |
| $'\\$                  | `\\                         | $∣∣$               | ∣∣                  |
| $\lvert{}\rvert$       | `\lvert` `\rvert`           | $∥∥$               | ∥∥                  |
| $< >$                  | `\lang` `\rang`             | $\lVert{}\rVert$   | `\lVert` `\rVert`   |
| ⌈⌉⌈⌉                   | `\lceil` `\rceil`           | $\lt{} \gt$        | `\lt \gt`           |
| ⌊⌋⌊⌋                   | `\lfloor` `\rfloor`         | $\uparrow$         | `\uparrow`          |
| ⎰⎱⎰⎱                   | `\lmoustache` `\rmoustache` | $\downarrow$       | `\downarrow`        |
| ⟮⟯⟮⟯                   | `\lgroup` `\rgroup`         | $\updownarrow$     | `\updownarrow`      |
| $\ulcorner{}\urcorner$ | `\ulcorner` `\urcorner`     | $\Updownarrow$     | `\Updownarrow`      |
| $\llcorner{}\lrcorner$ | `\llcorner` `\lrcorner`     | $\backslash$       | `\backslash`        |
| $\Uparrow$             | `\Uparrow`                  | $⌈ ⌉$              | `⌈ ⌉`               |
| $\Downarrow$           | `\Downarrow`                | $⌊ ⌋$              | `⌊ ⌋`               |
| $⎰⎱$                   | `⎰⎱`                        | $┌┐$               | ┌┐┌┐                |
| $⟮ ⟯$                  | `⟮ ⟯`                       | $└┘$               | └┘└┘                |
| $⟦ ⟧$                  | `⟦ ⟧`                       |                    |                     |

---
