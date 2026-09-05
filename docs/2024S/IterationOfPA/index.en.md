# Basics: Iterating and Updating Programming Assignments

## The 10-minute lecture

by @jiegec

### 1. When does a programming assignment need iteration/update?

For example, when as a TA you hear things like:

- The assignment is so "involved"; all my time goes to it with little gain
- Starting is so hard; stuck at the first step, worried I can't do it
- Please TA, extend the deadline
- Crap assignment, posting to Moments/Zhihu
- This ancient assignment from years ago, why still assign it?
- Unrelated to the teaching content, and unrelated to the assignments before/after
- No grading standard; I don't know how much to write

Or during tutoring/grading you have thoughts like:

- This assignment is so laborious to grade; 200+ people, it'll kill me
- If I had to do this assignment, I wouldn't want to

Examples:

A course lab: the lab requires hard server setup; the lab manual mentions Windows XP. On Linux you can start the server, but it involves VMs, WSL, etc. — environment setup is too complex and unrelated to the lab itself.

Revision: provide observation results, no longer requiring environment setup or reproducing the process.

A course in some year, some lab: for the basic implementation, the doc offers four optimization paths A, B, C, D, but sets too-high performance requirements so only D can pass. A student completes A, finds performance insufficient, moves to B, again insufficient — very discouraged.

Revision: provide more hints, improve the performance requirement.

### 2. What changes and what stays

After deciding an assignment needs iteration, first think: what changes? What stays?

What stays:

Why was the assignment designed?

Data structures: the lecture covered data structures and algorithms, so the PA should implement those ideas in code, applied to specific problems.

Computer networks: students rarely handle binary data, and later labs involve much binary-data processing, so binary-data handling is split out for individual practice.

These teaching goals shouldn't change; preserve the knowledge to be taught (unless out of scope/outdated).

What can change:

- Assignment content: which parts, what requirements
- Timing: when it starts, when it ends
- Grading standard: what earns how much
- Difficulty gradient: all easy / easy to hard / all hard

### 3. How to iterate/update an assignment

After deciding what changes and what stays, start doing it!

**When**:

- Start early before the semester; at least finish before assigning.

**Focus on feedback**:

- Collect feedback promptly after assigning, remedy found problems; within the semester you can adjust later assignments based on earlier feedback.

**Coordination**:

- Communicate among TAs; don't publish half-finished work. If you must temporarily put a half-finished version on a public site, mark it clearly: TODO / draft / not final.
- Communicate across courses: avoid deadline conflicts; stagger heavy assignments.

More notes:

- Iteration needn't finish in one semester/year: it may take years, even passed TAs continuing the work.
- Manage code and docs well, organize an FAQ, ensure continuity and updatability, keep original files to avoid a "single uneditable PDF" situation.
- Use GitLab, Tsinghua Cloud Drive, Tencent Docs, questionnaires, etc.
- Have other TAs/students evaluate the assignment's difficulty; do it yourself at least once.
- Anticipate situations and responses: too hard, too easy, errors, etc.

Reference other excellent assignments for inspiration.

International:

- CSDIY.wiki
- SIGCSE Nifty Assignments
- MIT OpenCourseWare
- Public courses from Stanford/CMU/Berkeley, etc.
- Note: course names may not correspond; even translated, course positioning may differ.

Domestic examples: Tsinghua https://lab.cs.tsinghua.edu.cn/#/sypt/sywd

## Discussion topics

- What assignments have you revised in recent years? Any interesting stories behind the iteration?
- Talk about an undergraduate/graduate course you're TAing; does its assignment need change, and how?
- How to evaluate the effect after iteration? Better, worse, or mixed?
- How to iterate an assignment into a form LLMs can't do?

Some views:

Consider bringing real-world scenarios/projects into the course, or adding visualization/drawing parts.

Turning an assignment into something LLMs can't do shouldn't be about making it harder for students' sake. Rather, like how linear-algebra courses after computers and MATLAB, no longer heavily require students to do tasks that computers/MATLAB should do.
