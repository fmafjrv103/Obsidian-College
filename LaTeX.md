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
| $a'$`a'`                     | $\tilde{a}$`\tilde{a}`                               | $\mathring{g}$`\mathring{g}`                   |
| ---------------------------- | ---------------------------------------------------- | ---------------------------------------------- |
| $a''$`a''`                   | $\widetilde{ac}$`\widetilde{ac}`                     | $\overgroup{AB}$`\overgroup{AB}`               |
| $a^{\prime}$`a^{\prime}`     | $\utilde{AB}$`\utilde{AB}`                           | $\undergroup{AB}$`\undergroup{AB}`             |
| $\acute{a}$`\acute{a}`       | $\vec{F}$`\vec{F}`                                   | $\Overrightarrow{AB}$`\Overrightarrow{AB}`     |
| $\bar{y}$​`\bar{y}`          | $\overleftarrow{AB}$`\overleftarrow{AB}`             | $\overrightarrow{AB}$`\overrightarrow{AB}`     |
| $\breve{a}$`\breve{a}`       | $\underleftarrow{AB}$`\underleftarrow{AB}`           | $\underrightarrow{AB}$`\underrightarrow{AB}`   |
| $\check{a}$`\check{a}`       | $\overleftharpoon{ac}$`\overleftharpoon{ac}`         | $\overrightharpoon{ac}$`\overrightharpoon{ac}` |
| $\dot{a}$`\dot{a}`           | $\overleftrightarrow{AB}$`\overleftrightarrow{AB}`   | $\overbrace{AB}$`\overbrace{AB}`               |
| $\ddot{a}$`\ddot{a}`         | $\underleftrightarrow{AB}$`\underleftrightarrow{AB}` | $\underbrace{AB}$`\underbrace{AB}`             |
| $\grave{a}$`\grave{a}`       | $\overline{AB}$`\overline{AB}`                       | $\overlinesegment{AB}$`\overlinesegment{AB}`   |
| $\hat{\theta}$`\hat{\theta}` | $\underline{AB}$`\underline{AB}`                     | $\underlinesegment{AB}$`\underlinesegment{AB}` |
| $\widehat{ac}$`\widehat{ac}` | $\widecheck{ac}$`\widecheck{ac}`                     | $\underbar{X}$`\underbar{X}`                   |
## Emphasis in \\text
| $\'{a}$`\'{a}`   | $\~{a}$`\~{a}` |
| ---------------- | -------------- |
| $\.{a}$`\.{a}`   | $\H{a}$`\H{a}` |
| $\`{a}$``\`{a}`` | $\={a}$`\={a}` |
| $\"{a}$`\"{a}`   | $\v{a}$`\v{a}` |
| $\^{a}$`\^{a}`   | $\u{a}$`\u{a}` |
| $\r{a}$`\r{a}`   |                |
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
| `\alpha`   | $\kappa$  | `\kappa`  | $\psi$     | `\psi`     | $\digamma$    | `\digamma`    | $\Delta$  | `\Delta`  | $\Theta$   | `\Theta`   |
| ---------- | --------- | --------- | ---------- | ---------- | ------------- | ------------- | --------- | --------- | ---------- | ---------- |
| `\beta`    | $\lambda$ | `\lambda` | $\rho$     | `\rho`     | $\varepsilon$ | `\varepsilon` | $\Gamma$  | `\Gamma`  | $\Upsilon$ | `\Upsilon` |
| `\chi`     | $\mu$     | `\mu`     | $\sigma$   | `\sigma`   | $\varkappa$   | `\varkappa`   | $\lambda$ | `\Lambda` | $\Xi$      | `\Xi`      |
| `\delta`   | $\nu$     | `\nu`     | $\tau$     | `\tau`     | $\varphi$     | `\varphi`     | $\Omega$  | `\Omega`  |            |            |
| `\epsilon` | $o$       | `o`       | $\theta$   | `\theta`   | $\varpi$      | `\varpi`      | $\Phi$    | `\Phi`    | $\aleph$   | `\aleph`   |
| `\eta`     | $\omega$  | `\omega`  | $\upsilon$ | `\upsilon` | $\varrho$     | `\varrho`     | $\Pi$     | `\Pi`     | $\beth$    | `\beth`    |
| `\gamma`   | $\phi$    | `\phi`    | $\xi$      | `\xi`      | $\varsigma$   | `\varsigma`   | $\Psi$    | `\Psi`    | $\daleth$  | `\daleth`  |
| `\iota`    | $\pi$     | `\pi`     | $\zeta$    | `\zeta`    | $\vartheta$   | `\vartheta`   | $\Sigma$  | `\Sigma`  | $\gimel$   | `\gimel`   |

### Other letters

