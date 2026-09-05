# Assignment Grading, Plagiarism Detection, and Exams

This chapter tries to answer:

- How to design reasonable assignment grading to promote effective learning?
- How to add more comment feedback in grading so students improve?
- How to do code plagiarism detection to encourage independent completion?
- How to write an exam with good discrimination?

(Integrating the 2023 Autumn sharing by @HarryChen.)

## Promote effective learning through grading

One question: should the detailed grading standard be published?

Vague standards make students anxious about getting a satisfying score, so students often want teachers to publish standards.

But teachers worry that after publishing, students will learn along the "shortest path to a satisfying score," reducing learning investment.

If the standard is smart enough that "fitting" it is also effective learning, then publishing has more benefit.

A middle ground: publish/state clearly the standard for a passing/basic score (e.g. the 60%-80% level), and only describe roughly the remaining part.

Some courses use real-time leaderboards / relative-performance ranking as part of the score, but meeting basic performance gets most of the points.

Discussion topics:

- What exactly is the phenomenon students call "involvement" (internal competition)?
- What evaluation style makes students feel it "encourages involvement"?
- Beyond "involvement," what might be the "real problems" students face, and what can we do?

Some articles for discussion:

- [《绩点为王：中国顶尖高校年轻人的囚徒困境》, Sanlian Life Weekly](https://www.sohu.com/a/419676894_105067)
- [《"内卷"是教育发挥筛选功能的成本》, Science Times, Li Fengliang](https://news.sciencenet.cn/htmlnews/2021/5/458355.shtm)
- [On Tsinghua's style of study, course "involution", special awards and more](https://mp.weixin.qq.com/s/QZHvnRcICYpq8411PxJ78g)
- [TOP2 CS department students beginning to doubt they're suited for the field; what path ahead?](https://www.zhihu.com/question/349438744)

??? note "Theory Discussion: Educational Goal Taxonomy"
    Bloom proposed different levels of teaching goals, the Bloom's Taxonomy — memory, comprehension, application, analysis, synthesis, etc. The specific levels and order aren't fixed; different courses may embody different levels. What matters is recognizing that teaching/evaluation has levels: remember a point, understand it, apply it flexibly, and a way of thinking beyond specific points. Some argue assignments/exams should pursue higher cognitive levels, e.g. reduce rote blank-filling.
    
    Others propose "a Bloom's taxonomy for CS": memory, understanding, application, analysis, evaluation, creation.
    
    Beyond Bloom, there are other ways, e.g. the SOLO taxonomy (Structure of Observed Learning Outcome), focusing on the progression from mastering a single point, to several isolated points, to the connections between points, to integrating them.
    
    If assignment/exam questions test the ability to connect and jointly use different knowledge points, you get more integrated, challenging questions.

    References:
    
    Errol Thompson, Andrew Luxton-Reilly, Jacqueline L. Whalley, Minjie Hu, and Phil Robbins. 2008. Bloom's taxonomy for CS assessment. ACE '08.
    
    Biggs, J., & Collis, K. (1982). Evaluating the quality of learning: The SOLO taxonomy. New York: Academic Press.

## Give students specific assignment feedback

In middle school, students learn from wrong answers, getting feedback on their learning state from errors. But in university assignments, detailed feedback on wrong questions isn't always possible — grading lab reports, TAs often lack time for specific comments. To reuse problems, it's usually inconvenient to publish reference answers. Students often can only get detailed feedback by asking TAs individually.

One idea: use a grading rubric to make grading and feedback faster. Roughly like "grading a gaokao essay in 40 seconds."

Seaching "高考作文评分标准表" reveals many tables, essentially splitting an essay into items like "on-topic," "fluent language," "substantive content," each with level descriptions.

Likewise, grading written assignments/lab reports: make a rubric splitting into items like "is the time-complexity analysis correct," "is the thinking clear," "is the final result correct."

With such a rubric, comment generation can be automated: each item's levels map to comments; the TA marks levels, and a script generates comments, combined with batch-entering grades on the platform. If feasible, consider publishing the rubric for student reference.

Discussion: what other ways to improve feedback efficiency / control TA workload? Automation?

## Encourage independent completion: not just code plagiarism detection

Strict plagiarism detection once deterred most copying. But recent LLMs that understand and generate code (Copilot, ChatGPT) pose a bigger challenge to maintaining good academic atmosphere. We need to consider encouraging independent completion from assignment design.

Simon. 2017. Designing Programming Assignments to Reduce the Likelihood of Cheating. (ACE '17) mentions reducing cheating:

- From a simple task, add complexity in different angles so students can't use ready online code.
- Provide different difficulty levels / split into steps; students can do the basic version/basic steps for most points.
- Tweak assignment details each semester.
- Prepare many test cases to avoid leakage.

Frank Vahid, Kelly Downey, Ashley Pang, and Chelsea Gordon. 2023. Impact of Several Low-Effort Cheating-Reduction Methods in a CS1 Class. (SIGCSE 2023) also describes:

- Spend 20-30 minutes in class discussing academic integrity.
- Require students to complete an academic-integrity self-check, clarifying what's allowed/not.
- At mid-term, emphasize academic integrity and consequences of misconduct.
- Show students the plagiarism-detection tool and process in class (reduce wishful thinking).
- Allow students to voluntarily withdraw a submission (after deadline, before results are released), since students may submit copied code impulsively before the deadline.
- Improve help provided; emphasize reasonable help channels (recitations, tutoring) so students don't cheat simply because they can't do the assignment.

Discussion: how to handle Copilot, ChatGPT, etc., in programming assignments and lab reports?

Related articles:

https://www.oreilly.com/radar/teaching-programming-in-the-age-of-chatgpt/

[From "Ban It Till We Understand It" to "Resistance is Futile": How University Programming Instructors Plan to Adapt as More Students Use AI Code Generation and Explanation Tools such as ChatGPT and GitHub Copilot. Sam Lau and Philip J. Guo. ACM Conference on International Computing Education Research (ICER), 2023.](https://pg.ucsd.edu/publications/cs-instructors-adapting-to-chatgpt-copilot-ai-tools_ICER-2023.pdf)

## Exam question design

Exam design is sensitive. Time-limited, we mainly discuss the "past questions" issue: how to avoid the final exam becoming an information war of "whoever finds past questions scores high"?

References:

[How to view Tsinghua final exams becoming an information war?](https://www.zhihu.com/question/265816912)

[University final-exam question banks being "shared" — who's fooled?](http://news.cyol.com/gb/articles/2022-01/05/content_NRWLXH8WV.html)

There's also a seemingly entertaining but deep topic: how to design a course to reduce students' "exam-week breakdown"? (A widely circulated video.)
