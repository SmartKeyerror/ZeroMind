
# ZeroMind

使用XMind记录CS的一些基础知识，项目包括`.xmind`源文件以及输出的`.pdf`文件。

----

## Index

- [LinuxAPI](#LinuxAPI)
- [数据结构](#数据结构)
- [Network](#Network)
- [设计模式](#设计模式)
- [Go语言基础](#Go语言基础)
- [Python](#Python)
- [Kubernetes基础](#Kubernetes基础)
- [MySQL](#MySQL)
- [分布式系统](#分布式系统)
- [C++基础](#C++基础)


## LinuxAPI

内容来源于《Linux-UNIX系统编程手册》以及《UNIX高级环境编程》

- UNIX-Linux历史
- [文件I/O](https://smartkeyerror.oss-cn-shenzhen.aliyuncs.com/ZeroMind/LinuxAPI/2.%20%E6%96%87%E4%BB%B6IO.pdf)
- [进程内存空间](https://smartkeyerror.oss-cn-shenzhen.aliyuncs.com/ZeroMind/LinuxAPI/3.%20%E8%BF%9B%E7%A8%8B%E5%86%85%E5%AD%98%E7%A9%BA%E9%97%B4.pdf)
- [进程的创建、执行与终止](https://smartkeyerror.oss-cn-shenzhen.aliyuncs.com/ZeroMind/LinuxAPI/4.%20%E8%BF%9B%E7%A8%8B%E7%9A%84%E5%88%9B%E5%BB%BA%E3%80%81%E6%89%A7%E8%A1%8C%E4%B8%8E%E7%BB%88%E6%AD%A2.pdf)
- [信号(01)](https://smartkeyerror.oss-cn-shenzhen.aliyuncs.com/ZeroMind/LinuxAPI/5.%20%E4%BF%A1%E5%8F%B7%2801%29.pdf)
- [信号(02)](https://smartkeyerror.oss-cn-shenzhen.aliyuncs.com/ZeroMind/LinuxAPI/6.%20%E4%BF%A1%E5%8F%B7%2802%29.pdf)
- [定时器API](https://smartkeyerror.oss-cn-shenzhen.aliyuncs.com/ZeroMind/LinuxAPI/7.%20%E5%AE%9A%E6%97%B6%E5%99%A8API.pdf)
- [线程](https://smartkeyerror.oss-cn-shenzhen.aliyuncs.com/ZeroMind/LinuxAPI/8.%20%E7%BA%BF%E7%A8%8B.pdf)
- [进程的非局部跳转](https://smartkeyerror.oss-cn-shenzhen.aliyuncs.com/ZeroMind/LinuxAPI/9.%20%E8%BF%9B%E7%A8%8B%E7%9A%84%E9%9D%9E%E5%B1%80%E9%83%A8%E8%B7%B3%E8%BD%AC.pdf)
- [标准I/O库](https://smartkeyerror.oss-cn-shenzhen.aliyuncs.com/ZeroMind/LinuxAPI/10.%20%E6%A0%87%E5%87%86IO%E5%BA%93.pdf)
- [高级I/O模型(01)](https://smartkeyerror.oss-cn-shenzhen.aliyuncs.com/ZeroMind/LinuxAPI/11.%20%E9%AB%98%E7%BA%A7IO%E6%A8%A1%E5%9E%8B%281%29.pdf)
- [高级I/O模型(02)](https://smartkeyerror.oss-cn-shenzhen.aliyuncs.com/ZeroMind/LinuxAPI/12.%20%E9%AB%98%E7%BA%A7IO%E6%A8%A1%E5%9E%8B%282%29.pdf)
- [内存映射](https://smartkeyerror.oss-cn-shenzhen.aliyuncs.com/ZeroMind/LinuxAPI/13.%20%E5%86%85%E5%AD%98%E6%98%A0%E5%B0%84.pdf)
- [Linux零拷贝](https://smartkeyerror.oss-cn-shenzhen.aliyuncs.com/ZeroMind/LinuxAPI/14.%20Linux%E9%9B%B6%E6%8B%B7%E8%B4%9D.pdf)


## 数据结构

内容来源于自己在实际应用中使用的总结，感觉数据结构其实就两种: 数组+链表

- [数组-连续排布的格子](https://smartkeyerror.oss-cn-shenzhen.aliyuncs.com/ZeroMind/DataStructure/1.%20%E6%95%B0%E7%BB%84-%E8%BF%9E%E7%BB%AD%E6%8E%92%E5%B8%83%E7%9A%84%E6%A0%BC%E5%AD%90.pdf)
- [链表-一根绳上的蚂蚱](https://smartkeyerror.oss-cn-shenzhen.aliyuncs.com/ZeroMind/DataStructure/2.%20%E9%93%BE%E8%A1%A8-%E4%B8%80%E6%A0%B9%E7%BB%B3%E4%B8%8A%E7%9A%84%E8%9A%82%E8%9A%B1.pdf)
- [实现链表-哨兵为你保驾护航](https://smartkeyerror.oss-cn-shenzhen.aliyuncs.com/ZeroMind/DataStructure/3.%20%E5%AE%9E%E7%8E%B0%E9%93%BE%E8%A1%A8-%E5%93%A8%E5%85%B5%E4%B8%BA%E4%BD%A0%E4%BF%9D%E9%A9%BE%E6%8A%A4%E8%88%AA.pdf)
- [链表-最简单的递归结构](https://smartkeyerror.oss-cn-shenzhen.aliyuncs.com/ZeroMind/DataStructure/4.%20%E9%93%BE%E8%A1%A8-%E6%9C%80%E7%AE%80%E5%8D%95%E7%9A%84%E9%80%92%E5%BD%92%E7%BB%93%E6%9E%84.pdf)
- 跳跃表-将二分查找应用于链表
- [散列表-感受数组的魅力](https://smartkeyerror.oss-cn-shenzhen.aliyuncs.com/ZeroMind/DataStructure/6.%20%E6%95%A3%E5%88%97%E8%A1%A8-%E6%84%9F%E5%8F%97%E6%95%B0%E7%BB%84%E7%9A%84%E9%AD%85%E5%8A%9B.pdf)
- [BitMap-小小的身躯蕴含着大大的能量](https://smartkeyerror.oss-cn-shenzhen.aliyuncs.com/ZeroMind/DataStructure/7.%20BitMap-%E5%B0%8F%E5%B0%8F%E7%9A%84%E8%BA%AB%E8%BA%AF%E8%95%B4%E5%90%AB%E7%9D%80%E5%A4%A7%E5%A4%A7%E7%9A%84%E8%83%BD%E9%87%8F.pdf)
- [二分搜索树-AVL的前身](https://smartkeyerror.oss-cn-shenzhen.aliyuncs.com/ZeroMind/DataStructure/8.%20%E4%BA%8C%E5%88%86%E6%90%9C%E7%B4%A2%E6%A0%91-AVL%E7%9A%84%E5%89%8D%E8%BA%AB.pdf)
- AVL树
- 红黑树
- [Trie-IDE的自动补齐可用什么结构实现](https://smartkeyerror.oss-cn-shenzhen.aliyuncs.com/ZeroMind/DataStructure/11.%20Trie-IDE%E7%9A%84%E8%87%AA%E5%8A%A8%E8%A1%A5%E9%BD%90%E5%8F%AF%E7%94%A8%E4%BB%80%E4%B9%88%E7%BB%93%E6%9E%84%E5%AE%9E%E7%8E%B0.pdf)
- [并查集-如何快速判断节点连通性](https://smartkeyerror.oss-cn-shenzhen.aliyuncs.com/ZeroMind/DataStructure/12.%20%E5%B9%B6%E6%9F%A5%E9%9B%86-%E5%A6%82%E4%BD%95%E5%BF%AB%E9%80%9F%E5%88%A4%E6%96%AD%E8%8A%82%E7%82%B9%E8%BF%9E%E9%80%9A%E6%80%A7.pdf)
- [堆-山顶的石头最有价值](https://smartkeyerror.oss-cn-shenzhen.aliyuncs.com/ZeroMind/DataStructure/13.%20%E5%A0%86-%E5%B1%B1%E9%A1%B6%E7%9A%84%E7%9F%B3%E5%A4%B4%E6%9C%80%E6%9C%89%E4%BB%B7%E5%80%BC.pdf)
- [线段树-快速求解区间问题](https://smartkeyerror.oss-cn-shenzhen.aliyuncs.com/ZeroMind/DataStructure/14.%20%E7%BA%BF%E6%AE%B5%E6%A0%91-%E5%BF%AB%E9%80%9F%E6%B1%82%E8%A7%A3%E5%8C%BA%E9%97%B4%E9%97%AE%E9%A2%98.pdf)


## Network

内容来自于《计算机网络：自顶向下方法》，《Wireshark网络分析就这么简单》以及《TCP/IP详解 卷1：协议》

- [网络分层](https://smartkeyerror.oss-cn-shenzhen.aliyuncs.com/ZeroMind/Network/1.%20%E7%BD%91%E7%BB%9C%E5%88%86%E5%B1%82.pdf)
- [数据链路层与网络层](https://smartkeyerror.oss-cn-shenzhen.aliyuncs.com/ZeroMind/Network/2.%20%E6%95%B0%E6%8D%AE%E9%93%BE%E8%B7%AF%E5%B1%82%E4%B8%8E%E7%BD%91%E7%BB%9C%E5%B1%82.pdf)
- [传输层(TCP)](https://smartkeyerror.oss-cn-shenzhen.aliyuncs.com/ZeroMind/Network/3.%20%E4%BC%A0%E8%BE%93%E5%B1%82%28TCP%29.pdf)
- [TCP拥塞控制](https://smartkeyerror.oss-cn-shenzhen.aliyuncs.com/ZeroMind/Network/4.%20TCP%E6%8B%A5%E5%A1%9E%E6%8E%A7%E5%88%B6.pdf)
- [传输层(UDP)](https://smartkeyerror.oss-cn-shenzhen.aliyuncs.com/ZeroMind/Network/5.%20%E4%BC%A0%E8%BE%93%E5%B1%82%28UDP%29.pdf)
- [应用层(HTTP)](https://smartkeyerror.oss-cn-shenzhen.aliyuncs.com/ZeroMind/Network/6.%20%E5%BA%94%E7%94%A8%E5%B1%82%28HTTP%29.pdf)
- [VXLAN](https://smartkeyerror.oss-cn-shenzhen.aliyuncs.com/ZeroMind/Network/7.%20VXLAN.pdf)
- [iptables](https://smartkeyerror.oss-cn-shenzhen.aliyuncs.com/ZeroMind/Network/8.%20iptables.pdf)


## 设计模式

- 设计原则
- [单例模式](https://smartkeyerror.oss-cn-shenzhen.aliyuncs.com/ZeroMind/DesignPattern/2.%20%E5%8D%95%E4%BE%8B%E6%A8%A1%E5%BC%8F.pdf)
- [工厂模式](https://smartkeyerror.oss-cn-shenzhen.aliyuncs.com/ZeroMind/DesignPattern/3.%20%E5%B7%A5%E5%8E%82%E6%A8%A1%E5%BC%8F.pdf)
- [建造者模式](https://smartkeyerror.oss-cn-shenzhen.aliyuncs.com/ZeroMind/DesignPattern/4.%20%E5%BB%BA%E9%80%A0%E8%80%85%E6%A8%A1%E5%BC%8F.pdf)
- [代理模式](https://smartkeyerror.oss-cn-shenzhen.aliyuncs.com/ZeroMind/DesignPattern/6.%20%E4%BB%A3%E7%90%86%E6%A8%A1%E5%BC%8F.pdf)
- [装饰器模式](https://smartkeyerror.oss-cn-shenzhen.aliyuncs.com/ZeroMind/DesignPattern/7.%20%E8%A3%85%E9%A5%B0%E5%99%A8%E6%A8%A1%E5%BC%8F.pdf)
- [适配器模式](https://smartkeyerror.oss-cn-shenzhen.aliyuncs.com/ZeroMind/DesignPattern/8.%20%E9%80%82%E9%85%8D%E5%99%A8%E6%A8%A1%E5%BC%8F.pdf)
- [观察者模式](https://smartkeyerror.oss-cn-shenzhen.aliyuncs.com/ZeroMind/DesignPattern/10.%20%E8%A7%82%E5%AF%9F%E8%80%85%E6%A8%A1%E5%BC%8F.pdf)
- [策略模式](https://smartkeyerror.oss-cn-shenzhen.aliyuncs.com/ZeroMind/DesignPattern/11.%20%E7%AD%96%E7%95%A5%E6%A8%A1%E5%BC%8F.pdf)


## Go语言基础

大部分内容源自于《Go程序设计语言》

- [程序结构](https://smartkeyerror.oss-cn-shenzhen.aliyuncs.com/ZeroMind/Go/1.%20%E7%A8%8B%E5%BA%8F%E7%BB%93%E6%9E%84.pdf)
- [基本数据类型](https://smartkeyerror.oss-cn-shenzhen.aliyuncs.com/ZeroMind/Go/2.%20%E5%9F%BA%E6%9C%AC%E6%95%B0%E6%8D%AE%E7%B1%BB%E5%9E%8B.pdf)
- [复合数据类型](https://smartkeyerror.oss-cn-shenzhen.aliyuncs.com/ZeroMind/Go/3.%20%E5%A4%8D%E5%90%88%E6%95%B0%E6%8D%AE%E7%B1%BB%E5%9E%8B.pdf)
- [函数](https://smartkeyerror.oss-cn-shenzhen.aliyuncs.com/ZeroMind/Go/4.%20%E5%87%BD%E6%95%B0.pdf)
- [方法](https://smartkeyerror.oss-cn-shenzhen.aliyuncs.com/ZeroMind/Go/5.%20%E6%96%B9%E6%B3%95.pdf)
- [接口](https://smartkeyerror.oss-cn-shenzhen.aliyuncs.com/ZeroMind/Go/6.%20%E6%8E%A5%E5%8F%A3.pdf)
- [goroutine](https://smartkeyerror.oss-cn-shenzhen.aliyuncs.com/ZeroMind/Go/7.%20goroutine.pdf)
- [goroutine的同步](https://smartkeyerror.oss-cn-shenzhen.aliyuncs.com/ZeroMind/Go/8.%20goroutine%E7%9A%84%E5%90%8C%E6%AD%A5.pdf)


## Python

内容源自于《Fluent Python》，《Python Cookbook》以及Python源码

- [Metaclass](https://smartkeyerror.oss-cn-shenzhen.aliyuncs.com/ZeroMind/Python/1.%20Metaclass.pdf)
- [Weakref](https://smartkeyerror.oss-cn-shenzhen.aliyuncs.com/ZeroMind/Python/2.%20Weakref.pdf)


## Kubernetes基础

- [Docker与Kubeadm](https://smartkeyerror.oss-cn-shenzhen.aliyuncs.com/ZeroMind/Kubernetes/1.%20Docker%E4%B8%8EKubeadm.pdf)
- [Pod](https://smartkeyerror.oss-cn-shenzhen.aliyuncs.com/ZeroMind/Kubernetes/2.%20Pod.pdf)
- [Controller](https://smartkeyerror.oss-cn-shenzhen.aliyuncs.com/ZeroMind/Kubernetes/3.%20Controller.pdf)
- [Service](https://smartkeyerror.oss-cn-shenzhen.aliyuncs.com/ZeroMind/Kubernetes/4.%20Service.pdf)
- [Kubernetes声明式API](https://smartkeyerror.oss-cn-shenzhen.aliyuncs.com/ZeroMind/Kubernetes/5.%20%E5%A3%B0%E6%98%8E%E5%BC%8FAPI.pdf)
- [Kubernetes容器网络](https://smartkeyerror.oss-cn-shenzhen.aliyuncs.com/ZeroMind/Kubernetes/6.%20Kubernetes%E5%AE%B9%E5%99%A8%E7%BD%91%E7%BB%9C.pdf)
- [Kubernetes持久化存储](https://smartkeyerror.oss-cn-shenzhen.aliyuncs.com/ZeroMind/Kubernetes/7.%20Kubernetes%E6%8C%81%E4%B9%85%E5%8C%96%E5%AD%98%E5%82%A8.pdf)
- [Informer](https://smartkeyerror.oss-cn-shenzhen.aliyuncs.com/ZeroMind/Kubernetes/8.%20Kubernetes-Informer.pdf)

## MySQL

- [ACID中的AD](https://smartkeyerror.oss-cn-shenzhen.aliyuncs.com/ZeroMind/MySQL/1.%20ACID%E4%B8%AD%E7%9A%84AD.pdf)


## 分布式系统

- [分布式系统概念](https://smartkeyerror.oss-cn-shenzhen.aliyuncs.com/ZeroMind/DistributedSystem/1.%20%E5%88%86%E5%B8%83%E5%BC%8F%E7%B3%BB%E7%BB%9F%E6%A6%82%E5%BF%B5.pdf)
- [MapReduce](https://smartkeyerror.oss-cn-shenzhen.aliyuncs.com/ZeroMind/DistributedSystem/2.%20MapReduce.pdf)
- [Raft-领导选举与日志复制](https://smartkeyerror.oss-cn-shenzhen.aliyuncs.com/ZeroMind/DistributedSystem/3.%20Raft%2801%29.pdf)
- [Raft-网络分区](https://smartkeyerror.oss-cn-shenzhen.aliyuncs.com/ZeroMind/DistributedSystem/4.%20Raft%2802%29.pdf)
- [Quorum NWR](https://smartkeyerror.oss-cn-shenzhen.aliyuncs.com/ZeroMind/DistributedSystem/5.%20Quorum%20NWR.pdf)
- [单领导者复制](https://smartkeyerror.oss-cn-shenzhen.aliyuncs.com/ZeroMind/DistributedSystem/6.%20%E5%8D%95%E9%A2%86%E5%AF%BC%E8%80%85%E5%A4%8D%E5%88%B6.pdf)


## C++基础
- [const](https://smartkeyerror.oss-cn-shenzhen.aliyuncs.com/ZeroMind/C%2B%2B/1.%20const.pdf)
