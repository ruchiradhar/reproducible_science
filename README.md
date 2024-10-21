# ReproducibleQuantitativeDataScience

This repository is primarily bsed on the course [Reproducible Quantitative Data Science](https://github.com/melanieganz/ReproducibleQuantitativeDataScience-2024) and contains additional useful information on getting started with creating your own repositories based on Open Science principles. 

## Step 1: Create project folder
## Step 2: Create environment 
## Step 3: Create README.md 

## Some Useful Commands: 

1. Opening a file: `cat filename.txt` (alternative use head/tail/less/more)
2. Creating a requirements.txt: `conda list -e > requirements.txt` or `conda env export > requirements.yml`

## Part 1

### Day 1 - Data Collection and data storage

- Introduction to reproducibility: [Definitions and origins](./lecture_slides/1.01_Definitions&Origins.pdf) (CP) 
- How do you store data on your computer? [Data structures and data naming](./lecture_slides/1.02_StoringData&Code.pdf) (CP)
- Data provenance: [keeping track of where data are coming from](./lecture_slides/1.03_DataProvenance.pdf) and [exercise](./provenance/ProvenanceInPractice.ipynb) (MG)
- [Reproducibility is hard](./lecture_slides/1.04_ReproducibilityIsHard.pdf): [case studies](http://www.practicereproducibleresearch.org/core-chapters/4-casestudies.html) (all)

### Day 2 - Reproducible designs, protocols and pre-registration

- [Concepts and tools for protocol documentation, and study pre-registration] (CP)
- [Ethic and GDPR] - lecture and practical case reviews (CP )
- [Using markdown] for documentation - practical (MG)
- [Version control and social coding with Git] see the [quick sheet](https://github.com/CPernet/Quicksheets/blob/main/git_github/git.mkd) and GitHub - practical, split into novice/advanced groups (all) 

### Course work

Using your PhD research data, protocol, code, etc, write a report explaining from where you start, and which measures are already in place to increase reproducibility as per concepts presented during days 1 and 2. What measures can be taken to increase reproducibility and if any, why some cannot be implemented? (page count 2 to 3)

Submit your coursework via e-mail to Cyril and Melanie three weeks before the next course day.

## Part 2

### Day 3 - Better coding 

- Feedback on coursework and discuss further issues to make your PhD reproducible (MG, CP)
- [Programming] (CP)
- [Good coding practices] (CP) 
- [An introduction to computational analysis methods]: permutation, bootstrap, cross-validation, out-of-sample generalization (MG)
- Understanding p-values (see [notebook](https://github.com/melanieganz/ReproducibleQuantitativeDataScience-2024/blob/main/p_values/p_values.ipynb))

### Day 4 - Better analyses 

- [Computational reproducibility](https://files.inm7.de/mih/pres/talks/rdm_reproducibility_copenhagen2023.html#/) lecture and practical all morning (MH, MG & CP as helpers).
- [P-hacking] your data (CP)
- Time to update your code - push code here, review each other work, present, discuss with teachers (students do the work)

Please prepare before the course:
  - [install docker on your own machine](https://docs.docker.com/engine/install/) so you can use a container and then build a container.
  - We will reproduce a full paper, to safe download time during the practical, please download the two files at https://datapub.fz-juelich.de/studyforrest/remodnav/docker-layers beforehand
  - [install DataLad on your own machine](https://handbook.datalad.org/r?install) to be able to execute all steps to reproduce the paper, and to be able to make your own reproducible in the same way

### Course work 

Improve code you are using based on the concepts and tools reviewed over the 4 days: from version control and better inline documentation, to functionalization and modern computational statistics.  

Make a 10 minutes presentation summarizing all of your course works and what measures you have taken to improve reproducibility in your PhD - include main aspects from session 1, add computational aspects presented in session 2. 

## Part 3

### Day 5 - Data sharing 

- The ‘data’ cycle, [sharing from raw data to figures] - lecture (CP & MG)
- [Reproducible publishing] (NS)
- Presentations and discussions

 
