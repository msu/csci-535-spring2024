# CSCI 535: Computational Topoloy, Spring 2024 #

This repository is for class materials for Computational Topology, taught by Prof. Fasy.

Course Catalog Description: Provides an introduction to topological data
analysis (TDA). This course will cover the topological, geometric, and algebraic
tools used in TDA. Specific topics covered include persistent homology, Reeb
graphs, and minimum homotopy area. Students will explore a data set of their
choice in a course project, and learn how to apply the tools discussed in
lecture.

Prerequisites: This course assumes that you are familiar with the following
topics: set theory, vector spaces, runtime analysis, and basic data structures.
A student in this class should be familiar with proof techniques, including
proof by induction and proof by contradiction. Although not necessary, a
suggested prerequesite for this class is either M 461 (Topology), which is
offered every other Fall (odd years), or CSCI 432 (Algorithms), which is offered
once a year.

## Course Outcomes and Objectives

By the end of this course, a student will be able to:

* Explain the basics in topology, as they apply to computing with data.
* Compute Betti number, topological persistence, homology cycles, Reeb graphs from data.
* Read recent research papers in the area of computational topology.
* Articulate, both orally and in writing, mathematical proofs.
* Demonstrate teamwork skills.
* Present and critique applications of research in Topological Data Analysis (TDA).
* Recognize potential applications of TDA.


## When and Where?

* When? Tuesdays and Thursdays, 12:15-13:30
* Where? AJMJH 251

## How do I contact you?

* The preferred method for asking quiestions in this class is through slack.
  You will be given a slack invite via email. 
* If you would prefer to email me, please use: brittany.fasy@montana.edu.  
* On DMs or emails for the first half of the
  semester, please include Alex McCleary and Braeden Sopp to ensure
  that your question is answered.

Office hours this semester will be by appointment. Open office hours will be
posted on slack.  I'm always happy to meet to discuss topology, so please reach
out!

## Land Acknowledgement

Living in Montana, we are on the ancestral lands of American Indians, including
the 12 tribal nations that call Montana home today: A’aninin (Gros Ventre),
Amskapi/Piikani (Blackfeet), Annishinabe (Chippewa/Ojibway), Annishinabe/Métis
(Little Shell Chippewa), Apsáalooke (Crow), Ktunaxa/Ksanka (Kootenai), Lakota,
Dakota (Sioux), Nakoda (Assiniboine), Ne-i-yah-wahk (Plains Cree), Qíispé (Pend
d’Oreille), Seliš (Salish), and Tsétsêhéstâhese/So’taahe (Northern Cheyenne).
We honor and respect these tribal nations as we live, work, learn, and play in
this state.

