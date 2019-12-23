- JDK,JRE,JVM,JIT
- JVM = 类加载器 + 执行引擎 + 运行时数据区域
# 运行时数据区域
    - 整体结构
    - 大小设置
        - [理解JVM（4）- 堆内存的分代管理](https://www.jianshu.com/p/5946c0a414b5)
# GC
    - 如何区分哪些是垃圾
        - [垃圾回收说的最好的--咱们从头到尾说一次 Java 垃圾n回收](https://mp.weixin.qq.com/s?__biz=MzIxMzk3Mjg5MQ==&mid=2247484435&idx=1&sn
        =480178f0cad18f06f05ded61a9d55fb1&chksm=97afe6e7a0d86ff18a2250d4ed03182288f958733e557dbd4ba7f82310ca891db5b779379a2e&mpshare=1&scene=1&srcid=#rd)
    - 垃圾回收算法
    - 分代回收
    - 垃圾回收器
        - [Major GC和Full GC的区别是什么？触发条件呢？](https://www.zhihu.com/question/41922036)


# jvm深度学习理解
- 调试工具
    - idea ASM Bytecode Outline
    - idea jclasslib Bytecode viewer
    - jitwatch
    - HSDB
- 性能测试
    - 基准测试
        - JMH java benchmarks
        
- todo 画流程图
- Java虚拟机规范
- 本地代码/机器码/内核和机器码得区别/c是如何执行机器码的
- JIT c1 c2模式
- AOT编译执行
- 微机原理、操作系统原理、编译原理、数据库原理、算法原理
- HSDB了解类信息 C:\Program Files (x86)\Java\jdk1.8.0_221\lib> java -cp sa-jdi.jar sun.jvm.hotspot.HSDB
- synchronized相关问题
    - 从理解Java字节码到hotspot真实在C++中对class的实现[java hotspot虚拟机 - class文件](https://blog.eson.org/pub/3a5d7b99/)
  - volatile
      - [volatile与lock前缀指令](https://blog.csdn.net/qq_26222859/article/details/52235930)

# java中的锁

# 修饰符
- [Final](https://www.jianshu.com/p/f68d6ef2dcf0)


# reference
- [jvm启动模式之client与server差异和区别](https://blog.csdn.net/qq_29340989/article/details/81586182)
- [JVM 类型以及编译器模式-参数设置](https://wiki.jikexueyuan.com/project/jvm-parameter/types-and-compiler.html)
- [Could not load hsdis-amd64.dll; library not loadable; PrintAssembly is disabled](https://www.cnblogs.com/niceboat/p/9786905.html)
- [编译原理——一起手写个JIT编译器](https://www.bilibili.com/video/av70254941?from=search&seid=11902408127600124897)
- [ jvm为什么选择用解释器-JIT编译器的混合执行引擎 ](https://www.zhihu.com/question/37389356/answer/73820511)
- [即时编译器与解释器的区别？](https://www.zhihu.com/question/36746487)
- [有执行原理图-如何通俗易懂地介绍「即时编译」（JIT），它的优点和缺点是什么？](https://www.zhihu.com/question/21093419)
- [视频地址-张龙](https://www.bilibili.com/video/av47756459/?p=8&t=33)
- [深入理解Java虚拟机-龙果学院](https://www.youtube.com/watch?v=0UoYQ7QtGm8&list=PLStUqVcO94bjZTvxJLxGE6R6CdSd7mvPP&index=98)
- [《Java虚拟机原理图解》4.JVM机器指令集-最优秀](https://blog.csdn.net/luanlouis/article/details/50412126)
- [Java 类加载机制分析说明了加载第一步](https://www.jianshu.com/p/3615403c7c84)
- [Java HotSpot VM Options](https://www.oracle.com/technetwork/articles/java/vmoptions-jsp-140102.html)
- [Java静态属性的初始化过程](http://softlab.sdut.edu.cn/blog/subaochen/2017/03/java%E9%9D%99%E6%80%81%E5%B1%9E%E6%80%A7%E7%9A%84%E5%88%9D%E5%A7%8B%E5%8C%96%E8%BF%87%E7%A8%8B/)
- [指针的意义和linux的内存回收艺术](http://blog.csdn.net/dog250/article/details/5303284)
- [Java内存管理的一些小疑问](https://lizhaoxuan.github.io/2017/05/08/Java%E5%86%85%E5%AD%98%E7%AE%A1%E7%90%86%E7%9A%84%E4%B8%80%E4%BA%9B%E5%B0%8F%E7%96%91%E9%97%AE/)
- [Java源码分析 一线互联网公司Java程序员源码面试集锦-说明了栈内存这块](https://www.bilibili.com/video/av63568054/?p=1)
- [垃圾回收说的最好的--咱们从头到尾说一次 Java 垃圾回收](https://mp.weixin.qq.com/s?__biz=MzIxMzk3Mjg5MQ==&mid=2247484435&idx=1&sn
=480178f0cad18f06f05ded61a9d55fb1&chksm=97afe6e7a0d86ff18a2250d4ed03182288f958733e557dbd4ba7f82310ca891db5b779379a2e&mpshare=1&scene=1&srcid=#rd)
- [死磕并发：Java内存模型](https://mp.weixin.qq.com/s?__biz=MzA3ODQ0Mzg2OA==&mid=2649050490&idx=2&sn=10684d5ced5a260c15615a47540f93b5&chksm=87534949b024c05f16fe46897bfad880de6ccced16cd196e6fa1833317f02a3d701e2b1b8554&mpshare=1&scene=1&srcid=&sharer_sharetime=1570966753964&sharer_shareid=30cd4d0cc6593e119b916aff48202a03&key=9a546c57841d73605d9ba86ce8f478abae5f661f0e35be4c78d9f5498a627bcfb28f4015ce9ae19da29c7a4b0d4b2f8f7e66b7cb3263a9ce099c3dd950ed7ffd0e7be1be85c05a9767a18af2ece33093&ascene=1&uin=MjMzNDY0MzcwMQ%3D%3D&devicetype=Windows+10&version=62060841&lang=zh_CN&pass_ticket=4viFmmbUVZ9%2FJTtdg4zszYtWN6PnO5ajCNX7I4T%2BO4pW9Zh0pzuV7X3vi64ph4k%2F)
- [Java内存模型详解(一)](https://mp.weixin.qq.com/s?__biz=Mzg3NDA4MjYyOQ==&mid=2247484083&idx=1&sn=02db9a9b4800c12808fc25807222041f&scene=21#wechat_redirect)
- [JVM 中你不可不知的参数](https://zhuanlan.zhihu.com/p/91757020)
* [JVM 优化经验总结](https://www.ibm.com/developerworks/cn/java/j-lo-jvm-optimize-experience/index.html)
* [Java Platform, Standard Edition HotSpot Virtual Machine Garbage Collection Tuning Guide 参数默认值](https://docs.oracle.com/javase/8/docs/technotes/guides/vm/gctuning/parallel
.html#default_heap_size)
- [图比较好-JVM内存模型](https://juejin.im/post/5ad5c0216fb9a028e014fb63)
- [JVM参数分类](https://zhanglijun1217.github.io/blog/2019/08/07/jvm%E5%8F%82%E6%95%B0%E5%88%86%E7%B1%BB/)
- [理解JVM（4）- 堆内存的分代管理](https://www.jianshu.com/p/5946c0a414b5)
- [视频教程-深入理解Java虚拟机](https://www.bilibili.com/video/av53020056?p=2)
- [JVM是怎么和操作系统交互的？](https://mp.weixin.qq.com/s?__biz=MzU0MzQ5MDA0Mw==&mid=2247488270&idx=2&sn=cdcbe762281c6868eb8933e310cf616e&chksm=fb0bf99acc7c708cb890c9d29a7852169aa7f02f9e17fe9e4400ddd208d387e4001ca534465a&mpshare=1&scene=1&srcid=&sharer_sharetime=1574988850476&sharer_shareid=30cd4d0cc6593e119b916aff48202a03&key=e1706a134ae79356ca9aa7e313fd75f48f35013699899fdec9fd23e54ef2bf7266ad98bcaea56240d60185d3992dc0a9489d6a3d7f5f5127d2f706952b5dc2d3f83ecd6790c10287af87e06ac8188c21&ascene=1&uin=MjMzNDY0MzcwMQ%3D%3D&devicetype=Windows+10&version=62070158&lang=zh_CN&pass_ticket=k1D4gVZECqwX4NqTdOTlM0Lwq9uYdJ8C23KxLovq6rfPu2j5HOStineTWWPcQlz1)