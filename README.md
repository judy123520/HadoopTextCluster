# HadoopTextCluster
##数据：
    DBLP
##设计：
    hadoop mapreduce+hbase+zookeeper
##初步设想:
    1、首先，解析xml文档，将数据存储在hbase当中，然后将数据从hbase倒入hdfs或者直接使用hbase作为mapreduce的数据源，分析数据，用爬虫获取每个文章的摘要，存储下来，然后再进行数据预处理，分词等
    2、实现聚类算法串行化，然后在转化为mareduce算法。
    3、数据测试
    4、改进算法，撰写小论文。
