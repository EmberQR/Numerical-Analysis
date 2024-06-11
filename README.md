# Numerical-Analysis
一个数值分析脚本，用来计算一些常用的函数。
- 求用近似值a来近似精确值b的有效数字位数：`EffectiveDigits[a,b]`
- 统计顺序Gauss消去法的乘除法计算次数：`GaussN[n]`，n为线性方程组的未知数个数
- LU分解：`LUDe[M]`，返回{L,U}，L为单位下三角矩阵，U为上三角矩阵
- Cholesky分解：`ChDe[M]`，接收一个矩阵M，把M分解为一个下三角矩阵G和其转置 G^T的乘积，即 M=GG^T，返回G
- 判定是否为正定矩阵：`PositiveDefiniteMatrixQ[A]`
- 求各阶顺序主子式：`PrincipalMinors[A]`
- 三对角矩阵的Crout分解（效率更快，只能用于三对角矩阵）：`CroutDe[A]`，返回一个下三角矩阵和一个单位上三角矩阵
- 普通矩阵的Crout分解：`CroutDeCo[A]`，返回一个下三角矩阵和一个单位上三角矩阵
- 向量或矩阵的范数：`Norm[A,p]`，p可以为1,2,Infinity,"Frobenius"（F-范数）
- 求矩阵的谱半径：`PBJ[A]`
- 求矩阵的p条件数：`Cond[A,p]`
- 求Jacobi迭代法的迭代矩阵：`Jacobi[A]`
- 求GS迭代法的迭代矩阵：`GS[A]`
- 判定矩阵是否严格对角占优：`IsStrictlyDiagonallyDominant[A]`
- 求SOR方法的迭代矩阵：`SOR[A,w]`，w为松弛因子
- QR分解：`QRDecomposition[M]`，返回一个正交矩阵和一个上三角矩阵

效果如图所示：
![image](https://github.com/EmberQR/Numerical-Analysis/assets/135571263/ef0ec4e0-2727-4828-b1ca-f43d03397dc3)

请先计算笔记本，然后在脚本下面的代码区域使用上述函数。
