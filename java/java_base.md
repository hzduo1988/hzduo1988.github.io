##一、Java基础和高级
- String类为什么是final的。

- HashMap的源码，实现原理，底层结构。

- 反射中，Class.forName和classloader的区别
- session和cookie的区别和联系，session的生命周期，多个服务部署时session管理。
- Java中的队列都有哪些，有什么区别。
- Java的内存模型以及GC算法
- Java7、Java8的新特性
- Java数组和链表两种结构的操作效率，在哪些情况下(从开头开始，从结尾开始，从中间开始)，哪些操作(插入，查找，删除)的效率高
- Java内存泄露的问题调查定位：jmap，jstack的使用等等

##二、spring框架
 - spring框架中需要引用哪些jar包，以及这些jar包的用途
 - srpingMVC的原理
 - springMVC注解的意思
 - spring中beanFactory和ApplicationContext的联系和区别
 - spring注入的几种方式
 - spring如何实现事物管理的
 - springIOC和AOP的原理
 - spring中循环注入的方式
 - Spring AOP与IOC的实现原理
 - Spring的beanFactory和factoryBean的区别
 - Spring的事务隔离级别，实现原理
 - 对Spring的理解，非单例注入的原理？它的生命周期？循环注入的原理，aop的实现原理，说说aop中的几个术语，它们是怎么相互工作的？
 - spring boot特性，优势，适用场景等

##三、java多线程常见问题
 - Java创建线程之后，直接调用start()方法和run()的区别
 - 常用的线程池模式以及不同线程池的使用场景
 - newFixedThreadPool此种线程池如果线程数达到最大值后会怎么办，底层原理。
 - 多线程之间通信的同步问题，synchronized锁的是对象，衍伸出和synchronized相关很多的具体问题，例如同一个类不同方法都有synchronized锁，一个对象是否可以同时访问。或者一个类的static构造方法加上synchronized之后的锁的影响。
 - 了解可重入锁的含义，以及ReentrantLock 和synchronized的区别
 - 同步的数据结构，例如concurrentHashMap的源码理解以及内部实现原理，为什么他是同步的且效率高
 - atomicinteger和volatile等线程安全操作的关键字的理解和使用
 - 线程间通信，wait和notify

##四、网络通信
 - http是无状态通信，http的请求方式有哪些，可以自己定义新的请求方式么。
 - socket通信，以及长连接，分包，连接异常断开的处理。
 - socket通信模型的使用，AIO和NIO。
 - socket框架netty的使用，以及NIO的实现原理，为什么是异步非阻塞。
 - 同步和异步，阻塞和非阻塞。

##五、常用Linux命令
 - 常用的linux下的命令
 - 大的log文件中，统计异常出现的次数、排序，或者指定输出多少行多少列的内容。
 - linux下的调查问题思路：内存、CPU、句柄数、过滤、查找、模拟POST和GET请求等等场景
 - shell脚本

##六、数据库MySql
 - MySql的存储引擎的不同
 - 单个索引、联合索引、主键索引
 - Mysql怎么分表，以及分表后如果想按条件分页查询怎么办(如果不是按分表字段来查询的话，几乎效率低下，无解)
 - 分表之后想让一个id多个表是自增的，效率实现
 - MySql的主从实时备份同步的配置，以及原理(从库读主库的binlog)，读写分离
 - 事物的四个特性，以及各自的特点（原子、隔离）等等，项目怎么解决这些问题

##七、设计模式(写代码)
 - 单例模式：饱汉、饿汉。以及饿汉中的延迟加载
 - 工厂模式、装饰者模式、观察者模式等

##八、算法&数据结构&设计模式
 - 使用随机算法产生一个数，要求把1-1000W之间这些数全部生成。（考察高效率，解决产生冲突的问题）
 - 两个有序数组的合并排序
 - 一个数组的倒序
 - 计算一个正整数的正平方根
 - 说白了就是常见的那些查找排序算法
 - 数组和链表数据结构描述，各自的时间复杂度
 - 二叉树遍历
 - 快速排序
 - BTree相关的操作
 - 在工作中遇到过哪些设计模式，是如何应用的
 - hash算法的有哪几种，优缺点，使用场景
 - 什么是一致性hash
 - paxos算法

