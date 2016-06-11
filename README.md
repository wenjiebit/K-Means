# K-Means
针对全班37个人(N)，每人4门课程成绩(T)，利用K-Means算法将其分成4类(K)


算法介绍
========

* 从N个文档随机选取K个文档作为质心
* 对剩余的每个文档测量其到每个质心的距离，并把它归到最近的质心的类
* 重新计算已经得到的各个类的质
* 迭代2～3步直至新的质心与原质心相等或小于指定阈值，算法结束


数据结构
========

![image](https://github.com/thanatoskira/K-Means/blob/master/K-Means数据结构.jpg)


Note
=======

* 20150701

    * 存在的缺陷: <br>
        在数据结构上写的过于复杂了，Cluster可以直接使用Score替代，从而Flag也可以省去，ptr可以不经过Flag的判断直接初始化，IsClustOk()函数处写的过于复杂，可以自行修改(本文仅作为参考)

* 20150721

    * 代码已经重新修整
