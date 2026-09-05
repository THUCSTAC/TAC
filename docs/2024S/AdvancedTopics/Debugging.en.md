# The Instruction of Debugging

Discussion questions:

- What bug did I help a student debug recently, and how? (Share one interesting bug you found recently)
- Where did we learn debugging ourselves? (How did TAs themselves learn debugging?)
- Why do students struggle at debugging? (Why students struggle at debugging?)

Related papers:

Competitive Debugging: Toward Contests Promoting Debugging as a Skill  (Onward! 2022)
RoboBUG: A Serious Game for Learning Debugging Techniques (ICER 17)

## Debugging methods/tools to teach students

- Delta Debugging — an automated method that simplifies test cases (*Why Programs Fail*, Chapter 5).
- Statistical Debugging (Debugging book).
- Reference materials: *Debugging: The 9 Indispensable Rules for Finding Even the Most Elusive Hardware and Software Problems* (David J. Agans), *Debugging From Art to Science* (G. Aaron Wilkin, Rose-Hulman, course docs open-sourced), [Debugging book](https://www.debuggingbook.org/), [Fuzzing book](https://www.fuzzingbook.org/).

## Difficulties in teaching debugging

- Debugging is a tool like a wrench that takes time to learn and use, with payoff later; students struggle to see its necessity.
- Common difficulties: poor search skills; lacking the "check intermediate vs. expected state" mindset (gdb/printf/dump are essentially the same); few systematic debugging courses; declining desire to write code and a subconscious want for ready frameworks, while building a framework from scratch is a precious debugging-learning opportunity.
- Needs practice rather than theory; some students don't like writing code, so lack motivation to learn debugging.

## Teaching debugging via assignments/docs

- Stanford CS107e LAB3, Tsinghua networking debugging docs, computer-organization error quick-check list.
- Data structures "debugging tutorial": once a week for 20-30 min in the first half, split into debugging overview, code style, and test-case construction (because offline tutoring couldn't overcome unreadable code, unfamiliar tools, and lack of confidence).
- Some TAs added a vscode-debugging doc and a section in the PA doc.

(The above was further developed in the 2024 Autumn, 2025 Spring, and 2025 Autumn debugging seminars, which also discussed the impact of LLMs on debugging teaching.)
