# Grading Different Types of Assignments

by @HarryChen

## Written-assignment grading

Often a heavy, boring task, but an important part of teaching and TA work. LLMs can't fully take it over yet.

Non-technical advice:

- Rotate problems (if possible) to prevent direct copying of past public assignments.
- When there are many questions, grade selectively, but don't grade by "fan" or strlen.
- Publish fairly detailed solutions promptly after the assignment.
- Run recitations or provide error compilations to help review.

Technical advice:

- Require a common electronic format (e.g. PDF), use scanning apps for handwritten work, avoid chaos and loss.
- Try automated grading: e.g. require students to write answers in a structured way.

## Programming-assignment grading

Programming-assignment grading usually splits into objective and subjective parts.

Objective scoring (black-box) has objective functional standards, usually auto-testable, giving students clear metrics.

Subjective scoring (white-box) is non-functional, human-judged, giving TAs more room.

### Black-box scoring

Usually 70%-90% of the score.

Has standard answers, or can be auto-tested, as the functional evaluation.

Key choice: publish test cases/data?

- If public, students may code to the tests and overfit.
- If not public, may cause fear.

Recommended: publish some test cases, design hidden tests, or grade with different data.

Some courses also set performance scores beyond correctness.

E.g. black-box split into correctness 80% + ranking 20%, by relative rank or absolute performance. Set mechanisms carefully to prevent meaningless "involvement" wasting time.

Automated grading can be layered (prefer the later options when possible):

- Students submit code, fully tested by TAs.
- Provide a testing framework without data/cases.
- Provide a testing framework with (possibly incomplete) tests/cases.
- Provide a testing framework with tests/cases + test environment.

Specifically:

- Automated testing: use Tsinghua GitLab CI.
- Testing framework: prefer generic ones (language built-in / Googletest, etc.).
- Results: as detailed as possible, structured output for scoring.

### White-box scoring

Usually 10%-30%, as the non-functional evaluation: lab reports, code style & taste, project management (Git). TAs can exercise reasonable discretion.

Despite human judgment, there should be clear items and standards to avoid large discrepancies between TAs. This cultivates good habits while reducing confusion.

## Optional vs. required

Whether black-box or white-box, when the scale is large you can set optional items.

E.g. black-box 80%, with basic 60% + advanced 20% (about 50% optional points). White-box optional can be bonus points (e.g. clearly excellent code style).

Required items focus on course fundamentals; describe requirements in detail, control difficulty, give students a sense of achievement.

Watch progression and dependencies, prevent students from getting "stuck."

Optional items as advanced requirements; offer several directions, assign points by difficulty.

Can leave open content for interested students (be cautious about point rewards), but strictly control the total score — don't leave room for "involvement"!

## Setting and publishing grading standards

**Must** predetermine and use a unified standard.

**Should** specify in detail how each scored requirement is graded.

**Not recommended** to proactively level differences: can adjust later, otherwise harms learning.

**Recommended** to decide whether to publish detailed standards by course.

- Too vague: students can't judge their own completion, lack expectations.
- Too detailed: easy to overfit and rigid; students and TAs lose agency.

Give students a simple version; TAs use the detailed version.

## Grading feedback / comments

Feedback should be timely and detailed. Early lack of timely feedback may cause wrong habits to persist; vague grading gives no guidance.

A recommended practice:

- List all possible grading points, annotate carefully when reviewing.
- Compute scores by rule afterward and generate comments, including per-part scores (at least as detailed as the doc).
- Include extra remarks (deduction reasons, what's good, what to improve).
- Use tools to reduce work: formulas / Python scripts.
- Auto-generate repetitive parts (e.g. pre-written comments for common issues), with built-in checking rules to reduce errors.

## Late-submission handling

Handling late submissions (especially projects) needs balance.

- Too lenient (few or no deductions) → students tend to procrastinate.
- Too strict (heavy deductions or no credit) → inflexible, may risk plagiarism.

Middle ground: decay-based by late time:

$$ S' = S \times \min(0.8, 0.95^D) $$

where S is the original score and D is the ceiling of days late (i.e. immediately late = one day after the deadline).

In practice this scheme (by tuning the two coefficients) balances across courses.

Whichever scheme, determine at the course start (at least before any assignment) and clearly tell students.

## Team-assignment grading

Team formation:

- Self-formed: most prefer, but unfriendly to some and easy to leave out.
- Random by TAs: easy to get uneven workload and low motivation.
- Manual by TAs: balanced but heavy TA load.

Cross-team grading:

- With different team sizes, standards shouldn't change, but consider proportional discount.
- E.g. solo 1.03x, pair 1.00x, trio 0.95x.
- Don't encourage "fighting alone" for points.

Uneven intra-team workload remains open; possible responses:

- Ask each member individually at acceptance to gauge workload.
- Mitigate via whole-process evaluation, student feedback, and timely intervention.

### References for team grading:

Intra-team peer review + individual oral:

Evaluating Group Work in (too) Large CS Classes with (too) Few Resources: An Experience Report. (SIGCSE 2023).

Weekly surveys tracking teamwork:

Identifying Struggling Teams in Software Engineering Courses Through Weekly Surveys (SIGCSE 2022).

CATME peer evaluation

https://info.catme.org/features/peer-evaluation/

https://info.catme.org/features/catme-five-dimensions/
