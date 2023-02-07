---
tags:
    - Production
    - Stability
    - Scalability
---

{% include-markdown "../links.md" %}

# Stage 4: Production (production software working on real-world data in a scalable and stable manner)

**Authors:**

- Fotis Psomopoulos [:custom-orcid:](https://orcid.org/0000-0002-0222-4273)

!!! info

In this phase, the software is used to generate publishable research data in a consistent, stableand reproducible way. The software should be easily reusable by other researchers with their datasets. Often this is the time when the software is being deployed on a High-PerformanceComputing infrastructure (e.g. local cluster, supercomputer etc.) or a cloud infrastructure. To ensure the software can be easily and successfully deployed, soft and hard dependencies need to be captured (e.g. versions of libraries or packages, databases and other resources, listing required / recommended packages, etc). This is often done by bundling and packaging all necessary software through different approaches, including static binaries, software containers,virtual machines or any other solution that encapsulates the entire required environment. Specific dependencies on hardware (e.g. CPU optimisations, GPU model, etc) needed by the different execution profiles should also be documented clearly.

## Learning Outcomes

### 1. Describe **what** are the key considerations that need to be made aware during the Production phase.

#### a. ensure the (re-)use and reproducibility of the software

 > *Narrative*: Explain that (re-)use and reproducibility of the software are fundamental aspects of a research software, when considered ready for production phase.
 > The most crucial aspect here is to ensure the (re-)use and reproducibility of the software, by clearly documenting any OS/Software/hardware dependencies. 
 > This can be achieved through different methods (incl. registry and package managers, containerisation,etc.)
 
 >**Learning experience**
 >
 >*Exercise*
 > 
 >

!!! example "Challenge 1"


### 2. For each consideration, explain why it’s important.


:bulb: covered in the previous LO 
```
a. ensure the (re-)use and reproducibility of the software

Software often depends on libraries and their versions that may not be available on some systems. Packaging the software into easy-to-use forms (e.g. [R](https://www.r-project.org/) / [python](https://www.python.org/) / [conda](https://docs.conda.io/) packages, pre-compiled binaries, containers or virtual machines, etc.) can greatly facilitate its (re)use and adoption, as well as ensure (to an extent) its reproducibility
 ``` 




### 3. Identify the specific SMP questions that are relevant in this Phase.

> *Narrative*:  
> 
> Enumerate the questions: 
> 
> - Interoperability?


### 4. Using the ELIXIR SMW, fill in the appropriate information to each SMP question that is relevant to this Phase.

> **Learning Experience** 
> 
> *Exercise*: 
> 
> Go to the workspace you just created in the [SMW](https://smw.ds-wizard.org/) and complete the previous questions for a piece of software.




