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
- [LaTeX official website](https://latex-project.org)
- [KaTeX official website](https://katex.org)
And KaTeX handles only a smaller subset of LaTeX’s mathematical notation for display on the web.
# Example
$$
f(x)=\large\displaystyle\int_{\large-\infty}^{\large\infty}\large f\hat\xi\,e^{\Large s\pi i \xi x}\,\large d\xi
$$
```latex
f(x)=\displaystyle\int_{-\infty}^{\infty}f\hat\xi\,e^{s\pi i \xi x}\,d\xi
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
# Variable Size Symbols

| preview     | method      | preview      | method       | preview    | method     |
| ----------- | ----------- | ------------ | ------------ | ---------- | ---------- |
| $\biguplus$ | `\biguplus` | $\sum$       | `\sum`       | $\int$     | `\int`     |
| $\bigcap$   | `\bigcap`   | $\prod$      | `\prod`      | $\oint$    | `\oint`    |
| $\bigcup$   | `\bigcup`   | $\coprod$    | `\coprod`    | $\iint$    | `\iint`    |
| $\bigvee$   | `\bigvee`   | $\bigoplus$  | `\bigoplus`  | $\bigodot$ | `\bigodot` |
| $\bigwedge$ | `\bigwedge` | $\bigotimes$ | `\bigotimes` |            |            |
# Standard Function Names
| preview   | method    | preview   | method    | preview   | method    | preview   | method    |
| --------- | --------- | --------- | --------- | --------- | --------- | --------- | --------- |
| $\arccos$ | `\arccos` | $\arcsin$ | `\arcsin` | $\arcsin$ | `\arcsin` | $\arg$    | `\arg`    |
| $\cos$    | `\cos`    | $\cosh$   | `\cosh`   | $\cot$    | `\cot`    | $\coth$   | `\coth`   |
| $\csc$    | `\csc`    | $\deg$    | `\deg`    | $\det$    | `\det`    | $\dim$    | `\dim`    |
| $\exp$    | `\exp`    | $\gcd$    | `\gcd`    | $\hom$    | `\hom`    | $\inf$    | `\inf`    |
| $\ker$    | `\ker`    | $\lg$     | `\lg`     | $\lim$    | `\lim`    | $\liminf$ | `\liminf` |
| $\limsup$ | `\limsup` | $\ln$     | `\ln`     | $\log$    | `\log`    | $\max$    | `\max`    |
| $\min$    | `\min`    | $\Pr$     | `\Pr`     | $\sec$    | `\sec`    | $\sin$    | `\sin`    |
| $\sinh$   | `\sinh`   | $\sup$    | `\sup`    | $\tan$    | `\tan`    | $\tanh$   | `\tanh`   |
#### Function names should be in roman font, not italics, for example:

|            |                 |                     |                 |
| ---------- | --------------- | ------------------- | --------------- |
| Correct:   | `\tan(at-n\pi)` | →→                  | $\tan(at-n\pi)$ |
| Incorrect: | `tan(at-n\pi)`  | `katex:\rightarrow` | $tan(at-n\pi)$  |
# Logic And Set Theory 
|               |               |               |               |                   |                   |
| ------------- | ------------- | ------------- | ------------- | ----------------- | ----------------- |
| $\forall$     | `\forall`     | $\complement$ | `\complement` | $\therefore$      | `\therefore`      |
| $\exists$     | `\exists`     | $\subset$     | `\subset`     | $\because$        | `\because`        |
| $\nexists$    | `\nexists`    | $\supset$     | `\supset`     | $\mapsto$         | `\mapsto`         |
| $\in$         | `\in`         | $\mid$        | `\mid`        | $\to$             | `\to`             |
| $\notin$      | `\notin`      | $\land$       | `\land`       | $\gets$           | `\gets`           |
| $\ni$         | `\ni`         | $\lor$        | `\lor`        | $\leftrightarrow$ | `\leftrightarrow` |
| $\emptyset$   | `\emptyset`   | $\implies$    | `\implies`    | $\iff$            | `\iff`            |
| $\varnothing$ | `\varnothing` | $\impliedby$  | `\impliedby`  | $\neg$ or $\lnot$ | `\neg` or `\lnot` |

|                            |                          |                |              |
| -------------------------- | ------------------------ | -------------- | ------------ |
| $\Set{ x \| x<\frac 1 2 }$ | \Set{ x \| x<\frac 1 2 } | $\set{x\|x<5}$ | \set{x\|x<5} |
# Special Symbols
|              |              |              |              |                                            |                                            |
| ------------ | ------------ | ------------ | ------------ | ------------------------------------------ | ------------------------------------------ |
| $\bra{\phi}$ | `\bra{\phi}` | $\ket{\psi}$ | `\ket{\psi}` | $\braket{\phi\\\|\psi}$                    | `\braket{\phi\\\|\psi}`                    |
| $\Bra{\phi}$ | `\Bra{\phi}` | $\Ket{\psi}$ | `\Ket{\psi}` | $\Braket{ ϕ \\\|\frac{∂^2}{∂ t^2} \\\|ψ }$ | `\Braket{ ϕ \\\|\frac{∂^2}{∂ t^2} \\\|ψ }` |
# Mathematical operator
|           |           |           |           |                     |                     |
| --------- | --------- | --------- | --------- | ------------------- | ------------------- |
| $\arcsin$ | `\arcsin` | $\injlim$ | `\injlim` | $\min$              | `\min`              |
| $\arccos$ | `\arccos` | $\lim$    | `\lim`    | $\Pr$               | `\Pr`               |
| $\arctan$ | `\arctan` | $\liminf$ | `\liminf` | $\projlim$          | `\projlim`          |
| $\cosh$   | `\cosh`   | $\limsup$ | `\limsup` | $\sup$              | `\sup`              |
| $\cot$    | `\cot`    | $\max$    | `\max`    | $\sec$              | `\sec`              |
| $\arg$    | `\arg`    | $\deg$    | `\deg`    | $\sin$              | `\sin`              |
| $\tan$    | `\tan`    | $\dim$    | `\dim`    | $\sinh$             | `\sinh`             |
| $\cos$    | `\cos`    | $\exp$    | `\exp`    | $\tanh$             | `\tanh`             |
| $\coth$   | `\coth`   | $\hom$    | `\hom`    | $\varinjlim$        | `\varinjlim`        |
| $\csc$    | `\csc`    | $\ker$    | `\ker`    | $\varliminf$        | `\varliminf`        |
| $\det$    | `\det`    | $\lg$     | `\lg`     | $\varlimsup$        | `\varlimsup`        |
| $\gcd$    | `\gcd`    | $\ln$     | `\ln`     | $\varprojlim$       | `\varprojlim`       |
| $\inf$    | `\inf`    | $\log$    | `\log`    | $\operatorname*{f}$ | `\operatorname*{f}` |
# Examples
- Example 1 Array
	```latex
\def\arraystretch{1.5}
   \begin{array}{c:c:c}
   a & b & c \\ \hline
   d & e & f \\
   \hdashline
   g & h & i
\end{array}
	```
$$
\def\arraystretch{1.5}
   \begin{array}{c:c:c}
   a & b & c \\ \hline
   d & e & f \\
   \hdashline
   g & h & i
\end{array}
$$
- Example 2 Matrix
```latex
\begin{matrix}
   a & b \\
   c & d
\end{matrix}
```
$$
\begin{matrix}
   a & b \\
   c & d
\end{matrix}
$$
```latex
\begin{array}{cc}
   a & b \\
   c & d
\end{array}
```
$$
\begin{array}{cc}
   a & b \\
   c & d
\end{array}
$$
```latex
\begin{pmatrix}
   a & b \\
   c & d
\end{pmatrix}
```
$$
\begin{pmatrix}
   a & b \\
   c & d
\end{pmatrix}
$$
```latex
\begin{bmatrix}
   a & b \\
   c & d
\end{bmatrix}
```
$$
\begin{bmatrix}
   a & b \\
   c & d
\end{bmatrix}
$$
```latex
\begin{vmatrix}
   a & b \\
   c & d
\end{vmatrix}
```
$$
\begin{vmatrix}
   a & b \\
   c & d
\end{vmatrix}
$$
```latex
\begin{Vmatrix}
   a & b \\
   c & d
\end{Vmatrix}
```
$$
\begin{Vmatrix}
   a & b \\
   c & d
\end{Vmatrix}
$$
- Example 3 Cases
```latex
x = \begin{cases}
   a &\text{if } b \\
   c &\text{if } d
\end{cases}
```
$$
x = \begin{cases}
   a &\text{if } b \\
   c &\text{if } d
\end{cases}
$$
```latex
\begin{rcases}
   a &\text{if } b \\
   c &\text{if } d
\end{rcases}⇒…
```
$$
\begin{rcases}
   a &\text{if } b \\
   c &\text{if } d
\end{rcases}⇒…
$$
# Small Array
```latex
\begin{smallmatrix}
   a & b \\
   c & d
\end{smallmatrix}
```
$$
\begin{smallmatrix}
   a & b \\
   c & d
\end{smallmatrix}
$$
# Subarray
```latex
\sum_{
\begin{subarray}{l}
   i\in\Lambda\\
   0<j<n
\end{subarray}}
```
$$
\sum_{
\begin{subarray}{l}
   i\in\Lambda\\
   0<j<n
\end{subarray}}
$$
# Equation
```latex
\begin{equation}
\begin{split}  a &=b+c\\
      &=e+f
\end{split}
\end{equation}
```
$$
\begin{equation}
\begin{split}  a &=b+c\\
      &=e+f
\end{split}
\end{equation}
$$
# Alignment
```latex
\begin{align}
   a&=b+c \\
   d+e&=f
\end{align}
```
$$
\begin{align}
   a&=b+c \\
   d+e&=f
\end{align}
$$
# Gather
```latex
\begin{gather}
   a=b \\
   e=b+c
\end{gather}
```
$$
\begin{gather}
   a=b \\
   e=b+c
\end{gather}
$$
# Alignat
```latex
\begin{alignat}{2}
   10&x+&3&y=2\\
   3&x+&13&y=4
\end{alignat}
```
$$
\begin{alignat}{2}
   10&x+&3&y=2\\
   3&x+&13&y=4
\end{alignat}
$$
# CD
```latex
\begin{CD}
   A @>a>> B \\
@VbVV @AAcA \\
   C @= D
\end{CD}
```
$$
\begin{CD}
   A @>a>> B \\
@VbVV @AAcA \\
   C @= D
\end{CD}
$$
# Color
|                               |                                 |
| ----------------------------- | ------------------------------- |
| $\color{blue} F=ma$           | `\color{blue} F=ma`             |
| $\textcolor{blue}{F=ma}$      | `\textcolor{blue}{F=ma}`        |
| $\textcolor{#228B22}{F=ma}$   | `\textcolor{#228B22}{F=ma}`     |
| $\colorbox{aqua}{F=ma}$       | `\colorbox{aqua}{$F=ma$}`       |
| $\fcolorbox{red}{aqua}{F=ma}$ | `\fcolorbox{red}{aqua}{$F=ma$}` |
# Symbols and Punctuation
|                    |                      |                      |                      |                   |                   |
| ------------------ | -------------------- | -------------------- | -------------------- | ----------------- | ----------------- |
|                    | `% comment`          | $\dots$              | `\dots`              |                   |                   |
| $\%$               | `\%`                 | $\cdots$             | `\cdots`             | $\LaTeX$          | `\LaTeX`          |
| $\#$               | `\#`                 | $\ddots$             | `\ddots`             |                   |                   |
| $\&$               | `\&`                 | $\ldots$             | `\ldots`             | $\nabla$          | `\nabla`          |
| $\_$               | `\_`                 | $\vdots$             | `\vdots`             | $\infty$          | `\infty`          |
| $\text{\_}$        | `\textunderscore`    | $\dotsb$             | `\dotsb`             |                   |                   |
| $\text{--}$        | `\text{--}`          | $\dotsc$             | `\dotsc`             |                   |                   |
| $\textendash$      | `\textendash`        | $\dotsi$             | `\dotsi`             |                   |                   |
| $\text{---}$       | `\text{---}`         | $\dotsm$             | `\dotsm`             | $\dagger$         | `\dagger`         |
| $\textemdash$      | `\textemdash`        | $\dotso$             | `\dotso`             | $\textdagger$     | `\textdagger`     |
| $\textasciitilde$  | `\textasciitilde`    |                      |                      |                   |                   |
| $\textasciicircum$ | `\textasciicircum`   |                      |                      | $\ddagger$        | `\ddagger`        |
| $`$                | `                    | $\textellipsis$      | `\textellipsis`      | $\textdaggerdbl$  | `\textdaggerdbl`  |
| $\textquoteleft$   | `\textquoteleft`     | $\Box$               | `\Box`               |                   |                   |
|                    |                      | $\square$            | `\square`            | $\angle$          | `\angle`          |
| $\textquoteright$  | `\textquoteright`    | $\blacksquare$       | `\blacksquare`       | $\measuredangle$  | `\measuredangle`  |
|                    |                      | $\triangle$          | `\triangle`          | $\sphericalangle$ | `\sphericalangle` |
|                    | `\textquotedblleft`  | $\triangledown$      | `\triangledown`      | $\top$            | `\top`            |
| $"$                | `"`                  | $\triangleleft$      | `\triangleleft`      | $\bot$            | `\bot`            |
|                    | `\textquotedblright` | $\triangleright$     | `\triangleright`     | $\$$              | `\$`              |
| $\colon$           | `\colon`             | $\bigtriangledown$   | `\bigtriangledown`   | $\textdollar$     | `\textdollar`     |
| $\backprime$       | `\backprime`         | $\bigtriangleup$     | `\bigtriangleup`     |                   |                   |
| $\prime$           | `\prime`             | $\blacktriangle$     | `\blacktriangle`     |                   |                   |
| $\textless$        | `\textless`          | $\blacktriangledown$ | `\blacktriangledown` | $\textsterling$   | `\textsterling`   |
| $\textgreater$     | `\textgreater`       | $\blacktriangleleft$ | `\blacktriangleleft` | $\yen$            | `\yen`            |
| $\textbar$         | `\textbar`           | $\blacktriangleleft$ | `\blacktriangleleft` | $\surd$           | `\surd`           |
| $\textbardbl$      | `\textbardbl`        | $\diamond$           | `\diamond`           | $\degree$         | `\degree`         |
| $\textbraceleft$   | `\textbraceleft`     | $\Diamond$           | `\Diamond`           | $\textdegree$     | `\textdegree`     |
| $\textbraceright$  | `\textbraceright`    | $\lozenge$           | `\lozenge`           | $\mho$            | `\mho`            |
| $\textbackslash$   | `\textbackslash`     | $\blacklozenge$      | `\blacklozenge`      | $\diagdown$       | `\diagdown`       |
|                    |                      | $\star$              | `\star`              | $\diagup$         | `\diagup`         |
| $\text{\S}$        | `\text{\S}` or `\S`  | $\bigstar$           | `\bigstar`           | $\flat$           | `\flat`           |
|                    |                      | $\clubsuit$          | `\clubsuit`          | $\natural$        | `\natural`        |
|                    |                      |                      |                      | $\sharp$          | `\sharp`          |
| $\circledR$        | `\circledR`          | $\diamondsuit$       | `\diamondsuit`       | $\heartsuit$      | `\heartsuit`      |
| $\textregistered$  | `\textregistered`    |                      |                      |                   |                   |
| $\circledS$        | `\circledS`          | $\spadesuit$         | `\spadesuit`         |                   |                   |
|                    |                      | $\maltese$           | `\maltese`           |                   |                   |
# Expandable Arrows
|                            |                            |                             |                             |
| -------------------------- | -------------------------- | --------------------------- | --------------------------- |
| $\xleftarrow{abc}$         | `\xleftarrow{abc}`         | $\xrightarrow[under]{over}$ | `\xrightarrow[under]{over}` |
| $\xLeftarrow{abc}$         | `\xLeftarrow{abc}`         | $\xRightarrow{abc}$         | `\xRightarrow{abc}`         |
| $\xleftrightarrow{abc}$    | `\xleftrightarrow{abc}`    | $\xLeftrightarrow{abc}$     | `\xLeftrightarrow{abc}`     |
| $\xhookleftarrow{abc}$     | `\xhookleftarrow{abc}`     | $\xhookrightarrow{abc}$     | `\xhookrightarrow{abc}`     |
| $\xtwoheadleftarrow{abc}$  | `\xtwoheadleftarrow{abc}`  | $\xtwoheadrightarrow{abc}$  | `\xtwoheadrightarrow{abc}`  |
| $\xleftharpoonup{abc}$     | `\xleftharpoonup{abc}`     | $\xrightharpoonup{abc}$     | `\xrightharpoonup{abc}`     |
| $\xleftharpoondown{abc}$   | `\xleftharpoondown{abc}`   | $\xrightharpoondown{abc}$   | `\xrightharpoondown{abc}`   |
| $\xleftrightharpoons{abc}$ | `\xleftrightharpoons{abc}` | $\xrightleftharpoons{abc}$  | `\xrightleftharpoons{abc}`  |
| $\xtofrom{abc}$            | `\xtofrom{abc}`            | $\xmapsto{abc}$             | `\xmapsto{abc}`             |
| $\xlongequal{abc}$         | `\xlongequal{abc}`         |                             |                             |
# Arrows
|                     |                     |                        |                        |     |                      |
| ------------------- | ------------------- | ---------------------- | ---------------------- | --- | -------------------- |
| $\circlearrowleft$  | `\circlearrowleft`  | $\leftharpoonup$       | `\leftharpoonup`       |     | `\rArr`              |
| $\circlearrowright$ | `\circlearrowright` | $\leftleftarrows$      | `\leftleftarrows`      |     | `\rarr`              |
| $\curvearrowleft$   | `\curvearrowleft`   | $\leftrightarrow$      | `\leftrightarrow`      |     | `\restriction`       |
| $\curvearrowright$  | `\curvearrowright`  | $\Leftrightarrow$      | `\Leftrightarrow`      |     | `\rightarrow`        |
|                     |                     | $\leftrightarrows$     | `\leftrightarrows`     |     | `\Rightarrow`        |
|                     |                     | $\leftrightharpoons$   | `\leftrightharpoons`   |     | `\rightarrowtail`    |
|                     |                     | $\leftrightsquigarrow$ | `\leftrightsquigarrow` |     | `\rightharpoondown`  |
| $\dashleftarrow$    | `\dashleftarrow`    | $\Lleftarrow$          | `\Lleftarrow`          |     | `\rightharpoonup`    |
| $\dashrightarrow$   | `\dashrightarrow`   | $\longleftarrow$       | `\longleftarrow`       |     | `\rightleftarrows`   |
| $\downarrow$        | `\downarrow`        | $\Longleftarrow$       | `\Longleftarrow`       |     | `\rightleftharpoons` |
| $\Downarrow$        | `\Downarrow`        | $\longleftrightarrow$  | `\longleftrightarrow`  |     | `\rightrightarrows`  |
| $\downdownarrows$   | `\downdownarrows`   | $\Longleftrightarrow$  | `\Longleftrightarrow`  |     | `\rightsquigarrow`   |
| $\downharpoonleft$  | `\downharpoonleft`  | $\longmapsto$          | `\longmapsto`          |     | `\Rrightarrow`       |
| $\downharpoonright$ | `\downharpoonright` | $\longrightarrow$      | `\longrightarrow`      |     | `\Rsh`               |
| $\gets$             | `\gets`             | $\Longrightarrow$      | `\Longrightarrow`      |     | `\searrow`           |
|                     |                     | $\looparrowleft$       | `\looparrowleft`       |     | `\swarrow`           |
|                     |                     | $\looparrowright$      | `\looparrowright`      |     | `\to`                |
|                     |                     | $\Lrarr$               | `\Lrarr`               |     | `\twoheadleftarrow`  |
| $\hookleftarrow$    | `\hookleftarrow`    | $\lrArr$               | `\lrArr`               |     | `\twoheadrightarrow` |
| $\hookrightarrow$   | `\hookrightarrow`   | $\lrarr$               | `\lrarr`               |     | `\Uarr`              |
| $\iff$              | `\iff`              | $\Lsh$                 | `\Lsh`                 |     | `\uArr`              |
| $\impliedby$        | `\impliedby`        | $\mapsto$              | `\mapsto`              |     | `\uarr`              |
| $\implies$          | `\implies`          | $\nearrow$             | `\nearrow`             |     | `\uparrow`           |
|                     |                     | $\nleftarrow$          | `\nleftarrow`          |     | `\Uparrow`           |
|                     |                     |  $'$                   | `\nLeftarrow`          |     | `\updownarrow`       |
|                     |                     |                        | `\nleftrightarrow`     |     | `\Updownarrow`       |
| $\leadsto$          | `\leadsto`          |                        | `\nLeftrightarrow`     |     | `\upharpoonleft`     |
| $\leftarrow$        | `\leftarrow`        |                        | `\nrightarrow`         |     | `\upharpoonright`    |
| $\Leftarrow$        | `\Leftarrow`        |                        | `\nRightarrow`         |     | `\upuparrows`        |
| $\leftarrowtail$    | `\leftarrowtail`    |                        | `\nwarrow`             |     |                      |
| $\leftharpoondown$  | `\leftharpoondown`  |                        | `\Rarr`                |     |                      |

---
