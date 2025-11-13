# Алгебра операций в БСС

## 1. Бесконечности n-порядка
Для последовательности $\mathbf{x}=(x_1,\dots,x_n)$:
$$\infty_{\mathbf{x}}^{(n)}.$$

## 2. Сложение
$$\infty_{\mathbf{x}}^{(m)} + \infty_{\mathbf{y}}^{(n)} = \infty_{(\mathbf{x},\mathbf{y})}^{(m+n)}.$$

## 3. Скалярное умножение
$$\lambda \cdot \infty_{\mathbf{x}}^{(n)} = \infty_{\lambda \mathbf{x}}^{(n)}.$$

## 4. Тензорное умножение
$$\infty_{\mathbf{x}}^{(m)} \otimes \infty_{\mathbf{y}}^{(n)} = 
\infty_{\mathbf{x}\otimes\mathbf{y}}^{(mn)}.$$

## 5. Матрицы бесконечностей
Матрица:
$$
\mathbf{A} =
\begin{pmatrix}
\infty^{(k_{11})}_{\mathbf{x}_{11}} & \cdots & \infty^{(k_{1n})}_{\mathbf{x}_{1n}} \\
\vdots & \ddots & \vdots \\
\infty^{(k_{m1})}_{\mathbf{x}_{m1}} & \cdots & \infty^{(k_{mn})}_{\mathbf{x}_{mn}}
\end{pmatrix}
$$

Умножение:
$$
(AB)_{ij} = \sum_{k=1}^{p} \Big( A_{ik} \otimes B_{kj} \Big)
$$