# 如何出好编程作业

(整合 2023秋季 @jiegec 分享内容)

本章尝试回答下面几个问题:

- 学生和教师心目中好的编程作业是什么样的？
- 如何平衡作业里的挑战和支持?
- 在实际的课程中，好的编程作业是怎样设计出来的?

线下讨论时, 我们会邀请经验丰富的助教分享自己命制编程作业的一些经验教训, 并讨论一些优质的编程作业好在哪里, 例如[attack lab](./attacklab.md)

## 学生和教师眼中的“好编程作业”

之前CS TA's Weekly 尝试收集了一些符合“好编程作业”标准的作业。也可以去参考“CS自学指南”中整理的课程的作业。

讨论话题1: 讲讲你遇到过最好的编程作业是什么样的？

（备选话题: 课前完成讨论话题1的征集，选择一些案例，课上讨论话题: 拿出一个优秀编程作业的案例，请大家讨论好在哪里？）

（备选话题：低年级基础必修课、高年级专业必修课、高年级专业选修课，在编程作业设计上，可以有什么不同？）

## 平衡挑战和支持

“提升课程挑战度”是学校一直提倡的风格。我们这里认为，给学生恰当的支持，可以帮助学生克服更难的挑战。

假如说，“挑战度” 是让同学们在课程里完成的任务的难度，支持度是给同学们完成任务的帮助。那么，更高的支持度会让同学们完成任务变得更容易、挑战度下降吗?

假如说在没有任何支持的情况下，同学们可以完成难度为5的任务A，提供文档答疑等支持之后完成任务A的实际难度下降为3。

但是，如果同学们的实际能力是完成难度为5的任务，那么在提供文档答疑等支持之后，就可以让同学们完成“没有支持的情况下难度为7的任务B”, 在文档答疑让实际难度下降后，可能实际难度还是有5左右的水平。此时, 课程的挑战度、支持度都得到了提升。

我们不妨把没有任何支持的情况下，完成任务的难度称之为“原始难度”。放到课程内之后，由于时间限制、先修知识、文档答疑等因素，导致的学生在课内完成该任务的实际难度称之为“实际难度”。

可以想一想, 同样是在课程中完成一件实际难度为5的事情, 可能有下列三种情况：

- 完成一件原始难度为3，但由于课程文档混乱、要求不明确，而实际难度增加到5的事情
- 完成一件原始难度为5，课程文档质量差强人意，相当于没有支持，而实际难度也差不多为5的事情
- 完成一件原始难度为7，通过较完善的文档和少量的助教答疑，而实际难度下降到5的事情
- 完成一件原始难度为9，通过整个课程非常合理的设计引导、非常完善的文档和非常充分的答疑，而实际难度下降到5的事情。

假设这里不同原始难度的事情都是实际科研工作中有用的任务，只是难度层次不同，那么请问，哪一种情况，对学生来说，会有更多的成就感、更多的收获感?

打个比方，要求学生边倒立吃面条边蒙眼写冒泡排序程序, 简单讲课然后让学生独立实现一个归并排序程序，给学生充分的文档引导让他实现一个分布式系统并行排序程序, 可能学生要用的时间差不多, 但学生在编程能力、算法知识的提升截然不同。

也可以按照挑战和支持的多少，给课程进行分类。

- 挑战很少，支持很少: 普通的水课，学不到什么东西。
- 挑战很少，支持很多: 体验较好的水课，适合混学分。
- 挑战很多，支持很少: 学生可能会认为是fly bitch、恶心人的“石头课”，也可能认为是“用心的话能学到东西”的课。
- 挑战很多，支持很多(能和挑战匹配): 学生会认为这是能学到东西、有收获的“金课”。

因此，重要的是让挑战度和支持度互相匹配。这需要持续收集学生的反馈，了解学生主观感受到的挑战程度和支持程度。

在学期初想衡量作业难度是否合适，可以找人试做。但也要考虑到试做的同学助教的水平通常高于全体同学的平均水平，要在此基础上修正评估结果。

另外，也需要了解增加挑战度或支持度的各种技巧。这里尝试列出一些增加挑战度/支持度的可能思路，希望有所启发。

增加挑战度的方法思路:

- 要求完成更多的作业题目
- 选用前沿科研项目作为大作业
- 选用更复杂、更贴合实际的工程项目作为大作业
- 综合多块知识，例如涉及本课程不同章节的综合任务，或不同课程的联合实验。
- 综合理论与实践，例如给编程作业加思考题，给书面作业加编程任务。
- 将组队作业改为单人完成
- 从按绝对性能给分改为按性能排名给分
- 提升对性能指标的要求
- 不提供实验框架，要求从零实现
- 增加额外的bonus选项, 实现某功能获得加分，或完成困难版本获得加分。
- (持续补充中)

