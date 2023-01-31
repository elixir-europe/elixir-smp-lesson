---
tags:
    - Application
    - Prototype
    - Communication
    - Community
---

{% include-markdown "../links.md" %}

# Stage 3: Application 

**Authors:**

- Eva Martín del Pico [:custom-orcid:](https://orcid.org/0000-0001-8324-2897)


!!! info 
  This is the stage in which core functionality is developed in an iterative process. The software will most likely be developed with the use of toy example input data. During this stage, developers will document the code while writing it (inline documentation, docstrings etc.). It is also important to ensure that the code functions as intended (e.g. via unit tests or doctests). 
 
## Learning Outcomes

### 1. Describe what are the main activities that take place during the Application phase. 

#### a. Documenting how the software can be reliably used by people external to the development group or person 

> *Narrative*: 

The first thing to document about a software is its purpose, this is, the intended outcome that it is designed to achieve, what problem it solves, why it being created. The purpose of a software can be defined in terms of user needs, technical requirements, problem to solve, etc, and needs to include the scope and contraints of the software. 
Defining the purpose of a software is a crucial step in the software development process, as it provides direction and focus to the development team, and helps to ensure that the software meets the needs and expectations of its intended users. A clear definition of the software's purpose can also help to guide decision making throughout the development process, and can be used to evaluate the success of the software after its release.

> **Learning Experience** - *Exercise* 

!!! example "Challenge 1"
  Think of two pieces of software you normally use. 
  Imagine you are working on a new project where, unfortunateyl, you can't use them due to some licensing incompatibilities. Your only alternative is to develop them from scratch for your usual purposes. Two colleagues, both experienced research software engineers, will help you with the development to speed up the process. To help them get a clear idea of what you are going to build, for each software, define: 

 1. Purpose, scope and constraints. 
 
 2. Two functional tests the finished software must be able to pass.

#### b. Providing tests as extensively as possible (ideally through automated processes)

> *Narrative*: 

There are several types of software testing, which can be broadly categorized into the following categories:
  - Unit testing: Testing individual units or components of the software to ensure they function as intended.
  - Integration testing: Testing the integration of different components or modules of the software to ensure they work together as expected.
  - Functional testing: Testing the software's functionality to ensure it works as specified and meets the requirements.
  - System testing: Testing the entire software system to ensure it meets the requirements and works as intended. 
  - Exploratory testing: Ad-hoc testing performed by testers to discover new or unexpected issues in the software.
  - Regression testing: Testing the software after changes have been made to ensure the changes did not introduce new bugs or issues.
  - Non-functional testing: Testing the software's non-functional aspects, such as performance, security, usability, and compatibility.
  - Stress testing: Testing the software under extreme or unrealistic conditions to determine its performance and stability limits.
  - Acceptance testing: Testing the software to ensure it meets the customer's acceptance criteria and is ready for release.

Not all kinds of testing are necessary for every project.

>**Learning Experience** - *Discussion* 

!!! question "Discussion"

  Do you do test-driven development? Why/why not? 

>**Learning Experience** - *Exercise*: 

!!! example "Challenge 2"
  Think of a familiar case where test-driven development was not applied (or was not applicable, like in a fast-pace developing environment, early stages of development, prototyping, ...). Describe:

  - Two situations where a test was necessary and why.
  - Two situations where a test was prescindible and why.

!!! question "Brainstorming"
> What are the advantages of using tests?

> *Narrative*: 
> Complement previous brainstorming 

The advantages of testing are: 

  1. Helps ensure that when something is fixed, it will not break other things or if it does, it will not go unnoticed. 
  2. Ensure that the documented functionality is stable, as well as identifying potential bugs and/or issues.
  3. Essential for reproducibility
  4. Enhance the overall trust that the software will work as intended


#### c. Setting up Communication channels  

Setting communication channels allow users to: 

- Report any problems or pose questions about usage and documentation 
- Address issues/bugs.


> **Learning Experience** - *Discussion*. 

!!! question "Discussion"
  What is your preferred communication channel as a user? and as a developer? Why? 


??? abstract "Learning outcomes already covered in previos sections"

 2. For each activity, explain why it’s important. 

  a. Documenting how the software can be reliably used by people external to the development group or person  
   i. to ensure adoption/use of the software outside the original developer
  
  b. Providing tests as extensively as possible(ideally through automated processes 
   i. Helps ensure that when something is fixed, it will not break other things or if it does, it will not go unnoticed. 
   ii. Ensure that the documented functionality is stable, as well as identifying potential bugs and/or issues.
   iii. Essential for reproducibility
   iv. Enhance the overall trust that the software will work as intended 

  c. Setting up Communication channels
   i. Users to report any problems or pose questions about usage and documentation 
   ii. clarifying the process to address issues/bugs 
  

### 3. Identify the specific SMP questions that are relevant in this Phase. 


> *Narrative*: 
> 
SMP questions relevant to this phase: 

- What type of documentation is available, provided with the software and delivered under the same conditions? 
  - Documentation in general as well as README, API documentation, docstring in source code and tutorial in particular are relevant. 

!!! danger "Questions not mapped yet in the SMP"
  Some questions that belong here are still not mapped in the [SMP wizard](https://smw.ds-wizard.org/km-editor/editor/f311aeda-cff2-4155-b2f8-1208876d39ec/question-tags)

### 4. Using the ELIXIR SMW, fill in the appropriate information to each SMP question that is relevant to this Phase. 

> **Learning Experience** - *Exercise*: 

!!! example "Challenge 3"
  Go to the project in the [SMW](https://smw.ds-wizard.org/) and complete the previous questions for a piece of software.

