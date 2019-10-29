# Script

I'm Will Furnass and I'd like to propose a SSI fellowship around improving researchers' and PIs' understanding of the value of software packaging.
++++
A little about me.

I work in and help run the Research Software Engineering team at the University of Sheffield.
/
I mainly work on paid-for research software and infrastructure projects with groups across the University including central IT
and support other team members in doing this.
Projects are really varied: 
 - with some I develop software for researchers, 
 - with others I help researchers develop software.  
 - Some involve building sustainable ecosystems around existing software (packaging, testing, docs).  
 - Others involve taking sustainable software and building services from it e.g. web services or HPC workflows.
/
To complement this project work my team also runs a free Code Clinic (surgery), through which we've learned quite a bit about the common computing challenges/questions that researchers encounter.
/
We also develop and deliver training.  For example:

  * I'm a certified Carpentries instructor and have also 
  * developed and delivered my own high-performance Python workshop

We also engage with various national and regional bodies to share ideas, establish collaborations and promote activities:
/
  * I'm part of the RSE Leaders Network and N8 Centre for Computationally Intensive research, which both discuss and implement strategies for training, amongst other things.
  * and I helped organise the 2018 UK RSE conference (I was a talks chair)

/
My team also disseminates information about our projects and processes via our blog.

++++

Before becoming an RSE, 

I provided support to the users of our high-performance computer clusters.
A big part of this was listening to researchers, finding solutions/suggestions that would address their needs and communicating those ideas in a meaningful way
/
Before that I was a researcher in civil engineering, during which time I developed numerical models using Python.  This made me aware of the needs of researchers and the research lifecycle.
/
I also have a Computer Science degree, which equipped me with a sound technical foundation.

+++

So, my plans for the fellowship.

Take Robin, a typical researcher.  Thanks to the Carpentries and other initiatives they now know the basics of version control and testing, and they use both when working with Jupyter Notebooks and smaller scripts.  But

  * How can they structure the software they develop as it evolves to
    * make parts reusable and 
    * make version control and testing easier?
/
There's currently insufficient introductory guidance on how to structure research software projects
    - How/when to extract common functionality from Notebooks by
        - creating modules from collections of functions/classes 
        - and organise modules within a directory tree

+++

My thesis is that basic knowledge of why, when and how to create software packages would be useful here.

    - Packaging provides structure for incorporating testing/documentation frameworks/tools
    - and for meaningfully versioning software/analysis components

---

### Activities

I propose four activities:

One: a workshop targeting RSEs. We would discuss
a) common challenges researchers encounter as research software grows larger and barriers to entry for development tooling, 
b) current best practices and new ideas around how researchers could develop reproducible workflows by linking their packages, notebooks and data repositories.
c) how packaging approaches fit in with typical 'private then public' research workflow.
/
This could be promoted via the 
- SSI, RSE Society and N8 Centre for Computationally Intensive Research

and could possibly be held at the Collaborations Workshop 2020.

---

2 + 3: two day-long Carpentries-style workshops with researchers, one for Python users, one for R users, where 

- we explore why and how they could package existing code in idiomatic ways, including when in the research lifecycle this might be useful
Very little software in 2019 should be an island, so we would also cover managing dependencies.
In the second half of the workshop, we would explore how, once code has been packaged, it's much simpler integrating test frameworks and mechanisms for building and possibly auto-generating documentation.  This would be high-level with simple examples and sign-posts to external resources.
Participants should come away with non-exhaustive checklists that they can work through when considering packaging in future.

---

The final workshop would target PIs: by making them aware of the benefits of modularisation and packaging, plus equipping them with understanding of the most relevant tools, concepts and terminology they should then be able to audit the software their researchers produce, allowing them to encourage sustainable development practices.  

There would need to be some basic coverage of version control methods and tools.  

Academics would come away with checklists that would allow them to check whether some scripts are actually packaged and whether a package has tests/integrated documentation.  


The workshop could also sign-post training that PIs could recommend to their researchers.  

It would be perhaps only 3 hours so as to get buy-in from busy academics.

---

Outputs

- The developed materials for the R, Python and PI workshops would be made openly-available to permit the workshops to be re-run in their entirety.  
    - They could form new Carpentry lessons and/or provide some onboarding for reprohacks
- RSE workshop discussions would be used to write a blog post of possibly short paper with the goal of promoting discussions at a larger scale




