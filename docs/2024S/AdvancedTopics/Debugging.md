# 如何教会同学调试

The instruction of debugging

讨论问题：

- 我之前帮同学调出来的一个 bug 是什么，是怎样调出来的？(Share one interesting bug you found recently)
- 我们自己是从哪里学会调试的？(How did TAs themselves learn debugging?)
- 同学们学会调试的难点在哪？ (Why students struggle at debugging?)

相关论文：

Competitive Debugging: Toward Contests Promoting Debugging as a Skill  (Onward! 2022)
RoboBUG: A Serious Game for Learning Debugging Techniques (ICER 17)

## 可以教给学生的调试方法/工具

- Delta Debugging —— 一种自动化简化测试用例的调试方法 (Why Programs Fail Chapter 5)。
- Statistical Debugging (Debugging book)。
- 参考材料: *Debugging: The 9 Indispensable Rules for Finding Even the Most Elusive Hardware and Software Problems* (David J. Agans)、*Debugging From Art to Science* (G. Aaron Wilkin, Rose-Hulman, 课程文档开源)、[Debugging book](https://www.debuggingbook.org/)、[Fuzzing book](https://www.fuzzingbook.org/)。

## 教会调试的难点

- 调试是像扳手一样需要花时间学、花时间用的工具, 回报在未来, 同学很难意识到其必要性。
- 学会调试的常见难点: 不善于使用搜索工具; 缺乏 "找中间状态和预期状态是否一致" 的思路 (gdb/printf/dump 本质相同); 本科课程少系统教调试; 写码欲望下降、潜意识想要现成框架, 而从零写框架正是珍贵的调试学习机会。
- 需注重实践而非理论讲授; 有些同学不喜欢写码, 就缺乏动力学会调试。

## 通过作业/文档教会调试的尝试

- Stanford CS107e LAB3、清华网络原理调试文档、计算机组成原理错误速查清单。
- 数据结构 "调试辅导课": 前半学期每周一次 20-30 分钟, 分调试概论、代码风格、测例构造三节 (因线下答疑难以克服代码难读、工具不熟、调出后没建立信心等问题)。
- 有助教给课程加了用 vscode 调试的文档, 在 PA 文档里开一节。

(上述内容在 2024 秋、2025 春、2025 秋的调试主题研讨中被进一步展开, 也讨论了 LLM 对调试教学的影响。)
