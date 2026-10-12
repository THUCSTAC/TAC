# 2026 Autumn · New-TA Peer Sharing

The first training of the semester for new TAs, a panel with experienced TAs from various courses, online/offline combined, with recordings provided for makeup study. This session focused on **the impact of AI on course teaching and how to respond**, **AI applications in TA work**, **AI-oriented adjustments to course content and assessment**, **equity of access to AI models**, and the operation experience of the fully AI-taught course **"Toward General AI"**.

## Session flow

- Introduce the panel guests
- New TAs scan the **sign-in questionnaire**
- During the session, scan the **"real-time question questionnaire"**, which syncs to an online spreadsheet; the host periodically switches to the sheet and invites the sharing TAs to answer briefly
- **"Toward General AI" sharing**
- A makeup-study notice for absent TAs will be posted in the TA group

## Panel guests

- **Chen Jiajie** (host): Computer Culture Basics and other courses
- **Fan Ruwen**: Fundamentals of Programming, Compilers
- **Xie Ziyi**: Cryptography, Introduction to Theoretical Computer Science
- **Zhang Yingqi**: Computer Organization, Formal Languages and Automata
- **Huang Yuxiang**: TA for "Toward General AI" (taught by Prof. Liu Zhiyuan)

## Discussion topics (mainly guest sharing + real-time questions)

- **What impact has AI had on the teaching of the course you TA for?**
- **If students submit a large amount of AI-generated, low-quality questions or content, how would you handle it?**
- **Have you actively applied AI in your TA work? If so, how exactly?**
- **Has the course you TA for made adjustments for AI? If so, what adjustments, and how well did they work?**
- **What have you learned from students in the course of being a TA?**

## Session notes

### 1. The impact of AI on course teaching

- **Impact on programming assignments**: on programming assignments with automated tests, AI often passes everything in one go; in programming courses, as long as you ask the AI not to write comments, TAs mostly can't tell whether a student used AI.
- **Impact on math assignments**: math courses are hit too, but students have to understand AI output to some extent to copy it, so copying everything stands out; yet when the writing is flawless, TAs are in a bind.
- **"Perfect assignments, failing exams"**: AI makes assignments generally of very high quality, while exams drop sharply, a break in the individual learning curve, since assignments can be done casually and crammed at the end.
- **Unable to assess real mastery**: as long as students can finish assignments without understanding the course material, TAs and instructors can't judge their real mastery. There is no good solution yet.

### 2. How to respond to AI-generated low-quality content

- **Have students find the AI's problems themselves**: when AI hallucinations are severe, TAs have students read through the AI-written code and find the problems themselves, rather than telling them where the bug is (or letting AI do it).
- **Grade math wrong answers as wrong + add quizzes/handwriting**: a wrong answer is simply marked wrong; TAs also suggest instructors raise the proportion of quizzes or require handwritten work, to examine the real thinking process.
- **Regulate the AI-usage report**: the Fundamentals of Programming course once required a report stating how much AI was used. Later they found that without limits, students pasted entire AI chat logs, which increased grading workload; so it was changed to "just explain where AI was used in algorithm design or debugging," and it was made clear that **using AI does not lead to a deduction**, because TAs care more about what the student doesn't understand.
- **Reintroduce subjective / "white-box" points**: previously only objective points (pass the tests = full marks) existed, so there was no way to deduct for AI ghost-writing. Now subjective points (called "white-box points" in the data structures course) are used again to target AI slop. The cost is more TA workload. Example: in the summer session, students used AI to write an agent; one student pasted the requirements to AI and submitted as-is, sending fewer than 10 messages over the whole session; this is corrected for fairness via the submitted AI collaboration session records plus subjective points.

### 3. AI applications in TA work

- **Automated collection / organization of assignments**: previously TAs wrote scripts to crawl students' git repos, test on a test machine, pull reports from repos and package them for grading; now you drop the link to AI, generate a script, and run it, greatly reducing work outside the course content.
- **AI-assisted plagiarism detection**: use AI to directly find highly overlapping reports or code, then have TAs judge manually whether plagiarism exists, lowering the cost of manual comparison. This works especially well with models like GPT6 and Opus5.5 that can directly process long texts and many files.
- **Using AI to deal with AI / generating reference solutions**: AI is very good at high-volume work or fairly standard writing; for published reference solutions, generate with AI and then edit.
- **Course platform construction**: for the Formal Languages and Automata course website, a simulator covering all computation models was built; the Computer Organization platform added online Vivado usage and a course knowledge-base Q&A. Such "software engineering" tasks are well suited to AI scaffolding that TAs then adjust, much faster than looking up system commands by hand.
- **AI-assisted preliminary grading**: write a pipeline to do a preliminary analysis of student code and find obvious problems (e.g. no framework refactoring, very poor code, poorly done git); humans then adjust on top of the AI score. Cost is low, on the order of tens of yuan of DeepSeek per semester.
- **Less tutoring load**: even with many office-hour slots, students may not come because they have AI, greatly reducing TA workload.

