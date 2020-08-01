# Android 高级面试

 

## ![面试](img/面试.jpg)写给Android的一封信

 

最近半年，常常有人问我 “Android就业市场究竟怎么样，我还能不能坚持下去 ?”

现在想想，移动互联网的发展不知不觉已经十多年了，Mobile First 也已经变成了 AI First。换句话说，我们已经不再是“风口上的猪”。移动开发的光环和溢价开始慢慢消失，并且正在向 AI、区块链等新的领域转移。移动开发的新鲜血液也已经变少，最明显的是国内应届生都纷纷涌向了 AI 方向。

 

​    可以说，国内移动互联网的红利期已经过去了，现在是增量下降、存量厮杀，从争夺用户到争夺时长。比较明显的是手机厂商纷纷互联网化，与传统互联网企业直接竞争。另外一方面，过去渠道的打法失灵，小程序、快应用等新兴渠道崛起，无论是手机厂商，还是各大 App 都把出海摆到了战略的位置。

 

各大培训市场也不再培训Android，**作为开发Android的我们该何去何从？**



​     其实如果你技术深度足够，大必不用为就业而忧愁。每个行业何尝不是这样，最开始的风口，到慢慢的成熟。Android初级在2020年的日子里风光不再， 靠会四大组件就能够获取到满意薪资的时代一去不复返。**经过一波一波的淘汰与洗牌，剩下的都是技术的金子。就像大浪褪去，裸泳的会慢慢上岸。**而真正坚持下来的一定会取得不错成绩。毕竟Android市场是如此之大。从Android高级的蓬勃的就业岗位需求来看，能坚信我们每一位Android开发者的梦想 。

 

 接下来我们针对Android高级展开的完整面试题 

 
## --------------------------------预习专区----------------------------------

