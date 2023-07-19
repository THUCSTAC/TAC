# 学生评教与课程调研

本章尝试回答下面几个问题：

1. 学生给一些课程的评教打低分、一些课程的评教打高分，这些课程有什么不同？反映学生对课程的哪些**普遍期待**？
2. 我们如何在课程中收集反馈，以了解学生的**具体需求**？
3. 我们如何将学生的需求转换为**可行的课程改进措施**, 从而让学生实际学到更多、课程评教分数更好？


**讲义内容不是线下研讨的主要内容，只是线下研讨的辅助材料/自学材料。**

线下研讨将主要围绕这四个讨论话题展开:

1. 同样是反馈/改进的机制，学生教评和论文审稿有什么不同？
2. 同学们倾向于给一节什么样的课打最高/最低的教评分数？反映了对课程的哪些期待？
3. 如何制作一份课前调研问卷？
4. 那些”失败“的课程改进措施，为什么让我们有挫败感？

## A. 学生教评高/低的课程有什么特征？

您或许认为，关于“哪些因素会让评教分数变高”, 教育学领域一定有丰富的研究供我们参考。但事实是，研究尽管丰富，却不一定能供我们参考。

这要从研究的出发点说起。教育学领域，很多关于评教分数影响因素的研究，是为了制定更规范严谨的、真实反映教学质量的评教方案，而不是为了帮教师找到改善评教分数的方法。

例如这篇研究综述，IDEA Paper No. 50: Student ratings of teaching: A summary of research and literature.(2010), 列举了很多影响/不影响学生评教分数的变量: 课程是否必修可能影响评教（选修课里对内容本身感兴趣的同学比较多）, 课程的学科领域可能影响评教（文科课程普遍比理工科评教高），但咱也决定不了自己的课是必修/选修，更不可能把课当成文科来讲（尽管有的学生吐槽有的计算机课上得像文科，但这并不是一句表扬）。

我们引用一下这篇综述的结尾部分：
!!! quote "From IDEA Paper No. 50: Student ratings of teaching: A summary of research and literature.(2010)"
    This paper summarizes the general conclusions from the research on student ratings. Whether these conclusions hold true for all contexts is an empirical question. If an institution has reason to believe that these conclusions do not apply, key players should gather local data to address the issue. In the absence of evidence to the contrary, however, the following general conclusions can be used as a guide (Marsh, 2007, p. 372):
    
    SETs [student evaluations of teaching effectiveness] are multidimensional, reliable and stable, primarily a function of the instructor who teaches a course rather than the course that is taught, relatively valid against a variety of indicators of effective teaching, relatively unaffected by a variety of potential biases, and are seen to be useful by faculty, students, and administrators.

    翻译（仅供参考）: 本文总结了学生评教相关的研究结论。这些结论是否普遍适用，是一个实证研究问题。如果某所大学感觉某个结论在那里不适用，管事的人应该收集自己学校的数据来做一些检验。但是，如果拿不出相反的证据，那么下列说法通常总是成立:

    学生评教分数是多维的、可靠的、稳定的，主要受到教课程的老师影响，而不是受到课程的影响。和其他关于教学效果的评价方式交叉分析时，学生评教都是相对有效的。和一些可能的扰动变量交叉分析时，学生评教都是相对不受影响的。在教师、学生和教学管理人员眼中，学生评教都是有用的。

大概就是说，我们知道学生评教总体上客观反映了教学质量，统计学上，学生通常总是对的。 如果感觉学校的评教制度有问题，就请在学校收集具体的数据做实证研究。

也有一些研究关注了“教师做哪些事情能改善评教分数”，但具体参考价值也一般。

例如这篇研究，McGowan, W. R., & Graham, C. R. (2009). Factors contributing to improved teaching performance. Innovative Higher Education, 34(3), 161-171， 调研了教评分数连续几年有所提升的教师，询问他们采取了哪些改进教学的措施。主要是这三类措施：

