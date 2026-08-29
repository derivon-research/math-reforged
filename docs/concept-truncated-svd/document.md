# 截断 SVD

将奇异值按 $\sigma_1\ge\cdots\ge\sigma_r>0$ 排序，只保留前 $k$ 项：
+
$$A_k=\sum_{i=1}^k\sigma_i u_i v_i^T.$$
+
所得矩阵秩至多 $k$，并保留最强的输入输出方向。

> 来源：Strang 5e, §§7.1, 7.4, pp. 365-370, 393-394。
