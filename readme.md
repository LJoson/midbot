# 灵魂画手

## 结构
现在市面上有很多结构的写字机，而我要介绍的是经典的corexy结构的写字机。该写字机是基于T站上一个开源[写字机项目](https://www.thingiverse.com/thing:2587684).其结构如图：

![](https://imgconvert.csdnimg.cn/aHR0cHM6Ly9sal9ldmFuLmdpdGVlLmlvL2ltZy9wcm9qZWN0cy9taWRib3QvMS5qcGc?x-oss-process=image/format,png)
<br/>
一般的corexy十字架构写字机两个电机是分开，其不好的一点就是太占空间，而midbot将两个控制电机集中在了中间，极大节省了空间。
另外想补充的是在我diy的过程中也发现几点可改进的地方
 - （1）底部支撑：不稳，容易倒
- （2）舵机抬笔：卡同步带地方易断裂,可以控制填充度，不易断裂或者改结构

## 工具
T站上控制主板多是esp32以及arduino nano,我使用的是arduino uno+cnc sheild控制器，控制算法就是经典的GRBL，网络上也有在stm32上移植grbl,我还没有实现，后面实现了进行补充。


所有资料获取：[https://github.com/LJoson/midbot](https://github.com/LJoson/midbot)
