# Basics: Assignment Grading and Plagiarism Detection

## The 10-minute lecture

In TA work, you often face assignment-grading tasks. Sometimes the teacher gives a standard, or there's a past one. Sometimes you need to set your own standard.

The former just requires "following the rules"; here we mainly discuss when TAs must set their own standard.

For written assignments, first avoid random grading or grading by length. To reduce workload, consider randomly selecting a subset of questions to grade. Ideally, provide solutions to students, and rotate some questions across semesters. But in practice, past written assignments are often reused, and students reuse past answers — the assignment loses its training value. In that case, better to drop the written assignment and add more meaningful learning activities.

Technically, require a common file format (e.g. PDF), or even a spreadsheet-like template, and use scripts to make "review, grade, auto-jump to next" a workflow.

Programming assignments are more work, including white-box and black-box parts.

## Discussion questions

Question 1:

Suppose a course needs to add a big assignment implementing a map-pathfinding algorithm usable in Chongqing. How should the grading standard be set?

(Replace the course with discrete math, OOP, data structures, software engineering, etc., and think about how the answer differs.)

When setting the standard, consider:

- What level gets 60, 80-90, 100, and what earns extra points beyond 100?
- "The 80-90 standard" is usually the level you want most students to reach; the standard must align with the course's core goals.
- Then change the context: suppose it's a GIS / data-structures / OOP course's big assignment; how should the standard differ?

You can also practice on a concrete assignment: intro-programming's Wordle project, Software Institute's "write a game" project, data-structures white-box code-style and lab-report grading, graduate-course assignments, etc., discussing how to set standards.

Question 2:

What impact will LLMs have on code plagiarism detection?

More importantly: how to design good grading standards and plagiarism-detection methods so students can't get most marks just via an LLM, thereby encouraging deep thinking.

Finally, briefly shared the SIGCSE 2024 paper "learners teaching novices," about assessing mastery by having students teach others to program.
