# jiegec 的本科项目

受 [wangrunji0408/UndergraduateProjects](https://github.com/wangrunji0408/UndergraduateProjects) 启发，我也来总结一下。

> Q：时间都去哪儿了？
>
> A：刚刚睡醒 什么事

## 目录

### 计算机系课程作业

| 时间    | 课程                 | 项目                                                         |
| ------- | -------------------- | ------------------------------------------------------------ |
| 2017.10 | 离散数学             | [Props](#Props)                                              |
| 2017.11 | 程序设计基础         | [SimpleExtFs](#SimpleExtFs)                                  |
| 2018.5  | 面向对象程序设计基础 | [OnePassSynthesisDMFB](#OnePassSynthesisDMFB)，[NaiveLedger](#NaiveLedger) |
| 2018.6  | 概率论与数理统计     | [HLLeBPF](#HLLeBPF)                                          |
| 2018.7  | 程序设计小学期       | [DMCD](#DMCD)，[ChineseChess](#ChineseChess)，[SearchEngine](#SearchEngine) |
| 2018.11 | 软件工程             | [Info9](#Info9)                                              |
| 2019.2  | 操作系统             | [rCore](#rCore)                                              |
| 2019.4  | 人工智能导论         | [Pinyin](#Pinyin)，[FourChess](#FourChess)，[EmotionClassifier](#EmotionClassifier) |
| 2019.4  | 存储技术基础         | [KVEngine](#KVEngine)，[HERMES](#HERMES)                     |
| 2019.5  | 多媒体技术基础       | [RBSplit](#RBSplit)，[MultimediaCompression](#MultimediaCompression)，[MultimediaSound](#MultimediaSound)，[MultimediaAnalysis](#MultimediaAnalysis) |
| 2019.8  | Java程序设计与训练   | [JabaHomework](#JabaHomework)                                |

### 个人项目

| 时间   | 内容                     | 项目                      |
| ------ | ------------------------ | ------------------------- |
| 2016.3 | macOS 上的手势软件       | [MacGesture](#MacGesture) |
| 2018.2 | Stanford CS140e 实验课程 | [CS140e](#CS140e)         |

## 计算机系课程作业

### Props

一个简单的对于命题的计算器。

* [GitHub](https://github.com/jiegec/props)
* 相关技术：C++，Flex，Bison
* 投入时间：很少
* 喜爱：5
* 收获：1

### SimpleExtFs

一个简单的内存文件系统，支持可持久化和一些简单的shell指令。

* [GitHub](https://github.com/jiegec/extfs)
* 相关技术：C，FS
* 投入时间：很少
* 喜爱：3
* 收获：1

### OnePassSynthesisDMFB

DMFB 是 Digital MicroFluidic Biochips 的缩写。需要实现一篇文章里的算法，生成 SAT 规则后丢给 z3 求解，再把结果可视化。

* [GitHub](https://github.com/jiegec/OnePassSynthesisDMFB)
* 相关技术：C++，Graphviz，Z3，SAT
* 投入时间：不多
* 喜爱：0
* 收获：2

### NaiveLedger

一个简单的 AlgoRand 实现。

* 合作同学：wjd jl lxy lwb
* GitHub 未公开
* 相关技术：C++，密码学
* 投入时间：一般
* 喜爱：1
* 收获：2

### HLLeBPF

把 HyperLogLog 用 eBPF 实现了，可以估计一段时间内访问本机的 IP 数量。

* [GitHub](https://github.com/jiegec/hll_ebpf)
* 相关技术：C，eBPF，HyperLogLog
* 投入时间：很少
* 喜爱：5
* 收获：3

### DMCD

DMCD 是 Digital Microfluidic Chip Designer 的缩写。同样实现一个算法，按照给定的网络解一堆方程，然后用Qt可视化。可以在Qt上进行参数的调整，也可以用一个简单的遗传算法去求解。

* [GitHub](https://github.com/jiegec/codingterm/tree/master/Week1)
* 相关技术：Qt，遗传算法
* 投入时间：不多
* 喜爱：0
* 收获：0

### ChineseChess

Qt 编写的中国象棋在线对战。

*  [GitHub](https://github.com/jiegec/codingterm/tree/master/Week2)
* 相关技术：Qt，Socket
* 投入时间：不多
* 喜爱：2
* 收获：2

### SearchEngine

用 Python 编写爬虫，并实现简单的搜索引擎。

* [GitHub](https://github.com/jiegec/codingterm/tree/master/Week3)
* 相关技术：Python，Django，Web，Reverse Index，TF-IDF，ORM
* 投入时间：不多
* 喜爱：2
* 收获：2

### Info9

用 Vue.js 编写前端，Python Django 编写后端，实现一堆功能的网站。

* 合作同学：xlq wxp
* GitHub 未公开
* 相关技术：Vue，Python，Django，Web，MongoDB
* 投入时间：>100h
* 喜爱：5
* 收获：10

### rCore

完善用 Rust 编写的操作系统。

* 合作同学：太多了
* [GitHub](https://github.com/rcore-os/rCore)
* 相关技术：Rust，操作系统，文件系统，网络
* 投入时间：>200h
* 喜爱：10
* 收获：100

### Pinyin

用 Rust 实现的基于马尔可夫链的输入法。

* [GitHub](https://github.com/jiegec/pinyin)
* 相关技术：Rust，马尔可夫链
* 投入时间：不多
* 喜爱：1
* 收获：1

### FourChess

四字棋AI，用MCTS（UCT）实现。

* [GitHub](https://github.com/jiegec/FourChess)
* 相关技术：MCTS，UCT
* 投入时间：不多
* 喜爱：1
* 收获：2

### EmotionClassifier

用 CNN/RNN/MLP 实现一个分类任务。

* [GitHub](https://github.com/jiegec/EmotionClassifier)
* 相关技术：PyTorch
* 投入时间：不多
* 喜爱：0
* 收获：0

### KVEngine

实现一个简单的 KV 引擎，保证 Write Consistency 和 Crash Consistency。

* [GitHub](https://github.com/jiegec/kv-engine)
* 相关技术：C++，WAL
* 投入时间：不多
* 喜爱：3
* 收获：4

### HERMES

实现一个 FUSE 文件系统，背后采用 KV 来存储数据。

* 合作同学：csq gj lxy
* [GitHub](https://github.com/Harry-Chen/HERMES)
* 相关技术：C++，FUSE
* 投入时间：不多
* 喜爱：5
* 收获：5

### RbSplit

把图片的颜色拆开，然后错位后再拼在一起，变成一个新的图。

* [GitHub](https://github.com/jiegec/rbsplit)
* 相关技术：Python
* 投入时间：很少
* 喜爱：3
* 收获：1

### MultimediaCompression

第一部分是用不同的方法计算图片的 DCT ，然后再逆回来对比图片质量。对比不同量化矩阵对于图片的质量的影响。第二部分是实现一个动作估计，从一系列图中捕捉一个物体的轨迹。

* [GitHub](https://github.com/jiegec/MultimediaCompression)
* 相关技术：Python
* 投入时间：不多
* 喜爱：5
* 收获：10

### MultimediaSound

用 MATLAB 的 STRAIGHT 工具箱进行声音的调整，例如男声->女生。然后用 Python 衡量声音之间的距离。

* [GitHub](https://github.com/jiegec/MultimediaSound)
* 相关技术：Python，MATLAB
* 投入时间：不多
* 喜爱：5
* 收获：5

### MultimediaAnalysis

计算每个图的颜色分布立方图，根据立方图来进行聚类计算。

* [GitHub](https://github.com/jiegec/MultimediaAnalysis)
* 相关技术：Python
* 投入时间：很少
* 喜爱：4
* 收获：4

### JabaHomework

Java OJ 上的作业外加考试。

- [GitHub](https://github.com/jiegec/jaba-homework)
- 相关技术：Java
- 投入时间：很少
- 喜爱：1
- 收获：1

## 个人项目

### MacGesture

高中时候接手的一个项目，在 macOS 上进行手势识别，然后执行相应的动作。

* [GitHub](https://github.com/MacGesture/MacGesture)
* 相关技术：Objective-C
* 投入时间：不多
* 喜爱：3
* 收获：2

### CS140e

大一寒假的时候，Stanford CS140e 首次做出了用 Rust 写操作系统作为实验课程的尝试，我也跟着做了。

* [GitHub](https://github.com/jiegec/cs140e)
* 相关技术：Rust，操作系统
* 投入时间：较多
* 喜爱：10
* 收获：10

## 未完待续
