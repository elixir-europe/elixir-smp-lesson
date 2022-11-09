---
title: "Introduction to ELIXIR Software Management Plan (SMP)"
teaching: 10
exercises: 2
---

# Overview

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
    1. Understand which parts of the SMP are critical for each Software Development Stage
    2. Understand the implications of the different choices provided in the SMP.
    3. Be able to fill in the required information across all sections of the SMP in the ELIXIR Software Management Wizard (SMW)

# Introduction
## Learning Outcomes
1. Explain what is the purpose of a management plan and why this is a good practice for Open Science.
2. List/Highlight what are the key differences between managing data and managing software.
3. Describe the five Software Development Stages.
4. Identify the two main groups of stakeholders for the ELIXIR SMP.
5. Access the SMW and create a project, i.e. a workspace where you can create your SMP 

## Learning Experiences
LO #1: Explain what is the purpose of a management plan and why this is a good practice for Open Science.  
LO #2: List the key differences between managing data and managing software.
 
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

**Narrative**
Data management is the practice of collecting, organising, storing, maintaining, and using data securely, efficiently and cost-effectively. Software developed during the course of research, like data, should be managed appropriately. Although general data management principles can be applied to software development, managing software consists in planning and leading the process of developing and publishing software, since its inception throughout all the phases of its planning, development, delivery, use, and publishing. A management plan is a comprehensive plan that describes the objectives of any given project, clearly defines roles and responsibilities, the strategies used to meet the objectives, and the methods used to measure performance (= the achievement of objectives/deliverables). It is a resource that can be used as a guideline in the initial phases of a project, as well as throughout its execution, thus ensuring that everything operates smoothly.
Data Management Plans (DMPs) are a cornerstone of good data management and are now considered a key element of Open Science practices. A DMP describes the data management life cycle for the data to be collected, processed and/or generated within the lifetime of a particular project or activity. A Software Management Plan (SMP) is a device wihch may help formalise a set of structures and goals that ensure the software is accessible and reusable in the short, medium and long term. Although it has a management perspective, the main advantage of an SMP is that it provides clear context to the software that is being developed. In that sense, it addresses several aspects of the software development process such as (a) supporting reproducibility and reusability of the software, (b) allowing funding agencies to have a better grasp of the envisioned development process (as well as the achieved milestones), (c) increasing the awareness of the existing community standards that can/should be used, and (d) ensuring that the software can be easily accessed by the wider community. DMPs and SMPs often come in the form of checklists. 
There are a few flavours of SMPs already available in one form or another. The Software Sustainability Institute (SSI) offers a very detailed checklist (Institute, 2018) that is further complemented by an online sustainability evaluation service (SES). Several journals (such as SoftwareX and the Journal of Open Source Software (JOSS)) have checklists that are expected to be filled in by the software authors before any submissions addressing most of the key points of an SMP. Finally, there are funding agencies (such as the Wellcome Trust) that expect a plan for the management of research output, including software, in submitted applications.

> **Reflection**: [here](https://www.software.ac.uk/resources/guides/software-management-plans) is an example of an SMP. Explore it and try to answer the following questions:  
> how could you implement it in the development process of your software? I.e., how could you use it?  
> How difficult would be to check whether your software meets all the recommandations provided in this SMP?  

_LO #3: Describe the five Software Development Stages._

**Narrative**

#### The ELIXIR Software Management Plan

A key downside of the aforementioned SMPs is that they tend to be rather complex, occasionally requiring deep technical knowledge of the software development process. In order to address these drawbacks, ELIXIR has designed a simplified version of an SMP, tailored for Life Science oriented projects but still general enough so as to be widely used. The primary goal of the ELIXIR SMP is to encourage wider adoption by Life Science researchers, and be as inclusive as possible to the various levels of technical expertise, while also having an explicit connection to the FAIR principles for Research Software (Hong et al., 2021,@lamprecht_towards_2020). A common theme in Life Science researchers is the wide differences in background expertise, with the vast majority of researchers being self-taught research software developers. Having an SMP with a relatively low barrier in technical knowledge, while maintaining all the best practices expected in research software development, may both encourage wider adoption of these practices as well as increase the awareness of the multiple aspects involved in research software development.  
In terms of structure, the ELIXIR SMP comprises seven areas relevant for software quality, each of which is composed of a **collection of targeted questions**. The main areas are **Accessibility**, **Documentation**, **Testing**, **Interoperability**, **Versioning**, **Reproducibility** and **Recognition**, and the questions vary in complexity and requirements. The seven areas, and therefore the questions, can be connected across the five distinct software stages: inception, construction, application, production, publication. 


> **Exercise**:  The five stages of software development are:    
> Stage 1: Inception (concept, proposal writing, planning and inception). 
> Stage 2: Construction (prototyping, construction and implementing core functionality). 
> Stage 3: Application (release and quality assessment). 
> Stage 4: Production (production software working on real-world data in a scalable and stable manner). 
> Stage 5: Publication (Publishing software and/or research results ob- tained with the software). 
> Think about research software you develop (or is developed in your group by others): can you clearly recognise the five phases? When you start a new software project, do you plan its development according to the five stages? When there are more than one contributor to the project, do you assign roles according to the stages?
> **Solution**: Write your answers on a shared document. The instructor discuss most interesting answers.
> 

**Narrative**: Alignment of ELIXIR SMP seven areas relevant for software quality to Software Development Stages


> **Exercise**: The main areas of the ELIXIR SMP are: Accessibility, Documentation, Testing, Interoperability, Versioning, Reproducibility, and Recognition. Using the table provided in the shared document (see below)

| Stage                |     area(s)  |  why |
|----------------------|:------------:|-----:|
| Stage1: inception    |              |      |
| Stage 2: construction|              |      |
| Stage 3: application |              |      |
| Stage 4: production  |              |      |
| Stage 5: application |              |      |
> 
> **Solution**: 
> 

_LO #4: Identify the two main groups of stakeholders for the ELIXIR SMP._ 

> **Exercise**:
> **Solution**:
> 

_LO #6: Access the SMW and create a project, i.e. a workspace where you can create your SMP_

> **Exercise**:
> **Solution**:
> 

## Notes on content

- Personas based on the SMP Stakeholders: Group 1 (Users / Benefiters / Enforcers) and Group 2 (Adopters)
- Make a list of potential stakeholders, and the learners have to identify which group each belongs to.

