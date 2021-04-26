# DPKB
大数据相关文章汇总（知识库）
持续更新中（2021-04）





## 一、开源组件

### HDFS


### YARN
- [Hadoop YARN 在滴滴离线与实时计算中的应用](https://blog.didiyun.com/index.php/2018/12/11/hadoop-yarn/)    2018-12


### Hive
- [HiveCube在有赞的实践](https://tech.youzan.com/cube/)    2019-07
- [Hive Metastore Federation 在滴滴的实践](https://blog.didiyun.com/index.php/2019/03/25/hive-metastore-federation/)    2019-03



### Presto、Trino

#### 1）官网、社区、博客
- [PrestoDB 官网](https://prestodb.io/)
- [Trino 官网](https://trino.io/)     原PrestoSql
- [Google Presto Group](https://groups.google.com/g/presto-users)
- [Presto知乎专栏](https://www.zhihu.com/column/presto-cn)
- [若飞-技术博客](http://armsword.com/archives/)


#### 2）大厂实践
- [Presto在车好多的实践](https://mp.weixin.qq.com/s/Bmqv54sVZgTqQ82I_RfmsA)    2020-12
- [Presto在滴滴的探索与实践](https://zhuanlan.zhihu.com/p/266162270)    2020-10
- [Presto 在有赞的实践之路](https://tech.youzan.com/presto-zai-you-zan-de-shi-jian-zhi-lu/)    2020-04
- [PrestoCon 2020：云原生数据湖分析DLA的Presto实践](https://zhuanlan.zhihu.com/p/260784762)    2020-03
- [携程 Presto 技术演进之路](https://zhuanlan.zhihu.com/p/41538472)    2018-08
- [Presto实现原理和美团的使用实践](https://tech.meituan.com/2014/06/16/presto.html)    2014-06


#### 3）专栏
- [Presto架构、源码分析专栏](columns/Presto架构、源码分析专栏.md)
- [Presto最佳实践、调优、踩坑专栏](columns/Presto最佳实践、调优、踩坑专栏.md)
- [Presto资料汇总、会议资讯专栏](columns/Presto资料汇总、会议资讯专栏.md)





### Spark
- [SparkSQL 在有赞的实践](https://tech.youzan.com/sparksql-in-youzan/)    2019-01
- [SparkSQL 在有赞大数据的实践（二）](https://tech.youzan.com/sparksql-in-youzan-2/)    2020-01







### Flink
#### 1）官网、社区、博客
- [Flink官网](https://flink.apache.org/)
- [Flink Blog](https://flink.apache.org/blog/)
- [Ververica Blog](https://www.ververica.com/blog?hsLang=en) 
- [Ververica 中文](https://ververica.cn/developers-resources/)
- [Flink 知识图谱](https://ververica.cn/wp-content/uploads/2020/03/Apache-Flink-Stateful-Computations-over-Data-Streams.pdf)


#### 2）教程推荐
- [ververica - flink-sql-cookbook](https://github.com/ververica/flink-sql-cookbook/)
- [Flink零基础入门](columns/Flink零基础入门.md)
- [Flink进阶教程](columns/Flink进阶教程.md)
- [Apache Flink 漫谈系列](columns/Apache%20Flink%20漫谈系列.md)


#### 3）专栏
- [Flink架构、源码分析专栏](columns/Flink架构、源码分析专栏.md)
- [Flink开源项目汇总](columns/Flink开源项目汇总.md)
- [Flink实战系列](columns/Flink实战系列.md)









### Kudu
- [Kudu官网](https://kudu.apache.org/)

- [分布式存储系统Kudu与HBase的简要分析与对比](https://sq.163yun.com/blog/article/198870236065431552)    2018-11






### HBase
- [HBase Bulkload 实践探讨](https://tech.youzan.com/hbase-bulkloadshi-practice/)    2019-12




### ClickHouse

- [ClickHouse 在有赞的实践之路](https://tech.youzan.com/clickhouse-zai-you-zan-de-shi-jian-zhi-lu/)    2021-01



### Calcite
- [Calcite官网](http://calcite.incubator.apache.org/)
- [Apache Calcite 处理流程详解（一）](https://matt33.com/2019/03/07/apache-calcite-process-flow/)    2019-03
- [Apache Calcite 优化器详解（二）](https://matt33.com/2019/03/17/apache-calcite-planner/)    2019-03
- [SQL解析在美团的应用](https://tech.meituan.com/2018/05/20/sql-parser-used-in-mtdp.html)    2018-05





## 二、大数据应用

### 大数据架构
- [SQL on Hadoop 在快手大数据平台的实践与优化](https://www.infoq.cn/article/BN9cJjg1t-QSWE6fqkoR)    2019-06
- [携程机票大数据架构最佳实践](https://dbaplus.cn/news-73-1420-1.html)    2017-08







### 数仓相关
- [有赞数据仓库实践之路](https://tech.youzan.com/dw-in-youzan/)    2020-03
- [OneData建设探索之路：SaaS收银运营数仓建设](https://tech.meituan.com/2019/10/17/meituan-saas-data-warehouse.html)    2019-10
- [有赞指标库实践](https://tech.youzan.com/you-zan-zhi-biao-ku-shi-jian/)    2020-03
- [有赞BI平台实现原理](https://tech.youzan.com/principle-on-bi-platform/)    2021-01







### 数据治理、数据资产
- [美团配送数据治理实践](https://tech.meituan.com/2020/03/12/delivery-data-governance.html)    2020-03
- [全链路数据治理在网易严选的实践](https://www.infoq.cn/article/FOV6aEWRGNOfhD91YVcr)    2020-10
- [数据资产、数据治理 - 有赞](https://tech.youzan.com/shu-ju-zi-chan-zan-zhi-zhi-li/)    2019-11
- [浅谈有赞大数据安全体系](https://tech.youzan.com/you-zan-da-shu-ju-an-quan-ti-xi-jian-she-shi-jian/)    2021-01
- [有赞数据仓库元数据系统实践](https://tech.youzan.com/youzan-metadata/)    2018-08
- [饿了么元数据管理实践之路](https://dbaplus.cn/news-73-2143-1.html)    2018-07
- [元数据管理系统解析](https://mp.weixin.qq.com/s?src=11&timestamp=1618555532&ver=3011&signature=j7T-s05mGRylTpswE-bYnmXDzbFtKd4lIoCHtDtcCJumP0JSKmxVg7iuZyu*aoZYu6ahwagxByeYoNnzIOPDsO5lVAyjrXKY3vRGLR99J9YlbW1Vlv6vtTfSOzCfeMnU&new=1)    2018-03
- [数据治理方案技术调研 Atlas VS Datahub VS Amundsen](https://cloud.tencent.com/developer/article/1746714)    2020-11







### 数据湖
- [从自研到 Delta 到 Iceberg，网易严选数据湖建设实践](https://www.infoq.cn/article/SJr7sHxxVBczcl5ArCiF)    2021-03








## 三、资源汇总
### 大厂技术博客
- [美团技术团队](https://tech.meituan.com/)
- [有赞技术团队](https://tech.youzan.com/)
- [滴滴云博客](https://blog.didiyun.com/)

## 大数据相关网站
- [dbaplus](https://dbaplus.cn/)







