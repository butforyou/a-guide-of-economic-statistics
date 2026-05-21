# Python 编程基础

编程能力是经济统计专业学生的必备技能。无论是数据处理、模型实现，还是后续的机器学习与深度学习，都离不开扎实的编程基础。是ai选择了python，不是python选择了ai。CS61A 是公认的计算机科学入门最佳课程之一，它以 Python 为主要教学语言，核心训练的是**计算思维与抽象能力**——这对统计建模尤为重要。(当然我真的很不确定未来深入编程基础语法是否是必要的，但是在当下 还是一项必要的选择)

这一面课是我自学的梦开始的地方，在此前我从未想过一门公开课能有多大的力量，只有在最后一章结束时的热泪盈眶足以回答。

---

## CS61A：伯克利计算机程序的构造与解释

CS61A（全称：*Structure and Interpretation of Computer Programs*）是加州大学伯克利分校计算机科学专业的入门神课，脱胎于经典的 SICP 教材。课程以 **Python** 为主要语言，同时涵盖 Scheme（Lisp 方言）和 SQL，从函数式编程、面向对象编程到解释器实现，构建起完整的计算思维框架。

### 课程信息

| 项目 | 详情 |
|------|------|
| **课程名称** | CS61A: Structure and Interpretation of Computer Programs |
| **授课教师** | John DeNero 等 |
| **难度** | ⭐⭐ |
| **预计学时** | 约 50 小时 |
| **先修要求** | 无（零基础可学，但建议有一点点编程概念会更容易上手） |
| **课程官网** | [cs61a.org](https://cs61a.org/) |
| **在线教材** | [composingprograms.com](https://www.composingprograms.com/) |

### 课程大纲

1. 函数与函数式编程：高阶函数、递归、Lambda
2. 数据抽象：序列、树、可变数据
3. 面向对象编程：类、继承、多态
4. 解释器：Scheme 语法与解释器实现
5. 声明式编程：SQL 数据库查询
6. 算法复杂度分析基础

课程包含丰富的配套资源：**Lecture（视频）、Slides（课件）、Textbook（教材）、Lab（实验）、Homework（作业）、Projects（4个课程项目）**。

### 视频资源

| 版本 | 链接 | 说明 |
|------|------|------|
| **2024 精翻·中文语音（完结）** | [B站 BV16J4m1u7xP](https://www.bilibili.com/video/BV16J4m1u7xP/) | 最新版本，中文语音精翻，适合国内学习者 |
| **2024 精翻双语·英文原声** | [B站 BV1sy411z7nA](https://www.bilibili.com/video/BV1sy411z7nA/) | 中英双语字幕，保留英文原声 |
| **2021 Spring 精译** | [B站搜索](https://search.bilibili.com/all?keyword=CS61A%20Spring%202021%20%E7%B2%BE%E8%AF%91) | 中英双语字幕，John DeNero 授课 |

### 学习建议

1. **先看中文精翻建立感觉**：如果英语听力有压力，推荐先跟「2024 中文语音精翻版」
2. **一定要做 Lab 和 Homework**：光看不练等于没学。每个 Lab 都设计精巧，帮助巩固当周知识点
3. **4个Project是精华**：
    - Project 1 (Hog)：用 Python 实现一个骰子游戏，练习控制流与函数
    - Project 2 (Cats)：实现自动更正与打字速度测量，练习递归与字符串处理
    - Project 3 (Ants)：塔防游戏，练习面向对象编程
    - Project 4 (Scheme Interpreter)：**用 Python 写一个 Scheme 解释器**，这是整门课的集大成之作
4. **善用中文资源**：
    - [CS61A-CN 中文镜像站](https://github.com/ChillyHigh/CS61A-CN)：Fall 2020 官网的完整中文翻译
    - [SICP Python 中文版教材](https://bookstack.cn/read/sicp-py-zh/README.md)：composingprograms 的中文翻译
5. **在线工具**：[Python Tutor](http://pythontutor.com/composingprograms.html) 可以在线可视化代码执行过程，对理解递归和树结构非常有帮助

> 零基础的同学如果觉得 CS61A 起步偏难，可以先花一周快速过一遍哈佛 CS50 的前几讲作为预热。但 CS61A 才是真正帮你建立计算思维的课程——学完之后，Python 对你来说将不再只是一门"脚本语言"。
