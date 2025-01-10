# 计算机网络

!!! info "课程基本信息"

    - 课程名称：计算机网络
    - 课程代码：`21121340`
    - 授课老师：陆魁军、陆系群、邱劲松等

!!! info "笔记基本信息"

    内容范围根据 [Computer Networks, Global Edition, 6th edition](https://www.pearson.com/en-gb/subject-catalog/p/computer-networks-global-edition/P200000005535/9781292374017) 和陆魁军老师2024年提供的[考试范围Excel](./221009.xls)，以
    Zhang-Each（RandomStar/小角龙）[2020年的笔记](https://zhang-each.github.io/My-CS-Notebook/Networking/)
    为基本框架。
    
    笔记编写的主要原则是：面向教材，参考但不依赖王道。
    
    参考资料包括：
    
    - 陆魁军老师2024年提供的课程PPT（下称lkj PPT）
    - [陆系群老师班2024年实验文档中的术语对照表](https://zjucomp.net/docs/terms/)
    - 2025王道计算机网络考研辅导
    
    本笔记使用的模板来自[ZIJI-CS项目](https://ziji-cs.github.io/)，可以点击Home Project查看具体信息。

!!! section "编写进度"

    - [x] [Chapter 1: Introduction](./1-x.md)
    - [x] [Chapter 2: Physical Layer](./2-x.md)
    	- 待补充：2.2-2.3、2.5.2-DSL、2.9
    - [x] [Chapter 3: Data Link Layer](./3-x.md)
        - 待补充：3.5.3
    - [x] [Chapter 4: MAC Sublayer](./4-x.md)
        - 待补充：4.5.2
    - [x] [Chapter 5: Network Layer](./5-x.md)
    	- 待补充：5.4.3-5.4.5、5.7.7
    - [x] [Chapter 6: Transport Layer](./6-x.md)
        - 待补充：6.2.2
    - [x] [Chapter 7: Application Layer](./7-x.md)
        - 待补充：7.5
    - [x] [Chapter 8: Network Security](./8-x.md)
        - 待补充：8.9 及以后

!!! section "本地运行"
    - 安装 Python 环境
    - 将本项目下载或克隆到本地
    - 进入目录 `cd T-ComputerNetworks`
    - 环境建立（只需最开始运行一次）
        - 建立虚拟机 `python -m venv localvenv`
        - 安装依赖 `pip install -r requirements.txt` 
    - 启动虚拟机，根据操作系统从下面选择指令运行。
        - Windows Git Bash: `source localvenv/Scripts/activate`
        - Linux: `. localvenv/bin/activate`
    - 运行 `python -m mkdocs serve`
        - 访问 `http://localhost:8000/`

!!! section "评论区"
    暂未设置 Giscus，烦请直接在代码仓库中提 Issue 或到 CC98 的[ 这个帖子 ](https://www.cc98.org/topic/6075929)（内网打开）反馈问题。