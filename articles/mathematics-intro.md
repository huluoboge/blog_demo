---
title: "数学公式入门"
date: 2024-01-15
tags: ["数学", "LaTeX", "教程"]
excerpt: "学习如何在Markdown中使用LaTeX数学公式，包括行内公式和块级公式的写法。"
---

# 数学公式入门

在技术文档中，数学公式是非常重要的组成部分。本文将介绍如何在Markdown中使用LaTeX语法来编写数学公式。

## 行内公式

行内公式使用单个美元符号包裹，例如：$E = mc^2$ 是爱因斯坦的质能方程。

另一个例子是二次方程的求根公式：$x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}$

## 块级公式

块级公式使用两个美元符号包裹，会单独成行并居中显示：

$$
\int_{-\infty}^{\infty} e^{-x^2} dx = \sqrt{\pi}
$$

这是高斯积分公式。

## 矩阵表示

$$
A =
\begin{bmatrix}
a_{11} & a_{12} & \dots & a_{1n} \\
a_{21} & a_{22} & \dots & a_{2n} \\
\vdots & \vdots & \ddots & \vdots \\
a_{m1} & a_{m2} & \dots & a_{mn}
\end{bmatrix}, \quad
B =
\begin{bmatrix}
b_{11} & b_{12} & \dots & b_{1p} \\
b_{21} & b_{22} & \dots & b_{2p} \\
\vdots & \vdots & \ddots & \vdots \\
b_{n1} & b_{n2} & \dots & b_{np}
\end{bmatrix}
$$

矩阵乘积 \(C = A B\) 为：

$$
C =
\begin{bmatrix}
\sum_{k=1}^{n} a_{1k} b_{k1} & \sum_{k=1}^{n} a_{1k} b_{k2} & \dots & \sum_{k=1}^{n} a_{1k} b_{kp} \\
\sum_{k=1}^{n} a_{2k} b_{k1} & \sum_{k=1}^{n} a_{2k} b_{k2} & \dots & \sum_{k=1}^{n} a_{2k} b_{kp} \\
\vdots & \vdots & \ddots & \vdots \\
\sum_{k=1}^{n} a_{mk} b_{k1} & \sum_{k=1}^{n} a_{mk} b_{k2} & \dots & \sum_{k=1}^{n} a_{mk} b_{kp}
\end{bmatrix}
$$

$$
\begin{bmatrix}
1 & 2 \\
3 & 4
\end{bmatrix}
\times
\begin{bmatrix}
5 & 6 \\
7 & 8
\end{bmatrix}
\;=\;
\begin{bmatrix}
? & ? \\
? & ?
\end{bmatrix}
$$

## 常用数学符号

- 求和：$\sum_{i=1}^{n} i = \frac{n(n+1)}{2}$
- 积分：$\int_{a}^{b} f(x) dx$
- 极限：$\lim_{x \to 0} \frac{\sin x}{x} = 1$
- 偏导数：$\frac{\partial f}{\partial x}$

## 复杂公式示例

$$
\nabla \cdot \mathbf{E} = \frac{\rho}{\varepsilon_0}
$$

这是麦克斯韦方程组中的第一个方程。

$$
\mathcal{L} = \frac{1}{2} (\partial_\mu \phi)^2 - \frac{1}{2} m^2 \phi^2 - \frac{\lambda}{4!} \phi^4
$$

这是标量场论的拉格朗日量。

掌握LaTeX数学公式的书写，可以让你的技术文档更加专业和清晰。
