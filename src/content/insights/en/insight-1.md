---
title: "网格软件项目课程目录"
description: "详细列举课程中的每个专题的学习资料，如果有优质资源欢迎私信或发PR进行补充！"
cardImage: "@/images/insights/insight-1.png"
cardImageAlt: ""
---

课程目录是**学习资源目录**，如果有优质学习资源或意见与问题可以改

## 现代C++基础

**自学时间**：2025年6月下旬到8月上旬**集中学习**，之后可以自己接着学

C++基础十分重要，**无论之前学没学过**C++都需要选择一门适合自己水平的系列教程或书籍打打基础，因为现代C++的语法特性也同C++98有**很大的不同**，并**选择性**看一些其他课程巩固一下。

**学习建议**：
- 看自己的代码水平**至少挑一套**书（或教程）从头过到尾
- 常用的语法特性**只占大概20%**。不需要掌握并记住C++的所有语法特性，记得在哪看到的需要的时候知道回头看。重点是要把基础过一遍
- 多做练习或写工程代码，在**实践**中磨练代码水平
- 不需要掌握**最新的**语法特性。C++26快要出了，但很多企业还没用上C++20的特性，越新的语法特性相对用的越少
- C++**岗位方向**很多，基础打牢转行也相对容易，没事可以多去看看就业up、招聘软件和面经
- 图书可以去图书馆借纸质书看，如果觉得有意思可以下电子版或自己买一本
- 初学阶段先**避开**CMake与vcpkg等工具，专注C++语法特性学习、IDE使用、项目调试与配置技巧

