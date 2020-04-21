## [java](https://www.trinea.cn/android/localbroadcastmanager-impl/)

##### （一） java基础知识点

##### java数据类型

- [java中==和equals和hashCode的区别](https://www.jianshu.com/p/585d8f444bc0)
- [int、char、long各占多少字节数](https://www.jianshu.com/p/3a0cc6a370e1)
- [int与integer的区别](https://www.jianshu.com/p/0dbfcbd42f02)
- [String、StringBuffer、StringBuilder区别](https://blog.csdn.net/u011702479/article/details/82262823)
  - StringBuilder 维护一个数组
  - StringBuffer 在一些关键的方法上增加了 同步
##### java 类接口
- [抽象类和接口区别](https://www.cnblogs.com/catluo/p/10803970.html)
- [抽象类的意义](https://blog.csdn.net/github_37130188/article/details/89931962)
- [抽象类与接口的应用场景](https://www.jianshu.com/p/ee3c57289ddd)
- 抽象类是否可以没有抽象方法和属性？
- [接口的意义](https://www.jianshu.com/p/2aaac0941aee)
- 静态属性和静态方法是否可以被继承？是否可以被重写？以及原因？
- [父类的静态方法能否被子类重写](https://www.jianshu.com/p/15e21428d884)
- 静态内部类的设计意图
- [什么是内部类？内部类的作用](https://www.jianshu.com/p/06bc1ac4a0a1)
- [成员内部类、静态内部类、局部内部类和匿名内部类的理解，以及项目中的应用](https://www.cnblogs.com/latter/p/5665015.html)
- [闭包和局部内部类的区别](https://www.jianshu.com/p/f55b11a4cec2)
##### java 范型
- [泛型中extends和super的区别](https://www.jianshu.com/p/d357b044978a)
##### java 异常
- [【Java】try-catch-finally语句中return的执行顺序思考](https://blog.csdn.net/u010983881/article/details/78053673)
- [final，finally，finalize的区别](https://www.jianshu.com/p/f94fd0812048)
- [Java的异常体系](https://www.cnblogs.com/aspirant/p/10790803.html)

##### java IO

- [Java有几种文件拷贝方式？哪一种最高效？](https://blog.csdn.net/weixin_40805079/article/details/86551991)
- 

##### （二） java深入源码级的面试题（有难度）
##### java 数据类型

- [string 转换成 integer的方式及原理](https://www.jianshu.com/p/9eebb4f2ccb1)
- [utf-8编码中的中文占几个字节；int型几个字节？](https://zhidao.baidu.com/question/1945589025310630548.html)
- [Java中String的了解](https://www.cnblogs.com/xiaoxi/p/6036701.html)
- [String为什么要设计成不可变的？](https://baijiahao.baidu.com/s?id=1640190566307184844&wfr=spider&for=pc)

##### java 类

- 修改对象A的equals方法的签名，那么使用HashMap存放这个对象实例的时候，会调用哪个equals方法？
- [Object类的equal和hashCode方法重写，为什么？](https://blog.csdn.net/m0_37462976/article/details/77866572)

##### java特性

- [Java中实现多态的机制是什么？](https://blog.csdn.net/qzh_ks/article/details/80482584)
- 

##### java范型

- [深入学习Java中的泛型](https://www.cnblogs.com/aimei/p/12200884.html)
- [说一下泛型原理，并举例说明](https://www.cnblogs.com/xunzhi/p/5683709.html)
##### java反射

- [说说你对Java反射的理解](https://www.cnblogs.com/yougewe/p/10125073.html)
- 反射及动态代理模式
- [说说你对Java注解的理解](https://blog.csdn.net/zhang0558/article/details/52643016)
- [说说你对依赖注入的理解](https://wenku.baidu.com/view/b77a0bfb700abb68a982fb85.html)

##### java IO

- [java笔记七：IO流之字节流与字节缓冲流](https://www.cnblogs.com/shamo89/p/9860582.html)
- [使用FileChannel(文件通道)来实现文件快速复制(transferTo)](https://blog.csdn.net/weixin_36586120/article/details/88756436)

##### java API
- [Java的Comparator升序降序的记法](https://www.cnblogs.com/jingpeng77/p/10098933.html)
- [Collections.sort使用的排序方式](https://blog.csdn.net/u011410529/article/details/56668545)
- [深入理解final关键字的作用](https://www.jianshu.com/p/2b17e3daaff0)
- [讲一下常见编码方式？](https://www.cnblogs.com/mlan/p/7823375.html)

##### （三） 数据结构
- [常用数据结构简介](https://blog.csdn.net/yeyazhishang/article/details/82353846)
- [java并发集合了解哪些？](https://www.cnblogs.com/zengxianxi/p/3607953.html)
- [列举java的集合以及集合之间的继承关系](https://www.jianshu.com/p/e203b23acf45)
- [集合类以及集合框架](https://blog.csdn.net/ccj_ok/article/details/77986307)
- 容器类介绍以及之间的区别（容器类估计很多人没听这个词，Java容器主要可以划分为4个部分：List列表、Set集合、Map映射、工具类（Iterator迭代器、Enumeration枚举类、Arrays和Collections），具体的可以看看这篇博文 [Java容器类](http://alexyyek.github.io/2015/04/06/Collection/)）
- [List,Set,Map的区别](https://www.cnblogs.com/IvesHe/p/6108933.html)
- List和Map的实现方式以及存储方式
- [SparseArray源码解析](https://www.jianshu.com/p/1739363c0e50)
  - key只能是int值
  - 默认大小为10
  - key是一个数组
  - value是一个数组
- HashMap的实现原理
- HashMap多线程死循环问题
- [HashMap 用可变对象作为 key 踩坑](https://icharle.com/hashmapkebianobj.html)
- [HashMap数据结构？](https://www.jianshu.com/p/8b372f3a195d)
- [HashMap源码理解](https://blog.csdn.net/m0_37914588/article/details/82287191)
- [Java 8系列之重新认识HashMap](https://zhuanlan.zhihu.com/p/21673805)
- [ConcurrentHashMap的实现原理](https://blog.csdn.net/lsgqjh/article/details/54867107)
- [ArrayMap和HashMap的对比](https://blog.csdn.net/vansbelove/article/details/52422087)
- [深入剖析 Android中的 ArrayMap](http://www.imooc.com/article/80448)
- [深度解读ArrayMap优势与缺陷](https://blog.csdn.net/gityuan/article/details/100570134)
- HashTable实现原理
- TreeMap具体实现
- [HashMap、TreeMap、HashTable区别](https://blog.csdn.net/Jason847/article/details/78050358)
- [HashMap和HashTable的区别](https://blog.csdn.net/u010983881/article/details/49762595)
- HashMap与HashSet的区别
- HashSet与HashMap怎么判断集合元素重复？
- 集合Set实现Hash怎么防止碰撞
- ArrayList和LinkedList的区别，以及应用场景
- [Java ArrayList、LinkedList、Vector的区别](https://blog.csdn.net/zhangqiluGrubby/article/details/72870493)
- 数组和链表的区别
- 堆的结构
- 堆和树的区别
- 堆和栈在内存中的区别是什么(解答提示：可以从数据结构方面以及实际实现方面两个方面去回答)？
- 什么是深拷贝和浅拷贝
- [手写链表逆序代码](https://www.jb51.net/article/133791.htm)
- 讲一下对树，B+树的理解
- 讲一下对图的理解
- 判断单链表成环与否？
- 二叉树的深度优先遍历和广度优先遍历的具体实现
- 链表翻转（即：翻转一个单项链表）
- 合并多个单有序链表（假设都是递增的）

##### （四） 线程、多线程和线程池

- [开启线程的三种方式？](https://www.jianshu.com/p/86e79c8306f0)
- 序列化的作用[Serializable 和Parcelable 的区别](https://www.cnblogs.com/yezhennan/p/5527506.html)
- [Parcelable原理](https://blog.csdn.net/u011315960/article/details/90634644)
  - 调用native代码，避免了大量的反射操作，减少了临时变量的创建
  - memcpy(https://blog.csdn.net/jxhgh/article/details/46859607)
- Android为什么引入Parcelable？
- 有没有尝试简化Parcelable的使用？
- 进程和线程的区别
- 剖析Android中进程与线程调度之nice
- [Android 线程间通信有哪几种方式](https://blog.csdn.net/liuxingyuzaixian/article/details/78893392)
- [Java 四种线程池的用法分析](https://blog.csdn.net/u011974987/article/details/51027795)
- [Android 线程和线程池一篇就够了](https://juejin.im/entry/593109e72f301e005830cd76)
- [java ThreadPoolExecutor 参数详解](https://segmentfault.com/a/1190000009111732)
- [聊聊并发（七）——Java中的阻塞队列](http://ifeve.com/java-blocking-queue/)
- 为什么要有线程，而不是仅仅用进程？
- run()和start()方法区别
- [如何控制某个方法允许并发访问线程的个数？](https://cloud.tencent.com/developer/article/1368378)
- 在Java中wait和seelp方法的不同；
- 谈谈wait/notify关键字的理解
- [什么导致线程阻塞？](https://blog.csdn.net/weixin_41101173/article/details/79679300)
- 线程如何关闭？
- 讲一下java中的同步的方法
- 数据一致性如何保证？
- 如何保证线程安全？
- 如何实现线程同步？
- 两个进程同时要求写或者读，能不能实现？如何防止进程的同步？
- 线程间操作List
- Java中对象的生命周期
- Synchronized用法
- [Java并发编程：Synchronized及其实现原理](https://www.cnblogs.com/paddix/p/5367116.html)
- 谈谈对Synchronized关键字，类锁，方法锁，重入锁的理解
- static synchronized 方法的多线程访问和作用
- 同一个类里面两个synchronized方法，两个线程同时访问的问题
- volatile的原理
- 聊聊并发（一）——深入分析Volatile的实现原理
- [谈谈volatile关键字的用法](https://www.cnblogs.com/awkflf11/p/9218414.html)
- [深入分析Volatile的实现原理](http://ifeve.com/volatile/)
- 谈谈NIO的理解
- synchronized 和volatile 关键字的区别
- synchronized与Lock的区别
- ReentrantLock 、synchronized和volatile比较
- [Unsafe 与 CAS](https://www.cnblogs.com/xrq730/p/4976007.html)
- Java CAS 和ABA问题
- [Java AtomicInteger原理分析](https://fangjian0423.github.io/2016/03/16/java-AtomicInteger-analysis/)
- [Java魔法类：Unsafe应用解析](https://tech.meituan.com/2019/02/14/talk-about-java-magic-class-unsafe.html)
- ReentrantLock的内部实现
- lock原理
- [CountDownLatch详解](https://www.jianshu.com/p/128476015902)
- [深入理解读写锁ReentrantReadWriteLock](https://www.jianshu.com/p/4a624281235e)
- [理解ReentrantLock的公平锁和非公平锁](https://www.jianshu.com/p/2ada27eee90b)
- [Java面试必问-死锁终极篇](https://juejin.im/post/5aaf6ee76fb9a028d3753534)
- [Java并发编程：CountDownLatch、CyclicBarrier和Semaphore](https://www.cnblogs.com/dolphin0520/p/3920397.html)
- [Java实现线程同步的几种方式](https://www.jianshu.com/p/6542c8a96392)
- [死锁的四个必要条件？](https://www.jianshu.com/p/688076925583)
  - 互斥条件
  - 请求和保持
  - 不剥夺
  - 循环等待
- 怎么避免死锁？
- 多线程的实现方法
- （synchronized和lock的异同）
- 对象锁和类锁是否会互相影响？
- 什么是线程池，如何使用?
- CAS介绍（这是阿里巴巴的面试题，我不是很了解，可以参考博客: [CAS简介](http://blog.csdn.net/jly4758/article/details/46673835)）
- Android性能优化之使用线程池处理异步任务
- Java的并发、多线程、线程模型
- 谈谈对多线程的理解
- 多线程有什么要注意的问题？
- 谈谈你对并发编程的理解并举例说明
- 谈谈你对多线程同步机制的理解？
- 如何保证多线程读写文件的安全？
- 多线程断点续传原理
- [主线程等待所有线程执行完毕，再执行某个特定任务怎么实现？原理和源码看过没？（Thread.join原理）](https://www.cnblogs.com/lcplcpjava/p/6896904.html)
- 断点续传的实现
- ELF文件格式解析

##### （五）并发编程有关知识点（这个是一般Android开发用的少的，所以建议多去看看）：

平时Android开发中对并发编程可以做得比较少，Thread这个类经常会用到，但是我们想提升自己的话，一定不能停留在表面，,我们也应该去了解一下java的关于线程相关的源码级别的东西。

**学习的参考资料如下：**

> Java 内存模型

- [java线程安全总结](http://www.iteye.com/topic/806990)
- [深入理解java内存模型系列文章](http://ifeve.com/java-memory-model-0/)

> 线程状态：

- [一张图让你看懂JAVA线程间的状态转换](https://my.oschina.net/mingdongcheng/blog/139263)

> 锁：

- [锁机制：synchronized、Lock、Condition](http://blog.csdn.net/vking_wang/article/details/9952063)
- [Java 中的锁](http://wiki.jikexueyuan.com/project/java-concurrent/locks-in-java.html)

> 并发编程：

- [Java并发编程：Thread类的使用](http://www.cnblogs.com/dolphin0520/p/3920357.html)
- [Java多线程编程总结](http://blog.51cto.com/lavasoft/27069)
- [Java并发编程的总结与思考](https://www.jianshu.com/p/053943a425c3#)
- [Java并发编程实战-----synchronized](http://www.cnblogs.com/chenssy/p/4701027.html)
- [深入分析ConcurrentHashMap](http://www.infoq.com/cn/articles/ConcurrentHashMap#)

#####  (六)Kotlin

- 谈谈对kotlin的理解
- Kotlin 相关from-java-to-kotlin
- kotlin_tips
- 从原理分析Kotlin的延迟初始化: lateinit var和by lazy
- 使用Kotlin Reified 让泛型更简单安全
- Kotlin里的Extension Functions实现原理分析
- Kotlin系列之顶层函数和属性
- Kotlin 兼容 Java 遇到的最大的 “坑”
- Kotlin 的协程用力瞥一眼
- Kotlin 协程「挂起」的本质
- 到底什么是「非阻塞式」挂起？协程真的更轻量级吗？
- 资源混淆是如何影响到Kotlin协程的
- Kotlin Coroutines(协程) 完全解析
- 破解 Kotlin 协程

##### （七）JVM

- [哪些情况下的对象会被垃圾回收机制处理掉？](https://cloud.tencent.com/developer/article/1332790)
- [谈谈你对解析与分派的认识。](https://blog.csdn.net/u011080472/article/details/51334288)
- [谈谈对ClassLoader(类加载器)的理解](https://blog.csdn.net/github_37130188/article/details/97255131)
- 关于JAVA中的Class.cast方法
- [理解Java中的弱引用](https://droidyue.com/blog/2014/10/12/understanding-weakreference-in-java/)
- [理解Java的强引用、软引用、弱引用和虚引用](https://juejin.im/post/5b82c02df265da436152f5ad)
- 谈谈对动态加载（OSGI）的理解
- 内存对象的循环引用及避免
- 内存回收机制、GC回收策略、GC原理时机以及GC对象
- 垃圾回收机制与调用System.gc()区别
- 虚拟机原理，如何自己设计一个虚拟机(内存管理，类加载，双亲委派)
- 谈谈你对双亲委派模型理解
- JVM内存模型，内存区域
- [类加载机制](https://www.jianshu.com/p/3556a6cca7e5)
- java虚拟机的特性
- [谈谈对jvm的理解](https://blog.csdn.net/yinni11/article/details/80917652)
- [JVM类加载机制详解（二）类加载器与双亲委派模型](https://blog.csdn.net/zhangliangzi/article/details/51338291)
- [JVM类加载机制详解（一）JVM类加载过程](https://blog.csdn.net/zhangliangzi/article/details/51319033)
- [JVM内存区域，开线程影响哪块内存](https://blog.csdn.net/github_37130188/article/details/96509321)
- [Java反射在JVM的实现](https://blog.csdn.net/jim__charles/article/details/52815318)
- [对Dalvik、ART虚拟机有什么了解？](https://blog.csdn.net/github_37130188/article/details/89577492)
- [Art和Dalvik对比](https://www.jianshu.com/p/59d98244fb52)
- [Java中的堆和栈的区别](https://droidyue.com/blog/2014/12/07/differences-between-stack-and-heap-in-java/)
- 强引用置为null，会不会被回收？
- [java中的四种引用的区别以及使用场景](https://blog.csdn.net/github_37130188/article/details/89857016)
- [Java内存管理：深入Java内存区域](https://www.cnblogs.com/gw811/archive/2012/10/18/2730117.html)
- JVM 的工作原理，层次结构以及 GC 工作原理

------


## 二、Android面试题

Android面试题包括Android基础，还有一些源码级别的、原理这些等。所以想去大公司面试，一定要多看看源码和实现方式，常用框架可以试试自己能不能手写实现一下，锻炼一下自己。

##### （一）Android基础知识点
##### Android四大组件
- 四大组件是什么
- 四大组件的生命周期和简单用法
###### Activity

- [Activity之间的通信方式](https://www.jianshu.com/p/12438e23c6b8)
- Activity各种情况下的生命周期
- [Activity的启动方式和flag详解](https://blog.csdn.net/singwhatiwanna/article/details/9294285)
- [AlertDialog,popupWindow,Activity区别](https://blog.csdn.net/github_35186068/article/details/81663185)
- Application 和 Activity 的 Context 对象的区别
- Activity上有Dialog的时候按Home键时的生命周期
- 两个Activity 之间跳转时必然会执行的是哪几个方法？
- 前台切换到后台，然后再回到前台，Activity生命周期回调方法。弹出Dialog，生命值周期回调方法。
- Activity的四种启动模式对比
- Activity状态保存于恢复

###### Services

- Activity 怎么和Service 绑定？
- [bindServices过程](https://www.jianshu.com/p/03fb12a96b30)
- 怎么在Activity 中启动自己对应的Service？
- [service和activity怎么进行数据交互？](https://www.cnblogs.com/l2rf/p/5953214.html)
  - 广播
  - bindServices
- Service的开启方式
- 请描述一下Service 的生命周期

###### ContentProvider

- [谈谈你对ContentProvider的理解](https://www.jianshu.com/p/9fdc894fb97c)
- [说说ContentProvider、ContentResolver、ContentObserver 之间的关系](https://blog.csdn.net/github_37130188/article/details/89321609)

###### BrocaseReceiver

- 请描述一下广播BroadcastReceiver的理解
- [广播的分类](https://blog.csdn.net/carson_ho/article/details/53160580)
  - 普通广播（Normal Broadcast）
    - 开发者自定义的intent的广播
  - 系统广播（System Broadcast）
    - 网络变化、安装卸载等
  - 有序广播（Ordered Broadcast）
    - 发送出去的广播按照接受的先后顺序进行接受
  - 粘性广播（Sticky Broadcast）
  - App应用内广播（Local Broadcast）
- 广播使用的方式和场景
- 在manifest 和代码中如何注册和使用BroadcastReceiver?
- [LocalBroadcastManager 的实现原理，与 BroadcastReceiver 异同](https://www.trinea.cn/android/localbroadcastmanager-impl/)
- 本地广播和全局广播有什么差别？
- BroadcastReceiver，LocalBroadcastReceiver 区别

##### Fragment

- Activity与Fragment之间生命周期比较

- fragment各种情况下的生命周期
- Fragment状态保存startActivityForResult是哪个类的方法，在什么情况下使用？
- 如何实现Fragment的滑动？
- [Fragment原理分析](https://blog.csdn.net/zhaoyw2008/article/details/50744839)
- [Fragment是什么？为什么要用Fragment：](https://www.cnblogs.com/cr330326/p/5712022.html)
- [Activity与fragment之间传递数据的方式？](https://juejin.im/entry/59746af7f265da6c34337d2e)
  - Handler
  - 广播
  - 接口
  - EventBus
  - Bundle和setArguments(bundle)
- [fragment之前传递数据](https://www.jianshu.com/p/f87baad32662)
  - 根据tag获取到Fragment的，调用方法
  - 创建接口
  - Eventbus
##### Android View容器

- LinearLayout、RelativeLayout、FrameLayout的特性及对比，并介绍使用场景。
- 介绍下SurfView
- [RecycleView的使用](https://www.kymjs.com/code/2016/07/10/01/)
  - 回收与复用Recycler
    - 第一级缓存 mCacheViews,如果仍依赖于 RecyclerView （比如已经滑动出可视范围，但还没有被移除掉），但已经被标记移除的 ItemView 集合会被添加到 mAttachedScrap 中。然后如果 mAttachedScrap 中不再依赖时会被加入到 mCachedViews 中。 mChangedScrap 则是存储 notifXXX 方法时需要改变的 ViewHolder 。
    - 第二级缓存,**ViewCacheExtension** 是一个抽象静态类，用于充当附加的缓存池，当 RecyclerView 从第一级缓存找不到需要的 View 时，将会从 **ViewCacheExtension** 中找。不过这个缓存是由开发者维护的，如果没有设置它，则不会启用。通常我们也不会去设置他，系统已经预先提供了两级缓存了，除非有特殊需求，比如要在调用系统的缓存池之前，返回一个特定的视图，才会用到他。
    - 第三级缓存：最强大的缓存器。之前讲了，与 ListView 直接缓存 ItemView 不同，从上面代码里我们也能看到，RecyclerView 缓存的是 ViewHolder。而 ViewHolder 里面包含了一个 View 这也就是为什么在写 Adapter 的时候 必须继承一个固定的 ViewHolder 的原因。首先来看一下 RecycledViewPool

##### Android 动画
- [Android属性动画特性](https://blog.csdn.net/weixin_44046503/article/details/93137524)
- 差值器
- 估值器

##### Android 其他

- 谈谈对接口与回调的理解
- 回调的原理
- 写一个回调demo
- Android中数据存储方式

##### Android WebView

- [Android Webview H5 秒开方案实现](https://www.jianshu.com/p/85e4f982cbdf)
- Android Webview独立进程架构实战
- WebView性能、体验分析与优化

##### （二）Android源码相关分析

- [Android 高级面试高频知识点](https://www.jianshu.com/p/6d56690ef510)
- Android年薪百万的进阶攻略-PKMS

##### Android 四大组件

###### Activity

- [startActivity启动过程分析](http://gityuan.com/2016/03/12/start-activity/)
- [Android 源码解析 之 setContentView](https://blog.csdn.net/lmj623565791/article/details/41894125)
- ActivityThread，AMS，WMS的工作原理
- LaunchMode应用场景

######  Services

- [startService启动过程分析](http://gityuan.com/2016/03/06/start-service/)
- AndroidService与Activity之间通信的几种方式
- [Android IntentService完全解析 当Service遇到Handler](https://www.jianshu.com/p/6d56690ef510)
- 说说Activity、Intent、Service 是什么关系
- ApplicationContext和ActivityContext的区别

###### ContentProvider

- 请介绍下ContentProvider 是如何实现数据共享的？

###### BrocaseReceiver

##### Androud 动画

- Android动画框架实现原理

##### Android View 容器

- [SurfaceView 的原理](https://www.jianshu.com/p/239536901078)
- Choreographer 结合 View 刷新
- VSYNC、双缓冲、三缓冲
- SurfaceFlinger
- RecycleView原理

##### Android View

- [Requestlayout，onlayout，onDraw，DrawChild区别与联系](https://blog.csdn.net/weixin_41101173/article/details/79726311)
- [invalidate和postInvalidate的区别及使用](https://blog.csdn.net/mars2639/article/details/6650876)
- Activity-Window-View三者的差别
- 自定义View如何考虑机型适配
- 自定义View的事件
- 封装View的时候怎么知道view的大小

##### Android 其他

- Android各个版本API的区别
- [Android源码分析-资源加载机制](https://blog.csdn.net/singwhatiwanna/article/details/24532419)
- 低版本SDK如何实现高版本api？

##### Android 事件分发

- InputManagerServices

##### Application

- [Application启动过程分析](https://juejin.im/post/582583c95bbb50005915045a)
- 进程和 Application 的生命周期
- [Android Context完全解析，你所不知道的Context的各种细节](https://blog.csdn.net/guolin_blog/article/details/47028975)

- Bitmap对象的理解
- 为什么主线程不会因为 Looper 阻塞：系统每 16ms 会发送一个刷新 UI 消息唤醒
- AndroidManifest的作用与理解
- Android应用进程的管理 以及保活拉活的那些事儿
- SP是进程同步的吗?有什么方法做到同步？
- [Android之SharedPreferences内部原理浅析](https://blog.csdn.net/u010687392/article/details/50174271)
- Google Exoplayer之全面认识
- 告别繁琐的AIDL，IPC通信框架设计与实现
- 谈谈多线程在Android中的使用
- AsyncTask 如何使用?

##### （三）常见的一些原理性问题

- [SwipeRefreshLayout 源码解析](https://juejin.im/entry/57c93f6bc4c971005425b00c)

-  [Android NestedScrolling机制完全解析 带你玩转嵌套滑动](https://blog.csdn.net/lmj623565791/article/details/52204039)

- [Handler机制和底层实现](https://blog.csdn.net/itheimach/article/details/51170857)

- [Handler nativePollOnce](https://juejin.im/post/59dc75cc6fb9a0452340d4c4)

- 从架构师的角度分析AndroidHandler源码的正确姿势

- [Android I/O 那些事儿](https://isuperqiang.cn/post/android-io-na-xie-shi-er/)

- [10分钟了解Android项目构建流程](https://juejin.im/post/5a69c0ccf265da3e2a0dc9aa)

- [Handler、Thread和HandlerThread的差别](https://blog.csdn.net/weixin_41101173/article/details/79687313)

- [HandlerThread源码解析](https://www.cnblogs.com/leipDao/p/8005520.html)

- handler发消息给子线程，looper怎么启动？

- Hanlder消息延迟原理

- 关于Handler，在任何地方new Handler 都是什么线程下?

- ThreadLocal原理，实现及如何保证Local属性？

- [理解Java中的ThreadLocal](https://droidyue.com/blog/2016/03/13/learning-threadlocal-in-java/index.html)

- 请解释下在单线程模型中Message、Handler、Message Queue、Looper之间的关系

- [Android源码分析-消息队列和Looper](https://blog.csdn.net/singwhatiwanna/article/details/17361775)

- [Android中Thread、Handler、Looper、MessageQueue的原理分析](https://blog.csdn.net/bboyfeiyu/article/details/38555547)

- 请描述一下View事件传递分发机制

- [Toast 原理剖析](http://thinkdevos.net/2017/10/13/2017-10-13-toast/)

- Touch事件传递流程

- [事件分发中的onTouch 和onTouchEvent 有什么区别，又该如何使用？](https://blog.csdn.net/github_37130188/article/details/89112747)

- [View和ViewGroup分别有哪些事件分发相关的回调方法](https://blog.csdn.net/github_37130188/article/details/89112835)

- 说一下View的事件分发机制

- View刷新机制

- View绘制流程

- Android View的绘制流程知识点总结

- [深入理解Android之View的绘制流程](https://www.jianshu.com/p/060b5f68da79)

- 自定义控件原理

- [自定义View如何提供获取View属性的接口？](https://blog.csdn.net/github_37130188/article/details/89075593)

- AsyncTask机制

- [Android AsyncTask 源码解析](https://blog.csdn.net/lmj623565791/article/details/38614699)

- [AsyncTask原理及不足](https://www.jianshu.com/p/7ad6b5a94e94)

- [Android源码分析—带你认识不AsyncTask](https://blog.csdn.net/singwhatiwanna/article/details/17596225)

- [如何取消AsyncTask？](https://blog.csdn.net/zgljl2012/article/details/47258301/)

- [为什么不能在子线程更新UI？](https://www.jianshu.com/p/29e75093f5a2)

- ContentProvider的权限管理(解答：读写分离，权限控制-精确到表级，URL控制)

- [如何通过广播拦截和abort一条短信？](https://blog.csdn.net/github_37130188/article/details/89321637)

- 广播是否可以请求网络？

- 广播引起anr的时间限制是多少？

- [计算一个view的嵌套层级](https://blog.csdn.net/github_37130188/article/details/89075808)

- Activity栈

- Android线程有没有上限？

- [线程池有没有上限？](https://blog.csdn.net/weixin_44181382/article/details/102713078)

- ListView重用的是什么？

- 


##### （四）开发中常见的一些问题

- [ListView 中图片错位的问题是如何产生的?](https://blog.csdn.net/github_37130188/article/details/89648006)
- 滑动banner到最后一页然后再翻页到下一个tab的实现原理
- 每次遇到滑动冲突都头大Leo带你寻找事件冲突的根源
- [屏幕适配的处理技巧都有哪些?](https://www.jianshu.com/p/ec5a1a30694b)
  - 使用dp
  - 使用相对布局，不要使用绝对布局
  - 支持wrap_content，match_parent
- 使用相对布局，
- 尺寸限定，不同的目录
- dp
- match warp
- 图片资源”匹配
- 服务器只提供数据接收接口，在多线程或多进程条件下，如何保证数据的有序到达？
- [动态布局的理解](https://blog.csdn.net/github_37130188/article/details/89648040)
- [怎么去除重复代码？](https://blog.csdn.net/github_37130188/article/details/89648077)
  - 布局重复
  - 代码重复
- 画出 Android 的大体架构图
- Android系统架构
- RecyclerView性能为什么这么好？深度解析它的缓存机制
- ViewPager 源码解析与性能优化
- CardView+RecyclerView实现一线名企的UI炫酷界面
- [Recycleview和ListView的区别](https://www.jianshu.com/p/257c279a3493)
  - 缓存机制 ( RecyclerView的优势在于a.mCacheViews的使用),b.mRecyclerPool可以供多个RecyclerView共同使用
  - 缓存不同
  - 局部刷新
- [ListView图片加载错乱的原理和解决方案](https://www.jianshu.com/p/0aa4dc6e1208)
- [ListView源码解析](https://blog.csdn.net/guolin_blog/article/details/44996879)
- 动态权限适配方案，权限组的概念
- [Android系统为什么会设计ContentProvider？](https://blog.csdn.net/github_37130188/article/details/89648175)
- 下拉状态栏是不是影响activity的生命周期
- 如果在onStop的时候做了网络请求，onResume的时候怎么恢复？
- [Bitmap 使用时候注意什么？](https://www.jianshu.com/p/fbf5a310788c)
  - 选择合适的图片规格
  - 降低采样率
  - 复用内存
  - 及时回收
  - 压缩图片
  - 
- [Bitmap的recycler()](https://blog.csdn.net/github_37130188/article/details/89684423)
- [Android中开启摄像头的主要步骤](https://www.jb51.net/article/87424.htm)
- ViewPager2重大更新，支持offscreenPageLimit
- [ViewPager使用细节，如何设置成每次只初始化当前的Fragment，其他的不初始化？](https://blog.csdn.net/github_37130188/article/details/89684440)
- [点击事件被拦截，但是想传到下面的View，如何操作？](https://www.jianshu.com/p/7e92121814ed)
- [权限管理系统（底层的权限是如何进行 grant 的）？](https://blog.csdn.net/github_37130188/article/details/89463350)
- 微信主页面的实现方式
- 微信上消息小红点的原理

##### （五）Android系统

- 简述Activity启动全部过程
- [【凯子哥带你学Framework】Activity启动过程全解析](https://blog.csdn.net/zhaokaiqiang1992/article/details/49428287)
- [【凯子哥带你学Framework】Activity界面显示全解析](https://blog.csdn.net/zhaokaiqiang1992/article/details/49681321)
- [Android LayoutInflater原理分析，带你一步步深入了解View(一)](https://blog.csdn.net/guolin_blog/article/details/12921889)
- [App启动流程，从点击桌面开始](https://yq.aliyun.com/articles/26960)
- [由App的启动说起 | jaminzzhang](https://yq.aliyun.com/articles/26960)
- [Android内核开发：图解Android系统的启动过程](https://blog.51cto.com/ticktick/1659473)
- 说一下View从app启动到显示在界面上的绘制流程
- Android为每个应用程序分配的内存大小是多少？
- Android中进程内存的分配，能不能自己分配定额内存？
- 进程保活的方式
- 如何保证一个后台服务不被杀死？（相同问题：如何保证service在后台不被kill？）比较省电的方式是什么？
- App中唤醒其他进程的实现方式
- 系统启动流程是什么？（提示：Zygote进程 –> SystemServer进程 –> 各种系统服务 –> 应用进程）
- 谈谈你对安卓签名的理解。
- 请解释安卓为啥要加签名机制?
- 对于应用更新这块是如何做的？(解答：灰度，强制更新，分区域更新)？
- [MeasureSpec](https://blog.csdn.net/sinat_29874521/article/details/79994169)



------

## 三、高端技术面试题

**这里讲的是大公司需要用到的一些高端Android技术，这里专门整理了一个文档，希望大家都可以看看。这些题目有点技术含量，需要好点时间去研究一下的。**

##### （一）图片

- 网络框架对比和源码分析

- 图片库对比

- 图片库的源码分析

- 图片框架缓存实现

- [LRUCache原理](https://www.jianshu.com/p/b49a111147ee)

- 图片加载原理

- 自己去实现图片库，怎么做？

- [Glide源码解析]()

- Glide使用什么缓存？

- Glide内存缓存如何控制大小？

- [Fresco图片框架内部实现原理探索](https://blog.csdn.net/u010687392/article/details/50266633)
  
  - 可以用这个学习一下mvc
  
- [彻底弄懂 GLIDE V4 之宏观原理分析](http://yinshudi.com/2019/01/03/%E5%BD%BB%E5%BA%95%E5%BC%84%E6%87%82%20Glide%20v4%20%E4%B9%8B%E5%AE%8F%E8%A7%82%E5%8E%9F%E7%90%86%E5%88%86%E6%9E%90/)
  - 生命周期
  - 图片宽高
  - 缩略图、展位图
  - 缓存实现
  - 缓存的Key
  - 图片加载 HttpUrlFetcher
  - 加载线程图和管理
  
- [WebP原理和Android支持现状介绍](https://zhuanlan.zhihu.com/p/23648251)

- [WebP 技术原理及应用](https://www.jianshu.com/p/7fb720ec57cd)

- [浓缩的才是精华：浅析 GIF 格式图片的存储和压缩](https://cloud.tencent.com/developer/article/1004763)

- [高效加载大型位图](https://developer.android.com/topic/performance/graphics/load-bitmap)

- [Android 高清加载巨图方案 拒绝压缩图片](https://blog.csdn.net/lmj623565791/article/details/49300989)
  
  - 局部加载
  
- [Lottie 动画原理剖析](http://ivanfan.site/2018/07/01/Lottie%E5%8A%A8%E7%94%BB/)

- [SVGA 背后的故事](https://www.jianshu.com/p/dfa16d9d67cd)

- [拆轮子系列：拆 Okio](https://blog.piasy.com/2016/08/04/Understand-Okio/index.html)

- [okhttp源码解析](https://www.jianshu.com/p/82f74db14a18)

  - 

- [拆轮子系列：拆 OkHttp](https://blog.piasy.com/2016/07/11/Understand-OkHttp/index.html)
  
  - 配置参数进行执行，getResponseWithInterceptorChain();   
  - 有几个intercept
  
- [Retrifit源码解析](https://www.jianshu.com/p/c72fa159d7e9)

- [拆轮子系列：拆 Retrofit](https://blog.piasy.com/2016/06/25/Understand-Retrofit/index.html)

  - 构造者模式创建Retrofit。

  - 外观模式通过一个高层次的接口使得子系统更容易使用

  - 通过动态代理创建实例

    - 创建委托类

    - 实现invocationHandler接口

    - #### Proxy对象生成代理对象

  - ### `ServiceMethod`把接口调用转化为一次HTTP调用

    - callFactory OKHTTP 负责创建HTTP请求
    - callAdapter把把 `retrofit2.Call` 转为 `T`，生成Observable
    - responseConverter负责把服务器返回的数据转化为 `T` 类型的对象
    - parameterHandlers则负责解析 API 定义时每个方法的参数，并在构造 HTTP 请求时设置参数；

  - 通过工厂模式分别提供不同的模块
  
- [Android Volley完全解析(四)，带你从源码的角度理解Volley](https://blog.csdn.net/guolin_blog/article/details/17656437)

- [网络请求缓存处理，okhttp如何处理网络缓存的](https://blog.csdn.net/weixin_40255793/article/details/81018358)

- 从网络加载一个10M的图片，说下注意事项

- 谈谈对Volley的理解

- 描述一次网络请求的流程

- HttpUrlConnection 和 okhttp关系

- AstncTask+HttpClient 与 AsyncHttpClient有什么区别？

##### （二）开源库源码分析

- [RxJava的功能与原理实现](https://www.jianshu.com/p/cd3557b1a474)
- [RxJava的作用，与平时使用的异步操作来比的优缺点](https://www.jianshu.com/p/8f6c64464e01)
- [说说EventBus作用，实现方式，代替EventBus的方式](https://www.jianshu.com/p/d9516884dbd4)
- 用到的一些开源框架，介绍一个看过源码的，内部实现过程。
- 谈谈对RxJava的理解

##### （五）插件化、模块化、组件化、热修复、增量更新、Gradle

- [Android插件化库比较](https://blog.csdn.net/u013435893/article/details/78972782)
- [深入理解Android插件化技术](https://zhuanlan.zhihu.com/p/33017826)
- [Android 插件化 -- ClassLoader 源码分析](https://www.heqiangfly.com/2017/05/18/android-plugins-dynamic-load-source-code-analysis/)
- [Android热补丁之Tinker原理解析](http://w4lle.com/2016/12/16/tinker/index.html)
- [Android插件化原理解析——Hook机制之动态代理](https://blog.csdn.net/csdn_aiyang/article/details/79085039)
- Android 动态代理与Hook机制详解
- MultiDex工作原理分析和优化方案
- Android 一种在Dalvik虚拟机上多Dex加载优化的方案
- Android 8.0 中的 ART 功能改进
- 组件化路由实现(ARoute：通过 APT 解析 @Route 等注解，结合 JavaPoet 生成路由表，即路由与 Activity 的映射关系)
- DEX、ODEX、OAT文件&Dalvik和ART虚拟机
- art dex2oat 加载加速浅析
- 剖析 Android ART Runtime (1) - 背景知识
- 剖析 Android ART Runtime (2) – dex2oat
- 剖析 Android ART Runtime (3) – Compilerb
- Android ART运行时无缝替换Dalvik虚拟机的过程分析
- 入门ART虚拟机(1)——加载DEX文件
- 入门ART虚拟机(5)——OAT文件
- Android运行时ART加载OAT文件的过程分析
- Android App Bundle 构建流程浅析
- 系统级插件化？Google全新的动态化框架Android App Bundles分析
- 深入解读Android新特性——App Bundles
- 基于Android App Bundle的动态化方案探索
- Qigsaw - dynamic modularization library
- Android 组件化最佳实践
- Android组件化方案及组件消息总线modular-event实战
- 描述清点击 Android Studio 的 build 按钮后发生了什么
- Android Gradle Plugin 源码分析
- Android Gradle Plugin 源码阅读与编译
- Improving Android Build Performance
- Using Gradle's Worker API to reduce build time
- Gradle 学习之 Android 插件的 Transform API
- Android AOP三剑客之AspectJ
- Android AOP三剑客之APT
- Android AOP三剑客之Javassist
- Chapter-ASM - Android 开发高手课
- matrix-gradle-plugin - matrix
- Android Lint增量扫描实战纪要
- 便于性能分析的日志框架hugo
- WMRouter：美团外卖Android开源路由框架
- ARouter - Android App 进行组件化改造的路由框架
- 滴滴开源 Booster：移动APP质量优化框架
- 对热修复和插件化的理解
- 插件化原理分析
- 模块化实现（好处，原因）
- 热修复,插件化
- 项目组件化的理解
- 描述清点击 Android Studio 的 build 按钮后发生了什么
- Android组件化，Transfrom和切面编程
- 什么是函数式编程

##### （六）架构设计和设计模式

- 谈谈你对Android设计模式的理解
- 如何正确地写出单例模式
- 从零开始MVVM新闻客户端架构实战
- [单例设计模式都写写，静态内部类是怎么保证线程安全的？](https://blog.csdn.net/mnb65482/article/details/80458571)
- MVC MVP MVVM原理和区别
- MVC MVP MVVM的演化过程
- android mvvm architecture-samples
- 你所知道的设计模式有哪些？
- 项目中常用的设计模式
- [手写生产者/消费者模式](https://www.jianshu.com/p/de683751dcef)
- 写出观察者模式的代码
- [适配器模式](https://blog.csdn.net/mrkohaku/article/details/79087688)，[装饰者模式](https://blog.csdn.net/csdn15698845876/article/details/81544562)，[外观模式](https://www.cnblogs.com/jimoer/p/9463698.html)的异同？
- 从0设计一款App整体架构，如何去做？
- 说一款你认为当前比较火的应用并设计(比如：直播APP，P2P金融，小视频等)
- 谈谈对java状态机理解
- Fragment如果在Adapter中使用应该如何解耦？
- 实现一个Json解析器(可以通过正则提高速度)
- 

##### （七）性能优化

- [统计启动时长,标准](https://www.jianshu.com/p/796c629196d9)
  
- [应用启动优化](https://juejin.im/post/5d95f4a4f265da5b8f10714b#heading-10)
  
  - Splash优化
  - Mutildex优化
  - 第三方库懒加载
    - Glide
  - Webview启动优化
  - 数据预 加载
  - 线程的多少由CPU进行决定
  
- [深度探索Android启动优化](https://juejin.im/post/5e6f18a951882549422ef333)

- UI卡顿优化(减少布局层级及控件复杂度，避免过度绘制
  使用 include、merge、viewstub
  优化绘制过程，避免在 Draw 中频繁创建对象、做耗时操作)

- [Android性能优化来龙去脉总结](https://juejin.im/post/5b194563e51d4506d25e20f5)

- ANR产生的原因是什么？

- 知道什么会引起ANR吗 怎么避免

- ANR定位和修正

- oom是什么？

- 什么情况导致oom？

- 有什么解决方法可以避免OOM？

- Oom 是否可以try catch？为什么？

- 内存泄漏是什么？

- 什么情况导致内存泄漏？

- 如何防止线程的内存泄漏？

- 内存泄露场的解决方法

- 内存泄漏和内存溢出区别？

- LruCache默认缓存大小

- [Android 性能优化最佳实践](https://juejin.im/post/5b50b017f265da0f7b2f649c)

- [Android GC 原理探究](https://zhuanlan.zhihu.com/p/24835977)

- android 应用对内存是如何限制的?我们应该如何合理使用内存？

- [深入研究java.lang.Object类](https://blog.51cto.com/lavasoft/15456)

- [Java内存问题及 LeakCanary 原理分析](https://juejin.im/post/5ab8d3d46fb9a028ca52f813)(通过弱引用和引用队列监控对象是否被回收

  比如 Activity 销毁时开始监控此对象，检测到未被回收则主动 gc ，然后继续监控)

  - Application中进行install
  - install后单独开了一个进程用来分析任务，和监听任务分开处理
  - refwatch收集销毁的Activity，用弱引用，并且创建ReferenceQueue来监听GC后 的回收情况
  - 检查回收的部分
  - 如果没有GC，手动进行GC
  - 执行检测做了一点优化，主线程空闲时进行分析
  - 

- [看完这篇垃圾回收，和面试官扯皮没问题了](https://mp.weixin.qq.com/s/8vXENzg580R7F2iNjSdHFw)

- [大众点评App的短视频耗电量优化实战](https://tech.meituan.com/2018/03/11/dianping-shortvideo-battery-testcase.html)

- [AndroidJniBitmapOperations](https://github.com/AndroidDeveloperLB/AndroidJniBitmapOperations)

- Android图片加载尺寸监控

- 理解Native Crash处理流程

- [美团外卖Android Crash治理之路](https://tech.meituan.com/2018/06/14/waimai-android-crash.html)

  - 常规的Crash
  - 内存leakcannary
  - 卡顿

- [理解Android Crash处理流程](http://gityuan.com/2016/06/24/app-crash/#handleApplicationCrashInner)

- [安装包立减1M--微信Android资源混淆打包工具](https://mp.weixin.qq.com/s?__biz=MzAwNDY1ODY2OQ==&mid=208135658&idx=1&sn=ac9bd6b4927e9e82f9fa14e396183a8f#rd)

- zstd 高质量压缩算法

- [Android 存储优化 —— MMKV 集成与原理](https://juejin.im/post/5d55284d6fb9a06aee362b07)

  - 源码分析
  
- [AabResGuard: AAB 资源混淆工具](https://juejin.im/post/5e115ca7e51d4540e53b7dcc)

- [Matrix IOCanary -- I/O 质量监控]()

- [Matrix TraceCanary -- 初恋·卡顿](https://github.com/Tencent/matrix/wiki/Matrix-Android-TraceCanary)

- [Matrix ResourceCanary -- Activity 泄漏及Bitmap冗余检测](https://github.com/Tencent/matrix/wiki/Matrix-Android-ResourceCanary)

- [Android性能优化（十一）之正确的异步姿势](https://www.jianshu.com/p/5f99f0e51118)

  - Android中的线程调度
    - 优先级 nice value
    - cgroup分组，限制后台线程执行，只有5%-10%几率使用cpu，避免影响主线程
    - app的前台和后台，对分组的影响
  - 正确的异步姿势
    - 直接创建。创建销毁消耗性能，缺乏统一管理，抢占主线程资源，可能存在内存泄漏、需要自己处理线程切换
    - AsyncTask
      - 线程切换使用的是Handler，那么如果是子线程的话，需要自己创建一个Lopper
    - HandlerThread 
      - 串行执行
      - 不指定优先级，默认是default的
    - IntentServices
      - 内部使用HandlerThread
    - ThreadPoolExecutor
      - 注意并发数量
      - 线程优先级和UI线程平等
  - 线程池一定会提升效率吗
  
- [Android 性能优化之布局优化](https://henleylee.github.io/posts/2019/d59595e2.html)

  - 选择合适的布局
    - wrap_content 需要测量成本
    - 使用include 局部模块化，也就是抽出公共部分
    - viewstub 默认不会被显示解析。
    - merge解决嵌套过多、当某个布局被include时，顶点是framelayout时不需要背景和pading
  - 减少布局层级
  - 提高布局复用性
  - 减少测量绘制时间
  - 监测工具，查看View绘制时间

- [Android中Bitmap内存优化](https://www.jianshu.com/p/3f6f6e4f1c88)

  - BitmapFactory 创建bitmap
  - native层是如何创建bitmap的
  - 在创建之前的scale
  - 具体占用多大内存
  - 内存优化
    - 使用低色彩解析模式
    - 合理放置分辨率目录文件
    - 图片缩小减小尺寸

- [Android性能优化：那些不可忽略的绘制优化](https://www.jianshu.com/p/cbdaeb1bede5)

  - 移除windows背景，这个背景平时用不到，所以会导致多绘制
  - 移除控件中不必要的背景，
    - 例如RecyclerView的背景
    - ViewPager和Fragment，如果Frament本身都有背景色，那么Viewpager不需要背景色
  - 减少布局的层级
  - 自定义控件：使用clipRect、quickReject
  - 扩展
    - opengl绘制
    - 为所有分辨率进行配置资源
  - 

- 如何对Android 应用进行性能分析以及优化?

- ddms 和 traceView

- 通过ApkTool分析resources.arsc文件以及resources.arsc文件的格式

- 性能优化如何分析systrace？

- [用IDE如何分析内存泄漏？](https://blog.csdn.net/hpc19950723/article/details/53561659)

- [Java多线程引发的性能问题，怎么解决？](https://blog.csdn.net/luofenghan/article/details/78596950)

  - 产生原因
  - 调优策略(线程池)
  - 同步锁自身的调优
    - 自旋锁
    - 锁消除
    - 锁粗化
    - 轻量级锁
    - 偏向锁
  - 线程池的介绍
    - 最大线程数
    - 核心线程数
    - 设置额外线程存活的时间
    - 选择线程池队列
      - SynchronousQueue 不存储任何任务
      - 无界队列
      - 有界队列
        - LinkedBlockingQueue
        - PriorityBlockingQueue
    - 合适的饱和策略
      - 默认 AbortPolicy中止，会抛出未检查的*RejectedExecutionException*
      - DiscardPolicy 抛弃
      - DiscardOldestPolicy（抛弃最旧的）
      - CallerRunsPolicy（调用者运行）不会抛弃任务，不会抛出异常，而是会在调用者线程去执行

- [启动页白屏及黑屏解决？](https://www.jianshu.com/p/c49831372605)

- 启动太慢怎么解决？

- 怎么保证应用启动不卡顿？

- [App启动崩溃异常捕捉](https://blog.csdn.net/github_37130188/article/details/89819706)

- [自定义View注意事项](https://www.jianshu.com/p/9862cddca1b3)

  - 让View支持wrap_content
  - 让View支持padding
  - 尽量不要在View中使用Handler
  - View中如果有线程或者动画，需要及时停止
  - View带有滑动嵌套时，需要处理好滑动冲突问题
  - 在View的onDraw方法中不要创建太多的临时对象，也就是new出来的对象
  - 

- [自定义View优化](https://www.jianshu.com/p/46ffc75dcbe2)

  - 减少不必要的代码：对于频繁调用的方法，需要尽量减少不必要的代码

  - 不在 onDraw 中做内存分配的事

  - 降低view的刷新频率

  - 使用硬件加速

  - 状态保存与恢复

- [如何优化自定义View](https://blog.csdn.net/whb20081815/article/details/74474736)
  - 避免在onDraw中创建对象
  - 减少不必要的代码
  - 降低刷新频率，减少onDraw方法的调用
  - 使用硬件加速
  - 状态的存储与恢复
  - 使用扁平化的View

- 现在下载速度很慢,试从网络协议的角度分析原因,并优化(提示：网络的5层都可以涉及)。

- Https请求慢的解决办法（提示：DNS，携带数据，直接访问IP）

- 如何保持应用的稳定性

- [RecyclerView和ListView的性能对比](https://blog.csdn.net/github_37130188/article/details/89819752)

- [RecyclerView源码分析](https://www.cnblogs.com/jiangbeixiaoqiao/p/5672766.html)

- [ListView的优化](https://www.jianshu.com/p/f0408a0f0610)

- [RecycleView优化](https://www.jianshu.com/p/bd432a3527d6)

  - 数据部分
    - 数据处理和视图绑定分离
    - 根据DiffUtil处理局部数据刷新
    - 分页加载，对拉去的数据进行缓存，提高二次的速度 
    - 滑动过程中不进行数据的加载
  - 布局
    - 减少布局层级
    - 减少inflate的时间
    - 减少View对象的创建，复杂的View可以分成多个TYPE
    - 设置固定高度
  - RecyclerView本身
    - 公用RecycledViewPoll
    - 增加缓存
    - 增加预留空间
    - 减少监听器的创建
    - 通过`onViewRecycled(holder)`来回收资源
  
- Bitmap如何处理大图，如一张30M的大图，如何预防OOM

##### （八）NDK、jni、Binder、AIDL、进程通信有关

- 请介绍一下NDK
- 什么是NDK库?
- jni用过吗？
- Android JNI 之 Bitmap 操作
- Android JNI 中的线程操作
- 【android】动态链接库so的加载原理
- 如何在jni中注册native函数，有几种注册方式?
- Java如何调用c、c++语言？
- [jni如何调用java层代码？](https://blog.csdn.net/yus201120/article/details/91060274)
- Android 进程间通信的方式？
- [Binder机制](https://blog.csdn.net/AndroidStudyDay/article/details/93749470)
- Binder机制及底层实现
- [为什么 Android 要采用 Binder 作为 IPC 机制？](https://www.zhihu.com/question/39440766)
- [Binder VS socket](https://blog.csdn.net/graitude/article/details/55522626)
- [写给 Android 应用工程师的 Binder 原理剖析](https://juejin.im/post/5acccf845188255c3201100f)
- [Android跨进程通信：图文详解 Binder机制 原理](https://juejin.im/post/5acccf845188255c3201100f)
- 简述IPC？
- [跨进程传递大内存数据如何做？](https://www.csdn.net/gather_2c/MtTakg5sMDM0OS1ibG9n.html)
- [Android进程间通信（IPC）机制Binder简要介绍和学习计划](https://blog.csdn.net/luoshengyang/article/details/6618363)
- 什么是AIDL？
- AIDL解决了什么问题？
- [AIDL如何使用？](https://blog.csdn.net/hai_qing_xu_kong/article/details/82893344)
- Android 上的 Inter-Process-Communication 跨进程通信时如何工作的？
- 多进程场景遇见过么？
- [Android进程分类？](https://www.jianshu.com/p/f8c676bceebf)
- [进程和 Application 的生命周期？](https://blog.csdn.net/qq_34115898/article/details/83276519)
- [进程调度](https://baike.baidu.com/item/%E8%BF%9B%E7%A8%8B%E8%B0%83%E5%BA%A6/10702294?fr=aladdin)
- 谈谈对进程共享和线程安全的认识
- [谈谈对多进程开发的理解以及多进程应用场景](https://blog.csdn.net/salaheiyao/article/details/61844412)
  - 前台进程
  - 可见进程
  - 服务进程
  - 后台进程
  - 空进程
  - 
- [什么是协程？](https://www.jianshu.com/p/ca8d1fe6d9f8)
  - 由程序控制线程切换而不是操作系统内核，节省资源
- App 是如何沙箱化，为什么要这么做？

##### （九）framework层、ROM定制、Ubuntu、Linux之类的问题

- 7.Devik 进程，linux 进程，线程的区别
- 简述 android 应用程序结构是哪些
- Ubuntu编译安卓系统
- APK 打包流程(1.aapt 打包资源文件生成 R.java 文件；aidl 生成 java 文件
   2.将 java 文件编译为 class 文件 
  3.将工程及第三方的 class 文件转换成 dex 文件
  4.将 dex 文件、so、编译过的资源、原始资源等打包成 apk 文件 
  5.签名
  6.资源文件对齐，减少运行时内存
- 大体说清一个应用程序安装到手机上时发生了什么
- App 安装过程(首先要解压 APK，资源、so等放到应用目录
  Dalvik 会将 dex 处理成 ODEX ；ART 会将 dex 处理成 OAT；
  OAT 包含 dex 和安装时编译的机器码)
- 逻辑地址与物理地址，为什么使用逻辑地址？
- 静态代理和动态代理的区别，什么场景使用？

##### （十）音视频

- 音频输出方式：AudioTrack、OpenSL 
- ES；视频输出方式：NativeWindow、OpenGL ES
- IjkPlayer 原理（集成了 MediaPlayer、ExoPlayer 和 IjkPlayer 三种实现，其中 IjkPlayer 基于 FFmpeg 的 ffplay
- 音视频同步：(选择参考时钟源：音频时间戳、视频时间戳和外部时间三者选择一个作为参考时钟源（一般选择音频，因为人对音频更敏感，ijk 默认也是音频）通过等待或丢帧将视频流与参考时钟源对齐，实现同步)
- 视频播放原理(：（mp4、flv）-> 解封装 -> （mp3/aac、h264/h265）-> 解码 -> （pcm、yuv）-> 音视频同步 -> 渲染播放)
- 音视频&FFmpeg&播放器(FFmpeg基于命令方式实现了一个音视频编辑 App： https://github.com/yhaolpz/FFmpegCmd集成编译了 AAC、MP3、H264 编码器)
- [Android直播开发之旅(7)：Android视频直播核心技术(架构)详解](https://blog.csdn.net/AndrExpert/article/details/76919535)
- 视频加密传输
- 视频缓存AndroidVideoCache攻略



## 四、技术通用面试题

##### （一）网络和安全机制

- [深度解析HTTPS原理](https://blog.csdn.net/zhongzh86/article/details/69389967)
- [http协议如何解决粘包问题](https://www.cnblogs.com/kex1n/p/6502002.html)
- [沾包处理](https://blog.csdn.net/soli/article/details/1297109)
- [TCP长连接沾包解决方案](https://blog.csdn.net/soli/article/details/1297109)
- [HTTP 断点续传（分块传输）](https://blog.csdn.net/liang19890820/article/details/53215087)
- [HTTPS 原理浅析及其在 Android 中的使用](https://cloud.tencent.com/developer/article/1005073)
- [HttpDns 原理是什么](http://www.linkedkeeper.com/171.html)
- [《客厅TV-APP HttpDNS技术接入与实战》](https://mp.weixin.qq.com/s/BVF24W6pyfhtoZo9cTbtpA)
- [HttpDns接入以及全局替换的实现](https://juejin.im/post/5b8a1c31f265da436d7e5874)
- [happy-dns-android](https://github.com/qiniu/happy-dns-android)
- [TCP、UDP、HTTP、SOCKET之间的区别](https://blog.csdn.net/magister_feng/article/details/8634518)
- [一文搞懂TCP与UDP的区别](https://blog.fundebug.com/2019/03/22/differences-of-tcp-and-udp/)
- [Android代码中实现WAP方式联网](https://www.cnblogs.com/navy-wang/p/3281953.html)
- [Android最佳实践——深入浅出WebSocket协议](https://blog.csdn.net/sbsujjbcy/article/details/52839540)
- 自己去设计网络请求框架，怎么做 ？
- [美团点评移动网络优化实践](https://tech.meituan.com/2017/03/17/shark-sdk.html)
- 域名合并
  - IP直连
  - http2.0优点
  - 代理长连接模式
    - 简单模式 tcp-http
    - 增加专线网络
    - tcp进行加密
    - 增加UDP传输
    - 增加公用网络HTTP
    - 
- [TCP的3次握手和四次挥手](https://www.cnblogs.com/bj-mr-li/p/11106390.html)
- [TCP与UDP的区别](https://www.cnblogs.com/fundebug/p/differences-of-tcp-and-udp.html)
- TCP与UDP的应用
- [HTTP协议](https://www.cnblogs.com/an-wen/p/11180076.html)
- [HTTP1.0与2.0的区别](https://www.cnblogs.com/smlp/p/9779206.html)
  - 多路复用同一个连接可以并发处理多个请求
  - 对头部数据进行压缩
  - 
- [*HTTP报文结构*](https://www.pianshen.com/article/8039276632/)
- [Http首部字段](https://www.cnblogs.com/milanleon/p/10213936.html)
- HTTP与HTTPS的区别以及如何实现安全性
- 如何验证证书的合法性?
- [https中哪里用了对称加密，哪里用了非对称加密，对加密算法（如RSA）等是否有了解?](https://www.optbbs.com/thread-5178169-1-1.html)
- client如何确定自己发送的消息被server收到?
- 谈谈你对WebSocket的理解
- [WebSocket与socket的区别](https://www.cnblogs.com/Javi/p/9303020.html)
- 网络优化及检测
  - 速度：1.GZIP 压缩（okhttp 自动支持）；2.Protocol Buffer 替代 json；3.优化图片/文件流量；4.IP 直连省去 DNS 解析时间
  - 成功率：1.失败重试策略；
  - 流量：1.GZIP 压缩（okhttp 自动支持）；2.Protocol Buffer 替代 json；3.优化图片/文件流量；5.文件下载断点续传 ；6.缓存
  - 协议层的优化，比如更优的 http 版本等
  - 监控：Charles 抓包、Network Monitor 监控流量

##### （二）数据库

- sqlite升级，增加字段的语句
- 数据库框架对比和源码分析
- 数据库的优化
- 如何导入外部数据库?
- 数据库数据迁移问题

##### （三）算法

- [排序算法有哪些？](https://blog.csdn.net/hanxiaoran906/article/details/81488232)
- 二分查找法的实现和应用汇总
- Java最小堆解决TopK问题
- 最快的排序算法是哪个？
- 手写一个冒泡排序
- [手写快速排序代码](https://baike.baidu.com/item/%E5%BF%AB%E9%80%9F%E6%8E%92%E5%BA%8F%E7%AE%97%E6%B3%95/369842?fromtitle=%E5%BF%AB%E9%80%9F%E6%8E%92%E5%BA%8F&fromid=2084344&fr=aladdin)
- [外排序](https://baike.baidu.com/item/%E5%A4%96%E9%83%A8%E6%8E%92%E5%BA%8F/10595890?fr=aladdin)
- 快速排序的过程、时间复杂度、空间复杂度
- [手写堆排序](https://baike.baidu.com/item/%E5%A0%86%E6%8E%92%E5%BA%8F/2840151?fr=aladdin#3_3)
- 堆排序过程、时间复杂度及空间复杂度
- 写出你所知道的排序算法及时空复杂度，稳定性
- 二叉树给出根节点和目标节点，找出从根节点到目标节点的路径
- 给阿里2万多名员工按年龄排序应该选择哪个算法？
- GC算法(各种算法的优缺点以及应用场景)
- 蚁群算法与蒙特卡洛算法
- 子串包含问题(KMP 算法)写代码实现
- 一个无序，不重复数组，输出N个元素，使得N个元素的和相加为M，给出时间复杂度、空间复杂度。手写算法
- 万亿级别的两个URL文件A和B，如何求出A和B的差集C(提示：Bit映射->hash分组->多文件读写效率->磁盘寻址以及应用层面对寻址的优化)
- 百度POI中如何试下查找最近的商家功能(提示：坐标镜像+R树)。
- 两个不重复的数组集合中，求共同的元素。
- 两个不重复的数组集合中，这两个集合都是海量数据，内存中放不下，怎么求共同的元素？
- 一个文件中有100万个整数，由空格分开，在程序中判断用户输入的整数是否在此文件中。说出最优的方法
- 一张Bitmap所占内存以及内存占用的计算
- 2000万个整数，找出第五十大的数字？
- 烧一根不均匀的绳，从头烧到尾总共需要1个小时。现在有若干条材质相同的绳子，问如何用烧绳的方法来计时一个小时十五分钟呢？
- 求1000以内的水仙花数以及40亿以内的水仙花数
- 5枚硬币，2正3反如何划分为两堆然后通过翻转让两堆中正面向上的硬8币和反面向上的硬币个数相同
- 时针走一圈，时针分针重合几次
- N*N的方格纸,里面有多少个正方形
- x个苹果，一天只能吃一个、两个、或者三个，问多少天可以吃完？



## 四、混合开发面试题

**大厂除了技术深度之外，还要求你具备一些广度的知识，比如你要会前端知识，会混合开发，至少会一种脚本语言，C c++更不用说了，也是必会的。**

##### （一）通用的混合开发

- Hybrid做过吗？
- Hybrid通信原理是什么，有做研究吗？
- react native有多少了解？讲一下原理。
- 混合开发有了解吗？
- 知道哪些混合开发的方式？说出它们的优缺点和各自使用场景？（解答：比如:RN，weex，H5，小程序，WPA等。做Android的了解一些前端js等还是很有好处的)；
- weex了解吗？如何自己实现类似技术？
- flutter了解吗？内部是如何实现跨平台的？
- Dart语言有研究贵吗？
- 快应用了解吗？跟其她方式相比有什么优缺点？
- 说说你用过的混合开发技术有哪些？各有什么优缺点？
- Python会吗？
- 会不会PHP？
- Gradle了解多少？groovy语法会吗？

##### （二） flutter

- [Flutter核心原理](https://book.flutterchina.club/chapter14/)

- [Flutter面试集锦](https://wizardforcel.gitbooks.io/gsyflutterbook/content/Flutter-msjj.html)

- [Flutter深入理解状态管理设计](https://wizardforcel.gitbooks.io/gsyflutterbook/content/Flutter-12.html)

- [Flutter Bloc图解](https://juejin.im/post/5d6e1a086fb9a06aec265a28)
  - Strem、SteamBuilder
  - RXDart
  - InheritedWidget
  - Bloc
  
- [Flutter原理与实践](https://tech.meituan.com/2018/08/09/waimai-flutter-practice.html)
  - Flutter控件Widget接近于原生
  - Flutter所使用的Dart语言同时支持AOT和JIT(Hot Reload)运行方式
  - 热刷新限制
  - Flutter插件
  - Flutter Framework
  - Flutter与原生代码通信
  - 
  
- [揭秘Flutter Hot Reload（原理篇）](https://juejin.im/post/5bc80ef7f265da0a857aa924)
  - 检查本地代码改动，生成kernel FIle，通过HTTP端口发送给DartVm
  - 通过PRC接口调用reloadSources进行资源的加载
  - 确定资源加载成功，触发UI接口，重建重绘
  
- [Flutter 动态化探索](https://fucknmb.com/2019/03/22/Flutter-%E5%8A%A8%E6%80%81%E5%8C%96%E6%8E%A2%E7%B4%A2/)

- [Flutter如何和Native通信-Android视角](https://juejin.im/post/5b4c3c9a5188251ac446d915)

- [深入理解Flutter Platform Channel](https://juejin.im/post/5b84ff6a6fb9a019f47d1cc9)

- [Flutter Engine 编译指北](https://fucknmb.com/2019/02/26/Flutter-Engine-%E7%BC%96%E8%AF%91%E6%8C%87%E5%8C%97/)

- [Flutter Engine 线程模型](https://zhuanlan.zhihu.com/p/64034467)

- [深入理解Flutter多线程](https://zhuanlan.zhihu.com/p/64034467)

- [Flutter状态管理 - 初探与总结](https://wizardforcel.gitbooks.io/gsyflutterbook/content/Flutter-12.html)

- [Flutter | 状态管理指南篇——Provider](https://juejin.im/post/5d00a84fe51d455a2f22023f)

- [深入理解Flutter应用启动](http://gityuan.com/2019/06/29/flutter_run_app/)

- [Flutter渲染机制—UI线程](http://gityuan.com/2019/06/15/flutter_ui_draw/)

- [Flutter渲染机制—GPU线程](http://gityuan.com/2019/06/16/flutter_gpu_draw/)

- [深入理解Flutter应用启动](http://gityuan.com/2019/06/29/flutter_run_app/)

- [深入理解setState更新机制](http://gityuan.com/2019/07/06/flutter_set_state/)
  - setState()过程主要工作是记录所有的脏元素，
  - 添加到BuildOwner对象的_dirtyElements成员变量，
  - 然后调用scheduleFrame来注册Vsync回调。
  -  当下一次vsync信号的到来时会执行handleBeginFrame()和handleDrawFrame()来更新UI。
  
- [深入理解Flutter消息机制](http://gityuan.com/2019/07/20/flutter_message_loop/)

- [深入理解Flutter动画原理](http://gityuan.com/2019/07/13/flutter_animator/)

- [Dart虚拟机运行原理](http://gityuan.com/2019/10/05/dart_vm/)

- [源码解读Flutter tools机制](http://gityuan.com/2019/09/01/flutter_tool/)

- [源码解读Flutter run机制](http://gityuan.com/2019/09/07/flutter_run/)

- [Fultter App 国际化/多语言](https://github.com/Sky24n/fluintl)

- [Flutter豆瓣客户端](https://github.com/kaina404/FlutterDouBan)

- [理解 Flutter 中的 Key](https://www.jianshu.com/p/6e704112dc67)


## 五、非技术性问题&HR问题汇总

**这里整理的是一些与技术没有直接关系的面试题，但是能够考察你的综合水平，所以不要以为不是技术问题，就不看，往往有时候就是这样一些细节的题目被忽视，而错过了一次次面试机会。**

##### （一）非技术问题

- 对业内信息的关注渠道有哪些？
- 最近都读哪些书？
- 有没有什么开源项目？
- 项目中用了哪些开源库，如何避免因为引入开源库而导致的安全性和稳定性问题
- 都使用过哪些自定义控件？
- 都使用过哪些框架、平台？
- 研究比较深入的领域有哪些？
- 介绍你做过的哪些项目
- 自己最擅长的技术点，最感兴趣的技术领域和技术点

##### （二）HR提出的面试问题

- 您在前一家公司的离职原因是什么？
- 你有什么优点
  - 我比较喜欢运动
  - 我比较喜欢读书
- 你有什么缺点
  - 如果有技术分享的话，人比较多的时候会比较紧张
  - 工作中，主线任务中穿插其他的碎片内容，有可能会记不住，所以在有道云笔记上进行，一些记录。包括今天的内容，附加内容。已完成...
- 讲一件你印象最深的一件事情
- 介绍一个你影响最深的项目
- 介绍你最热爱最擅长的专业领域
- 公司实习最大的收获是什么？
- 与上级意见不一致时，你将怎么办？
- 自己的优点和缺点是什么？并举例说明？
- 你的学习方法是什么样的？实习过程中如何学习？实习项目中遇到的最大困难是什么以及如何解决的？
- 说一件最能证明你能力的事情
- 针对你你申请的这个职位，你认为你还欠缺什么
- 如果通过这次面试我们单位录用了你，但工作一段时间却发现你根本不适合这个职位，你怎么办？
- 项目中遇到最大的困难是什么？如何解决的？
- 你的职业规划以及个人目标、未来发展路线及求职定位
- 如果你在这次面试中没有被录用，你怎么打算？
- 评价下自己，评价下自己的技术水平，个人代码量如何？
- 业余都有哪些爱好？
- 你做过的哪件事最令自己感到骄傲？
- 假如你晚上要去送一个出国的同学去机场，可单位临时有事非你办不可，你怎么办？
- 就你申请的这个职位，你认为你还欠缺什么？
- 当前的offer状况；如果BATH都给了offer该如何选？
- 你对一份工作更看重哪些方面？平台，技术，氛围，城市，还是money？
- 理想薪资范围；杭州岗和北京岗选哪个？
- 理想中的工作环境是什么？
- 谈谈你对跳槽的看法
- 说说你对行业、技术发展趋势的看法
- 实习过程中周围同事/同学有哪些值得学习的地方？
- 家人对你的工作期望及自己的工作期望
- 如果你的工作出现失误，给本公司造成经济损失，你认为该怎么办？
- 若上司在公开会议上误会你了，该如何解决？
- 在五年的时间内，你的职业规划
- 你看中公司的什么？或者公司的那些方面最吸引你？
- 自己最擅长的技术点，最感兴趣的技术领域和技术点
- 有没有什么开源项目？
- 最近都读哪些书？
  - 深入了解Java虚拟机
  - 计算机网络
  - 深入理解Android
- 对业内信息的关注渠道有哪些？
  - 公众号 ：技术社区、Android开发精选、谷歌开发者等
  - 公司同事的交流
  - 一起毕业同学之前的交流

### 

#### 面试题

- handler原理



1、Android查询资源文件layout原理

2、设计一个decode bitmap方法

3、启动Activity A后，按home键，再从桌面启动activity A ， Activity A的生命周期

4、

5、给定一个数组n, K位旋转算法。 如数组1、2、3、4，1位旋转结果为4、1、2、3， 2位旋转为3、4、1、2

三面面试题：

Activity启动流程

Android app签名原理





\1. 数组实现队列

\2. gc的流程

\3. java软引用与弱引用区别

\4. java中的this编译时的原理

\5. final变量用反射修改

\6. HashMap的内部结构，给定一个key，如何找到对应的value，使用equal

\7. volatile

\8. Java线程池有什么作用

\9. Java动态代理

\10. handler机制

\11. android跨进程通信的方式

12.自定义控件方式

13.Canvas绘制过什么 手写功能

14.断点续传的实现

15.如何设计图片加载库

16.有看过哪些安卓的源码 View树绘制 事件分发 Activity启动 handler

17.看过哪些开源项目 eventbus volley 图片 线程池管理 插件化 资源加载

18.app 启动速度的优化做过哪些

19.fresco加载图片原理 优势是什么

20.写程序时，堆和栈有什么优化点 内存回收时机 如何判断对象可被回收

引用计数法和gc root法

\21. 事件分发 cancel事件一般在什么时候被触发

\22. touchdelagate 一个父view只能设置一个delegate，如何解决设置多个

\23. App整个架构了解么

24.mvvm data binding

\25. webview

26.fragment startactivity

\27. 动画的原理

\28. 黄油计划 vsync

\29. 职业规划 做些有挑战的事儿 有意义的事儿 缺乏实战场景

30.设计一个离线视频下载功能





