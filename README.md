LearnMind

## 一、java

熟练掌握java是很关键的，大公司不仅仅要求你会使用几个api，更多的是要你熟悉源码实现原理，甚至要你知道有哪些不足，怎么改进，还有一些java有关的一些算法，设计模式等等。

##### （一） java基础知识点

- [x] java中==和equals和hashCode的区别
- [x] int、char、long各占多少字节数
- [x] int与integer的区别
- [x] 谈谈对java多态的理解
- [x] String、StringBuffer、StringBuilder区别
- [x] 什么是内部类？内部类的作用
- [x] 抽象类和接口区别
- [x] 抽象类的意义
- [x] 抽象类与接口的应用场景
- [x] 抽象类是否可以没有方法和属性？
- [x] 接口的意义
- [x] 泛型中extends和super的区别
- [x] 父类的静态方法能否被子类重写
- [x] 进程和线程的区别
- [x] final，finally，finalize的区别
- [x] 序列化的方式
- [x] Serializable 和Parcelable 的区别
- [x] 静态属性和静态方法是否可以被继承？是否可以被重写？以及原因？
- [x] 静态内部类的设计意图
- [x] 成员内部类、静态内部类、局部内部类和匿名内部类的理解，以及项目中的应用
- [x] 谈谈对kotlin的理解
- [x] 闭包和局部内部类的区别
- [x] string 转换成 integer的方式及原理

##### （二） java深入源码级的面试题（有难度）

- [x] 哪些情况下的对象会被垃圾回收机制处理掉？
- [x] 讲一下常见编码方式？
- [x] utf-8编码中的中文占几个字节；int型几个字节？
- [x] 静态代理和动态代理的区别，什么场景使用？
- [x] Java的异常体系
- [x] 谈谈你对解析与分派的认识。
- [x] 修改对象A的equals方法的签名，那么使用HashMap存放这个对象实例的时候，会调用哪个equals方法？
- [x] Java中实现多态的机制是什么？
- [x] 如何将一个Java对象序列化到文件里？
- [x] 说说你对Java反射的理解
- [x] 说说你对Java注解的理解
- [x] 说说你对依赖注入的理解
- [x] 说一下泛型原理，并举例说明
- [x] Java中String的了解
- [x] String为什么要设计成不可变的？
- [x] Object类的equal和hashCode方法重写，为什么？

##### （三） 数据结构

