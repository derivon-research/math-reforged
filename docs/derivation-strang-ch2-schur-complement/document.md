# 块消元产生 Schur 补

对 $\begin{psmallmatrix}A&B\\C&D\end{psmallmatrix}$，用 $CA^{-1}$ 倍第一块行从第二块行相减。矩阵乘法使左下块成为 $C-CA^{-1}A=0$，右下块成为 $D-CA^{-1}B$。

**权重：3.0。** 需要块形状、逆矩阵与消元顺序共同参与。

> 来源：Strang 5e, §2.4, pp. 75-76。
