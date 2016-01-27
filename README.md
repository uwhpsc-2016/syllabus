# AMath 483/583 Spring 2016 - High Performance Scientific Computing

**Instructor:** Chris Swierczewski (cswiercz)

**Teaching Assistants:**
* (tbd)
* (tbd)

**In-Class Meetings:** TTh 230-330 MUE 153 (pending)

**Video Lectures:** (tdb)

## Course Description

Computation and simulation are increasingly important in all aspects of science and engineering. At the same time writing efficient computer programs to take full advantage of current computers is becoming increasingly difficult. Even laptops now have 4 or more processors, but using them all to solve a single problem faster often requires rethinking the algorithm to introduce parallelism, and then programming in a language that can express this parallelism. Writing efficient programs also requires some knowledge of machine arithmetic, computer architecture, and memory hierarchies.

Although parallel computing will be covered, this is not a class on the most advanced techniques for using supercomputers, which these days have tens of thousands of processors and cost millions of dollars. Instead, the goal is to teach tools that you can use immediately on your own laptop, desktop, or a small cluster. Cloud computing will also be discussed, and students who don't have a multiprocessor computer of their own will still be able to do projects using [Sage Math Cloud](http://www.sagemath.com) at very low cost.

Along the way there will also be discussion of software engineering tools such as debuggers, unit testing, Makefiles, and the use of version control systems. After all, your time is more valuable than computer time, and a program that runs fast is totally useless if it produces the wrong results. High performance programming is also an important aspect of high performance scientific computing, and so another main theme of the course is the use of basic tools and techniques to improve your efficiency as a computational scientist.

## Syllabus

The use of a variety of languages and techniques will be integrated throughout the course as much as possible, rather than taught linearly. The topics below will be covered at an introductory level, with the goal of learning enough to feel comfortable starting to use them in your everyday work. Once you've reached that level, abundant resources are available on the web to learn the more advanced features that are most relevant for you.

* Working at the command line in Unix-like shells (e.g. Linux or a Mac OSX terminal).
* Version control systems, particularly Git, and the use of Github repositories.
* Work habits for documentation of your code, use of Git commit messages and pull requests, and reproducibility of your results.
* Interactive Python using IPython, and the IPython Notebook.
* Python scripting and its uses in scientific computing.
* Subtleties of computer arithmetic that can affect program correctness. How numbers are stored: binary vs. ASCII representations, efficient I/O.
* Fortran 90, a compiled language that is widely used in scientific computing.
* Makefiles for building software and checking dependencies.
* The high cost of data communication. Registers, cache, main memory, and how this memory hierarchy affects code performance.
* OpenMP on top of Fortran for parallel programming of shared memory computers, such as a multicore laptop.
* MPI on top of Fortran for distributed memory parallel programming, such as on a cluster.
* Parallel computing in IPython.
* Debuggers, unit tests, regression tests, verification and validation of computer codes.
* Graphics and visualization of computational results using Python.

# Homework and Projects

## Workflow

## Requirements and Grading

# Course Outline
