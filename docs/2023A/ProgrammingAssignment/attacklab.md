# Attack LAB 好在哪里? 

(by @jiegec)

[Attack LAB](https://csapp.cs.cmu.edu/3e/attacklab.pdf)是 CMU 15-213 计算机系统导论的一个LAB, 让学生尝试体验代码注入攻击, 广受好评。

线下交流时, 我们讨论它的优点在哪里, 如何借鉴到我们自己出的编程作业里，这里列出的部分只是引子。毕竟，只是直接照搬海外课程已有的LAB是不够的, 结合教学的需要, 我们常常会需要自己出一些作业题目。

## 学习目标清晰

 直接在编程作业一开头就交代清楚锻炼了什么能力，让学生觉得做了有分数以外的收获。

This assignment involves generating a total of five attacks on two programs having different security vulnerabilities. Outcomes you will gain from this lab include:

- You will learn different ways that attackers can exploit security vulnerabilities when programs do not
safeguard themselves well enough against buffer overflows.
- Through this, you will get a better understanding of how to write programs that are more secure, as
well as some of the features provided by compilers and operating systems to make programs less
vulnerable.
- You will gain a deeper understanding of the stack and parameter-passing mechanisms of x86-64
machine code.
- You will gain a deeper understanding of how x86-64 instructions are encoded.
- You will gain more experience with debugging tools such as GDB and OBJDUMP.


## 循序渐进

拆成多个步骤, 按步骤给分, 步骤之间要有内容的依赖和难度的递进。

| Phase | Program | Level | Method | Function | Points |
| ----- | ------- | ----- | ------ | -------- | ------ |
| 1     | CTARGET | 1     | CI     | touch1   | 10     |
| 2     | CTARGET | 2     | CI     | touch2   | 25     |
| 3     | CTARGET | 3     | CI     | touch3   | 25     |
| 4     | RTARGET | 2     | ROP    | touch2   | 35     |
| 5     | RTARGET | 3     | ROP    | touch3   | 5      |

## 文档完善

- 教学目的
- 如何上手
- 期望输入输出
- 常见问题和解决方法

## 充满乐趣

- 掌握了攻击软件的技能
- 以前觉得很困难的事情，经过学习以后，发现自己也可以完成
- 获得巨大的成就感
- 除了得高分以外，有没有其他的动力？