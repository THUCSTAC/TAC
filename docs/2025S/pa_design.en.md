# 2025 Spring · Innovative Design of Programming Assignments

Using a new course — the **Rust summer term** — as an example, telling how it was designed from scratch and how it changed over three years.

## Background and design

- Background: many courses introduced Rust (operating systems, compilers). After the summer-term reform, it became a 4-week intro-programming training for freshmen (Python/Rust/Java), with assembly-language programming moved to the autumn computer-systems intro. Goal: complete the dual goals of "learning a new language + building programming ability" in 4 weeks.
- Design: lectures mainly cover syntax (basic to complex); small assignments first have students rewrite programs they wrote in C/C++ in Rust, gradually introducing Rust features and appreciating differences, mainly reinforcing class content, not discriminating; project 1 tests Rust syntax and standard library (Bonus: third-party libs can greatly lower difficulty), project 2 tests building a large program from third-party libs; each project has a difficulty ladder, with some discrimination.

## Small assignments (phased)

- Stage 0: environment setup (WSL + VSCode + Git).
- Stage 1: rewrite a past C/C++ program, ensuring students know the implementation — just "translate" to Rust, starting from C-like Rust — students: "Ah, I can write Rust!"
- Stage 2: introduce some Rust syntax, teaching how to simplify code with Rust features — students: "Ah, Rust is nice, can simplify! Never write C-like Rust again!"
- Stage 3: introduce the hardest part — ownership and borrowing — training a new way of thinking — students: "Ah, Rust is hard, I'm dead!"
- Stage 4: "ease up." By now the project is assigned and students have no energy for small assignments, so assign simple problems matching the lectures.
- In-class exercises: assign a small assignment after each class with a few syntax points from that day's lecture; hint which syntax to use but don't require it, allow bypassing, no deduction.
- Small-assignment grading: 20 OJ problems, 1 point each, 20% of the total; three days from assignment to deadline, no plagiarism check, mostly for credit; over-deadline deducted by time. Manage problem statements/data locally with Git, sync to the OJ platform with Python scripts, fetch submission results, compute scores, and generate the Canvas grading xls.

## Projects

- Weeks 1-2: Wordle project (write a game, mainly testing Rust standard library; initially not Rust-y, more C-like).
- Weeks 3-4: OJ project (write an online judge, mainly testing website development on Rust third-party libs, testing the ability to learn/understand unfamiliar third-party libs; students self-study, then TAs help via two recitations).
- Grading in three parts: basic requirements (must implement, multi-step, must implement in order, provide automated tests so students can know their score), advanced requirements (several directions, students choose which to implement, graded by TA acceptance, but capped and cannot offset basic-requirement losses), non-functional (code style, Git management, report). Ratios: project 1 60+20+20, project 2 40+40+20; average around 75.
- Acceptance: 10 minutes per student to demonstrate the project, explaining and demoing each functional requirement; plagiarism is obvious (a copyist can't explain what the code does); builds presentation ability (useful in many later courses). Results recorded in a shared spreadsheet, exported as csv, processed by Python into grades; use git to keep grade history, avoiding manual arithmetic; total computed by script; a chance to appeal after publication.

## AI small assignment

- Last year discussed an AI-prompt assignment: students input prompts for an LLM to generate Rust code that passes the OJ. In summer 2024 an ungraded AI small assignment was added, but few participated (only ten), so a more interesting form is welcome.

## Telling the story

- Rust summer-term homepage: https://lab.cs.tsinghua.edu.cn/rust/ .
- Future: continue adjusting course/assignment content; plagiarism in projects is emerging — it's time for a big three-year revision; "retire" and hand over to a new generation of TAs.
- Class discussion: brainstorming/confusions about assignment design + each course's "what form do our programming assignments take" self-intro; also reintroduced the 2024 Autumn "build a router" iteration as a contrast.

[⇦ Back to 2025 Spring](index.md)