1. 让学生的学习更加active和practical! 比如让学生在课上动手实操、小组讨论等等。 
2. 增加各种形式的师生互动! 和学生在课上课下多做交流。
3. 设立清晰的学习产出(Learning Outcomes)、围绕学习目标打造课程，并给学生提出较高的期望。

这些方向看起来都没问题。但是，具体要怎样做？动手实操和小组讨论会不会导致课程讲不完？所有学生都喜欢师生互动吗？学习产出到底是啥？

关于学习产出，确实有一个叫做Outcome-Based Education的教育名词，简称OBE。大概原理是，我首先想清楚，这门课能够给学生带来哪几项提升，然后把这门课的所有环节（上课、作业、考试）都围绕着让学生获得这些提升、测量学生是否获得了这些提升来设计。感兴趣的当然可以把自己的课这么梳理一遍，或许有助于上课、作业、考试之间的联系更加紧密。但这似乎也不足以让教师们打消对教评的忧虑, 毕竟，怎么知道现在的学生吃不吃这一套？怎么知道学生会因为做哪些事情而打更好的教评？

看来，我们需要针对我们系的学生，做一些调研，看他们是怎么想的。把已有的关于学生教评的研究看做一个LLM，我们现在就要用本地的数据做fine-tune。

（如果有更有针对性的、关于学生教评的研究，欢迎提供给我们）

（我们实际收集了一些访谈数据，不公开，仅在线下研讨时用于讨论）

??? note "理论研讨: 教学目标与Outcome Based Education"

    一些经典的课程设计理论认为“教学目标”是一切教学设计的出发点，没有清晰的教学目标就没有成功的教学。教师发展中心的“青年教师教学能力进阶项目”有一部分是讲“教学目标的选择和提炼”。 学生对“作业和课堂联系不紧密” “平时作业和考试联系不紧密“的感受，也可以理解为”作业和课堂未能体现出围绕同一个教学目标的清晰联系。“

    “学习产出”和“教学目标”略有不同。关于”学习产出",您可能听说过工程教育专业认证的三大基本理念：成果导向理念、学生中心理念、持续改进理念，相关文献[1,2,3]。

    提出Outcome Based Education这个名词的Williams G Spady，认为 Outcome-based education (OBE) means clearly focusing and organizing everything in an educational system around what is essential for all students to be able to do successfully at the end of their learning experiences. [4]
    
    可以认为，对计算机系来说，Outcome是培养方案里的人才培养目标。对课程来说，Outcome是教学大纲里的教学目标，但是需要把“本课程讲授这些知识”的句式改写为“上课后，学生将能掌握这些知识、具备这些能力”的句式。
    
    像ACM制定的Computing Curricula CC2020中的“胜任力”，也可以认为是计算机专业需要的学习产出(Learning Outcomes).[5] 有些地方认为learning outcome和competency可以互换使用。[6]

    参考文献:
    
    1. 解析工程教育专业认证的成果导向理念. 李志义.中国高等教育,2014
    2. 解析工程教育专业认证的学生中心理念. 李志义.中国高等教育,2014
    3. 解析工程教育专业认证的持续改进理念. 李志义.中国高等教育,2015
    4. Outcome Based Education, William G Spady: https://files.eric.ed.gov/fulltext/ED380910.pdf
    5. 张铭,陈娟.ACM/IEEE CC2020胜任力模型对中国计算机教育发展的影响[J].计算机教育,2023(04):3-8+14.DOI:10.16512/j.cnki.jsjjy.2023.04.019.
    6. https://cset.mnsu.edu/departments/computer-information-science/se/


我们真正想知道的信息是，如果咱们系的学生给一些课程的评教打低分、一些课程的评教打高分，这些课程具体有什么不同？

这样，我们就能找出课程中哪些feature会带来更高的评教分数，然后尝试把这些feature添加到课程中。但这个过程并不简单，有几个问题要解决。

### 问题1: 学生给出的理由，有些和教学质量有关，有些和学生个人偏见有关。

