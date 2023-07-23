# 作业评分查重与考试

本章尝试回答下面几个问题:

- 怎样设计合理的作业评分, 促进学生有效学习?
- 作业评分中，怎样增加更多的评语反馈，让学生针对提高?
- 怎样做好代码查重, 鼓励学生独立完成？
- 怎样出一套区分度良好的考试题？

## 通过作业评分促进学生有效学习

一个问题: 是否要将详细的评分标准公开?

模糊的评分标准会让学生焦虑, 担心自己能否拿到满意的分数, 因此学生往往希望教师公布评分标准。

但教师也会担心公开评分标准后，同学们会按照“拿到满意分数的最短路径”来安排学习，导致学习投入变少。

如果评分标准足够聪明, 让学生对着标准“拟合”也是一种有效的学习, 那么公开评分标准的好处就会更多。

折中的方法可能是，公开/明确拿到基本合格分数的评分标准(例如拿到作业的60%到80%分数的标准), 然后剩余部分的评分标准只给出大致的描述。

也有课程采用实时排行榜/相对性能排名作为分数的一部分，但满足基本性能要求就能得到大部分分数。

讨论话题: 

- 学生谈论的“内卷”具体是什么现象？
- 怎样的评价方式会让学生感到“鼓励内卷”？
- “内卷”现象之外，学生面临的“真问题”可能是什么，我们能为之做些什么？

一些可供讨论的文章: 

