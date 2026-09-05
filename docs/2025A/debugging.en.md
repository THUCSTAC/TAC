# 2025 Autumn · How to Teach Debugging Techniques

- Introduce more systematic debugging methods: **Delta Debugging** (an automated method that simplifies test cases, from *Why Programs Fail* Chapter 5) and **Statistical Debugging**.
- Materials: Debugging book, fuzzing book, David J. Agans' *Debugging: The 9 Indispensable Rules*, G. Aaron Wilkin's *Debugging From Art to Science* (Rose-Hulman, course documents open on GitHub).
- Discussion questions (the rest are from previous semesters, for reference):
  - How does students using LLMs to complete assignments affect code debugging? What new LLM-related debugging techniques emerge? (e.g. first have the LLM explain the code to the student)
  - Where did we learn debugging ourselves? Distributed/parallel systems are hard to reproduce and involve randomness; graphics mostly print-debugging; hardware debugging mainly by waveform (advanced: compare with an ISA simulator); minimize code / minimal working example to reproduce; some taught themselves gdb as TAs.
  - Why do students struggle with debugging? Needs practice rather than theory; some don't like writing code and lack motivation. One TA said "I did this topic last year; this year I added a vscode-debugging doc and a section in the PA doc."
- Teaching debugging via assignments/docs: Stanford CS107e LAB3, Tsinghua networking debugging docs, computer-organization error quick-check list, and the data-structures "debugging tutorial" (first half of the semester, weekly 20-30 min: debugging overview, code style, test-case construction — because offline tutoring couldn't overcome unreadable code, unfamiliar tools, and a lack of confidence).
- Some quotes (Dijkstra, Kernighan on debugging; "Teacher JYY, the green mentor forgives you") and *Debugging From Art to Science*'s listed learning objectives and how to achieve them (describe how defects arise, classify bugs by reproducibility/determinism, read and understand large projects, use the scientific method to search for bugs, efficiently use debugging tools, use cause-and-effect rules to fix and prove the fix, design techniques/patterns to simplify future debugging; plus a bug logbook).
- Content is same-source as [2025 Spring debugging](../2025S/debugging.md) and [2024 Autumn debugging](../2024A/debugging.md); cross-reference them.

[⇦ Back to 2025 Autumn](index.md)