### 4. Adjustments courses made for AI

- **Add closed-book / restrict strong models**: Formal Languages and Automata made no special adjustment; Computer Organization plans to add closed-book, or open-book-only content, to assess whether students can complete course tasks without strong AI.
- **"Judging mastery" matters more than "restricting AI"**: rather than restricting AI use, think about how to set course topics and assessment so students absorb knowledge faster and do more real mental work.
- **Raising difficulty is not a good approach**: the first reaction is often "make it harder," but students can still solve it with AI, which only raises the bar for students who don't use AI.
- **Use prompts to guide the AI's path**: it was once proposed to add `CLAUDE.md` / `AGENTS.md` to assignments to hint the AI to proceed step by step, exposing the trade-offs along the implementation path to students (who could also just ignore it); it was rejected by other TAs as too much work.
- **Course content shifting toward AI**: Computer Culture Basics began as "computer literacy" (Word/Excel/PPT/Windows), and now adds a lot of AI content (image/video/music generation, and simple vibe coding), emphasizing human agency; a new "Advanced AI Programming" course (Prof. Han, weeks 5–12) is a purely AI-programming course re-examining software engineering in the AI era. Fundamentals of Programming hasn't changed content yet, but everyone is thinking about how.
- **Assessment shifting toward presentations**: gradually move part of the assessment from objective assignments to presentations; in the summer session and other courses, presentation segments were added back, requiring each person to present for a few minutes with students and the instructor grading together, so students put their names behind their AI work and are more willing to polish it, making it less sloppy.

### 5. Equity of access to AI models

- **Make assignments doable with free models**: the compilers theory course aims to keep difficulty within reach of free market AI (a TA used the free GLM-4.6-Flash plan); students without accounts can contact TAs to learn how to apply and use it.
- **Lower the handwriting bar**: the discrete math course at Wuqiong College requires handwritten assignments but encourages omitting steps, requiring only that key parts taught in class be written clearly; the point is "can you judge whether the AI is correct?"
- **Fallback small model**: it was confirmed that models from over half a year ago (e.g. GPT-5.3-Codex-Spark) can already solve the assignments; the lab deployed a small Qwen model on GPUs for students as a fallback.
- **Provide basic compute and cultivate cost awareness**: the Rust summer session encourages heavy AI code-writing and provides university compute vouchers (1,000 yuan of API credit), the GLM Coding Plan, Meituan LongCat tokens, etc., guaranteeing basic use. Students are also asked to tally their AI spending at each stage (not affecting grades) to build cost awareness. With the 4.0 rate already above 50%, the marginal benefit is small, so "guaranteeing everyone can use the basic version is enough."

### 6. What we learned from students

- **Handy computer tips**: typing `cmd` directly in the Windows address bar opens a terminal in the current folder; GitHub's official `gh` tool is handy for opening/pulling PRs and for interacting with AI.
- **Beginners' "genuine confusion"**: students are genuinely confused about new knowledge, which often points to deeper issues in the discipline; they also more easily spot unclear spots in course documentation that need strengthening.
- **Surprises from sticklers**: some students seriously read papers and propose theorems no one has seen, or new proof methods; in the cryptography course a student implemented a cryptography protocol themselves in Minecraft and attached screenshots. Assignments done seriously and with human effort really stand out.
- **A reserve force**: thoughtful students are a valuable source of future TAs or even teachers; the teaching team needs a steady intake of new blood.

### 7. Sharing on the "Toward General AI" course (Huang Yuxiang)

> This course is taught by Prof. Liu Zhiyuan; in this sharing, TA Huang Yuxiang introduced the scale, system, assignments and operation experience of this fully AI-taught course.

#### 1. Course overview

- **History**: not new this semester; it has run for about one to two years, formally credit-bearing for three semesters since Spring 2025; from 2026 Prof. Liu decided to run it in both spring and autumn.
- **Enrollment scale**: 157 in the first year → nearly 700 in the second semester → nearly 1,700 this semester, showing a scaling law.
- **TA staffing**: TAs dropped from 4 to 3 (a 25% decrease), with each TA facing over 500 students on average.
- **Positioning**: a general-education course in the science group, one credit, pass/fail; the philosophy is "All about AI, nothing about CS": no programming is required or taught, no computer systems or networks, only basic AI philosophy (e.g. scaling law, unified encoding, test-time scaling, RSI).
- **Grade composition**: 40% online lectures (MAIC) + 20% small assignments + 30% large assignment + 10% offline participation; this semester, with nearly 1,700 students, offline participation couldn't be arranged, so the 10% was split between the small and large assignments.

#### 2. Fully AI-taught: the MAIC system

- An agent system jointly developed by the lab and the school of education, achieving an effect like "online-course generation": the human instructor only uploads slides, and the system automatically generates the lecture script and the AI teacher's voice (which sounds very much like Prof. Liu himself, though both script and voice are AI-generated).
- When updating materials each year, only the slides need changing, with no need to re-record the instructor, greatly reducing repeated preparation; future plans include "prepare a whole course in one sentence."

