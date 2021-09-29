# Presto架构、源码分析专栏

## 一、原理、架构
- [Presto概述：特性、原理、架构](https://zhuanlan.zhihu.com/p/260399749)    2020-10
- [分布式SQL查询引擎Presto原理介绍](http://armsword.com/2017/12/05/presto/)    2017-12
- [深入理解Presto](https://zhuanlan.zhihu.com/p/101366898)    2020-01
- [分布式SQL查询引擎原理（以Presto SQL为例）](https://zhuanlan.zhihu.com/p/293775390)    2020-11
- [深入理解Presto,Presto的内部架构](https://mayunlei.github.io/2020/08/16/%E6%B7%B1%E5%85%A5%E7%90%86%E8%A7%A3Presto-Presto%E7%9A%84%E5%86%85%E9%83%A8%E6%9E%B6%E6%9E%84/)    2020-08
- [Presto 分布式SQL查询引擎及原理分析](https://mp.weixin.qq.com/s?__biz=MzI5MDEzMzg5Nw==&mid=2660400264&idx=1&sn=ebff65980ef45f7dffea1e5ec7d51fdc&chksm=f7425e6ec035d778dcc5704babe5241d8c80f3d21059434b00d8d4c46d9ce0bd232467ec92a6&scene=21#wechat_redirect)    2020-05





## 二、源码分析

### 2.1 前期准备
- [如何快速掌握Presto源码：思路和经验](https://zhuanlan.zhihu.com/p/262236892)    2020-10
- [Presto 源码阅读： Overview](https://zhuanlan.zhihu.com/p/51393518)    2018-12
- [Presto的一些基本概念](http://armsword.com/2018/08/11/the-basic-concepts-of-presto/)    2018-08
- [Presto/Trino权威指南及官方设计文档解读](https://www.jianshu.com/p/d3600d2a115d)    2021-05


### 2.2 数据类型、Query Execution Model
- [Presto类型系统初探](https://zhuanlan.zhihu.com/p/55299409)    2019-01
- [Presto源码分析之数据类型](https://zhuanlan.zhihu.com/p/52713533)    2018-12
- [Presto Core Data Structures: Slice, Block & Page](https://zhuanlan.zhihu.com/p/60813087)    2019-03
- [Presto源码分析之Slice](https://zhuanlan.zhihu.com/p/52735465)    2018-12
- [Presto Driver,Split and Pipeline](https://www.lewuathe.com/presto-driver,split-and-pipeline.html)    2017-05


### 2.3 SQL解析、执行计划生成与优化
- [Presto 源码分析：Coordinator 篇](https://www.infoq.cn/article/VNe0A9yKszPCmp32akCa)    2019-12
- [Presto SQL Parser源码分析](https://zhuanlan.zhihu.com/p/57438825)    2019-02
- [Presto 源码阅读：Optimizers](https://zhuanlan.zhihu.com/p/52154130)    2019-01
- [Presto逻辑执行计划生成](https://zhuanlan.zhihu.com/p/57395047)    2019-02
- [Presto源码分析之IterativeOptimizer](https://zhuanlan.zhihu.com/p/52879375)    2018-12
- [Presto源码分析之模式匹配](https://zhuanlan.zhihu.com/p/52916774)    2018-12
- [Presto技术源码解析总结-一个SQL的奇幻之旅 上](https://www.jianshu.com/p/3fccfa82e1ec)    2019-04
- [Presto技术源码解析总结-一个SQL的奇幻之旅 下](https://www.jianshu.com/p/d8a3d7488358)    2019-04
- [Presto查询执行过程和索引条件下推分析](https://mp.weixin.qq.com/s?src=11&timestamp=1616394200&ver=2961&signature=E7fzfl-wO5wGpohLLkE8v9hRKn5GR1TbVwU-N6Hl11T0Xl6TtlgCbhJmisPs*Z-hYiprO0yYK91O5GR0m-V-s5kvv6NudfeWMGW4iPXdAdetAfDAo4EITB9l*yZajiJS&new=1)    2020-05


### 2.4 分布式任务调度、split生成与调度策略、worker选择策略
- [Presto运行时浅析](https://zhuanlan.zhihu.com/p/345733460)    2021-01
- [Presto源码阅读——如何获取Hive中的Metadata(HMS+HDFS)](https://blog.csdn.net/huang_quanlong/article/details/80380474)    2018-07
- [Presto如何构建和使用海量Hive Splits](https://zhuanlan.zhihu.com/p/344559757)    2021-01
- [Presto之Task执行框架](https://zhuanlan.zhihu.com/p/54172313)    2019-01
- [Presto 是如何 schedule task 的?](https://zhuanlan.zhihu.com/p/58959725)    2019-03
- [Presto 由Stage到Task的旅程](https://zhuanlan.zhihu.com/p/55785284)    2019-01
- [Presto调度task选择Worker方法](http://armsword.com/2020/04/08/presto-scheduling-task/)    2020-04
- [presto中的AllAtOnce与Phased](https://zhuanlan.zhihu.com/p/61656233)    2019-05
- [Presto 任务调度： 任务分配到哪里](https://mayunlei.github.io/2020/05/30/Presto-%E4%BB%BB%E5%8A%A1%E8%B0%83%E5%BA%A6%EF%BC%9A-%E4%BB%BB%E5%8A%A1%E5%88%86%E9%85%8D%E5%88%B0%E5%93%AA%E9%87%8C/)    2020-05
- [Presto Split 详解](https://blog.csdn.net/zhanyuanlin/article/details/109215177)


### 2.5 常用Operator分析、常用SQL底层实现原理
- [Window函数与WindowOperator源码解析](https://zhuanlan.zhihu.com/p/59550902)    2019-03
- [Presto中coalesce函数的实现与Expression Codegen](https://zhuanlan.zhihu.com/p/64131496)    2019-04
- [Presto Limit 类算子分析](https://zhuanlan.zhihu.com/p/62448395)    2019-04
- [Presto分页功能概述](https://zhuanlan.zhihu.com/p/57030465)    2019-02

#### join、shuffle
- [Presto 数据如何进行shuffle](https://zhuanlan.zhihu.com/p/61565957)    2019-04
- [Presto中的Hash Join](https://zhuanlan.zhihu.com/p/54731892)    2019-03

#### 分组聚合
- [Presto中的分组聚合查询流程](https://zhuanlan.zhihu.com/p/54385845)    2019-01
- [深入理解Presto中的Group By查询](https://zhuanlan.zhihu.com/p/67742519)    2019-09


### 2.6 Function、UDF



### 2.7 Connector机制、常用Connector分析
- [ORC & Presto](https://zhuanlan.zhihu.com/p/110013789)    2020-02
- [Presto ORC及其性能优化](http://armsword.com/2019/09/30/presto-orc-and-performance-optimization/)    2019-09
- [Presto Hive MetaStore相关代码分析](https://zhuanlan.zhihu.com/p/109033118)    2020-02
- [Presto Connector之SystemTable](https://zhuanlan.zhihu.com/p/60934739)    2019-03
- [如何让Presto可以连接Hbase？文中含Hbase-Connect开发详解](https://www.analysys.cn/article/detail/20019023)    2018-11


### 2.8 其他
- [Presto源码分析之TupleDomain](https://zhuanlan.zhihu.com/p/53113638)    2018-12
- [Presto的缓存机制](https://zhuanlan.zhihu.com/p/196398077)    2020-08
- [Presto Caching](https://zhuanlan.zhihu.com/p/147769024)    2020-06
- [Presto Codegen简介与优化尝试](https://zhuanlan.zhihu.com/p/53469238)    2018-12
- [Presto Procedure](https://zhuanlan.zhihu.com/p/59159147)    2019-03
- [How is data inserted into Presto?](https://zhuanlan.zhihu.com/p/59846328)    2019-03
- [Presto兼容Hive SQL的一些改造工作](http://armsword.com/2019/03/31/presto-compatible-hive-syntax/)    2019-03
- [Presto Coordinator分布式改造](https://mayunlei.github.io/2019/11/26/Presto-Coordinator%E5%88%86%E5%B8%83%E5%BC%8F%E6%94%B9%E9%80%A0/)    2019-11
- [Visualize Execution Plan in Presto](https://www.lewuathe.com/visualize-execution-plan-in-presto.html)    2019-09
- [Presto兼容Hive隐式类型转换](https://mp.weixin.qq.com/s/1hn3nVBdBtBeiPl3wxvHfQ)    2021-02
- [Presto 标量函数注册和调用过程简述](https://mp.weixin.qq.com/s/vd65OVeIOH7YFQ0QOAmsUg)    2020-09
- [Presto 函数实现简述](https://mp.weixin.qq.com/s/1Z_qik61N3hKwWqG8QR69w)    2020-07
- [Improved Hive Bucketing](https://trino.io/blog/2019/05/29/improved-hive-bucketing.html)




## 三、相关论文
- [官方论文《Presto: SQL on everything》](https://trino.io/Presto_SQL_on_Everything.pdf)    [中文翻译](https://www.jianshu.com/p/de0a1de9f26e)
- [《F1 Query: Declarative Querying at Scale》读后感](https://zhuanlan.zhihu.com/p/53299556)    2018-12
- [《Column-Stores vs. Row-Stores》读后感](https://zhuanlan.zhihu.com/p/54433448)    2019-01    abei-知乎
- [读后感之《Column-Stores vs. Row-Stores》](https://zhuanlan.zhihu.com/p/54484592)    2019-01    萌豆-知乎
- [Wander Join:Online Aggregation via Random Walks读后感](https://zhuanlan.zhihu.com/p/55050773)    2020-03
- [《The Snowflake Elastic Data Warehouse》读后感](https://zhuanlan.zhihu.com/p/55577067)    2019-01


















