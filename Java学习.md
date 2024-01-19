# cmd

+ cd/、dir、cd..、cls、exit、cd
+ 配置环境变量快速找到路径
+ 地址栏输入cmd快速打开

#　环境变量

+ 环境变量（environment variables）一般是指在[操作系统](https://baike.baidu.com/item/操作系统/192?fromModule=lemma_inlink)中用来指定操作系统运行环境的一些参数，如：[临时文件夹](https://baike.baidu.com/item/临时文件夹/1061467?fromModule=lemma_inlink)位置和[系统文件夹](https://baike.baidu.com/item/系统文件夹/5328647?fromModule=lemma_inlink)位置等。
+ 安装时，JDK自动配置环境变量

# JDK（Java开发工具包）

## 用法

+ javac编译.java文件
+ java运行class文件

## 内容

+ JVM（Java virtual machine：虚拟机）

+ 核心类库
+ 开发工具（javac编译、java运行、jdb调试、jhat内存分析工具）

## JRE（Java运行环境）

### 内容

+ JVM
+ 核心类库
+ 运行工具

# Java

## 分类

+ JavaSE桌面开发
+ JavaME嵌入式开发
+ JavaEE服务器开发

## 语法

###　基本数据类型

+ 浮点数类型后加F（如：float a=1.5F）
+ byte类型（-127-128）
+ 布尔类型为boolean
+ String类型需大写
+ 其余与c/c++类似

### 输入（导包、创建对象、接收数据）

+ 导包：import java.util.Scanner;
+ 创建对象：Scanner sca=new Scanner(System.in);
+ 接受数据（整形）：int i=sca.nextInt();

### 接收数据

+ int i=obj.nextInt()/String arr=obj.next()

### 输出

+ 打印：System.out.print（）；
+ 打印一行：System.out.println（）；

### 注释

+ 文档注释（Java中doc工具）

###　运算符和表达式

+ 强制转换（默认转为范围大的类型，有字符串转为字符串，byte/short/char转为int计算）
+ 逻辑符号（^:异或   |;或   &:与    !: 非   ||:短路或（前条件为假直接返回假）   &&:短路与（前条件为真直接返回真）>>>:无符号右移 >>:右移   <<:左移）

### 数据处理

+ 开平方：Math.sqrt（）；
+ 随机数：Random r=new Random（seed）；Datetype i=r.nextInt（bound）+k（确定范围）；（导包：java.util.Random）
+ 数组：（1）静态创建：char[]  arr=new char{" "}，简写为char[] arr={" "}；（2）获取大小：arr.length（）；（3）动态创建：char       []  arr=new char[length];

### 关键字（小写）

+ 类

### 方法

+ 最小执行单元
+ public class 类型 方法名(参数){内容+返回值 }

## idea

### 项目构成

+ 项目——模块——包——类
+ idea设置：自动导包、背景设置、无视大小写联想等

### 项目和模块的操作



