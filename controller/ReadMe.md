# sql控制器

1. 如何防止一条待执行的sql占用过多的资源(统计信息？执行代价？)
2. 监视qps，qps达到某一阈值，自动kill占用资源多的资源(或其他类型)。
3. 典型故障处理  
    - 大事务  
    - 热定数据问题
    - 连接数满
    - 慢查询