# Prediction of Fibril-Forming Peptides

### Prerequisites
To most easily run this code out of the box, the following packages must be installed:
* pandas
* numpy
* scikit-learn
* matplotlib
* seaborn
* great expectations
* fastai
* huggingface
* datasets

This is easiest to achieve through first installing an Anaconda distribution, which installs the first 5 packages and all of their dependencies.  The install directions to the other packages may be found on their documentation pages.

# Quick navigation
[Background](#background)  
[Data](#data)  
[Models](#models)  
[Timeline](#timeline)  
[Repo Structure](#repo-structure)  
[Logistics](#project-logistics)  
[Resources](#resources)  
[Contact](#contact-info)

# Goal
The goal is to computationally establish the relationship between sequence and function, whether a peptide is able to form fibrils. The knowledge obtained in this project may be applicable not only to understanding the molecular mechanisms of beta-sheet self-assembly and protein folding in general, but also to rationally designing the next generation of nanomaterials consisting of assembling peptides.

# Background  
Proteins are the building blocks of life, responsible for most of what happens inside cells. How a protein works and what it does is determined by its 3D shape. The shape of a protein is specified by its amino acid sequence. Proteins are made up of hundreds or thousands of smaller units called amino acids, which are attached to one another in long chains. There are 20 different types of amino acids that can be combined to make a protein. 

Peptides are smaller than proteins. Traditionally, peptides are defined as molecules that consist of between 2 and 50 amino acids, whereas proteins are made up of 50 or more amino acids. Peptide self-assembly into cross-β fibril structures has important implications for plaque formation in amyloid diseases that include Alzheimer’s and Parkinson’s. However, the molecular mechanisms promoting the assembly of beta-sheet peptides are still elusive. 

# Data

http://waltzdb.switchlab.org/sequences
WALTZ-DB 2.0 is a database for characterizing short peptides for their amyloid fiber-forming capacities. The majority of the data comes from electron microscopy, FTIR and Thioflavin-T experiments done by the Switch lab. 

Reference:
Louros, N. et al. (2019) WALTZ-DB 2.0: an updated database containing structural information of experimentally determined amyloid-forming peptides. Nucleic Acids Res, 48 (D1), D389–D393

## Counts

The total number of experimentally characterized hexapeptides in the WALTZ-DB database is 1416, of which 515 are annotated as positive for amyloid formation.

# Models

The models to be used in this project include large language transformer models and other smaller transformer models based on performance.

# Timeline

Outline the desired timeline of the project and any explicit deadlines.

# Repo Structure 

Give a description of how the repository is structured. Example structure description below:

The repo is structured as follows: Notebooks are grouped according to their series (e.g., 10, 20, 30, etc) which reflects the general task to be performed in those notebooks.  Start with the *0 notebook in the series and add other investigations relevant to the task in the series (e.g., `11-cleaned-scraped.ipynb`).  If your notebook is extremely long, make sure you've utilized nbdev reuse capabilities and consider whether you can divide the notebook into two notebooks.

All files which appear in the repo should be able to run, and not contain error or blank cell lines, even if they are relatively midway in development of the proposed task. All notebooks relating to the analysis should have a numerical prefix (e.g., 31-) followed by the exploration (e.g. 31-text-labeling). Any utility notebooks should not be numbered, but be named according to their purpose. All notebooks should have lowercase and hyphenated titles (e.g., 10-process-data not 10-Process-Data). All notebooks should adhere to literate programming practices (i.e., markdown writing to describe problems, assumptions, conclusions) and provide adequate although not superfluous code comments.

# Project logistics

**Sprint planning**:  
**Demo**:  

**Data location**:  

**Slack channel**:  
**Zoom link**:  

# Resources 
* **Python usage**: Whirlwind Tour of Python, Jake VanderPlas ([Book](https://learning.oreilly.com/library/view/a-whirlwind-tour/9781492037859/), [Notebooks](https://github.com/jakevdp/WhirlwindTourOfPython))
* **Data science packages in Python**: [Python Data Science Handbook, Jake VanderPlas](https://jakevdp.github.io/PythonDataScienceHandbook/) 
* **HuggingFace**: [Website](https://huggingface.co/transformers/index.html), [Course/Training](https://huggingface.co/course/chapter1), [Inference using pipelines](https://huggingface.co/transformers/task_summary.html), [Fine tuning models](https://huggingface.co/transformers/training.html)
* **fast.ai**: [Course](https://course.fast.ai/), [Quick start](https://docs.fast.ai/quick_start.html)
* **nbdev**: [Overview](https://nbdev.fast.ai/), [Tutorial](https://nbdev.fast.ai/tutorial.html)
* **Git tutorials**: [Simple Guide](https://rogerdudler.github.io/git-guide/), [Learn Git Branching](https://learngitbranching.js.org/?locale=en_US)
* **ACCRE how-to guides**: [DSI How-tos](https://github.com/vanderbilt-data-science/how-tos)  

# Contact Info

Zhaoqian Su, Zhaoqian.Su@vanderbilt.edu, Vanderbilt Data Science Institute (DSI) Posdoc Fellow
