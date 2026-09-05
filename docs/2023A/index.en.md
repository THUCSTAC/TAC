# 2023 Autumn TA Training and Teaching Seminar

Contact editor: liurd22@mails.tsinghua.edu.cn

Most of the content in the current edition can be considered a collective creation by Tsinghua's CS faculty, TAs, and the Institute of Education.

Submit your issues here: https://github.com/THUCSTAC/TAC/issues

## About this reader/notes

This reader/notes was prepared in the summer of 2023 for a seminar on computer-science teaching held in August 2023 for some faculty and TAs in Tsinghua's Department of Computer Science and Technology.

(After the seminar, the notes were iterated based on the actual process and materials.)

Although named a "reader/notes," its purpose is more to inspire — using plain, sometimes not-very-rigorous language to open up the discussants' thinking. Therefore, please treat the content critically.

"Teachers" in the title includes both course instructors and TAs, and can also be read as "educators."

The first edition planned four chapters:

1. Student evaluation and course research
2. Classroom teaching and recitations
3. Programming assignments and offline tutoring
4. Assignment grading feedback and code plagiarism detection

## About the "education" in these notes

The author hopes these notes are both practically useful for CS teaching and have some theoretical depth in education.

To make them readable, the body is practical and case-based. For readers seeking theoretical depth, there are scattered theory-discussion modules that can be folded/unfolded.

??? note "Theory Discussion: A Brief History of Education"
    Apprenticeship, lecturing, and similar educational phenomena appeared thousands of years ago, and people discussed educational ideas then — Confucius in the East, Socrates in the West.

    Only after the Industrial Revolution, to train the large number of literate workers needed by factories, did mass schooling emerge, and only then could modern educational research with schooling as its object arise.

    At the same time, the birth of modern science drove the "positivization" of various humanities (sociology, psychology, education, etc.). Applying positivist scientific methodology to the study of human social phenomena gave rise to the methodology of modern social science.

    In the first half of the 20th century, apart from some philosophical speculations (e.g. Dewey), educational research was limited to statistics-based quantitative research (questionnaires, regression, statistical significance), forming a "quantitative hegemony."

    In the second half of the 20th century, qualitative methods from sociology began to influence education (interviews, fieldwork, text collection, manual data mining and clustering). Today both quantitative and qualitative research are considered basic methods in education. Both have produced many classic educational theories. There are also mixed methods and action research emphasizing practice.

    Today, as in other disciplines, educational research types are increasingly complex and the body of educational knowledge is vast, so that even education-school professors cannot be familiar with all fields.

    One driver is that educational phenomena themselves are more complex — higher education has its own pedagogy, graduate education its own.

    Another is that other disciplines cross with education — e.g. CS + education produced educational technology, educational data science, AI education, etc.

    References:
    
    Chen Guisheng 1998, "Historical Perspective on 'Educational Phenomena'" (readable in ChaoXing e-books)

    John Nisbet, 1999, HOW IT ALL BEGAN: EDUCATIONAL RESEARCH 1880-1930, Scottish Educational Review

Education is a huge field. For CS teachers, we want to introduce the most practically useful parts.

At least these areas:

1. Computing education research, directly about CS-course teaching, represented by ACM SIGCSE, ICER, etc.
2. Engineering education research, about engineering teaching, represented by JEE (Journal of Engineering Education), Higher Engineering Education Research, etc.
3. Curriculum Studies and Pedagogy, focusing on "how to design courses and lecture," represented by China University Teaching, etc.
4. Educational measurement and evaluation, about assessing teaching/learning outcomes and quality — related to exam-based grading and student evaluation. Represented by Studies in Educational Evaluation, etc.

Each of these is a vast sea. So we "take a spoon from the three thousand waters," making targeted references and explanations around the practical problems CS faculty and TAs face. The body remains practical, putting deeper theory into collapsible sections.

Although educational works and papers are numerous, real educational practice still outstrips existing educational knowledge. So we gather new materials for this reader/seminar and discuss them. In this process new, practical educational knowledge is actually born. Some modern educational-research paradigms hold that this practical knowledge also has educational-theory value. Yes: the practical teaching wisdom you gain by collecting feedback and reflecting during your course teaching is also a kind of educational theory! Compared with more famous educational ideas, it's just less well-known and narrower in scope. But for you, it's worth more than any classic educational work or highly cited paper.

??? note "Theory Discussion: Grounded Theory"
    "Educational theory is divorced from practice" was a heated debate in Chinese education at the turn of the 21st century; neither classic works nor new research explained many phenomena of China's basic-education reform.

    What is educational theory? You can have your own answer. Here we introduce a hugely influential research-method school in social science: grounded theory, for reference.

    Grounded theory is theory "grounded in first-hand data" — not derived by philosophical speculation, nor by adapting existing theories, but by collecting large amounts of first-hand data and, following rigorous steps, inducing concepts, patterns, connections, etc., into a theoretical framework. Initially its operational details were vague; later a strict process was designed: data coding, concept extraction, relationship building, until convergence. This was proposed against the backdrop of the US sociology field being full of empty "grand theory," calling for a return to social reality and refining concepts/theories from reality rather than forcing new reality into old theory. Some think grounded theory isn't rigorous or is too tedious; others think it's irreplaceable for transcending existing-theory limits and achieving theoretical innovation.

    An interesting thought: if we liken theory-building to "wisdom-building," grounded theory resembles statistical machine learning / "data-centric AI" — collect lots of data, organize it by specific rules to form rules, and "intelligence/theory" emerges. And if we mechanically apply others' past theories to our own present teaching-practice problems, are we stuck in the expert-system dilemma from AI history?

    References:
    
    Glaser & Strauss (1967), The Discovery of Grounded Theory

    Chen Xiangming, "Exploration of the Use of Grounded Theory in Chinese Educational Research," Peking University Education Review, 2015.

## Recommended references

*Your First Year Teaching Computer Science: A Practical Guide to Success for New Computer Science Teachers*, by Chris Gregg (Stanford) — written for his CS 298: Seminars on Teaching Introductory Computer Science; practical, mainly for lower-level CS courses.

*Everyone is a Product Manager* / *Everyone is a Product Manager 2.0*, by Su Jie — viewing courses, assignments, and classroom teaching from a product perspective may open new angles. Compared with educational-research-methods books, the "user research" part in product-manager books is easier to understand. Of course, courses differ from products in many ways (e.g. university courses shouldn't be too "commercial"), so borrow critically.

SIGCSE 2023 Proceedings / ICER 2023 Proceedings, if you consider conference proceedings "books." These computing-education conferences are fairly scattered; generally two or three papers relate to your field.
