# Аксиоматическая система БСС

## Аксиома 1. Существование индивидуальных бесконечностей
Для каждого $x \in \mathbb{R}$ существует уникальный элемент $\infty_x 
otin \mathbb{R}$.

## Аксиома 2. Деление на ноль
$$rac{x}{0} = \infty_x, \quad x \in \mathbb{R}.$$

## Аксиома 3. Уникальность направлений
Если $x 
eq y$, то $\infty_x 
eq \infty_y$.

## Аксиома 4. Композиция бесконечностей
Для последовательностей оснований $\mathbf{x}=(x_1,\dots,x_m)$ и $\mathbf{y}=(y_1,\dots,y_n)$:
$$\infty_{\mathbf{x}}^{(m)} + \infty_{\mathbf{y}}^{(n)} = \infty_{(\mathbf{x},\mathbf{y})}^{(m+n)}.$$

## Аксиома 5. Абсорбция конечных чисел
$$\infty_x + r = \infty_x, \quad r \in \mathbb{R}.$$

## Аксиома 6. Умножение нулём
$$0 \cdot \infty_x = 0.$$

## Аксиома 7. Параллельность бесконечностей
Бесконечности первого порядка параллельны, если:
$$
\infty^{(1)}_x \parallel \infty^{(1)}_y
\quad \text{iff} \quad
\exists \alpha > 0,\ \beta \in \mathbb{R}:\ y = \alpha x + \beta.
$$


## Аксиома 8. Пересечение бесконечностей
$$
I\big( \infty^{(m)}_{\mathbf{x}},\ \infty^{(n)}_{\mathbf{y}} \big)
=
\begin{cases}
\infty^{(k)}_{\mathbf{z}}, & \text{если } \mathbf{z} \subseteq \mathbf{x} \text{ и } \mathbf{z} \subseteq \mathbf{y},\\[6pt]
\varnothing, & \text{иначе.}
\end{cases}
$$