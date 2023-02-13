# 写在开头
   
大伙可以通过此项目来深入了解操作系统层次方面的细节，这为从事系统底层工作有一定的帮助

---
   
可以通过branch转换分支，我每一章都新建一个分支，方便大家不同阶段来查看，就比如当前是main分支，我们只需要点击切换即可
![](http://imgsrc.baidu.com/super/pic/item/3ac79f3df8dcd1003d523ae5378b4710b8122f2c.jpg)

当然大伙也可以fork了本项目然后到本地用git进行切换

---
   
在这里给出分支及其对应进度，这样大伙可以按照自身情况来查看源码
> 0x00 环境准备 ，对应分支名-master
   
> 0x01 BIOS以及简易MBR ， 对应分支名-BIOS

> 0x02 改进版MBR，利用显卡实现输出，对应分支名-UMBR

> 0x03 加强版MBR，通过读取硬盘来加载Loader，对应分支名-UUMBR

> 0x04 进入保护模式，介绍了一些基础知识和如何进入的方法，对应分支名-Protector

> 0x05 检测内存容量，介绍如何检测的三种方法，简单易懂，对应分支名-Checkout

> 0x06 实现内存分页机制，这里是二级页表，实现了页目录表和页表，对应分支名-Page

> 0x07 载入初始内核，详细介绍特权级知识， 对应分支名-Kernel

> 0x08 实现自己的打印函数，可支持字符串，字符，整数，对应分支名-Print

> 0x09 实现了传说中的中断，重点介绍了时钟中断，对应分支名-Interrupt

> 0x0A 初步实现了内存管理机制，代码较多，对应分支名-Memory

> 0x0B 实现了内核多线程机制，对应分支名为-Thread

> 0x0C 实现了包含锁的输入输出机制，对应分支名为-IOsys

> 0x0D 实现了用户进程及其调度，对应分支名为-User

> 0x0E 实现了多种系统调用，对应分支名为-Syscall

> 0x0F 实现了硬盘分区并得到关键数据，对应分支名为-Disk

> 0x10 将文件系统初始化，并且挂载了分区，对应分支名为-FileSys_0

> 0x11 实现了几个基本的文件操作函数，对应分支名-FileSys_1
