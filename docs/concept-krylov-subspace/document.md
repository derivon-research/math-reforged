# Krylov 子空间

给定 $A,b$，第 k 个 Krylov 子空间为
+
$$\mathcal K_k(A,b)=\operatorname{span}\{b,Ab,\ldots,A^{k-1}b\}.$$
+
大型稀疏算法在该逐步增长空间内寻找近似解或特征向量，只需矩阵-向量乘法。

> 来源：Strang 5e, §11.3, pp. 528, 533-534。
