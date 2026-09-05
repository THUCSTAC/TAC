# 2024 Autumn · Assignment Grading and Code Plagiarism Detection

Slides by Chen Shengqi.

## Optional vs. required

- Whether black-box or white-box, when the scale is large you can set optional items (points). E.g. black-box 80% (basic 60% + advanced 20%), providing about 50% optional points; white-box optional can be bonus points (e.g. clearly excellent code style).
- Required items focus on course fundamentals; describe requirements in detail, control difficulty, give students a sense of achievement; watch the progression and dependencies so students don't get "stuck".
- Optional items as advanced requirements, can be left to stretch; offer several directions, assign points by difficulty; can leave open content for interested students to explore (be cautious about point rewards).
- Strictly control the total score — don't leave room for "involvement" (internal competition)!

## Setting and publishing grading standards

- Must: predetermine and use a unified grading standard.
- Should: specify in detail how each scored requirement is graded.
- Not recommended: proactively leveling differences (can be adjusted later, otherwise undermines learning).
- Recommended: decide whether to publish detailed standards based on the course — too vague, students can't judge their own completion and lack expectations; too detailed, easy to overfit and rigid, taking away agency from both students and TAs.

## Grading feedback

- Should be timely and detailed: early lack of timely feedback may cause wrong habits to persist; vague grading gives no guidance.
- A recommended approach: list all possible grading points, annotate carefully when reviewing; then compute the score by rules and generate corresponding comments, including per-part scores (at least as detailed as the document) and extra remarks (deduction reasons, what's good, what to improve).
- Use tools to reduce work: formulas / Python scripts to auto-generate repetitive parts (e.g. pre-written comments for common issues); built-in checking rules to quickly reduce errors.

## Late-submission handling

- Handling late submissions (especially projects) needs balance: too lenient (few deductions) → students tend to procrastinate; too strict (many deductions or no credit) → inflexible and may risk plagiarism.
- Middle ground: decay-based scoring by late time (S original score, D ceiling of days late, i.e. immediately late by one day after deadline). In practice, tuning the coefficients balances across courses.
- Whichever scheme, determine it at course start (at least before any assignment) and clearly tell students.

## Team assignments and grading

- Team formation: self-formed (most prefer, but unfriendly to some and easy to leave out); random assignment (uneven workload, low motivation); manual assignment (balanced but heavy TA load).
- Cross-team grading: with different team sizes, standards shouldn't change, but you can apply a proportional discount (e.g. 1.03x solo, 1.00x pair, 0.95x trio); don't encourage "fighting alone" for points.
- Uneven intra-team workload remains open: possible responses — ask each member during acceptance to gauge workload; mitigate via whole-process evaluation, student feedback, and timely intervention.
- References: intra-team peer review + individual oral (*Evaluating Group Work in (too) Large CS Classes*, SIGCSE 2023); weekly surveys to track teamwork (*Identifying Struggling Teams in Software Engineering Courses Through Weekly Surveys*, SIGCSE 2022); [CATME peer evaluation](https://info.catme.org/features/peer-evaluation/) and its five dimensions.

## Example: Programming Training Rust course

Programming assignments 20 + projects 80 + class participation 5. Small assignments via OJ; two projects at 40 each (both black-box 80% + white-box 20%). Black-box both use GitLab CI, with hidden tests at acceptance: project 1 basic 60% + advanced 20% (~65% of options offered), project 2 basic 40% + advanced 40% (~135% options offered). White-box provides grading points, reviewed by deduction; grades given about 1 week after acceptance, comments auto-generated from the grading table including black-box points and white-box deductions.

## Plagiarism detection

- Why detect? Not to distrust students, but as a necessary means to establish and maintain academic-integrity awareness.
- Typical cases: copying previous-year code published on GitHub verbatim after the deadline; taking a classmate's code directly without understanding; transcribing a classmate's code from an explanation recording; two students generating identical code with GitHub Copilot.
- Tools: Stanford MOSS (remote, no new languages like Rust); mossum to help analyze MOSS; Study in Scarlet; JPlag (Java, sometimes odd results); JiePlag (rewritten by @jiegec, MOSS-like, supports C/C++/CUDA/Rust/Verilog/Python, written in Rust, local/server, privately deployed in the department).
- Process: automated analysis → read results to find suspicious duplicates (large-scale repetition, same core control flow, all using niche syntax/odd whitespace, etc.) → invite students to talk about their process and cross-check with honor code (don't pressure, but seriously state consequences) → the team judges based on subjective statements and objective facts; the core criterion is whether similarity exceeds the normal range of (not sharing specific code) communication.

## Written and programming assignments

- Written assignments: often tedious, but important. Non-technical advice — rotate problems to prevent copying past public ones; selectively grade when many, but don't grade by "fan" or strlen; publish detailed solutions promptly; run recitations or provide error compilations. Technical advice — require a common electronic format (PDF), use scanning apps for handwritten work; try automated grading with structured answers.
- Written assignments + LLM: math is still hard to recognize/understand; plain text needs lots of prompt tuning; domain knowledge may be hard to feed; the model isn't good at scoring yet.
- Programming-assignment score split: objective (black-box, functional, auto-testable, clear metrics) vs. subjective (white-box, non-functional, human-judged, more TA discretion).
- Black-box: usually 70%-90%, with standard answers or auto-testing. Key choice: publish test cases? Publishing → students code to the tests, overfitting; not publishing → fear. Recommended: publish some, design hidden tests, or grade with different data. Some courses add performance scores beyond correctness (e.g. correctness 80% + ranking 20%), by relative rank or absolute performance; carefully set mechanisms to avoid meaningless "involvement".
- Automated grading schemes (simple to full): students submit code purely tested by TAs; provide a testing framework without data/cases; provide tests and cases; provide tests + cases + test environment. Recommend the latter when possible. Automation via Tsinghua GitLab CI; use generic frameworks (language built-in / Googletest); make results detailed and structured for scoring.
- White-box: usually 10%-30%, evaluating reports, code style & taste, project management (Git); TAs can exercise reasonable discretion, but should still have clear items and standards to avoid large discrepancies between TAs.

[⇦ Back to 2024 Autumn](index.md)
