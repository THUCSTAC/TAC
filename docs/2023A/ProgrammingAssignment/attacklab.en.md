# Why Is Attack Lab Good?

(by @jiegec)

[Attack Lab](https://csapp.cs.cmu.edu/3e/attacklab.pdf) is a lab from CMU 15-213 Computer Systems Intro, where students experience code-injection attacks; it's widely praised.

In offline exchanges, we discussed its strengths and how to borrow them into our own assignments. What's listed here is only a teaser — copying existing overseas labs isn't enough; combined with teaching needs, we often need to design our own assignments.

## Clear learning goals

It states at the very beginning what abilities are trained, so students feel gains beyond the grade.

This assignment involves generating a total of five attacks on two programs having different security vulnerabilities. Outcomes you will gain from this lab include:

- You will learn different ways that attackers can exploit security vulnerabilities when programs do not safeguard themselves well enough against buffer overflows.
- Through this, you will get a better understanding of how to write programs that are more secure, as well as some of the features provided by compilers and operating systems to make programs less vulnerable.
- You will gain a deeper understanding of the stack and parameter-passing mechanisms of x86-64 machine code.
- You will gain a deeper understanding of how x86-64 instructions are encoded.
- You will gain more experience with debugging tools such as GDB and OBJDUMP.

## Step by step

Split into multiple steps, grade per step, with content dependency and difficulty progression between steps.

| Phase | Program | Level | Method | Function | Points |
| ----- | ------- | ----- | ------ | -------- | ------ |
| 1     | CTARGET | 1     | CI     | touch1   | 10     |
| 2     | CTARGET | 2     | CI     | touch2   | 25     |
| 3     | CTARGET | 3     | CI     | touch3   | 25     |
| 4     | RTARGET | 2     | ROP    | touch2   | 35     |
| 5     | RTARGET | 3     | ROP    | touch3   | 5      |

## Complete documentation

- Teaching purpose
- How to get started
- Expected input/output
- Common problems and solutions

## Fun

- Mastering the skill of attacking software
- Things that once seemed hard, you find you can do after learning
- A huge sense of achievement
- Besides a high score, is there another motivation?
