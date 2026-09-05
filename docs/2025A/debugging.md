# 2025 秋 · 如何教学调试技巧

- 介绍更系统的调试方法：**Delta Debugging**（一种自动化简化测试用例的方法，出自 Why Programs Fail Chapter 5）与 **Statistical Debugging**。
- 材料：Debugging book、fuzzing book、David J. Agans《Debugging: The 9 Indispensable Rules》、G. Aaron Wilkin《Debugging From Art to Science》（Rose-Hulman，课程文档在 GitHub 上公开）。
- 讨论问题（后面是之前学期的内容，供参考）：
  - 学生使用大语言模型完成作业，对代码调试带来哪些影响？会产生哪些新的结合大语言模型的调试技巧？（例如先让大模型给同学解释一下代码）
  - 我们自己是从哪里学会调试的？分布式/并行系统难以重现且涉随机；图形学以输出调试为主；硬件调试主要看波形（进阶做法如与模拟 ISA 对拍）；最小化代码 / minimal working example 复现；有人当了助教才自学 gdb。
  - 同学们学会调试的难点在哪？需要注重实践而非理论讲授；有些同学不喜欢写代码，就没有强烈动力学会调试。也有助教 "去年我来过这个主题，今年给课程加了个用 vscode 调试的文档，在 PA 文档里开了一节"。
- 通过作业/文档教会调试的尝试：Stanford CS107e LAB3、清华网络原理调试文档、计算机组成原理错误速查清单、数据结构 "调试辅导课"（前半学期每周一次 20-30 分钟：调试概论、代码风格、测例构造; 因为线下答疑难以克服代码难读、工具不熟、调出后没建立信心等问题）。
- 一些段子（Dijkstra、Kernighan 关于调试的名言，"JYY 绿导师原谅你了"）; 以及 *Debugging From Art to Science* 论文列出的教学目标与如何实现（例如描述缺陷如何产生、按可复现/确定性对 bug 分类、阅读和理解大型项目、用科学方法搜索 bug、高效利用调试工具、用因果规则修复并证明修复、设计技术/模式以简化未来调试; 并做 bug logbook）。
- 内容与 [2025 春 调试讲](../2025S/debugging.md)、[2024 秋 调试讲](../2024A/debugging.md) 同源，可互相参照。

[⇦ 返回 2025 秋主页](index.md)