教师需要区分“学生个人偏见导致学习体验不好”和“课程有待完善导致学习体验不好”两种情况。具体来说，如果把“学生个人偏见”当成”课程质量不足“做优化，只会改善极少数学生的体验，大多数学生的体验甚至有可能下降。毕竟教师时间精力有限，课程建设的精力都用在少部分人身上，就减少了改善大多数人学习体验的精力。对于某些极端的学生意见，沉默的大多数很可能都在他的对立面。

一个例子是“给分好坏”: 

假设课程A给30%的人4.0, 课程B给40%的人4.0，有些人在课程A、B的排名类似，但课程A中没有拿到4.0，课程B拿到4.0, 于是吐槽课程A给分不好，那么他是否具有代表性？

把4.0的比例从30%调到40%，对原先前30%的人是否有好处？似乎没有，他们只会感到自己的成绩含金量下降了。后60%的人呢？怎么也拿不到4.0, 本来就认下这个分数了。

还有很多人，在课程A和课程B的排名有很大的不同，他们的感受会更加复杂。可能有人在课程A排第50%，课程B排第35%，他觉得课程A给分不好，但即使课程A给分和课程B一样，他还是得不到课程A的4.0，还是会觉得课程A给分不好。

如此看来，在等级制下，调节“给分好坏”，基本上只会影响“边界值处对绩点敏感的学生“的评教心态。绝大多数学生并不会仅仅因为”给分好”就给课程好评。相反，如果给分过于宽松，大部分认真学习的同学都会发现身边有不认真上课的同学也拿到4.0，从而对课程产生一定的负面情绪。

退一万步讲，如果给分好坏真的显著影响学生教评，不出几年就会收敛到老师们给分都好到不能再好。到时候同学们还是只能根据实际教学质量决定教评。

!!! note "补充"

    比起单纯的给分好坏, 同学们更重视成绩评价的公平性、合理性。我们依然可以思考用更加合理的成绩评价方式帮助同学们学得更好。之后我们会有章节讨论这部分内容。
    
    这里只是说，在整体给分机制不变的前提下，简单“向上调分”对评教分数的正面影响有限。

### 问题2: 学生给出的理由即使看上去有普遍性，也不能直接得出解决方案。

一些学生反馈“课上讲得太快 来不及消化吸收”，这很可能有普遍性。但讲慢一点是解决方案吗？很可能会讲不完，而且也会有学生觉得讲得太慢。

如果学生真正的问题其实是”课堂上来不及消化吸收“，那么我们能不能采取一些措施，帮助学生在课下消化吸收？例如加入预习环节，开设习题课梳理课上讲过的内容，鼓励同学们在课程群里就课堂上没听懂的问题提问。这里又涉及到很多具体的问题：如何鼓励学生预习？要布置预习作业/编写预习学案吗？谁来开设习题课，助教人手不足怎么办？课程群里提问没人回答怎么办？...... 我们会在之后的几章里对一些问题做讨论。

另外，学生具体是哪些知识点来不及消化吸收？如果我们发现很多学生课上没听懂的地方都相似，或许可以考虑课上给这部分更多的时间。当然，这需要更加具体的调研。

如果学生消化吸收的困难是因为某个前置知识点，教师以为在之前的课上学过，但其实学生没学过/都忘了，那么是否需要提供相关文档/在课上回顾一下？

更多可能的原因: 会不会是因为PPT上的图不够清楚或者字号太小？学生忙着做笔记没听老师讲？学生在课上边做作业边听课？学生在前几节课上有一个概念理解错误？国际生因为语言导致理解速度慢? 昨晚学生刚刚熬夜赶ddl导致早八的课上没有精神？

甚至，课上讲的东西真的需要都消化吸收吗？例如，在课上讲了一些前沿性、介绍性的东西，学生本来就没必要理解吃透，是否要给学生说明这部分仅作为了解，不需要完全搞懂？

具体解决这些问题，需要我们在课程中对学生有更加具体的了解，也就是说，需要一系列具体的调研来了解学生的需求，获得更及时的反馈。

