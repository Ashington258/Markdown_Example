
>https://github.com/oldbulb/LaTex_Math/blob/main/LaTex_Math.md
#Latex数学公式示例


<!-- @import "[TOC]" {cmd="toc" depthFrom=1 depthTo=6 orderedList=false} -->

<!-- code_chunk_output -->

- [希腊字母(\&不同字体)](#希腊字母不同字体)
- [二元运算符(等号)](#二元运算符等号)
- [大尺寸运算符](#大尺寸运算符)
- [定界符](#定界符)
- [大尺寸定界符](#大尺寸定界符)
- [上标](#上标)
- [空格](#空格)
- [箭头](#箭头)
- [其它符号](#其它符号)
- [常用数学公式](#常用数学公式)
- [公式排列示例](#公式排列示例)

<!-- /code_chunk_output -->

---

## 希腊字母(&不同字体)

| **大写**`LaTeX`**命令** | **小写**`LaTeX`**命令** | **大写**     | **小写**                  |
| ----------------------- | ----------------------- | ------------ | ------------------------- |
| `A`                     | `\alpha`                | $$A$$        | $$\alpha$$                |
| `B`                     | `\beta`                 | $$B$$        | $$\beta$$                 |
| `\Gamma`                | `\gamma`                | $$\Gamma$$   | $$\gamma$$                |
| `\Delta`                | `\delta`                | $$\Delta$$   | $$\delta$$                |
| `E`                     | `\epsilon, \varepsilon` | $$E$$        | $$\epsilon, \varepsilon$$ |
| `Z`                     | `\zeta`                 | $$Z$$        | $$\zeta$$                 |
| `H`                     | `\eta`                  | $$H$$        | $$\eta$$                  |
| `\Theta`                | `\theta, \vartheta`     | $$\Theta$$   | $$\theta, \vartheta$$     |
| `I`                     | `\iota`                 | $$I$$        | $$\iota$$                 |
| `K`                     | `\kappa`                | $$K$$        | $$\kappa$$                |
| `\Lambda`               | `\lambda`               | $$\Lambda$$  | $$\lambda$$               |
| `M`                     | `\mu`                   | $$M$$        | $$\mu$$                   |
| `N`                     | `\nu`                   | $$N$$        | $$\nu$$                   |
| `\Xi`                   | `\xi`                   | $$\Xi$$      | $$\xi$$                   |
| `O`                     | `o`                     | $$O$$        | $$o$$                     |
| `\Pi`                   | `\pi, \varpi`           | $$\Pi$$      | $$\pi, \varpi$$           |
| `P`                     | `\rho, \varrho`         | $$P$$        | $$\rho, \varrho$$         |
| `\Sigma`                | `\sigma, \varsigma`     | $$\Sigma$$   | $$\sigma, \varsigma$$     |
| `T`                     | `\tau`                  | $$T$$        | $$\tau$$                  |
| `\Upsilon`              | `\upsilon`              | $$\Upsilon$$ | $$\upsilon$$              |
| `\Phi`                  | `\phi, \varphi`         | $$\Phi$$     | $$\phi, \varphi$$         |
| `X`                     | `\chi`                  | $$X$$        | $$\chi$$                  |
| `\Psi`                  | `\psi`                  | $$\Psi$$     | $$\psi$$                  |
| `\Omega`                | `\omega`                | $$\Omega$$   | $$\omega$$                |

| 操作             | `LaTeX`**命令**       | **符号**                |
| ---------------- | --------------------- | ----------------------- |
| **加粗**         | `\boldsymbol{\delta}` | $$\boldsymbol{\delta}$$ |
| **空心**         | `\mathbb{M}`          | $$\mathbb{M}$$          |
| **上标干扰**     | `\jmath, \imath`      | $$\jmath, \imath$$      |
| **正体，罗马体** | `\mathrm{d}`          | $$\mathrm{d}$$          |
| **哥特体**       | `\mathfrak{A, a, 1}`  | $$\mathfrak{A, a, 1}$$  |
| **斜体数字**     | `\mathit{1, 2, 3}`    | $$\mathit{1, 2, 3}$$    |
| **手写体**       | `\mathcal{A, B, C}`   | $$\mathcal{A, B, C}$$   |
| **铜板体**       | `\mathscr{A, B, C}`   | $$\mathscr{A, B, C}$$   |


## 二元运算符(等号)

| `LaTeX`**命令**  | **符号**           |     | `LaTeX`**命令**    | **符号**                  |     | `LaTeX`**命令**  | **符号**           |
| ---------------- | ------------------ | --- | ------------------ | ------------------------- | --- | ---------------- | ------------------ |
| `+`              | $$+$$              |     | `-`                | $$-$$                     |     | `\triangleleft`  | $$\triangleleft$$  |
| `\pm`            | $$\pm$$            |     | `\mp`              | $$\mp$$                   |     | `\triangleright` | $$\triangleright$$ |
| `\cdot`          | $$\cdot$$          |     | `\div`             | $$\div$$                  |     | `\star`          | $$\star$$          |
| `\times`         | $$\times$$         |     | `\setminus`        | $$\setminus$$             |     | `\ast`           | $$\ast$$           |
| `\cup`           | $$\cup$$           |     | `\cap`             | $$\cap$$                  |     | `\circ`          | $$\circ$$          |
| `\sqcup`         | $$\sqcup$$         |     | `\sqcap`           | $$\sqcap$$                |     | `\bullet`        | $$\bullet$$        |
| `\vee, \lor`     | $$\vee, \lor$$     |     | `\wedge, \land`    | $$\wedge, \land$$         |     | `\diamond`       | $$\diamond$$       |
| `\oplus`         | $$\oplus$$         |     | `\ominus`          | $$\ominus$$               |     | `\uplus`         | $$\uplus$$         |
| `\odot`          | $$\odot$$          |     | `\oslash`          | $$\oslash$$               |     | `\amalg`         | $$\amalg$$         |
| `\otimes`        | $$\otimes$$        |     | `\bigcirc`         | $$\bigcirc$$              |     | `\dagger`        | $$\dagger$$        |
| `\bigtriangleup` | $$\bigtriangleup$$ |     | `\bigtriangledown` | $$\bigtriangledown$$      |     | `\lhd, \rhd`     | $$\lhd, \rhd$$     |
| `\ddagger`       | $$\ddagger$$       |     | `\wr`              | $$\wr$$                   |     | `\unlhd, \unrhd` | $$\unlhd,\unrhd$$  |
| `=`              | $$=$$              |     | `\xlongequal`      | $$\xlongequal[abc]{def}$$ |     | `\neq`           | $$\neq$$           |

## 大尺寸运算符

| `LaTeX`**命令** | **符号**    |     | `LaTeX`**命令** | **符号**      |     | `LaTeX`**命令** | **符号**      |     | `LaTeX`**命令** | **符号**       |
| --------------- | ----------- | --- | --------------- | ------------- | --- | --------------- | ------------- | --- | --------------- | -------------- |
| `\sum`          | $$\sum$$    |     | `\bigcup`       | $$\bigcup$$   |     | `\bigvee`       | $$\bigvee$$   |     | `\bigoplus`     | $$\bigoplus$$  |
| `\prod`         | $$\prod$$   |     | `\bigcap`       | $$\bigcap$$   |     | `\bigwedge`     | $$\bigwedge$$ |     | `\bigotimes`    | $$\bigotimes$$ |
| `\coprod`       | $$\coprod$$ |     | `\bigsqcup`     | $$\bigsqcup$$ |     | `\iiint`        | $$\iiint$$    |     | `\bigodot`      | $$\bigodot$$   |
| `\int`          | $$\int$$    |     | `\oint`         | $$\oint$$     |     | `\iint`         | $$\iint$$     |     | `\biguplus`     | $$\biguplus$$  |



## 定界符

| `LaTeX`**命令** | **符号**    |     | `LaTeX`**命令** | **符号**       |     | `LaTeX`**命令** | **符号**         |     | `LaTeX`**命令** | **符号**         |
| --------------- | ----------- | --- | --------------- | -------------- | --- | --------------- | ---------------- | --- | --------------- | ---------------- |
| `(`             | $$($$       |     | `)`             | $$)$$          |     | `\uparrow`      | $$\uparrow$$     |     | `\Uparrow`      | $$\Uparrow$$     |
| `\[`            | $$\[$$      |     | `\]`            | $$\]$$         |     | `\downarrow`    | $$\downarrow$$   |     | `\Downarrow`    | $$\Downarrow$$   |
| `\{`            | $$\{$$      |     | `\}`            | $$\}$$         |     | `\updownarrow`  | $$\updownarrow$$ |     | `\Updownarrow`  | $$\Updownarrow$$ |
| `\langle`       | $$\langle$$ |     | `\rangle`       | $$\rangle$$    |     | `\|, \vert`     | $$\|, \vert$$    |     | `\\|, \Vert`    | $$\\|, \Vert$$   |
| `\lfloor`       | $$\lfloor$$ |     | `\rfloor`       | $$\rfloor$$    |     | `\lceil`        | $$\lceil$$       |     | `\rceil`        | $$\rceil$$       |
| `/`             | $$/$$       |     | `\backslash`    | $$\backslash$$ |     | `\%`            | $$\%$$           |     |                 |                  |



## 大尺寸定界符

| `LaTeX`**命令** | **符号**       |     | `LaTeX`**命令** | **符号**       |     | `LaTeX`**命令** | **符号**        |     | `LaTeX`**命令** | **符号**        |
| --------------- | -------------- | --- | --------------- | -------------- | --- | --------------- | --------------- | --- | --------------- | --------------- |
| `\lgroup`       | $$\lgroup$$    |     | `\rgroup`       | $$\rgroup$$    |     | `\lmoustache`   | $$\lmoustache$$ |     | `\rmoustache`   | $$\rmoustache$$ |
| `\arrowvert`    | $$\arrowvert$$ |     | `\Arrowvert`    | $$\Arrowvert$$ |     | `\bracevert`    | $$\bracevert$$  |     |                 |                 |



## 上标

| `LaTeX`**命令** | **符号**      |     | `LaTeX`**命令**       | **符号**              |     | `LaTeX`**命令**  | **符号**           |
| --------------- | ------------- | --- | --------------------- | --------------------- | --- | ---------------- | ------------------ |
| `\hat{a}`       | $$\hat{a}$$   |     | `\dot{a}`, `\ddot{a}` | $$\dot{a}, \ddot{a}$$ |     | `\widehat{AB}`   | $$\widehat{AB}$$   |
| `\grave{a}`     | $$\grave{a}$$ |     | `\vec{a}`             | $$\vec{a}$$           |     | `\acute{a}`      | $$\acute{a}$$      |
| `\bar{a}`       | $$\bar{a}$$   |     | `\tilde{a}`           | $$\tilde{a}$$         |     | `\breve{a}`      | $$\breve{a}$$      |
| `\check{a}`     | $$\check{a}$$ |     | `\mathring{a}`        | $$\mathring{a}$$      |     | `\widetilde{AB}` | $$\widetilde{AB}$$ |



## 空格

| `LaTeX`**命令** | **符号**       | 宽度             |
| --------------- | -------------- | ---------------- |
| `a \qquad b`    | $$a \qquad b$$ | $$2m$$           |
| `a \quad b`     | $$a \quad b$$  | $$m$$            |
| `a \ b`         | $$a \ b$$      | $$\frac{m}{3}$$  |
| `a \; b`        | $$a \; b$$     | $$\frac{2m}{7}$$ |
| `a \, b`        | $$a \, b$$     | $$\frac{m}{6}$$  |
| `a b`           | $$a b$$        | $$0$$            |
| `a \! b`        | $$a \! b$$     | $$-\frac{m}{6}$$ |



## 箭头

| `LaTeX`**命令**      | **符号**               |     | `LaTeX`**命令**       | **符号**                |     | `LaTeX`**命令** | **符号**         |
| -------------------- | ---------------------- | --- | --------------------- | ----------------------- | --- | --------------- | ---------------- |
| `\leftarrow, \gets`  | $$\leftarrow, \gets$$  |     | `\longleftarrow`      | $$\longleftarrow$$      |     | `\uparrow`      | $$\uparrow$$     |
| `\rightarrow, \to`   | $$\rightarrow, \to$$   |     | `\longrightarrow`     | $$\longrightarrow$$     |     | `\downarrow`    | $$\downarrow$$   |
| `\leftrightarrow`    | $$\leftrightarrow$$    |     | `\longleftrightarrow` | $$\longleftrightarrow$$ |     | `\updownarrow`  | $$\updownarrow$$ |
| `\Leftarrow`         | $$\Leftarrow$$         |     | `\Longleftarrow`      | $$\Longleftarrow$$      |     | `\Uparrow`      | $$\Uparrow$$     |
| `\Rightarrow`        | $$\Rightarrow$$        |     | `\Longrightarrow`     | $$\Longrightarrow$$     |     | `\Downarrow`    | $$\Downarrow$$   |
| `\Leftrightarrow`    | $$\Leftrightarrow$$    |     | `\Longleftrightarrow` | $$\Longleftrightarrow$$ |     | `\Updownarrow`  | $$\Updownarrow$$ |
| `\mapsto`            | $$\mapsto$$            |     | `\longmapsto`         | $$\longmapsto$$         |     | `\nearrow`      | $$\nearrow$$     |
| `\hookleftarrow`     | $$\hookleftarrow$$     |     | `\hookrightarrow`     | $$\hookrightarrow$$     |     | `\searrow`      | $$\searrow$$     |
| `\leftharpoonup`     | $$\leftharpoonup$$     |     | `\rightharpoonup`     | $$\rightharpoonup$$     |     | `\swarrow`      | $$\swarrow$$     |
| `\leftharpoondown`   | $$\leftharpoondown$$   |     | `\rightharpoondown`   | $$\rightharpoondown$$   |     | `\nwarrow`      | $$\nwarrow$$     |
| `\rightleftharpoons` | $$\rightleftharpoons$$ |     | `\iff`                | $$\iff$$                |     | `\leadsto`      | $$\leadsto$$     |



## 其它符号

| `LaTeX`**命令** | **符号**         |     | `LaTeX`**命令** | **符号**         |     | `LaTeX`**命令** | **符号**       |     | `LaTeX`**命令** | **符号**       |
| --------------- | ---------------- | --- | --------------- | ---------------- | --- | --------------- | -------------- | --- | --------------- | -------------- |
| `\dots`         | $$\dots$$        |     | `\cdots`        | $$\cdots$$       |     | `\vdots`        | $$\vdots$$     |     | `\ddots`        | $$\ddots$$     |
| `\hbar`         | $$\hbar$$        |     | `\imath`        | $$\imath$$       |     | `\jmath`        | $$\jmath$$     |     | `\ell`          | $$\ell$$       |
| `\Re`           | $$\Re$$          |     | `\Im`           | $$\Im$$          |     | `\aleph`        | $$\aleph$$     |     | `\wp`           | $$\wp$$        |
| `\forall`       | $$\forall$$      |     | `\exists`       | $$\exists$$      |     | `\Join`         | $$\Join$$      |     | `\partial`      | $$\partial$$   |
| `‘`             | $$‘$$            |     | `\prime`        | $$\prime$$       |     | `\emptyset`     | $$\emptyset$$  |     | `\infty`        | $$\infty$$     |
| `\nabla`        | $$\nabla$$       |     | `\triangle`     | $$\triangle$$    |     | `\vdash`        | $$\vdash$$     |     | `\vdash`        | $$\vdash$$     |
| `\bot`          | $$\bot$$         |     | `\top`          | $$\top$$         |     | `\angle`        | $$\angle$$     |     | `\surd`         | $$\surd$$      |
| `\diamondsuit`  | $$\diamondsuit$$ |     | `\heartsuit`    | $$\heartsuit$$   |     | `\clubsuit`     | $$\clubsuit$$  |     | `\spadesuit`    | $$\spadesuit$$ |
| `\neg, \lnot`   | $$\neg, \lnot$$  |     | `\flat`         | $$\flat$$        |     | `\natural`      | $$\natural$$   |     | `\sharp`        | $$\sharp$$     |
| `\mho`          | $$\mho$$         |     | `\Box`          | $$\Box$$         |     | `\Diamond`      | $$\Diamond$$   |     | `\in`           | $$\in$$        |
| `\bigstar`      | $$\bigstar$$     |     | `\blacksquare`  | $$\blacksquare$$ |     | `\checkmark`    | $$\checkmark$$ |     | `\cup`          | $$\cup$$       |



## 常用数学公式

| 功能             | `LaTeX`**命令**                                                                 | 效果                                                                                               |
| ---------------- | ------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- |
| argmax           | `\arg\underset{\theta}{\max}`                                                   | $$\displaystyle \arg\underset{\theta}{\max}$$                                                      |
| 条件概率         | `P(a\vert x)`                                                                   | $$\displaystyle P(a\vert x)$$                                                                      |
| 求和             | `\sum_{k=1}^n x`, `\begin{matrix} \sum_{k=1}^n x \end{matrix}`                  | $$\displaystyle\sum_{k=1}^n x$$                                                                    |
| 积分             | `\int_{-N}^{N} e^x\, dx`                                                        | $$\displaystyle\int_{-N}^{N} e^x\, dx$$                                                            |
| 分式(带括号)     | `\left\lceil\frac{x}{y}\right\rceil`                                            | $$\displaystyle\left(\frac{x}{y}\right)$$                                                          |
| 曲面积分(自定义) | `{\bigcirc\kern{-11.7pt}\int}`,`{\subset\kern{-3pt}\supset\kern{-16.8pt}\iint}` | $$\displaystyle {\bigcirc\kern{-11.7pt}\int} \quad{\subset\kern{-3pt}\supset\kern{-16.8pt}\iint}$$ |



## 公式排列示例

1. 使用`{align}`环境，默认`&`符号左右两端的内容向中间对齐, 使用`&&`添加备注。

```latex
\begin{align}
	\nabla \cdot \mathbf{E} &= \cfrac{\rho}{\varepsilon_0} && \mathrm{Gauss\ law}
	\\
	\nabla \cdot \mathbf{B} &= 0 && \mathrm{Gauss\ law\ for\ magnetism}
	\\
	\nabla \times \mathbf{E} &= - \cfrac{\partial\mathbf{B}}{\partial t} 
	&& \mathrm{Faraday\ law\ of\ induction}
	\\
	\nabla \times \mathbf{B}&= 
	\mu_0 \left(\mathbf{J} + \varepsilon_0 \ \cfrac{\partial\mathbf{E}}{\partial t}\right)
	&& \mathrm{Amp\grave{e}re\ circuital\ law}
\end{align}
```

---

$$
\nabla \cdot \mathbf{E} = \cfrac{\rho}{\varepsilon_0} 
$$

$$
\nabla \cdot \mathbf{B} = 0
$$

$$
\nabla \times \mathbf{E} = - \cfrac{\partial\mathbf{B}}{\partial t} 
$$

$$
\nabla \times \mathbf{B}= 
	\mu_0 \left(\mathbf{J} + \varepsilon_0 \ \cfrac{\partial\mathbf{E}}{\partial t}\right)
$$

---

2.使用`{array}`环境，`{l}`-左对齐，`{r}`-右对齐，`{c}`-居中对齐。

```latex
\begin{array}{}
	\displaystyle
	\oiint_{\partial\Omega}\mathbf{E} \cdot \mathrm{d} \mathbf{B} = \cfrac{1}{\varepsilon_0} \iiint_\Omega\rho	\mathrm{d}V
	&& \mathrm{Gauss\ law}
	\\
	\displaystyle
	\oiint_{\partial\Omega}\mathbf{B} \cdot \mathrm{d} \mathbf{S} = 0
	&& \mathrm{Gauss\ law\ for\ magnetism}
	\\
	\displaystyle
	{\bigcirc\kern{-11.7pt}\int}_{\partial\Sigma}\mathbf{E} \cdot \mathrm{d} \boldsymbol{\ell} = 
	-\cfrac{\mathrm{d}}{\mathrm{d}t} \iint_\Sigma \mathbf{B} \cdot \mathrm{d} \mathbf{S}
	&& \mathrm{Faraday\ law\ of\ induction}
	\\
	\displaystyle
	{\bigcirc\kern{-11.7pt}\int}_{\partial\Sigma}\mathbf{B} \cdot \mathrm{d} \boldsymbol{\ell} = 
	\mu_0 \left(\iint_\Sigma \mathbf{J} \cdot \mathrm{d} \mathbf{S} + \varepsilon_0 \ \cfrac{\rm d}{\mathrm{d}t}\iint_\Sigma \mathbf{E} \cdot \mathrm{d} \mathbf{S}\right)
	&& \mathrm{Amp\grave{e}re\ circuital\ law}
\end{array}
```

---

$$
\displaystyle
\oiint_{\partial\Omega}\mathbf{E} \cdot \mathrm{d} \mathbf{B} = \cfrac{1}{\varepsilon_0} \iiint_\Omega\rho\mathrm{d}V
$$

$$
\displaystyle
\oiint_{\partial\Omega}\mathbf{B} \cdot \mathrm{d} \mathbf{S} = 0
$$

$$
\displaystyle
{\bigcirc\kern{-11.7pt}\int}_{\partial\Sigma}\mathbf{E} \cdot \mathrm{d} \boldsymbol{\ell} = 
	-\cfrac{\mathrm{d}}{\mathrm{d}t} \iint_\Sigma \mathbf{B} \cdot \mathrm{d} \mathbf{S}
$$

$$
\displaystyle
{\bigcirc\kern{-11.7pt}\int}_{\partial\Sigma}\mathbf{B} \cdot \mathrm{d} \boldsymbol{\ell} = 
\mu_0 \left(\iint_\Sigma \mathbf{J} \cdot \mathrm{d} \mathbf{S} + \varepsilon_0 \ \cfrac{\rm d}{\mathrm{d}t}\iint_\Sigma \mathbf{E} \cdot \mathrm{d} \mathbf{S}\right)
$$

---