#### 3. Assignment design and assessment reform

- **Problems with the old assignments**: previously one small reflection question per lecture + a 1,500-word final paper. Though the course is strongly pro-AI, the assignments were not AI-native at all; students wrote the papers with AI, with no value for critical thinking; with 1,600 students and 3 TAs, each TA had to grade 3,500 short papers per semester, only possible with AI (LLM judge), and students got no feedback, making it impossible to assess whether they really understood.
- **This semester's reform**: small assignments raised to 25%, reduced from 6 to 3; the large assignment changed to vibe coding.
    - **Small assignment 1**: first set up an agent, then write a 10,000-word survey of LLMs (30 references), with 8 hidden references embedded and at least 2 required to be hit; students aren't told which 8, so AI must find them.
    - **Small assignment 2**: use AI to fabricate data and discuss "do multimodal models have spatial perception?"
    - **Large assignment (vibe coding)**: use one agent to write another coding agent (e.g. use WorkBuddy to imitate the DeepSeek harness), then use the self-made agent to make a mini-game, conveying the concept of "RSI (self-improvement)": at least at the harness level, AI can already iterate itself.

#### 4. Three core philosophies of assignment design

- **Feasibility**: with 1,700 students and 3 TAs, assignments must "be assignable, doable by students, and gradable by TAs." LLM judge is used; to avoid students getting no feedback, the Rubrics are public and students are explicitly told "**you can hack our Rubrics**": if someone really constructs a prompt that gets full marks on any assignment under any Rubrics, give them the points, because they clearly understand AI very well.
- **Timely feedback**: Rubrics are public, and results come out within a week of the deadline; last semester, delayed grading led to students constantly emailing to ask their scores, which was very reactive.
- **Detectability**: with a huge sample, one can estimate how many undergraduates truly integrate AI into their workflow, how many just use agents ordinarily, and how many can't use it at all.
- One hack scheme the TA team considered feasible: ① infer the LLM and harness used by the TA team from the course overview; ② do prompt hacking against that environment, constructing a prompt that gets full marks no matter what assignment or Rubrics is inserted.
- **Assignment-design advice**: ① keep pace with the times: assignments should be updated even faster than content; this year the assignments were rebuilt from scratch; ② be interesting and doable: any large assignment design must first validate the manpower, platform and grading pipeline, and accommodate humanities students (e.g. using an agent, configuring the API key).

#### 5. Large-scale course operation experience

- **Make repetitive labor reusable**: rebuild all stages (preparation, lecturing, grading and tutoring) with AI, forming a reusable methodology.
- **Scaling education and scaling LLMs are essentially the same thing; infra matters**: the Chinese-language course has about 1,200 students; the platform's auto-group-creation crashed as soon as it was clicked; WeChat groups without invites cap at 200; a 1,200-person Feishu group is equivalent to a dozen mid-size companies and requires payment; no platform can support so many people creating groups at once. In the end they had to fall back to email; and they publish information on three platforms (the course platform, MAIC, email), placing a heavy information load on students. To expand course scale in the AI era may require **rebuilding the education infrastructure from scratch** (groups, human–AI interaction, assignment and data distribution, etc.).
- **Meet students' needs**:
    - **Emotional value**: promise to reply to emails within 48 hours (the sharer himself replies to 30–40 per day), never letting a student's problem drag beyond two days.
    - **Human interaction**: students want to see the real instructor and TAs and to communicate offline, so the offline AMA lectures continue even though this year no room large enough could be found (only 6C300 on campus can hold that many); removing it from the graded components doesn't mean cancelling it.
    - **Cognitive floor**: some humanities students don't even know what an API key is, requiring very detailed illustrated explanations and a slow on-ramp; once the first agent is set up, progress is very fast. For example, a humanities student wanted Codex/Claude Code, and was taught to "first set up WorkBuddy, then have WorkBuddy configure Codex and CC for you."
    - **Feeling "caught"**: respect students' different backgrounds, regions, cultures and majors, and different levels, giving help when needed, something AI cannot do. When improving the course, the most important thing is to maintain human-to-human communication.

#### 6. Future plans

- **Practical**: enrollment next semester is expected to be flat or slightly lower (spring is usually smaller than autumn); by the same time next year it may reach 2,000–3,000, about half of undergraduates and one-fifth of all undergraduates, still supportable. University leadership hopes the course covers all students, so the platform must keep supporting **high concurrency and high availability**.
- **Aspirational**: Prof. Liu's hope is to let more people (including those originally outside AI who want to switch into it) truly apply AI to their own workflows. This has many challenges, and "taking a course is not necessarily the best way to learn"; the team continues to explore future possibilities.

## To-dos

- Arrange make-up study for TAs who missed the session, and post the related notice in the group.
- Continue exploring the possibility and solutions for extending the "Toward General AI" course nationwide and to a larger scale.

[⇦ Back to 2026 Autumn](index.md)