??? note "跨界灵感: 在课程中缩短反馈周期/采样周期"

    在自动控制领域中，反馈(feedback)指的是将系统输出信号反馈到输入端，用输入信号和输出信号的函数对系统进行控制，力图减少现实输出信号和理想输出信号之间的偏差。

    在生物学中，人体通过感知周围环境的温度、湿度等，通过激素分泌、神经调节等手段保持体内的稳态，是一种反馈调节机制。

    在自动驾驶中，车辆时刻感知周围的车道环境，随时做出车辆速度、方向的调整，也是一种反馈机制。
    
    网络的负载均衡算法也用到了反馈。每过一段时间，就获取当前网络状态，调整流量分配的方式。

    通过教学评估、课程调研来调节课程安排、教学方法，也是一种反馈机制。

    生物学的人体稳态调节、自动驾驶的车辆控制，都可以看作连续时间系统，时时刻刻需要对当前状态进行采样，进行调节。

    而网络的负载均衡算法、课程通过教学评估来反馈，可以看作离散时间系统，每隔一段时间，完成一次采样，做一些调整。

    对于离散时间系统，“采样周期”高度影响其反馈控制的稳定性。粗略来说，采样周期越短，离散系统的控制性能越接近连续时间系统，稳定性越好，能更快收敛到稳态。采样周期越长，系统越倾向于不稳定。一个直观的理解是，一个赛车手，挑战每隔 X 秒钟才看一眼路、握一下方向盘调整方向，那么X就是一种采样周期/反馈周期，X越大，操控赛车越难。

    对于课程教学这样的复杂系统，自动控制原理并不总能套用。反馈采样的方式复杂多样，且总需要付出一定的成本。同学们愿意用在完成作业、填写问卷、接受访谈上的精力是有限的。老师助教用来出问卷、分析数据、调整课程的精力也是有限的。
    
    一个简单想法是，学校的学生教评采样周期长达一学期/一年，导致教学质量的改善有所延迟，可以尝试在学期中使用一些低成本、短反馈周期的方法，来提升课程的质量。当然，这需要老师助教付出额外的精力，设计合适的低成本反馈方案（不过度打扰学生），并认真思考反馈数据的含义、做出适当的调整。比如每节课后给少量同学(<10名)通过邮件发送简短问卷寻求他们的反馈，或者课前把课件发给少量同学(<10名)询问他们预习课件的难点，对课程教学做出对应调整。如果学生知道自己的反馈会影响自己这个学期的学习，可能会更加积极填写反馈。（学期结束后的反馈只能造福学弟学妹）

    不过，如果反馈调整周期过短，学生会不会无所适从呢？或许要权衡一下，学生适应教学风格也需要时间，不能老是变来变去。

??? note "跨界灵感：用户、需求与产品"

    产品经理都听过这样一句话：”听用户的，但不要照着做”。
    
    福特说，我造出汽车之前，人们只想要更快的马车。

    乔布斯说，消费者并不知道自己需要什么，直到我们拿出自己的产品，他们就发现，这是我要的东西。

    或许我们也需要“听学生的，但不要照着做”，未必像乔布斯那么偏执，但至少可以像福特一样，从”想要更快的马车“，分析出”想要更快的交通方式“这一本质需求，然后采取用户没有设想过的方式来满足他的本质需求。

（线下研讨时，会有两个讨论话题：同样是反馈/改进的机制，学生教评和论文审稿有什么不同？根据访谈材料，同学们会给一节什么样的课打最高/最低的教评分数？）

## B. 如何收集课程反馈，了解学生的具体需求？

### 收集和使用课程反馈的原则

反馈收集相关(问卷):

- 实名匿名均可，但“看似匿名、后续被实名”是一定要避免的。无论实名还是匿名，都需要合法合规保护学生的个人信息。
- 问卷的问题要减少引导性，让学生汇报更接近“客观事实”的东西，而不是做主观判断。例如，让学生估计完成作业用的小时数，而不是让学生回答作业负担是否过重。
- 只收集实际影响教学行为的反馈。如果一个问题的回答并不影响之后的课程教学，那就删掉这一题。
- 减轻学生填问卷的思考负担。例如能做成选择就不要填空，让学生估计完成作业的小时数，可以给出0到3、3到6、6到9小时的选项，而不是让学生填写一个具体数字。
- 可以找两三个学生试答问卷，看看学生是否理解问题的本意、填答是否容易，从而对问卷做一点修改。

