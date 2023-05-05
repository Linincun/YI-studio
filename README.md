## 逸工作室训练手册

- [逸工作室训练手册](#逸工作室训练手册)
  - [前言](#前言)
  - [目标](#目标)
  - [如何学习？](#如何学习)
  - [如何训练](#如何训练)
  - [其他](#其他)
  - [写在最后](#写在最后)

### 前言
最近了解到有些新同学对自己在如何开始走上算法竞赛这条路有些迷茫，我想编写这篇文章，借此与你们分享一下我有限的一些经验。

### 目标
在开始学习之前，有一个目标是自己能不能在这条路上坚持走下去的关键。对于在大一就了解到算法竞赛的各位同学们来说，我想罗勇军老师在《算法竞赛》一书中的目标就很合理。

> * 初学者。一名刚学过C/C++、Java、Python 中任意一门编程语言的学生，做了一些编程题目，建立了编码的兴趣，对进一步学习有信心和动力，希望有一本介绍算法竞赛知识点的书指导学习，这本书的初级部分正适合他，帮助他了解基础算法知识点、学习模板代码、练习基础题。经过这样的学习后，他很可能获得蓝桥杯省赛三等奖，甚至更好。不过，他仍没有获得ICPC、CCPC铜奖的能力。
> * 中级队员。中级队员顺利地跨过了初学者阶段，他证明自己已经走上了成为杰出程序员的道路。中级队员符合这样的画像：精通编程语言，编码得心应手；他做过几百道基础算法题，并且准备继续对算法竞赛倾心投入；他有了志同道合、水平相当的队友一起学习进步；他遇到了学习瓶颈，计算思维还不够；他只能做简单题和一些中等题，对难题无从下手。中级队员可能获得蓝桥杯省赛二等奖、一等奖，也差不多有ICPC、CCPC铜奖的水平。本书的中级部分能帮助他进一步掌握算法知识、提高算法思维能力、练习较难的题目。
> * 高级队员。他们获得了蓝桥杯国赛二等奖或一等奖，以及ICPC、CCPC 银牌或金牌。这些奖牌是“高级队员”的标签，他们已经足够被称为“出色的程序员”，在就业市场上十分抢手。本书的高级部分能帮助他们进一步扩展知识点，增强计算思维。

同学们可以自我定位一下，自己现在是初级队员、中级队员还是高级队员？我的建议是，如果是从大学入学起接触算法，对于一个比较勤奋的同学来说，在大二达到中级队员，大三达到高级队员，是比较合理的。~~可惜的是，我个人接触算法比较晚，也没那么勤奋（悲）。~~

### 如何学习？
算法竞赛知识点又多又杂，我该从哪里学起呢？实际上这个可以在网上找到许多的资源。在放那些东西之前，我先给大家看看23年蓝桥杯考试范围。

Tips：以下范围中标*的部分只限于 C/C++研究生组、C/C++大学 A 组、Java 研究生组、Java 大学 A 组。

计算机算法：枚举、排序、搜索、计数、贪心、动态规划、图论、数论、博弈论*、概率论*、计算几何*、字符串算法等。

数据结构：数组、对象/结构、字符串、队列、栈、树、图、堆、平衡树/线段树、复杂数据结构*、嵌套数据结构*等。

大家可以先从这些着手学起！

* 学习资源
  * [OI WIKI](https://oi-wiki.org/)
    OI所需算法概览，可以当做索引使用。
  * [在这里可以找到一些书](https://github.com/acm-clan/algorithm-stone)
    实际上一些书在工作室都有，工作室成员可以在爱惜的前提下借阅，非常推荐**跟着一本书，结合网络资源的学习方式！！**

我建议大家先学一些简单的知识点，边学边刷题，以下是我总结的一些个人认为比较适合先学的一些算法，大家可以根据知识点找网络上的资源学习。

* 基础算法
  * 前缀和、差分
  * 二分
  * 双指针
  * 递推
  * 离散化
* 搜索与图论
  * DFS
  * BFS
  * 最短路
    * Dijkstra
    * BellmanFord
    * SPFA
    * Floyd
  * 拓扑排序
  * 最小生成树
    * Prim
    * Kruskal
  * 最近公共祖先
  * 二分图
  * 并查集
* 字符串
  * Trie树
  * KMP
* 基础数据结构
* 数论
  * 筛质数
  * 分解质因数
  * 求约数、求约数个数、求约数和
  * GCD与LCM
  * 试除法判断质数
  * 快速幂
  * 求组合数
  * n进制与n进制转换
* 动态规划：
  * 线性DP
  * 数位统计DP
  * 状态压缩DP
  * 区间DP
  * 树形DP

我相信如果你能把上面的知识学完，那么你对算法竞赛的理解一定不亚于我了，~~我算哪根葱啊喂~~。你可以根据自己的经验进一步学习，在刷题中成长。

### 如何训练

学了这么多，我该去哪里练习呢？这些我之前也在群里发过，你可以看看OI Wiki的这个页面

[学习资源](https://oi-wiki.org/contest/resources/)

下面是我比较推荐的、适合我校学子水平的！
* [codeforces](https://codeforces.com)
  * 可以做一下里面的比赛，从div3和div2的第一题做起
* [牛客](https://ac.nowcoder.com/acm/home)
  * 牛客有小白月赛等很多比赛可以做。还可以做做别的学校的校赛同步赛等等。~~你甚至可以在小白月赛中抽到奖品~~
* [ACWing](https://www.acwing.com/)
  * Acwing每周有周赛，赛后有讲解，y总也会经常讲一些题，可以白嫖到大量的课程资源。还有一些价格便宜的活动，比如一块钱的每日一题，每天都会有讲解，可以参加一下。
* [洛谷](https://www.luogu.com.cn/)
  * 洛谷主要面向搞OI的初高中生，但是其中大量的题库值得一看，并且里面有不错的社区氛围。
* [Vjudge](https://vjudge.net/)
  * 可以将这个网站当做中介评测其他网站的题目，还是非常方便的。

### 其他

如果你的英语不错，或者对英语很感兴趣，那么我强烈建议你作为一名CS专业生不要局限在中文互联网中。你可以用[谷歌](https://www.google.com/)替代百度，[Stackoverflow](http://stackoverflow.com)替代百度知道（或者CSDN，不过CSDN在一些基础性问题上还是很有参考价值的），[维基百科](http://en.wikipedia.org)替代百度百科（最好是英文维基百科）。~~至于如何更快的访问这些网站，非常抱歉但是这不在我的分享范围之内~~

说回到算法竞赛，如果你们想以英文课程入门算法的话，我觉得[UCB CS61B](https://sp18.datastructur.es/)是一门值得推荐的课程。在CS领域，前沿技术和优质资源基本都要去国际互联网上检索，~~说实话我很后悔我没有早点知道这个道理~~

### 写在最后

关于本文章，我希望这能作为面向逸工作室新成员的指引，以后如果你们学有所成，可以向我提交pull request，让这个文章更加完善。