- [《绩点为王：中国顶尖高校年轻人的囚徒困境》 三联生活周刊](https://www.sohu.com/a/419676894_105067)
- [《“内卷”是教育发挥筛选功能的成本》，中国科学报，李锋亮](https://news.sciencenet.cn/htmlnews/2021/5/458355.shtm)
- [浅谈清华学风、课程内卷、特奖与其他](https://mp.weixin.qq.com/s/QZHvnRcICYpq8411PxJ78g)
- [TOP2计算机系，已经开始怀疑自己完全不适合相应领域的学习，未来的路应该如何走？](https://www.zhihu.com/question/349438744)

??? note "理论探讨: 教育目标分类"

    教育学家布鲁姆认为教学目标有不同的层次，提出了布鲁姆教育目标分类法(Bloom's Taxonomy), 包括记忆、理解、应用、分析、融会贯通等层次。其实这些具体的层次并不重要，层次的顺序也不固定，具体的课程中可能会体现不同的层次。重要的是意识到教学/评价存在不同的层次，记住知识点、理解知识点、灵活运用知识点、超越具体知识点的思维方式等。有人认为在作业、考试的考核中，应当尽量追求更高的认知层次，比如减少背诵填空题目的含量。
    
    有人提出了“计算机的布鲁姆分类法”，认为计算机课程中，认知层次应当划分为“记忆“ “理解” “应用” “分析” “评判” “创造”这些层次。

    除了布鲁姆的教育目标分类法，还有很多可以分类教育目标的方法，比如 SOLO taxonomy(Structure of observed learning outcome), 更关注学生先掌握单个知识点、再掌握多个孤立的知识点，到掌握多个知识点之间的联系，再将知识点融会贯通的过程。

    如果在出作业题/考试题的时候，能考察到学生将不同知识点联系起来、共同运用的能力，或许就能得到更综合、更有挑战性的题目。

    参考文献: 
    
    Errol Thompson, Andrew Luxton-Reilly, Jacqueline L. Whalley, Minjie Hu, and Phil Robbins. 2008. Bloom's taxonomy for CS assessment. In Proceedings of the tenth conference on Australasian computing education - Volume 78 (ACE '08).

    Biggs, J., & Collis, K. (1982). Evaluating the quality of learning: The SOLO taxonomy. New York: Academic Press.

## 给学生提供具体的作业反馈

中学阶段，学生都习惯于从自己的错题中学习，从做错的题目中获取关于自身学习状况的反馈。但大学作业中，并不总能对学生做错的题目给予详细的反馈，例如给实验报告打分时助教常常没有时间给具体的评语。为了反复使用作业题目，通常也不方便提供参考答案。学生通常只有单独询问助教才能获得详细的作业反馈。

一种可能的思路是使用作业评分量表(rubric)，来让判作业和给反馈变得更快。这大概类似于“40秒判完一篇高考作文”。

搜索“高考作文评分标准表“，就能发现很多表格, 基本上是把作文拆分成“是否切题” “语言流畅” “内容充实“等小项，然后列出每个小项不同等级的标准。

对应的，批改书面作业/实验报告，也可以尝试列一个量表，分解出 “时间复杂度分析是否正确” “思路是否清晰” “最终结果是否正确” 等小项来评分。

借助这种量表，也可以实现评语的自动化生成: 每一小项的不同等级对应不同的评语，助教只要把不同小项的等级打出来，就可以通过脚本自动化生成评语，结合网络学堂批量录入评语成绩的功能即可。另外，如果可行，也可以考虑把量表公开出来供学生参考学习。

讨论话题: 还有哪些方式能提高给作业具体反馈的效率、控制助教需要的工作量? 自动化工具? 

## 鼓励独立完成: 不只是代码查重

曾经，严格的代码查重足以威慑大部分学生不进行抄袭。但近年来，Copilot、ChatGPT等能理解和生成代码的大语言模型，给维护良好学风带来了更大的挑战。我们需要更多考虑从作业设计中，就鼓励学生独立完成。

Simon. 2017. Designing Programming Assignments to Reduce the Likelihood of Cheating. (ACE '17). 提到了一些减少作业抄袭的方式: 

- 从一个简单的任务出发，在不同角度增加复杂度使得学生无法使用网络上现成的的代码；
- 提供不同难度的作业/拆分不同的步骤，学生可以做基础版本的题目/基础的步骤来获得大部分分数；
- 每个学期对作业的细节进行微调；
- 准备较多的不同测例，避免测例泄漏带来的影响

Frank Vahid, Kelly Downey, Ashley Pang, and Chelsea Gordon. 2023. Impact of Several Low-Effort Cheating-Reduction Methods in a CS1 Class. (SIGCSE 2023) 也描述了一些方法:

- 在课上拿出20-30分钟讨论学术诚信
- 要求学生完成一个学术诚信自测，明确哪些事情可以做/哪些事情不能
- 期中时向学生强调学术诚信，强调被发现学术不端的后果
- 在课上给学生展示代码查重的工具和流程(减少学生侥幸心理)
- 允许学生(在ddl之后、公布查重结果之前)主动撤回提交, 因为学生可能在ddl前不够理智而提交抄袭的代码。
- 完善给学生提供的帮助, 向学生强调他们可以获得帮助的合理途径(习题课、答疑等), 避免学生单纯因为做不出作业而选择抄袭。

讨论话题: 如何应对Copilot、ChatGPT等大语言模型在编程作业、实验报告中的使用？

相关文章:

https://www.oreilly.com/radar/teaching-programming-in-the-age-of-chatgpt/ 


[From "Ban It Till We Understand It" to "Resistance is Futile": How University Programming Instructors Plan to Adapt as More Students Use AI Code Generation and Explanation Tools such as ChatGPT and GitHub Copilot. Sam Lau and Philip J. Guo. ACM Conference on International Computing Education Research (ICER), 2023.](https://pg.ucsd.edu/publications/cs-instructors-adapting-to-chatgpt-copilot-ai-tools_ICER-2023.pdf)

## 考试出题

考试出题是一个较为敏感的话题。时间有限, 我们这里主要讨论关于“往年题”的问题: 怎样避免期末考试变成“谁找到往年题谁就分数高”的信息战？

参考: 

[如何看待清华大学期末考试变成信息战？](https://www.zhihu.com/question/265816912)

[大学期末考试题库“共享”，糊弄了谁？](http://news.cyol.com/gb/articles/2022-01/05/content_NRWLXH8WV.html)

还有一个看似比较娱乐, 但可以深入讨论的话题: 如何设计课程可以减少学生的“考试周破防”现象?(一个广泛传播的视频)