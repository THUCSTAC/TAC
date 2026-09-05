# Insights Mined from Training Questionnaires and Feedback

We organized the questionnaire/feedback data left by past TA training (check-in, registration, satisfaction, makeup-study reflections, real-time questions, etc.) and distilled some observations useful for improving the program.

## Participation

Rough attendance for the new-TA peer-sharing sessions:

| Semester | Session | Attendees (approx.) |
| --- | --- | --- |
| 2024 Autumn | 0912 New-TA training | ~34 |
| 2025 Spring | 0314 New-TA peer sharing (online) | ~21 |
| 2025 Autumn | 0918 New-TA peer sharing | ~25 |
| 2026 Spring | 260323 New-TA peer sharing | ~13 |

(Rough counts from check-in questionnaires, not de-duplicated.)

Per-session attendance for 2024 Autumn (91 man-times total): the mandatory new-TA training (panel with experienced TAs) **34**, then lunch meetings of 5-9 each: how to teach debugging 9, office hours/tutoring 5, teacher exchange 8, assignment design 8, CS education & games 8, K-12 programming 7, evaluation-committee sharing 6, grading & plagiarism 6. Notably, the **mandatory orientation draws far more people than the relaxed lunch meetings**, so format and compulsory-ness strongly affect participation.

## One satisfaction feedback (2024 Spring "How to do regular tutoring well")

Satisfaction with the opening self-introductions, discussion, the gift, and the SIGCSE paper/tool sharing was mostly 4-5 (out of 5).

**What was mentioned as good**: open exchange guidance; very active Q&A and discussion; the LLM-answer opening plus the tutoring-center TA joining; the final paper/tool sharing; the insights about debugger environment setup and tutoring-rule design.

**Suggestions and topics of interest**:

- How to guide students to learning resources?
- Communication between TAs and teachers (teachers are often more traditional, inconsistent with contemporary students' habits).
- How to guide students from "directly asking AI for answers" toward "using AI to assist thinking"? (e.g. designing prompts that give only keywords, letting students connect the logic chain themselves.)
- Introduction and typical examples of foreign TA systems.
- Could experienced TAs' tips be compiled and voted on, with the top-voted ones entering the next year's first TA training?
- Could courses and the department tutoring center be linked? How?
- Provides bilingual (Chinese and English) versions.
- (Light-hearted feedback: ordering the fish-roe rice again next time; hoping for different books, etc.)

## Common themes in makeup-study reflections

Students who couldn't attend and claimed via recording submitted reflections, showing the topics TAs found most inspiring and of concern:

- **Impact of LLMs on assignments and grading**: e.g. an "85%-correct AI assignment" — looking at the answer alone isn't enough; you must dig into whether the student truly understands the logic; guide students to use tools reasonably rather than rely on generated answers. One TA proposed "**supervised use**": establish an "operating norm" for AI use — clarify when it's okay to get ideas from AI, but students must keep their own debugging process and key decisions. A concrete case: in a cross-disciplinary (CS x humanities/social science) course, a student pasted the entire assignment doc into ChatGPT and hadn't written or couldn't understand a line of the code.
- **Teaching debugging**: how to guide students from "directly asking AI for answers" to "using AI to assist thinking"; even if AI gives direction, deep thinking remains irreplaceable. One TA offered an actionable methodology — turn "fixing it once" into "he'll do it himself from now on": state the goal and boundaries up front (don't write the code for them, just help solve the most blocking problem within a set time), require a minimal reproducible example and a "cause - evidence - fix" record; follow a "**reproduce - minimize - determine**" sequence, entering a "**hypothesis - verification**" loop (enumerate probable root causes: environment & dependencies, input preconditions, state & caching, boundary conditions, concurrency & timing, numerical stability) and design the cheapest verification experiment for each hypothesis.
- **Identity change from student to TA**: your words represent the teaching team; "learn alongside students" rather than "teach students"; avoid communicating by "assuming students have the same ability as you."
- **Role boundaries and teamwork**: a TA isn't an "all-capable savior"; work by the syllabus and division of labor, avoid over-promising or emotional communication; automation tools and standardized workflows significantly improve efficiency.
- **AI tutors vs. human TAs**: AI can be an auxiliary tool, but a human TA's companionship, personalized guidance, and emotional support are hard to replace in the short term.
- **Balancing academic integrity and care**: maintaining course fairness without pressuring students too much is a real dilemma.
- **Inclusive teaching** (2026 Spring): dispel the "talent myth," emphasizing that CS relies on practice rather than being "naturally smart"; foster an inclusive atmosphere and promptly stop discriminatory jokes.

## Paper-reading reflections (2026 Spring)

In 2026 Spring the makeup task changed to: pick any computing-education paper from SIGCSETS 2026 and discuss its insight for TA work. The submissions show TAs connecting papers to concrete tutoring/office-hour/grading practice:

- *Why Some Students Still Opt Out of CS* — inclusive teaching: dispel the "talent myth" (CS is practice, not "naturally smart"), foster an inclusive atmosphere, break stereotypes (show diverse CS people), widen value perception (code can be used for creative/artistic work or solving nearby problems).
- *AI-Augmented Instruction: Real-Time Misconception Detection* — reframe "educational support" as continuously sensing where the class is stuck rather than waiting for hands to raise; the takeaway is to deliberately record "error patterns" during office hours (e.g. the top three conceptual mistakes), whose value far exceeds answering one by one — pass them to the professor, put them in review material, or proactively mention them next time.
- *How AI Ethics is Taught* — nearly 90% of AI-related courses skip ethics; students now commonly use AI coding agents, yet risks like code-copyright ownership, responsibility for AI-generated vulnerabilities, and uploading sensitive code to the cloud are rarely discussed. A reminder: don't just train "coders who can call AI tools," but engineers who hold an ethical bottom line.

## Real-time questions (2026 Spring)

Questions collected live via the "real-time question questionnaire", e.g.: "How to view the introductory course offered in the junior year?"
