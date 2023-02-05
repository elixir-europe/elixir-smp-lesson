---
tags:
    - Construction
    - Prototype
    - Core features
---

{% include-markdown "../links.md" %}

# Stage 2: Construction (prototyping, construction and implementing core functionality)

!!! info

    This is the stage in which the main development of the software is taking place and its core functionality is developed in an iterative process. The software will most likely be developed with the use of toy example input data, developers will document the code while writing it (inline documentation, docstrings etc.). It is also important to ensure that the code functions as intended (e.g. via unit tests or doctests).

#### Learning Outcomes:

**1. Describe what are the key decisions that need to be made during the Construction phase.**

During the Construction phase, there are two main types of decisions that should be taken:
1. How will you test your software? How will you make sure it works as intended? This also includes decisions about sample input data that will be used to test the software, as well as decisions about what will be the output of your software.
2. How are you going to document your code? The documentation should describe not only what the various parts of code do, but also the actual scope, goals and purpose of the software and how to test it. Therefore, you should decide what would be effective ways to document your software.

### Testing or ensuring software functions as intended

> **Learning Experience** - *Exercise*: 

!!! example "Challenge 1"
> Learners individually answer the following questions in a shared document: 
> - Do you test your software?
> - Which testing approach do you use normally? Would you be able to make a list of the types of test implemented and corresponding relevant test parameters?
> - Which testing approach did you use to test the software at hand?
> - Does the testing approach also include sample example input and output files?
> - If yes, what are the relevant features of such files?
> The instructor will discuss the answers and use the discussion as a starting point to deliver narrative.  


> #### Narrative............................... 
> - How to test your software (different types of testing approaches)
>   --> None, Unit, Integration, Functional, End-to-end, Linting, Regression, Frontend - GUI, Other (e.g.)
> - Features of example input and output files (recommendations on how to create "ideal" test files)
> - Effective ways to document your software

### Documenting your code

> **Learning Experience** - *Exercise*: 

!!! example "Challenge 2"
> In groups, each learner will describe to other group memebers: 
> - What are the actual scope, goals and purpose of their software; 
> - How will these be documented;
> - What type of documentation is available or they plan to make available.
> Each group will discuss purposes, advantages and disadvantages of the various ways of documenting software/code.
> The instructor will facilitate a discussion on "What's the purpose of documenting software? How many different ways can be used to document software? Is there any that is more effective than others? 

> #### Narrative..................................
> Different approaches to documenting software 


**2. For each decision, explain why it’s important.**
- testing approach needs to be defined (incl. the list of the types of test implemented and relevant test parameters)

    a. to ensure that the code functions as intended
    b. tests can also act as documentation by showing how the software can be executed and configured
    
- include also sample example input and output files.

    a. necessary for the development of functioning software, and for ensuring that it works as intended
    
- the actual scope, goals and purpose of the software needs to be defined and documented

    a. is necessary in focussing the development effort and avoiding feature creep
    
    b. Crucial in defining functional tests

###


**3.Identify the specific SMP questions that are relevant in this Phase.**

1) Documentation: What type of documentation is available, provided with the software and delivered under the same conditions? Please provide a URL (when available).
2) Documentation: Is the purpose of the software stated in the documentation?
3) Documentation: Does the documentation describe how to test the software?
4) Testing: What type of testing do you use?
5) Testing: Are sample data and/or parameters that can be used to test the software available with the source code?

**4.Using the ELIXIR SMW, fill in the appropriate information to each SMP question that is relevant to this Phase.**

> **Learning Experience** - *Exercise*: 

!!! example "Challenge 3"
  Go to the project in the [SMW](https://smw.ds-wizard.org/) and complete the previous questions for a piece of software.
