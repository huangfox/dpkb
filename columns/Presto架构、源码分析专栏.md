# Presto架构、源码分析专栏

## 1）原理、架构
- [Presto概述：特性、原理、架构](https://zhuanlan.zhihu.com/p/260399749)    2020-10
- [Presto的一些基本概念](http://armsword.com/2018/08/11/the-basic-concepts-of-presto/)    2018-08
- [分布式SQL查询引擎Presto原理介绍](http://armsword.com/2017/12/05/presto/)    2017-12
- [深入理解Presto](https://zhuanlan.zhihu.com/p/101366898)    2020-01
- [分布式SQL查询引擎原理（以Presto SQL为例）](https://zhuanlan.zhihu.com/p/293775390)    2020-11







## 2）源码分析

### 源码分析思路、方法论
- [如何快速掌握Presto源码：思路和经验](https://zhuanlan.zhihu.com/p/262236892)    2020-10
- [Presto 源码阅读： Overview](https://zhuanlan.zhihu.com/p/51393518)    2018-12


### 数据类型、Query Execution Model
- [Presto类型系统初探](https://zhuanlan.zhihu.com/p/55299409)    2019-01
- [Presto源码分析之数据类型](https://zhuanlan.zhihu.com/p/52713533)    2018-12
- [Presto Core Data Structures: Slice, Block & Page](https://zhuanlan.zhihu.com/p/60813087)    2019-03
- [Presto源码分析之Slice](https://zhuanlan.zhihu.com/p/52735465)    2018-12


### SQL解析、执行计划生成与优化
- [Presto SQL Parser源码分析](https://zhuanlan.zhihu.com/p/57438825)    2019-02
- [Presto 源码阅读：Optimizers](https://zhuanlan.zhihu.com/p/52154130)    2019-01
- [Presto逻辑执行计划生成](https://zhuanlan.zhihu.com/p/57395047)    2019-02
- [Presto源码分析之IterativeOptimizer](https://zhuanlan.zhihu.com/p/52879375)    2018-12
- [Presto源码分析之模式匹配](https://zhuanlan.zhihu.com/p/52916774)    2018-12


### 分布式任务调度、split生成与调度策略、work选择策略
- [Presto之Task执行框架](https://zhuanlan.zhihu.com/p/54172313)    2019-01
- [Presto如何构建和使用海量Hive Splits](https://zhuanlan.zhihu.com/p/344559757)    2021-01
- [Presto 是如何 schedule task 的?](https://zhuanlan.zhihu.com/p/58959725)    2019-03
- [Presto 由Stage到Task的旅程](https://zhuanlan.zhihu.com/p/55785284)    2019-01
- [Presto调度task选择Worker方法](http://armsword.com/2020/04/08/presto-scheduling-task/)    2020-04
- [presto中的AllAtOnce与Phased](https://zhuanlan.zhihu.com/p/61656233)    2019-05
- [Presto运行时浅析](https://zhuanlan.zhihu.com/p/345733460)    2021-01


### 数据shuffle机制
- [Presto 数据如何进行shuffle](https://zhuanlan.zhihu.com/p/61565957)    2019-04


### 常用Operator分析、常用SQL底层实现原理
- [Window函数与WindowOperator源码解析](https://zhuanlan.zhihu.com/p/59550902)    2019-03
- [Presto中coalesce函数的实现与Expression Codegen](https://zhuanlan.zhihu.com/p/64131496)    2019-04
- [Presto Limit 类算子分析](https://zhuanlan.zhihu.com/p/62448395)    2019-04
- [Presto分页功能概述](https://zhuanlan.zhihu.com/p/57030465)    2019-02
### join相关
- [Presto中的Hash Join](https://zhuanlan.zhihu.com/p/54731892)    2019-03
### 分组聚合
- [Presto中的分组聚合查询流程](https://zhuanlan.zhihu.com/p/54385845)    2019-01
- [深入理解Presto中的Group By查询](https://zhuanlan.zhihu.com/p/67742519)    2019-09


### 常用Connector分析、ORC、Parquet
- [ORC & Presto](https://zhuanlan.zhihu.com/p/110013789)    2020-02
- [Presto ORC及其性能优化](http://armsword.com/2019/09/30/presto-orc-and-performance-optimization/)    2019-09
- [Presto Hive MetaStore相关代码分析](https://zhuanlan.zhihu.com/p/109033118)    2020-02
- [Presto Connector之SystemTable](https://zhuanlan.zhihu.com/p/60934739)    2019-03


### 其他
- [Presto源码分析之TupleDomain](https://zhuanlan.zhihu.com/p/53113638)    2018-12
- [Presto的缓存机制](https://zhuanlan.zhihu.com/p/196398077)    2020-08
- [Presto Caching](https://zhuanlan.zhihu.com/p/147769024)    2020-06
- [Presto Codegen简介与优化尝试](https://zhuanlan.zhihu.com/p/53469238)    2018-12
- [Presto Procedure](https://zhuanlan.zhihu.com/p/59159147)    2019-03
- [How is data inserted into Presto?](https://zhuanlan.zhihu.com/p/59846328)    2019-03







## 3）最佳实践、调优
- [Presto兼容Hive SQL的一些改造工作](http://armsword.com/2019/03/31/presto-compatible-hive-syntax/)    2019-03
- [Presto的ETL之路](https://zhuanlan.zhihu.com/p/53996153)    2019-01
- [Presto的应用场景与企业案例](https://zhuanlan.zhihu.com/p/260653669)    2020-10
### 性能调优
- [Presto性能调优的五大技巧](https://zhuanlan.zhihu.com/p/162809568)    2020-07


### 内存调优
- [Presto内存管理原理和调优](http://armsword.com/2018/05/22/the-memory-management-and-tuning-experience-of-presto/)    2018-05
- [Presto内存管理相关参数设置](http://armsword.com/2019/11/13/the-configuration-settings-of-presto-memory-management/)    2019-11
- [Presto集群内存不足时保护机制](http://armsword.com/2020/02/18/presto-memory-kill-policy/)    2020-02


### 技术选型
- [PrestoDB VS PrestoSQL发展比较](https://zhuanlan.zhihu.com/p/87621360)    2019-10
- [PrestoDB和PrestoSQL比较及选择](http://armsword.com/2020/05/02/the-difference-between-prestodb-and-prestosql/)    2020-05




## 4）问题排查（踩坑）
- [说下那些导致Presto查询变慢的JVM Bug和解决方法](http://armsword.com/2021/02/07/jvm-bug-causes-Presto-queries-to-slow-down/)    2021-02
- [Presto Master JVM Core问题调研](http://armsword.com/2020/12/10/solve-presto-jvm-coredump/)    2020-12
- [Jetty导致Presto堆外内存泄露的排查过程](http://armsword.com/2020/06/23/jetty-cause-presto-memory-leak/)    2020-06
- [记一次Presto Worker OOM的查找过程](http://armsword.com/2020/06/03/the-solution-of-presto-oom-caused-by-orc-statistics/)    2020-06
- [Presto System load过高问题调研](http://armsword.com/2019/09/18/solve-presto-system-load-too-high/)    2019-09
- [一次 Presto 的连接数超限的问题定位](https://zhuanlan.zhihu.com/p/57956341)    2019-03
- [Presto Codegen问题排查案例](https://zhuanlan.zhihu.com/p/66243773)    2019-05







## 5）相关论文
- [官方论文《Presto: SQL on everything》](https://trino.io/Presto_SQL_on_Everything.pdf)    [中文翻译](https://www.jianshu.com/p/de0a1de9f26e)
- [《F1 Query: Declarative Querying at Scale》读后感](https://zhuanlan.zhihu.com/p/53299556)    2018-12
- [《Column-Stores vs. Row-Stores》读后感](https://zhuanlan.zhihu.com/p/54433448)    2019-01    abei-知乎
- [读后感之《Column-Stores vs. Row-Stores》](https://zhuanlan.zhihu.com/p/54484592)    2019-01    萌豆-知乎
- [Wander Join:Online Aggregation via Random Walks读后感](https://zhuanlan.zhihu.com/p/55050773)    2020-03
- [《The Snowflake Elastic Data Warehouse》读后感](https://zhuanlan.zhihu.com/p/55577067)    2019-01








## 6）技术博客、专栏
- [Presto知乎专栏](https://www.zhihu.com/column/presto-cn)
- [若飞-技术博客](http://armsword.com/archives/)





## 7）书籍
- 《Presto: The Definitive Guide》
- 《Presto技术内幕》    京东Presto团队




## 8）其他
- [Presto Meetup Oct 2019](https://zhuanlan.zhihu.com/p/88350254)    2019-10
- [惊闻Facebook开源大数据引擎Presto团队正在分裂](https://zhuanlan.zhihu.com/p/55628236)    2019-01