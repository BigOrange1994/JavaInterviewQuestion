===
云知声
Hashmap 的key冲突的处理原则
什么叫散列
mysql索引的主键和普通索引的区别、回表
mysql表数据量限制，阿里规范说的是多少
mysql表锁和行锁的区别
个人规划

========
Soul面试题
Spring bean的循环引用问题
ThreadLocal的使用场景和原理
AOP 原理
求N个集合的差算法实现
ConcurrentHashmap原理
mybatis原理
实现自定义的JDBC连接池，怎么实现整体的过程，需要考虑哪些
单例模式
二叉树、红黑树
大表分页查询优化
JMM
线程的状态

=========
百信银行：
CAP？
幂等性？
redis数据类型
JWT和其他校验
zk和eureka的优缺点
countdownlatch？
线程安全问题遇到过么
@Transaction原理
AOP原理
hashmap、hashtable
redis分布式锁
redis IO复用原理
mysql explain
Mysql最左匹配原则
dubbo负载均衡原理
自定义注解实现的过程
适配器模式、策略模式
本地缓存和redis缓存的使用场景
======

薪人薪事：
Object中的方法
哪些concurrent包下的类，说下场景
hashmap性能问题
arraylist实现
mysql聚簇索引，非聚簇索引，锁相关
mysql优化，having count
设计一个分布式定时任务调度系统，思路，表有哪些
mysql 乐观锁、悲观锁原理


=======
58面试题：
mysql树的关键字位置
redis单实例高并发原理
set关键字执行过程，原理
ThreadLocal原理，加上静态static，线程间能互相访问么这个共享变量么？
synchronized原理
volatile原理
重入锁原理
hashmap扩容后，新的键值对放在哪里，时间、空间复杂度
垃圾回收算法有哪些
JVM结构
minorgc原理
CPU100%问题排查
redis主从同步过程
Canal原理
线程池参数

======
真融宝：
zuul原理
SpringBoot @SpringBootApplication 注解原理，说下启动过程
Springboot引入xxx-starter的pom ，为什么就能集成这样的组件，原理
redis分布式锁原理
hashmap什么时候，红黑树转为链表
hashmap1.7性能问题
线程的状态
Apollo原理
线程池参数
Ribbon负载均衡原理
mysql默认的隔离级别

=====
开课吧：
kafka Spring自动提交的带来的问题
kafka高可用原理
topic、brokers、group概念

====
天猫电话面试-一面

JVM结构
垃圾回收的机制和算法
双亲委派机制原理、双亲委派能避免什么问题
AOP原理, 
kafka LAG 排查
死锁的预防
负责什么、项目架构、
程序宕机的排查，
Spring cloud和dubbo的区别

天猫电话面试-二面
bean  的生命周期
ThreadLocal 和线程池
ThreadPool参数的意义
Wait notify 执行的时候，要注意什么 线程的状态
Kafka重复消费
ForkJoinPool、CompletableFuture

=====转转===
ThreadPool原理
Mysql 联合索引(a,b) (b,a) 说一下使用场景的区别
分库分表存在的问题： id  name userid  字段：select name  ; select id 分别怎么分表
分布式锁释放锁时，如果不检测UUID谁设置的，会有什么问题
分布式锁在redis集群中出现的问题
分布式锁TTL过断，怎么让线程继续执行
如何保证幂等性
hashmap的原理
怎么排查线上问题，内存溢出、CPU100%
数据库有很多数据怎么通过快速传输给另一端
如何保证kafka生产者的高可用
一种微服务集群中服务挂了，怎么快速剔除，会不会调用到这个机器上
你所熟知的RPC，都有哪些负载均衡机制，如果让你实现，怎么实现？
只读实例和读写实例如何保证同步
多线程同时写数据库，数据库会不会挂掉、如果挂了，怎么处理
分布式锁ETCD
自定义切面的过程
你做的并发量有多大，多少QPS
多个业务之间实现实时的通信，怎么处理？我说发kafka消息，他说还有别的方案。

======陌陌=====
给定CPU核心数、给定要求达到的QPS 、要求99.99%可用率， 应该部署多少台机器
redis ZSET底层的数据结构实现
JDK1.8的新特性
单核机器，多线程处理动作快还是单线程
为什么选取redis作为缓存、为什么不用别的Ecache、memcache
为什么选取kafka，不用其他的MQ
实现一种RPC时，应该考虑调用和响应之间的哪些问题
多线程是怎么处理线程之间的状态的
降低YGC的方法
guava cache的使用场景
mybatis的实现原理：怎么和数据库做的交互，又是怎么最后生成结果的
Spring事务的实现原理
Spring事务传播机制的实现原理
会看新技术的原理么？说一个技术的原理，比如opensearch的原来，为什么用它而不是es
分布式锁在redis集群中出现的问题
redis分布式锁出现死锁问题，怎么解决？
redis lpushrpop 操作中的数据结构
为什么用kafka会比较快，说一下原理
很多线程对redis写，如何保证redis的高可用，怎么优化

====百度====
mysql的B+树存储结构，为什么一个块大小是16K
一种微服务集群中的服务全挂了，怎么保证高可用
一种微服务集群中服务挂了，怎么快速剔除，会不会调用到这个机器上
hashmap的数据结构，为什么使用红黑树查询会快
currenthashmap怎么实现的线程安全
JVM各个区域和作用，清理对象的算法，举例说明几个GC用到的垃圾回收算法
技术选型谁来决定
guava cache的使用场景
给定一个数字，16453 只能交换一次其中两位数字，如何找到相对的最大值。如果第一位是9怎么优化算法。上述两种情形的时间复杂度是多少
你做的并发量有多大，多少QPS
手写fork join任务计算 1到10000的累加和
为什么用Apollo，不用Cloud Config
线上出问题了怎么排查
会使用到redis做持久化么？
MYSQL事务的隔离级别有哪些？
volitale的原理
用的什么代码版本管理工具


====一亩田===
一些算法题

=====新东方
线程池
list的remove操作带来的问题
一个分组排序的SQL，找出各个学科分数最大的学生信息
hashmap的实现
SQL优化
limit大表优化
切面的使用
