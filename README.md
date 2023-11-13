# DPKB

大数据相关知识库，主要包括：
* 数据存储层、数据库（HDFS、Hive、HBase、Kudu、Doris、StarRocks、ClickHouse、TiDB等）
* 数据处理层、OLAP引擎（Spark、Flink、Presto、Trino等）
* 数据湖（IceBerg、Hudi、Delta等）
* 大数据开发、应用（主要包括ETL、调度、数仓、数据应用等，例如Seatunnel、Dolphinscheduler等）
* 数据治理（元数据管理、数据模型、数据标准、数据质量、数据安全等）

持续更新中（2023-11）





## 一、数据存储层、数据库（HDFS、Hive、HBase、Kudu、Doris、StarRocks、ClickHouse、TiDB等）

### ▶ HDFS




### ▶ Hive
#### 1）官网、社区、博客
- [Hive 官网](https://hive.apache.org/)


#### 2）专栏
- [Hive 教程](columns/hive/hive教程.md)


#### 3）大厂实践
- [HiveCube 在有赞的实践](https://tech.youzan.com/cube/)    2019-11
- [Hive Metastore Federation 在滴滴的实践](https://blog.didiyun.com/index.php/2019/03/25/hive-metastore-federation/)    2019-03




### ▶ HBase
#### 1）官网、社区、博客
- [HBase 官网](https://hbase.apache.org/)
- [hbasefly](http://hbasefly.com/) 


#### 2）专栏


#### 3）大厂实践


#### 4）其他
- [HBase Bulkload 实践探讨](https://tech.youzan.com/hbase-bulkloadshi-practice/)    2019-12




### ▶ Kudu
#### 1）官网、社区、博客
- [Kudu 官网](https://kudu.apache.org/)


#### 2）专栏
- [Kudu 原理 论文](columns/kudu/Kudu原理论文.md)
- [网易云Kudu技术专栏](columns/kudu/网易云Kudu技术文章.md)


#### 3）大厂实践
- [Apache Kudu 在网易的实践](https://www.infoq.cn/article/kgwyqb5wer5wl8cquweq)   2021-08
- [Apache Kudu 在网易实时数仓的实践](https://www.infoq.cn/article/QETxjyIu5tAJTZ9ksMdu)    2020-02
- [Kudu架构介绍及其在小米的应用实践](https://www.modb.pro/db/119708)    2017-06


#### 4) 其他
- [我是如何成为Apache Kudu committer & PMC 的？](https://cloud.tencent.com/developer/article/1450749)    2019-06




### ▶ Doris
#### 1）官网、社区、博客
- [Doris 官网](https://doris.apache.org/)
- [Doris github](https://github.com/apache/doris)
- [Doris 论坛](https://github.com/apache/incubator-doris/discussions)


#### 2）专栏
- [Doris全面解析](columns/doris/Doris全面解析.md)
- [Doris最佳实践](columns/doris/Doris最佳实践.md)


#### 3）案例实践
- [Apache Doris在美团外卖数仓中的应用实践](https://tech.meituan.com/2020/04/09/doris-in-meituan-waimai.html)    2020-04
- [Apache Doris 在韵达物流领域的应用实践](https://mp.weixin.qq.com/s/Z_PhWk92ctZ7slz4SrVZ9Q)    2021-07
- [Apache Doris 在蜀海供应链的实践](https://mp.weixin.qq.com/s/SHuE-KCsIyh6jfo0DqLD6w)    2021-07
- [京东物流基于 Doris 的亿级数据自助探索应用](https://mp.weixin.qq.com/s/qVFa40yMg0_N9Lsb10ACQA)    2021-07
- [Doris on ES在快手商业化的最佳实践](https://mp.weixin.qq.com/s/5Pc5ewVFWPgauG4hNLH9xw)    2021-08
- [基于Doris的有道精品课数据中台建设实践](https://mp.weixin.qq.com/s/Gz-au9CHJ4lHrs5MkzeAJg)    2020-12
- [美团外卖实时数仓建设实践](https://mp.weixin.qq.com/s/-JPWqa_-at7F5hZ0zekVSQ)    2020-10
- [Doris在作业帮实时数仓中的应用&实践](https://mp.weixin.qq.com/s/hjbMM8CbElO04VLN5cfJtQ)    2020-09
- [基于Apache Doris的小米增长分析平台实践](https://mp.weixin.qq.com/s/WeNAItPJ4b7fsqW4kf0dSA)    2020-08
- [Apache Doris在京东双十一大促中的实践](https://mp.weixin.qq.com/s/8XnwJXm4kzq56SvElwL6kA)    2020-03
- [Apache Doris 在百度商业大规模微服务全链路监控的实践](https://mp.weixin.qq.com/s/k7CcCdHPTK1ZTDs_qKgh5w)    2020-02




### ▶ StarRocks
#### 1）官网、社区、博客
- [StarRocks](https://www.starrocks.com/zh-CN/index)
- [StarRocks文档](https://docs.starrocks.com/zh-cn/main/introduction/StarRocks_intro)
- [编程小梦 康凯森](https://blog.bcmeng.com/)


#### 2) 专栏
- [StarRocks技术内幕](columns/starrocks/StarRocks技术内幕.md)




### ▶ ClickHouse
#### 1）官网、社区、博客
- [ClickHouse 官网](https://clickhouse.com/)


#### 2）专栏


#### 3）大厂实践
- [ClickHouse 在有赞的实践之路](https://tech.youzan.com/clickhouse-zai-you-zan-de-shi-jian-zhi-lu/)    2021-01


#### 4）其他




## 二、数据处理层、OLAP引擎（Spark、Flink、Presto、Trino等）

### ▶ Spark
#### 1）官网、社区、博客
- [Spark 官网](https://spark.apache.org/)


#### 2）专栏
- [Apache Spark 的设计与实现](columns/spark/Apache%20Spark的设计与实现.md)


#### 3）大厂实践
- [SparkSQL 在有赞的实践](https://tech.youzan.com/sparksql-in-youzan/)    2019-01
- [SparkSQL 在有赞大数据的实践（二）](https://tech.youzan.com/sparksql-in-youzan-2/)    2020-01




### ▶ Flink
#### 1）官网、社区、博客
- [Flink 官网](https://flink.apache.org/)
- [Flink Confluence](https://cwiki.apache.org/confluence/display/FLINK/)
- [Flink Blog](https://flink.apache.org/blog/)
- [Ververica Blog](https://www.ververica.com/blog?hsLang=en) 
- [Ververica 中文](https://ververica.cn/developers-resources/)
- [Flink 知识图谱](https://ververica.cn/wp-content/uploads/2020/03/Apache-Flink-Stateful-Computations-over-Data-Streams.pdf)
- [Jark's Blog - WuChong - 云邪](http://wuchong.me/)


#### 2）专栏
- [Flink 架构、源码分析专栏](columns/flink/Flink架构、源码分析专栏.md)
- [Flink 实战系列](columns/flink/Flink实战系列.md)
- [Flink 开源项目汇总](columns/flink/Flink开源项目汇总.md)
##### 教程
- [Flink SQL Cookbook - Ververica](https://github.com/ververica/flink-sql-cookbook/)
- [Flink 零基础入门](columns/flink/Flink零基础入门.md)
- [Flink 进阶教程](columns/flink/Flink进阶教程.md)
- [Apache Flink 漫谈系列](columns/flink/Apache%20Flink%20漫谈系列.md)
- [Flink 相关论文](columns/flink/Flink%20相关论文.md)


#### 3）大厂实践
- [flink-forward-asia-hackathon-2021](https://github.com/flink-china/flink-forward-asia-hackathon-2021/issues)




### ▶ Presto、Trino
#### 1）官网、社区、博客
- [PrestoDB 官网](https://prestodb.io/)
- [Trino 官网](https://trino.io/)     原PrestoSql
- [Google Presto Group](https://groups.google.com/g/presto-users)
- [Presto 知乎专栏](https://www.zhihu.com/column/presto-cn)
- [若飞-技术博客](http://armsword.com/archives/)


#### 2）专栏
- [Presto 架构、源码分析专栏](columns/presto/Presto架构、源码分析专栏.md)
- [Presto 最佳实践、调优、踩坑专栏](columns/presto/Presto最佳实践、调优、踩坑专栏.md)
- [Presto 资料汇总、会议资讯专栏](columns/presto/Presto资料汇总、会议资讯专栏.md)


#### 3）大厂实践
- [Presto 在车好多的实践](https://mp.weixin.qq.com/s/Bmqv54sVZgTqQ82I_RfmsA)    2020-12
- [Presto 在滴滴的探索与实践](https://zhuanlan.zhihu.com/p/266162270)    2020-10
- [Presto 在有赞的实践之路](https://tech.youzan.com/presto-zai-you-zan-de-shi-jian-zhi-lu/)    2020-04
- [PrestoCon 2020：云原生数据湖分析DLA的Presto实践](https://zhuanlan.zhihu.com/p/260784762)    2020-03
- [携程 Presto 技术演进之路](https://zhuanlan.zhihu.com/p/41538472)    2018-08
- [Presto 实现原理和美团的使用实践](https://tech.meituan.com/2014/06/16/presto.html)    2014-06
- [Presto 高性能引擎在美图的实践](https://zhuanlan.zhihu.com/p/408957032)    2021-09




## 三、数据湖（IceBerg、Hudi、Delta等）

- [一文看懂：什么是数据库、数据湖、数据仓库、湖仓一体、智能湖仓？](https://www.smartcity.team/consultingskills/experience/shujukuyushujuhu/#comments)    2021-08


### ▶ Iceberg
#### 1）官网、社区、博客
- [Iceberg 官网](https://iceberg.apache.org/)


#### 2）应用
- [数据湖 Iceberg | 实时数据仓库的发展、架构和趋势](https://mp.weixin.qq.com/s?__biz=MzIwNTUxNTI1Ng==&mid=2247485623&idx=1&sn=9f03a36dbfc06c712b6132faabaa1dfd&chksm=972ef820a05971360311fd69c686e4b420222cfa639a1bcb5648bece4c3d886ae8f981712d8c&scene=21#wechat_redirect)    2021-03
- [数据湖 Iceberg | Apache Iceberg 快速入门](https://mp.weixin.qq.com/s?__biz=MzIwNTUxNTI1Ng==&mid=2247485637&idx=1&sn=0489f233e3bda2bcef221c9532bb001e&chksm=972ef852a0597144538b7807948443a27e58f99ba33d17a7bcb12ccb8b382fd1d712d6e80cbc&cur_album_id=1746684202856579076&scene=190#rd)    2021-03
- [数据湖 Iceberg | 如何正确使用 Iceberg](https://mp.weixin.qq.com/s?__biz=MzIwNTUxNTI1Ng==&mid=2247485644&idx=1&sn=b2194d8f3c1e7cf7e8e8d9296b9025e2&chksm=972ef85ba059714dc69472e3860497389f2ca4503d2cddeedd348695b5c314da49aad0278978&cur_album_id=1746684202856579076&scene=190#rd)    2021-04
- [数据湖 Iceberg | 在网易云音乐的实践](https://mp.weixin.qq.com/s?__biz=MzIwNTUxNTI1Ng==&mid=2247485718&idx=1&sn=34347ac54e97877e4401ad37f1d15577&chksm=972ef981a059709724b7abab56786ef047a68f31fd829031d2214fa4994b9ec0f1b04e25318c&cur_album_id=1746684202856579076&scene=190#rd)    2021-04




### ▶ Hudi
#### 1）官网、社区、博客
- [Hudi 官网](https://hudi.apache.org/)

#### 2）应用
- [Flink CDC + Hudi + Hive + Presto 构建实时数据湖最佳实践](https://mp.weixin.qq.com/s/079VeDeIM_MQPyiiDX2l_w)
 



### ▶ Delta




## 四、大数据开发、应用（主要包括ETL、调度、数仓、数据应用等，例如Seatunnel、Dolphinscheduler等）

### ▶ Seatunnel



### ▶ DolphinScheduler



### ▶ 大数据架构
- [SQL on Hadoop 在快手大数据平台的实践与优化](https://www.infoq.cn/article/BN9cJjg1t-QSWE6fqkoR)    2019-06
- [携程机票大数据架构最佳实践](https://dbaplus.cn/news-73-1420-1.html)    2017-08
- [火山引擎DataLeap一站式数据治理解决方案及平台架构](https://www.cnblogs.com/bytedata/p/17745908.html)    2023-10



### ▶ 数仓相关
- [有赞数据仓库实践之路](https://tech.youzan.com/dw-in-youzan/)    2020-03
- [OneData 建设探索之路：SaaS 收银运营数仓建设](https://tech.meituan.com/2019/10/17/meituan-saas-data-warehouse.html)    2019-10
- [面向AI技术的工程架构实践 | 贝壳一站式大数据开发平台实践](https://www.infoq.cn/article/mmnwzdlcyjg83qm0tgqm)    2020-11




### ▶ 报表平台
- [有赞 BI 平台实现原理](https://tech.youzan.com/principle-on-bi-platform/)    2021-01




## 五、数据治理（元数据管理、数据模型、数据标准、数据质量、数据安全等）

### ▶ 数据治理
- [美团配送数据治理实践](https://tech.meituan.com/2020/03/12/delivery-data-governance.html)    2020-03
- [全链路数据治理在网易严选的实践](https://www.infoq.cn/article/FOV6aEWRGNOfhD91YVcr)    2020-10
- [数据资产、数据治理 - 有赞](https://tech.youzan.com/shu-ju-zi-chan-zan-zhi-zhi-li/)    2019-11




### ▶ 元数据管理
- [字节跳动构建Data Catalog数据目录系统的实践](https://www.cnblogs.com/bytedata/p/16189474.html)    2022-04
- [有赞数据仓库元数据系统实践](https://tech.youzan.com/youzan-metadata/)    2018-08
- [饿了么元数据管理实践之路](https://dbaplus.cn/news-73-2143-1.html)    2018-07
- [数据治理方案技术调研 Atlas VS Datahub VS Amundsen](https://cloud.tencent.com/developer/article/1746714)    2020-11
- [数据资产治理-元数据采集那点事 - 有赞](https://tech.youzan.com/zi-chan-zhi-li-yuan-shu-ju-cai-ji-na-dian-shi/)    2020-12
- [来看看字节跳动内部的数据血缘用例与设计](https://segmentfault.com/a/1190000041452770)    2022-02
- [携程数据血缘构建及应用](https://mp.weixin.qq.com/s/LGK3YPZCe6oPTf48QaAIqA)    2021-09
- [Datahub](https://datahubproject.io/)    A Metadata Platform for the Modern Data Stack




### ▶ 数据标准
- [有赞指标库实践](https://tech.youzan.com/you-zan-zhi-biao-ku-shi-jian/)    2020-03




### ▶ 数据安全
- [浅谈有赞大数据安全体系](https://tech.youzan.com/you-zan-da-shu-ju-an-quan-ti-xi-jian-she-shi-jian/)    2021-01



## 六、机器学习、AI

### ▶ 机器学习平台
- [机器学习平台建设指南](https://mp.weixin.qq.com/s/HEg_6Gly2WMrcPD5Ao2n6g)    2021-04
- [一站式机器学习平台建设实践](https://mp.weixin.qq.com/s/ZDRD0vAxkSqe4UeXi9avKQ)    2020-02
- [汽车之家机器学习平台的架构与实践](https://blog.csdn.net/hellozhxy/article/details/107210015)    2020-07
- [微博推荐算法实践与机器学习平台演进](https://blog.csdn.net/m0_37586850/article/details/116465255)    2021-05
- [爱奇艺机器学习平台的建设实践](https://mp.weixin.qq.com/s/Np4w7RC2JFlB7ZGIduu71w)    2020-11
- [爱奇艺一站式机器学习平台Deepthought的建设与初探](https://mp.weixin.qq.com/s?__biz=MzI0MjczMjM2NA==&mid=2247487206&idx=1&sn=c8db1e12378376722a1521f409149d44&chksm=e97692c5de011bd3f1b42a8112cd04c24907cb101ac5474b0054c95941ff5c4769a42d496f3a&scene=21#wechat_redirect)    2020-06
- [一站式机器学习平台在 vivo AI 的实践](https://www.infoq.cn/article/THlkStomYLRgXL2hzm8w)    2020-02
- [再见，Yarn！滴滴机器学习平台架构演进](https://mp.weixin.qq.com/s/iTfHv8EFx4O4G1sNxsuMkg)    2019-03
- [网易严选机器学习平台建设实践](https://www.6aiq.com/article/1661745581086)    2022
- [Sunfish-有赞智能平台实践](https://tech.youzan.com/sunfish/)    2020-06




## 七、资源汇总

### ▶ 大厂技术博客
- [美团技术团队](https://tech.meituan.com/)
- [有赞技术团队](https://tech.youzan.com/)
- [滴滴云博客](https://blog.didiyun.com/)



### ▶ 大数据相关网站
- [dbaplus](https://dbaplus.cn/)



### ▶ 相关开源项目
- [数仓相关开源项目汇总](columns/opensource/数仓相关开源项目汇总.md)



### ▶ 相关论文
- [raft 中文翻译](https://github.com/maemual/raft-zh_cn/blob/master/raft-zh_cn.md)


