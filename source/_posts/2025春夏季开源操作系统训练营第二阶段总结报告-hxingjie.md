---
title: 2025春夏季开源操作系统训练营第二阶段总结报告-hxingjie
date: 2025-4-06 19:18:43
categories:
    - summary report
tags:
    - author:hxingjie
    - repo:https://github.com/LearningOS/2025s-rcore-hxingjie
---


## 一、前言

通过阅读实验指导书，我跟着操作系统的发展历程，学习了批处理系统、多道程序与分时多任务、虚拟地址空间、进程管理、文件系统、进程通信和并发等核心概念，并对rCore的实现有了更深入的认识。以下是我对这两周学习过程的总结。


## 二、学习内容

1. 搭建执行环境：

   学习了平台与目标三元组，理解了应用程序执行环境。

2. 批处理系统：

   学习了批处理系统的基本原理，包括作业调度、作业执行过程。

3. 多道程序与分时多任务：

   掌握了多道程序设计的基本概念，以及如何实现分时多任务调度。

4. 虚拟地址空间：

   理解了虚拟内存的概念，包括页表、地址映射。

5. 进程管理：

   学习了进程的管理、调度，更加深入的理解了fork+exec。

6. 文件系统：

   掌握了文件系统的基本结构，包括目录、文件。

7. 进程通信：

   学习了父子进程之间的通信机制——管道。

8. 并发：

   学习了线程管理机制的设计与实现，理解了同步互斥的实现，包括锁、信号量、条件变量。


## 三、学习心得

第二次学习rCore，加之前段时间学习xv6的经历，对rCore有了更深入的认识，包括trap的过程、地址空间的切换等，和群里同学的讨论也加深了我对代码的理解。

通过学习rCore，我对操作系统的原理有了更深入的理解，虽然考研的时候较为系统的学习了操作系统的知识，但是基本上还是停留在理论知识方面。这次rCore学习之旅，我获取PCB对进程进行操作、实现课本上学习过的系统调用、深入汇编代码理解什么是 '陷入' ，让我对操作系统的设计理念、计算机的体系结构有了具象化的认识。

在学习过程中，我也遇到了许多挑战，解决了旧问题又出现了新问题，对操作系统有了更深入的认识反而产生了更多的问题，但是我相信计算机没有魔法，多查资料多看源码一定能把疑惑解开。

两周的rCore学习之旅让我受益匪浅。通过学习rCore，我对操作系统的设计和实现有了更深刻的认识，同时也提升了我的编程技能。我相信，这些知识和经验将对我未来的学习和职业发展产生积极影响。