##九、分布式缓存
 - 为什么用缓存，用过哪些缓存，redis和memcache的区别
 - redis的数据结构
 - redis的持久化方式，以及项目中用的哪种，为什么
 - redis集群的理解，怎么动态增加或者删除一个节点，而保证数据不丢失。（一致性哈希问题）

##线程池、高并发、NIO
 - 分析线程池的实现原理和线程的调度过程
 - 线程池如何调优
 - 线程池的最大线程数目根据什么确定
 - 动态代理的几种方式
 - HashMap的并发问题
 - 了解LinkedHashMap的应用吗
 - 反射的原理，反射创建类实例的三种方式是什么？
 - cloneable接口实现原理，浅拷贝or深拷贝
 - Java NIO使用
 - hashtable和hashmap的区别及实现原理，hashmap会问到数组索引，hash碰撞怎么解决
 - arraylist和linkedlist区别及实现原理
 - 反射中，Class.forName和ClassLoader区别
 - String，Stringbuffer，StringBuilder的区别？
 - 有没有可能2个不相等的对象有相同的hashcode
 - 简述NIO的最佳实践，比如netty，mina
 - TreeMap的实现原理

##JVM相关(面试必考)
 - JVM内存分代
 - Java 8的内存分代改进
 - JVM垃圾回收机制，何时触发MinorGC等操作
 - jvm中一次完整的GC流程（从ygc到fgc）是怎样的，重点讲讲对象如何晋升到老年代，几种主要的jvm参数等
 - 你知道哪几种垃圾收集器，各自的优缺点，重点讲下cms，g1
 - 新生代和老生代的内存回收策略
 - Eden和Survivor的比例分配等
 - 深入分析了Classloader，双亲委派机制
 - JVM的编译优化
 - 对Java内存模型的理解，以及其在并发中的应用
 - 指令重排序，内存栅栏等
 - OOM错误，stackoverflow错误，permgen space错误
 - JVM常用参数
##分布式相关
 - Dubbo的底层实现原理和机制
 - 描述一个服务从发布到被消费的详细过程
 - 分布式系统怎么做服务治理
 - 接口的幂等性的概念
 - 消息中间件如何解决消息丢失问题
 - Dubbo的服务请求失败怎么处理
 - 重连机制会不会造成错误
 - 对分布式事务的理解
 - 如何实现负载均衡，有哪些算法可以实现？
 - Zookeeper的用途，选举的原理是什么？
 - 数据的垂直拆分水平拆分。
 - zookeeper原理和适用场景
 - zookeeper watch机制
 - redis/zk节点宕机如何处理
 - 分布式集群下如何做到唯一序列号
 - 如何做一个分布式锁
 - 用过哪些MQ，怎么用的，和其他mq比较有什么优缺点，MQ的连接是线程安全的吗
 - MQ系统的数据如何保证不丢失
 - 列举出你能想到的数据库分库分表策略；分库分表后，如何解决全表查询的问题。

##数据库
 - MySQL InnoDB存储的文件结构
 - 索引树是如何维护的？
 - 数据库自增主键可能的问题
 - MySQL的几种优化
 - mysql索引为什么使用B+树
 - 数据库锁表的相关处理
 - 索引失效场景
 - 高并发下如何做到安全的修改同一行数据，乐观锁和悲观锁是什么，INNODB的行级锁有哪2种，解释其含义
 - 数据库会死锁吗，举一个死锁的例子，mysql怎么解决死锁
##Redis&缓存相关

 - Redis的并发竞争问题如何解决了解Redis事务的CAS操作吗
 - 缓存机器增删如何对系统影响最小，一致性哈希的实现
 - Redis持久化的几种方式，优缺点是什么，怎么实现的
 - Redis的缓存失效策略
 - 缓存穿透的解决办法
 - redis集群，高可用，原理
 - mySQL里有2000w数据，redis中只存20w的数据，如何保证redis中的数据都是热点数据
 - 用Redis和任意语言实现一段恶意登录保护的代码，限制1小时内每用户Id最多只能登录5次
 - redis的数据淘汰策略