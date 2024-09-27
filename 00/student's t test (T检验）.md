[一文详解t检验](https://zhuanlan.zhihu.com/p/138711532)
t检验的前提是要求样本服从正态分布或近似正态分布，不然可以利用一些变换（取对数、开根号、倒数等等）试图将其转化为服从正态分布是数据，如若还是不满足正态分布，只能利用非参数检验方法。不过当样本量大于30的时候，可以认为数据近似正态分布。

t检验最常见的四个用途：

1. 单样本均值检验（One-sample _t_-test）  
    用于检验 **总体方差未知、正态数据或近似正态的 单样本的均值 是否与 已知的总体均值相等**  
    
2. 两独立样本均值检验（Independent two-sample _t_-test）  
    用于检验 两**对独立的 正态数据或近似正态的 样本的均值 是否相等**，这里可根据总体方差是否相等分类讨论  
    
3. 配对样本均值检验（Dependent _t_-test for paired samples）  
    用于检验 **一对配对样本的均值的差 是否等于某一个值**  
    
4. 回归系数的显著性检验（t-test for regression coefficient significance）  
    用于检验 **回归模型的解释变量对被解释变量是否有显著影响**
![[一文详解t检验 - 知乎.pdf]]【【统计科普】五分钟轻松掌握三大 t 检验 - 独立样本t检验、配对样本t检验与单样本t检验】 https://www.bilibili.com/video/BV1eg411a7eh/?share_source=copy_web&vd_source=01f54932032792ace33723010055a63c