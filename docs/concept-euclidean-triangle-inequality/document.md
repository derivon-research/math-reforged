# 欧几里得三角不等式

对任意 $v,w\in\mathbb R^n$，

$$
\|v+w\|_2\leq \|v\|_2+\|w\|_2.
$$

展开平方长度并应用 Cauchy-Schwarz：

$$
\begin{aligned}
\|v+w\|_2^2
&=\|v\|_2^2+2v\cdot w+\|w\|_2^2\\
&\leq(\|v\|_2+\|w\|_2)^2.
\end{aligned}
$$

两边非负，开平方即得结论。几何上，直接沿 $v+w$ 到达终点不会比先走 $v$ 再走 $w$ 更长。等号发生在两个向量同向或其中一个为零时。

> 来源：Strang, 5th ed., §1.2, p. 16 and Problem 1.2.21, p. 20。
