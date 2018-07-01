# Genetic-Algorithm
How to use the genetic algorithm :
`targetfun.m` 修改目标函数.本例中为y=200*exp(-0.05*x).*sin(x);对于优化最大值或极大值函数问题，目标函数可以作为适应度函数
`selection.m` 新种群选择操作
`crossover.m` 新种群交叉操作
`fitnessfun.m` 计算适应度函数
`IfCroIfMut.m` 判断遗传运算是否需要进行交叉或变异
`mutation.m` 新种群变异操作
`transform2to10.m` 将2进制数转换为10进制数
****
`GAmain` 主程序
`bounds`一维自变量的取值范围
`precision`运算精度

`popsize`初始种群大小
`Generationnmax`最大代数
`pcrossover`交配概率
`pmutation`变异概率
****
绘制经过遗传运算后的适应度曲线。一般地，如果进化过程中种群的平均适应度与最大适应度在曲线上有相互趋同的形态，表示算法收敛进行得很顺利，没有出现震荡；在这种前提下，最大适应度个体连续若干代都没有发生进化表明种群已经成熟。
