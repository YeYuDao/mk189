# mk189
面试跳槽提升必备 全面解析iOS中的Runtime机制
面试跳槽提升必备 全面解析iOS中的Runtime机制
[![下载地址](https://img.mukewang.com/szimg/5fce046709c79c1405400304.jpg "下载地址")](https://51xueit.vip "下载地址")
[下载地址](https://51xueit.vip "下载地址")
### 第1章 课程介绍 

#### 介绍课程目标和学习内容，以及课程需要用到的知识点和环境参数。
1-1 全面解析iOS中的Runtime机制导学 (11:17)

1-2 介绍课程目标和学习内容 (09:05)

1-3 课程需要用到的知识点和环境参数 (02:45)


### 第2章 Runtime之必备C知识

#### 本章主要介绍指针、结构体、位运算以及宏定义相关知识点对应的操作及概念。
2-1 指针介绍 (05:13)

2-2 普通指针、指针的指针实际演练 (07:36)

2-3 数组指针实际演练 (05:56)

2-4 函数指针实际演练 (05:43)

2-5 结构体介绍 (09:04)

2-6 访问结构体、结构体指针 (07:48)

2-7 结构体位域 (06:12)

2-8 位运算介绍 (08:42)

2-9 左移、右移位运算 (11:08)

2-10 或、异或、取反位运算 (05:16)

2-11 宏定义介绍及基本宏定义操作 (06:53)

2-12 宏定义逻辑判断 (04:51)

2-13 通过C语言中的结构体设计类的实现，该如何处理


### 第3章 Runtime之类的本质

#### 本章主要介绍什么是Runtime、Tagged Pointer、isa_t以及讲解OC中的类结构和NSObject常用方法解析。
3-1 介绍OC、C、Runtime三者之间的关系 (05:08)

3-2 Runtime库和Runtime开源代码演示 (09:10)

3-3 OC中的类结构 (07:14)

3-4 OC对象模型 (11:42)

3-5 Tagged Pointer介绍 (07:52)

3-6 isa_t介绍 (10:16)

3-7 NSObject常用方法介绍 (07:31)

3-8 NSObject常用方法解析 (11:31)

3-9 id类型和NSObject的区别？


### 第4章 Runtime之消息处理

#### 本章主要讲解消息处理策略，包含类方法和实例方法之间的区别、objc_msgSend、消息发送流程、直接跳过消息发送流程、消息转发流程、动态消息解析、重定向、转发、模拟多继承。
4-1 类方法和实例方法之间的区别 (15:14)

4-2 objc_msgSend介绍 (11:29)

4-3 消息发送流程 (10:42)

4-4 直接跳过消息发送流程 (07:54)

4-5 消息转发流程 (09:32)

4-6 类方法动态消息解析 (11:01)

4-7 实例方法动态消息解析 (07:41)

4-8 重定向 (03:30)

4-9 转发 (10:59)

4-10 模拟多继承 (05:31)

4-11 OC语言中模拟实现多继承的方式有哪些？


### 第5章 Runtime之常用API

#### 本章主要讲解Runtime的常用API，包含获取一个类objc_getClass、获取类的名称class_getName、获取变量列表class_copyIvarList、获取属性列表class_copyPropertyList、获取方法列表class_copyMethodList 、获取协议列表class_copyProtocolList、动态添加变量class_addIvar、动态添加方法class_addMethod、动态交换方法method_...
5-1 获取一个类objc_getClass (11:42)

5-2 获取类的名称class_getName (05:04)

5-3 获取成员变量class_copyIvarList介绍 (06:35)

5-4 获取成员变量class_copyIvarList实践 (07:59)

5-5 获取成员属性class_copyPropertyList (11:47)

5-6 获取类的方法class_copyMethodList (13:41)

5-7 获取协议列表class_copyProtocolList (10:32)

5-8 动态添加变量class_addIvar介绍 (08:29)

5-9 动态添加变量class_addIvar实践 (08:51)

5-10 动态添加方法class_addMethod介绍 (06:28)

5-11 动态添加方法class_addMethod实践 (08:39)

5-12 动态交换方法method_exchangeImplementations (07:29)


### 第6章 Runtime之初始化过程

#### 本章主要讲解Runtime的初始化过程，主要讲解程序加载过程、函数map_images、函数load_images、函数initialize 。
6-1 程序加载过程 (10:34)

6-2 函数map_images介绍 (08:55)

6-3 函数map_images实践 (09:54)

6-4 函数load_images (11:33)

6-5 函数initialize (09:50)


### 第7章 Runtime之Category

#### 本章主要讲解Runtime的Category，首先会介绍什么是Category，接着会讲解Category的初始化、Category中的方法覆盖问题、Category Associate的介绍 、Category Associate的实现。
7-1 Category介绍 (12:33)

7-2 Category的初始化 (11:11)

7-3 Catory中的方法覆盖问题(一) (08:08)

7-4 Catory中的方法覆盖问题(二) (06:21)

7-5 Category Associat的介绍及实现 (12:17)


### 第8章 Runtime之KVO 

#### 本章主要讲解KVO的原理解析，并且会手动调用KVO，以及模拟KVO的实现。
8-1 KVO介绍 (10:48)

8-2 KVO原理解析 (10:44)

8-3 KVO配合代码解析 (07:07)

8-4 手动调用KVO (12:25)

8-5 模拟KVO的实现-修改isa指针 (20:03)

8-6 模拟KVO的实现-添加修改后的Setter、class方法 (15:27)

8-7 模拟KVO的实现-通知外界 (17:44)

8-8 模拟KVO的实现-实际运用 (12:49)


### 第9章 Runtime之应用技巧 

#### 本章主要讲解Runtime在企业开发中的实际应用，包括Method Swizzling处理数组越界、字典和模型的自动转换、自动归档和自动解档、万能跳转界面方法。
9-1 Method Swizzling处理数组越界-原理分析 (08:28)

9-2 Method Swizzling处理数组越界-主要方法实现 (10:32)

9-3 Method Swizzling处理数组越界-在load中交换方法 (08:42)

9-4 Method Swizzling处理数组越界-如何处理数组越界 (12:49)

9-5 字典和模型的自动转换-原理分析 (12:01)

9-6 字典和模型的自动转换-Model的三种情况 (14:26)

9-7 字典和模型的自动转换-特殊需求的转换 (12:43)

9-8 手动归档和手动解档 (10:19)

9-9 自动归档和自动解档 (10:14)

9-10 自动归档和自动解档代码封装 (05:57)

9-11 万能跳转界面方法-原理分析 (20:50)

9-12 万能跳转界面方法-主要方法实现 (14:42)

9-13 万能跳转界面方法-跳转指定界面 (12:48)

9-14 如何利用Runtime全局埋点？


### 第10章 Runtime之面试题目

#### 本章会讲解企业面试中十道经典的Runtime面试题目，让你轻松拿高薪offer。
10-1 面试题-alloc+init与new区别 (12:19)

10-2 面试题-Runtime如何通过Selector找到对应的IMP地址 (20:53)

10-3 面试题-实例变量 (08:25)

10-4 面试题-类结构体 (05:37)

10-5 面试题-Runtime Associate (14:21)

10-6 面试题-Objective-C中调用方法的过程 (10:19)

10-7 面试题-Runtime 如何实现 Weak 属性 (18:24)

10-8 面试题-[self class]和[super class] (08:15)

10-9 面试题-isKindOfClass和isMemberOfClass (07:01)

10-10 面试题-类间组织关系的理解 (05:30)

10-11 你了解热修复原理吗？


### 第11章 课程总结

#### 回顾课程知识点，尤其Runtime中的重难点，技术点。针对如何扩展学习Runtime，给出经验与建议。
11-1 内容总结 (07:09)

11-2 经验建议 (08:40)


[下载地址](https://51xueit.vip "下载地址")