增加支持度的方法思路:

- 对一个复杂的作业任务做更多的分解
- 增加更详细的作业文档、先修知识文档、视频讲解
- 设置更多的习题课
- 增加线上、线下的完善答疑渠道、讨论平台
- 允许组队完成单人作业，或其他鼓励同学交流的方法
- 从按性能排名给分改为按绝对性能给分
- 提供实验框架或可参考的范例
- 增加简单版的题目，选做简单版可以获得略少于标准版本的分数
- 给出完成题目/步骤的参考用时，学生可判断自己是否用时过长, 需要求助
- 对大作业，增加更多的milestone，汇报作业的过程进度。
- (持续补充中)

讨论话题: 有哪些合理方法增加编程作业的挑战度/支持度？

??? note "理论探讨: 脚手架(scaffolding)与最近发展区(Zone of Proximal Development)"

    关于给学生提供支持，最著名的两个教育心理学理论是维果茨基提出的最近发展区理论和布鲁纳提出的脚手架(Scaffolding)理论。
    
    这是两个独立的理论，后来被人们联系在一起。一种通俗且流行的看法是，如果儿童能独立解决难度为A的问题，在成年人帮助下能解决难度为B的问题，那么难度A和B之间，就是儿童的最近发展区。成年人给儿童提供的帮助是“脚手架”。通过逐步减少提供的帮助，可以让儿童逐步提高到能独立解决难度为B的问题的水平。“儿童和成年人”也可以替换为“学徒和专家” “学生和老师” ”学生和助教“的关系。它可以指在教室里讲课的时候，给学生一些即兴的提示、引导。也可以指提供给学生的答疑、文档。

    Scaffolding and the zone of proximal development: A problematic relationship(2020) 这篇文章质疑了“脚手架理论”: 它可能只适合于学习目标非常明确，就是要完成某个特定任务的情况。如果我们希望学生通过完成任务锻炼独立解决问题的能力的意志，那么提供类似“脚手架”的帮助未必有好处。

    可以说，“最近发展区”和“脚手架”只是原则，建议我们既不要让学生独立完成远超他们能力的任务，也不要给学生布置过于轻松的任务。但是，具体如何找到中间的平衡点，让学生既因为适当的挑战感到兴奋，又不因为过高的难度而产生畏难情绪，同时尽可能让不同水平的学生都有这种“恰到好处”的感觉，需要我们充分了解学生，充分了解自己所教的课程。离开对学科本身和学生具体情况的了解，教育学的理论和原则并不好用。
    
    

## 好的编程作业从何而来?

大家可能听说过软件的生命周期、产品的生命周期。我们尝试把这种思维方式用在编程作业上，划分一下编程作业的生命周期。

不妨粗略划分为：初步想法 - 命题实现 - 实际使用 - 反馈迭代 四个阶段

??? note "跨界灵感: 软件生命周期"

    软件生命周期(Software Development Lifecycle) 是软件工程/产品管理中的重要概念。常见的阶段包括规划、设计、实现、测试、部署、维护。

    这些阶段连接起来就形成了不同的软件开发模式(或者软件生命周期的模型)，比如瀑布(waterfall, 循序渐进依次完成每个阶段)、迭代(首先创建一个最小的可用版本，随后在上面不断改进)、敏捷方法(将整个项目开发流程拆成若干个规模较小的sprint)等等。

### A. 初步想法

这一阶段，获得一个模糊的想法“我要出一个什么样的作业，实现什么样的目标”

之前提到的“怎样得到可行的课程改进措施”产生想法的途径，大部分也适合于编程作业初步想法的获得途径。

一些具体的场景可能是这样:

例如，从平时同学对编程作业的反馈中，发现调试是同学们消耗时间很多的环节，就可以想“能不能在学期最开始加一个作业，教同学们使用一些调试工具和方法”。

再比如, 课上同学们提到另一门课程正在“造CPU”，老师就可以设想“我们课程要不要也造点什么”。

还有可能是，前置课程/后置课程在某个知识点的讲授上有所改动，因此我们要新出用到某个知识点/没用到某个知识点的作业。

