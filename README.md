# AMath 483/583 Spring 2016 - High Performance Scientific Computing

**Instructor:** Chris Swierczewski (cswiercz)

**Teaching Assistants:**
* (tbd)
* (tbd)

**In-Class Meetings:** TTh 230-330 MUE 153 (pending)

**Video Lectures:** (tdb)

**Course Chat Room:**
[![Gitter](https://badges.gitter.im/Join Chat.svg)](https://gitter.im/uwhpsc-2016?utm_source=share-link&utm_medium=link&utm_campaign=share-link)

## Course Description

Computation and simulation are increasingly important in all aspects of science and engineering. At the same time writing efficient computer programs to take full advantage of current computers is becoming increasingly difficult. Even laptops now have 4 or more processors, but using them all to solve a single problem faster often requires rethinking the algorithm to introduce parallelism, and then programming in a language that can express this parallelism. Writing efficient programs also requires some knowledge of machine arithmetic, computer architecture, and memory hierarchies.

Although parallel computing will be covered, this is not a class on the most advanced techniques for using supercomputers, which these days have tens of thousands of processors and cost millions of dollars. Instead, the goal is to teach tools that you can use immediately on your own laptop, desktop, or a small cluster. Cloud computing will also be discussed, and students who don't have a multiprocessor computer of their own will still be able to do projects using [Sage Math Cloud](http://www.sagemath.com) at very low cost.

Along the way there will also be discussion of software engineering tools such as debuggers, unit testing, Makefiles, and the use of version control systems. After all, your time is more valuable than computer time, and a program that runs fast is totally useless if it produces the wrong results. High performance programming is also an important aspect of high performance scientific computing, and so another main theme of the course is the use of basic tools and techniques to improve your efficiency as a computational scientist.

## Overview of Topics Covered

The use of a variety of languages and techniques will be integrated throughout the course as much as possible, rather than taught linearly. The topics below will be covered at an introductory level, with the goal of learning enough to feel comfortable starting to use them in your everyday work. Once you've reached that level, abundant resources are available on the web to learn the more advanced features that are most relevant for you.

> NOTE: The Course Syllabus is a work in progress and will be finalized a week before the course begins

* The command line in Unix-like shells
* Git and GitHub
* Reproducibility
  * documentation
  * writing good commit messages
  * pull requests
* Python and its uses in scientific computing
* C++11 and its uses in scientific computing
* Cython and its uses in scientific computing
* Single-core performance
  * computer arithmetic
  * memory management: registers, cache, memory, and performance
  * effective use of pointers
* Multi-core performance
  * basic parallelism in Python
  * OpenMP wiht C++ for shared memory parallel programming
  * MPI with C++ for distributed memory parallel programming
* Debugging and testing
  * writing unit tests
  * writing regression tests
  * debugging tools: pdb, gdb, valgrind, tau


# Homework and Projects

## Workflow

## Requirements and Grading

# Course Outline
