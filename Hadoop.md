# Hadoop 从入门到进阶
Hadoop自2006年诞生以来，经过10年的发展，已经成为大数据领域生态最为成熟的解决方案，本次课程覆盖了Hadoop系统最重要几个方面 包括如何配置单机Hadoop系统，高级集群配置，使用分布式 文件系统，开发基于Hadoop MapReduce的复杂应用程序，Hadoop批量处理 和查询工具Pig/Hive。 我们还会介绍主流的商业化的Hadoop系统，以及成熟的云计算 平台Amazon Cloud和Ali Cloud 对于Hadoop的支持。 最后介绍Hadoop领域的最新进展，包括大数据系统监管，云计算，大数据，IOT的应用融合


# 大数据介绍
  - 大数据特性
  - Hadoop发展历史
  - 主流大数据处理技术以及适用场景
  - Hadoop / Spark 


# Hadoop介绍
## 本节目标
  - 了解Hadoop的适用范围
  - 了解Hadoop如何采用自己的方式解决这些问题


# Hadoop 适用范围
  - Hadoop是大规模分布式批处理基础设施
  - Hadoop处理的数据量的规模，多大？
  - 大规模系统的挑战
  - 摩尔定律

# Hadoop解决大数据问题方法
  - 其他大数据处理技术比较
  - 数据分布
  - MapReduce 隔离的处理过程
  - 线性扩展

# Hadoop 核心技术 分布式文件系统HDFS
## 本节目标
  - Hadoop 分布式文件系统(HDFS)架构，以及如何同分布式系统的概念相关联
  - 如何通过命令行安装和使用HDFS
  - 如何在应用程序中使用HDFS存储和读取数据


# 分布式文件系统基础
  - NFS
  - HDFS

# 配置使用HDFS
  - 分布式文件系统集群配置
  - 启动HDFS文件系统
  - 同HDFS文件系统交互
  - 从HDFS获取数据
  - 关闭HDFS文件系统
  - 文件系统健康检查

# HDFS安全管理

# 计算模型MapReduce
## 本节目标
  - 理解MapReduce函数式编程范式
  - 理解MapReduce执行流程
  - 了解如何为Hadoop MapReduce编写程序

# MapReduce 基础
  - 函数式编程概念
  - 列表处理
  - Mapping 过程
  - Reducing 过程
  - 整合　Mapping / Reducing
  - Word Count示例
 

# MapReduce 数据流
  - 理解MapReduct数据流
  - MapReduce 便利工具
  - 容错处理


# MapReduce实用技巧

  - 链式任务处理
  - Troubleshooting: 调试 MapReduce
  - MapReduce任务监控，管理


# MapReduce 高阶内容
## 本节目标
  - 理解Hadoop高级特性
  - 在公有云平台使用Hadoop (Amazon EC2 / S3)

# 定制数据类型
  - Writable 类型
  - Custom Key 类型
  - 使用定制数据类型
  - 快速比较操作
    

# 输入数据格式
  - 定制文件格式
  - 数据源选择
    
# 输出数据格式
  - 数据分区
  - 用户定制关键指标汇报
  - 使用亚马逊Web Services


# 生产环境部署Hadoop实务

## Hadoop安装
  - Java 版本需求Requirements
  - 操作系统需求
  - 下载安装Hadoop
  - 重要目录介绍

## 服务器选型
  - 集群配置
  - 小规模: 2-10 节点
  - 中等规模: 10-40 节点
    大型集群: 多机架

## 性能监控
  - Ganglia
  - Nagios
  - Ambari


# Apache Hadoop Pig
## 本节目标
  - 介绍Hadoop　数据自动化处理脚本工具

# 通过脚本语言自动化数据处理
  - Pig 核心特征介绍
  - Pig 主要应用场景介绍
  - Pig 组件介绍
  - Pig 工作原理简介　　　

# Apache Hive
## 本节目标
  - 介绍基于分布式系统的数据仓库Hive 查询和管理海量数据集

# Hive介绍
  - 为什么需要新的数据仓库系统
  - Hive应用场景
  - Hive主要组件介绍
  - Hive查询语言
  - SQL vs NoSQL
  - Hive在Facebook中的应用



# Hadoop商用解决方案
## 本节目标
  - 比较主流基于开源方案的Hadoop系统，以及企业在选择商业方案时主要考量

## 商用解决方案
  - Cloudera
  - MapR
  - HortonWorks
  - Apache Hadoop
  - 商用方案综合比较


# Hadoop在主流互联网巨头的应用
##本节目标
  - 了解Hadoop相关技术对互联网业务的支持

# 应用场景
  - 产品发展策略的数据支持
  - 推荐系统
  - 广告定向与优化
  - 文本分析工具
  - 监控与运维工具


# Hadoop 最新进展
## 本节目标
  - 了解Hadoop领域的最新进展，包括Hadoop在云端部署，物联网的融合，了解企业级的安全监管技术

# Apache Atlas 开源大数据监管技术
  - 数据分类
  - 集中审计
  - 搜索，浏览
  - 安全策略引擎

# AliYun MaxCompute 介绍
# Amazon EMR Cluster　介绍
# Hadoop 与Iot


# Hadoop实验室
  - 搭建MapReduce实验环境
  - 定制分区
  - Counter　案例
  - Combiner 适用场景实验

# Hadoop 学习资源汇总