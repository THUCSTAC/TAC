# Student Evaluation and Course Research

This chapter tries to answer:

1. What's different between courses students rate low vs. high? What **general expectations** do students have of courses?
2. How do we use teaching goals well?
3. How do we collect feedback in a course to learn students' **specific needs**?
4. How do we turn student needs into **feasible course improvements**, so students learn more and ratings improve?

**The notes are not the main content of offline seminars, just auxiliary/self-study material.**

Offline seminars may cover:

1. What kind of course do students tend to rate highest/lowest, and what expectations does that reflect?
2. How to use / how to state course goals?
3. Principles for course research / how to make a pre-course questionnaire?
4. Concrete course-reform case discussions
5. Computing Education Research paper readings

## A. What features distinguish high- vs. low-rated courses?

You might think there's research on "factors affecting ratings." There's indeed a lot, but not much worth a teacher's attention.

This starts from the research's motivation. Much educational research on "rating factors" aims to build more rigorous, valid evaluation instruments that truly reflect teaching quality — not to help a teacher improve ratings. That is, it's to make a more credible rating benchmark, not to help a teacher profile their course. Or: student ratings are themselves for benchmarking, not profiling.

??? note "benchmark vs. profiling"
    If unfamiliar with these systems terms: a benchmark compares a set of programs to rank them; profiling analyzes one specific program to find its internal bottlenecks/strengths-weaknesses. Benchmarking tells you where your program ranks; profiling tells you what aspects to optimize. We say student ratings are closer to benchmarking than profiling — they don't give specific improvement directions, just "where does this course's teaching effect/experience rank relative to others."

For example, the review IDEA Paper No. 50: Student ratings of teaching (2010) lists variables affecting ratings: whether required (electives attract content-interested students), subject domain (humanities consistently rated higher than STEM), etc. But we can't decide whether our course is required.

A quote from that review's conclusion:
!!! quote "From IDEA Paper No. 50: Student ratings of teaching (2010)"
    This paper summarizes the general conclusions from the research on student ratings. Whether these conclusions hold true for all contexts is an empirical question. If an institution has reason to believe that these conclusions do not apply, key players should gather local data to address the issue. In the absence of evidence to the contrary, however, the following general conclusions can be used as a guide (Marsh, 2007, p. 372):
    
    SETs [student evaluations of teaching effectiveness] are multidimensional, reliable and stable, primarily a function of the instructor who teaches a course rather than the course that is taught, relatively valid against a variety of indicators of effective teaching, relatively unaffected by a variety of potential biases, and are seen to be useful by faculty, students, and administrators.

In short, ratings generally objectively reflect teaching quality; statistically students are usually right. If you feel your institution's rating system is flawed, you need local data to test it.

Some research looks at "what teachers can do to improve ratings":

McGowan, W. R., & Graham, C. R. (2009). Factors contributing to improved teaching performance. Innovative Higher Education, 34(3), 161-171 — surveyed teachers whose ratings improved over years, asking what they did. Mainly three kinds:

1. Make learning more active and practical, e.g. hands-on activities, group discussion.
2. Increase various teacher-student interactions, in and out of class.
3. Set clear learning outcomes (Learning Outcomes), build the course around goals, and set high expectations.

These directions seem fine. But concretely how? Does hands-on/group work risk not finishing the syllabus? Do all students like interaction? What exactly are learning outcomes?

On learning outcomes there's a term Outcome-Based Education (OBE). Roughly:
- Design upfront what improvements the course brings students,
- Design all course parts (lectures, assignments, exams) around achieving these improvements,
- Measure whether students gained them.

It seems for our department's students (or a particular course), we need to survey what they think. As an analogy, treat existing rating research as a big model we need to fine-tune with local data.

(If you have more targeted rating research, welcome to share.)

(We actually collected some interview data, not public, only used in offline seminars.)

What we really want to know: if our department's students rate some courses low and others high, what concretely differs?

For example, we interview many students, asking them to describe the course they rated lowest and the one they rated highest, yielding insightful answers.

Then we can find which course features lead to higher ratings, and try adding them.

For interview outlines and result discussion, see [reasons for good/bad ratings](./reasons_of_ratings.md); raw interview data is not included here.