- [x] 常用数据结构简介
- [x] 并发集合了解哪些？
- [x] 列举java的集合以及集合之间的继承关系
- [x] 集合类以及集合框架
- [x] 容器类介绍以及之间的区别（容器类估计很多人没听这个词，Java容器主要可以划分为4个部分：List列表、Set集合、Map映射、工具类（Iterator迭代器、Enumeration枚举类、Arrays和Collections），具体的可以看看这篇博文 [Java容器类](http://alexyyek.github.io/2015/04/06/Collection/)）
- [x] List,Set,Map的区别
- [x] List和Map的实现方式以及存储方式
- [x] HashMap的实现原理
- [x] HashMap数据结构？
- [x] HashMap源码理解
- [x] HashMap如何put数据（从HashMap源码角度讲解）？
- [x] HashMap怎么手写实现？
- [x] ConcurrentHashMap的实现原理
- [x] ArrayMap和HashMap的对比
- [x] HashTable实现原理
- [x] TreeMap具体实现
- [x] HashMap和HashTable的区别
- [x] HashMap与HashSet的区别
- [x] HashSet与HashMap怎么判断集合元素重复？
- [x] 集合Set实现Hash怎么防止碰撞
- [x] ArrayList和LinkedList的区别，以及应用场景
- [x] 数组和链表的区别
- [x] 二叉树的深度优先遍历和广度优先遍历的具体实现
- [x] 堆的结构
- [x] 堆和树的区别
- [x] 堆和栈在内存中的区别是什么(解答提示：可以从数据结构方面以及实际实现方面两个方面去回答)？
- [x] 什么是深拷贝和浅拷贝
- [x] 手写链表逆序代码
- [x] 讲一下对树，B+树的理解
- [x] 讲一下对图的理解
- [x] 判断单链表成环与否？
- [x] 链表翻转（即：翻转一个单项链表）
- [ ] 合并多个单有序链表（假设都是递增的）

##### （四） 线程、多线程和线程池

- [x] 开启线程的三种方式？
- [x] ~~线程和进程的区别？~~
- [x] 为什么要有线程，而不是仅仅用进程？
- [x] run()和start()方法区别
- [x] 如何控制某个方法允许并发访问线程的个数？
- [x] 在Java中wait和seelp方法的不同；
- [x] 谈谈wait/notify关键字的理解
- [x] 什么导致线程阻塞？
- [x] 线程如何关闭？
- [x] 讲一下java中的同步的方法
- [x] 数据一致性如何保证？
- [x] 如何保证线程安全？
- [x] 如何实现线程同步？
- [x] 两个进程同时要求写或者读，能不能实现？如何防止进程的同步？
- [x] 线程间操作List
- [x] Java中对象的生命周期
- [x] Synchronized用法
- [x] synchronize的原理
- [x] 谈谈对Synchronized关键字，类锁，方法锁，重入锁的理解
- [x] static synchronized 方法的多线程访问和作用
- [x] 同一个类里面两个synchronized方法，两个线程同时访问的问题
- [x] volatile的原理
- [x] 谈谈volatile关键字的用法
- [x] 谈谈volatile关键字的作用
- [x] 谈谈NIO的理解
- [x] synchronized 和volatile 关键字的区别
- [x] synchronized与Lock的区别
- [x] ReentrantLock 、synchronized和volatile比较
- [x] ReentrantLock的内部实现
- [x] lock原理
- [x] 死锁的四个必要条件？
- [x] 怎么避免死锁？
- [x] 对象锁和类锁是否会互相影响？
- [x] 什么是线程池，如何使用?
- [x] Java的并发、多线程、线程模型
- [x] 谈谈对多线程的理解
- [x] 多线程有什么要注意的问题？
- [x] 谈谈你对并发编程的理解并举例说明
- [x] 谈谈你对多线程同步机制的理解？
- [x] 如何保证多线程读写文件的安全？
- [x] 多线程断点续传原理
- [x] 断点续传的实现

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

------

## 二、Android面试题

Android面试题包括Android基础，还有一些源码级别的、原理这些等。所以想去大公司面试，一定要多看看源码和实现方式，常用框架可以试试自己能不能手写实现一下，锻炼一下自己。

##### （一）Android基础知识点

- [x] 四大组件是什么
- [x] 四大组件的生命周期和简单用法
- [x] Activity之间的通信方式
- [x] Activity各种情况下的生命周期
- [x] 横竖屏切换的时候，Activity 各种情况下的生命周期
- [x] Activity与Fragment之间生命周期比较
- [x] Activity上有Dialog的时候按Home键时的生命周期
- [x] 两个Activity 之间跳转时必然会执行的是哪几个方法？
- [x] 前台切换到后台，然后再回到前台，Activity生命周期回调方法。弹出Dialog，生命值周期回调方法。
- [x] Activity的四种启动模式对比
- [x] Activity状态保存于恢复
- [x] fragment各种情况下的生命周期
- [x] Fragment状态保存startActivityForResult是哪个类的方法，在什么情况下使用？
- [x] 如何实现Fragment的滑动？
- [x] fragment之间传递数据的方式？
- [x] Activity 怎么和Service 绑定？
- [x] 怎么在Activity 中启动自己对应的Service？
- [x] service和activity怎么进行数据交互？
- [x] Service的开启方式
- [x] 请描述一下Service 的生命周期
- [x] 谈谈你对ContentProvider的理解
- [x] 说说ContentProvider、ContentResolver、ContentObserver 之间的关系
- [x] 请描述一下广播BroadcastReceiver的理解
- [x] 广播的分类
- [x] 广播使用的方式和场景
- [x] 在manifest 和代码中如何注册和使用BroadcastReceiver?
- [x] 本地广播和全局广播有什么差别？
- [x] BroadcastReceiver，LocalBroadcastReceiver 区别
- [x] AlertDialog,popupWindow,Activity区别
- [x] Application 和 Activity 的 Context 对象的区别
- [x] Android属性动画特性
- [x] 如何导入外部数据库?
- [x] LinearLayout、RelativeLayout、FrameLayout的特性及对比，并介绍使用场景。
- [x] 谈谈对接口与回调的理解
- [x] 回调的原理
- [x] 写一个回调demo
- [x] 介绍下SurfView
- [x] RecycleView的使用
- [x] 序列化的作用，以及Android两种序列化的区别
- [x] 差值器
- [x] 估值器
- [x] Android中数据存储方式

##### （二）Android源码相关分析

- [x] Android动画框架实现原理
- [x] Android各个版本API的区别
- [x] Requestlayout，onlayout，onDraw，DrawChild区别与联系
- [x] invalidate和postInvalidate的区别及使用
- [x] Activity-Window-View三者的差别
- [x] 谈谈对Volley的理解
- [x] 如何优化自定义View
- [x] 低版本SDK如何实现高版本api？
- [x] 描述一次网络请求的流程
- [x] HttpUrlConnection 和 okhttp关系
- [x] Bitmap对象的理解
- [x] looper架构
- [x] ActivityThread，AMS，WMS的工作原理
- [x] 自定义View如何考虑机型适配
- [x] 自定义View的事件
- [x] AstncTask+HttpClient 与 AsyncHttpClient有什么区别？
- [x] LaunchMode应用场景
- [x] AsyncTask 如何使用?
- [x] SpareArray原理
- [x] 请介绍下ContentProvider 是如何实现数据共享的？
- [x] AndroidService与Activity之间通信的几种方式
- [x] IntentService原理及作用是什么？
- [x] 说说Activity、Intent、Service 是什么关系
- [x] ApplicationContext和ActivityContext的区别
- [x] SP是进程同步的吗?有什么方法做到同步？
- [x] 谈谈多线程在Android中的使用
- [x] 进程和 Application 的生命周期
- [x] 封装View的时候怎么知道view的大小
- [x] RecycleView原理
- [x] AndroidManifest的作用与理解

##### （三）常见的一些原理性问题

- [x] Handler机制和底层实现
- [x] Handler、Thread和HandlerThread的差别
- [x] handler发消息给子线程，looper怎么启动？
- [x] 关于Handler，在任何地方new Handler 都是什么线程下?
- [x] ThreadLocal原理，实现及如何保证Local属性？
- [x] 请解释下在单线程模型中Message、Handler、Message Queue、Looper之间的关系
- [x] 请描述一下View事件传递分发机制
- [x] Touch事件传递流程
- [x] 事件分发中的onTouch 和onTouchEvent 有什么区别，又该如何使用？
- [x] View和ViewGroup分别有哪些事件分发相关的回调方法
- [x] View刷新机制
- [x] View绘制流程
- [x] 自定义控件原理
- [x] 自定义View如何提供获取View属性的接口？
- [x] Android代码中实现WAP方式联网
- [x] AsyncTask机制
- [x] AsyncTask原理及不足
- [x] 如何取消AsyncTask？
- [x] 为什么不能在子线程更新UI？
- [x] ANR产生的原因是什么？
- [x] ANR定位和修正
- [x] oom是什么？
- [x] 什么情况导致oom？
- [x] 有什么解决方法可以避免OOM？
- [x] Oom 是否可以try catch？为什么？
- [x] 内存泄漏是什么？
- [x] 什么情况导致内存泄漏？
- [x] 如何防止线程的内存泄漏？
- [x] 内存泄露场的解决方法
- [x] 内存泄漏和内存溢出区别？
- [x] LruCache默认缓存大小
- [x] ContentProvider的权限管理(解答：读写分离，权限控制-精确到表级，URL控制)
- [x] 如何通过广播拦截和abort一条短信？
- [x] 广播是否可以请求网络？
- [x] 广播引起anr的时间限制是多少？
- [x] 计算一个view的嵌套层级
- [x] Activity栈
- [x] Android线程有没有上限？
- [x] 线程池有没有上限？
- [x] ListView重用的是什么？
- [x] Android为什么引入Parcelable？
- [x] 有没有尝试简化Parcelable的使用？

##### （四）开发中常见的一些问题

- [x] ListView 中图片错位的问题是如何产生的?
- [x] 混合开发有了解吗？
- [x] 知道哪些混合开发的方式？说出它们的优缺点和各自使用场景？（解答：比如:RN，weex，H5，小程序，WPA等。做Android的了解一些前端js等还是很有好处的)；
- [x] 屏幕适配的处理技巧都有哪些?
- [x] 服务器只提供数据接收接口，在多线程或多进程条件下，如何保证数据的有序到达？
- [x] 动态布局的理解
- [x] 怎么去除重复代码？
- [x] 画出 Android 的大体架构图
- [x] Recycleview和ListView的区别
- [x] ListView图片加载错乱的原理和解决方案
- [x] 动态权限适配方案，权限组的概念
- [x] Android系统为什么会设计ContentProvider？
- [x] 下拉状态栏是不是影响activity的生命周期
- [x] 如果在onStop的时候做了网络请求，onResume的时候怎么恢复？
- [x] Bitmap 使用时候注意什么？
- [x] Bitmap的recycler()
- [x] Android中开启摄像头的主要步骤
- [x] ViewPager使用细节，如何设置成每次只初始化当前的Fragment，其他的不初始化？
- [x] 点击事件被拦截，但是想传到下面的View，如何操作？
- [ ] 微信主页面的实现方式
- [ ] 微信上消息小红点的原理
- [ ] CAS介绍（这是阿里巴巴的面试题，我不是很了解，可以参考博客: [CAS简介](http://blog.csdn.net/jly4758/article/details/46673835)）

------

## 三、混合开发面试题

**大厂除了技术深度之外，还要求你具备一些广度的知识，比如你要会前端知识，会混合开发，至少会一种脚本语言，C c++更不用说了，也是必会的。**

- [x] Hybrid做过吗？
- [x] Hybrid通信原理是什么，有做研究吗？
- [x] react native有多少了解？讲一下原理。
- [x] weex了解吗？如何自己实现类似技术？
- [x] flutter了解吗？内部是如何实现跨平台的？
- [x] Dart语言有研究贵吗？
- [x] 快应用了解吗？跟其她方式相比有什么优缺点？
- [x] 说说你用过的混合开发技术有哪些？各有什么优缺点？
- [x] Python会吗？
- [x] 会不会PHP？
- [x] Gradle了解多少？groovy语法会吗？
- [ ] 

------

## 四、高端技术面试题

**这里讲的是大公司需要用到的一些高端Android技术，这里专门整理了一个文档，希望大家都可以看看。这些题目有点技术含量，需要好点时间去研究一下的。**

##### （一）图片

- [x] 图片库对比
- [x] 图片库的源码分析
- [x] 图片框架缓存实现
- [x] LRUCache原理
- [x] 图片加载原理
- [x] 自己去实现图片库，怎么做？
- [x] Glide源码解析
- [x] Glide使用什么缓存？
- [x] Glide内存缓存如何控制大小？

##### （二）网络和安全机制

- [x] 网络框架对比和源码分析
- [x] 自己去设计网络请求框架，怎么做？
- [x] okhttp源码
- [x] 网络请求缓存处理，okhttp如何处理网络缓存的
- [x] 从网络加载一个10M的图片，说下注意事项
- [x] TCP的3次握手和四次挥手
- [x] TCP与UDP的区别
- [x] TCP与UDP的应用
- [x] HTTP协议
- [x] HTTP1.0与2.0的区别
- [x] HTTP报文结构
- [x] HTTP与HTTPS的区别以及如何实现安全性
- [x] 如何验证证书的合法性?
- [x] https中哪里用了对称加密，哪里用了非对称加密，对加密算法（如RSA）等是否有了解?
- [x] client如何确定自己发送的消息被server收到?
- [x] 谈谈你对WebSocket的理解
- [x] WebSocket与socket的区别
- [x] 谈谈你对安卓签名的理解。
- [x] 请解释安卓为啥要加签名机制?
- [x] 视频加密传输
- [x] App 是如何沙箱化，为什么要这么做？
- [x] 权限管理系统（底层的权限是如何进行 grant 的）？

##### （三）数据库

- [x] sqlite升级，增加字段的语句
- [x] 数据库框架对比和源码分析
- [x] 数据库的优化
- [x] 数据库数据迁移问题

##### （四）算法

- [x] 排序算法有哪些？
- [x] 最快的排序算法是哪个？
- [x] 手写一个冒泡排序
- [x] 手写快速排序代码
- [x] 快速排序的过程、时间复杂度、空间复杂度
- [x] 手写堆排序
- [x] 堆排序过程、时间复杂度及空间复杂度
- [x] 写出你所知道的排序算法及时空复杂度，稳定性
- [x] 二叉树给出根节点和目标节点，找出从根节点到目标节点的路径
- [x] 给阿里2万多名员工按年龄排序应该选择哪个算法？
- [x] GC算法(各种算法的优缺点以及应用场景)
- [x] 蚁群算法与蒙特卡洛算法
- [x] 子串包含问题(KMP 算法)写代码实现
- [x] 一个无序，不重复数组，输出N个元素，使得N个元素的和相加为M，给出时间复杂度、空间复杂度。手写算法
- [x] 万亿级别的两个URL文件A和B，如何求出A和B的差集C(提示：Bit映射->hash分组->多文件读写效率->磁盘寻址以及应用层面对寻址的优化)
- [x] 百度POI中如何试下查找最近的商家功能(提示：坐标镜像+R树)。
- [x] 两个不重复的数组集合中，求共同的元素。
- [x] 两个不重复的数组集合中，这两个集合都是海量数据，内存中放不下，怎么求共同的元素？
- [x] 一个文件中有100万个整数，由空格分开，在程序中判断用户输入的整数是否在此文件中。说出最优的方法
- [x] 一张Bitmap所占内存以及内存占用的计算
- [x] 2000万个整数，找出第五十大的数字？
- [x] 烧一根不均匀的绳，从头烧到尾总共需要1个小时。现在有若干条材质相同的绳子，问如何用烧绳的方法来计时一个小时十五分钟呢？
- [x] 求1000以内的水仙花数以及40亿以内的水仙花数
- [x] 5枚硬币，2正3反如何划分为两堆然后通过翻转让两堆中正面向上的硬8币和反面向上的硬币个数相同
- [x] 时针走一圈，时针分针重合几次
- [x] N*N的方格纸,里面有多少个正方形
- [x] x个苹果，一天只能吃一个、两个、或者三个，问多少天可以吃完？

##### （五）插件化、模块化、组件化、热修复、增量更新、Gradle

- [x] 对热修复和插件化的理解
- [x] 插件化原理分析
- [x] 模块化实现（好处，原因）
- [x] 热修复,插件化
- [x] 项目组件化的理解
- [x] 描述清点击 Android Studio 的 build 按钮后发生了什么

##### （六）架构设计和设计模式

- [x] 谈谈你对Android设计模式的理解
- [x] MVC MVP MVVM原理和区别
- [x] 你所知道的设计模式有哪些？
- [x] 项目中常用的设计模式
- [x] 手写生产者/消费者模式
- [x] 写出观察者模式的代码
- [x] 适配器模式，装饰者模式，外观模式的异同？
- [x] 用到的一些开源框架，介绍一个看过源码的，内部实现过程。
- [x] 谈谈对RxJava的理解
- [x] RxJava的功能与原理实现
- [x] RxJava的作用，与平时使用的异步操作来比的优缺点
- [x] 说说EventBus作用，实现方式，代替EventBus的方式
- [ ] 从0设计一款App整体架构，如何去做？
- [ ] 说一款你认为当前比较火的应用并设计(比如：直播APP，P2P金融，小视频等)
- [ ] 谈谈对java状态机理解
- [x] Fragment如果在Adapter中使用应该如何解耦？
- [x] Binder机制及底层实现
- [x] 对于应用更新这块是如何做的？(解答：灰度，强制更新，分区域更新)？
- [ ] 实现一个Json解析器(可以通过正则提高速度)
- [x] 统计启动时长,标准

##### （七）性能优化

- [x] 如何对Android 应用进行性能分析以及优化?
- [x] ddms 和 traceView
- [x] 性能优化如何分析systrace？
- [x] 用IDE如何分析内存泄漏？
- [x] Java多线程引发的性能问题，怎么解决？
- [x] 启动页白屏及黑屏解决？
- [x] 启动太慢怎么解决？
- [x] 怎么保证应用启动不卡顿？
- [x] App启动崩溃异常捕捉
- [x] 自定义View注意事项
- [x] 现在下载速度很慢,试从网络协议的角度分析原因,并优化(提示：网络的5层都可以涉及)。
- [x] Https请求慢的解决办法（提示：DNS，携带数据，直接访问IP）
- [x] 如何保持应用的稳定性
- [x] RecyclerView和ListView的性能对比
- [x] ListView的优化
- [x] RecycleView优化
- [x] View渲染
- [x] Bitmap如何处理大图，如一张30M的大图，如何预防OOM
- [x] java中的四种引用的区别以及使用场景
- [x] 强引用置为null，会不会被回收？

##### （八）NDK、jni、Binder、AIDL、进程通信有关

- [x] 请介绍一下NDK
- [x] 什么是NDK库?
- [x] jni用过吗？
- [x] 如何在jni中注册native函数，有几种注册方式?
- [x] Java如何调用c、c++语言？
- [x] jni如何调用java层代码？
- [x] 进程间通信的方式？
- [x] Binder机制
- [x] 简述IPC？
- [x] 什么是AIDL？
- [x] AIDL解决了什么问题？
- [x] AIDL如何使用？
- [x] Android 上的 Inter-Process-Communication 跨进程通信时如何工作的？
- [x] 多进程场景遇见过么？
- [x] Android进程分类？
- [x] 进程和 Application 的生命周期？
- [x] 进程调度
- [x] 谈谈对进程共享和线程安全的认识
- [x] 谈谈对多进程开发的理解以及多进程应用场景
- [x] 什么是协程？

##### （九）framework层、ROM定制、Ubuntu、Linux之类的问题

- [x] java虚拟机的特性
- [x] 谈谈对jvm的理解
- [x] JVM内存区域，开线程影响哪块内存
- [x] 对Dalvik、ART虚拟机有什么了解？
- [x] Art和Dalvik对比
- [x] 虚拟机原理，如何自己设计一个虚拟机(内存管理，类加载，双亲委派)
- [x] 谈谈你对双亲委派模型理解
- [x] JVM内存模型，内存区域
- [x] 类加载机制
- [x] 谈谈对ClassLoader(类加载器)的理解
- [x] 谈谈对动态加载（OSGI）的理解
- [x] 内存对象的循环引用及避免
- [x] 内存回收机制、GC回收策略、GC原理时机以及GC对象
- [x] 垃圾回收机制与调用System.gc()区别
- [x] Ubuntu编译安卓系统
- [x] 系统启动流程是什么？（提示：Zygote进程 –> SystemServer进程 –> 各种系统服务 –> 应用进程）
- [x] 大体说清一个应用程序安装到手机上时发生了什么
- [x] 简述Activity启动全部过程
- [x] App启动流程，从点击桌面开始
- [x] 逻辑地址与物理地址，为什么使用逻辑地址？
- [x] Android为每个应用程序分配的内存大小是多少？
- [x] Android中进程内存的分配，能不能自己分配定额内存？
- [x] 进程保活的方式
- [x] 如何保证一个后台服务不被杀死？（相同问题：如何保证service在后台不被kill？）比较省电的方式是什么？
- [x] App中唤醒其他进程的实现方式

------

## 五、非技术性问题&HR问题汇总

**这里整理的是一些与技术没有直接关系的面试题，但是能够考察你的综合水平，所以不要以为不是技术问题，就不看，往往有时候就是这样一些细节的题目被忽视，而错过了一次次面试机会。**

##### （一）非技术问题

- [ ] 介绍你做过的哪些项目
- [ ] 都使用过哪些框架、平台？
- [ ] 都使用过哪些自定义控件？
- [ ] 研究比较深入的领域有哪些？
- [ ] 对业内信息的关注渠道有哪些？
- [ ] 最近都读哪些书？
- [ ] 有没有什么开源项目？
- [ ] 自己最擅长的技术点，最感兴趣的技术领域和技术点
- [ ] 项目中用了哪些开源库，如何避免因为引入开源库而导致的安全性和稳定性问题
- [ ] 实习过程中做了什么，有什么产出？

##### （二）HR提出的面试问题

- [ ] 您在前一家公司的离职原因是什么？
- [ ] 讲一件你印象最深的一件事情
- [ ] 介绍一个你影响最深的项目
- [ ] 介绍你最热爱最擅长的专业领域
- [ ] 公司实习最大的收获是什么？
- [ ] 与上级意见不一致时，你将怎么办？
- [ ] 自己的优点和缺点是什么？并举例说明？
- [ ] 你的学习方法是什么样的？实习过程中如何学习？实习项目中遇到的最大困难是什么以及如何解决的？
- [ ] 说一件最能证明你能力的事情
- [ ] 针对你你申请的这个职位，你认为你还欠缺什么
- [ ] 如果通过这次面试我们单位录用了你，但工作一段时间却发现你根本不适合这个职位，你怎么办？
- [ ] 项目中遇到最大的困难是什么？如何解决的？
- [ ] 你的职业规划以及个人目标、未来发展路线及求职定位
- [ ] 如果你在这次面试中没有被录用，你怎么打算？
- [ ] 评价下自己，评价下自己的技术水平，个人代码量如何？
- [ ] 通过哪些渠道了解的招聘信息，其他同学都投了哪些公司？
- [ ] 业余都有哪些爱好？
- [ ] 你做过的哪件事最令自己感到骄傲？
- [ ] 假如你晚上要去送一个出国的同学去机场，可单位临时有事非你办不可，你怎么办？
- [ ] 就你申请的这个职位，你认为你还欠缺什么？
- [ ] 当前的offer状况；如果BATH都给了offer该如何选？
- [ ] 你对一份工作更看重哪些方面？平台，技术，氛围，城市，还是money？
- [ ] 理想薪资范围；杭州岗和北京岗选哪个？
- [ ] 理想中的工作环境是什么？
- [ ] 谈谈你对跳槽的看法
- [ ] 说说你对行业、技术发展趋势的看法
- [ ] 实习过程中周围同事/同学有哪些值得学习的地方？
- [ ] 家人对你的工作期望及自己的工作期望
- [ ] 如果你的工作出现失误，给本公司造成经济损失，你认为该怎么办？
- [ ] 若上司在公开会议上误会你了，该如何解决？
- [ ] 是否可以实习，可以实习多久？
- [ ] 在五年的时间内，你的职业规划
- [ ] 你看中公司的什么？或者公司的那些方面最吸引你？

