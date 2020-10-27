# Hadoop-HDFS

## 简介

HDFS = Hadoop Distributed File System，分布式文件系统，简而言之，就是文件太多，不能放在一台机器上，所以分到很多机器上进行存储。其实还有很关键的一点——高可用，存放在多台机器上可以设置副本，这样，当一台机器宕机后，数据不会丢失，因为其他机器上还存在副本。

## 架构

![HDFS 架构](../Picture/HDFS-Architecture.png)