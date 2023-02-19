---
tags:
    - Publication
    - Registries
    - Repositories
    - Changelog
---

{% include-markdown "../links.md" %}

# Stage 5: Publication

**Authors:**

- Johan Gustafsson
- Leyla Jael Castro [:custom-orcid:](https://orcid.org/0000-0003-3986-0510)

!!! info

    At this stage the software is ready to be used and generate the intended results. It is a good practice to also create a first release at this point (and then every time that the software is upgraded and new, revised or improved functionality is added). Independent from the publication of research results, the software itself should also be published in a software-oriented journal, or deposited to a software archive. In addition, it is a good practice to register your software in a community-oriented software registry.


## Learning Outcomes

### 1. Describe **what** are the key decisions that need to be made during the Publication phase.  

#### a. Document the way people should cite the software

> *Narrative*: Explain that including citation information gives recognition to those participating in the development and mention some possible options.
> 
> Similar to a scientific article, a software also has a title, a description, and co-authors (i.e., people involved in the development from its conception to its deployment), and all of those elements are part of a software citation. 
> Software citation should be included for the code source and releases (different releases can involve different co-authors) by using a [CFF file]( https://citation-file-format.github.io/), [bibtex]( http://www.bibtex.org) of JSON-LD (for instance following [CodeMeta]( https://codemeta.github.io/) or [Bioschemas Computation Tool]( https://bioschemas.org/profiles/ComputationalTool) specifications).

> **Learning experience**

> *Exercise* 

!!! example "Challenge 1"

    Create a CFF file for any software you have participated in the development. Remember to include ORCIDs for the co-authors.
    
    ??? danger "Solution"
    
        ```
        cff-version: 1.2.0
        message: "If you use this software, please cite it as below."
        authors:
        - family-names: "Doe"
          given-names: "Jane"
          orcid: "https://orcid.org/0000-0000-0000-0000"
        - family-names: "Dude"
          given-names: "John"
          orcid: "https://orcid.org/0000-0000-0000-XXXX"
        title: "My awesome project"
        version: 1.0.0
        url: "https://github.com/example-group/example-repo"
        ```

!!! example "Challenge 2"

    Find any repository in GitHub without citation information. Are citation files a common practice in your team?
    
    ??? danger "Solution"
    
        There are many :worried:
        If any of your repos fall in the no citation bag, please start adding citation information now :relaxed:

!!! example "Challenge 3"

    Discuss with your peers who should be included as co-author for a software. What practices are followed in your team?
    
    ??? danger "Solution"
    
        Be aware that co-authorship practices might change from team to team. If some roles are not included as co-authors, it is a godd practice to still name them in the software repositories as contributors recognising their role in the development.

#### b. Create a release
> *Narrative*: Explaing what a release is and what elements should be present.
> 
> Whenever a software has been upgraded with some additional, revised or improved functionality, it is a good practice to create a new release, accompanied by a CHANGELOG explaining what is new wrt the previous release.

> **Learning experience**

> *Exercise*

!!! example "Challenge 1"

    Brainstorm reasons for creating releases and maintaining a CHANGELOG. Why is this necessary even if version control is being used for development?
    
    ??? danger "Solution"
    
        Reasons to use CHANGELOG, including explanation of the types of changes you might record in the log. Comments on whether or not CHANGELOG are also needed outside releases.

#### c. Decide where to publish your software/release

> *Narrative*: Explain options to publish/deposit software.
> 
> Whether a journal-style or a deposition is chosen, either way software/releases should be published. Even if the source code is not open, it is still useful to let the world know about the existence of a pieace of software. 

> **Learning experience**

> *Exercise*

!!! example "Challenge 1" 

    Make a list of your key drivers/requirements when publishing your software. Some publishing platforms for software include software-oriented journals (e.g., [Journal of Open Source Software (JOSS)](https://joss.theoj.org/), [Software X](https://www.sciencedirect.com/journal/softwarex), BioMedCentral Software publications --see [software at the Journal of Biomedical Semantics](https://jbiomedsem.biomedcentral.com/submission-guidelines/preparing-your-manuscript/software), [Bioinformatics Application Notes](https://academic.oup.com/bioinformatics/pages/instructions_for_authors#Types%20of%20Manuscript) --although not exlusive for software), and software archives (e.g., [Software Heritage Foundation](https://www.softwareheritage.org/), [Zenodo](https://zenodo.org/) --although not exclusive for software) Is it authorship on a primary publication, findability, reusability, contributing to a community, something else? Which publishing platforms align closely with your drivers/requirements? do you know the expectations of your research community? Discuss with peers.

    ??? danger "Solution"
    
        A list of your requirements and which publication / registration / deposition options match that requirement best

#### d. Create persistent, global and unique identifiers that point to each released version of the software 

> *Narrative*: Outline some options for generating persistent identifiers for software and the sort of identifiers that exist.
>
> Somehow this goes hand-in-hand with "where to publish your software" as some kind of identifier will be assigned to your software/release in the examples given for platforms where to publish software. There are two main kind of identifiers, intrinsic (e.g., hashcode calculated from the source code) and extrinsic (assigned by the platform where the software is published/deposited).

> **Learning experience**

> *Exercise*: 

!!! example "Challenge 1" 

    Persistent identifiers usally relate directly to the location you publish or deposit your software. Based on your the examples listed above, which persistent identifier method is immediately available to you? Discuss why this does or does not meet your expectations (i.e., your list of requirements for publishing). If not, discuss what your other options are for generating an identifier, and the potential benefits of each.

    ??? danger "Solution"

        Pros and cons of the different alternatives to identify software/releases. Hint: depending on your requirements, you might want to go for multiple publishing platforms.

#### e. Register your software in a community-driven registry

> *Narrative*: Outline some options to register software.
> 
> Community-driven registries will make your software even more findable, specially for your own community. 
> Communities can be broad, e.g., research software engineers, specific to a particular purpose, e.g., used for machine learning purposes, specific to a particular community, e.g., bioinformaticians.

> **Learning experience**

> *Exercise*: 

!!! example "Challenge 1" 

    List some software registries that your are aware of.

    ??? danger "Solution"

        Two examples are [Research software directory](https://research-software-directory.org/) and [bio.tools](https://bio.tools/)

### 2. For each decision, explain **why** it's important. 

:bulb: covered in the previous LO 

```
a. Citation
- Essential to communicate how the authors want the work to be referenced by their peers, and lead the way to acknowledgement and recognition of their effort
- People involved in the development get credit for it
- Regardless of the status of your software (none of multiple releases), people will be aware on how to cite your software

b. Releases
- Releases and CHANGELOGs contribute make them easier to understand the lifecycle of medium- and long-term software developments, improving traceability
- Even for short-term developments, releases are a good practice as they provide a version "frozen" in time corresponding to a particula status of the software lifecylce
- CHANGELOGs are useful to communicate changes, developers and users should have enough information (e.g., through the CHANGELOG file) to assess the impact of the changes on ongoing projects that rely on the software

c. Formal publication
- Journal-like platforms to publish software usually provide feedback at the time of submission, i.e., peer-reviews which could help improve narrative and scope
- Deposition platforms contribute to preservation and preservation contributes to reproducibility (together with the releases --"frozen" versions of your software)

d. PIDs
- Researchers need to be able to find (via the persistent identifier) a specific version of software that has been used to generate published results. This is crucial in order to facilitate reproducibility of research results.

e. Registries
- Registries make it easier to find your software, particularly for communities of practice
- Registries collect some metadata about your software, making it easier to, e.g., connecting it to other digital objects and make them available to aggregators
- Community-driven registries could also help you learn some of the expectations of your own community

```

### 3. Identify the specific SMP questions that are relevant in this Phase. 

> *Narrative*:  
> 
> Enumerate the questions: 
>
> - Documentation 1.a.5. Release notes
> - Documentation 1.a.7. CHANGELOG
> - [Not covered in the lesson] Versioning 2. Do you use semantic versioning?
> - Reproducibility 1. Do you provide releases of your software?
> - Recognition 1. Do you include citation information (i.e. how to cite your software in the form of citation.cff, codemeta.json or bibtex)?
> - Recognition 2. Do the releases have a persistent global unique identifier (such as release on Zenodo with DOI, snapshot or/and release referenced on Software Heritage with SWHID)?
> - Recognition 3. Does the citation information contain ORCIDs of (at least one of) the authors?
> - Recognition 4. Is the software registered in a domain-specific registry

### 4. Using the ELIXIR SMW, fill in the appropriate information to each SMP question that is relevant to this Phase. 

> **Learning Experience** 
> 
> *Exercise*: 
> 
> Go to the workspace you just created in the [SMW](https://smw.ds-wizard.org/) and complete the previous questions for a piece of software.
