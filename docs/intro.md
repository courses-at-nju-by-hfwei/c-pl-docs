# 课程简介

<small>最后更新于 {docsify-updated}。</small>

## 课程信息

- **课程名称：** C 语言程序设计基础 (C Programming Language)

- **课程简称：** `CPL`

- **课程编号：** $25000490$ || $90211101$

- **课程性质：** 平台课（即专业基础课）

- **授课对象：** 南京大学软件学院 && 技术科学试验班（包括数字经济专业）大一新生

- **课程图标：** ![CPL](.assets/images/C_Programming_Language.svg ':size=50')

- **授课教师：**

<!-- tabs:start -->

### **软件学院**

- [魏恒峰](https://hengxin.github.io/) <small>([蚂蚁蚂蚁](https://www.bilibili.com/video/BV16y4y1Y7u6))</small>
- [王慧妍](http://www.why.ink:8080/)

### **技术科学试验班**

- 1 班：郭延文

- 2 班：冯洋

- 3 班：[王慧妍](http://www.why.ink:8080/)

- 4 班：[杨已彪](https://yangyibiao.github.io/cpl/)

- 5 班：陈鑫

- 6 班：[魏恒峰](https://hengxin.github.io/)

- 7 班：赵振南

<!-- tabs:end -->

## 授课安排

软件学院每周 $2$ 个课时，技术科学试验班每周 $3$ 个课时。

<!-- tabs:start -->

### **软件学院**

- 周五 7-8 节 3-17 周 费彝民楼 A-318
	- [腾讯会议: 724-5404-3881](https://meeting.tencent.com/dm/ZFU47hkkPgxX)

<!-- ![2022-CPL-Software](.assets/images/2022-CPL-Software.svg ':size=60%') -->

### **技术科学试验班**

- 1 班：周五 2-4 节 3-17 周 教学楼-213

- 2 班：周四 9-11 节 3-17 周 教学楼-102

- 3 班：周五 2-4 节 3-17 周 逸夫馆 III-201

- 4 班：周五 2-4 节 3-17 周 费彝民楼 A-206
  - [腾讯会议：315-039-2484](https://meeting.tencent.com/p/3150392484)

- 5 班：周五 2-4 节 3-17 周 费彝民楼 A-202

- 6 班：周四 9-11 节 3-17 周 费彝民楼 A-318
  - [腾讯会议: 884-4770-1358](https://meeting.tencent.com/dm/pC25I6sbAybt)

- 7 班：周三 9-11 节 1-17 周 南雍-西122（苏州校区）

<!-- ![2022-CPL-SuZhou](.assets/images/2022-CPL-SuZhou.svg ':size=60%') -->

<!-- tabs:end -->

## 授课教材

?> 不会统一发放教材。</br>
请同学们自行购买印刷版或使用 [电子版](resources?id=电子书籍)。</br>
可以考虑从学长处购买二手书，书上的笔记或许对你有帮助（如果学长读了书的话）。

- **《C语言程序设计 现代方法 (英文版/中文版) 第2版 修订版》 K. N. King 著, 人民邮电出版社**

本书是大部头，一学期讲不完。

每周课前，会发布建议阅读章节。见下方 [教学周历](intro?id=教学周历)。

**课后，学生也要反复阅读教材指定章节，尤其是要补充学习课上仅作简单介绍的知识点。**

对于课堂上仅作简要介绍或没有介绍、但属于教材指定章节的知识点，[OJ 练习](problemset) 中也会涉及。

## 教学周历

!> 具体内容可能会随课堂进度进行调整。</br>
根据 2023 年授课经验，软件学院每堂课 $2$ 个学时，进度偏快。</br>
技术与科学试验班，$3$ 个学时，节奏可以更从容些。

?> 可访问 **2023-CPL** 资源获取更详细信息：[课程课件](resources?id=课程课件)、[示例代码](resources?id=课程代码仓库)、[授课录屏](resources?id=视频资源)。</br>
周历中 **阅读材料** 指的是教材中的章节。各位同学应仔细、反复阅读。

| 周数 | 内容 | 知识点 | 备注 | 阅读材料 |
| ----- | ----- | ----- | ----- | ----- |
| 3 (0-intro) | Introducing C | 课程简介、 演示开发环境、`hello-world`、 `Game: Guess the Number` | `Game: Guess the Number` 涉及到第 4 到 8 周的内容，目的是让学生对将要学习的内容有个初步认识 | 1.1、1.2；2.1、2.2、2.3 |
| 4 (1-types-io) | Variables, Types, I/O | Variables, Data Types; Operators, Expressions, Assignment Statements; `int`, `double`, `char`, `C string`; `printf`, `scanf`; `math.h`, `ctype.h` | 本次课程不讲授 `float`、`unsigned` 等 C 语言中初学者容易犯错的知识点, 留到第 9 周 | 2.4--2.8；3.1--3.2；4.1--4.5；22.3；23.4、23.5 |
| 5 (2-if-for-array) | If, For, Array | `if` 语句、初步介绍 `for` 循环语句、初步介绍一维数组 | 软件学院 2 个学时内讲不了 `switch/case`（5.3），请大家自学 | 5.1--5.3；6.3；8.1 |
| 6 (3-for-a-while) | For, While, Do-While | 更多 `for` 例子、`while` 与 `do-while` 语句、`break` | 请**务必**讲解 `selection sort` 与 `binary search` (这周与下周两周内); 请自学 `continue` | 6.1、6.2、6.4、6.5 |
| 7 (4-loops) | Loops; Multi-dimensional Arrays | More examples on loops; 二维数组 | *建议*讲解 Conway's Game of Life; 请**务必**讲解 `Merge sort` 中的 `merge` 过程 | 8.2、8.3 |
| 8 (5-function) | Function; Scopes | 函数的概念与使用; 作用域与程序结构 | 9.7 内容可选, 或许会录制短视频讲解 | 9.1 -- 9.5、10.1 -- 10.5 |
| 9 (6-data-types) | Data Types | 基本数据类型; 与数据类型相关的安全编程 | 介绍 Undefined Behaviors (最迟在此次课介绍) | 7.1 -- 7.6 |
| 10/11 (7-pointers-arrays) | Pointers | 指针的基本概念，指针与一维数组，动态内存分配 | | 11.1 -- 11.5；12.1 -- 12.3；17.1 -- 17.4 |
| 12 (8-pointers-cstrings) | Pointers and C Strings | 指针与字符串 | | 12.4；13.1 -- 13.6 |
| 13 (9-double-pointers) | Double Pointers | 指针与字符串数组、命令行参数、指针与二维数组 | | 12.4；13.7；17.6 |
| 14 (10-function-pointers) | Function Pointers | 函数指针、如何解读声明语句 | | 17.7; 18.4 |
| 15 (11-struct) | Struct; Union; Enum | 结构体、联合体、枚举类型 | 软件学院 16.4 节自学;  | 16.1 -- 16.5; 17.9 |
| 16 (12-linkedlists) | Linked Lists | 链表 | | 17.5; 19.4 |
| 17 (13-recursion) | Recursion | 递归的概念与举例 | *建议*介绍 `merge-sort`; 本节内容不作过多要求 | 9.6 |

## 授课方式

(软件学院) 授课采用“现场解题、写代码”的形式。

每次课前（前两次课除外），在 [GitHub](resources?id=课程代码) 上公布题目以及空的代码文件。

?> 大家**不需要**做到在课堂上跟着写代码。</br>
课堂上重在理解知识点，掌握思路。</br>
可以课后再跟着录屏写代码

!> 这件事，一定要做；你以为你会写了，与你写了，完全是两回事。

每次课后，会在 GitHub 上提交完整的代码文件。

## 课程讲义
本学期 CPL 课程新增[【课程讲义】](https://ymv59wdgrr.feishu.cn/wiki/A1HzwviAgiFnQwkfRUWcVjqunLf)，提供一些图文教程作为课堂的补充，将在飞书平台上持续更新。

浏览器可直接访问；手机 QQ 若无法直接访问，可复制链接到浏览器打开。

大家可持续关注更新。如有建议/补充/勘误，也欢迎各位指出~

?> 课程讲义是上课的一个重要辅助工具，内含**课堂讲义、基础教程、工具精讲、经验分享**等多个板块，</br>
是 CPL 课程的重要组成部分，鼓励同学们在课余时间多阅读、多思考。

## 学习方法

?> **纸上得来终觉浅，绝知此事要躬行。**

学习程序设计语言，没有捷径。所有的捷径，都是“从入门到放弃”。

看似最笨、最慢的那条路，方为正途。

?> **操千曲而后晓声，观千剑而后识器。**

学习程序设计语言，一要多写（敲代码），二要多读。

多写，熟能生巧，才能有真正的体会。

多读，向高手学习，才能不断精进，同时提高编程品味。
