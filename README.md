![alt text](/logo.png)



## Contributors
Lusha Cao (lcao10@jhmi.edu)

Kerry Goetz (kerry.goetz@nih.gov, kgoetz2@masonlive.gmu.edu)

Dina Mikdadi

Divya Palaniswamy

Yajing Song

Violet Zhang

## Background

Biomedical Research Data is notoriously challenging when it comes to FAIR (Findable, Accessible, Interoperable and Re-usable) principles. Often, in order to understand the data set from a clinical research study, one needs to understand the data dictionary and associated code list. This means that someone interested in the data needs to spend a lot of time to understand the relationship between many files of several types. Additionally, the case report forms (CRF) are often contained within pdf type files and sometimes the codebooks are separate files. In some cases, the crf files also contain handwritten annotations. The goal of this work is to create an automated method to merging data from each source to a single containerized object that includes enough meta-data for an outsider to make sense of the study. This is the means to the goal of making biomedical research data FAIR.

### All about the data
We are working with survey data from the Patient Reported Outcomes with LASIK (PROWL). This was a joint project for DOD/FDA/NIH. More information can be found at [FDA PROWL Website](https://www.fda.gov/medical-devices/lasik/lasik-quality-life-collaboration-project) and [NEI PROWL Website](https://prowl.nei.nih.gov/). We looked three data categories: Demographic, Pre-Operation survey responses and Post-Operation surveys.

We started with a annotated case report form (CRF) and seperate code book in pdf format. Cooresponding Data Dictionary and survey response data in csv. 

### Data Information:
* Cohort = 1100 people
* Demographic = 8 Data Elements (DE)
* Pre-OP = 142 DE
* Post-OP = 108 DE
* 6 data files but we used one for proof of concept (see note about data access)
* 42 PDFs (21 pairs of annotated CRF and code book)

Data is available on controlled access basis. Required to sign a user agreement before account approval. Low-barrier to access, basically just want to track usage and make sure no third party sharing. Request access at [NEI BRICS](https://brics.nei.nih.gov).

## Goals
### Target: 
  1. Extract schema from the data sets
  2. Capture inventories of the files in the directories
  * Bagit and Pandas as tools
  * How many variables and missing values are in each file
### Stretch: 
  1. Pulling data from CRFs and PDFs as a structured data format 
  2. Associate the variables with the descriptions 
  3. Validate the variables against the data dictionary and report the record that does not find a match
  
## Workflow  

![alt text](/workflow.png)

## Presentations
[Project Concept](https://docs.google.com/document/d/1TnwnpWZsiipe2CH5zI_E20LvC_MvSOaQ_qIA1LlxgjM/edit?usp=sharing)

[Mid-way Lightning Talk](https://docs.google.com/presentation/d/1HCeoqp5jsKcanOoGPzKoNtMGqlKLhIXQKGbLvbgXUYs/edit?usp=sharing)

[Final Presentation]

### Dependencies:
* R
* R Studio
* Python
* Jupiter Notebook

### Input Data: 
![Example from CRF](/CRF.png)

![Example from Code list](/codelist.png)

![Example from Data Dictionary](/data_dictionary.png)

![Example from Data](/Data_set.png)

### Shoe #1 - CRF
  -Read CRF
  -Put into Data Frame to do cool stuff
    1. headers in data - variable names to questions
    2. other fun stuff like text analysis, mesh terms
    
### Shoe #2 - Variable Cleanup
![Example of cleanup based on the variable](cleanup.png)
![Example of Cleanup Stats grahp](/LasikGLCLCLSEScl.png)

### Shoe #3 - Generate Stats Charts
  
###

### Output



