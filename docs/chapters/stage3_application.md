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
- José Mª Fernández [:custom-orcid:](https://orcid.org/0000-0002-4806-5140)


!!! info 
  In this stage the software can be readily applied to all relevant data, still used mostly by the development team (or the lone developer). The primary focus at this stage is the quality assessment of the software, i.e. provide a battery of tests, ideally fully automated, that ensure valid execution and behaviour. Also, care should be given to providing proper instructions to assure the software can be easily installed and set up in common scenarios
 
## Learning Outcomes

### 1. Describe which are the main activities that take place during the Application phase. 

#### a. Documenting how the software can be reliably used by yourself in several months, by people external to the development group but related to the scientific field, or any person 

> *Narrative*: 

Proper documentation of software is critical for ensuring that it can be used reliably over time by various individuals. This is especially important in scientific fields, where research software is often developed to aid in the analysis of data.

One way to ensure that software is well-documented is to create a clear and detailed documentation. This documentation should include step-by-step instructions for how to use the software, as well as explanations of any key concepts or terminology that may be unfamiliar to users.

Additionally, it can be helpful to provide examples of how the software can be used to solve common problems or perform common tasks. These examples should be relevant to the scientific field in question and should be accompanied by clear explanations of the underlying processes and assumptions.

Finally, it is important to update the documentation regularly as the software evolves. This will ensure that users always have access to the most up-to-date information and will help to prevent confusion or errors caused by outdated instructions.

By taking the time to create comprehensive and up-to-date documentation, developers can ensure that their software is accessible and reliable for a wide range of users, including those outside of the development group.


> **Learning Experience** - *Exercise* 

!!! example "Challenge 1"

TO ADD

#### b. Providing tests as extensively as possible (ideally through automated processes)

> *Narrative*: 

As defined before in Stage 2, testing is a critical component of software development, as it helps to ensure that the software works as intended and is free of bugs or errors. Having the test defined for internal use, it is important to ensure that the software testing process is made available to the end users, such as through automated testing.

Automated testing involves creating scripts or programs that can automatically test different aspects of the software, such as its functionality, performance, and security. These scripts can be run repeatedly to ensure that the software is functioning as intended and that any changes or updates do not introduce new errors or bugs.

Automated testing can be especially helpful in large software projects, where manual testing can be time-consuming and prone to human error. By automating the testing process, developers can save time and reduce the risk of introducing new errors or issues, while have a systematic way of getting direct feedback from the end users.


>**Learning Experience** - *Discussion* 

!!! question "Discussion"

TO ADD

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

- Report any problems or pose questions about deployment, usage and documentation 
- Address issues/bugs.


> **Learning Experience** - *Discussion*. 

!!! question "Discussion"
  What is your preferred communication channel as a user? and as a developer? Why? 


??? abstract "Learning outcomes already covered in previos sections"

2. For each activity, explain why it’s important. 

   <ol type="a">
    <li>Documenting how the software can be reliably used by people external to the development group or person</li>
    <ol type="i">
        <li>To ensure adoption/use of the software outside the original developer</li>
    </ol>
    <li>Providing tests as extensively as possible (ideally through automated processes) </li>
    <ol type="i">
        <li>Helps to ensure that when something is fixed, it will not break other things or if it does, it will not go unnoticed.</li>
        <li>Ensure that the documented functionality is stable, as well as identifying potential bugs and/or issues.</li>
        <li>Essential for reproducibility</li>
        <li>Enhance the overall trust that the software will work as intended </li>
    </ol>
    <li>Setting up Communication channels</li>
    <ol type="i">
        <li>Users to report any problems or pose questions about usage and documentation.</li>
        <li>Clarifying the process to address issues/bugs: what it is expected to report, which technical details should be provided, the code of conduct, etc...</li>
        <li>Different user profiles require different communication channels. i.e. a potential developer and an end user could use different communication and reporting channels.</li>
    </ol>
  </ol>
  

### 3. Identify the specific SMP questions that are relevant in this Phase. 


> *Narrative*: 
> 
SMP questions relevant to this phase: 

- What type of documentation is available, provided with the software and delivered under the same conditions? 
  - Documentation in general as well as README, API documentation, docstring in source code, input and usage examples, and tutorial in particular are relevant. 

!!! danger "Questions not mapped yet in the SMP"
  Some questions that belong here are still not mapped in the [SMP wizard](https://smw.ds-wizard.org/km-editor/editor/f311aeda-cff2-4155-b2f8-1208876d39ec/question-tags)

### 4. Using the ELIXIR SMW, fill in the appropriate information to each SMP question that is relevant to this Phase. 

> **Learning Experience** - *Exercise*: 

!!! example "Challenge 3"
  Go to the project in the [SMW](https://smw.ds-wizard.org/) and complete the previous questions for a piece of software.

