---
title: Summary of 2024s-rcore 2nd stage  -- Rust for OS
date: 2024-05-19 15:58:49
categories:
    - <catogory>
tags:
    - author:<ldq3>
    - repo:https://github.com/LearningOS/2024s-rcore-ldq3
---

Rust 具有安全和高效的特性，这使得它有希望被用于构建更好的操作系统

# 操作系统
在计算机的分层体系结构中，操作系统位于软件和硬件的分界处

操作系统的职责是帮助用户程序管理计算机硬件，这基于 CPU 提供 ISA 实现（在本次实验过程中，具体是 RISC-V）

操作系统的职责可以被进一步细分为几个方面——虚拟化、并发、持久性和驱动（和外部设备的通信）

在第二阶段，我们并没有太多的关于驱动的内容。虚拟化考虑如何在有限的硬件资源上为多个软件提供相互隔离的服务，并发考虑如何控制软件对共享资源的使用、持有性主要指文件系统

操作系统称得上是人类所设计的最复杂的一类程序，在这里你几乎能用上计算机中的所有知识

# To Be Continue
这篇简短的博客作为2024春夏季开源操作系统训练营第二阶段的总结，我在其中简单概述了我对 Rust 用于构建操作系统的理解

因为我所学尚浅，且没有足够的实践经历，导致以上内容十分简略，甚至可能有不少错误

我并不希望这些内容就这样简短的结束并被掩埋和遗忘，所以我将在[我的个人博客](https://ldq3.github.io/)上持续更新我对使用 Rust 编写 OS 的理解