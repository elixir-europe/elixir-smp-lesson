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

 What is important? During the Construction phase, there are two main types of important decisions that should be taken:
1. How will you test your software? How will you make sure it works as intended? This also includes decisions about sample input data that will be used to test the software, as well as decisions about what will be the output of your software.
2. How are you going to document your code? The documentation should describe not only what the various parts of code do, but also the actual scope, goals and purpose of the software and how to test it. Therefore, you should decide what would be effective ways to document your software.

### Testing or ensuring software functions as intended

> *Narrative*: 

There are several types of software testing, which can be broadly categorized into the following categories:
- Unit testing: Testing individual units or components of the software project to ensure they function as intended.
- Integration testing: Testing the integration of different components or modules of the software project to ensure they work together as expected.
- Functional testing: Testing the software's functionality to ensure it works as specified and meets the requirements.
- System testing: Testing the entire software system to ensure it meets the requirements and works as intended. 
- Exploratory testing: Ad-hoc testing performed by testers to discover new or unexpected issues in the software.
- Regression testing: Testing the software after changes have been made to ensure the changes did not introduce new bugs or issues.
- Non-functional testing: Testing the software's non-functional aspects, such as performance, security, usability, and compatibility.
- Stress testing: Testing the software under extreme or unrealistic conditions to determine its performance and stability limits.
- Acceptance testing: Testing the software to ensure it meets the customer's acceptance criteria and is ready for release.

Not all kinds of testing are necessary for every project.

> **Learning Experience** - *Exercise*: 

!!! example "Challenge 1"
> Learners answer individually the following questions in a shared document: 
> Think about a piece of software you recently developed or you're developing.
> - Did you test it? / Are you testing it?
> - Which testing approach(es) are you using?
> - Does your testing approach also include sample example input and output files?
> - If yes, what are the relevant features of such files?
> - Which testing approach(es) do you use normally? Would you be able to make a list of the types of tests you usually implement and of the corresponding relevant test parameters?
> 
> The instructor will discuss the answers and use the discussion as a starting point to deliver the content below.  


>**Learning Experience** - *Discussion* 

!!! question "Discussion"

  Do you do test-driven development? Why/why not? 

>**Learning Experience** - *Exercise*: 

!!! example "Challenge 2"
  Think of a familiar case where test-driven development was not applied (or was not applicable, like in a fast-pace developing environment, early stages of development, prototyping, ...). Describe:

  - Two situations where a test was necessary and why.
  - Two situations where a test was prescindible and why.



------------------------------------------
> *Narrative............................... 
NOTE: I REALISED THE NARRATIVE REGARDING **DIFFERENT (COMMON) TYPES OF TESTING APPROACHES** I WANTED TO INSERT HERE IS ALREADY PRESENT IN STAGE 3 (WRITTEN BY EVA). I BELIEVE IT WOULD FIT BETTER HERE (CONSTRUCTION) THAN IN STAGE 3 (APPLICATION). WHAT DO YOU THINK?*

#### Different (common) types of testing approaches
>   --> None, Unit, Integration, Functional, End-to-end, Linting, Regression, Frontend - GUI, Other (e.g.)
>   
------------------------------------------

#### Sample example input and output files.
Sample input and output files are necessary for the development of functioning software, and for ensuring that it works as intended.
These files should have the same format and content type of the actual data files, i.e. those for which the software is being developed. However, they should *not* be the actual data files, as these cannot be always kept under control and it may be difficult to decipher how your software behaves when running on actual data file. Aspects you should think about when you create toy example input data are:
- *file size*. The the size of the file should be such that you have complete control over input and output. Ideally, you should be able to do manually the calculations that your software does automatically, so that you know in advance what you can expect the output file will contain. Unless you specifically need to test the performance of the software on big data files, the smaller the input file size, the better.
- *file format*. Input file format need to be exactly the same as the actual data files. 
- *file content*. The content of the file should be exactly of the same type of the actual data file and include all the possibilities and potential exceptions that could be observed in actual data. 

### Documenting your code