- [Android预习专题](https://github.com/733gh/Android-Notes/blob/598d20d2a91c06cbec3a21909f4a4d87bbc88abd/android/README.md)
  - [视频学习地址](https://space.bilibili.com/598568989)
  - [详细说说Binder通信原理与机制](https://github.com/733gh/Android-Notes/blob/598d20d2a91c06cbec3a21909f4a4d87bbc88abd/android/binder.md)

## ---------------------2020Android年高级面试----------------------

- [2020年Bat面试集合](#2020年Bat面试集合)
- [架构相关面试](#架构相关面试)
- [NDK相关面试](#NDK相关面试)
- [算法相关面试](#算法相关面试)
- [高级UI相关面试](#高级UI相关面试)
- [性能优化相关面试](#性能优化相关面试)
- [专业领域相关面试](#专业领域相关面试)
- [2020年Android最新技术讲解](#2020年Android最新技术讲解)
- [其他](#其他)

## 2020年Bat面试集合

> 阿里巴巴面试集合

- [谈谈线程池原理](https://github.com/733gh/Android-Notes/blob/598d20d2a91c06cbec3a21909f4a4d87bbc88abd/android/thread1.md)
- [垃圾回收机制是如何实现的](https://github.com/733gh/Android-Notes/blob/598d20d2a91c06cbec3a21909f4a4d87bbc88abd/android/traked.md)
- [https原理你知道吗](https://github.com/733gh/Android-Notes/blob/598d20d2a91c06cbec3a21909f4a4d87bbc88abd/android/https.md)
- [Hadler是如何实现线程通信的](https://github.com/733gh/Android-Notes/blob/598d20d2a91c06cbec3a21909f4a4d87bbc88abd/study/framework/Android消息机制.md)
- [Glide对Bitmap的缓存与解码复用如何做到的](https://github.com/733gh/Android-Notes/blob/598d20d2a91c06cbec3a21909f4a4d87bbc88abd/android/thread.md)
- [给你一个Demo 你如何快速定位ANR](https://github.com/733gh/Android-Notes/blob/598d20d2a91c06cbec3a21909f4a4d87bbc88abd/android/anr.md)
- [说说你对Dalvik虚拟机的认识](https://github.com/733gh/Android-Notes/blob/598d20d2a91c06cbec3a21909f4a4d87bbc88abd/android/dalvik.md)
- [接下来说说 Android 虚拟机Dalvik与ART区别在哪里？](https://github.com/733gh/Android-Notes/blob/598d20d2a91c06cbec3a21909f4a4d87bbc88abd/android/artordalvik.md)
- [有用过插件化吗？谈谈插件化原理？](https://github.com/733gh/Android-Notes/blob/598d20d2a91c06cbec3a21909f4a4d87bbc88abd/android/plugin.md)
- [进程保活如何做到，你们保活率有多高？](https://github.com/733gh/Android-Notes/blob/598d20d2a91c06cbec3a21909f4a4d87bbc88abd/android/process.md)
- [详细说说Binder通信原理与机制](https://github.com/733gh/Android-Notes/blob/598d20d2a91c06cbec3a21909f4a4d87bbc88abd/android/binder.md)
- [Handler的原理是什么?能深入分析下 Handler的实现机制吗？](https://github.com/733gh/Android-Notes/blob/598d20d2a91c06cbec3a21909f4a4d87bbc88abd/study/framework/Handler机制源码.md)
- [Handler中有Loop死循环，为什么没有阻塞主线程，原理是什么](https://github.com/733gh/Android-Notes/blob/598d20d2a91c06cbec3a21909f4a4d87bbc88abd/study/framework/Android消息机制.md)

> 腾讯面试集合

- [热修复连环炮(热修复是什么 有接触过tinker吗，tinker原理是什么)](https://github.com/733gh/Android-Notes/blob/598d20d2a91c06cbec3a21909f4a4d87bbc88abd/tencent/tinker.md)
- [增量升级为什么减少升级代价，增量升级原理](https://github.com/733gh/Android-Notes/blob/598d20d2a91c06cbec3a21909f4a4d87bbc88abd/tencent/update.md)
- [数据库版本如何单独升级，并且将原有数据迁移过去](https://github.com/733gh/Android-Notes/blob/598d20d2a91c06cbec3a21909f4a4d87bbc88abd/tencent/sqlite.md)
- [如何设计一个多用户，多角色的App架构](https://github.com/733gh/Android-Notes/blob/598d20d2a91c06cbec3a21909f4a4d87bbc88abd/android/thread.md)
- [谈谈volatile关键字与synchronized关键字在内存的区别](https://github.com/733gh/Android-Notes/blob/598d20d2a91c06cbec3a21909f4a4d87bbc88abd/android/volatile.md)
- [synchronize关键字在虚拟机执行原理是什么，能谈一谈什么是内存可见性，锁升级吗](https://github.com/733gh/Android-Notes/blob/598d20d2a91c06cbec3a21909f4a4d87bbc88abd/android/synchronize.md)
- [ButterKnife为什么执行效率为什么比其他注入框架高？它的原理是什么](https://github.com/733gh/Android-Notes/blob/598d20d2a91c06cbec3a21909f4a4d87bbc88abd/android/butterknife.md)
- [Linux自带多种进程通信方式，为什么Android都没采用二偏偏使用Binder通信](https://github.com/733gh/Android-Notes/blob/598d20d2a91c06cbec3a21909f4a4d87bbc88abd/android/binder1.md)
- [谈一谈Binder的原理和实现一次拷贝的流程](https://github.com/733gh/Android-Notes/blob/598d20d2a91c06cbec3a21909f4a4d87bbc88abd/android/binder2.md)
- [组件化如何实现，组件化与插件化的差别在哪里，该怎么选型](https://github.com/733gh/Android-Notes/blob/598d20d2a91c06cbec3a21909f4a4d87bbc88abd/android/commpont.md)
- [说下组件之间的跳转和组件通信原理机制](https://github.com/733gh/Android-Notes/blob/598d20d2a91c06cbec3a21909f4a4d87bbc88abd/android/commpontrounter.md)
- [类比于微信，如何对Apk进行极限压缩,谈下Android压缩8大步](https://github.com/733gh/Android-Notes/blob/598d20d2a91c06cbec3a21909f4a4d87bbc88abd/android/AndResGuard.md)
- [如何彻底防止反编译，dex加密怎么做](https://github.com/733gh/Android-Notes/blob/598d20d2a91c06cbec3a21909f4a4d87bbc88abd/android/thread.md)

> 字节跳动面试集合

[抖音-直播中 网速比较差的条件下，如何使画面保证流畅的效果](https://github.com/733gh/Android-Notes/blob/598d20d2a91c06cbec3a21909f4a4d87bbc88abd/android/thread.md)

[抖音-谈下音视频同步原理，音频和视频能绝对同步吗](https://github.com/733gh/Android-Notes/blob/598d20d2a91c06cbec3a21909f4a4d87bbc88abd/android/thread.md)

[抖音-硬编码与软编码区别，如何选取硬编与软编](https://github.com/733gh/Android-Notes/blob/598d20d2a91c06cbec3a21909f4a4d87bbc88abd/android/thread.md)

[抖音-抖音中时间特效与美颜特效怎么做的](https://github.com/733gh/Android-Notes/blob/598d20d2a91c06cbec3a21909f4a4d87bbc88abd/android/thread.md)

[抖音-Include、Merge、ViewStub的作用和原理](https://github.com/733gh/Android-Notes/blob/598d20d2a91c06cbec3a21909f4a4d87bbc88abd/android/thread.md)

[抖音-如何在脸部区域增加特效，怎样才能使这个特效跟随脸部](https://github.com/733gh/Android-Notes/blob/598d20d2a91c06cbec3a21909f4a4d87bbc88abd/android/thread.md)

[抖音-Opencv中定位人脸的五个点是如何做到的](https://github.com/733gh/Android-Notes/blob/598d20d2a91c06cbec3a21909f4a4d87bbc88abd/android/thread.md)

[今日头条-为什么RecyclerView加载首屏会慢一些](https://github.com/733gh/Android-Notes/blob/598d20d2a91c06cbec3a21909f4a4d87bbc88abd/android/thread.md)

[今日头条-说下RecyclerView回收池原理](https://github.com/733gh/Android-Notes/blob/598d20d2a91c06cbec3a21909f4a4d87bbc88abd/android/thread.md)

[今日头条-View绘制机制，onMeasure onLayout ,onDraw方法的调用机制谈一下](https://github.com/733gh/Android-Notes/blob/598d20d2a91c06cbec3a21909f4a4d87bbc88abd/android/thread.md)

[今日头条-为什么Android会出现卡顿](https://github.com/733gh/Android-Notes/blob/598d20d2a91c06cbec3a21909f4a4d87bbc88abd/android/thread.md)

[今日头条-ThreadLocal底层原理和Handler的关系](https://github.com/733gh/Android-Notes/blob/598d20d2a91c06cbec3a21909f4a4d87bbc88abd/android/thread.md)

[今日头条-Flutter为什么会做到一处写 处处运行 与RN的区别](https://github.com/733gh/Android-Notes/blob/598d20d2a91c06cbec3a21909f4a4d87bbc88abd/android/thread.md)

[今日头条-Flutter的图形引擎与Android的渲染引擎原理](https://github.com/733gh/Android-Notes/blob/598d20d2a91c06cbec3a21909f4a4d87bbc88abd/android/thread.md)

[今日头条-sync关键字和lock的区别? 他们对线程的控制原理简单说下](https://github.com/733gh/Android-Notes/blob/598d20d2a91c06cbec3a21909f4a4d87bbc88abd/android/thread.md)

## 架构相关面试

[EventBus源码详解与架构分析，使用EventBus会造成什么弊端](https://github.com/733gh/Android-Notes/blob/598d20d2a91c06cbec3a21909f4a4d87bbc88abd/android/thread.md)

[AOP面向切面编程原理](https://github.com/733gh/Android-Notes/blob/598d20d2a91c06cbec3a21909f4a4d87bbc88abd/android/thread.md)

[说说饿了么Hermes跨进程架构原理](https://github.com/733gh/Android-Notes/blob/598d20d2a91c06cbec3a21909f4a4d87bbc88abd/android/thread.md)

[Message链表原理与重用机制是怎么实现](https://github.com/733gh/Android-Notes/blob/598d20d2a91c06cbec3a21909f4a4d87bbc88abd/android/thread.md)

[QQ是怎么做到皮肤换肤的，谈谈换肤原理](https://github.com/733gh/Android-Notes/blob/598d20d2a91c06cbec3a21909f4a4d87bbc88abd/android/thread.md)

[阿里巴巴ARouter原理执行流程，对组件化开发有什么好处](https://github.com/733gh/Android-Notes/blob/598d20d2a91c06cbec3a21909f4a4d87bbc88abd/android/thread.md)

[RePlugin插件化通过什么方式实现强兼容](https://github.com/733gh/Android-Notes/blob/598d20d2a91c06cbec3a21909f4a4d87bbc88abd/android/thread.md)

[谈谈对Rxjava的底层认识，如何做到线程切换的](https://github.com/733gh/Android-Notes/blob/598d20d2a91c06cbec3a21909f4a4d87bbc88abd/android/thread.md)

[APT实现手写Dagger注入式框架](https://github.com/733gh/Android-Notes/blob/598d20d2a91c06cbec3a21909f4a4d87bbc88abd/android/thread.md)

[-----持续更新 未完待续-------](https://github.com/733gh/Android-Notes/tree/598d20d2a91c06cbec3a21909f4a4d87bbc88abd#)

## NDK相关面试

[Java中有指针吗？说说 为什么C会需要指针](https://github.com/733gh/Android-Notes/blob/598d20d2a91c06cbec3a21909f4a4d87bbc88abd/android/thread.md)

[MakeFile编译一个so库的流程](https://github.com/733gh/Android-Notes/blob/598d20d2a91c06cbec3a21909f4a4d87bbc88abd/android/thread.md)

[CmakeList.txt中find_library语法是什么意思](https://github.com/733gh/Android-Notes/blob/598d20d2a91c06cbec3a21909f4a4d87bbc88abd/android/thread.md)

[谈谈阿里云andfix热修复原理](https://github.com/733gh/Android-Notes/blob/598d20d2a91c06cbec3a21909f4a4d87bbc88abd/android/thread.md)

[直播推流中，通过rtmp协议发送一个packet包的流程](https://github.com/733gh/Android-Notes/blob/598d20d2a91c06cbec3a21909f4a4d87bbc88abd/android/thread.md)

[直播中为什么需要将摄像头的NV21数据通过x264编码 再发送](https://github.com/733gh/Android-Notes/blob/598d20d2a91c06cbec3a21909f4a4d87bbc88abd/android/thread.md)

[怎么编译一个FFmpeg 并且集成到AndroidStudio中](https://github.com/733gh/Android-Notes/blob/598d20d2a91c06cbec3a21909f4a4d87bbc88abd/android/thread.md)

[webrtc是如何实现点对点通信的](https://github.com/733gh/Android-Notes/blob/598d20d2a91c06cbec3a21909f4a4d87bbc88abd/android/thread.md)

[谈下webrtc 内网穿透原理](https://github.com/733gh/Android-Notes/blob/598d20d2a91c06cbec3a21909f4a4d87bbc88abd/android/thread.md)

[-----持续更新 未完待续-------](https://github.com/733gh/Android-Notes/tree/598d20d2a91c06cbec3a21909f4a4d87bbc88abd#)

## 算法相关面试

- [Hash值是如何生成](https://github.com/733gh/Android-Notes/blob/598d20d2a91c06cbec3a21909f4a4d87bbc88abd/basic/1-algo/2-hash.md)
- [谈谈HashMap的原理](https://github.com/733gh/Android-Notes/blob/598d20d2a91c06cbec3a21909f4a4d87bbc88abd/basic/1-algo/2-hash.md)
- [最小生成树算法](https://github.com/733gh/Android-Notes/blob/598d20d2a91c06cbec3a21909f4a4d87bbc88abd/basic/1-algo/3-mst.md)
- [最短路径算法](https://github.com/733gh/Android-Notes/blob/598d20d2a91c06cbec3a21909f4a4d87bbc88abd/basic/1-algo/4-path.md)
- [KMP算法](https://github.com/733gh/Android-Notes/blob/598d20d2a91c06cbec3a21909f4a4d87bbc88abd/basic/1-algo/5-kmp.md)
- [查找算法](https://github.com/733gh/Android-Notes/blob/598d20d2a91c06cbec3a21909f4a4d87bbc88abd/basic/1-algo/6-search.md)
- [排序算法](https://github.com/733gh/Android-Notes/blob/598d20d2a91c06cbec3a21909f4a4d87bbc88abd/basic/1-algo/7-sort.md)
- [跳跃表](https://github.com/733gh/Android-Notes/blob/598d20d2a91c06cbec3a21909f4a4d87bbc88abd/basic/1-algo/9-skip_list.md)
- [对称加密与非对称加密是如何实现的](https://github.com/733gh/Android-Notes/blob/598d20d2a91c06cbec3a21909f4a4d87bbc88abd/basic/1-algo/9-skip_list.md)
- [-----持续更新 未完待续-------](https://github.com/733gh/Android-Notes/tree/598d20d2a91c06cbec3a21909f4a4d87bbc88abd#)

## 高级UI相关面试

[你知道Bat公司如何对屏幕适配的](https://github.com/733gh/Android-Notes/blob/598d20d2a91c06cbec3a21909f4a4d87bbc88abd/android/thread.md)

[谈谈对刘海屏开发与适配方案](https://github.com/733gh/Android-Notes/blob/598d20d2a91c06cbec3a21909f4a4d87bbc88abd/android/thread.md)

[Android9.0Api适配举例有哪些不一样的地方](https://github.com/733gh/Android-Notes/blob/598d20d2a91c06cbec3a21909f4a4d87bbc88abd/android/thread.md)

[讲讲你对UI绘制流程及其原理的](https://github.com/733gh/Android-Notes/blob/598d20d2a91c06cbec3a21909f4a4d87bbc88abd/android/thread.md)

[谈谈你对事件传递机制的认识](https://github.com/733gh/Android-Notes/blob/598d20d2a91c06cbec3a21909f4a4d87bbc88abd/android/thread.md)

[在自定义View中如何开启硬件加速](https://github.com/733gh/Android-Notes/blob/598d20d2a91c06cbec3a21909f4a4d87bbc88abd/android/thread.md)

[淘宝如何做到展示亿级商品（强排版，强交互实现机制）](https://github.com/733gh/Android-Notes/blob/598d20d2a91c06cbec3a21909f4a4d87bbc88abd/android/thread.md)

[-----持续更新 未完待续-------](https://github.com/733gh/Android-Notes/tree/598d20d2a91c06cbec3a21909f4a4d87bbc88abd#)

## 2020年Android最新技术讲解
[2020年Android最新技术讲解](https://github.com/733gh/Android-Notes/blob/master/%E6%8A%80%E6%9C%AF%E8%AE%B2%E8%A7%A3.md)

#### MMKV框架原理解密，MMKV如何利用mmap函数实现储存优化100倍

* [MMKV框架原理解密之01MMKV使用](https://github.com/733gh/Android-Notes/blob/master/MMKV%E6%A1%86%E6%9E%B6%E5%8E%9F%E7%90%86%E8%A7%A3%E5%AF%86%EF%BC%8CMMKV%E5%A6%82%E4%BD%95%E5%88%A9%E7%94%A8mmap%E5%87%BD%E6%95%B0%E5%AE%9E%E7%8E%B0%E5%82%A8%E5%AD%98%E4%BC%98%E5%8C%96100%E5%80%8D/MMKV%E6%A1%86%E6%9E%B6%E5%8E%9F%E7%90%86%E8%A7%A3%E5%AF%86%E4%B9%8B01MMKV%E4%BD%BF%E7%94%A8.md)
* [MMKV框架原理解密之02mmap函数](https://github.com/733gh/Android-Notes/blob/master/MMKV%E6%A1%86%E6%9E%B6%E5%8E%9F%E7%90%86%E8%A7%A3%E5%AF%86%EF%BC%8CMMKV%E5%A6%82%E4%BD%95%E5%88%A9%E7%94%A8mmap%E5%87%BD%E6%95%B0%E5%AE%9E%E7%8E%B0%E5%82%A8%E5%AD%98%E4%BC%98%E5%8C%96100%E5%80%8D/MMKV%E6%A1%86%E6%9E%B6%E5%8E%9F%E7%90%86%E8%A7%A3%E5%AF%86%E4%B9%8B02mmap%E5%87%BD%E6%95%B0.md)
* [MMKV框架原理解密之03-MMKV使用为什么会有内核空间与用户空间](https://github.com/733gh/Android-Notes/blob/master/MMKV%E6%A1%86%E6%9E%B6%E5%8E%9F%E7%90%86%E8%A7%A3%E5%AF%86%EF%BC%8CMMKV%E5%A6%82%E4%BD%95%E5%88%A9%E7%94%A8mmap%E5%87%BD%E6%95%B0%E5%AE%9E%E7%8E%B0%E5%82%A8%E5%AD%98%E4%BC%98%E5%8C%96100%E5%80%8D/MMKV%E6%A1%86%E6%9E%B6%E5%8E%9F%E7%90%86%E8%A7%A3%E5%AF%86%E4%B9%8B03-MMKV%E4%BD%BF%E7%94%A8%E4%B8%BA%E4%BB%80%E4%B9%88%E4%BC%9A%E6%9C%89%E5%86%85%E6%A0%B8%E7%A9%BA%E9%97%B4%E4%B8%8E%E7%94%A8%E6%88%B7%E7%A9%BA%E9%97%B4.md)
* [MMKV框架原理解密之04-内存管理单元](https://github.com/733gh/Android-Notes/blob/master/MMKV%E6%A1%86%E6%9E%B6%E5%8E%9F%E7%90%86%E8%A7%A3%E5%AF%86%EF%BC%8CMMKV%E5%A6%82%E4%BD%95%E5%88%A9%E7%94%A8mmap%E5%87%BD%E6%95%B0%E5%AE%9E%E7%8E%B0%E5%82%A8%E5%AD%98%E4%BC%98%E5%8C%96100%E5%80%8D/MMKV%E6%A1%86%E6%9E%B6%E5%8E%9F%E7%90%86%E8%A7%A3%E5%AF%86%E4%B9%8B04-%E5%86%85%E5%AD%98%E7%AE%A1%E7%90%86%E5%8D%95%E5%85%83.md)
* [MMKV框架原理解密之05-Binder关于mmap函数面试流程](https://github.com/733gh/Android-Notes/blob/master/MMKV%E6%A1%86%E6%9E%B6%E5%8E%9F%E7%90%86%E8%A7%A3%E5%AF%86%EF%BC%8CMMKV%E5%A6%82%E4%BD%95%E5%88%A9%E7%94%A8mmap%E5%87%BD%E6%95%B0%E5%AE%9E%E7%8E%B0%E5%82%A8%E5%AD%98%E4%BC%98%E5%8C%96100%E5%80%8D/MMKV%E6%A1%86%E6%9E%B6%E5%8E%9F%E7%90%86%E8%A7%A3%E5%AF%86%E4%B9%8B05-Binder%E5%85%B3%E4%BA%8Emmap%E5%87%BD%E6%95%B0%E9%9D%A2%E8%AF%95%E6%B5%81%E7%A8%8B.md)
* [MMKV框架原理解密之06-读懂Binder 从mmap开始](https://github.com/733gh/Android-Notes/blob/master/MMKV%E6%A1%86%E6%9E%B6%E5%8E%9F%E7%90%86%E8%A7%A3%E5%AF%86%EF%BC%8CMMKV%E5%A6%82%E4%BD%95%E5%88%A9%E7%94%A8mmap%E5%87%BD%E6%95%B0%E5%AE%9E%E7%8E%B0%E5%82%A8%E5%AD%98%E4%BC%98%E5%8C%96100%E5%80%8D/MMKV%E6%A1%86%E6%9E%B6%E5%8E%9F%E7%90%86%E8%A7%A3%E5%AF%86%E4%B9%8B06-%E8%AF%BB%E6%87%82Binder%20%E4%BB%8Emmap%E5%BC%80%E5%A7%8B.md)
* [MMKV框架原理解密，MMKV如何利用mmap函数实现储存优化100倍 讲解](https://www.bilibili.com/video/BV1LK4y1x7Ws)

#### 屏蔽手机厂商底层适配细节。带你手写小米、Oppo、华为最强刘海屏适配架构
* [小米手机适配](https://github.com/733gh/Android-Notes/blob/master/android/%E5%B0%8F%E7%B1%B3%E9%80%82%E9%85%8D.md)
* [华为屏幕适配](https://github.com/733gh/Android-Notes/blob/master/android/%E5%8D%8E%E4%B8%BA%E6%89%8B%E6%9C%BA%E5%B1%8F%E5%B9%95%E9%80%82%E9%85%8D.md)
* [Oppo手机适配](https://github.com/733gh/Android-Notes/blob/master/android/Oppo%E6%89%8B%E6%9C%BA%E9%80%82%E9%85%8D.md)
* [各大手机厂商官方文档](https://github.com/733gh/Android-Notes/blob/master/android/%E5%90%84%E5%A4%A7%E6%89%8B%E6%9C%BA%E5%8E%82%E5%95%86%E5%AE%98%E6%96%B9%E6%96%87%E6%A1%A3.md)

## 深入讲解音视频编码原理，H264码流详解
* **[音视频格式封装原理](https://github.com/733gh/Android-Notes/blob/master/android/%E9%9F%B3%E8%A7%86%E9%A2%91%E6%A0%BC%E5%BC%8F%E5%B0%81%E8%A3%85%E5%8E%9F%E7%90%86.md)**
* **[视频压缩原理](https://github.com/733gh/Android-Notes/blob/master/android/%E8%A7%86%E9%A2%91%E5%8E%8B%E7%BC%A9%E5%8E%9F%E7%90%86.md)**
* **[帧内预测](https://github.com/733gh/Android-Notes/blob/master/android/%E5%B8%A7%E5%86%85%E9%A2%84%E6%B5%8B.md)**
* **[切片](https://github.com/733gh/Android-Notes/blob/master/android/%E5%88%87%E7%89%87.md)**
* **[H264分层](https://github.com/733gh/Android-Notes/blob/master/android/H264%E5%88%86%E5%B1%82.md)**
* **[手写H264编码器](https://github.com/733gh/Android-Notes/blob/master/android/%E6%89%8B%E5%86%99H264%E7%BC%96%E7%A0%81%E5%99%A8.md)**

## javassist即时编译技术，美团热修复核心与原理解
* **[javassist即时编译技术，美团热修复核心与原理解密01-美团热修复原理](https://github.com/733gh/Android-Notes/blob/master/android/javassist%E5%8D%B3%E6%97%B6%E7%BC%96%E8%AF%91%E6%8A%80%E6%9C%AF%EF%BC%8C%E7%BE%8E%E5%9B%A2%E7%83%AD%E4%BF%AE%E5%A4%8D%E6%A0%B8%E5%BF%83%E4%B8%8E%E5%8E%9F%E7%90%86%E8%A7%A3%E5%AF%8601-%E7%BE%8E%E5%9B%A2%E7%83%AD%E4%BF%AE%E5%A4%8D%E5%8E%9F%E7%90%86.md)**
* **[javassist即时编译技术，美团热修复核心与原理解密02-手写美团插件环境](https://github.com/733gh/Android-Notes/blob/master/android/javassist%E5%8D%B3%E6%97%B6%E7%BC%96%E8%AF%91%E6%8A%80%E6%9C%AF%EF%BC%8C%E7%BE%8E%E5%9B%A2%E7%83%AD%E4%BF%AE%E5%A4%8D%E6%A0%B8%E5%BF%83%E4%B8%8E%E5%8E%9F%E7%90%86%E8%A7%A3%E5%AF%8602-%E6%89%8B%E5%86%99%E7%BE%8E%E5%9B%A2%E6%8F%92%E4%BB%B6%E7%8E%AF%E5%A2%83.md)**
* **[javassist即时编译技术，美团热修复核心与原理解密03-Transform开发](https://github.com/733gh/Android-Notes/blob/master/android/javassist%E5%8D%B3%E6%97%B6%E7%BC%96%E8%AF%91%E6%8A%80%E6%9C%AF%EF%BC%8C%E7%BE%8E%E5%9B%A2%E7%83%AD%E4%BF%AE%E5%A4%8D%E6%A0%B8%E5%BF%83%E4%B8%8E%E5%8E%9F%E7%90%86%E8%A7%A3%E5%AF%8603-Transform%E5%BC%80%E5%8F%91.md)**

## 专业领域相关面试

> Opengl面试

[-----持续更新 未完待续-------](https://github.com/733gh/Android-Notes/tree/598d20d2a91c06cbec3a21909f4a4d87bbc88abd#)

> 智能家居串口面试

[-----持续更新 未完待续-------](https://github.com/733gh/Android-Notes/tree/598d20d2a91c06cbec3a21909f4a4d87bbc88abd#)

> 图形识别Opencv面试

[-----持续更新 未完待续-------](https://github.com/733gh/Android-Notes/tree/598d20d2a91c06cbec3a21909f4a4d87bbc88abd#)
 

#### 后续持续更新中，添加QQ群：[314550815](https://jq.qq.com/?_wv=1027&k=iB4pGGEY), 备注github
**[资料领取地址](https://shimo.im/docs/VYcc3wyJRpy9jJ83/ )**

**加QQ号，获取Android 2020年面试视频。发送"github "即可领取 另附企业内推，架构设计资料，相关视频资料**

![QQ扫码](img/QQ二维码.jpg)
 
