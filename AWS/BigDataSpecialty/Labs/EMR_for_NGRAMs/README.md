# Use EMR to analyze NGRAMS data

## Create EMR cluster
  * Cluster Name
  * Software Application Configurations(up to 08/20/2017)
    * Core Hadoop: Hadoop 2.7.3 with Ganglia 3.7.2, Hive 2.3.0, Hue 3.12.0, Mahout 0.13.0, Pig 0.16.0, and Tez 0.8.4
    * HBase: HBase 1.3.1 with Ganglia 3.7.2, Hadoop 2.7.3, Hive 2.3.0, Hue 3.12.0, Phoenix 4.11.0, and ZooKeeper 3.4.10
    * Presto: Presto 0.170 with Hadoop 2.7.3 HDFS and Hive 2.3.0 Metastore
    * Spark: Spark 2.2.0 on Hadoop 2.7.3 YARN with Ganglia 3.7.2 and Zeppelin 0.7.2
  * Hardware Configurations(up to 08/20/2017)
    * Compute Optimized
    * GPU Instances
    * Memory Optimized
    * Storage Optimized
    * General Purpose
  * Number of Instances
  * EC2 Key Pair
  * Security Group Configurations

## Hive Analysis in hadoop
  * Explore Raw Data
  * Normalize the Data
  * Monitor Job Execution by Ganglia
  * Explore Normalized Data
  * Complex Analysis