??? note "Theory Discussion: Teaching Goals and Outcome-Based Education"
    Some classic curriculum-design theories hold that "teaching goals" are the starting point of all instructional design; without clear goals there's no successful teaching. The faculty-development center's "young-teacher teaching-ability advancement" partially covers "selecting and refining teaching goals." Students' feeling that "assignments aren't closely tied to lectures" / "assignments and exams aren't closely tied" can be read as "assignments and lectures fail to reflect a clear connection around the same teaching goal."

    "Learning outcomes" and "teaching goals" differ slightly. On outcomes, you may have heard the three ideas of engineering-education accreditation: outcome-oriented, student-centered, continuous improvement [1,2,3].

    William G. Spady, who coined OBE: "Outcome-based education (OBE) means clearly focusing and organizing everything in an educational system around what is essential for all students to be able to do successfully at the end of their learning experiences." [4]

    For a CS department, the "outcome" is the program's educational goals; for a course, the "outcome" is the syllabus's teaching goals, but reworded from "this course teaches these topics" to "after this course, students will be able to grasp these and have these abilities."

    The "competency" in ACM's Computing Curricula CC2020 can also be seen as CS learning outcomes [5]; some treat learning outcomes and competency as interchangeable [6].

    References:
    
    1-3. Li Zhiyi, analyses of engineering-education accreditation's outcome-oriented / student-centered / continuous-improvement ideas, China Higher Education, 2014-2015.
    4. Outcome Based Education, William G. Spady: https://files.eric.ed.gov/fulltext/ED380910.pdf
    5. Zhang Ming, Chen Juan. Impact of ACM/IEEE CC2020 competency model on Chinese CS education. Computer Education, 2023.
    6. https://cset.mnsu.edu/departments/computer-information-science/se/

## B. How to use teaching goals?

Whether the course's teaching goals are clear and accepted by students is a major rating factor, so it gets its own discussion.

For example, the common "lecture and assignments are disconnected" — the fix isn't "make lectures match assignments" or vice versa, but "make both match the teaching goals." If a course is hands-on and goals mainly achieved via assignments, you might design assignments around the goals first, then think about what theory students need from lectures to complete them, and arrange lectures accordingly.

A key role of teaching goals is "convincing students this course is worth it." There are many ways to state goals across levels:

- "Master x knowledge and y skills" / "grow in teamwork and problem-solving"
- "Increase interest and confidence in x field" / "afterward can take on x research and engineering roles"
- "Lay foundation for later courses x and y" / "meet department/school x goals"

Teachers' endorsed goals and students' learning goals may differ. Either persuade students to accept, or modify the goals to fit students.

