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