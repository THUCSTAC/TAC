# Code Plagiarism Detection — Details

by @HarryChen

Plagiarism detection isn't about not trusting students; it's a necessary means to establish and maintain academic-integrity awareness.

Cases:

- A student's code didn't pass all tests in a lab; after the deadline, they copied, verbatim, code a past student had published on GitHub into their own repo and submitted.
- Before the deadline, student A explained code to B, but B still didn't understand, so B asked A for the code and submitted it directly.
- A explained the assignment to a peer while recording; B later transcribed A's code from the recording and submitted it.
- Two students used GitHub Copilot and generated identical code.

**Some academic-integrity policies:**

MIT's Policy on Collaboration and Sharing

https://web.mit.edu/6.031/www/fa20/general/collaboration.html

MIT Writing Code Handbook and a Chinese translation by Jiege:

https://integrity.mit.edu/handbook/writing-code

https://jia.je/programming/2022/07/12/writing-code-cn/

Require students to fill in an honor code when submitting all assignments; it serves as a basis in later plagiarism checks, reducing unnecessary disputes.

Plagiarism tools:

- [Stanford MOSS](https://theory.stanford.edu/~aiken/moss/): widely used, but depends on a remote service and doesn't support new languages (e.g. Rust).
- [mossum](https://github.com/hjalti/mossum) can help analyze MOSS results.
- [Study in Scarlet](https://github.com/a-nikolaev/study-in-scarlet): Ruby script, produces analysis plots.
- [JPlag](https://github.com/jplag/JPlag): written in Java, but results sometimes odd.
- [JiePlag](https://github.com/thu-cs-lab/jieplag): rewritten by @jiegec, MIT-licensed.
    * MOSS-like experience, supports more languages.
    * C / C++ / CUDA / Rust / Verilog / SystemVerilog / Python.
    * Written in Rust, supports local/server, privately deployed in the department.
    * Tested in multiple courses; contact Jiege to try!

A possible plagiarism-detection process:

- Run automated analysis with the above tools.
- Read results to find suspicious duplicates, e.g.:
    * Large-scale repetition (only variable names or order differ).
    * Same core control flow (roughly the same code shape).
    * Other suspicious signs (all using niche syntax, odd whitespace, etc.).
- Invite students to talk about their process (cross-check with honor code), and ask for an explanation of parts of the code when necessary.
    * Don't pressure students too much, but must seriously state possible consequences.
- The team judges based on subjective statements and objective facts; the core criterion is whether code similarity exceeds the normal range of (not sharing concrete code) communication.

Plagiarism detection and AI:

AI can generate many basically-working variants; TAs can hardly exhaust search sources.

- Systems courses (projects) are currently much less affected than programming/algorithm courses.
- As long as students don't admit it, you get no strong evidence.
- Besides technology, more means are needed to encourage independent completion.

Use an LLM to detect plagiarism? Results are likely erroneous. Be cautious about replacing human judgment!
