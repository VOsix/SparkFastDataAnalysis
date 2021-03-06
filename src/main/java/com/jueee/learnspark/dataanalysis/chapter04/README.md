### 第 4 章	键值对操作 ###
-   介绍如何操作键值对 RDD。
-   讨论用来让用户控制键值对 RDD 在各节点上分布情况的高级特性：分区。  
使用可控的分区方式把常被一起访问的数据放到同一个节点上，可以大大减少应用的通信开销。
#### 本章目录 ####
1.	[动机](C1动机.md)    
2.	[创建 Pair RDD](C2创建PairRDD.md)    
3.	[Pair RDD 的转化操作](C30PairRDD的转化操作.md)    
3.1	[聚合操作](C31聚合操作.md)    
3.2	[数据分组](C32数据分组.md)    
3.3	[连接](C33连接.md)    
3.4	[数据排序](C34数据排序.md)    
4.	[Pair RDD 的行动操作]()    
5.	[数据分区（进阶）](C5数据分区.md)    
5.1	获取 RDD 的分区方式    
5.2	从分区中获益的操作    
5.3	影响分区方式的操作    
5.4	示例：PageRank    
5.5	自定义分区方式  
#### 本章总结 ####    
-   学习了如何使用 Spark 提供的专门的函数来操作键值对数据。