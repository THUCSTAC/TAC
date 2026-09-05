# How to Support Student Learning Effectively

Earlier, discussing how to design good assignments, we tried listing ways to "increase support." Here we discuss "how to effectively support student learning" in more detail. This isn't limited to assignment help; it may include understanding lecture content.

## Why provide help?

Imagine: suppose we have assignments of suitable difficulty, good docs and frameworks, reasonable grading standards — and between release and deadline, the TAs provide no tutoring or help. What happens?

Will everyone complete smoothly?

In fact, the "variance" among students is large due to differences in ability and background. An assignment of suitable difficulty for the "average" student is almost certainly too easy for some and too hard for others.

The "too easy" part isn't a big problem; students spend little time on simple tasks for points. There may be optional challenges for their needs.

But "too hard" is bigger. Since programming assignments are often complex and student variance is large, it may not mean 70% complete smoothly and 30% struggle. It could mean only 30% can complete without help; 70% encounter problems somewhere needing help. (Numbers are estimates, not exact.)

Roommates' mutual help solves some but not all — transfer/major-change, electives, roommates can't help. Tutoring centers can handle some basic courses but not specialized problems. (And when students must use a tutoring center, they often feel the course itself lacks support.)

If students can't find suitable help, they either invest far more time than the team expected, or give up. Both learning outcomes and course ratings suffer.

So we need ways to provide effective help, or "academic support."

Another angle: appropriate "academic support" doesn't make the course "watery." Without help, students do difficulty-1.0 things; with tutoring/recitation support, they can do difficulty-1.5 things.

A reference: [A top-2 CS department student doubting they're suited for the field; what path ahead?](https://www.zhihu.com/question/349438744) describes some CS-student anxiety; some of it stems from insufficient support.

??? note "Theory Discussion: Academic Support / Learning Assistance"
    Academic support (or learning assistance) originally meant measures at the department or school level, beyond the course, to help students succeed — e.g. the academic-advising center's academic advising, tutoring centers. The expansion of US higher ed in the second half of the 20th century increased the need for academic help; in the 1960s-70s many universities set up learning-assistance centers to help underprepared students.
    
    Structured learning assistance (SLA) is a newer form: instead of supporting students in difficulty, SLA finds courses where students often struggle and actively provides recitations and tutoring for those courses.
    
    Relying on extra-course support for difficulties works for a small number of special cases. But if a significant share of a course (e.g. >20%) struggles, it's better handled inside the course — via teacher/TA help, better docs, encouraging in-course mutual aid. For many specialized courses, the learning center's capacity and targeting is limited, mainly for lower-level basics.

    Reference: https://www.lsche.net/about/history/

## Ways to improve course academic support

### What students need to do

Tutoring and recitations require students to actively seek help (ask in tutoring, attend/join recitations).

First, students must realize they need help and know how to ask.

What TAs do:

1. Help students realize they need help, and that TAs provide it.
2. Within capacity, provide the needed help.

Concretely, introduce clear standards/tools for students to gauge whether they need help.

E.g. give a reference completion time for assignments; students can time themselves and seek help when far over.

Also, students need to know what help TAs can/can't provide. Clarify at semester start, avoiding students wrongly thinking TAs can't provide something, or conversely expecting too much.

??? note "Concept: Metacognition"
    "Metacognition" is often vaguely defined. "Metacognition is essentially cognition about cognition: one's self-awareness, self-reflection, self-evaluation, and self-regulation of one's own cognitive processing, comprising metacognitive knowledge, metacognitive experience, and metacognitive monitoring." First encounters with such definitions are confusing. Without concrete examples, the concept is hard to grasp.
    
    Take "struggling to understand course material." A "high cognitive ability" person understands faster, struggling less.
    
    A "low cognitive ability" person understands slower, struggling more often.
    
    A "high metacognitive ability" person notices they're struggling, knows where, and tries help channels.
    
    A "low metacognitive ability" person may not notice (pretending to understand, half-understanding), doesn't know where they struggle or how to seek help.
    
    Course design can guide students toward better metacognition via suggestions.

## Providing the help students need

One approach:

1. Understand what difficulties students mainly encounter / what they can't solve alone.
2. Think about what help the team can/will provide.
3. Assess the match between "difficulty" and "help" (make a matrix/table) and improve.

Help and difficulty need content matching:

- If students often struggle with environment setup, write setup docs / provide docker or VM images.
- If they often struggle with debugging, provide debugging-tool/thinking help.
- If they often struggle with ideas, make the approach clearer, provide hints.

Help and difficulty need temporal matching:

- Can't guarantee help at any moment from teacher/TA — unless an auto-bot or FAQ docs.
- Guide students to seek help when available (offline tutoring/office hours).
- TAs can't promise always-prompt online replies; online can't guarantee continuous interaction.
- Help students realize when to seek help and where — give reference times (seek help at 2x reference), announce all help channels at start, describe a recommended help-seeking workflow.

??? note "Borrowed Insight: limits of online tutoring"
    Generally, it's almost impossible to answer programming question over email. Round-trip time is too long, not interactive; email discussions often devolve to a TA finding a bug for you, not educational. So attend office hours.

    from https://cs144.github.io/logistics.pdf

### Specific tutoring techniques

- Avoid directly telling answers / how to get a grade.
- Guide students to search information themselves, e.g. suggest a search keyword or doc, rather than giving the content directly.
- If online and can't reply now, say "I'll reply later today."
- Stay calm, don't bring emotion into tutoring, avoid seeming impatient/passive-aggressive.
- If possible, record/reflection on early tutorings.
- Compile some "quick replies" for efficiency.
- (Continues.)

TODO: summarize https://pg.ucsd.edu/publications/cs-undergrad-lab-tutoring-experiences_SIGCSE-2021.pdf

### Encourage peer help

Peer help often happens within class/dorm. But some classes/dorms lack it, and some students aren't with CS peers (e.g. special programs, transfers who didn't move dorms, or external electors). Techniques can increase mutual help.

