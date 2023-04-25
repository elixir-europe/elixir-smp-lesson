---
tags:
    - Introduction
    - Software Management Plan
    - Training
---

{% include-markdown "../links.md" %}

# Introduction to ELIXIR Software Management Plan (SMP)

## Overview

1. Target audience (probably similar to the 4OSS lesson)
    1. Research software Engineers (RSEs)(people writing the software need to be aware of the basic principles to follow)
    2. Researchers developing software (people writing the software need to be aware of the basic principles to follow)
    3. Principal Investigators / Group Leads (they can use the SMP to ensure compliance with best practices)
    4. Project managers (they have a vested interest that in-house research output meets criteria and is sustainable)
2. Levels:
    1. Remember
    2. Understand
    3. Apply

3. Prerequisites:
    1. To have a working understanding of the research software development process
    2. Coding experience is useful, but not necessary

3. Goals
    1. Understand which parts of the SMP are critical at various points of the Software Development process.
    2. Understand the implications of the different choices provided in the SMP.
    3. Be able to fill in the required information across all sections of the SMP in the ELIXIR Software Management Wizard (SMW)

## Introduction

### Learning Outcomes
1. Explain what is the purpose of a management plan and why this is a good practice for Open Science.
2. List/Highlight what are the key differences between managing data and managing software.
3. Identify the two main groups of stakeholders for the ELIXIR SMP.
4. Describe the five Software Development Stages.
5. Access the SMW and create a project, i.e. a workspace where you can create your SMP 

### LO: Explain what is the purpose of a management plan and why this is a good practice for Open Science.  
### LO: List the key differences between managing data and managing software.
 
#### Management plans
**Questions**:   
    - What is a Management Plan?   
    - Why a Management Plan?   
    - What are the differences between managing data and managing software?  
    - What is the difference between a DMP and a SMP?  
    - (Can we deal with software in the same way as data?) (Use the differences in FAIR principles as an example.) --> to be removed?  

> **Exercise**: in groups. Discuss: 
> 1) what could be the purpose of a management plan (in general)?    
> 2) what could be the purpose of a Data Management Plan?   
> 3) what could be the purpose of a Software Management Plan?
> **Solution**: each group summarises the answers to the three questions and write them on sticky notes for later use.

Data management is the practice of collecting, organising, storing, maintaining, and using data securely, efficiently and cost-effectively. Software developed during the course of research, like data, should be managed appropriately. Although general data management principles can be applied to software development, managing software consists in planning and leading the process of developing and publishing software, since its inception throughout all the phases of its planning, development, delivery, use, and publishing. A management plan is a comprehensive plan that describes the objectives of any given project, clearly defines roles and responsibilities, the strategies used to meet the objectives, and the methods used to measure performance (= the achievement of objectives/deliverables). It is a resource that can be used as a guideline in the initial phases of a project, as well as throughout its execution, thus ensuring that everything operates smoothly.
Data Management Plans (DMPs) are a cornerstone of good data management and are now considered a key element of Open Science practices. A DMP describes the data management life cycle for the data to be collected, processed and/or generated within the lifetime of a particular project or activity. A Software Management Plan (SMP) is a device wihch may help formalise a set of structures and goals that ensure the software is accessible and reusable in the short, medium and long term. Although it has a management perspective, the main advantage of an SMP is that it provides clear context to the software that is being developed. In that sense, it addresses several aspects of the software development process such as (a) supporting reproducibility and reusability of the software, (b) allowing funding agencies to have a better grasp of the envisioned development process (as well as the achieved milestones), (c) increasing the awareness of the existing community standards that can/should be used, and (d) ensuring that the software can be easily accessed by the wider community. DMPs and SMPs often come in the form of checklists. 
There are a few flavours of SMPs already available in one form or another. The Software Sustainability Institute (SSI) offers a very detailed checklist (Institute, 2018) that is further complemented by an online sustainability evaluation service (SES). Several journals (such as SoftwareX and the Journal of Open Source Software (JOSS)) have checklists that are expected to be filled in by the software authors before any submissions addressing most of the key points of an SMP. Finally, there are funding agencies (such as the Wellcome Trust) that expect a plan for the management of research output, including software, in submitted applications.

