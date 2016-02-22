# Grading

This document outlines how the course will be graded.

> NOTE: This grading policy is tentative and subject to change until the start of the course.

Assignment | % of Grade
-----------|-----------
4 homework assignments | 40% of grade
4 in-class quizzes     | 40% of grade
1 final project        | 20% of grade

## Academic Integrity

Non-group programming assignments and quizzes must be completed indiviudally and all work must be your own. All students must abide by the following rules:
* you may not work as a partner with another student on an assignment,
* you may not show your solutions to another student or look at their solution,
* you may not discuss homework solutions in the course chat room or on the Issues pages,

We enforce these policies by periodically running similarity detection software over all submitted code. Students who violate this policy will receive zero scores on their submissions.

We encourage appropriate forms of collaboration during this course such as,
* asking for help in understanding a part of a lecture,
* assistance in the use of a software tool or library outside the context of a homework assignment,
* requesting a reference on a given software tool or library,
* discussion of topics beyond the scope of this course.

The instructors and teaching assistants hope that the student understands these policies are in place to help the student achieve a firm grasp of the course material. Cheating does not result in understanding and any assignments submitted which is not the product of your own hard work is a detriment only to yourself and your education.

The University of Washington explains academic integrity very clearly in the [Student Academic Responsibility](https://depts.washington.edu/grading/pdf/AcademicResponsibility.pdf) guide.

## Homework

See the [example-python-homework]https://github.com/uwhpsc-2016/example-python-homework) and [example-c-homework](https://github.com/uwhpsc-2016/example-c-homework) for examples on how the homework will be presented. This will be discussed at length in class.

Each homework assignment will be graded based on several components:
* 60 / 100 points - code passes tests
* 20 / 100 points - well-written report and analysis
* 10 / 100 points - code is documented according to the rubric
* 10 / 100 points - sufficient program performance (where applicable)

Details:
* **code passes tests**

  Every student's code will be run against an automated test suite. A sample / toy test suite will be supplied with every homework assignment. This supplied test suite will be there to make sure your code compiles well against our own tests suite and that your implementation conforms to certain function prototypes and interfaces.
  
  Your code will be subjected to these tests as well as some "hidden" tests written by the instructor and TAs. We will describe these hidden tests (in words) with each homework but it will be up to the student to write their own tests, unless they wish to submit their homework based on faith.
  
* **well-written report and analysis**
 
  Every homework assignment will have a handful of questions where the student will need to write some exposition. This may involve deriving certain formulae, determining the computational complexity of a certain algorithm, or plot and describe some results.

* **code documentation**
 
  Good code is code that not only runs well but is well-understood by others. Your code will be graded for cleanliness and sufficient documentation. In particular, every Python function you write should have a docstring with the following formatting, similar to the formatting used in [Numpydoc]

  ```python
  def my_function(arg1, arg2, kwd1=default_value):
      """(one-line description of function)
      
      (extended description of function)
      
      Parameters
      ----------
      arg1 : argument type
          (Descrtipion of parameter)
      arg2 : argument type
          (Description of parameter)
      kwd1 : keyword type
          Default: default_value. (Description of keyword)
          
      Returns
      -------
      variable_name : output type
          (Description of output)
      """
      # function body goes here.
  ```
  
  C code should be similarly documented. If a parameter is return by reference then be sure to indicate as such. Documentation should be provided for every function appearing in a header file. It is not necessary to duplicate the docstring for both the function prototype in the header and the function body in the source files. However, every function without a corresponding function prototype should be documented.
  
  ```c
  /*
      my_function
      
      (one-line description of function)
      
      (extended description of function)
      
      Parameters
      ----------
      arg1 : parameter type
          (Descrtipion of parameter)
      arg2 : parameter type,
          (Description of parameter)
          
      Returns
      -------
      argument or variable_name : output type
          (Description of output)
      arg2 : type, return by reference
          (Description of output)
  */
  double my_function(int, double*);  // function prototype
  
  double my_function(int arg1, double* arg2)
  {
    // function body goes here
  }
  ```

* **performance**
  
  Because this is a course on high-performance computing some of your code will be judged based on performance. While testing the correctness of your code it will be timed. The run times of every student's code will be collected and we will determine the average run time across all submissions. Performance score is based on which standard deviation your runtime will fall in.

  Std. Deviation | Points Awarded
  ---------------|---------------
  -3    | 0 / 10
  -2    | 5 / 10
  +/- 1 | 10 / 10
  +2    | 15 / 10
  +3    | 15 / 10
  

## Quizzes

Every other week we will have an in-class quiz.

## Final Examination

The final project 
