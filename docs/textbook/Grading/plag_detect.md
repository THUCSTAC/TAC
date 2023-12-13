# 代码查重细节

by @HarryChen

查重不是不相信同学，而是帮助建立和维护学术诚信意识的必要手段。

案例:

- 一位同学在做实验的时候，自己编写的代码没有通过所有的测试，在 DDL 后将往年同学公布在 GitHub 的代码原样复制到自己的仓库中提交。
- DDL 前，A 同学给 B 同学讲解了代码，但 B 同学依然没有搞懂，就从 A 同学处要了一份代码，结果 B 同学直接把 A 同学的代码提交上去。
- A 同学对着代码，给同学讲解了作业，并进行了录像，之后 B 同学对着录像把 A 同学的代码摘抄下来提交。
- 两位同学用 GitHub Copilot 生成了一样的代码。

**一些学术诚信政策: **

MIT's Policy on Collaboration and Sharing

https://web.mit.edu/6.031/www/fa20/general/collaboration.html

MIT Writing Code Hankbook 和杰哥翻译的中文版：

https://integrity.mit.edu/handbook/writing-code

https://jia.je/programming/2022/07/12/writing-code-cn/

要求同学在提交所有作业时填写 honor code, 在后续查重等环节可作为依据，减少不必要的争执

查重工具:

- [Stanford MOSS](https://theory.stanford.edu/~aiken/moss/)：使用广泛，但依赖远端，且不支持新语言（如 Rust）
- [mossum](https://github.com/hjalti/mossum) 可辅助分析 MOSS 结果：
- [Study in Scarlet](https://github.com/a-nikolaev/study-in-scarlet)：Ruby 脚本，可产生分析图
- [JPlag](https://github.com/jplag/JPlag)：Java 编写，但算法有时结果比较奇怪
- [JiePlag](https://github.com/thu-cs-lab/jieplag)：@jiegec 重写，MIT 开源
    * 类 MOSS 体验，支持更多语言
    * C / C++ / CUDA / Rust / Verilog / SystemVerilog / Python
    * Rust 编写，支持本地/服务器运行，在计算机系私有部署
    * 已在多门课程中测试，欢迎联系杰哥试用！

一种可能的查重流程:

- 使用上述的软件运行自动化分析；
- 阅读分析结果，找到可疑的重复代码对，如：
    * 大篇幅重复（如只有变量名或顺序不同）
    * 核心控制流相同（大致看代码形状）
    * 可疑的其他迹象（均使用了小众的语法结构、奇怪的空白字符等）
- 邀约同学面谈，询问作业完成过程（并与 honor code 交叉对比），有必要时可要求给出部分代码的解释；
    * 不应给学生太大的压力，但必须严肃告知可能的后果；
- 教学团队基于主观陈述和客观事实完成最后的判断，核心准则是代码的相似程度是否超出了（不交流具体代码的）正常范围。

查重与AI:

AI 可以生成多种版本基本 work 的代码，助教很难穷尽作为检索来源；
 
 - 系统类课程（大作业）受到的影响目前显著比编程/算法课程小；
 - 只要学生不承认，就无法获得有力证据。
 - 除了技术之外，也需要更多的手段，引导鼓励学生独立完成。

用大模型来查重? 结果很可能有差错。谨慎替代人工！