*"The secret to good documentation is to write it while you're writing the code. You are your first audience. Explain what you're doing to yourself. Future you will thank you!"*
—- [Victoria Drake November 24, 2020](https://twitter.com/victoriadotdev/status/1331262801797652483?ref_src=twsrc%5Etfw) --

#### Documenting scope, goals and purpose of the software

The first thing to document about a software is its purposes. These are: the intended outcome that it is designed to achieve; what problem it solves; why it is being created; etc... The main purpose of a software can be defined in terms of user needs, technical requirements, problems to solve, etc... It needs to include both the scope and constraints of the software. 

Defining the purpose of a software piece is a crucial step in the software development process, as it provides insight, direction and focus to the development team. It also helps to ensure that the software meets the needs and expectations of its intended users. A clear definition of the software's purpose can also help to guide decision making throughout the development process, and it should be used to evaluate the success of the software after its release.



> **Learning Experience** - *Exercise*: 

!!! example "Challenge 2"
> 1. In groups, each learner will describe to the other group memebers: 
> - What are the actual scope, goals and purpose of their software (referring to a piece of software they recently developed or are developing); 
> - How will scope, goals and purpose be documented;
> - What type of documentation is available or they plan to make available.
> 2. Each group will then discuss purposes, advantages and disadvantages of the various ways of documenting software/code.
> 3. The instructor will facilitate a discussion on "How many different ways can be used to document software? Is there any that is more effective than others?"

> *Narrative: Effective ways to document your project

> From the [Berkley Library Guide on how to write good documentation](https://guides.lib.berkeley.edu/how-to-write-good-documentation):
> Best Practices for Writing Documentation:

> 1. Include a README file that contains:
> - A brief description of the project
> - Installation instructions
> - A short example/tutorial
> 2. Allow issue tracker for others
> 3. Write an API documentation
> - What a function does
> - What are the function's parameters or arguments are
> - What a function returns
> 4. Document your code
> 5. Apply coding conventions, such as file organization, comments, naming conventions, programming practices, etc.
> 6. Include information for contributors
> 7. Include citation information
> 8. Include licensing information
> 9. Link to your e-mail address at the end
> 10. List all the versions of the files along with the major edits you did in each version


> **Learning Experience** - *Exercise* 

!!! example "Challenge 1"
  Think of two pieces or components of software you normally use. 
  Imagine you are working on a new project where you have to provide the compound usage to a third party. But, unfortunatedly, you cannot redistribute the compound usage due to some licensing incompatibilities. Your only alternative is to develop one or both from scratch for your usual purposes. In the worst scenario, two colleagues, both experienced research software engineers, should help you with the reimplementations to speed up the process.
  
  To help them get a clear idea of what you want to build, for each software, define: 

 1. Purpose, scope and constraints. 
 
 2. Two functional tests the finished software components must be able to pass.



**2. For each decision, explain why it’s important.**

> **Learning Experience** - *Exercise*: 

!!! example "Challenge 3"
> The instructor will facilitate a discussion on the following three spects:
>  - "Why defining functional tests is important?
>  Why sample input and output files are necessary? 
>  What's the purpose of documenting software?" 

> *Narrative*
Why is it important? Sample input and output files are necessary for the development of functioning software, and for ensuring that it works as intended. Having the purpose (scope, and possible constraints) of the software clearly documented is necessary in focussing the development effort and avoiding feature creep. It is also crucial towards defining functional tests. Tests can also act as documentation by showing how the software can be executed and configured, but they should not be a replacement for the in-depth documentation.


Defiining how your software will be tested during development is essential to ensure that the code functions as intended. Tests can also act as documentation by showing how the software can be executed and configured
    
Including sample example input and output files is absolutely necessary for the development of functioning software, and for ensuring that it works as intended.
    
Writing good documentation to your software will help create more readable and efficient code with minimal errors. It is necessary in focussing the development effort and avoiding feature creep, and crucial in defining functional tests.


> From the [Berkley Library Guide on how to write good documentation](https://guides.lib.berkeley.edu/how-to-write-good-documentation):

> Documentation effectively connects humans and machines.

> Why writing documentation is important:
> For you:
> - You will be using your code in 6 months
> - You want people to use your code and give you credit
> - You want to learn self-determination
> - Others would be encouraged to contribute to your code
> For others: 
> - Others can easily use your code and build upon it
> For science:
> - Advances the science
> - Encourages open science 
> - Allows reproducibility and transparency

**3.Identify the specific SMP questions that are relevant in this Phase.**

SMP questions relevant to this phase:

1) Documentation: What type of documentation is available, provided with the software and delivered under the same conditions? Please provide a URL (when available).
2) Documentation: Is the purpose of the software stated in the documentation?
3) Documentation: Does the documentation describe how to test the software?
4) Testing: What type of testing do you use?
5) Testing: Are sample data and/or parameters that can be used to test the software available with the source code?

**4.Using the ELIXIR SMW, fill in the appropriate information to each SMP question that is relevant to this Phase.**

> **Learning Experience** - *Exercise*: 

!!! example "Challenge 3"
  Go to the project in the [SMW](https://smw.ds-wizard.org/) and complete the previous questions for a piece of software.
