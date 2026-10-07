# Final Project Proposal - Benjamin Wilson

**Due: October 7. Must be approved by the instructor before full-scale work begins.**
Length: ~1 page (plus references if needed). Submit as a single team, not per-member.

---

**Team members:**

Benjamin Wilson

**Project title:** Differential Gene Expression in Benchmark Alzheimer's Disease
Dataset

**Project type:** RNA-Seq Pipeline with R using GEOquery, DESeq2, and tidyverse

## 1. Problem statement

This workflow will address Alzheimer's Disease, a neurodegenerative disorder
responsible for 60%-80% of dementia cases in the United States (source: CDC). 
Given the aging population in the United States, it becomes more important
to address these neurodegenerative disorders. For the purposes of this class,
analyzing differences between a control sequence and a case with Alzheimer's
may allow researchers to hone in on at-risk genes for this disease. 

## 2. Data source(s)

This data comes from the NCBI GEO database at this url: 
https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE48350. This data is 
publicly available and uploaded by the Institute for Memory Impairments and 
Neurological Disorders at UC Irvine. This data fall under transformative fair 
use, even if it is not completely in the public domain. I did not notice
any license or use restrictions. 

## 3. Planned methods and tools

I will build a reproducible coding environment and notebook project structure
(drawing on the content from Weeks 1 + 2). My plan is to use the GEOquery
Bioconductor package (extracting data) along with the DESeq2 package in R (for 
analysis). I plan to use concepts developed in Week 5 for wrangling this data 
(which may necessitate the use of the R package tidyverse). Although we have not
covered it in our coursework so far, I imagine I will be drawing on concepts 
found in Week 8 for relational databases, Week 10 for workflow management, 
and Week 14 for AI-assisted pipelines. I am familair with most of these
packages from my time in the Rahnavard Lab, and I may ask my peers there
if I run into a package I am not as familiar with. The end goal is to highlight
which genes are differently expressed between someone with Alzheimer's Disease
and someone who is healthy.

## 4. Generative AI plan

I expect to use AI largely for debugging purposes. I like to handle literature 
searches on my own. If there are any visualizations I do not know how to code,
I may ask AI for assistance in providing a template code for a visualization.
I will validate the AI output by tweaking the code to the specifications for 
this project until a process succeeds and outputs a result I expect it to.

## 5. Team roles

I will be responsible for all work in this project. Many aspects of this 
workflow will be carried forward in my Principles of Bioinformatics final 
project as well. 

## 6. Timeline

I would like to have the data downloaded by October 14th, a full outline done
by October 31st (depending on when proposals for the Principles of Bioinformatics
course are due), and then the first working version and draft done by November
17th. Further tweaks and cleaning to the pipeline can be carried out between then
and December 9th.

## 7. Risks / open questions

My computer can be extremely slow when handling large datasets. I only have 
about 8GB of RAM, so the amount of compute can be a limitation when working 
with these workflows. Given that GEO is such a large source of data, the trick
will be to choose a sensible amount of data to compare for differential gene
expression. I will adapt by documenting all of my steps, and if something does
go wrong, I can switch gears and try an easier path to still fulfill the goals
of this project.

---

### Instructor approval checklist
See `rubrics/proposal_checklist.md`.
