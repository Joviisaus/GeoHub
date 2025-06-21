---
title: "网格软件项目课程"
description: "网格软件项目课程学习路线" 
main:
  id: 2
  content: |
    网格项目课程面向本科生同学，特别是工业软件班成员开设。课程不是工业软件班的系列课程，没有学分，是学生自行组织的培训课程，不要求强制选修。但项目课程会讲解具体上手的开发技术，服务于项目本身，是工业软件班系列课程的补充部分。
  imgCard: "@/images/C++.png"
  imgMain: "@/images/C++.png"
  imgAlt: "Mockup boxes of assorted screw set"
tabs:
  - id: "tabs-with-card-item-1"
    dataTab: "#tabs-with-card-1"
    title: "简介"
  - id: "tabs-with-card-item-2"
    dataTab: "#tabs-with-card-2"
    title: "详细内容"
longDescription:
  title: "工业软件开发技术分享"
  subTitle: |
    关注工业软件中的研发设计类软件，其中的CAX需要实现三维模型的表示，允许用户通过模型选择施加算法输入条件，根据输入条件进行算法处理。算法越灵活，对模型表示与模型元素定义的要求就越高，这些都是CAX软件的实现困难所在。
  btnTitle: "网格软件开发"
  btnURL: "../../insights/insight-1/"
descriptionList:
  - title: "现代C++ 开发基础"
    subTitle: "虽然近年来有很多新技术，但C++仍然是目前工业软件企业与注重性能场景的主流软件开发技术。但与若干年前不同，C++在近年间不断推陈出新了许多紧跟时代的新特性，到C++17甚至C++20的新特性已经被工业界所广泛使用。"
  - title: "大型项目管理与合作开发"
    subTitle: "你是否想过把声明分离到头文件中？或是把一部分函数或类定义放在另一个cpp文件中？如何把他们编译成可运行的程序？是否知道软件安装目录中的dll文件是什么作用？如何使用Git等工具管理代码与合作开发？这些问题在这部分都会有答案。"
  - title: "第三方库开发示例"
    subTitle: "从工程角度上说，使用纯C++进行开发是不太现实的，单单是创建图形界面并调用渲染接口，使用纯C++标准库就做不到这一点。会讲解如何安装或从源码构建三方库并导入到项目中。项目使用到了Qt Quick、VTK、OCC这些三方库，会对这些三方库进行基础的开发讲解 "
specificationsLeft:
  - title: "现代C++开发基础"
    subTitle: "C语言开发经验能学会面向过程的编程能力，学习C++能了解面向对象的设计范式。虽然C++很多语法从C语言而来，但学习C++需要当成是一门全新的语言去学习。C++的面向对象特性和一些基础的语法特性大多是C++98版本的，2011年C++11版本的推出标志现代C++的诞生，之后相继推出了C++14、C++17、C++20、C++23等，工业界目前到C++17或C++20用的较多。"
  - title: "C++项目管理基础"
    subTitle: "编译指将某个代码文件编译成二进制文件，链接是将二进制文件合并成更大的二进制文件或可执行文件（.exe）；而构建是将从项目源文件到目标二进制文件的过程，包括了前面的过程。各个操作系统中由操作系统提供各种C++开发工具链（编译工具+项目构建工具），比如Windows中的MSVC、Linux中的GCC+Make、MacOS中的LLVM+XCode。项目构建目标除了可以生成可执行文件外，还可以生成静态库文件或动态库文件，也可以依赖现成的构建好的库文件。"
  - title: "使用CMake管理C++项目"
    subTitle: "CMake是一个跨平台的项目管理工具，可以识别各种系统的编译工具，利用现有的项目构建工具实现项目构建。入门CMake需要了解CMake项目从配置到构建项目、安装项目、测试项目、打包项目大概流程。CMake也有现代CMake项目的区分，现代在最大的特征是使用预设（presets）接入IDE的工作流、使用目标（target）和目标命令来配置构建目标和依赖、配置安装命令用于项目的安装和打包。"
  - title: "项目合作开发工作流"
    subTitle: "使用Git借助代码托管平台如Github、Gitee等，可以实现代码合作开发。Git是代码版本管理工具，不仅可以做到和远程仓库代码同步，如果没有合作开发需求还可以在本地进行版本管理，便于版本回溯和隔离更改。开发工作流除了代码同步工具，还涉及分支管理和仓库Issue等托管仓库相关管理，和具体的提交代码流程。"
specificationsRight:
  - title: "Qt Quick"
    subTitle: "Qt Quick与Qt Widgets相对，后者是经典的Qt，是目前C++跨平台应用软件开发的事实标准；前者是Qt新兴的编程框架，使用声明语言Qml做界面布局、使用js作为脚本语言组织功能，且较容易支持C++做拓展。"
  - title: "The Visualization Toolkit"
    subTitle: "VTK是可视化框架，对底层图d形API包括OpenGL、WebGL做了面向对象的封装，可以很方便的对物体创建渲染窗口。除了面向对象的渲染外，还提供了预置的模型处理工具库，支持对模型进行定制化处理以支持更灵活的渲染。"
  - title: "OpenCASCADE Technology"
    subTitle: "OCC是CAD的三维几何引擎，支持对CAD模型的文件IO、支持对模型各个级别元素的表示与点击拾取，预置了各种CAD常用的几何修改操作，如倒角和布尔运算等。目前在项目中使用OCC是为了CAD模型的导入与表示。"
blueprints:
  first: "@/images/blueprint-1.avif"
  second: "@/images/blueprint-2.avif"
---
