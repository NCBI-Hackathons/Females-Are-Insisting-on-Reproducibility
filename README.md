![alt text](/logo.png)



## Team Members
Lusha Cao

Kerry Goetz (kerry.goetz@nih.gov, kgoetz2@masonlive.gmu.edu)

Dina Mikdadi

Divya Palaniswamy

Yajing Song

Violet Zhang

## Background

Biomedical Research Data is notoriously challenging when it comes to FAIR (Findable, Accessible, Interoperable and Re-usable) principles. Often, in order to understand the data set from a clinical research study, one needs to understand the data dictionary and associated code list. This means that someone interested in the data needs to spend a lot of time to understand the relationship between many files of several types. Additionally, the case report forms (CRF) are often contained within pdf type files and sometimes the codebooks are separate files. In some cases, the crf files also contain handwritten annotations. The goal of this work is to create an automated method to merging data from each source to a single object to make biomedical research data FAIR and to provide visualizations of summary data from the source. 

### All about the data
We are working with Patient Reported Data from the National Eye Institute who have gone through or about to go through LASIK Surgery. There three data categories: Demographic, Pre-Operations, Post-Operations. The Data is in PDF and unclean and non-standard Excel Format.

### More details on the data:
* CRFs: Data Dictionary + PDFs
* 1100 people
* Structure: 
* Demographic 8 DE
* Pre-OP 142 DE
* Post -OP 108 DE
* 6 data files
* 42 PDFs

![alt text](/workflow.png)

# Presentations
[Click Me!](https://docs.google.com/document/d/1TnwnpWZsiipe2CH5zI_E20LvC_MvSOaQ_qIA1LlxgjM/edit?usp=sharing)

[Click Me for the Lightning talk slides!](https://docs.google.com/presentation/d/1HCeoqp5jsKcanOoGPzKoNtMGqlKLhIXQKGbLvbgXUYs/edit?usp=sharing)

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

## WorkFlow: 
### Input Data: 
Raw Non-standard Data + PDFs

### Automatically Transform To …. (Magic Happening!)

### Output



