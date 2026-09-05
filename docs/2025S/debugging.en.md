# 2025 Spring · How to Teach Students Debugging

- Introduces more systematic methods: Delta Debugging (auto-simplifies test cases, from *Why Programs Fail* Chapter 5) and Statistical Debugging.
- Materials: Debugging book, fuzzing book, David J. Agans' *Debugging: The 9 Indispensable Rules*, G. Aaron Wilkin's *Debugging From Art to Science* (lists learning objectives, e.g. describe how defects arise, classify bugs by reproducibility/determinism, read and understand large projects, reproduce/force failures, apply the scientific method to bug search, efficiently use debugging tools, use cause-and-effect rules to fix and prove the fix, design techniques/patterns to simplify future debugging; plus a bug logbook).
- Discussion: where TAs themselves learned debugging; why students struggle.
  - TAs themselves: distributed/parallel systems are hard to reproduce and involve randomness; graphics mostly print-debugging; hardware debugging mainly by waveform (advanced: compare with an ISA simulator); minimize code / minimal working example to reproduce; some TAs only taught themselves gdb as TAs, and found it great.
  - Students' difficulties: poor search; lacking the "compare intermediate vs. expected state" mindset (gdb, printf, dump are the same); few systematic debugging courses; declining desire to write code and a subconscious want for ready frameworks, while building a framework from scratch is a precious debugging-learning opportunity.
- Can LLMs help debugging: discussed "anti-LLM assignments" and "use a sufficiently large open-source project as learning material." For "slacker" students a bug may make them give up; or they may use copilot/cursor constantly.
- Teaching debugging via assignments/docs: Stanford CS107e LAB3, Tsinghua networking debugging docs, computer-organization error quick-check list, and the data-structures "debugging tutorial" (first half of semester, weekly 20-30 min, split into debugging overview, code style, test-case construction — because offline tutoring couldn't overcome unreadable code, unfamiliar tools, and lack of confidence); some TAs added a vscode-debugging doc and a section in the PA doc.
- Debugging contest: an algorithmic contest but requiring timed code debugging (Competitive Debugging).
- Icebreaker: "I'm a TA for course XX; a recent interesting bug I found was..." (can be one's own or a student's; e.g. programming, digital logic, OS user/kernel context switch not considering floating-point registers, Windows driver debugging, etc.).

[⇦ Back to 2025 Spring](index.md)
