# proj262-malloc_for_openharmony
# 在OpenHarmony轻量系统上实现内存管理，实现类似malloc，free函数

## 项目描述

内存管理是指软件运行时对计算机内存资源的管理（如分配、使用、回收）的技术。

参赛者可以在OpenHarmony轻量系统上实现自己的内存管理函数（类似malloc，free）。

## 源码

- 可以直接参考C库中malloc，free的实现
- https://gitee.com/openharmony

## 项目导师

- 连志安 [https://gitee.com/lianzhian](https://gitee.com/lianzhian)
- email [lian_zhian@runkaihong.com.cn](mailto:lian_zhian@runkaihong.com.cn)

## 难度

中等

## 文档

这里给出malloc和free函数的定义

malloc函数函数定义

其函数原型为void *malloc(unsigned int size)；其作用是在内存的动态存储区中分配一个长度为size的连续空间。 此函数的返回值是分配区域的起始地址，或者说，此函数是一个指针型函数，返回的指针指向该分配域的开头位置。

free()是C语言中释放内存空间的函数，通常与申请内存空间的函数malloc()结合使用，可以释放由malloc()、calloc()、realloc() 等函数申请的内存空间。

## License

Apache 2.0(https://www.apache.org/licenses/LICENSE-2.0.html)

## 预期目标

注意：下面的内容是建议内容，不要求必须全部完成。选择本项目的同学也可与导师联系，提出自己的新想法，如导师认可，可加入预期目标 。

在OpenHarmony轻量系统上实现类似malloc，free函数对内存进行管理

## **选择该赛题的支持**

开发套件支持：提供给参赛队伍开发套件，此开发板采用海思Hi3861芯片，它集成了 32位高能效的 RISC-V 指令集架构的 CPU，内置了 SRAM 和 Flash，可以独立运行程序，它的外设接口也比较丰富，包括：15个通用输入/输出（General Purpose Input/Output，GPIO）接口；支持7路模数转换器（Analog to Digital Converter，ADC）输入；支持6路脉宽调制（Pulse Width Modulation，PWM）输出；支持3个通用异步收发器（Universal Asynchronous Receiver & Transmitter，UART）接口；支持2个串行外设接口（Synchronous Peripheral Interface，SPI）；集成了两个内部集成电路（The Inter Integrated Circuit，I2C）接口；另外，它还具备一个内部集成电路音频（Inter-IC Sound，I2S）接口和一个安全数字输入输出（Secure Digital Input/Output，SDIO）从机接口。

技术答疑指导：针对OpenHarmony操作系统及本赛题技术要点，资深研发工程师提供专业的技术支持、指导，全程辅导技术方案的实现。

技术资料：提供相关技术资料和对应索引，指导赛题方向。
