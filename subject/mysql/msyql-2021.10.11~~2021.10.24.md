# Mysql高频面试考点

| 子类                | 题目                                                      | 频次 |
| ------------------- | --------------------------------------------------------- | ---- |
| Mysql复制           |                                                           | 8    |
|                     | Mysql主从复制过程                                         | 7    |
|                     | 主从一致性如何保证                                        | 1    |
| Mysql基础           |                                                           | 15   |
|                     | char与varchar的区别                                       | 1    |
|                     | Drop delecte truncate                                     | 1    |
|                     | Mysql基本数据类型                                         | 1    |
|                     | Mysql数据存储形式                                         | 2    |
|                     | sql 语句的执行顺序                                        | 1    |
|                     | update或者insert语句内部执行过程？                        | 2    |
|                     | 关系型数据库与非关系型数据库区别                          | 2    |
|                     | 数据库三范式                                              | 5    |
| Mysql事务           |                                                           | 116  |
|                     | ACID中为什么需要隔离性                                    | 1    |
|                     | Mvcc实现机制(RC和RR隔离级别下的区别)                      | 16   |
|                     | Mysql的binlog redolog undolog日志文件及其作用             | 11   |
|                     | Mysql的默认隔离级别、不同等级隔离级别解决的问题与实现原理 | 48   |
|                     | Mysql事务及特性                                           | 26   |
|                     | 不可重复读与幻读的区别                                    | 1    |
|                     | 解释脏读、幻读及产生条件                                  | 10   |
|                     | 可重复读是如何实现的                                      | 1    |
|                     | 事务失效的场景举例                                        | 1    |
|                     | 事务四个特性中隔离性的作用                                | 1    |
| Mysql索引           |                                                           | 148  |
|                     | myisam和innodb的区别                                      | 5    |
|                     | Mysql的聚簇索引和非聚簇索引作用与区别                     | 20   |
|                     | Mysql索引数据结构                                         | 24   |
|                     | Mysql索引优化与设计规则                                   | 11   |
|                     | 回表操作                                                  | 1    |
|                     | 简述什么是全文索引                                        | 1    |
|                     | 简述什么是索引下推                                        | 1    |
|                     | 简述索引覆盖与回表查询                                    | 6    |
|                     | 简述索引作用与优缺点                                      | 5    |
|                     | 如何对Sqls语句进行索引使用分析                            | 1    |
|                     | 什么时候需要加索引                                        | 2    |
|                     | 什么是覆盖索引                                            | 1    |
|                     | 说一下b+ 树                                               | 13   |
|                     | 索引的数据结构对比（hash、B树与B+树），为什么不用红黑树   | 35   |
|                     | 索引的最左匹配原则                                        | 4    |
|                     | 索引失效的几种场景                                        | 13   |
|                     | 索引下推是什么                                            | 1    |
|                     | 主键为什么自增，不自增是否可行                            | 3    |
|                     | 最左匹配原则是啥意思                                      | 1    |
| Mysql锁机制         |                                                           | 20   |
|                     | mysql 产生死锁的原因                                      | 1    |
|                     | Mysql产生死锁的原因及解决方案                             | 2    |
|                     | Mysql有哪几种锁                                           | 8    |
|                     | 按照索引查询会发生死锁吗                                  | 1    |
|                     | 按照索引查询是否会发生死锁                                | 1    |
|                     | 间隙锁的作用与应用场景                                    | 3    |
|                     | 乐观锁与悲观锁的区别                                      | 2    |
|                     | 行锁与表锁的区别                                          | 2    |
| Mysql问题与解决方案 |                                                           | 4    |
|                     | Mysql承受不住压力怎么办？                                 | 1    |
|                     | 如何防止库存减为0？                                       | 1    |
|                     | 数据高写入量场景，如何设计数据读取方案？                  | 1    |
|                     | 字段存在唯一性约束，数据库设计需要考虑哪些？              | 1    |
| 查询性能优化        |                                                           | 25   |
|                     | count(1)、count(*)、count(列名)区别                       | 2    |
|                     | Inner join与left join区别                                 | 8    |
|                     | Mysql sql优化，慢Sql如何排查                              | 9    |
|                     | Mysql查询优化器机制                                       | 1    |
|                     | union和union all区别                                      | 1    |
|                     | 如果数据量变大，分页变慢，limit如何优化？                 | 1    |
|                     | 如何避免回表查询                                          | 2    |
|                     | 整型字段加索引进行范围查找的优化                          | 1    |
| 存储引擎            |                                                           | 26   |
|                     | Innodb与myisam的区别、应用场景                            | 13   |
|                     | Mysql的几种存储引擎                                       | 12   |
|                     | 简要说明Innodb的优势                                      | 1    |
| 分库分表            |                                                           | 4    |
|                     | 分库分表                                                  | 4    |