> **Reflection**: [here is an example of an SMP](https://www.software.ac.uk/resources/guides/software-management-plans). Explore it and try to answer the following questions:  
> how could you implement it in the development process of your software? I.e., how could it be used?  
> How difficult would be to check whether your software (or software developed in your group) meets all the recommandations provided in this SMP?  

### LO: Identify the two main groups of stakeholders for the ELIXIR SMP

#### SMP stakeholders

> **Exercise**: Who are the stakeholders involved in SMPs? How would this role use the SMP? 
> The group make a list of potential stakeholders involved in SMPs. Who may be potentially interested in using an SMP? Why?   
> One first example of stakeholder is a research software developer. Could you identify other profiles? Try to identify at least another one.
> Use the table template in the shared document (see below):

| Stakeholders                |    How the stakeholders would use the SMP   |  
|:---------------------------:|:-------------------------------------------:|
|Research software developers| The person writing the software needs to be aware of the basic principles to follow. They would use the SMP as a guide to implement best practices in software development efforts| 
|                            |                                             | 
|                            |                                             | 

> **Solution**: The group discusses and the instructor facilitates the discussion.
>
> We identified two main stakeholders’ groups corresponding to users and adopters. In addition, we defined a group of distinguished personas that are out of the scope of the SMP’s stakeholders, specifically the (a) **software users** who might also be contributors (e.g. by submitting bugs), and (b) the **end-users** of the software, who have no involvement with the software development process.
>
> **Group 1: Users / Benefiter / Enforcers**
This group includes stakeholders that require access to the SMP for a given software, but are not responsible for filling it in.
> *Funders (e.g ELIXIR, Wellcome Trust)*
> – Use the SMP in order to assess whether a software fits the funding requirements (e.g adhere to FAIR principles).  
> – Evaluate if the proposal addresses essential aspects of Research Software Management (incl. “scoring” the software based on their alignment to best practices).  
> – Ensure that the software is well-done (reproducible, reusable/open, robust) and funding is not wasted.    
> *Policy Makers (e.g. European Commission can use SMPs as a way of “enforcing” their recommendations and policies)*  
> – Use the SMP as a basis, inspiration or requirements for their guidelines or policies in their domain of action.  
> *Service providers* (e.g. Compute Platform, PaaS, IaaS, SaaS use an SMP in order to ensure compatibility to the minfrastructure offered).  
> – A service provider would use the SMP to assess if the software meets the qualityand reproducibility standards of the platform. The SMP can therefore also be used as a requirement.   
> – To assess the level of maintenance effort necessary to provide access to the software on their platform 
> *Software manager not necessarily contributing to the software - making sure principles are enforced*.  
> – To assess if the software is reliable for ongoing research projects or during the conceptualisation phase of new research projects.   
> – To assess if the development process of software is compatible with the timeframe of research projects.  
> *Publishers* e.g. F1000 should use an SMP in order to ensure software “quality” / availability?).  
> – To ensure research published can be reproduced by peers with the software that was used to generate the results.  

**Group 2: Adopters**
> This group includes stakeholders that are primarily responsible for filling a SMP for a given software.   
> *Developer/Researcher* the person writing the software needs to be aware of the basic principles to follow.  
>
> – As a guide to implement best practices in ongoing or new software development efforts.  
> – As a quality filter when considering if existing software meets the needs for new research projects.  
>
> *PI of a group* can use the SMP to ensure compliance with best practices.  
> – To inform the proposal writing process.  
> – As a guide to ensure any software developed in the group meets an acceptable quality and technical level in order to maximise the chances of adoption.  
> – To ensure the team composition supports skills necessary to develop software according with best practices.  
> – To ensure software can be reused in the future, enabling building on vs reinventing.   
> – To increase the bus factor of the project.  
> – As a checklist prior to publication.  
> 
> *Organisation (Fundee)* Vested interest that in-house research output meets criteria and is sustainable - select appropriate SMP. This is the instance where an Institution is attempting to create a policy for internal use (ensure that any “badged” research software produced under it, aligns to the expectations of the selected SMP).   
> – To ensure there is supporting infrastructure at the organisation level.  
> – To ensure there is a training program / supporting personnel, supporting skillnecessary to implementing the SMP (e.g. software stewards).  

### LO: Describe the five Software Development Stages.

#### The ELIXIR Software Management Plan

