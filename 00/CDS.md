
[基因_序列_中的一些名词区别（_CDS_、Exon、Intron、UTR、ORF、启动子、TF等）](https://zhuanlan.zhihu.com/p/557609219)
 **CDS**（coding sequences）它就是与蛋白序列一一对应的DNA序列，并且序列中间不存在其他与蛋白无关的序列，和真实情况最接近。

ORF：理论上的氨基酸编码区，一般是在分析DNA核酸图谱中（主要是利用电脑程序）得到的。程序会自动在DNA序列中寻找启动因子（ATG或AUG），然后按每3个核酸一组，一直延伸寻找下去，直到碰到终止因子（TAA或TAG）。程序把这个区域当成ORF区，认为理论上可以编码一组氨基酸。但问题是，在一个整体核酸序列中寻找ATG并不靠谱。因为寻找到的ATG很可能是两个氨基酸编码片段的尾和头的混合体。

比如AACGCATGCAGC序列

如果以T为中心，会有三种编码组合的可能。即：

（1）ATG（T在中心）电脑程序发现的启动因子的组合

（2）CAT（T在最右侧）

（3）TGC（T在最左侧）本例中实际核酸编码的组合。

这就是ORF三种框架的来源。实际上，DNA序列可以按六种框架阅读和翻译（每条链三种，双链对应六种不同的三联密码子）。

所以，我们说ORF只是理论上的编码区，与真实的情景可能并不一样。