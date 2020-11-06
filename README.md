# Android知识架构体系
个人对Android开发用到的知识进行积累，温故知新，主要针对中高级工程师

## 语言篇

### Java

- #### 常用的类原理

  - ArrayList
  - HashMap

- #### jvm虚拟机

  - 内存模型
  - 内存回收机制

- #### 并发编程

  - 同步机制
    - violate和synchronize
    - wait和notify
  - 线程池
  - 锁
  - 源码分析concurrent包
    - ConcurrentHashMap
    - CopyOnWriteArrayList
    - BlockingQeque
  - ThreadLocal

### Kotlin

- ### Kotlin的优势

  - Kotlin比Java效率高的tips

- ### 协程

## Android热门技术

- ### 代码插桩技术

- ### 动态代理

- ### 插件化

- ### 热修复

- ### 日志系统

- ### OKHttp

- ### Jetpack

  - LiveData原理
  - DataBinding原理
  - Navigation
  - Compose

- ### 崩溃收集（包含Native）

- ### Handler

- ### 常用的控件原理

  - TextView
  - RecyclerView原理
  - Fragment
  - WebView

- ### 打包

  - 打包流程
  - 加固
  - 构建速度
  - 包size优化

- ### 图片优化技术

  - 图片内存计算
  - png、jpeg、webp、svg比较
  - gif原理
  - svga原理
  - 帧动画内存优化

- ### 性能优化

  - [性能优化优秀博客汇总](https://zhuanlan.zhihu.com/p/30691789)
  - 流畅度、响应速度优化
  - 内存优化
  - CPU优化
  - 网络游湖
  - 启动优化
  - 稳定性
  - 功耗
  - IO优化

## Android Framework

- ### ActivityManagerService

- ### WindowManagerService

- ### PackageManagerService

- ### IPC

  - Binder
  - Socket、共享内存、管道、Binder优劣对比和使用场景

- Android虚拟机

  - ART和Dalvik的优劣势对比
  - ART的内存回收
  - ART的Dex加载

- Surface

## 开源项目解读

- Glide
- Small
- Tinker
- Arouter
- Retrofit

## 算法和数据结构

- ### 数组

- ### 链表

- ### 栈

- ### 队列

- ### 堆

- ### 树

- ### 动态规划

- ### 排序算法

- LRUCache

## 知识广度

- ### 计算机网络

  - TCP
    - TCP连接
    - TCP如何保证可靠性
  - UDP
    - UDP和TCP的区别的场景
    - UDP的原理
  - HTTP
  - HTTPS的原理

- ### 操作系统

  - LRUCache
  - CPU调度算法
  - 死锁

- ### Flutter

- ### 脚本化工具

  - gradle
  - python

- ### 设计模式

- ### NDK

  - JNI
  - OpenGL
  - FFmpeg

