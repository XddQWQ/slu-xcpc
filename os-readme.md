# OS-README

## 写在前面

这个文档是xdd与2023年给他的学弟学妹们写的，他憧憬着可以和学弟学妹们在系统能力大赛中能够大展身手，可惜事与愿违，他们在那次比赛中并没有取得什么好成绩，不过xdd还是认为他的文档写的蛮好的。

但是这都2024了，xdd也应该与时俱进，更新一下他的文档了，以下是原文档内容：

## 旧时代的船

首先官网有很多文档都是蛮好的[全国大学生计算机系统能力大赛 (educg.net)](https://os.educg.net/#/index)（往届的培训会、优秀作品、技术报告）

然后就是徐迪迪的推荐：

* linux的使用以及一些基础命令\
  这里推荐ubuntu 20.04LTS （其实wsl挺爽的  Windows subsystem for Linux 你的Windows为何不能是一台Linux捏😜）\
  推荐资料：
  * Unix\&Linux大学教程（ Harley Hahn's Guide to UNIX and Linux）
  * 【Linux入门教程 \[第五期“一生一芯”计划 - P2]】 [https://www.bilibili.com/video/BV1Ud4y137kN/?share\_source=copy\_web\&vd\_source=04a216ab1eb7bfebc10736bf69fc01a5](https://www.bilibili.com/video/BV1Ud4y137kN/?share\_source=copy\_web\&vd\_source=04a216ab1eb7bfebc10736bf69fc01a5)
  * GNU/Linux入门教程 [https://ysyx.oscc.cc/docs/ics-pa/linux.html](https://ysyx.oscc.cc/docs/ics-pa/linux.html)

RTFM && STFW: read the friendly manual  && read the friendly web 学会读手册、学会在互联网上搜索自己需要的资料，say no to baidu，使用Google && bing，科学上网\
ps. 还有jyy老师的os课！！！\
【操作系统概述 (操作系统的历史；学习建议) \[南京大学2023操作系统-P1] (蒋炎岩)】 [https://www.bilibili.com/video/BV1Xx4y1V7JZ/?share\_source=copy\_web\&vd\_source=04a216ab1eb7bfebc10736bf69fc01a5](https://www.bilibili.com/video/BV1Xx4y1V7JZ/?share\_source=copy\_web\&vd\_source=04a216ab1eb7bfebc10736bf69fc01a5)

* RISC- V

中文手册、官方手册、大赛官网也有一些risc-v的资料

[RISC-V Manual (oscc.cc)](https://jemu.oscc.cc/)

* GNU工具链like gcc 、gdb、make

这里引用一段话：

> IDE，或者“集成开发工具”，会使你变笨。如果你想要成为一个好的程序员，它会是最糟糕的工具，因为它隐藏了背后的细节，你的工作是弄清楚背后发生了什么。如果你试着完成一些事情，并且所在平台根据特定的IDE而设计，它们非常有用，但是对于学习C编程（以及许多其它语言），它们没有意义。

* qemu

大赛第一阶段区域赛用的qemu模拟器，决赛才用开发板（一提这个好像还得看一下交叉编译来着= =不过话又说回来，这不比智能车燃多了！！！）

ps.  可以试着用qemu跑一下xv6感受一下

* 汇编
* git

协作开发 && 代码托管

而且材料提交也要用这个嗷

* markdown？？？

> Markdown的语法十分简单，常用的标记符号不超过十个，用于日常写作记录绰绰有余，不到半小时就能完全掌握。就是这十个不到的标记符号，却能让人**优雅地沉浸式记录，专注内容而不是纠结排版**，达到「心中无尘，码字入神」的境界。

写文档很舒服

主要是徐迪迪很喜欢markdown，他已经疯狂到做ppt都要用markdown的地步惹Σ(っ °Д °;)っ

不过也确实，做ppt何必非得用power point (￣▽￣)\*

[Markdown 官方教程](https://markdown.com.cn/)

以上，就这，一起变强！！！



## 新时代

随着比赛的不断发展，大家也越来越卷了，最开始的几届比赛中用c语言实现的内核还是大多数，最近两年的获奖作品里面就很少看到c的影子了，取而代之的是近年来的新贵，以系统安全为噱头的程序设计语言-RUST，并且清华大学也是每年都举办操作系统训练营，来推动这一块儿的交流。



然后捏，本来这里应该像上述文档一样，罗列一些作为新手需要关注的技术栈，但是这里是新时代了，相较之下xdd有更好的的推荐：

* 清华大学主办的OS训练营：[https://opencamp.cn/](https://opencamp.cn/)
* r-core 手册：[https://rcore-os.cn/rCore-Tutorial-Book-v3/index.html](https://rcore-os.cn/rCore-Tutorial-Book-v3/index.html)

值得一提的是，os训练营的第二阶段的主要任务就是r-core的实验，而第三阶段也是根据需求不同安排不同的项目，比如系统能力大赛相关的项目，对驱动感兴趣的项目，etc...

所以相较于自己摸索，参加os训练营不失为一个更好的选择



> 这里小小的吐槽一下
>
>
>
> 算了，下次再吐槽吧

TO BE CONTINUE！！！
