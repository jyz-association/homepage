---
title: 基于jiangyi-boolean实现的薛定墨的狗模型
date: 2020-03-31 15:26:11
tags: AprilFoolsDay
category: Science
---

摘要：jiangyi-boolean是一个通过伪随机的数学方法产生布尔型的模块。通过jiangyi-boolean，借助Isotope单片机，我们实现了一个24线程并发通过产生随机布尔型值来决定姜懿真生死的物理模型。通过最高可达86GHz的处理频率对姜懿真进行认为干涉，我们得出了这一逻辑模型，即薛定墨的狗。 

<!--more-->

# 薛定墨的狗实验的实现过程

我们将实验分为三个组进行。对于每一个实验组，通过创造某种绿色植物和红色的建筑物，以及在长度约为3华尺的木制结构和*Diospyros Kaki* Thunb的植株下通过某种声波干涉jiangyi-boolean的随机布尔型值生成，进行观测，将三个实验组的结果求算术平均值，得出了以下实验数据：

|干涉强度（0~10）|观测后的存活率|
|-|-|
|0||
|1|77%|
|2|29%|
|3|0%|
|4|17%|
|5|64%|
|6|98%|
|7|88%|
|8|43%|
|9|4%|
|10|8%|

数据表明，在对姜懿真不加干涉的情况下，无法得知其存活情况，对姜懿真进行不同强度的干涉，得到不同的存活率，对数据进行建模分析，发现可以使用于轩函数的图像拟合。

![Graph](https://pic.downk.cc/item/5e833b70504f4bcb043d8091.jpg)

干涉强度与存活率在定义域内的关系式如下：

$$
y=k\cos(x)+m
$$

其中$k=0.502, m=0.499$.

至此，我们得出了在薛定墨的狗模型中，干涉强度与存活率的函数关系。

# 引用

[1]Crindzebra.jiangyi-boolean[OL].[https://npmjs.com/package/jiangyi-boolean](https://npmjs.com/package/jiangyi-boolean)