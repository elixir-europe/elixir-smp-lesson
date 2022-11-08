---
title: "Stage 1: Inception"
teaching: 10
exercises: 3
---

:::questions 
* What are the key decisions that need to be made during the Inception phase? 

* Why are them important?

::: 

:::objectives
* What is important at this stage and why (general)
* What are the SMP components (specific SMP questions) that are relevant here
* Describe what each of these components mean, require and imply
:::

This stage starts with the idea of the research project that includes software. In this stage theproposal for the project is written, planning and first steps for the software development are made.

### Learning Outcomes

 1. Describe **what** are the key decisions that need to be made during the Inception phase.  

 a. licence of the software  

 > *Narrative*: Explain what a license is. The license will determine the rules for access and use of the software. It is a legal document, usually composed by a lawyer.

:::instructor
[Open Source Development - An Introduction To Ownership And Licensing Issues
](http://oss-watch.ac.uk/resources/iprguide)
::: 


 >**Learning experience** 
 >
 >*Exercise*
 >The following challenges explore the **implications** of this component. 
 >Each one provides scenarios in which license becomes relevant. 

:::challenge
In the project we are developing, we want to use a very popular library that has a strong copyleft license, but we would like to distribute our project under a more permissive license. What can we do? 

:::solution
We cannot use that library, we have to find an alternative with a compatible license or adopt a strong copyleft license for our project. License governs reusing the software, with implications for the software integrating it.
::: 

:::

:::challenge
We developed our project, a command line program, and finally realeased it under GPL-3. Someone used that program in an application with a privative license. Is that legal? 

:::solution 
It is perfectly legal, since the applications code that uses my code is not actually being distributed. License can govern the public performance of a software.
::: 

:::


:::::challenge
We are a team of several people happily developing a software in a public GitHub repository. Since we are not ready to share our code yet, we did not add any license. Is this a good way to prevent anyone making copies or use our code?.  

:::solution 
In absence of a license, the code is under exclusive copyright, which means copying or using it comes with a risk of litigations and take-downs, including the very colaborators of the code! However, in this case, GitHub might be copying your repository and using it as stated in the GitHub Terms and Conditions. Any public GitHub repository can be forked by others users.
::: 

:::::

>### Useful resources:
>- Guides to assist in the election of a license:
>    - https://choosealicense.com/
>    - https://www.gnu.org/licenses/license-recommendations.html
>
>- [Clarifications on frequently asked questions regarding choosing a licenses and compilation of guides by the SSI](https://www.software.ac.uk/resources/guides/choosing-open-source-licence) 

   
b. where the software will be stored during development   

> **Learning experience**  
>
> *Exercise*: brainstorm which are the requirements for a system used to storage code while it is being developed.  

i. will determine how it can be accessed by others

:::discussion
Which are the possible requirements for a system used to storage code while it is being developed? 
:::

> *Narrative*: Explain the different code hosting options (gitlab, github, bitbucket, sourceforge, ...). Depending on the requirements, like privacy-related ones, some systems will be more suitable (GitLab private instance, for example). 

c. what kind of versioning system will be used  
- i. is used for tracking changes in the software

> *Narrative*: explain version control systems and available compatible hosting services (GitLab, GitLab).
>
> They very likelly fulfill all the requirements mentioned before in addition to others that can become useful in later stages.

- ii. serves as a mechanism for due diligence for software projects 

> One of the additional benefits of systems like git + GitHub/GitLab 

- ii. will narrow down available online services that can be used

>


d. what kind of input and output standards the software will have 



2. For each decision, explain **why** it’s important. 

    a. licence of the software 
    - i. will determine the rules for access and use of the software 

    b. where the software will be stored during development 
    - i. will determine how it can be accessed by others

    c. what kind of versioning system will be used 
    - i. is used for tracking changes in the software
    - ii. serves as a mechanism for due diligence for software projects
    - ii. will narrow down available online services that can be used to share code

    d. what kind of input and output standards the software will have

    - i. will greatly affect the level of adoption
    - ii. Choosing standards in the field will make it easier for adopters to integrate the tool in their own workflows and will 
    - iii. allow for reuse with their own datasets.
