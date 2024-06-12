# Python<!-- omit in toc -->

- [1. 快速开始](#1-快速开始)
  - [1.1. 定义](#11-定义)
  - [1.2. 背景](#12-背景)
  - [1.3. 应用场景](#13-应用场景)
  - [1.4. 权威资源](#14-权威资源)
  - [1.5. 尝试](#15-尝试)
- [2. 按需学习](#2-按需学习)
- [3. 系统学习](#3-系统学习)

# 1. 快速开始

## 1.1. 定义

Python 是一种开源、跨平台、[高级](https://github.com/itabbot/glossary/blob/main/glossary/高级语言与低级语言.md)、[通用](https://github.com/itabbot/glossary/blob/main/glossary/通用编程语言与领域特定语言.md)、[多范式](https://github.com/itabbot/glossary/blob/main/glossary/编程范式.md)、[解释型](https://github.com/itabbot/glossary/blob/main/glossary/解释型、编译型与即时编译型语言.md)编程语言。由于其全面的标准库，它经常被描述为“功能齐全”的语言。

Python 的设计哲学，强调代码的可读性和简洁的语法，尤其是使用空格缩进来划分代码块。相比于 C 语言或 Java，Python 让开发者能够用更少的代码表达想法。

## 1.2. 背景

Python 是由 Guido van Rossum 在荷兰科学与信息中心（CWI, Centrum Wiskunde & Informatica）工作期间发明的。他在 1989 年圣诞节期间开始构思，并在 1991 年发布了第一个公开版本。他创建 Python 的目的包括替代 ABC 语言、提高开发者生产力以及借助开源社区的力量。

版本历程概要：

-   Python 起源
    -   1989 年圣诞节期间开始构思。
    -   1991 年，Python 0.9.0 版本发布，这是 Python 的第一个公开版本。
-   Python 1.x
    -   1994 年，Python 1.0 发布，添加了 lambda、map、filter 和 reduce 等功能。
    -   1997 年，Python 1.5 发布，引入了许多改进和新功能，包括更好的模块和包支持。
-   Python 2.x
    -   2000 年，Python 2.0 发布，引入了垃圾回收机制和列表推导（list comprehensions）。Python 软件基金会 (PSF) 成立，以支持 Python 的发展。
    -   2008 年，Python 2.6 发布，为向 Python 3.x 过渡做准备，包含了一些 Python 3.x 的新特性。
-   Python 3.0
    -   2008 年，Python 3.0 发布，这一版本引入了许多重大变化，不向后兼容 Python 2.x 系列。改进了语法和标准库，以简化语言并清除历史遗留问题。Python 3.0 的发布标志着 Python 语言的一个重要里程碑。
    -   2020 年，Python 2.7 停止支持（EOL，End of Life），所有用户和开发者被鼓励迁移到 Python 3.x。

Guido van Rossum 被社区称为 Python 语言的 “终身仁慈独裁者”（Benevolent Dictator For Life, BDFL）：

-   仁慈： Guido van Rossum 以友善和负责任的方式引导社区。他注重社区的意见，并尽量做出对大多数人有利的决定。
-   独裁： 尽管 Python 是一个开源项目，并且有大量贡献者和活跃的社区，Guido van Rossum 作为语言的创始人和主要设计者，对 Python 的设计和发展有最终的决策权。
-   终身： Guido van Rossum 长期担任这个角色，直到他在 2018 年宣布从 Python 的日常管理中退休。

## 1.3. 应用场景

1.  Web 开发
    -   框架和工具： Django、Flask、Pyramid 等是流行的 Web 开发框架，提供了从小型应用到复杂企业级应用的开发支持。
    -   后端开发： 利用 Python 构建 RESTful API、Web 服务和动态网站。
    -   模板引擎： 如 Jinja2，支持动态生成 HTML。
2.  数据科学与机器学习
    -   数据分析： Pandas、NumPy 和 SciPy 等库广泛用于数据处理、分析和科学计算。
    -   数据可视化： Matplotlib、Seaborn 和 Plotly 等库用于创建各种图表和可视化。
    -   机器学习： Scikit-learn、TensorFlow、Keras 和 PyTorch 等框架用于构建和训练机器学习模型。
    -   大数据处理： 通过与 Hadoop、Spark 等大数据工具集成，实现大规模数据处理。
3.  自动化与脚本编写
    -   系统管理： 使用 Python 编写脚本来自动化系统管理任务，如文件操作、网络配置和进程管理。
    -   任务调度： 通过编写脚本实现定时任务的调度和执行，如定期备份和日志分析。
4.  网络爬虫
    -   框架和工具： Scrapy 是一个功能强大的爬虫框架，适用于复杂的抓取任务。
    -   简单抓取： Requests 库结合 BeautifulSoup、lxml 等解析库，适合快速开发简单的抓取工具。
5.  嵌入式系统
    -   MicroPython： 在微控制器上运行的 Python 解释器，用于嵌入式开发。
    -   CircuitPython： 由 Adafruit 维护的 Python 实现，专注于电子项目和教学。
6.  科学计算与工程
    -   数值计算： NumPy 和 SciPy 是科学计算和工程应用中的重要工具。
    -   高性能计算： 通过并行计算库如 Dask 和 mpi4py 实现高性能计算。
7.  游戏开发
    -   2D 游戏： Pygame 是一个简单易用的库，适合开发 2D 游戏。
    -   3D 游戏和图形： Panda3D 和 PyOpenGL 提供了 3D 游戏和图形开发的支持。
8.  教育
    -   教学语言： Python 由于其简洁的语法和强大的功能，广泛用于编程教学，适合初学者和高级编程课程。
    -   编程竞赛： Python 也常用于编程竞赛和算法竞赛，因其高效的开发速度和丰富的库支持。
9.  金融科技
    -   量化交易： Python 在金融行业中用于量化交易和分析，利用库如 NumPy、Pandas 和 scikit-learn 进行数据分析和模型构建。
    -   金融数据处理： 用于处理和分析金融数据，生成报告和预测模型。
10. 网络与通信
    -   网络编程： 使用 socket 编程、Twisted 框架和 asyncio 库进行网络通信和异步编程。
    -   网络安全： 用于编写安全工具和漏洞扫描器，如使用 Scapy 进行网络包分析和操作。
11. 物联网（IoT）
    -   设备控制： 通过 Raspberry Pi 等硬件平台，使用 Python 控制和监测 IoT 设备。
    -   数据收集和处理： 从传感器和设备中收集数据并进行处理和分析。
12. 图像处理和计算机视觉
    -   库和工具： OpenCV、Pillow 和 scikit-image 等库用于图像处理和计算机视觉任务。
    -   应用： 用于面部识别、物体检测、图像增强和视频分析。

## 1.4. 权威资源

官方： [官方网站](https://www.python.org) / [官方文档](https://www.python.org/doc) / [软件包](https://pypi.org) / [在线 shell](https://www.python.org/shell/) / [GitHub](https://github.com/python)  
教程： [官方开发者指南](https://devguide.python.org/) / [realpython](https://realpython.com/) / [programiz](https://www.programiz.com/python-programming) / [w3schools](https://www.w3schools.com/python/)  
其它： [awesome-python](https://github.com/vinta/awesome-python)

## 1.5. 尝试

# 2. 按需学习

# 3. 系统学习
