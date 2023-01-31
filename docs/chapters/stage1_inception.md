---
tags:
    - Inception
    - License
    - Versioning
    - Standards
---

{% include-markdown "../links.md" %}

# Stage 1: Inception

**Authors:**

- Eva Martín del Pico [:custom-orcid:](https://orcid.org/0000-0001-8324-2897)

!!! info

    This stage starts with the idea of the research project that includes software. In this stage the proposal for the project is written, planning and first steps for the software development are made.

## Learning Outcomes

### 1. Describe **what** are the key decisions that need to be made during the Inception phase.  

#### a. licence of the software  

 > *Narrative*: Explain what a license is. The license will determine the rules for access and use of the software. It is a legal document, usually composed by a lawyer.
 > A software license is a legal agreement that outlines the terms and conditions under which a piece of software can be used, distributed, and modified. It's essentially a set of rules that govern how the software can be used and by whom.
 >  When it comes to software licenses, open source licenses are those that allow the source code of the software to be freely distributed and modified. This is in line with the principles of open science, as it allows anyone to access the software and use it for their own purposes. FAIR science, on the other hand, focuses on making sure that scientific data and research can be easily found, accessed, and used by others. A software license that promotes FAIR science would therefore allow others to easily access and use the software, in line with the principles of openness and accessibility.
 > Note for instructor: [Open Source Development - An Introduction To Ownership And Licensing Issues](https://oss-watch.ac.uk/resources/iprguide)

 >**Learning experience** 
 >
 >*Exercise*
 >The following challenges explore some _implications_ that choosing one license or another can have. They highlight different aspects of software that licese can govern. 
 >

!!! example "Challenge 1"

    In the project we are developing, we want to use a very popular library that has a strong copyleft license, but we would like to distribute our project under a more permissive license. What can we do?
 
    ??? danger "Solution"

        We cannot use that library, we have to find an alternative with a compatible license or adopt a strong copyleft license for our project. License governs reusing the software, with implications for the software integrating it.

!!! example "Challenge 2"

    We developed our project, a command line program, and finally realeased it under GPL-3. Someone used that program in an application with a privative license. Is that legal?

    ??? danger "Solution"

        It is perfectly legal, since the applications code that uses my code is not actually being distributed. License can govern the public performance of a software.

!!! example "Challenge 3"

    We are a team of several people happily developing a software in a public GitHub repository. Since we are not ready to share our code yet, we did not add any license. Is this a good way to prevent anyone making copies or use our code?.

    ??? danger "Solution"

        In absence of a license, the code is under exclusive copyright, which means copying or using it comes with a risk of litigations and take-downs, including the very colaborators of the code! However, in this case, GitHub might be copying your repository and using it as stated in the GitHub Terms and Conditions. Any public GitHub repository can be forked by other users.

>*Narrative*
>Useful resources:
>- Guides to assist in the election of a license:
>    - https://choosealicense.com/
>    - https://www.gnu.org/licenses/license-recommendations.html
>
>- [Clarifications on frequently asked questions regarding choosing a licenses and compilation of guides by the SSI](https://www.software.ac.uk/resources/guides/choosing-open-source-licence) 

   
#### b. where the software will be stored during development   
##### i. will determine how it can be accessed by others 

> **Learning experience**  
>
> *Exercise*: brainstorm which are the requirements for a system used to store code while it is being developed.  

> *Narrative*: Explain the different code hosting options (gitlab, github, bitbucket, sourceforge, ...). 
> Depending on the requirements, like privacy-related ones, some systems will be more suitable (GitLab private instance, for example). 

##### ii. will determine how it will preserved

> *Narrative*:
> Self hosted solutions will require us to explicitly push releases of the software source code to either internal backup systems or third party services (osf.io, zenodo, B2SHARE, SSI).
> Third party public solutions, like GitHub, eases the preservation through the collaboration with Zenodo, automating most of the process.
> Public preservation solutions usually provide public, permanent identifiers.

#### c. what kind of versioning system will be used  

##### i. is used for tracking changes in the software
##### ii. serves as a mechanism for due diligence for software projects 
##### iii. will narrow down available online services that can be used

> *Narrative*: 
> Version control systems are tools that allow developers to keep track of the changes made to a piece of software over time. These systems create a history of all the changes that have been made to the software, and make it easy for developers to roll back to an earlier version if necessary.
> 
> GitLab and GitHub are two popular hosting services for version control systems. They allow developers to store their code and track changes to it using tools like Git. Both GitLab and GitHub offer a range of features that make it easy for developers to collaborate on projects and manage their code. For example, they both allow users to create branches (i.e. different versions) of their code, review and merge changes made by others, and track issues and bugs.
> 
> In layman's terms, you could think of a version control system as a way of keeping track of different versions of a project, like a book. Each time you make a change to the book, the version control system records the change and saves a new version of the book. This makes it easy to go back and see how the book has changed over time, and to revert to an earlier version if necessary. GitLab and GitHub are like the libraries where you can store and manage your books (i.e. code projects). They provide the tools you need to collaborate with other writers, keep track of changes, and make sure your book stays organized.
> 
> Explain version control systems and available compatible hosting services (GitLab, GitLab). Comparative table: https://chiplicity.readthedocs.io/en/latest/_images/VersionControlSystems.png
> They very likelly fulfill all the requirements mentioned before. In addtition, some of them are not only hosting services, but offer a wide range of additional tools (issues, docker/package registry, CI/CD, pages, etc). 
> 
> Advantages of version control:
> - Systematic tracking changes in the software -> version control != version history 
> 
> https://assets-global.website-files.com/5ff3926f03b3ba043ed639d1/601f3c78397f41080913a10e_5ea8b3a73bda8c4a33bb47d0_version-history-comparison-chart.jpeg 
> 
> - Mechanism for due diligence for software projects 
> 
> However:
> - The election of the hosting service can limit the options of version control systems -> some repository hosting services like BitBucket only support Git and Mercurial


#### d. what kind of input and output standards the software will have 

##### i. will greatly affect the level of adoption
##### ii. Choosing standards in the field will make it easier for adopters to integrate the tool in their own workflows and will 
##### iii. allow for reuse with their own datasets.

> **Learning experience**
> 
> Discussion: What are the advantages of using standard data formats?
> 
> Solution:
> (among others) 
> 
> - Data reformatting to meet custom data formats comes with high risk of introducing errors.
> - There are libraries to effectively handle common data formats without risk of truncating data.
> - Easier to integrate with other software and use with their own datasets, so increased adoption by users.

> Exercise: 
> Suppose there is no standard format suitable for the tool you are building, how do you reduce the impact of the points raised before?
> Solution:
> (among others)
> 
> - Create a format specification a register it in FAIRsharing -> makes the format public, providing identifier, contact, etc
> - Use a schema to describe the format (machine readable representation) -> facilitates users the task of transforming their data to my custom format
> - Provide a validator for my format -> facilitates users the task of transforming their data to my custom format
> - Provide plenty of data examples for realistic use cases


### 2. For each decision, explain **why** it's important. 
:bulb: covered in the previous LO 
```
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
 ``` 
 
### 3. Identify the specific SMP questions that are relevant in this Phase. 

> *Narrative*:  
> 
> Enumerate the questions: 
> 
> - Accessibilty 1. What is the name of the software? 
> - Accessibility 2. How can the software be accessed by third parties? 
> - Accessibility 3. Does your software have a license? 
> - Interoperability 1. Do you use existing and standard input/output formats? 
> - [Not covered in lesson] Interoperability 2. (?) What programming languages are you using in your project? 
> - Versioning 1. Do you use a version control system? 
> - [Not covered in lesson] Versioning 2. Do you use Semantic Versioning? 

### 4. Using the ELIXIR SMW, fill in the appropriate information to each SMP question that is relevant to this Phase. 

> **Learning Experience** 
> 
> *Exercise*: 
> 
> Go to the workspace you just created in the [SMW](https://smw.ds-wizard.org/) and complete the previous questions for a piece of software.