并不是每个出作业的初步想法都会真正进入到课程中，但有大量的初步想法从中筛选肯定是一件好事。为此，教学团队最好在平时做好相关想法的积累讨论，尽量不要在新学期来临想出一些新作业时，从零开始头脑风暴。可以建一个课程团队的共享文档，有什么关于教学、出作业的想法，平时就记一下。

### B. 命题实现

这一阶段需要一个可以正式发布的作业版本。细节不一定完美，之后可以继续完善。

出一份编程作业，至少需要有作业文档、实验框架和评分标准。评分标准的相关话题将在后续章节详细讨论。

有些课程还需要自动评测的OJ平台/CI平台。关于搭建和使用平台的技术细节，建议多和有类似需求的课程交流。

**作业文档**: 推荐使用流行的开源文档框架[Material for MkDocs](https://squidfunk.github.io/mkdocs-material/), 可以方便地部署在自己的服务器或者github pages上, 这样也方便让课程获得更大的影响力。相比列出“写文档的原则”，这里建议直接参考优秀的课程作业文档。这里列出两个推荐: 

- [rust小学期](https://lab.cs.tsinghua.edu.cn/rust/) 
- [rcore tutorial](https://rcore-os.cn/rCore-Tutorial-Book-v3/chapter0/0intro.html)。
- (后续可以增加)

文档中最好给出明确的作业要求。如果文档不够明确，助教就要准备好随时澄清题意。据说也有课程故意把题意写得模糊，要求同学主动询问题意，模拟现实中细化需求的过程。

(可能的讨论话题: 从优秀的作业文档我们能学到什么?)

**实验框架**:

实验框架可以避免同学们面对作业要求无从下手。如果提供实验框架，那么实验框架本身应当让学生学习到良好的代码风格和项目架构。

尽量确保实验框架在不同的开发环境下都能工作，或者告知学生搭建开发环境的方法/提供开发环境。Windows下通过WSL可以解决很多开发环境问题，但ARM指令集的MacOS容易被教学团队忽略。

也有同学认为过于完善的实验框架中, 自己不需要理解整个实验框架，只做低技术含量的代码填空，成就感不高。可以尝试出一些需要阅读实验框架的思考题。

**评分标准**:

需要最先明确一点: 我们是否希望作业有区分度? (或者说，希望作业评分是“形成性评价”还是“终结性评价”？)

如果有期末考试，编程作业是平时作业，以学习为主, 或许可以不要让作业分数有区分度，大家完成基本要求就能得到大部分分数。

如果编程作业是期末总评占主要部分的大项目，这时就需要让作业分数有区分度。

后续章节会详细讨论作业评分查重相关话题。

??? note "理论探讨: 形成性评价和终结性评价"

    形成性评价(formative assessment) 指的是在评价的过程中学生也在学习, 例如平时的各种作业，完成作业也是学习的过程。

    终结性评价(summative assessment) 指的是评价的过程中学生没有学习(但可以促进评价前后的学习)，例如随堂小测、期末考试、期末项目。

    两种评价方式都有对应的应用场合。使用得当，两种评价方式都可以鼓励学生为获得高分而认真学习。


**其他**:

课程团队通常在假期出作业，或者至少在作业发布前出完。

“把作业按时出完”看似简单，但如果对项目管理不够上心，就很有可能出不完，所以最好留出冗余(比如把助教出完作业的ddl设置在作业发布的一周前而不是一天前）, 并经常核对出作业的进度。

如果有人力，最好能把作业审阅、试做一下。打字笔误和排版错误还好，但至少不要在作业发布之后，才发现某些要求完全无法完成。或许可以考虑面向本学期选课同学公开招募一些试做作业的志愿者。

### C. 实际使用

对应在学期中，布置编程作业、学生完成编程作业和教学团队给分的过程。

设置DDL的时候，注意避开期中、期末考试周(甚至有时要避开学生节), 避开其他课程的重大ddl。(典型: 大三专业课往往需要互相协调)

在作业布置后、作业截止前一周/前几天，助教可以在群里提醒一下。

如果同学反馈作业有题意不清、实验框架出bug等问题，需要及时跟进解决。也可以考虑将同学们的常见问题更新到一个共享文档里/合并到作业文档里。

作业的给分、反馈需要及时完成。如果拖到学期末再给出作业分数，同学们的感受会不太好。

### D. 迭代完善

对应学期结束后，总结作业可改进的地方，进一步完善的过程。

可能需要考虑：同学们的整体完成程度、作业的平均分和区分度、同学们的实际工作量等。

可参考之前“收集关于编程作业的反馈”的章节。

有条件的话，最好对每年的作业都做一定的更新/更改。



