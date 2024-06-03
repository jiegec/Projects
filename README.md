---
date: 1970-01-01
---

# jiegec 的项目

受 [wangrunji0408/UndergraduateProjects](https://github.com/wangrunji0408/UndergraduateProjects) 启发，我也来总结一下。

> Q：时间都去哪儿了？
> 
> A：刚刚睡醒 什么事

## 目录

### 计算机系课程及相关作业

| 时间    | 课程                 | 项目                                                                                                                                                                    |
|---------|--------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 2017.10 | 离散数学             | [Props](#props)                                                                                                                                                         |
| 2017.11 | 程序设计基础         | [SimpleExtFs](#simpleextfs)                                                                                                                                             |
| 2018.05 | 面向对象程序设计基础 | [OnePassSynthesisDMFB](#onepasssynthesisdmfb)，[NaiveLedger](#naiveledger)                                                                                               |
| 2018.06 | 概率论与数理统计     | [HLLeBPF](#hllebpf)                                                                                                                                                     |
| 2018.07 | 程序设计小学期       | [DMCD](#dmcd)，[ChineseChess](#chinesechess)，[SearchEngine](#searchengine)                                                                                               |
| 2018.11 | 软件工程             | [Info9](#info9)                                                                                                                                                         |
| 2019.02 | 操作系统             | [rCore](#rcore)                                                                                                                                                         |
| 2019.04 | 人工智能导论         | [Pinyin](#pinyin)，[FourChess](#fourchess)，[EmotionClassifier](#emotionclassifier)                                                                                       |
| 2019.04 | 存储技术基础         | [KVEngine](#kvengine)，[HERMES](#hermes)                                                                                                                                 |
| 2019.05 | 多媒体技术基础       | [RBSplit](#rbsplit)，[MultimediaCompression](#multimediacompression)，[MultimediaSound](#multimediasound)，[MultimediaAnalysis](#multimediaanalysis)                       |
| 2019.06 | 数字逻辑设计         | [NaiveRouter](#naiverouter)，[router](#router)，[router_mb](#router_mb)，[router_ksz8795](#router_ksz8795)，[rgmiimux](#rgmiimux)                                           |
| 2019.06 | 计算机网络原理       | [Router-Lab](#Router-Lab)                                                                                                                                               |
| 2019.07 | 专业实践             | [GuGuMIPS](#gugumips)，[GuGuMIPSSoC](#gugumipssoc)，[linux-gugumips](#linux-gugumips)，[u-boot-gugumips](#u-boot-gugumips)，[ucore-gugumips](#ucore-gugumips)，[usbh](#usbh) |
| 2019.08 | Java 程序设计与训练  | [JabaHomework](#jabahomework)，[NewsApp](#newsapp)                                                                                                                       |
| 2019.08 | 汇编语言程序设计     | [asm-homework](#asm-homework)                                                                                                                                           |
| 2019.09 | 计算机网络安全技术   | [sdes-visualization](#sdes-visualization)                                                                                                                               |
| 2019.10 | 计算机组成原理       | [booth-visualization](#booth-visualization)，[integer-divide-visualization](#integer-divide-visualization)，[rocket2thinpad](#rocket2thinpad)                             |
| 2019.10 | 编译原理             | [online_tac_vm](#online_tac_vm)，[online_decaf](#online_decaf)，[gll-pg](#gll-pg)，[decaf-lsp](#decaf-lsp)，[decaf-rs-pa](#decaf-rs-pa)                                     |
| 2020.01 | 信号处理原理         | [SignalProcessing](#SignalProcessing)                                                                                                                                   |
| 2020.03 | 软件分析与验证       | [dpll](#dpll)                                                                                                                                                           |
| 2020.04 | 计算机系统结构       | [cache](#cache)，[tomasulo](#tomasulo)                                                                                                                                   |
| 2020.04 | 现代密码学           | [crypto](#crypto)，[miller-rabin](#miller-rabin)                                                                                                                         |
| 2020.05 | 网络编程技术         | [file-server](#file-server)                                                                                                                                             |
| 2021.10 | 高等计算机系统结构   | [cache-advanced](#cache-advanced)                                                                                                                                       |
| 2021.10 | 高性能计算实验       | [sgemm-optimize](#sgemm-optimize)                                                                                                                                       |

### 参加比赛的项目

| 时间    | 比赛         | 项目                                                                                                                                                                                                                                                                                                         |
|---------|--------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 2018.09 | THUCTF2018   | [ctf-writeups](#ctf-writeups)                                                                                                                                                                                                                                                                                |
| 2019.07 | 龙芯杯       | [GuGuMIPS](#gugumips)，[GuGuMIPSSoC](#gugumipssoc)，[linux-gugumips](#linux-gugumips)，[u-boot-gugumips](#u-boot-gugumips)，[ucore-gugumips](#ucore-gugumips)，[usbh](#usbh)，[nontrivial-mips](#nontrivial-mips)，[linux-nontrivial-mips](#linux-nontrivial-mips)，[u-boot-nontrivial-mips](#u-boot-nontrivialmips) |
| 2020.08 | 华为杯       | [trivialcompiler](#trivialcompiler)                                                                                                                                                                                                                                                                          |
| 2020.06 | ISC20 SCC    | [Elmerfem](#Elmerfem)                                                                                                                                                                                                                                                                                        |
| 2020.11 | SC20 VSCC    | [MemXCT](#MemXCT)，[miniVite](#miniVite)                                                                                                                                                                                                                                                                      |
| 2021.05 | ASC20-21 SCC | [PRESTO](#PRESTO)，[HPL](#HPL)                                                                                                                                                                                                                                                                                |
| 2021.07 | ISC21 SCC    | [Coding Challenge](#CodingChallenge)，[HPL](#HPL)                                                                                                                                                                                                                                                             |

### 个人参与或编写的项目

| 时间    | 内容                                                                      | 项目                                                                            |
|---------|-------------------------------------------------------------------------|---------------------------------------------------------------------------------|
| 2016.03 | MacGesture macOS 上的手势软件                                             | [MacGesture](#macgesture)                                                       |
| 2017.10 | clone-learn-tsinghua 清华网络学堂的备份工具                               | [clone-learn-tsinghua](#clone-learn-tsinghua)                                   |
| 2018.02 | cs140e Stanford CS140e 实验课程                                           | [CS140e](#cs140e)                                                               |
| 2019.02 | rustup-mirror Rustup 镜像工具                                             | [rustup-mirror](#rustup-mirror)                                                 |
| 2019.02 | thuip 从 BGP 信息中导出清华 IP 地址段                                     | [thuip](#thuip)                                                                 |
| 2019.02 | tantivy-jieba 把结巴分词用于 Tantivy                                      | [tantivy-jieba](#tantivy-jieba)                                                 |
| 2019.07 | classroom-helper GitHub Classroom 辅助 TUI                                | [classroom-helper](#classroom-helper)                                           |
| 2019.09 | verilog-format Verilog/SystemVerilog 格式化                               | [verilog-format](#verilog-format)                                               |
| 2019.10 | decode-bcbp 在线解码机票 BCBP 信息                                        | [decode-bcbp](#decode-bcbp)                                                     |
| 2020.02 | JieLabs 数字逻辑实验平台                                                  | [JieLabs](#JieLabs)                                                             |
| 2020.02 | verilog-lang 递归下降的 Verilog Parser                                    | [verilog-lang](#verilog-lang)                                                   |
| 2020.02 | maze-routing Rust 语言实现的 Grid Router 算法                             | [maze-routing](#maze-routing)                                                   |
| 2020.05 | webhookd 对 Gitlab/GitHub 的 webhook 进行响应                             | [webhookd](#webhookd)                                                           |
| 2020.05 | usbip 用 Rust 实现的 USB/IP 服务端                                        | [usbip](#usbip)                                                                 |
| 2020.06 | cluster-job-monitor 集群任务状态监测                                      | [cluster-job-monitor](#cluster-job-monitor)                                     |
| 2020.07 | netconf-rs RFC2641 NETCONF 客户端库                                       | [netconf-rs](#netconf-rs)                                                       |
| 2020.08 | TANLabs 网络原理实验平台                                                  | [TANLabs](#TANLabs)                                                             |
| 2020.09 | aws-static-website-cdk AWS CDK 部署静态网站                               | [aws-static-website-cdk](#aws-static-website-cdk)                               |
| 2020.10 | ddns 跨平台 DDNS 客户端                                                   | [ddns](#ddns)                                                                   |
| 2020.11 | machine-tester 集群机器测试工具                                           | [machine-tester](#machine-tester)                                               |
| 2020.12 | HT42B534 USB to UART 开源 PCB 设计                                        | [HT42B534USB2UART](#HT42B534USB2UART)                                           |
| 2020.12 | jieplag 代码查重软件                                                      | [jieplag](#jieplag)                                                             |
| 2021.01 | EspinalLib 使用 SpinalHDL 实现的 HDL 模块                                 | [EspinalLib](#espinnallib)                                                      |
| 2021.02 | daccountd 分布式强一致 LDAP 服务器                                        | [daccountd](#daccountd)                                                         |
| 2021.02 | minipxe 用于 PXE 的迷你 DHCP+TFTP 服务器                                  | [minipxe](#minpxe)                                                              |
| 2021.02 | wechat-dump 从 iOS 备份中导出微信聊天记录                                 | [wechat-dump](#wechat-dump)                                                     |
| 2021.03 | WM8731PMOD 音频 PMOD 扩展板                                               | [WM8731PMOD](#WM8731PMOD)                                                       |
| 2021.03 | YXPortal 实验用户管理系统                                                 | [YXPortal](#YXPortal)                                                           |
| 2021.07 | cpu-micro-benchmarks 针对 CPU 架构的微性能测试                            | [cpu-micro-benchmarks](#cpu-micro-benchmarks)                                   |
| 2021.09 | fpu-wrappers 浮点计算单元封装                                             | [fpu-wrappers](#fpu-wrappers)                                                   |
| 2021.09 | feishu-backup 飞书文档备份导出工具                                        | [feishu-backup](#feishu-backup)                                                 |
| 2021.09 | rocket-chip-vcu128 在 VCU128 开发板上运行 Rocket Chip                     | [rocket-chip-vcu128](#rocket-chip-vcu128)                                       |
| 2021.09 | dcst-facts 记录清华大学计算机系客观数据                                   | [dcst-facts](#dcst-facts)                                                       |
| 2021.10 | gitlab-cloner GitLab 项目批量克隆工具                                     | [gitlab-cloner](#gitlab-cloner)                                                 |
| 2021.12 | jtag-remote-server 远程 JTAG 调试工具                                     | [jtag-remote-server](#jtag-remote-server)                                       |
| 2022.01 | video2srt 使用云服务生成视频的字幕                                        | [video2srt](#video2srt)                                                         |
| 2022.01 | rvv-kernels 使用 RISC-V 向量扩展实现算法                                  | [rvv-kernels](#rvv-kernels)                                                     |
| 2022.07 | ifupdown-to-systemd-networkd 将 ifupdown 配置转换为 systemd-networkd 配置 | [ifupdown-to-systemd-networkd](#ifupdown-to-systemd-networkd)                   |
| 2022.09 | kicad-symbol-gen KiCad 符号生成器                                         | [kicad-symbol-gen](#kicad-symbol-gen)                                           |
| 2023.02 | china_bean_importers 将支付记录导入到 beancount                           | [china_bean_importers](#china_bean_importers)                                   |
| 2023.04 | chisel-memory-lower 转换 chisel 内存为原语                                | [chisel-memory-lower](#chisel-memory-lower)                                     |
| 2023.04 | kb 个人知识库                                                             | [kb](#kb)                                                                       |
| 2023.08 | la-inst 研究 LoongArch 指令的工具                                         | [la-inst](#la-inst)                                                             |
| 2023.10 | fatbinary 操作 CUDA fatbinary 文件格式的 Rust 库                          | [fatbinary](#fatbinary)                                                         |
| 2023.11 | data-link-protocols 网络原理数据链路层协议可视化                          | [data-link-protocols](#data-link-protocols)                                     |
| 2023.12 | unofficial-loongarch-intrinsics-guide 非官方 LoongArch Intrinsics 文档    | [unofficial-loongarch-intrinsics-guide](#unofficial-loongarch-intrinsics-guide) |
| 2023.12 | loongarch-csr 非官方 LoongArch CSR/IOCSR 文档                             | [loongarch-csr](#loongarch-csr)                                                 |
| 2023.12 | buildit AOSC 构建自动化                                                   | [buildit](#buildit)                                                             |
| 2023.12 | la_ow_ptrace 基于 PTrace 的在 LoongArch 新世界上运行旧世界程序的方案      | [la_ow_ptrace](#la_ow_ptrace)                                                   |
| 2024.02 | cold 玩具 ELF 链接器                                                      | [cold](#cold)                                                                   |

## 计算机系课程及相关作业

### Props

一个简单的对于命题的计算器。

* [GitHub](https://github.com/jiegec/props)
* 相关技术：C++，Flex，Bison
* 投入时间：很少
* 喜爱：5
* 收获：1

### SimpleExtFs

一个简单的内存文件系统，支持可持久化和一些简单的 shell 指令。

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

DMCD 是 Digital Microfluidic Chip Designer 的缩写。同样实现一个算法，按照给定的网络解一堆方程，然后用 Qt 可视化。可以在 Qt 上进行参数的调整，也可以用一个简单的遗传算法去求解。

* [GitHub](https://github.com/jiegec/codingterm/tree/master/Week1)
* 相关技术：Qt，遗传算法
* 投入时间：不多
* 喜爱：0
* 收获：0

### ChineseChess

Qt 编写的中国象棋在线对战。

* [GitHub](https://github.com/jiegec/codingterm/tree/master/Week2)
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

四字棋 AI，用 MCTS（UCT）实现。

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

第一部分是用不同的方法计算图片的 DCT，然后再逆回来对比图片质量。对比不同量化矩阵对于图片的质量的影响。第二部分是实现一个动作估计，从一系列图中捕捉一个物体的轨迹。

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

### NaiveRouter

硬件转发的路由器 IP 实现，通过 AXI 与 CPU 交互。

- [GitHub](https://github.com/jiegec/naiverouter)
- 相关技术：SystemVerilog，网络，AXI
- 投入时间：较多
- 喜爱：10
- 收获：10

### router

在黑金 AX7021 开发板上的 SoC，采用了 NaiveRouter 进行硬件转发，在 PS 上实现 RIP 协议和路由信息的更新。另外还实现了 HDMI 的路由状态可视化。

- [GitHub](https://github.com/jiegec/router)
- 相关技术：Vivado
- 投入时间：较多
- 喜爱：10
- 收获：10

### router_mb

同样在黑金 AX7021 开发板上的 SoC，也是采用 NaiveRouter 进行硬件转发，只不过把软件部分从 PS 移到了 MicroBlaze 中。

- [GitHub](https://github.com/jiegec/router_mb)
- 相关技术：Vivado
- 投入时间：不多
- 喜爱：8
- 收获：5

### router_ksz8795

在 Pynq 外接 KSZ8795 扩展板上开发的 SoC，采用 MicroBlaze 运行代码，对 KSZ8795 芯片的编程和操作进行了验证。

- [GitHub](https://github.com/jiegec/router_ksz8795)
- 相关技术：Vivado
- 投入时间：不多
- 喜爱：8
- 收获：5

### rgmiimux

一个 RGMII“一分四”的 IP，通过 VLAN 进行区分，类似 KSZ8795 的部分功能，只不过是在 FPGA 内部实现。

- [GitHub](https://github.com/jiegec/rgmiimux)
- 相关技术：Vivado
- 投入时间：不多
- 喜爱：5
- 收获：3

### Router-Lab

2019 计算机网络原理课程的实验。

- [GitHub](https://github.com/z4yx/Router-Lab)
- 相关技术：Networking
- 投入时间：较多
- 喜爱：10
- 收获：5

### GuGuMIPS

自己编写的小端 MIPS32 实现，能够启动 Linux，自己编写的 Cache 处于未完成状态。

- [GitHub](https://github.com/jiegec/GuGuMIPS)
- 相关技术：SystemVerilog
- 投入时间：很多
- 喜爱：10
- 收获：10

### GuGuMIPSSoC

以 GuGuMIPS 为 CPU，在龙芯实验箱上运行的一个 SoC，支持网络，USB，LCD 等外设

- [GitHub](https://github.com/jiegec/GuGuMIPSSoC)
- 相关技术：Vivado
- 投入时间：很多
- 喜爱：10
- 收获：10

### linux-gugumips

为 GuGuMIPS 适配的 Linux 代码，从主线内核上直接 patch，可以随时更新到最新内核。大部分代码参考了 [z4yx/linux-kernel](https://github.com/z4yx/linux-kernel)

- [GitHub](https://github.com/jiegec/linux-gugumips)
- 相关技术：Linux Kernel
- 投入时间：不多
- 喜爱：5
- 收获：3

### u-boot-gugumips

为 GuGuMIPS 适配的 U-Boot 代码，从 U-Boot 主线上 fork 而来。大部分代码参考了 [z4yx/u-boot-naivemips](https://github.com/z4yx/u-boot-naivemips)

- [GitHub](https://github.com/jiegec/u-boot-gugumips)
- 相关技术：U-Boot
- 投入时间：不多
- 喜爱：5
- 收获：3

### ucore-gugumips

为 GuGuMIPS 适配的 uCore 代码，只在外设方面做了微小的改动。

- [GitHub](https://github.com/jiegec/ucore-gugumips)
- 相关技术：Kernel
- 投入时间：很少
- 喜爱：3
- 收获：1

### usbh

USB 2.0 FS 控制器，从 UltraEmbedded USB Host Controller 修改而来，并且打包为了 Vivado IP。对应的驱动在上面的 Linux 和 U-Boot 仓库中。

- [GitHub](https://github.com/jiegec/usbh)
- 相关技术：Hardware
- 投入时间：很多
- 喜爱：10
- 收获：10

### JabaHomework

Java OJ 上的作业外加考试。

- [GitHub](https://github.com/jiegec/jaba-homework)
- 相关技术：Java
- 投入时间：很少
- 喜爱：1
- 收获：1

### NewsApp

Java 大作业，一个简单的新闻 App。

- [GitHub](https://github.com/qyz-thu/NewsApp)
- 相关技术：Java，Android
- 投入时间：很少
- 喜爱：1
- 收获：1

### asm-homework

汇编小学期的作业，包括小作业和两次实验的代码。

- [GitHub](https://github.com/jiegec/asm-homework)
- 相关技术：汇编，x86，MIPS
- 投入时间：很少
- 喜爱：5
- 收获：1

### sdes-visualization

对 S-DES 加密过程的可视化。

- [GitHub](https://github.com/jiegec/sdes-visualization)
- 相关技术：Elm，CSS
- 投入时间：很少
- 喜爱：10
- 收获：3

### booth-visualization

对 Booth 乘法过程的可视化。

- [GitHub](https://github.com/jiegec/booth-visualization)
- 相关技术：Elm
- 投入时间：很少
- 喜爱：10
- 收获：3

### integer-divide-visualization

对整数除法过程的可视化，非课程要求。

- [GitHub](https://github.com/jiegec/integer-divide-visualization)
- 相关技术：Elm
- 投入时间：很少
- 喜爱：10
- 收获：3

### rocket2thinpad

把 Rocket Chip 运行在 Thinpad 上。

- [GitHub](https://github.com/jiegec/rocket2thinpad)
- 相关技术：Verilog，Vivado，Rocket Chip，Chisel，Scala
- 投入时间：不多
- 喜爱：10
- 收获：7

### online_tac_vm

在线的 TAC 虚拟机，可以在线执行编译原理 PA3 生成的 TAC。

- [GitHub](https://github.com/jiegec/online_tac_vm)
- 相关技术：Rust，Yew
- 投入时间：很少
- 喜爱：10
- 收获：3

### online_decaf

在线的 Decaf 编译器，可以在线运行编译原理的 PA。

- [GitHub](https://github.com/jiegec/online_decaf)
- 相关技术：Rust，Yew
- 投入时间：很少
- 喜爱：10
- 收获：3

### gll-pg

一个 GLL 的 Parser Generator，参考了 MashPlant/lalr1 和 GLL 论文。

- [GitHub](https://github.com/jiegec/gll-pg)
- 相关技术：Rust，Proc macro，Parsing
- 投入时间：不多
- 喜爱：10
- 收获：10

### decaf-lsp

Decaf 语言的 LSP Server 实现，支持 Hover、Symbol 等功能，配合 [decaf-vscode](https://github.com/jiegec/decaf-vscode) 使用。

- [GitHub](https://github.com/jiegec/decaf-lsp)
- 相关技术：Rust，LSP，VSCode
- 投入时间：不多
- 喜爱：10
- 收获：10

### decaf-rs-pa

编译原理的 PA，基于 @MashPlant 的 Rust 框架。

- [GitHub](https://github.com/jiegec/decaf-rs-pa)
- 相关技术：Rust
- 投入时间：不多
- 喜爱：5
- 收获：5

### SignalProcessing

信号处理原理课程的实验。

- [GitHub](https://github.com/jiegec/SignalProcessing)
- 相关技术：信号处理
- 投入时间：较少
- 喜爱：3
- 收获：3

### dpll

软件分析与验证课程的实验。要求实现 DPLL 算法来解决 SAT 问题。

- [GitHub](https://github.com/jiegec/dpll)
- 相关技术：C++
- 投入时间：不多
- 喜爱：5
- 收获：3

### cache

计算机系统结构课程的实验。模拟一个 Cache 的行为。

- [GitHub](https://github.com/jiegec/cache)
- 相关技术：C++
- 投入时间：很少
- 喜爱：1
- 收获：1

### tomasulo

计算机系统结构课程的实验。实现 Tomasulo 算法。

- [GitHub](https://github.com/jiegec/tomasulo)
- 相关技术：C++
- 投入时间：不多
- 喜爱：1
- 收获：1

### crypto

现代密码学课程的实验。要求实现几个密码学算法。

- [GitHub](https://github.com/jiegec/crypto)
- 相关技术：密码学
- 投入时间：较少
- 喜爱：5
- 收获：5

### miller-rabin

现代密码学课程的实验。要求实现 Miller-Rabin 算法。

- [GitHub](https://github.com/jiegec/miller-rabin)
- 相关技术：密码学
- 投入时间：很少
- 喜爱：3
- 收获：3

### file-server

网络编程技术课程的实验。要求实现支持上传和下载的文件服务器和配套的客户端。

- [GitHub](https://github.com/jiegec/file-server)
- 相关技术：网络编程
- 投入时间：很少
- 喜爱：2
- 收获：2

### cache-advanced

高等计算机系统结构课程的实验。和本科生课实验类似。

- [GitHub](https://github.com/jiegec/cache-advanced)
- 相关技术：C
- 投入时间：很少
- 喜爱：0
- 收获：0

### sgemm-optimize

高性能计算实验课程的实验，在 Kunpeng 平台上优化 SGEMM。

- [GitHub](https://github.com/jiegec/sgemm-optimize)
- 相关技术：OpenMP, MPI
- 投入时间：较多
- 喜爱：8
- 收获：8

## 个人参与或编写的项目

### MacGesture

高中时候接手的一个项目，在 macOS 上进行手势识别，然后执行相应的动作。

* [GitHub](https://github.com/MacGesture/MacGesture)
* 相关技术：Objective-C
* 投入时间：不多
* 喜爱：3
* 收获：2

### clone-learn-tsinghua

清华网络学堂的备份工具。用于毕业生的资料归档。

* [GitHub](https://github.com/jiegec/clone-learn-tsinghua)
* 相关技术：TypeScript
* 投入时间：不多
* 喜爱：8
* 收获：1

### CS140e

大一寒假的时候，Stanford CS140e 首次做出了用 Rust 写操作系统作为实验课程的尝试，我也跟着做了。

* [GitHub](https://github.com/jiegec/cs140e)
* 相关技术：Rust，操作系统
* 投入时间：较多
* 喜爱：10
* 收获：10

### rustup-mirror

把 rustup 同步到本地的工具，用于 TUNA 等镜像站。

- [GitHub](https://github.com/jiegec/rustup-mirror)
- 相关技术：Rust
- 投入时间：不多
- 喜爱：10
- 收获：3

### classroom-helper

为“实验物理的大数据方法”课程编写的工具，配合 GitHub Classroom 使用的工具，自动批量 clone 作业仓库，并且执行脚本进行评分，显示代码更改历史。

- [GitHub](https://github.com/jiegec/classroom-helper)
- 相关技术：Rust，TUI
- 投入时间：不多
- 喜爱：10
- 收获：3

### verilog-format

一个简单的 Verilog / SystemVerilog 格式化工具。未完成，勿用。

- [GitHub](https://github.com/jiegec/verilog-format)
- 相关技术：Rust，Nom，Parsing
- 投入时间：不多
- 喜爱：10
- 收获：5

### JieLabs

数字逻辑实验平台，远程操作 FPGA 和一些元件。

- [GitHub](https://github.com/thu-cs-lab/JieLabs-Web)
- 相关技术：React、Rust、WebSocket、Buildroot
- 投入时间：很多
- 喜爱：10
- 收获：10

### webhookd

一个用于处理 webhook 消息并执行操作的服务。支持 Gitlab 和 GitHub。

- [GitHub](https://github.com/jiegec/webhookd)
- 相关技术：Rust
- 投入时间：不多
- 喜爱：10
- 收获：3

### usbip

运行一个 USB/IP 服务，可以模拟设备或者转发到 libusb。

- [GitHub](https://github.com/jiegec/usbip)
- 相关技术：Rust
- 投入时间：不多
- 喜爱：10
- 收获：8

### TANLabs

网络原理实验平台，包含 CI 自动评测，树莓派评测等功能。

- 相关技术：React、Rust、S3、SQS
- 投入时间：很多
- 喜爱：10
- 收获：10

### HT42B534USB2UART

一个 USB 2 UART 板子，采用的芯片是 HT42B534。

- [GitHub](https://github.com/jiegec/HT42B534USB2UART)
- 相关技术：KiCad、JLC
- 投入时间：不多
- 喜爱：10
- 收获：10

### daccountd

基于 etcd 编写的 LDAP 服务器。

- [GitHub](https://github.com/jiegec/daccountd)
- 相关技术：Go、Etcd
- 投入时间：不多
- 喜爱：10
- 收获：10

### WM8731PMOD

一个 PMOD 接口的扩展板，上有 WM8731 芯片用于音频处理。

- [GitHub](https://github.com/jiegec/WM8731PMOD)
- 相关技术：LCEDA、JLC
- 投入时间：不多
- 喜爱：10
- 收获：10

### YXPortal

一个简单的 OAuth 客户端 + 服务端，用于实验系统的用户认证。

- 相关技术：Go、Elm
- 投入时间：不多
- 喜爱：10
- 收获：8

## 未完待续