C++**就业区**up：[2025年C++方向分析【程序员老秦】](https://www.bilibili.com/video/BV1ZL5szJEYb/)

### C++语言学习

 **入门** ：**C语言基础，没写过C++；学过C++但基础不牢靠**，想重新过一遍基础并学习C++新特性。这些书关注**C++基础语法与面向对象编程技巧**。
- **《C++ Primer中文版》**：经典入门书籍，原书出版于2012年，只涵盖到C++11标准
- **《C++程序设计：原理与实践（原书第2版）》**：英文名《Programming -- Principles and Practice Using C++(2nd Edition)》**（PPP 2ed）**，原书于**2014年**出版，涵盖到C++14的特性，比较够用了。译本：
  - 机械工业出版社：**2017年**出版，分两本书 基础篇/实践篇
  - 清华大学出版社：**2024年**出版，分上下卷，没找到电子版图书馆有纸质版，听说本书注解、ppt等配套资源挺多，比较推荐**初学者**尝试学习
- 上本**英文原书PPP第3版**出版于**2024年**，有电子版
  - 内容相比前半**减少了一半**，作者解释说是由于有在线上的语法参考文档方便了（cppreference），故略去了很多参考内容
  - 内容很新，涉及到最新C++23的特性
  - 但由于文章内大量使用 *模块*（modules，C++20新特性，目前主流编译工具并没有完全支持），且该版本目前国内没有译本，请初学者**谨慎阅读**，有基础者酌情翻看
- [C++ 教程 - 油管大佬The Cherno C++ 教程_哔哩哔哩_bilibili](https://www.bilibili.com/video/BV1uy4y167h2/)
- [C++基础知识点_打洞哥_哔哩哔哩_bilibili](https://space.bilibili.com/1209242940/lists/2931493?type=season)
  - 前者不仅讲基础还讲一些项目配置，后者偏基础
- 夏曹俊出品**精品现代C++课程**：[现代C++零基础到工程实战_哔哩哔哩_bilibili](https://www.bilibili.com/cheese/play/ep1178219)
  - 网盘链接部分课程：[大工云盘](http://pan.dlut.edu.cn/share?id=9sn5ndu82k2u)

**进阶**：**C++基础较牢**或有一定的**现代C++编程基础**。以下关注**现代C++知识与编程技巧**
- [cppreference.com — C++参考手册](https://zh.cppreference.com)：C++之父提到的参考网站
  - **仅作参考使用**，不建议猛攻文档学习
  - 这个参考文档本身是有中文版本维护的，但是目前主服务器在升级，临时下架了多语言暂时只能查阅英语文档
- 《C++20高级编程(第5版)》原书《Professional C++, 5th Edition》于2021年出版，涵盖到C++20的特性。**很好的一本书**从C++语法讲起逐渐深入到后面还有软件工程的知识，**美中不足**的是翻译的有点不上心。**（PC++ 5ed）**
  - 需要注意的是因为本书较新，所以代码也大量使用 *模块*，学习时需要注意一下
- 《PC++ 6ed》出版于**2024年** 涵盖了到C++23的特性，但国内没有出版社出译本，有一位大佬给出了自己的**译本**[2024年第二本C++相关的书籍——从C++20/23到软件工程的详细介绍（Professional C++）书评](https://book.douban.com/review/16089419/)
  - 《C++23高级编程(第6版)》7月1号刚出版，图书馆也还没购入，想买书的同学可以看看
  - 两个本书都挺**适合有一定C++基础**，希望上手与进阶**现代C++甚至上手软件开发**的同学
- [一起来学C++_哔哩哔哩_bilibili](https://space.bilibili.com/80353385/lists/3849162?type=season)
- [现代C++核心语言特性教程_哔哩哔哩_bilibili](https://space.bilibili.com/65858958/lists/5208246?type=season)
- [现代C++基础_哔哩哔哩_bilibili](https://space.bilibili.com/18874763/lists/2192185?type=season)
  - 前两个是逐个语法点讲解可以跳着看，后者偏硬核聚焦某个主题

**高级**：在对C++特性基本了解的情况下，可以学习了解代码规范与设计模式来进行大型项目程序设计了
- 《C++20代码整洁之道：可持续软件开发模式实践（原书第2版）》：原书著于2021年，书中主要对各种**设计原则和编程技巧**与方法做介绍，所以并不是讲解C++语法的书，但对编程方法特别是大型项目的开发方法有启发作用。
  - 本书主译是CSDN的C++版版主，译者和作者的水平都很高，看起来很舒服能较轻松理解作者的思想
  - 同系列类似封面的书籍好像都挺不错的，还有同系列的《C++20设计模式》、《C++20编程技巧：98个问题解决方案实例》、《现代C++编程实战》等书也可以看看
- 《C++ Core Guidelines 解析》原书著于2022年，内容是对网上一个开源项目（C++ Core Guidelines）做解析，原项目本身就是从各个语法角度出发来规范程序员写代码的行为，但内容比较零散，且例子可能不那么形象。为了不至于各种规则沦为“规则怪谈”就出了本书解释其中一些比较重要的规则。
- [CppCoreGuidelines-zh-CN | Translation of C++ Core Guidelines [https://github.com/isocpp/CppCoreGuidelines] into Simplified Chinese.](https://lynnboy.github.io/CppCoreGuidelines-zh-CN/)
  - 上面提到的开源项目网站
- [新手必学：华为C&C++语言编程规范 - 知乎](https://zhuanlan.zhihu.com/p/473111337)
  - 以上两个代码规范更多是从“**不能做什么**”的角度规定规则，编写项目代码还是要学习设计方法与设计原则等软件工程方法来指导设计
- [【熟肉】代码美学_哔哩哔哩_bilibili](https://space.bilibili.com/1629390/lists/1068921?type=season)

### C++开发环境配置

**编译**指将某个代码文件编译成二进制中间文件，**链接**是将二进制中间文件合并成更大的二进制文件或可执行文件（.exe）；而**构建**是从头将项目源代码文件到目标二进制文件（可执行文件.exe）的整个过程，包括了所有编译与链接的环节。

需要区分编译（compile）与构建（build）的概念，一个是编译**某个cpp文件**产生二进制中间文件（如.obj），另一个是构建**整个项目的源代码文件**到项目目标可执行文件（如.exe）

**介绍 *项目构建工具***：*项目配置文件* **指导** *项目构建工具* 构建项目，其**本质**是调用编译器程序执行编译与链接的**脚本**
- **Windows**: Visual Studio 与 VSC++项目中的 *项目配置文件* `.vcproj`
  - 这个 *项目构建工具* 包含在VS这个IDE内
  - 不推荐安装mingw等其他GNU工具集，来在Windows上使用make和gcc
- **Linux**: make 与 `Makefile` *项目配置文件*
  - [Makefile 20分钟入门，简简单单，展示如何使用Makefile管理和编译C++代码_哔哩哔哩_bilibili](https://www.bilibili.com/video/BV188411L7d2/)
- **MacOS**: XCode 与 Xcode *项目配置文件* `.xcodeproj`
  - 同样 *项目构建工具* 也涵盖在XCode这个IDE内
- （了解）跨平台：Ninja 与 `build.ninja`文件 、 CMake 与 `CMakeLists.txt`文件

**介绍C++集成开发环境（IDE）**: 写代码调代码的软件，自行**选择一个学习即可**
- **Visual Studio**: **Windows最常用**的C++开发IDE，有自己的*项目构建工具*
  - 也可用于连接Linux主机远程调试
- **Visual Studio Code (VSCode)**: 跨平台的轻量级代码编辑工具，没有自己的*项目构建工具* ，默认只能单cpp文件编译调试。需要配置其他 *项目构建工具* 才能做C++项目开发
  - 可以在Linux主机上结合 *项目构建工具* make开发
- **XCode**: MacOS上的C++开发IDE
- （了解）CLion: 功能强大的跨平台的C/C++开发IDE，前阵子开放免费社区版，借助CMake做项目构建

**Visual Studio**的C++开发教程：
1. **项目配置与调试入门**：群文件*第一次前处理上机.mp4/.pptx*（前半部分）
    - 项目配置：本质是修改了 `.vcproj`等 *项目配置文件*
2. **调试**：[教程：调试C++代码 - Visual Studio (Windows) | Microsoft Learn](https://learn.microsoft.com/zh-cn/visualstudio/debugger/getting-started-with-the-debugger-cpp)
3. （**了解通读即可**）越过VS IDE，直接使用**命令行操作**VC++工具集：
   1. [演练：在命令行上编译本机 C++ 程序 | Microsoft Learn](https://learn.microsoft.com/zh-cn/cpp/build/walkthrough-compiling-a-native-cpp-program-on-the-command-line)
   2. 这个MSBuild就是VS的 *项目构建工具*：[演练：使用 MSBuild 创建 Visual Studio C++ 项目 | Microsoft Learn](https://learn.microsoft.com/zh-cn/cpp/build/walkthrough-using-msbuild-to-create-a-visual-cpp-project)
4. **Linux**系统远程开发**选学**：[在 Visual Studio 中配置 Linux MSBuild C++ 项目 | Microsoft Learn](https://learn.microsoft.com/zh-cn/cpp/linux/configure-a-linux-project)
> 以下内容建议有**一定C++基础**了再选修
1. [动态库和静态库到底有什么区别？_哔哩哔哩_bilibili](https://www.bilibili.com/video/BV1fb421q7gc/)
2. [演练：创建并使用静态库 (C++) | Microsoft Learn](https://learn.microsoft.com/zh-cn/cpp/build/walkthrough-creating-and-using-a-static-library-cpp)
3. [在 Visual Studio 中创建 C/C++ DLL | Microsoft Learn](https://learn.microsoft.com/zh-cn/cpp/build/dlls-in-visual-cpp)
4. [演练：创建和使用自己的动态链接库 (C++) | Microsoft Learn](https://learn.microsoft.com/zh-cn/cpp/build/walkthrough-creating-and-using-a-dynamic-link-library-cpp)
5. 尝试安装并导入第三方库（OCC）并成功运行：
   1. 下载预编译包的[github链接](https://github.com/Open-Cascade-SAS/OCCT/releases/download/V7_9_1/occt_vc14-64-combined-with-debug.zip)
   2. [参考系列教程的第一节课程](https://www.bilibili.com/video/BV1Kx421D7As)

**VSCode**的C++开发教程：跨平台都可以用，更推荐在**Linux**系统使用，教程以官方文档为主
1. 设置**中文界面**：`Ctrl+Shift+P`输入`display language`找到`Configure Display Language`，找到简体中文
2. 在欢迎页面找到**演练**，找到**C++开发入门**并学习基本操作
3. 群文件 *C++ in VS Code： A Quick Guide (中英双语).mp4*
4. [Introductory Videos for C++](https://code.visualstudio.com/docs/cpp/introvideos-cpp)
   * 页面第一个视频是C++ in VS Code： A Quick Guide，可以开字幕看第2~4个视频
5. 在这个页面左侧选择自己的系统应用场景，如[Using C++ on Linux in VS Code](https://code.visualstudio.com/docs/cpp/config-linux)
6. 顺着[Editing and Navigating C++ Code](https://code.visualstudio.com/docs/cpp/cpp-ide)接着看
7. （Linux系统）下载`Makefile Tools`插件[VSCode使用Makefile管理工程_vscode makefile-CSDN博客](https://blog.csdn.net/yueyuanhuaqing/article/details/140159208)