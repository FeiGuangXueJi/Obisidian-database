系统发育树是通过对不同生命物种的形态特征、遗传信息以及分子结构等进行比较，来推断它们之间进化关系的一种图表。其构建基于进化论的基本原理，即所有生命物种都起源于共同祖先，并随着时间的推移不断进化分化，形成了现在各种不同的物种。系统发育树通过分析物种之间的相似性和差异性，以及它们在进化时间轴上的分布情况，可以揭示它们之间的演化关系。
构建系统发育树通常需要三个步骤：数据收集、数据分析和数据可视化。其中，数据收集涉及到对目标物种的形态特征、遗传信息、分子结构等进行采集和记录。数据分析则是根据收集到的数据，利用生物信息学方法来推断物种之间的进化关系。常用的R包有：ggtree,  V.PhyloMaker, treeio, tidytree和ggtreeExtra等。最后，通过数据可视化技术将推断结果以树形图的形式呈现出来。
**常用的建树方法有以下几种：**  

1. 最大简约法 (maximum parsimony, MP)

MP法认为进化历程中发生碱基替代次数最少的系统发育树最符合物种进化过程。但MP法不能对长枝的平行突变进行校正，可能会得到错误的拓扑结构。

2. 最大似然法 (maximum likelihood, ML) [1]

ML法基于碱基替代模型，其原理是考虑到每个位点出现残基的似然值，将每个位置所有可能出现的残基替换概率进行累加，产生特定位点的似然值。ML法对所有可能的系统发育树都计算似然函数，似然函数值最大的树即为最优树。在进化模型选择合理的情况下，ML法与进化事实吻合最好。但其计算强度需求非常大。

3. 非加权配对算术平均法 (unweighted pair group method with arithmetic methods, UPGMA) [2]

UPGMA法十分直观简单，运算速度快，是最常用的方法。该法认为在进化过程中，每一代发生趋异的次数应一致，即碱基或氨基酸的替换速率是均等且恒等的。他的缺点在于当分子进化速率较大时，在构建过程中会引入系统误差[3]。

[1] Kolaczkowski B, Thornton JW. Performance of maximum parsimony and likelihood phylogenetics when evolution is heterogeneous. Nature. 2004 Oct 21;431(7011):980-4. doi: 10.1038/nature02917. PMID: 15496922.

[2] Limsatanun A, Pakpinyo S, Limpavithayakul K, Prasertsee T. Targeted sequencing analysis of Mycoplasma gallisepticum isolates in chicken layer and breeder flocks in Thailand. Sci Rep. 2022 Jun 14;12(1):9900. doi: 10.1038/s41598-022-14066-4. PMID: 35701517; PMCID: PMC9198072.

[3] Morrison DA. Phylogenetic tree-building. Int J Parasitol. 1996 Jun;26(6):589-617. doi: 10.1016/0020-7519(96)00044-6. PMID: 8875305.


https://mp.weixin.qq.com/s/LXq5LFhObDFDo9Z7zS1tCw
基因家族之系统发育树构建

https://mp.weixin.qq.com/s/myhe3Y2TkdqYi6j92G1ELw
R 笔记：临摹 Ecology Letter 文章的一个漂亮的系统发育树

