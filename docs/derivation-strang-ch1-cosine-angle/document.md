# 点积与长度确定夹角

将非零向量归一化为 $u=v/\|v\|_2$ 与 $U=w/\|w\|_2$。旋转不改变单位向量的点积，而平面单位向量可写成 $(\cos\alpha,\sin\alpha)$，故
+
$$u\cdot U=\cos(\beta-\alpha)=\cos\theta.$$
+
代回归一化因子即得
+$\cos\theta=(v\cdot w)/(\|v\|_2\|w\|_2)$。
+
**权重：2.0。** 两个 tails 分别提供分子和尺度；新步骤是归一化并识别角差余弦。
+
> 来源：Strang, 5th ed., §1.2, pp. 15-16。
