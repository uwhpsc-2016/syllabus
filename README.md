> **Disclaimer**: The content of this document and the other documents in this repository are subject to change until the start of the Spring 2016 Quarter.

# AMath 483/583 Spring 2016 - High Performance Scientific Computing

**Instructor:** Chris Swierczewski ([cswiercz](https://github.com/cswiercz))

**Teaching Assistants:**
* 483 - Sean Santos ([quantheory](https://github.com/quantheory))
* 583 - Meghana Velegar ([mvelegar](https://github.com/mvelegar))

**In-Class Meetings:** TTh 800-930 LOW 206

**EDGE Videos:** (tdb)

**Course Chat Room:**
[![Gitter](https://badges.gitter.im/Join Chat.svg)](https://gitter.im/uwhpsc-2016?utm_source=share-link&utm_medium=link&utm_campaign=share-link)

## Additional Important Information

* [Course Syllabus](https://github.com/uwhpsc-2016/syllabus/blob/master/Syllabus.md) - detailed course syllabus, day-by-day lectures, homework due dates, quiz dates
* [Grading Policy](https://github.com/uwhpsc-2016/syllabus/blob/master/Grading.md) - how the course homework, quizzes, and final project will be graded,
* [Asking Questions](https://github.com/uwhpsc-2016/syllabus/blob/master/AskingQuestions.md) - course rules on posting questions in the course chat and issues pages, list of resources on various topics

## Course Description

Computation and simulation are increasingly important in all aspects of science and engineering. At the same time writing efficient computer programs to take full advantage of current computers is becoming increasingly difficult. Even laptops now have 4 or more processors, but using them all to solve a single problem faster often requires rethinking the algorithm to introduce parallelism, and then programming in a language that can express this parallelism. Writing efficient programs also requires some knowledge of machine arithmetic, computer architecture, and memory hierarchies.

Although parallel computing will be covered, this is not a class on the most advanced techniques for using supercomputers, which these days have tens of thousands of processors and cost millions of dollars. Instead, the goal is to teach tools that you can use immediately on your own laptop, desktop, or a small cluster. Cloud computing will also be discussed, and students who don't have a multiprocessor computer of their own will still be able to do projects using [Sage Math Cloud](http://www.sagemath.com) at very low cost.

Along the way there will also be discussion of software engineering tools such as debuggers, unit testing, Makefiles, and the use of version control systems. After all, your time is more valuable than computer time, and a program that runs fast is totally useless if it produces the wrong results. High performance programming is also an important aspect of high performance scientific computing, and so another main theme of the course is the use of basic tools and techniques to improve your efficiency as a computational scientist.

## Prerequisites

* CSE 142 or AMath 301
* Linear Algebra

It is recommended, but not necessary, that the student have programming experience beyond that taught in AMath 301. The course will be taught in Python and C. Experience in these languages help. Although we will spend some time becoming acquainted with these languages we will quickly move on to solving computational science problems with them. At the very least, the student should have a firm grasp of basic programmatical constructs. (conditional statements, loops, array manipulation)
