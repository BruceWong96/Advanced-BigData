# Hadoop

## Overview

Hadoop可运行于一般的商用服务器上，具有高容错、高可靠性、高扩展性等特点。

特别适合写一次，读多次的场景。

### 适合

- 大规模数据
- 流式数据（写一次，读多次）

### 不适合

- 低延时的数据访问
- 大量的小文件
- 频繁修改文件（基本就是写 1 次）

### Hadoop 架构

![Hadoop 架构](Picture/Hadoop-Architecture.png)

- HDFS: 分布式文件存储
- YARN: 分布式资源管理
- MapReduce: 分布式计算
- Others: 利用YARN的资源管理功能实现其他的数据处理方式

内部各个节点基本都是采用Master-Woker架构