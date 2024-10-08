## 2.1.7

*发布日期: 2024-08-23*

### Features
- 支持 `trim database` 语句，实现对资源进行加速回收。
- 在集群模式下，对于存储的数据支持混合缓存（内存与磁盘），提升数据查询效率。 
- 在本次发版本中，增加了对 ARM 的支持。
- 在 `dlsql` 中，支持通过`\G`对数据进行格式化输出。

### 增强
- 对 HTTP 返回的结构进行调整。
- 优化 InfluxDB 行协议写入。


### 修复
- 在 `dlsql`中，当返回结果为空时的显示问题。

