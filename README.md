[<img src="https://cdn.rawgit.com/rayokota/awesome-hbase/a8c487f2/hbase_logo_with_orca.png" align="right">](http://hbase.apache.org/)

# Awesome HBase [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)


A curated list of awesome HBase projects and resources.

## Contents

- [Projects](#projects)
    - [Clients](#clients)
    - [Cloud](#cloud)
    - [Frameworks](#frameworks)
        - [Datasets](#datasets)
        - [Document](#document)
        - [Entity/JPA](#entityjpa)
        - [Geospatial](#geospatial)
        - [Graph](#graph)
        - [SQL/OLAP](#sqlolap)
        - [Time Series](#time-series)
    - [Infrastructure](#infrastructure)
        - [Secondary Indices](#secondary-indices)
        - [Transactions](#transactions)
    - [Integrations](#integrations)
    - [Tools](#tools)
    - [Miscellaneous](#miscellaneous)

- [Resources](#resources)
    - [Books](#books)
    - [Papers](#papers)

    
## Projects

### Clients

* [asynchbase](https://github.com/OpenTSDB/asynchbase) - Fully asynchronous, non-blocking HBase client.
* [gohbase](https://github.com/tsuna/gohbase) - Pure Go client for HBase.
* [happybase](https://github.com/wbolster/happybase) - Python client for HBase.


### Cloud

* [Amazon EMR](https://aws.amazon.com/emr/) - Amazon's Hadoop/HBase offering on AWS.
* [Azure HDInsight](https://azure.microsoft.com/en-us/services/hdinsight/) - Microsoft's Hadoop/HBase offering on Azure.
* [Google Cloud Bigtable](https://cloud.google.com/bigtable/) - High-performance NoSQL database service accessible via HBase client API.

### Frameworks

#### Datasets

* [Kite](http://kitesdk.org) - High-level data layer for Hadoop/HBase.

#### Document

* [HDocDB](https://github.com/rayokota/hdocdb) - HBase as a JSON document database.

#### Entity/JPA

* [DataNucleus](http://www.datanucleus.org) - JPA persistence layer with support for HBase.
* [Gora](http://gora.apache.org) - Persistence library for big data with support for HBase.
* [HEntityDB](https://github.com/rayokota/hentitydb) - HBase as an entity database.
* [Kundera](https://github.com/impetus-opensource/Kundera) - JPA client with support for HBase.

#### Geospatial

* [GeoMesa](http://www.geomesa.org/) - Spatial-temporal database with support for Accumulo, HBase, Cassandra, and Kafka.

#### Graph
* [Gradoop](https://github.com/dbs-leipzig/gradoop) - Research framework for scalable graph analytics built on Flink and HBase.
* [HGraphDB](https://github.com/rayokota/hgraphdb) - HBase as a TinkerPop graph database.
* [JanusGraph](http://janusgraph.org/) - Scalable graph database with support for Cassandra, HBase, Google Cloud Bigtable, and BerkeleyDB.
* [S2Graph](http://s2graph.incubator.apache.org) - High-performance distributed graph database built on HBase.

#### SQL/OLAP

* [EsgynDB](https://esgyn.com/) - Commercial SQL engine providing ACID transactions and BI analytics on top of Hadoop, based on Trafodian.
* [Kylin](http://kylin.apache.org) - Extreme OLAP engine for big data that stores data in HBase.
* [LeanXScale](http://www.leanxcale.com) - Commercial full ACID full SQL product built on Hadoop/HBase.
* [Phoenix](https://phoenix.apache.org) - SQL layer on top of HBase.
* [Splice Machine](https://www.splicemachine.com) - Commercial RDBMS built on top of HBase.
* [Trafodian](http://trafodion.apache.org) - Transactional SQL-on-Hadoop/HBase.

#### Time Series

* [Axibase](http://axibase.com/products/axibase-time-series-database/) - Distributed time series database built on HBase.
* [OpenTSDB](http://opentsdb.net) - Scalable time series database built on HBase.
* [Warp10](http://www.warp10.io) - Time series database for sensor data.

### Infrastructure

#### Secondary Indices

* [hindex](https://github.com/Huawei-Hadoop/hindex) - Secondary index for HBase.
* [Lily HBase Indexer](http://ngdata.github.io/hbase-indexer/) - Quickly and easily search for content stored in HBase.

#### Transactions

* [Haeinsa](https://github.com/VCNC/haeinsa) - Multi-row/multi-table transaction library for HBase.
* [Omid](https://github.com/yahoo/omid) - Transactional support for HBase.
* [Tephra](http://tephra.incubator.apache.org) - Globally consistent transactions on top of HBase.
* [Themis](https://github.com/XiaoMi/themis) - Cross-row/cross-table transactions on HBase based on Google's Percolator.

### Integrations

* [Apex](https://github.com/apache/apex-malhar/tree/master/contrib/src/main/java/com/datatorrent/contrib/hbase) - Apex-HBase connector.
* [Flink](https://github.com/apache/flink/tree/master/flink-connectors/flink-hbase) - Flink-HBase connector.
* [Hive](https://cwiki.apache.org/confluence/display/Hive/HBaseIntegration) - Hive HBase integration.
* [Spark](https://github.com/hortonworks-spark/shc) - Spark-HBase connector.
* [Spring for Apache Hadoop](https://projects.spring.io/spring-hadoop/) - Spring-Hadoop integration, including HBase support.

### Tools

* [Ambari](https://ambari.apache.org) - Software for provisioning, managing, and monitor Hadoop/HBase clusters.
* [Cloudera Manager](https://www.cloudera.com/products/product-components/cloudera-manager.html) - Tool for managing Hadoop/HBase in production.
* [Hannibal](https://github.com/sentric/hannibal) - Tools to monitor and maintain HBase clusters.

### Miscellaneous

* [HubSpot HBase support](https://github.com/HubSpot/hbase-support) - Configs and tools for HBase at HubSpot, including Hystrix integration and coprocessors.

## Resources

### Books

* [HBase in Action](https://www.manning.com/books/hbase-in-action) - Experience-driven guide that shows you how to use HBase.
* [HBase: The Definitive Guide, 2nd Edition](http://shop.oreilly.com/product/0636920033943.do) - Comprehensive guide to HBase.
* [Architecting HBase Applications](http://shop.oreilly.com/product/0636920035688.do) - Includes HBase principles, cluster guidelines, and in-depth case studies.
* [HBase Administration Cookbook](https://www.packtpub.com/big-data-and-business-intelligence/hbase-administration-cookbook) - How to master HBase configuration and administration.
* [HBase Essentials](https://www.packtpub.com/big-data-and-business-intelligence/hbase-essentials) - A practical guide to using HBase.
* [HBase Design Patterns](https://www.packtpub.com/big-data-and-business-intelligence/hbase-design-patterns) - Successful patterns to develop scalable applications with HBase.
* [Learning HBase](https://www.packtpub.com/big-data-and-business-intelligence/learning-hbase) - Learn the fundamentals of HBase administration and development.
* [HBase High Performance Cookbook](https://www.packtpub.com/big-data-and-business-intelligence/hbase-high-performance-cookbook) - Exciting projects that teach you how to use HBase.
* [Apache HBase Primer](http://www.apress.com/us/book/9781484224236) - A compact guide to HBase essentials.
* [Pro Apache Phoenix](http://www.apress.com/us/book/9781484223697) - Basic and best practices for using Phoenix.

### Papers

* [Bigtable: A Distributed Storage System for Structured Data](https://static.googleusercontent.com/media/research.google.com/en//archive/bigtable-osdi06.pdf) - The inspiration for HBase.
* [Apache Hadoop Goes Realtime at Facebook](https://pdfs.semanticscholar.org/865a/215390cd49af9e4941e03107120e631dcaa0.pdf) - How Facebook deployed HBase to production.

## License

<p xmlns:dct="http://purl.org/dc/terms/">
<a rel="license" href="http://creativecommons.org/publicdomain/mark/1.0/">
<img src="https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/publicdomain.svg"
     style="border-style: none;" alt="Public Domain Mark" />
</a>