To learn more about Montana Indians, I suggest starting with the following
pamphlet:
[Essential Understandings Regarding Montana
Indians](http://opi.mt.gov/Portals/182/Page%20Files/Indian%20Education/Indian%20Education%20101/essentialunderstandings.pdf)


## What is in this repository?

The folders in this repository contain all materials for this class.

- hw: homework assignments (in LaTex) 
- README.md: the syllabus, including:
    * course objectives (above)
    * schedule (bottom)

## Creating Your Own Repository 

The repository is set as public, so you can access all course materials easily.
I suggest creating a private repository with this one setup as an upstream git
repo, so that you can use your repository to maintain your own materials for
this class. 

To do so, follow these instructions:
    
    - Going to <https://github.com/new>
    - Enter the name `my-csci-535-spring2024`
    - Select `Private`
    - **DO NOT ADD A README.MD or .gitignore!**

Once your repository is initialized, you can clone it down to your local
machine.  Assuming that you have SSH keys set-up, you can do this using the
following command:
```bash
$ git clone git@github.com:USERNAME/my-csci-535-spring2024.git
```

You will likely get a warning that you just cloned an empty repo.
Next, you should add the class repository as an upstream git repo:

```bash
$ cd my-csci-535-spring2024
$ git remote add upstream https://github.com/msu/csci-535-spring2024.git
$ git pull upstream main
$ git push
```
This will synchronize your private repository with the class repository.  You
only need to run these commands once.  Then, when you want to get an update from
the public class repository you can run this command:

```
$ git pull upstream main
```

As a general workflow on your own repository, I suggest:
```
$ git pull upstream main
[[ do work here ]]
$ git add [[ list filenames edited ]]
$ git commit -m "Descriptive message here"
$ git push origin main
```

## Grading

Your grade for this class will be determined by:

- 50% Homework/Quizes
- 25% Exam (5% Oral Exam; 20% Final Exam) 
- 25% Project (including lit review)

A grade of 70\% or higher on the final exam is required to earn a B- or higher in the class.


## Class Policies

### Policy on Class Attendance

Class attendance and participation is required to succeed in this class.
Please come to class prepared by reading and working on homework problems
throughout the week. Questions are encouraged!

That being said, if you are sick, please take the time you need to feel better
and do what you need to in order to not spread illness to others. Although
in-person attendance is best, we can Zoom you into class if you are unable to
make it in person.

### Policy on Homework

All assignments must be submitted by 23:59 on the due date. Late
assignments will not be accepted.

For descriptive assignments and reports, the submission should be typeset in
LaTex (use the assingment itself as a starting point!), and submitted as a PDF
to D2L. Each problem should be started on a fresh page.

If you hand in code with yourassignments, well-organized source code with clear
comments should be submitted directly to D2L.  Do not zip the files.

***Do not search for answers to the problems.*** You will learn in this class by
solving the problems, not by reading the solutions. Regurgitating solutions you
found elsewhere will not help you learn the material.  If you feel that you need
additional resources, please ask.

(n+1)st assignment: Write a two-page paper describing to me how you have grown
as a computer scientist, mathematician, and/or a researcher in this class, and
more generally, in this semester.  To support your argument, you should
include your homework (or excerpts from your homework) and other evidence in
an appendix as evidence (and reference them!) If you do not feel that you've
grown as a computer scientist, mathematician, or researcher, explain why.
Remember, style counts. Due: End of the day of the final exam. 

Grading of homeworks: Each homework question will be graded Pass/Fail.  At
times, Pass may be designated as High Pass, Pass, or Low Pass. These problem
grades will be used to calculate an overall letter grade for the assignment.
This categorical scheme might take time to adjust to, but hopefully it takes the
focus away from the grade itself and allows you to focus on learning the
material.

### Class Project

The class project is open-form.  The course project will be an opportunity for
you to investigate a research topic in computational topology (broadly
interpreted).  This can take the form of investigating an application of
topological (or geometric) techniques to understanding your data set of choice,
or studying a computational problem in topology/geometry. The final project
might take the form of a website, a video (easy to make these days!), or a traditional
paper, or something else appropriate for your topic.  Be creative! 

The final presentations will be the last week of class (the week before finals).
It is expected that you will touch base with me about your chosen topic on or
before mid-March.

Literature Review: For this assignment you are asked to write a short
literature review or survey articale  on a topology-related research topic of
your choice. Your write-up should be about five pages (not including
references), and should include at least five primary sources. This lit review
should be a descriptive summary of research relating to your topic, including
potentially comparisons of different algorithms, hisotrical context (in which
order were papers published, and how much time was in between them?).  These
articles are written individually, so if you are working on a project
together, I suggest that you have different spins on the related research, so
that this lit review can be helpful for making progress on your course
project.

Note: If your project overlaps with other classes or your paid research hours,
please discuss with me.  This is ok, but some line will need to be drawn to
differentiate this course project from your other projects.  And, approval from
the other instructor / research adviser will need to be ensured.

### Policy on Collaboration

Collaboration is encouraged on all aspects of the class, except where explicitly
forbidden. Note:

- All collaboration (who and what) must be clearly indicated in writing on
  anything turned in.
- Homework may be solved collaboratively except as explicitly forbidden (quizzes
  and exams), but solutions must be written up **independently**.  This is best
  done by writing your solutions when not in a group setting.  Groups should be
  small enough that each member plays a significant role.  (Note, if there is a
  group assignment, each group is treated as an 'individual'.

### Classroom Etiquette

** In person: **
Except for note taking and group work requiring a computer, please keep
electronic devices off during class, as they can be distractions to other
students. Disruptions to the class will result in being asked to leave the
lecture.

** Online: **
We welcome questions!  In the Zoom breakout rooms, we
expect that you are actively working on problems.  If needed, start your group
by recapping what was discussed right before going into the breakout room or
during the class period before.  If something is unclear, ask for a
clarification from your classmate.  If your group is unsure of what the task is,
please ask and do not sit idle!

### Withdrawing

After 15 March 2022, I will only support requests to withdraw from this course
with a ``W" grade if extraordinary personal circumstances exist.
If you are considering withdrawing from this class, discussing this with me as
early as possible is advised.  Since this class involves a project, the
decision to withdraw must be discussed with me, and with your group.

### Special Needs Information

If you have a documented disability for which you are or may be requesting an
accommodation(s), please contact me and Disabled
Student Services within the first two weeks of class.

### Diversity Statement

Montana State University considers the diversity of its students, faculty, and
staff to be a strength and critical to its educational mission. MSU expects
every member of the university community to contribute to an inclusive and
respectful culture for all in its classrooms, work environments, and at campus
events.  Dimensions of diversity can include sex, race, age, national origin,
ethnicity, gender identity and expression, intellectual and physical ability,
sexual orientation, income, faith and non-faith perspectives, socio-economic
status, political ideology, education, primary language, family status, military
experience, cognitive style, and communication style. The individual
intersection of these experiences and characteristics must be valued in our
community.

If there are aspects of the design, instruction, and/or experiences within this
course that result in barriers to your inclusion or accurate assessment of
achievement, please notify the instructor as soon as possible and/or contact
Disability Services or the Office of Institutional Equity.

## MSU Policies

### Academic Integrity

The integrity of the academic process requires that credit be given where credit
is due. Accordingly, it is academic misconduct to present the ideas or works of
another as one's own work, or to permit another to present one's work without
customary and proper acknowledgment of authorship. Students may collaborate with
other students only as expressly permitted by the instructor. Students are
responsible for the honest completion and representation of their work, the
appropriate citation of sources and the respect and recognition of others'
academic endeavors.

Plagiarism will not be tolerated in this course. According to the Meriam-Webster
dictionary, plagiarism is `the act of using another person's words or ideas
without giving credit to that person.'  Proper credit means describing all
outside resources (conversations, websites, etc.), and explaining the extent to
which the resource was used.  Penalties for plagiarism at MSU include (but are
not limited to) failing the assignment, failing the class, or having your degree
revoked.  This is serious, so do not plagiarize.
Even inadvertent or unintentional misuse or appropriation of another's work
(such as relying heavily on source material that is not expressly acknowledged)
is considered plagiarism. 

By participating in this class, you agree to abide by the Student Code of
Conduct.  This includes the following academic expectations:

- be prompt and regular in attending classes;
- be well-prepared for classes;
- submit required assignments in a timely manner;
- take exams when scheduled, unless rescheduled under 310.01;
- act in a respectful manner toward other students and the instructor and in a way
          that does not detract from the learning experience; and
- make and keep appointments when necessary to meet with the instructor. 

Note from the instructor: sharing

### MSU Drug and Alcohol Policies

Per the Code of Conduct for students, no student may come to class under the
influence of drugs or alcohol, as that would not be `Fostering a healthy, safe
and productive campus and community.`  See [Alcohol and Drug Policies
Website](http://www.montana.edu/deanofstudents/alcoholanddrugs.html) for more
information.  In particular, note:

As a federally-funded institution, we must adhere to all federal laws when it
comes to alcohol and drug use or distribution. This holds true for marijuana as
well. Using or distributing marijuana on or off campus is a violation of our
code of conduct even if a student has a medical card or comes from a state in
which marijuana is legal or has been decriminalized.

As noted, the University's alcohol and drug policies apply off campus. Using
drugs and/or alcohol and returning to your residence hall in a disruptive
fashion- either via odor, noise, destruction, etc- can lead to residence life
policy and alcohol or drug policy violations. Remember, not everyone wants to
hear or smell you.

## Resources

### Technical Resources

- [Git Udacity
  Course](https://www.udacity.com/course/how-to-use-git-and-github--ud775)
- [Markdown](http://daringfireball.net/projects/markdown/) and a [Markdown tutorial](https://www.markdowntutorial.com/).
- [Inkscape Can Tutorial](http://tavmjong.free.fr/INKSCAPE/MANUAL/html/SoupCan.html)
- [Plagiarism Blogpost](https://mrwachs.wordpress.com/2019/11/25/what-is-plagiarism-in-computer-science/#:~:text=The%20term%20plagiarism%20can%20be,them%20off%20as%20one's%20own%E2%80%9D.&text=Similarly%2C%20at%20Stanford%2C%2020%25,class%20were%20flagged%20for%20cheating)
- [Ott's 10 Tips](http://www.ms.uky.edu/~kott/proof_help.pdf)
- [Big-O, Intuitive Explanation](https://rob-bell.net/2009/06/a-beginners-guide-to-big-o-notation/)
- [Graph Algorithms](https://jeffe.cs.illinois.edu/teaching/algorithms/book/05-graphs.pdf), including Whatever First Search.

### Course Textbook(s) 

Required:

- Dey and Wang, [Computational Topology for Data Analysis](http://yusu.belkin-wang.org/CTDAbook-DeyWang.pdf)
- Edelsbrunner and Harer, Computational Topology

In Addition, the following will be helpful resources:

- Cormen, Leiserson, Rivest, and Stein, Introduction to Algorithms (in MSU library online!)
- Munkres, Elements of Algebraic Topology

Each week, there will be assigned readings from these resources, as well as from
papers and other resources found on the web.

## Schedule

### Week 1 (16, 18 January)

- Topics: Introductions, Shapes 
- Readings:
    * See [CompTaG onboarding](https://github.com/compTAG/student-resources/blob/master/how-tos/onboarding.md)
    * Additional Topology Background: Dey and Wang, Chapter 1
    * Loop Invariants: see handouts/topo-sort
- Links:
    * [Miro](https://miro.com/app/board/uXjVN5XpKSo=/?share_link_id=989912125647)
    * [Euler, 1736](https://archive.org/details/commentariiacade08impe/page/n185/mode/2up), page 186
- Assignments
    * Complete the pre-exam and submit to D2L.
    * Begin working on H1.

### Week 2 (23,25 January)

- Topics: Simplicial Complexes, From Data to Complexes (e.g., Vietoris-Rips and Cech Complexes)
- Readings:
    * Dey and Wang, Sections 2.1-2.3
    * Edelsbrunner and Harer, Chapter III
- Jan 23 zoom guest lecture on Simplicial Complexes, by [Dani Salinas](https://directory.msmary.edu/people/daniel-salinas-duron.html)
    * [Notes](https://dsalinasduron-msmary.github.io/comptop_jan23/index.html) and [activity](https://colab.research.google.com/drive/1_wBnlr5M3INm4OBFMpcZkN4P8YqmAH7v?usp=sharing)
- Jan 25 zoom guest lecture on the Nerve Theorem, by [Atish Mitra](https://www.mtech.edu/mathematical-sciences/faculty/atish-mitra/index.html)
    *[Notes](lectures/lec2/nerve-theorem.pdf) and [homework](hw/hw1/HW1-Atish.tex)
- Assignments:
    * Continue working on H1.

### Week 3 (30 Jan, 1 February)

- Topics: Homology
- Readings:
    * Dey and Wang, Sections 2.4-2.5
    * Edelsbrunner and Harer, Chapter IV
    * Munkres, Chapter 1 (especially Section 11)
- Feb 1 Zoom guest lecture on homology, by [Erin Chambers](https://www.slu.edu/science-and-engineering/academics/computer-science/faculty-and-staff/erin-chambers.php)
- Assignments:
    * Continue working on H1.

### Week 4 (6,8 February)

- Topics: Computing Persistence
- Readings and Viewings:
    * [AATRN by Heiss](https://youtu.be/a-va5BRs14k?si=n57o7DvQ-uzEELkV)
    * Dey and Wang, Chapter 3
    * Edelsbrunner and Harer, Chapter VII
- Feb 6 in-person guest lecture on Computing Persistence, by [Alex McCleary](http://alexmccleary.org/)
- Feb 8 Zoom guest lecture on Modern Persistence Computations, by [Hubert Wagner](https://people.clas.ufl.edu/hwagner/)
- Assignments:
    * Continue working on H1.

### Week 5 (13,15 February)

- Topics: Functions and Reeb graphs
- Readings: 
    * Dey and Wang, Chapter 7 
    * Edelsbrunner and Harer, Chapter VI
- Assignments:
    * Continue working on H1.

### Week 6 (20,22 February)

- Topics: Mapper
- Readings:
    * [Mapper paper](https://diglib.eg.org/bitstream/handle/10.2312/SPBG.SPBG07.091-100/091-100.pdf?sequence=1)
    * Dey and Wang, Section 9.3
- Feb 22 Zoom guest lecture on Mapper, by [Facundo Mémoli](https://facundo-memoli.org/)
- Assignments:
    * Continue working on H1.


### Week 7 (27,29 February)

- Topics: More Persistence
- Readings: 
    * Dey and Wang, Chapter 4 
    * [Generalized Persistence Diagrams by Patel](https://arxiv.org/abs/1601.03107)
    * [Edit Distance and Persistence Diagrams Over Lattices by McCleary and Patel](https://arxiv.org/abs/2010.07337)
- Feb 29 Zoom guest lecture on Generalizations of Persistence, by [Amit Patel](https://akpatel79.github.io/)
- Assignments:
    * H1 (the 6-week assignment) is due 2/29

### Week 8 (5,7 March)

- Topics: TBD
- Readings: TBD
- Deliverables and Exam:
    * Oral Exam: Please send a slack message to schedule!

### Week 9 (12,14 March)

- Topics: TBD
- Readings: TBD
- Deliverables:
    * H2 due 3/12
    * Lit review due 3/15

### Week 10 (19,21 March)

- Topics: TBD
- Readings: TBD

### Week 11 (26,28 March)

- Topics: TBD
- Readings: TBD
- Deliverables:
    * H3 due 3/28

### Week 12 (2,4 April)

- Topics: TBD
- Readings: TBD
- Deliverables and deadlines:
    * Your course project should be approved by this week.

### Week 13 (9,11 April)

- Topics: TBD
- Readings: TBD
- Deliverables:
    * H4 due 4/11

### Week 14 (16,18 April)

- Topics: TBD
- Readings: TBD

### Week 15 (23,25 April)

- Topics: TBD
- Readings: TBD

### Week 16 (30 April, 1 May)

- Project Presentations!
    * Tuesday: TBD
    * Thursday: TBD
- Deliverables:
    * H5 due 4/30
    * Project deliverables due 5/2

### Finals Week

- Final Exam 

--- 

This syllabus was created, using wording from previous courses that I have
taught, as well as from courses taught by my collaborators.  Thanks, all, for
making course content and syllabi publicly available!
All content in this repository is licensed under a [Creative Commons
Attribution-NonCommercial-ShareAlike 4.0 International License](This work is
licensed under a Creative Commons Attribution-NonCommercial-ShareAlike 4.0
International License.)
