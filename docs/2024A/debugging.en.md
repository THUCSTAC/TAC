# 2024 Autumn · How to Teach Students Debugging

Discussion:

- The difficulty of learning debugging. Emphasizes that debugging is "practice, not theory"; students may lack motivation because they don't like writing code.
- Difficulties come from many sides: poor search skills; lacking the "check intermediate state vs. expected state" mindset (gdb/printf/dump are essentially the same); few courses systematically teach debugging; declining desire to write code and a subconscious desire for ready-made frameworks — while building a framework from scratch is a valuable debugging-learning opportunity. Also raised the idea of a unified tool/GUI.
- Can LLMs help students debug: beneficial or harmful? Should we forbid, encourage, or guide/regulate? For "slacker" students, a bug may make them give up; or they may use copilot/cursor constantly. Should assignments be harder / "anti-LLM"? Use a sufficiently large open-source project as learning material?
- Teaching debugging via assignments/docs: Stanford CS107e LAB3, Tsinghua networking-course debugging docs, computer-organization error quick-check list, and the data-structures "debugging tutorial" (once a week for 20-30 min in the first half of the semester, split into debugging overview, code style, and test-case construction — because offline tutoring could not overcome unreadable code, unfamiliar tools, and a lack of confidence after debugging).
- "Where did TAs themselves learn debugging": distributed/parallel systems are hard to reproduce; graphics often uses print-debugging; hardware debugging mainly looks at waveforms; minimize code / minimal working example to reproduce; some TAs only taught themselves gdb after becoming TAs.
- Related materials: Competitive Debugging (Onward! 2022), RoboBUG (ICER 17); quotes from Dijkstra and Kernighan about debugging.

[⇦ Back to 2024 Autumn](index.md)
