# 三角関数と双曲線関数

## 定義

### 三角関数

$$
\begin{eqnarray*}
\sin{x} &=& \frac{e^{ix}-e^{-ix}}{2i} = x-\frac{x^3}{3!}+\frac{x^5}{5!}-\frac{x^7}{7!}\cdots\\
\cos{x} &=& \frac{e^{ix}+e^{-ix}}{2} = 1-\frac{x^2}{2!}+\frac{x^4}{4!}-\frac{x^6}{6!}\cdots\\
\end{eqnarray*}
$$

### 双曲線関数

$$
\begin{eqnarray*}
\sinh{x} &=& \frac{\sin{(ix)}}{i} = \frac{e^x-e^{-x}}{2}\\
\cosh{x} &=& \cos{(ix)} = \frac{e^x+e^{-x}}{2}\\
\tanh{x} &=& \frac{\sinh{x}}{\cosh{x}} = \frac{e^x-e^{-x}}{e^x+e^{-x}}
\end{eqnarray*}
$$

### 逆双曲線関数

$$
\begin{eqnarray*}
\sinh^{-1} x &=& \ln(x+\sqrt{x^2+1}) \\
\cosh^{-1} x &=& \ln(x+\sqrt{x^2-1}) \\
\tanh^{-1} x &=& \frac{1}{2}\ln{\frac{1+x}{1-x}}
\end{eqnarray*}
$$

## 微分

### 逆三角関数

$$
\begin{eqnarray*}
\frac{d}{dx}(\sin^{-1}x) &=& \frac{1}{\sqrt{1-x^2}}\\
\frac{d}{dx}(\cos^{-1}x) &=& -\frac{1}{\sqrt{1-x^2}}\\
\frac{d}{dx}(\tan^{-1}x) &=& \frac{1}{1+x^2}\\
\end{eqnarray*}
$$

### 双曲線関数

$$
\begin{eqnarray*}
\frac{d}{dx}(\sinh{x}) &=& \cosh{x}\\
\frac{d}{dx}(\cosh{x}) &=& \sinh{x}\\
\frac{d}{dx}(\tanh{x}) &=& \frac{1}{\cosh^{2}x}\\
\end{eqnarray*}
$$

### 逆双曲線関数

$$
\begin{eqnarray*}
\frac{d}{dx}(\sinh^{-1}x) &=& \frac{1}{\sqrt{x^2+1}}\\
\frac{d}{dx}(\cosh^{-1}x) &=& \frac{1}{\sqrt{x^2-1}}\\
\frac{d}{dx}(\tanh^{-1}x) &=& \frac{1}{1-x^2}\\
\end{eqnarray*}
$$

## 積分

$$
\begin{eqnarray*}
\int\frac{1}{\sqrt{x^2+1}} dx &=& \sinh^{-1} x\\
\int\frac{1}{\sqrt{x^2-1}} dx &=& \cosh^{-1} x\\
\int\frac{dx}{\sqrt{1-x^2}} dx &=&
    \left\{
	\begin{array}{l}
	-\cos^{-1} x + C  \\
	\sin^{-1} x + C \end{array}
	\right. \\
\int\frac{1}{1+x^2} dx&=& \tan^{-1}x + C\\
\int\frac{1}{1-x^2} dx &=& \tanh^{-1} x
\end{eqnarray*}
$$

# シグマ公式

### 2つのシグマの分解

$$
\sum^m_{i=1}\sum^n_{j=1}a_ib_j=\sum^m_{i=1}a_i\sum^n_{j=1}b_j
$$

# 座標系

## 極座標

### ラプラシアン

$$
\Delta f = \frac{1}{r^2}\frac{\partial}{\partial r}(r^2\frac{\partial f}{\partial r})+\frac{1}{r^2\sin\theta}\frac{\partial}{\partial\theta}(\sin\theta\frac{\partial f}{\partial\theta})+\frac{1}{r^2\sin^2\theta}\frac{\partial^2f}{\partial\phi^2}
$$

### 重積分の変数変換

$$
dxdydz=r^2\sin\theta drd\theta d\phi
$$

# 電磁気学

### ビオ・サバールの法則

$$
\textbf{B}((\textbf{r}))=\frac{\mu_0}{4\pi}\frac{Id\textbf{r}'\times(\textbf{r}-\textbf{r}')}{|\textbf{r}-\textbf{r}'|^3}
$$