E.g. create small groups. Large class groups may be dozens/hundreds; make subgroups of <20, encourage mutual help.

Or recruit some "small TAs" from students, train them, and give them some tutoring. Based on student evaluations, they can get points.

??? note "Cross-disciplinary Inspiration: small-group effect, bystander effect, and glossophobia"
    A Tencent product manager found that QQ groups >500 are a tiny share; most users are active in 4-6 groups, mostly family/friends/classmates/interests of <20.
    
    After joining a big group, the most common action is muting notifications — too much meaningless info. When disruption increases, users often leave.
    
    Whether WeChat or social media, "big groups are loose and silent, small groups are tight and active."
    
    From *Small Group Effect*: everyone wants in big groups, everyone is active in small ones. If we randomly form small groups among enrolled students, would people be more willing to speak/help than in the big group? Due to some psychological effects, possibly.
    
    Bystander effect (diffusion of responsibility): the more people present when someone asks for help, the less likely any individual helps. In small groups people may help more.
    
    Glossophobia: fear of public speaking. Online, similar "fear of speaking in a big group" — asking in a big group publicly reveals you don't know; stressful for some.

Discussion: if recruiting small TAs, what training do they need?

### Helping students in greater difficulty

By monitoring submissions, the team can identify struggling students (e.g. repeatedly not submitting without extension), but may not fully help them.

TAs can reach out to these students, ask if they need help, inform them of the academic-advising center's advising service. If needed, contact counselors.

### How to write good documentation

Docs are relatively fixed, with a "textbook" nature. "How to write good docs" vs. "good textbooks": similar? Both need authority and stability. Different: online docs are easy to iterate, correct, supplement.

Use this to continuously improve quality.

A question asked repeatedly, TAs giving the same answer — that's what docs should cover.

- In style, imitate excellent, classic textbooks or assignment docs.
- Try reading your doc aloud.
- Have someone review it.
- Use outlines, foldable blocks for clarity.
- Combine docs with code; sometimes docs as code comments.

### How to use "small TAs" (peer tutors)?

Guide peer help for broader coverage.

Select student small TAs to take tutoring/recitations; TAs handle selection, training, supervision.

At semester start, students apply, accept trial lectures and training.

Then small TAs prepare and teach recitations, handle some offline tutoring. TAs review and supervise. After recitations, attendees may rate them.

At term end, based on the semester's work, give points / waive part of the usual assignments.

References:

https://www.ccny.cuny.edu/chemistry/peer-led-recitations-general-chemistry (Peer-Led Team Learning)

Eric Roberts, John Lilly, and Bryan Rollins. 1995. Using undergraduates as teaching assistants in introductory programming courses: An update on the Stanford experience. SIGCSE Bull. 27, 1 (March 1995), 48-52. https://doi.org/10.1145/199691.199716 (for first-year intro programming, upperclass students who took the course serve as small TAs)

## FAQ

In the 2023 Autumn discussions, we collected some TA concerns and wrote one-line answers for reference.

??? question "How to ensure reasonable, balanced TA workload"
    A: Set workload caps per segment (e.g. only tutor offline at certain times) and clear shifts (e.g. who's on duty weekly).

??? question "How to solve 'no students attend recitation but many have high tutoring needs'; low participation"
    A: Clarify the audience (usually weaker students); match supply and demand (what form of tutoring students need). If students need one-on-one, try recitation first half, offline tutoring second half. Or more live coding/debugging demos.

??? question "How to control tutoring depth to avoid revealing answers or lowering difficulty"
    A: Clarify upfront the help level; don't tell current score, only suggest "next step," not "how to get full marks."

??? question "How to design a recitation"
    A: Clarify positioning: review/extend lecture, or introduce assignment ideas; clarify audience and goals.

??? question "How to design tutoring content balancing student gain and capacity; need harder extra problems?"
    A: Vary and try more, ask how students feel. Main audience is usually the weaker part.

??? question "Is it necessary to accept WeChat private chat tutoring?"
    A: If you allow it, it's hard to "meet students' expectations." Try other online channels: email, the online platform.

??? question "What knowledge/abilities should tutoring TAs have?"
    A: Know the course (lectures + assignments) and some extension; friendly; guide step by step; ability to learn and improve.