| $\imath$   | `\imath`   | $\nabla$   | `\nabla`   | $\Im$      | `\Im`      | $\Reals$     | `\Reals`     | $\text{\OE}$ | `\text{\OE}` |
| ---------- | ---------- | ---------- | ---------- | ---------- | ---------- | ------------ | ------------ | ------------ | ------------ |
| $\jmath$   | `\jmath`   | $\partial$ | `\partial` | $\image$   | `\image`   | $\wp$        | `\wp`        | $\text{\o}$  | `\text{\o}`  |
| $\aleph$   | `\aleph`   | $\Game$    | `\Game`    | $\Bbbk$    | `\Bbbk`    | $\weierp$    | `\weierp`    | $\text{\O}$  | `\text{\O}`  |
| $\alef$    | `\alef`    | $\Finv$    | `\Finv`    | $\N$       | `\N`       | $\Z$         | `\Z`         | $\text{\ss}$ | `\text{\ss}` |
| $\alefsym$ | `\alefsym` | $\cnums$   | `\cnums`   | $\natnums$ | `\natnums` | $\text{\aa}$ | `\text{\aa}` | $\text{\i}$  | `\text{\i}`  |
| $\beth$    | `\beth`    | $\Complex$ | `\Complex` | $\R$       | `\R`       | $\text{\AA}$ | `\text{\AA}` | $\text{\j}$  | `\text{\j}`  |
| $\gimel$   | `\gimel`   | $\ell$     | `\ell`     | $\Re$      | `\Re`      | $\text{\ae}$ | `\text{\ae}` |              |              |
| $\deleth$  | `\daleth`  | $\hbar$    | `\hbar`    | $\real$    | `\real`    | $\text{\AE}$ | `\text{\AE}` |              |              |
| $\eth$     | `\eth`     | $\hslash$  | `\hslash`  | $\reals$   | `\reals`   | $\text{\oe}$ | `\text{\oe}` |              |              |
## Annotation
|                     |                     |                                    |                                    |
| ------------------- | ------------------- | ---------------------------------- | ---------------------------------- |
| $\cancel{5}$​       | `\cancel{5}`        | $\overbrace{a+b+c}^{\text{note}}$  | `\overbrace{a+b+c}^{\text{note}}`  |
| $\bcancel{5}$       | `\bcancel{5}`       | $\underbrace{a+b+c}^{\text{note}}$ | `\underbrace{a+b+c}_{\text{note}}` |
| $\xcancel{ABC}$     | `\xcancel{ABC}`     | $\not=$                            | `\not =`                           |
| $\sout{abc}$        | `\sout{abc}`        | $\boxed{\pi=\frac c d}$            | `\boxed{\pi=\frac c d}`            |
| $$a_{\angl n}$      | `$a_{\angl n}`      | $a_{\angl n}$                      | `a_\angln`                         |
| $\phase{-78^\circ}$ | `\phase{-78^\circ}` |                                    |                                    |
`\tag{hi} x+y^{2x}`
$\tag{hi} x+y^{2x}$
`\tag*{hi} x+y^{2x}`
$\tag*{hi} x+y^{2x}$
# Vertical Layout
|                                  |                                  |                   |                   |                                                         |                                                       |
| -------------------------------- | -------------------------------- | ----------------- | ----------------- | ------------------------------------------------------- | ----------------------------------------------------- |
| $x_n$​                           | `x_n`                            | $\stackel{!}{=}$  | `\stackrel{!}{=}` | $a\atop b$                                              | `a \atop b`                                           |
| $e^x$                            | `e^x`                            | $\overset{!}{=}$  | `\overset{!}{=}`  | $a\raisebox{0.25em}{\$b\$}c$                            | `a\raisebox{0.25em}{$b$}c`                            |
| $_u^o$                           | `_u^o`                           | $\underset{!}{=}$ | `\underset{!}{=}` | $a+\left(\vcenter{\hbox{\$\frac{\frac a b}c\$}}\right)$ | `a+\left(\vcenter{\hbox{$\frac{\frac a b}c$}}\right)` |
| $\sum_{\substack{0<i<m\\0<j<n}}$ | `\sum_{\substack{0<i<m\\0<j<n}}` |                   |                   |                                                         |                                                       |
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
| preview                   | method            | preview             | method              | preview | method   | preview | method                      | preview                 | method            |                |
| ------------------------- | ----------------- | ------------------- | ------------------- | ------- | -------- | ------- | --------------------------- | ----------------------- | ----------------- | -------------- |
| $( )$                     | `()`              | $\lparen` `\rparen$ | `\lparen` `\rparen` | ⌈⌉⌈⌉    | `⌈ ⌉`    | ⌈⌉⌈⌉    | `\lceil` `\rceil`           | ↑↑                      | `\uparrow`        |                |
| $[ ]$                     | `[]`              | [][]                | `\lbrack` `\rbrack` | ⌊⌋⌊⌋    | `⌊ ⌋`    | ⌊⌋⌊⌋    | `\lfloor` `\rfloor`         | ↓↓                      | `\downarrow`      |                |
| $\{ \}$                   | `{}`              | {}{}                | `\lbrace` `\rbrace` | ⎰⎱⎰⎱    | `⎰⎱`     | ⎰⎱⎰⎱    | `\lmoustache` `\rmoustache` | ↕↕                      | `\updownarrow`    |                |
| $⟨⟩$                      | `⟨⟩`              | $\langle{}\rangle$  | `\langle` `\rangle` | ⟮⟯⟮⟯    | `⟮ ⟯`    | ⟮⟯⟮⟯    | `\lgroup` `\rgroup`         | ⇑⇑                      | `\Uparrow`        |                |
| $'\\$                     | `\\               | $∣∣$                | ∣∣                  | `\vert` | ┌┐┌┐     | `┌ ┐`   | ┌┐                          | `\ulcorner` `\urcorner` | ⇓⇓                | `\Downarrow`   |
| ∥∥ _(MD syntax conflict)_ | `\\               | $∥∥$                | ∥∥                  | `\Vert` | └┘└┘     | `└ ┘`   | └┘                          | `\llcorner` `\lrcorner` | ⇕⇕                | `\Updownarrow` |
| $\lvert{}\rvert$          | `\lvert` `\rvert` | $\lVert{}\rVert$    | `\lVert` `\rVert`   |         | `\left.` |         | `\right.`                   | \\                      | `\backslash`      |                |
| $\lang{}\rang$            | `\lang` `\rang`   | <><>                | `\lt \gt`           | ⟦⟧[[]]  | `⟦ ⟧`    | ⟦⟧[[]]  | `\llbracket` `\rrbracket`   | ⦃⦄{[]}                  | `\lBrace \rBrace` |                |

---
