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
    如果能顺利写完的话，可能考虑并入该项目。

!!! section "编写进度"

    - [ ] Chapter 1: Introduction 
    - [x] Chapter 2: Physical Layer
    - [x] Chapter 3: Data Link Layer
    - [x] Chapter 4: MAC Sublayer
    - [x] Chapter 5: Network Layer
    	- 待补充：
    		- 5.4.3-5.4.5
    		- 5.7.7
    - [ ] Chapter 6: Transport Layer（进行中）
    - [ ] Chapter 7: Application Layer
    - [ ] Chapter 8: Network Security

!!! section "本地运行"
    - 安装Python环境
    - 进入目录 `cd T-ComputerNetworks`
    - 环境建立（只需最开始运行一次）
        - 建立虚拟机 `python -m venv localvenv`
        - 安装依赖 `pip install -r requirements.txt` 
    - 启动虚拟机，根据操作系统从下面选择指令运行。
        - Windows Git Bash: `source localvenv/Scripts/activate`
        - Linux: `. localvenv/bin/activate`
    - 运行 `python -m mkdocs serve`
        - 访问 `http://localhost:8000/`