# Script

Hi, I'm Will Furnass and I'd like to propose a SSI fellowship around improving researchers' and PIs' understanding of the value of software packaging.

## Who I am

A little about me.

I work in and help run the Research Software Engineering team at the University of Sheffield.

I mainly work on paid-for research software and infrastructure projects with groups across the University including central IT
and support other team members in doing this.
Projects are really varied: 
 - with some I develop software for researchers, 
 - with others I help researchers develop software.  
 - Some involve building sustainable ecosystems around existing software (packaging, testing, docs).  
 - Others involve taking sustainable software and building services from it e.g. web services or HPC workflows.

To complement this project work my team also runs a free Code Clinic (surgery), through which we've learned quite a bit about the common computing challenges/questions that researchers encounter.

We also develop and deliver training.  For example:

  * I'm a certified Carpentries instructor and have also 
  * developed and delivered my own high-performance Python workshop

Another key part of what we do is engaging with various regional, national and international bodies, which is useful for sharing ideas, establishing collaborations and promoting activities:

  * we have two RSE Society committee members,
  * we've been involved with organising several UK RSE conferences (I was talks chair in 2018)
  * I'm part of the RSE Leaders Network, which discusses strategies for teaching and training, amongst other things.
  * Regionally, I'm involved with the N8 Centre for Computationally Intensive Research, which organises and promotes training around best practices
  * and finally I'd be a fool not to mention that several other team members are or have been SSI fellows

---

## Previously

The route to becoming a research software engineer has not been particularly linear!

I previously provided support to the users of our high-performance computer clusters.
A big part of this was listening to researchers, finding solutions/suggestions that would address their needs and communicating those ideas in a meaningful way

  * Before that I worked and studied as a researcher in civil engineering for several years, during which I developed numerical models using Python.  This made me aware of the needs of researchers and the research lifecycle.
  * This followed a change of career: I'd previously travelled round Europe providing IT support to the film and TV industry.  Funnily enough, this was similar in several ways to my Research Computing support work!
  * That was something I embarked on a couple of years after finishing my Computer Science undegrad degree.

---

Now, on to my plans for the fellowship.

So, take Robin, a typical researcher.  Thanks to the Carpentries and other initiatives they now know the basics of version control and testing, and they use both when working with Jupyter Notebooks and smaller scripts.  But

  * How can they structure the software they develop as it evolves to
    * make parts reusable and 
    * make version control and testing easier?

---

My thesis is that basic knowledge of why, when and how to create software packages would be useful here.

There's currently insufficient introductory guidance on how to structure research software projects
    - How/when to extract common functionality from Notebooks
        - How to create modules from collections of functions/classes 
        - How to organise modules within a directory tree
    - Structure for incorporating testing/documentation frameworks/tools
    - How to meaningfully version software/analysis components

I believe a little knowledge of software packaging, inc. if/when, would be useful.

---

### Activities

I propose four activities:

Firstly, I'd like to stage a workshop targeting RSEs where we
 - discuss common challenges researchers encounter as research software grows larger, particularly w.r.t. structure and barriers to entry for development tooling, and how packaging approaches fit in with typical 'private then public' research workflow.
 - discuss currently promoted best practices, if any, and new ideas around how researchers could develop workflows using self-penned packages, linear analysis scripts/notebooks and data repositories and robustly link them to aid reproducibility.  We could also explore existing and needed 'report card' tools for research software packages. 

This could be promoted via the RSE Society, the N8 Centre for Computationally Intensive Research, (in addition to the SSI) and could possibly be held at the Collaborations Workshop 2020.

---

Building on this, I'd then like to run two day-long workshops with researchers, one for Python users, one for R users, where 
- I introduce them to why they might be interested in packaging and 
- we explore how they could package existing code in idiomatic ways, including when in the research lifecycle this might be useful or necessary
Very little software in 2019 should be an island, so we would also cover managing dependencies.
In the second half of the workshop, we would explore how, once code has been packaged, it's much simpler integrating test frameworks and mechanisms for building and possibly auto-generating documentation.  This would be high-level with simple examples and sign-posts to external resources.
Participants should come away with non-exhaustive checklists that they can work through when considering packaging in future.

---

The final workshop would target PIs: by making them aware of the benefits of modularisation and packaging, plus equipping them with understanding of the most relevant tools, concepts and terminology they should then be able to audit the software their researchers produce, allowing them to encourage sustainable development practices.  

They would come away with checklists that would allow them to check whether some scripts are actually packaged and whether a package has tests/integrated documentation.  There would need to be some basic coverage of version control methods and tools.  

The workshop could also sign-post training that PIs could recommend to their researchers.  

It would be perhaps only 3 hours so as to get buy-in from busy academics.

---

Outputs

- The developed materials for the R, Python and PI workshops would be made openly-available to permit the workshops to be re-run in their entirety.
    - Parts could be re-used: the checklists to allow PIs to audit packages could be repurposed in Anna Krystalli's Reprohacks documentation/templates.
- RSE workshop discussions would be used to write a blog post of possibly short paper with the goal of promoting discussions at a larger scale re guidelines/checklists around best practices