In offline discussion, we'll talk about what's good about [15-213's teaching goals](./15213.md) and what it inspires.

Also, besides whole courses, per-assignment learning goals are sometimes useful. Stanford CS107 Assignment 2 states its learning goals, telling students what they'll gain:

This assignment covers topics in recent string lectures and the second lab. You will be building your skills with:
- C-strings (both raw manipulation and using string library functions)
- Viewing Unix utility programs from an internal perspective — as an implementer, not just a client
- Exposure to programmatic access of the filesystem and shell environment variables
- Thoroughly documenting your code, and learning about the importance of good documentation

Here are things to do around teaching goals:

- Try listing sub-goals for each chapter, class, and assignment.
- Review whether current course/assignment design matches the listed goals.
- For each goal, describe the degree students should reach.
- For each goal, write how to assess whether students reached it.
- Set multi-level goals for students with different pursuits.
- Invite past students to talk about "what I learned from this course."

Reference materials on teaching goals:

https://teachingcommons.stanford.edu/teaching-guides/foundations-course-design/course-planning/creating-learning-outcomes

https://evals.stanford.edu/end-term-feedback/how-write-learning-goals

https://www.cmu.edu/teaching/designteach/design/learningobjectives.html

## C. How to collect course feedback and learn students' specific needs?

### Principles for collecting and using feedback

Collection (questionnaire):

- Named or anonymous are both fine, but avoid "seemingly anonymous but later identified." Either way, protect students' personal information legally.
- Reduce leading questions; make students report closer to "objective facts," not subjective judgments. E.g. ask students to estimate hours spent, not whether the workload is too heavy.
- Only collect feedback that actually affects teaching. If a question's answer won't change teaching, drop it.
- Reduce thinking burden: prefer choices over blanks; for hours, give options "0-3, 3-6, 6-9" rather than a free number.
- Pilot with 2-3 students to see if they understand the questions and find it easy.

Collection (non-questionnaire):

- Consider only collecting an amount the team can analyze. E.g. have 1/16 of students fill a preview worksheet weekly; too much to review.
- Use assignments for natural feedback, reducing student burden. Students give feedback via their work; ask for opinions in lab reports.
- For longer text feedback, form an interview outline and send to some students (WeChat/email) or chat offline.
- In lunch-meeting/tea exchanges, prepare questions in advance. Downside: limits divergent thinking (search "focus groups").
- For large changes, pilot-test: e.g. a new project, have students trial-run it in the break or first half of the semester.

Analysis and use:

- Note that what students say and do may differ. If there's behavioral data (e.g. from assignments), analyze carefully.
- If possible, cross-validate ideas across different feedback channels.
- If response rate is low, reach out privately to non-responders (if named), or ignore them — they've given up their right to be heard.
- Make students feel their feedback is valued and affects teaching. Doesn't need class time; an announcement suffices. Students notice subtle improvements.
- The teacher must judge whether a piece of feedback is individual or universal. In math, a single proof doesn't establish; in reality, there are "silent majorities." (Anonymous feedback is often individual.)
- Following on: respond individually to individual, named feedback. Don't respond publicly to individual feedback — that wastes most people's time.

Course-team management/cooperation:

- Keep data well and maintained; don't lose past data due to TA turnover. This allows comparing feedback across semesters.
- Ensure the team agrees on collection, interpretation, and use. Teachers sometimes must decide.
- Use external resources: the faculty-development center offers [mid-term student feedback service](https://www.cfd.tsinghua.edu.cn/fwxm/jszx/zqxsfk.htm), or the department's course-research committee.

In offline sessions, we turn these principles into a questionnaire for participants to mark "agree/disagree."

### Understanding student background

Before course research, understand (or assume) student background, beyond the "overall quality" mentioned above.

- What kind of person do students want to become in CS?
- What's the ratio of students planning further study vs. jobs?
- What jobs do students most want? Thoughts on employment? This year's job market?
- Which CS sub-directions interest students more?
- What's the overall academic pressure?

These affect whether a course is popular.

For example, a required course from direction A may feel "useless" to students aiming for direction B, who rate it low. If you're the teacher and learn this, you can introduce the prospects of A-B cross research and how A's knowledge helps high-level B research, even design cross-lectures/assignments.

If overall pressure is already high, be very cautious increasing assignment challenge.

If certain important info can't come from other channels, add questions to your pre-course questionnaire. But much is already surveyed elsewhere:

1. School/department Youth League, student unions, department course-research committee may do basic surveys; contact their leads for data/reports.
2. Social media, private chats — helpful for understanding student spirit, but note: students willing to talk to teachers may not represent others.
3. Talk with counselors or other student-affairs staff about students' general state.
4. Teacher-teacher or teacher-TA discussions give reads on current students, but TAs are 3-4 years above students and may have a generation gap — be careful.

You may end up with "student personas," like "product personas." Ideally, when the team prepares changes, you can predict students' reactions fairly well from the (mental or written) persona. Experienced excellent teachers usually have this ability.

### Collecting specific feedback on classroom teaching / programming assignments

**On classroom teaching**

Classroom atmosphere and Rain-Classroom answers are timely feedback. After class, other means can gauge students' feelings.

You can even get pre-class feedback: distribute slides (or a preview worksheet) to some students, ask them to note the heavy/difficult points, and emphasize those in class.

Group-chat questions, students' online/offline questions to TAs, even assignment completion, all reflect teaching effect.

For example, if a knowledge point's error rate is high in an assignment, review whether it was explained clearly/thoroughly.

TA class-auditing is another feedback method but costs TA time; the team must weigh it.

After getting feedback, retell difficult points in class? Release documents? Ask TAs to arrange a recitation? It depends.

If TA time allows a weekly recitation for review, that's best.

(Detailed discussion on classroom teaching/recitations comes in later chapters.)

**On programming assignments**

If you use OJ, GitLab, etc., you naturally get lots of platform data. But data is only valuable after analysis. Consider scripts for an automated pipeline, or coordinate with the platform for analysis-friendly features (higher educational digitalization).

The submitted code and lab reports are also valuable feedback: from them we see how students completed assignments, hence feedback on assignment reasonableness. Consider asking directly in lab reports for feelings/opinions; many students are willing.

If a course has multiple assignments/parts, ask in a questionnaire: "Which assignment/module did you like/dislike most? Why?" And remember to list the assignments/modules as options. Also ask "which took most time."

Feedback about errors, unclear wording, even impossible-to-complete assignments deserves highest priority; even consider rewarding students who report such feedback.

TAs tutoring on assignments get high-quality feedback; organize it to improve assignments.

Deadline-extension feedback is common. Often students privately ask for extensions; sometimes the teacher runs a questionnaire. Avoid "extending at the last moment / after the deadline": imagine racing to meet a deadline, skipping exam review, missing a date, staying up to 3am, sloppy code, then waking to find the teacher extended by a week — you'd be tempted to rate lowest. If extending, at least let most students benefit by rescheduling.

(Detailed discussion on assignment design and tutoring comes in later chapters.)

### Pitfalls / red flags when collecting and analyzing feedback

- Treating students as "data-filling tools." We want students to participate in course-building / experience-optimization via feedback.
- If a feedback channel isn't a teaching activity, don't use score as an incentive.
- Overly long questionnaires — tiny response. Pilot to estimate time, state it, ideally under 10 minutes.
- Questionnaires with only multiple-choice/true-false/scale items. Unless it's a logistical survey, include at least one open text item.
- Overly leading questions. Don't ask "do you think the lecture is too fast?" but "to what extent did you absorb in class, and what factors caused poor absorption."
- Overly caring about extreme data. In a large class, outliers are statistically guaranteed; failing to filter pollutes data.
- Students not knowing feedback channels exist. In the first class, review feedback channels, or remind students to fill questionnaires between classes.
- Pressuring students in direct communication (one-on-one, lunch meetings). Keep a good atmosphere; even if a student is extreme, stay gracious.
- Continuing to add...

(An offline discussion topic: how to write a pre-course questionnaire?)

Reference: [How to increase course evaluation response rates: 10 do's and 3 don'ts](https://www.uhd.edu/provost/teaching-learning-excellence/instructional-excellence/Documents/How%20to%20increase%20course%20evaluation%20response%20rates.pdf)

## D. How to get feasible course improvements? / judge feasibility?

Judging whether a change is feasible and obtaining a feasible improvement are two different questions, a bit like NP=?. The list below (continuously updated) is where early improvement ideas may come from:

1. Summarized from the above course feedback — optimize pain points, refine students' suggestions. The student course-research committee may also provide ideas.
2. National/school policy direction: e.g. "curriculum ideology" reform, or "increase course challenge" reform.
3. Coordination with other course reforms: e.g. a course needs prerequisites, contact the prerequisite course's teacher.
4. Ideas from exchanges: teaching workshops, industry needs, or teacher-TA discussions.
5. Transferred from CS research: discover useful knowledge/tools in research and add them to the course.
6. Transferred from education research: read a good SIGCSE/ICER/Computer Education paper and bring the practice in.
7. Imitating other courses: compare with Stanford/MIT equivalents; differences reveal improvement directions.
8. Iterative refinement: polish new content/assignments from last semester.
9. Emergence: after absorbing enough teaching practices, student feedback, and related/unrelated knowledge, and pondering, ideas suddenly appear — unpredictable like LLM emergence.

Sometimes there are too many, not too few, ideas. Not all become feasible improvements. Even if all feasible, rarely can you realize all in one semester; choose the most important and feasible.

Feasible-looking improvements encounter unexpected situations in practice.

To improve feasibility, do more research, discussion, feedback collection. But there's no infinite time for feasibility analysis; sometimes just start small in the actual course.

For uncertain drastic changes, don't implement them all at once; find gradual ways to bring them in, always watching student reactions.

Or envision the worst case: in the worst scenario, what would this change cause? Any response? If consequences are basically controllable, you can be bolder.