反馈收集相关(非问卷形式):

- 考虑只回收教学团队能分析得了的数据量。例如，每周课前让十六分之一的同学填写预习学案，多了改不过来。
- 利用作业环节做自然的反馈，减轻学生负担。学生通过作业就把学习情况反馈给了老师。也可以在实验报告里请学生写写对作业的看法。
- 如果觉得长一些的文字反馈有用，可以列出一些问题，形成访谈提纲，用微信/邮件发给一些同学，或者线下聊一聊。
- 和多名同学们做午餐会、下午茶等交流的时候，也可以提前整理一些问题，方便同学们展开思路。缺点是会限制发散性。(可尝试搜索: 焦点小组)
- 对一些较大的改动，可以采取“测试”的方式。例如新的大作业，在假期或前半学期找同学试做。

反馈分析和使用相关：

- 注意学生所说和所做未必一致。作业环节如果有一些行为数据，可以仔细分析一下。
- 如果有可能，通过不同的反馈渠道对一些想法进行交叉验证。
- 如果问卷回收率不高，可以对不填写问卷的同学私聊联系（需要实名回收）。或者忽略不填写问卷的同学，因为他们主动放弃了让教学团队了解自己想法的权利。
- 努力让学生意识到，自己的反馈得到重视、对课程教学有所影响。但不一定占用课堂时间去讲，发公告就足够了。学生也会意识到潜移默化的教学改进。
- 教师需要判断，某个学生写的一段反馈，是个别的还是普遍的。数学证明里有孤证不立，现实社会里有“沉默的大多数”。（例如匿名社区的反馈常常是个别的）
- 接上条，如果有可能，对于个别的、实名的反馈做个别的回应。不要对个别的反馈做公开回应，这浪费了大多数人的时间。

课程团队管理/合作相关：

