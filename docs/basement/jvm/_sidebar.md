* JVM内存结构
            
    * class文件格式
    * 运行时数据区
    * 堆和栈区别
    * [Java中的对象一定在堆上分配吗？](/basement/jvm/stack-alloc.md)
    
* Java内存模型
    
    * 计算机内存模型
    * 缓存一致性
    * MESI协议
    
    * 可见性
    * 原子性
    * 顺序性
    * happens-before
    
    * 内存屏障
    * synchronized
    * volatile
    * final
    * 锁
    
* 垃圾回收
    
    * GC算法：标记清除、引用计数、复制、标记压缩、分代回收、增量式回收
    
    * GC参数
    * 对象存活的判定
    * 垃圾收集器（CMS、G1、ZGC、Epsilon）
    
* JVM参数及调优
    
    * -Xmx
    * -Xmn
    * -Xms
    * Xss
    * -XX:SurvivorRatio
    
    * -XX:PermSize
    * -XX:MaxPermSize
    * -XX:MaxTenuringThreshold
    
* Java对象模型
    
    * oop-klass
    * 对象头
    
* HotSpot
    
    * 即时编译器
    * 编译优化
    
* 虚拟机性能监控与故障处理工具
    
    * jps
    * jstack
    * jmap
    * jstat
    * jconsole
    * jinfo
    * jhat
    * javap
    * btrace
    * TProfiler
    * jlink
    * Arthas