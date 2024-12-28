# Matplotlib Challenge - Pymaceuticals
`Module 5`  
`EdX(2U) & UT Data Analytics and Visualization Bootcamp`  
`Cohort UTA-VIRT-DATA-PT-11-2024-U-LOLC`  
`By Neel Kumar Agarwal`  

## Table of Contents  
1. [Introduction](#introduction)  
2. [Challenge Overview](#challenge-overview)  
3. [Variables/Breakdowns](#variablesbreakdowns)
    - [Relevant Variables](#relevant-variables)
    - [Summary Breakdowns](#summary-breakdowns)
3. [Setup and Usage](#setup-and-usage)  
    - [Prerequisites](#prerequisites)  
    - [Instructions](#instructions)  
    - [Limitations](#limitations)  
4. [Files and Directory Structure](#files-and-directory-structure)  
5. [Expected Results](#expected-results)  
6. [Final Analysis](#final-analysis)  


## Introduction  
*Roleplay...*  
You've just joined Pymaceuticals, Inc., a new pharmaceutical company that  
specializes in anti-cancer medications. Recently, it began screening for potential  
treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.  

As a senior data analyst at the company, you've been given access to the complete  
data from their most recent animal study. In this study, 249 mice who were identified  
with SCC tumors received treatment with a range of drug regimens. Over the course of  
45 days, tumor development was observed and measured. The purpose of this study was  
to compare the performance of Pymaceuticals’ drug of interest, Capomulin, against the  
other treatment regimens.  

The executive team has tasked you with generating all of the tables and figures needed  
for the technical report of the clinical study. They have also asked you for a top-level  
summary of the study results.  

[:arrow_up: Return to TOC](#table-of-contents)  


## Challenge Overview  
This assignment is broken down into the following tasks:  
- Prepare the data.  
- Generate summary statistics.  
- Create bar charts and pie charts.  
- Calculate quartiles, find outliers, and create a box plot.  
- Create a line plot and a scatter plot.  
- Calculate correlation and regression.  
- Submit final analysis.  

The Pymaceuticals .ipynb is a Python-interactive Jupyter notebook that takes raw data  
from a test study of mice with tumors, transforms it into usable information, and  
creates graphical presentations of different variables and their relationships. The  
exact process consists of extracting raw data, combining data together for usability  
and portability, cleaning our merged data, and then using it to create palpable  
summaries and charts detailing the effectiveness of different drug regiments.  

Pymaceuticals was developed and currently runs on a conda based local python  
environment. Python version used is `3.12.7` running with imported dependencies of  
`pathlib`, `random`, `pandas`, `matplotlib`, and `scipy`. The files Mouse_metadata.csv  
and Study_results.csv were imported and read into two Pandas DataFrame objects.  
The two frames were checked for holes in their data types (NaN). After merging the two  
DFs on their column axis by the unique ID of the mice involved in the study, another  
scan over the newly merged DF was done but this time to check for any duplicate  
information found under data identifiers.  

The identifying labels for each datapoint consists of a mouse ID and the timepoint the  
data was measured at (days since study started for mouse). Each mouse ID's timepoints  
must be unique to that ID. For any ID found with duplicate timepoints, all data  
associated with said ID must be removed to ensure data integrity.  

> [!NOTE]  
> In the case of a majority duplicates, a different course of action would be taken  
> to maintain a usable amount of datapoints, however only one mouse ID was found and  
> thusly removed from the set.  

After cleaning has been completed, the study's data has been combined with its  
corresponding mouse ID to give access to the mouse's data at every datapoint. Summary  
statistics of tumor by drug treatment is calculated, graphs visualizing the usage of  
each drug in the study and distribution of mice by gender are rendered, and then  
outliers are found quantitatively and qualitatively. Last of all, 


[:arrow_up: Return to TOC](#table-of-contents)  


## Variables/Breakdowns  
### Relevant Variables:  
```
- Mouse Data  
    - Mouse ID  
    - Drug Regimen  
    - Sex  
    - Weight (g)  
- Study Data  
    - Mouse ID  
    - Timepoint  
    - Tumor Volume (mm3)  

- Datapoint identifiers  
    - Mouse ID  
        -Timepoints  
```  
[:arrow_up: Return to TOC](#table-of-contents)  

### Summary Breakdowns:  
- Loading Station & Data Cleanup  
    - Setup for Imports, CSVs, and DataFrames  
    - Locating Duplicate Mice by ID and Timepoint  
    - Duplicate Mice Data
    - Cleaned DataFrame
- Summary Statistics  
- Bar and Pie Charts  
- Quartiles, Outliers and Boxplots  
- Line and Scatter Plots  
- Correlation and Regression  

[:arrow_up: Return to TOC](#table-of-contents)  

## Setup and Usage  
### Prerequisites  
- Python 3.x  
- Standard libraries: `pathlib`, `random` (included with Python)  
- Non-standard library: `pandas`, `matplotlib`, `scipy`  
- IDE that supports Jupyter Notebooks with Python  

[:arrow_up: Return to TOC](#table-of-contents)  

### Instructions  
1. Clone this repository.  
2. Ensure IDE is up to date and running.  
3. Ensure the two input CSV files are in the `data` sub-folder.  
4. Open `main.ipynb` in your IDE and run all cells.  
5. If the necessary dependencies aren't found install using the following methods:  
    - For *pip*  
        ```  
        pip install pathlib  
        pip install random  
        pip install pandas  
        pip install matplotlib  
        pip install scipy  
        ```  
    - For *anaconda*  
        ```  
        conda install pandas  
        conda install matplotlib  
        conda install scipy  
        ```  
> [!WARNING]  
> Please note that neither *pathlib* nor *random* was installed using conda  
> *pathlib* and *random* are base modules almost always included with Python  
> installations. It is recommended to use `pip install` for these two modules.  
6. **Results will print throughout the Jupyter Interactive Notebook**  
<!-- 7. Results are then exported in .png format in new `snapshots` directory   -->

[:arrow_up: Return to TOC](#table-of-contents)  


### Limitations  
- [ ] Results are qualitative not quantitative  
- [ ] Exported images lack complete titling for easy comprehension in any space  
- [ ] Time frame for DataFrame is a static moment instead of a dynamic range  

[:arrow_up: Return to TOC](#table-of-contents)  


## Files and Directory Structure  
```  
matplotlib-challenge/
|
|— Pymaceuticals/
|   |— data/
|   |   — Mouse_metadata.csv
|   |   - Study_results.csv
|   |— main.ipynb  
|   |- README.md
```  
This structure ensures all inputs are organized within their respective folders.  

[:arrow_up: Return to TOC](#table-of-contents)  



## Expected Results  

> [!TIP]  
> Collapsing of various regions or use of `OUTLINE` in VSCode can  
> speed up exploration of the Notebook.  

[:arrow_up: Return to TOC](#table-of-contents)  



## Final Analysis  


[:arrow_up: Return to TOC](#table-of-contents)  