- 注重数据的保存和维护。不要因为助教人员变换而丢失往年数据。这样可以比较不同学期的反馈内容变化。
- 确保课程团队对于反馈数据的收集、解读和使用能达成共识。教师有时需要拍板。
- 可以积极利用外部资源，例如教师发展中心提供[中期学生反馈服务](https://www.cfd.tsinghua.edu.cn/fwxm/jszx/zqxsfk.htm), 或者和系课程调研委员会联系。

- 持续补充......
### 了解学生背景信息

在开展课程调研前，首先要对学生的背景信息有所了解（或有所假设）, 这不限于上面提到的“对课程质量的整体要求“。

- 同学们想在计算机系成为什么样的人？
- 同学们将来想深造和直接工作的比例如何？
- 同学们最想找到什么样的工作？对就业有什么想法？今年就业形势怎么样？
- 同学们对计算机领域的哪些细分方向更感兴趣？
- 同学们当前的整体课业压力如何?

这些问题, 对一门课程是否受欢迎, 会带来一定的影响。

例如方向A相关的必修课，对于想做方向B的同学，就可能感到“用不上”而打出低分。这时，如果你是这门必修课的教师，且了解到这一点，就可以尝试给同学们介绍未来方向A和方向B交叉研究的前景、以及方向B的高水平研究中方向A的知识可以发挥的作用。甚至可以设计一些与方向B交叉融合的讲座、作业环节。

如果整体课业压力已经偏大，那么课程在增加作业挑战度的时候，就要慎之又慎。

如果有一些你认为重要的信息实在无法从其他渠道获得，那么可以尝试把相关问题加到自己的课前问卷里。但也有很多信息已经被其他渠道调研过:

1. 校系团委、学生会、系课程调研委员会，都可能开展一些基础调研，可以向他们的相关负责人联系，获得一些数据/报告。
2. 通过社交媒体、私下聊天等方式和学生交流，对了解学生的精神面貌也有帮助，但要注意：乐于和教师交流的学生，不一定能代表其他的学生。
3. 也可以和辅导员等学生工作负责人交流，了解学生的普遍状态。
4. 教师之间讨论、教师和助教讨论，都可以获得一些关于当下学生的认知。但助教比课上的学生高出三四个年级，已经有可能和学生出现代沟，要小心这一点。

最终，你可能会获得一些“学生画像”（Personas），类似于“产品画像”。最好的状态是，当教学团队准备采取一些课程改进措施的时候，通过脑海中（或者写在文档里的）“学生画像”，你能对学生将来实际的反应预测个八九不离十。经验丰富的优秀教师通常拥有这个能力。

### 收集关于课堂教学 / 编程作业的具体反馈

**关于课堂教学**

课堂氛围、雨课堂答题都是在课堂上可以及时获得的反馈。课后也可以通过一些方式了解同学们对课堂的感受。

我们甚至可以在课前获得关于课堂教学的反馈：如果将课件（或单独编写预习学案）提前发放给部分学生，请他们反馈课件/学案的重难点，就可以在课上突出这些重点。

课程群的讨论和提问、同学对助教的线上线下提问，甚至作业的完成情况，都可以反映课堂教学的效果。

例如，作业中关于某个知识点的错误率很高，就要回顾课堂上是否没有把这个知识点讲清楚/讲透。

助教听课也是一种可能的反馈手段，但需要助教投入较多的时间，因此需要教学团队的权衡。

获得反馈之后，是否要在课堂上重复讲同学们理解困难的重难点？还是发一些文档？还是请助教安排习题课？这些都看情况而定。

如果能在助教精力允许的情况下每周安排习题课进行梳理，那么效果将是最好的。

（关于课堂教学、习题课的细致讨论将在之后章节进行）

**关于编程作业**

如果使用OJ、gitlab等平台来收取编程作业，那么就可以自然从平台获得大量数据。但这些数据只有经过分析之后才具有反馈的价值。有时间可以考虑写一些脚本，建立自动的数据分析管线。或者有可能的话，跟平台方联系，增加便于数据分析的特性，实现更高水平的教育数字化。

同学对作业提交的具体代码、实验报告也是价值很高的反馈：通过这些反馈，我们了解同学们对作业的完成情况，从而了解关于作业合理性的反馈。也可以考虑在实验报告里直接让同学写一些对这份作业的感受和意见，不少同学是愿意写的。

如果课程具有多个编程作业/编程作业有多个部分，不妨用这样的方式在问卷里问一些问题：“您最喜欢/讨厌的题目/作业模块是什么/哪些？为什么？”。当然，别忘了把各种作业题目/模块列成选项让同学们直接选。也可以问问“您花费最多时间的题目/作业模块/步骤”是什么。

关于作业本身出现错漏，表达不严谨、甚至难以完成的反馈，需要得到最高优先级的处理。甚至可以考虑给提供这类反馈的同学加分。

助教对编程作业开展答疑时，可以获得很多高质量的反馈，适当注意整理一下，会对改善作业质量有帮助。

关于作业延期的反馈也很常见。常常有同学私聊请求作业延期，有时候教师也会发布问卷询问大家是否延期。需要尽量避免的情况是“在最后一刻延期/在截止之后延期”：想一想，为了赶上作业deadline, 你已经放弃了一场考试的复习/错过了一场约会/熬夜到凌晨三点/代码写得很潦草，第二天醒来发现老师在群里说作业延期一个星期......这个时候你肯定有冲动给这门课的教评打最低分。如果要延期，至少让大多数同学有机会通过重新安排时间从延期中获益。

（关于设计编程作业与答疑的细致讨论将在之后章节进行）

### 收集分析课程反馈时，需要避开的误区/雷区

- 将学生当作“填数据的工具人”。我们希望学生通过提供反馈共同参与到课程建设/学习体验优化中。
- 如果反馈渠道本身不是教学活动，那么不要用分数作为激励。（或者说，不应当让学生通过填问卷获得平时分。）
- 问卷过长。可能会导致问卷回收量极小。建议通过试做，估计一个问卷用时写在问卷简介里，最好不超过10分钟。
- 问卷只包含大量的选择题/判断题/量表题。除非是安排答疑时间这种事务性的调研，建议至少包含一道开放性的文本题目, 学生可以讲讲自己的想法。
- 问题引导性过强。例如不要问“你是否觉得课堂讲授过快”，而要问“你在课上消化吸收到什么程度、哪些因素导致当堂吸收不好（选择或填空题）"
- 过于在乎极端数据。在大班课程中，统计学上必然出现离谱的反馈。如果不能过滤掉，就会导致反馈数据被污染。
- 学生不知道反馈渠道的存在。可以在第一节课梳理学生能提供反馈的相关渠道，或在课间/课后提醒学生填写问卷。
- 在和学生直接沟通时（一对一访谈、午餐会等），给学生过多的压力。尽量维持良好的讨论氛围，即使学生发言偏激，课程团队也要保持风度。
- 持续补充......
  
（线下研讨时，会有一个讨论话题：如何编写一份课前调研问卷？）

可参考: [How to increase course evaluation response rates: 10 do’s and 3 don’ts](https://www.uhd.edu/provost/teaching-learning-excellence/instructional-excellence/Documents/How%20to%20increase%20course%20evaluation%20response%20rates.pdf)

## C. 怎样得到可行的课程改进措施？/ 判断课程改进措施是否可行？

判断一项课程改进措施是否可行、得到一项可行的课程改进措施，是两个不同的问题，有一点NP=P？的意思。

首先我们看看课程改进最早的想法可能从哪里来(列表持续更新):

1. 从上述课程反馈中总结出来。对应学生反馈的课程痛点进行优化，或者对学生提出来的改进意见进行细化落地。学生课程调研委员会也可能会提供一些课改想法。
2. 国家/学校政策导向。例如近年一些老师会参与教育部推动的“课程思政”改革或学校推动的“提升课程挑战度”改革。
3. 与其他课程改革的协同。例如某门课程的改革需要一些先修知识，可以去联络先修课程的教师共同改革。
4. 和他人交流时产生想法。例如在教学工作坊和其他教师交流教学的想法、和企业界交流对学生能力的需求等，或者教师和助教讨论获得一些想法。
5. 从计算机专业科研中迁移过来。例如在科研中发现一块很有用的知识/一些有用的工具，想办法加入到课程中来。
6. 从教育研究中迁移过来。例如读了SIGCSE/ICER/《计算机教育》某篇文章觉得不错，把做法拿到课程中来。或者读教育专著产生新想法。
7. 模仿其他课程。例如把自己的课程和stanford、MIT的同类课程比较一下，容易发现不少做法不同的地方，从中就可以找到改进课程的思路。
8. 迭代完善。例如对上学期增加的新内容/新作业认为不够完善需要打磨。
9. 涌现。了解足够多的课程教学做法、学生反馈信息、和课程教学有关无关的知识后，花费一些时间琢磨怎么改进教学后，脑子里突然冒出来的想法。如同LLM的涌现一样不可预测。

有时候，课程改进的初步想法不是太少，而是太多。但并不是每一个想法都能变成可行的课程改进措施/方案。即使所有想法都可行，也很少有资源在一个学期内将所有想法全部圆满实现，往往只能选择最重要、最可行的几项来开展。

初步看似可行的课程改进措施/方案，在实际实施时又会遇到很多意想不到的情况。

对一个初步的课程改进想法或课程改进方案，想要提升其可行性，就需要尽可能地多做调研、讨论、收集反馈。但也没时间无止境地做可行性分析，有时只能在实际的课程里先一点点做起来。

无论如何，对于自己拿不准的课程剧烈改动，不要一下子就在课程里完全实施，尽量找一些逐步将其纳入课程的方法，时刻注意学生对这些变化的反馈。

或者说，要设想最坏的场景：在最糟糕的情况下，这个课程改进方案会导致什么后果? 有什么应对方法吗？ 在后果基本可控的情况下，也可以大胆一些。

（线下研讨时，会有一个讨论话题：那些”失败“的课程改进措施，为什么让我们有挫败感？应该如何避免？到时候会有几个“有挫败感”的课程改进案例。）