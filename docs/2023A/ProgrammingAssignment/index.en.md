# How to Design Good Programming Assignments

(Integrating the 2023 Autumn sharing by @jiegec.)

This chapter tries to answer:

- What is a good programming assignment from the student's and teacher's perspective?
- How to balance challenge and support in an assignment?
- In actual courses, how are good assignments designed?

In offline discussion, we invite experienced TAs to share lessons from designing assignments, and discuss what makes excellent assignments good, e.g. [Attack Lab](./attacklab.md).

## "Good programming assignments" in students' and teachers' eyes

Earlier, CS TA's Weekly tried to collect assignments meeting "good assignment" standards. You can also refer to "CS self-study guide" collections of course assignments.

Discussion topic 1: share the best programming assignment you've encountered.

(Alternative: collect examples before class, and in class discuss a case: what makes it good?)

(Alternative: lower-level required courses, upper-level required courses, upper-level electives — what differs in assignment design?)

### A case: how do students evaluate assignments?

In 2023 Autumn we collected students' evaluations of some assignments in Tsinghua's Data Structures course, as material for discussing "is an assignment good."

**Well-received assignments** (JumpIntoDSA / the decision-tree lab):

- Felt it was quite rewarding; deepened understanding.
- Learned a lot, rather than monotonously debugging.
- Taught me many debugging methods and virtual-machine usage.
- Very interesting / useful and meaningful.
- Could learn a bit of machine learning (the decision tree).
- The topic was interesting and it also builds ability; a real sense of achievement after finishing.

**Poorly-received assignment** (Zuma):
- Workload far above average for all assignments.
- Mainly tests debugging C++ programs, which wasn't systematically taught in class, so it didn't reinforce class learning; one bug involved a `cin` usage detail, which didn't feel like testing data-structure/algorithm knowledge.
- Reading others' non-standard, buggy code is painful; and the program is platform-dependent (bugs seen locally didn't appear on the OJ; different compiler versions).
- Long sample programs; if you don't read the code, you need lots of effort writing scripts to test, wasting time.
- Had to debug many pieces of code; self-made test cases might not match OJ errors, and can't use debugging tools, so had to read code to find errors.
- Too many test cases; a headache.
- A bit monotonous and time-consuming.

These echo the point above: good assignments make students "gain something" (learn new things rather than monotonous debugging) and are interesting/meaningful; poor assignments often involve testing an unsystematically-taught ability, hard-to-read code/docs, platform-dependent irreproducibility, and monotonous, time-consuming labor.

## Balancing challenge and support

"Increasing challenge" is a style the school advocates. Here we think giving appropriate support helps students overcome harder challenges.

Suppose "challenge" is the difficulty of tasks students complete in the course, and "support" is the help given to complete them. Does higher support make tasks easier and lower challenge?

Suppose with no support, students can complete task A of difficulty 5; with documentation/tutoring support, the actual difficulty of A drops to 3.

But if students can actually do difficulty 5, then with support they can complete task B of "original difficulty 7"; with support, actual difficulty may still be ~5. Then both challenge and support are increased.

Let's call the no-support difficulty "original difficulty"; within the course, due to time limits, prerequisites, docs/tutoring, the actual difficulty is "actual difficulty."

Consider doing something of actual difficulty 5 in a course; three cases:

- Original difficulty 3, but due to chaotic docs and unclear requirements, actual difficulty becomes 5.
- Original difficulty 5, docs mediocre, effectively no support, actual difficulty ~5.
- Original difficulty 7, with reasonably good docs and a bit of tutoring, actual difficulty drops to 5.
- Original difficulty 9, with excellent course design, docs, and tutoring, actual difficulty drops to 5.

Assume all are useful real-world research tasks, just at different difficulty levels: which case gives students more sense of achievement and gain?

Analogy: requiring a student to write bubble sort while standing on their head eating noodles and blindfolded; simply teaching then having them independently implement merge sort; giving thorough documentation to implement a distributed parallel sort. Time may be similar, but the gain in programming ability and algorithmic knowledge differs vastly.

Classify courses by challenge and support:

- Little challenge, little support: an ordinary "water course," learn little.
- Little challenge, lots of support: an enjoyable "water course," good for credits.
- Lots of challenge, little support: students may think "fly bitch," a "stone course," or "you can learn if you work hard."
- Lots of challenge, lots of support (matching): a "gold course" where students learn and gain.

So it matters to match challenge and support. This requires continuous feedback to understand students' perceived challenge and support.

At semester start, to gauge difficulty, have trial-runners. But note trial-runners (TAs) are usually above the class average; adjust the estimate accordingly.

Also, understand techniques to increase challenge/support. Here are some ideas (hopefully inspiring).

Increase challenge:

- Require more assignment problems.
- Use frontier research projects as big projects.
- Use more complex, real-world engineering projects.
- Combine multiple knowledge areas, e.g. across chapters, or joint labs across courses.
- Combine theory and practice, e.g. add thinking questions to programming labs, add programming tasks to written assignments.
- Change team assignments to solo.
- Change absolute-performance grading to performance-ranking grading.
- Raise performance requirements.
- Don't provide a framework; require from-scratch implementation.
- Add bonus options: implement a feature for points, or complete a harder version for bonus.
- (Continuously added.)

Increase support:

- Break a complex task into more parts.
- More detailed docs, prerequisite docs, video explanations.
- More recitations.
- More offline/online tutoring channels and discussion forums.
- Allow teams for solo assignments, or other ways to encourage exchange.
- Change performance-ranking grading to absolute-performance, set a performance baseline.
- Provide a framework or reference examples.
- Add a simpler version; choosing the simple version earns slightly fewer points than standard.
- Give reference time for each step; students can judge if they're taking too long and need help.
- For big projects, add more milestones and reporting.
- (Continuously added.)

Discussion topic: what are reasonable ways to increase challenge/support?

??? note "Theory Discussion: Scaffolding and Zone of Proximal Development"
    The two most famous education-psychology theories on providing support are Vygotsky's Zone of Proximal Development and Bruner's Scaffolding.
    
    These are independent theories, later linked. A popular view: if a child can solve difficulty A alone, and with an adult's help solve B, the range A-B is the ZPD; the adult's help is "scaffolding." By gradually reducing help, the child rises to solving B alone. "Child/adult" can be "apprentice/expert," "student/teacher," "student/TA." It can mean in-class impromptu hints, or provided docs/tutoring.
    
    Scaffolding and the zone of proximal development: A problematic relationship (2020) questions scaffolding theory: it may suit cases where the goal is very clear (complete a specific task). If we want students to build the will for independent problem-solving, providing scaffold-like help may not help.
    
    In short, "ZPD" and "scaffolding" are principles: neither assign tasks far beyond ability nor too easy. Finding the balance where students feel challenged but not discouraged — and ideally for all levels — requires knowing the students and the subject well. Without that, educational theory and principles are not very usable.

## Where do good assignments come from?

People mention software lifecycles, product lifecycles. Try applying this thinking to assignments, dividing the assignment lifecycle.

Roughly: initial idea - design/implementation - actual use - feedback iteration.

??? note "Cross-disciplinary Inspiration: Software Lifecycle"
    The Software Development Lifecycle is important in software engineering/product management. Common stages: planning, design, implementation, testing, deployment, maintenance.
    
    These connect into models: waterfall (sequential), iterative (start with a minimal version, improve on it), agile (split into small sprints), etc.

### A. Initial idea

Get a vague idea: "what assignment to make, achieving what goal."

Most ways of getting "feasible course improvements" also suit initial assignment ideas.

Specific scenarios:

- From student feedback, find debugging is time-consuming; think "can we add an early assignment teaching debugging tools/methods?"
- A class mentions another course is "building a CPU"; the teacher thinks "should we build something too?"
- Prerequisite/follow-up courses change a knowledge point; so we need an assignment using/not using it.

Not every initial idea enters the course, but having many to select from is good. The team should accumulate and discuss ideas normally, not brainstorm from scratch each semester. Create a shared doc for teaching/assignment ideas.

### B. Design/implementation

Need a publishable version. Details may be imperfect, refine later.

An assignment needs at least documentation, a framework, and a grading standard. Grading is discussed later.

Some courses need an auto-grading OJ/CI platform; for details, talk to courses with similar needs.

**Documentation**: use the popular open-source framework [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/), deployable to your server or GitHub Pages, giving the course more influence. Rather than "principles for writing docs," reference excellent assignment docs. Two recommendations:

- [Rust summer term](https://lab.cs.tsinghua.edu.cn/rust/)
- [rCore tutorial](https://rcore-os.cn/rCore-Tutorial-Book-v3/chapter0/0intro.html).
- (More can be added.)

Docs should give clear requirements. If not clear, TAs must be ready to clarify. Apparently some courses deliberately write vaguely, requiring students to ask, simulating real-world requirement refinement.

(Possible discussion topic: what can we learn from excellent assignment docs?)

**Framework**: avoids students being lost. If provided, the framework itself should teach good code style and project structure.

Ensure the framework works in different environments, or tell students how to set up / provide the environment. WSL solves many Windows issues, but ARM Macs are often overlooked.

Some students feel a too-complete framework means they don't need to understand it, just fill in low-tech blanks, with low achievement. Try thinking questions requiring reading the framework.

**Grading standard**: first clarify: do we want discrimination? (Formative vs. summative assessment?)

If there's a final exam and assignments are for learning, maybe don't discriminate; completing basics gets most points.

If the assignment is a big project dominating the grade, then discriminate.

Discussed further later.

??? note "Theory Discussion: Formative vs. Summative Assessment"
    Formative assessment: students also learn during assessment, e.g. regular assignments.
    
    Summative assessment: no learning during assessment (but can spur learning before/after), e.g. quizzes, final exams, final projects.
    
    Both suit certain contexts. Done well, both encourage studying.

**Other**:

Teams usually design assignments during the break, or at least before release.

"Get the assignment out on time" seems simple but with poor project management it slips; leave slack (e.g. set the TA deadline a week before release, not a day) and check progress often.

If manpower allows, review/trial-run the assignment. Typos and formatting are one thing, but at least don't discover after release that a requirement is impossible. Consider recruiting volunteers from enrolled students to trial-run.

### C. Actual use

During the semester: release assignment, students complete it, team grades.

Set deadlines avoiding midterm/finals week (sometimes avoiding student festivals), and other courses' major deadlines (upper-level courses often coordinate).

Before the deadline (a week/days), TAs can remind in the group.

If students report unclear wording or framework bugs, follow up promptly. Consider adding common questions to a shared doc / merging into the assignment doc.

Grading/feedback should be timely. Delaying grades to the end of semester feels bad.

### D. Iteration/refinement

After the semester, summarize improvements.

Consider: overall completion, average score and discrimination, actual workload, etc.

See the "collecting assignment feedback" chapter.

If possible, update/change assignments yearly.
