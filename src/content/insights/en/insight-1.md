---
title: "网格软件项目课程目录"
description: "详细列举课程中的每个专题的学习资料，如果有优质资源欢迎私信或发PR进行补充！"
cardImage: "@/images/insights/insight-1.png"
cardImageAlt: ""
---

课程目录会假定各位同学的基础，请对应选择课程自行观看学习，如果你们也有优质课程资源欢迎提供或者向仓库发PR。

## 现代C++基础

C++基础十分重要，无论之前学没学过C++都需要选择一门适合自己水平的系列教程或书籍打打基础，因为现代C++的语法特性也同C++98有很大的不同，并选择性看一些其他课程巩固一下。

**学习建议**：
- 看自己的代码水平挑一套教程从头过一遍
- 不需要掌握并记住C++的所有语法特性，C++常用的特性就那些，记得在哪看到的就行，需要的时候知道回头看哪里。重点是要把基础过一遍
- 多做练习或写工程代码，在**实践**中磨练代码水平
- 不需要掌握**最新的**语法特性。C++26快要出了，但很多企业还没用上C++20的特性，且基础不牢靠情况下追新的语法特性会失去重点
- C++**岗位方向**很多，基础打牢转行也相对容易，没事可以多去看看就业up、招聘软件和面经
- 图书可以去图书馆借纸质书看，如果觉得有意思可以下电子版或自己买一本

C++就业区up：[2025年C++方向分析【程序员老秦】](https://www.bilibili.com/video/BV1ZL5szJEYb/)

 **入门** ：C语言基础，没写过C++；学过C++但基础不牢靠，想重新过一遍基础并学习C++新特性。这些书关注C++基础语法与面向对象编程技巧。
- 《C++ Primer中文版》：经典入门书籍，原书出版于2012年，只涵盖到C++11标准
- 《C++程序设计：原理与实践（原书第2版）》：英文名《Programming -- Principles and Practice Using C++(2nd Edition)》**（PPP 2ed）**，原书于**2014年**出版，涵盖到C++14的特性，比较够用了。译本：
  - 机械工业出版社：**2017年**出版，分两本书 基础篇/实践篇
  - 清华大学出版社：**2024年**出版，分上下卷，没找到电子版图书馆有纸质版，听说本书注解、ppt等配套资源挺多，比较推荐**初学者**尝试学习
- 上本英文原书PPP，第3版出版于**2024年**，有电子版
  - 内容相比前半**减少了一半**，作者解释说是由于有在线上的语法参考文档方便了（cppreference），故略去了很多参考内容
  - 内容很新，涉及到最新C++23的特性
  - 但由于文章内大量使用模块（modules，C++20新特性，目前主流编译工具并没有完全支持），且该版本目前国内没有译本，请初学者**谨慎阅读**，有基础者酌情翻看
- [C++基础知识点_打洞哥_哔哩哔哩_bilibili](https://space.bilibili.com/1209242940/lists/2931493?type=season)
- [C++ 教程 - 油管大佬The Cherno C++ 教程_哔哩哔哩_bilibili](https://www.bilibili.com/video/BV1uy4y167h2/)
  - 前者不仅讲基础还讲一些项目配置，后者偏基础

**进阶**：C++基础较牢或有一定的现代C++编程基础。以下关注现代C++知识与编程技巧
- [cppreference.com — C++参考手册](https://zh.cppreference.com)：C++之父提到的参考网站
  - 这个参考文档本身是有各个语言版本维护的，但是目前主服务器在升级，临时下架了多语言暂时只能查阅英语文档
- 《C++20高级编程(第5版)》：原书《Professional C++, 5th Edition》（PC++ 5ed）于2021年出版，涵盖到C++20的特性。很好的一本书从C++语法讲起逐渐深入到后面还有软件工程的知识，美中不足的是翻译的有点不上心。
  - 需要注意的是因为本书较新，所以代码也大量使用模块，学习时需要注意一下
- 《PC++ 6ed》出版于**2024年** 涵盖了到C++23的特性，但国内没有出版社出译本，有一位大佬给出了自己的译本[2024年第二本C++相关的书籍——从C++20/23到软件工程的详细介绍（Professional C++）书评](https://book.douban.com/review/16089419/)
  - 两个本书都挺适合有一定C++基础，希望上手现代C++甚至上手软件开发的同学
- [一起来学C++_哔哩哔哩_bilibili](https://space.bilibili.com/80353385/lists/3849162?type=season)
- [现代C++核心语言特性教程_哔哩哔哩_bilibili](https://space.bilibili.com/65858958/lists/5208246?type=season)
- [现代C++基础_哔哩哔哩_bilibili](https://space.bilibili.com/18874763/lists/2192185?type=season)
  - 前两个是逐个语法点讲解可以跳着看，后者偏硬核聚焦某个主题

**高级**：在对C++特性基本了解的情况下，可以学习了解代码规范与设计模式来进行大型项目程序设计了
- 《C++20代码整洁之道：可持续软件开发模式实践（原书第2版）》：原书著于2021年，书中主要对各种**设计原则和编程技巧**与方法做介绍，所以并不是讲解C++语法的书，但对编程方法特别是大型项目的开发方法有启发作用。
  - 本书主译是CSDN的C++版版主，译者和作者的水平都很高，看起来很舒服能较轻松理解作者的思想
  - 同系列类似封面的书籍好像都挺不错的，还有本《C++20设计模式》等书可能也可以看看
- 《C++ Core Guidelines 解析》原书著于2022年，内容是对网上一个开源项目（C++ Core Guidelines）做解析，原项目本身就是从各个语法角度出发来规范程序员写代码的行为，但内容比较零散，且例子可能不那么形象。为了不至于各种规则沦为“规则怪谈”就出了本书解释其中一些比较重要的规则。
- [CppCoreGuidelines-zh-CN | Translation of C++ Core Guidelines [https://github.com/isocpp/CppCoreGuidelines] into Simplified Chinese.](https://lynnboy.github.io/CppCoreGuidelines-zh-CN/)
  - 上面提到的开源项目网站
- [新手必学：华为C&C++语言编程规范 - 知乎](https://zhuanlan.zhihu.com/p/473111337)
  - 以上两个代码规范更多是从“**不能做什么**”的角度规定规则，编写项目代码还是要学习设计方法与设计原则等软件工程方法来指导设计
- [【熟肉】代码美学_哔哩哔哩_bilibili](https://space.bilibili.com/1629390/lists/1068921?type=season)