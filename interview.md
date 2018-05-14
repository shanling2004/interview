1. JRE里Error，Exception和Throwable有什么关系 什么差别？

2. JRE里Exception和RuntimeException有什么关系 什么差别？

3. Thread 状态有哪些 怎么样的变迁状态？
http://blog.csdn.net/lifei128/article/details/20363257

4. ThreadPool构造函数有哪些可配置的参数 都是什么作用？

5. java.lang.Object 里equals方法的override有什么需要注意的？

6. Java内存模型 有哪些模块？列举JVM Tuning经验？什么是off-heap 内存？

7. 老内存模型 max heap size（Xmx），max permsize（maxPermSize）控制住，但启动的JVM进程 依然不断消耗超多内存 有什么其他可能会发生类似情况？

8. C10K 问题的解决方案？
http://www.360doc.com/content/13/0522/18/1542811_287328391.shtml
http://www.kegel.com/c10k.html#threaded

9. 描述一下 NIO 异步IO

10. 数据库多表Join 有哪些常用的方式？
hash Join， Nested loops，Sort Merge Join

11 LRU Cache
http://flychao88.iteye.com/blog/1977653

12 列举IP unavailable的各种可能原因？

13 已知 上亿的不重复的邮件地址 查询给定某个邮件地址 是不是已经存在于上亿的邮件地址中？
要求计算快 省内存

14 海量数据下 查找第100大数据值是多少？
要求省内存

15 Linux 给定端口 如何查询对应的进程？如何查询当前句柄连接有哪些？

16 Linux 如何查看CPU开销. Memory开销. Disk IO. Context Switch, 等待运行的进程数和 处在睡眠状态中的进程数?

17 Linux 如何查看某个进程limit控制室如何？如何查看某个进程的CPU core使用和切换情况？

18 Linux 如何在系统层面限制某个进程使用内存和CPU的开销？

19 free -g如下，buffers和cached指什么含义？
                   total       used       free     shared    buffers     cached
Mem:            128        119           8          0            1               22
-/+ buffers/cache:        95          32
swap:          255            0         255

http://www.cnblogs.com/pengdonglin137/p/3315124.html

20 NoSQL基石之一CAP原则 是什么含义？什么样的构架基本满足CP 什么样的构架基本满足AP?
21 Wildcard Match Algorith
* Recursive
* DP
* Greedy

https://longwayjade.wordpress.com/2015/04/26/leetcode-recursion-dp-greedy-wildcard-matching/


21 [MapReduce] 计算 大数据量的均方差 hyperLogLog

22 streaming 多流join
