---
home: true
heroImage: /images/dunwu-logo-200.png
heroText: JAVACORE
tagline: ☕ JavaCore 是一个 Java 核心技术教程。
actionLink: /
footer: CC-BY-SA-4.0 Licensed | Copyright © 2018-Now Dunwu
---

# JavaCore

> ☕ JavaCore 是一个 Java 核心技术教程。
>
> - 🔁 项目同步维护：[Github](https://github.com/dunwu/javacore/) | [Gitee](https://gitee.com/turnon/javacore/)
> - 📖 电子书阅读：[Github Pages](https://dunwu.github.io/javacore/) | [Gitee Pages](http://turnon.gitee.io/javacore/)

|           1️⃣            |           2️⃣            |           3️⃣            |           4️⃣            |         5️⃣         |             6️⃣              |
| :---------------------: | :---------------------: | :---------------------: | :---------------------: | :----------------: | :-------------------------: |
| [Java 基础](#java-基础) | [Java 高级](#java-高级) | [Java 容器](#java-容器) | [Java 并发](#java-并发) | [JavaIO](#java-io) | [Java 虚拟机](#java-虚拟机) |

## 教程内容 📖

### Java 基础

> [Java 基础](basics) 总结 Java 的一些基础特性。

- [Java 开发环境](basics/java-develop-env.md)
- [Java 基础语法特性](basics/java-basic-grammar.md)
- [Java 基本数据类型](basics/java-data-type.md)
- [Java 类和对象](basics/java-class.md)
- [Java 方法](basics/java-method.md)
- [Java 数组](basics/java-array.md)
- [Java 枚举](basics/java-enum.md)
- [Java 控制语句](basics/java-control-statement.md)
- [Java 异常](basics/java-exception.md)
- [Java 泛型](basics/java-generic.md)
- [Java 反射](basics/java-reflection.md)
- [Java 注解](basics/java-annotation.md)

### Java 高级

> [Java 高级](advanced) 总结 Java 的一些高级特性。

- [Java 正则](advanced/java-regex.md)
- [Java 编码和加密](advanced/java-crypto.md)
- [Java 本地化](advanced/java-locale.md)
- [JavaJDK8](advanced/jdk8.md)

### Java 容器

> [Java 容器](container) 涉及许多数据结构知识点，所以设立专题进行总结。

- [Java 容器简介](container/java-container.md)
- [Java 容器之 List](container/java-container-list.md) - 关键词：`List`、`ArrayList`、`LinkedList`
- [Java 容器之 Map](container/java-container-map.md) - 关键词：`Map`、`HashMap`、`LinkedHashMap`、`TreeMap`、`WeakHashMap`
- [Java 容器之 Set](container/java-container-set.md)
- [Java 容器之 Queue](container/java-container-queue.md)

### Java 并发

> [Java 并发](concurrent) 知识点庞杂且难懂，特设专题进行总结。

- [Java 并发面试题集 💯](concurrent/java-concurrent-interview.md)
- [Java 并发简介](concurrent/java-concurrent-introduction.md) - 关键词：`进程`、`线程`
- [Java 线程基础](concurrent/java-thread.md) - 关键词：`Thread`、`Runnable`、`Callable`、`Future`
- [Java 内存模型](concurrent/java-memory-model.md) - 关键词：`JMM`、`原子性`、`可见性`、`有序性`、`Happens-Before`
- [Java 并发核心机制](concurrent/java-concurrent-basic-mechanism.md) - 关键词：`synchronized`、`volatile`、`CAS`、`ThreadLocal`
- [Java 并发锁](concurrent/java-lock.md) - 关键词：`AQS`、`ReentrantLockA`、`ReentrantReadWriteLock`、`Condition`
- [Java 原子类](concurrent/java-atomic-class.md) - 关键词：`CAS`、`Atomic`
- [Java 并发容器](concurrent/java-concurrent-container.md) - 关键词：`ConcurrentHashMap`、`CopyOnWriteArrayList`
- [Java 线程池](concurrent/java-thread-pool.md) - 关键词：`Executor`、`ExecutorService`、`ThreadPoolExecutor`、`Executors`
- [Java 并发工具类](concurrent/java-concurrent-tools.md) - 关键词：`CountDownLatch`、`CyclicBarrier`、`Semaphore`

### Java IO

> Java IO 知识点

- [Java 基础 IO 类](io/java-io-base.md) - 关键词：`File`、`RandomAccessFile`、`System`、`Scanner`
- [Java BIO](io/java-bio.md) - 关键词：`InputStream`、`OutputStream`、`Reader`、`Writer`
- [Java NIO](io/java-nio.md) - 关键词：`Channel`、`Buffer`、`Selector`
- [Java 序列化](io/java-serialization.md) - 关键词：`Serializable`、`Externalizable`、`ObjectInputStream`、`ObjectOutputStream`、`transient`
- [Java 网络编程](io/java-net.md) - 关键词：`Socket`、`ServerSocket`、`DatagramPacket`、`DatagramSocket`

### Java 虚拟机

> [Java 虚拟机](jvm) 记录了 JVM 的基本机制。

- [JVM 内存区域](jvm/jvm-memory.md) - 关键词：程序计数器、虚拟机栈、本地方法栈、堆、方法区、运行时常量池、直接内存、`OutOfMemoryError`、`StackOverflowError`
- [JVM 垃圾收集](jvm/jvm-gc.md) - 关键词：`GC Roots`、`Serial`、`Parallel`、`CMS`、`G1`、`Minor GC`、`Full GC`
- [JVM 字节码](jvm/jvm-bytecode.md) - 关键词：`bytecode`、`asm`、`javassist`
- [JVM 类加载](jvm/jvm-class-loader.md) - 关键词：类加载过程、`ClassLoader`、双亲委派、
- [JVM 工具](jvm/jvm-tools.md) - 关键词：`jps`、`jstat`、`jmap` 、`jstack`、`jhat`、`jinfo`、`jconsole`、`jvisualvm`、`MAT`
- [JVM 实战](jvm/jvm-action.md) - 关键词：VM 参数、分析、调优
- [Java 故障排查](jvm/troubleshooting.md) - 关键词：CPU、内存、磁盘、网络、GC

## 其他教程 📚

> 你可能会感兴趣：

- [我的博客](https://github.com/dunwu/blog) 🎯
- [Java 教程](https://github.com/dunwu/java-tutorial) 📚
- [JavaCore 教程](https://dunwu.github.io/javacore/) 📚
- [JavaTech 教程](https://dunwu.github.io/javatech/) 📚
- [Spring 教程](https://dunwu.github.io/spring-tutorial/) 📚
- [Spring Boot 教程](https://dunwu.github.io/spring-boot-tutorial/) 📚
- [数据库教程](https://dunwu.github.io/db-tutorial/) 📚
- [数据结构和算法教程](https://dunwu.github.io/algorithm-tutorial/) 📚
- [Linux 教程](https://dunwu.github.io/linux-tutorial/) 📚
- [Nginx 教程](https://github.com/dunwu/nginx-tutorial/) 📚

## 学习资源 💎

- **书籍**
  - Java 四大名著
    - [《Java 编程思想（Thinking in java）》](https://item.jd.com/10058164.html)
    - [《Java 核心技术 卷 I 基础知识》](https://item.jd.com/12759308.html)
    - [《Java 核心技术 卷 II 高级特性》](https://item.jd.com/12791368.html)
    - [《Effective Java》](https://item.jd.com/12507084.html)
  - Java 并发
    - [《Java 并发编程实战》](https://item.jd.com/10922250.html)
    - [《Java 并发编程的艺术》](https://item.jd.com/11740734.html)
  - Java 虚拟机
    - [《深入理解 Java 虚拟机》](https://item.jd.com/11252778.html)
  - Java 入门
    - [《O'Reilly：Head First Java》](https://item.jd.com/10100190.html)
    - [《Java 从入门到精通》](https://item.jd.com/12555860.html)
    - [《疯狂 Java 讲义》](https://item.jd.com/12518025.html)
  - 其他
    - [《 Java 网络编程》](https://item.jd.com/11544991.html)
    - [《Java 加密与解密的艺术》](https://item.jd.com/26122568270.html)
    - [《Java 程序员面试宝典》](https://item.jd.com/11772823.html)
- **教程、社区**
  - [Runoob Java 教程](https://www.runoob.com/java/java-tutorial.html)
  - [JavaGuide](https://github.com/Snailclimb/JavaGuide)
  - [Java](https://github.com/TheAlgorithms/Java)
  - [java-design-patterns](https://github.com/iluwatar/java-design-patterns)
  - [advanced-java](https://github.com/doocs/advanced-java)