A key downside of the aforementioned SMPs is that they tend to be rather complex, occasionally requiring deep technical knowledge of the software development process. In order to address these drawbacks, ELIXIR has designed a simplified version of an SMP, tailored for Life Science oriented projects but still general enough so as to be widely used. The primary goal of the ELIXIR SMP is to encourage wider adoption by Life Science researchers, and be as inclusive as possible to the various levels of technical expertise, while also having an explicit connection to the FAIR principles for Research Software (Hong et al., 2021,@lamprecht_towards_2020). A common theme in Life Science researchers is the wide differences in background expertise, with the vast majority of researchers being self-taught research software developers. Having an SMP with a relatively low barrier in technical knowledge, while maintaining all the best practices expected in research software development, may both encourage wider adoption of these practices as well as increase the awareness of the multiple aspects involved in research software development.  
In terms of structure, the ELIXIR SMP comprises seven areas relevant for software quality, each of which is composed of a **collection of targeted questions**. The main areas are **Accessibility**, **Documentation**, **Testing**, **Interoperability**, **Versioning**, **Reproducibility** and **Recognition**, and the questions vary in complexity and requirements. The seven areas, and therefore the questions, can be connected across the five distinct software stages: inception, construction, application, production, publication. 


> **Exercise**:  The five stages of software development are:    
> Stage 1: Getting started (requirements, specifications, planning)  
> Stage 2: Construction (prototyping, construction and implementing core functionality)   
> Stage 3: Application (release and quality assessment)  
> Stage 4: Production (production software working on real-world data in a scalable and stable manner)   
> Stage 5: Publication (Publishing software and/or research results obtained with the software)   
> Think about research software you develop (or is developed in your group by others): can you clearly recognise the five phases? When you start a new software project, do you plan its development according to the five stages? When there are more than one contributor to the project, do you assign roles according to the stages?
> **Solution**: Write your answers on a shared document. The instructor discuss most interesting answers.
> 

> **Exercise**: Alignment of ELIXIR SMP seven areas relevant for software quality to Software Development Stages.  
> The main areas of the ELIXIR SMP are: Accessibility, Documentation, Testing, Interoperability, Versioning, Reproducibility, and Recognition. Using the table provided in the shared document (see below), try to align the areas to the five development stage. This exercise will be done in groups.

| Stage                |   area(s)  | reasons |
|----------------------|:----------:|--------:|
| Stage1: inception    |            |         |
| Stage 2: construction|            |         |
| Stage 3: application |            |         |
| Stage 4: production  |            |         |
| Stage 5: application |            |         |
> 
> **Solution**: Compare and discuss the tables created by different groups.
> 

> **Exercise**: At which stage of the software development the stakeholders would need the SMP most?
> For each group of identified stakeholders try to answer the questions: at which stage of the software development the stakeholders would need the SMP most? Why? You can use the table template below

| Stakeholders        |   Stage  |  Why? |
|:-------------------:|:--------:|:-----:|
|Funders              |          |       |
|Policy Makers        |          |       |
|Service providers    |          |       |
|Software manager     |          |       |
|Publishers           |          |       |
|Developer/Researcher |          |       |
|PI of a group        |          |       |
|Organisation (Fundee)|          |       |

>**Solution**:

| Stakeholders        |   Stage  | 
|:-------------------:|:---------|
|Funders              |Depending on the funding scheme; it’s usually at the Inception stage (Stage 1), but it can also be at the Production stage (Stage 4). In all cases, this role would expect the full SMP filled in (either defining what is already in place, or the plan to do this).| 
|Policy Makers        |During early phases of the development of similar policies|
|Service providers    |When adopting or integrating software into existing platforms or in early stages of the decision process.|
|Software manager     |While software is at its early stages of development (application or younger). The more mature a software the less likely that it will pose an obstacle to research goals.|
|Publishers           |At any stage when authors submit software to be published. e.g. checklist used by JOSS. A publisher may also require that software is in the “production” or “publication” stage to be considered for publication.|
|Developer/Researcher |At all stages, from inception to publication|
|PI of a group        |At all stages, from inception to publication|
|Organisation (Fundee)|At all stages|


### LO: Access the SMW and create a project, i.e. a workspace where you can create your SMP_

> **Exercise**: Access the SMW and create a project
> Go to the [Software Management Wizard webpage](https://smw.ds-wizard.org/) and create a new SMP custom project (not from Project Template).
> 
> **Solution**:
> On the SMP webpage, click on Projects on the left menu. You will end up on a page where you can create your SMP project. Give a name to your project and choose the Software Mangement Plan as Knowledge Model.  
> The list of stages will appear. If and only if you want to fill in the SMP for a given stage(s), select it (them). However, if you want to use all questions, do not select any stage.
> When you're done, click on Save.
> In answering questions, you may want to use the TODO and/or "comment" functionality. You may add a TODO if you want to remember, e.g., revising one or more of your answers.
> >




