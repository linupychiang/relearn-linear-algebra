# Determinant（行列式）

## 引言

乘法交换律：$2 \times 3=3 \times 2$ 或 $a \times b=b \times a$

> 在矩阵中，矩阵 A 乘以矩阵 B 不等于矩阵 B 乘以矩阵 A（一般情况下）

$ \frac{1}{2}$ 表示 2 的倒数，二分之一，但在矩阵中 $\frac{1}{A}$，矩阵 A 分之一，是错误的

> 因为，在线性代数中，永远不能把一个矩阵放到分母中

0，表示一个零

> 在线性代数中，0 可以有多种表示方式
>
> 1. 数字 0
> 2. 矩阵 0
> 3. 零向量

## 解方程组

二元一次方程

$$
方程组：
\begin{cases}
5x + 6y = 7 \\
9x + 4y = 3
\end{cases}
$$

解法：一般用消元法
$ 方程组：
\begin{cases}
5x + 6y = 7 && -> \times9 && 9\times5x + 9\times6y = 9\times7\\
9x + 4y = 3 && -> \times5 && 5\times9x + 5\times4y = 5\times3
\end{cases}
$

最终可解得：
$
\begin{cases}
x = \frac{7\times4 - 6\times3}{5\times4 - 6\times9}\\
y = \frac{3\times5 - 7\times9}{5\times4 - 6\times9}\\
\end{cases}
$

## 二阶行列式

> 特点：2 行，2 列，4 个元素

例：

$
\left|
\begin{matrix}
a_{11}&a_{12}\\
a_{21}&a_{22}
\end{matrix}
\right|
$

其中：$a_{ij}$的 `i` 指行标，`j` 指列标，结果等于 $a_{11}\times a_{22}-a_{12}\times a_{21}$
>主对角线： / （左上右下）
>副对角线： / （左下右上）
