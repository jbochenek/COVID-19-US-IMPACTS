# COVID-19 US IMPACTS
## Capstone Project for DSCI 591, Fall 2020, team COVID-19 US Impacts.
### Introduction
The COVID-19 US impact team has formed to understand the impact that COVID-19 has had on employment in the United States. We are approaching this issue from several directions by examining:

1. Employment and unemployment rates
1. State policies that directly impact unemployment or underemployment
1. Housing changes
1. Impacts on gig economies (specifically Airbnb)
1. COVID-19 infection rates

For each of these (except the last) it is important to have data for both before the pandemic up until current time. We will also try to look at the results by sub-population, such as by race/ethnicity, gender, and locale (i.e., rural compared to metropolitan areas) to determine the different impacts across each group. The team is currently more focused on the development of the data acquisition, ETL, and analysis and less so on actual product/project creation at this phase of the effort.

We will use a variety of means to obtain, analyze and display the data we will be using to present our results. Data sources include the Bureau of Labor Statistics (BLS) for employment information, O\*NET for descriptions of occupations, InsideAirbnb for Airbnb rental rates, The U.S Census Bureau Household Pulse Survey for impacts on housing, The COVID Tracking Project for COVID-19 infection rates, and more will be identified as the project continues.

The team has an interest to learn how to use and follow the data science life cycle process as it pertains to COVID-19. This issue has a wide range of data availability and it is an ever developing world issue that the team can offer some understanding. In the end we are aiming to share a deeper understanding of how to ensure that data obtained is clean, usable, and analyzed following industry best practices so that the conclusions will withstand peer review, with manual modifications to the model.


[Whole Project on Google Drive](https://drive.google.com/drive/folders/19lfxsikXBMdrO1NtgSw3vby5qSIUweOT?usp=sharing)
[Instructions on Mirroring Project and Running Code](https://docs.google.com/document/d/1ysa7SlRrU_gzBxPbzbzn_VbI47uG09an0JxQ1BUjOps/edit?usp=sharing)

---

# Table of Contents
1. [Team Members](#TEAM-MEMBERS)
1. [Datasets](#EXPLANATION-OF-DATASETS)
1. [Acquisition](#DATA-ACQUISITION)
1. [Pre-Processing](#DATA-PRE-PROCESSING)
1. [Analysis](#DATA-ANALYSIS)
1. [Vizualization](#DATA-VISUALIZATION)
1. [Final Report](#FINAL-REPORT)
1. [Responsibilities](#RESPONSIBILITY-SUMMARY)

---
# TEAM MEMBERS

### Jennifer Bochenek
- Education 
  - B.S. in Psychology with concentrations in Psychobiology of Addiction and Clinical Psychology, and a minor in Biology from Purdue University (May 2011)
  - M.S. in Psychology from New Mexico Highlands University, thesis topic on *Sensation Seeking and Sleep Quality: Activity as a pre-requisit for high quality sleep* (December 2012)
- Occupation
  - Research Associate at Educational Testing Service
- Skills
  - R, Python, Java, SQL, Unix
  - SPSS, Orange, Weka, Tableau
  - Data collection/acquisition, management and cleaning; descriptive and inferential statistics; machine learning; data visualization; paper writing


### Yifan Yang
- Education
  - B.S. in Statistics and minor in Computer Science from Virginia Tech
- Occupation
  - Student, formerly IT for a POS company
- Skills
  - SQL, Unix, Java, Python, R
  - R-Studio, Python 
  - Descriptive, infernetial, non-parametric and other advanced statistics, machine learning, data visualization
  
  
### Shibo Yao
- Education
  - B.S. in Software Engineering
- Occupation
  - Student, formerly assistant industry analyst for a consulting company
- Skills
  - Python, Java, R, SQL
  - Eclipse, Pycharm, Rstudio
  - Data acquisition, pre-processing, analysis, and interpretation

### Joe Larson
- Education
  - Penn State
  - Electrical Engineering 
  - MBA
  - Master of Expert Systems
- Occupation
  - Manager at a GSE
- Skills
  - R, Python
  - Google Colaboratory
  - Management

For our team we have split out the research areas/topics and each team member is responsible for acquisition, cleaning, merging (if needed) of data for their topic, and analysis of said data, which all contribute to the final dataset and report. We will also be rotating who is the team facilitator for meetings on a weekly basis.

---

# EXPLANATION OF DATASETS
## MAIN DATASETS
### Employment and Unemployment
- Files pulled from BLS.
- *Joe Larson*
- [Link](https://drive.google.com/drive/folders/1G8CtuVW_-vminXfllFqchp7HxZY__MOf?usp=sharing)

### Housing
- ????
- *Jenni Bochenek*
- [Link](https://drive.google.com/drive/folders/1uUxcXyEI5Sd8kzCF6nYGPxXofZt5Z3Uk?usp=sharing)

### Gig Economy
- Data webscraped from Inside Airbnb
- *Shibo Yao and Yifan Yang*
- [link](https://drive.google.com/drive/folders/1uUxcXyEI5Sd8kzCF6nYGPxXofZt5Z3Uk?usp=sharing)

## SECONDARY DATASETS
### O\*NET 
- [Link](https://drive.google.com/drive/folders/1oM_zdreL6KT9U784PeAH0Z-ZDWaYSoKI?usp=sharing)

### Healthcare
- [Link](https://drive.google.com/drive/folders/1iECY-vzQSwlk8Vqn-4cb86gC2jD01YDf?usp=sharing)

### Population
- [Link](https://drive.google.com/drive/folders/1pJGSVfCg-vrLQjgIcwk7N5L7KgJgO23y?usp=sharing)

## COVARIANT DATASETS
### State Policies
- Collection of files related to state and local level policies
- [Link](https://drive.google.com/drive/folders/1t4oifBna6v0Z6VMyP_-ZrAtPgbS7__Sd?usp=sharing)

### COVID Infection Rates
- Need to grab.

---

# DATA ACQUISITION
## MAIN DATASETS
### Employment and Unemployment
- Using a mixture of BLS API, webscraping with selenium from beta.bls.gov, and using BLS's built in datafinder.
- *Joe Larson*
- [Colab for Defining Employment in BLS](https://colab.research.google.com/drive/17fNM9f3VWPehbJHCtwCb7jP0d2kpoksl?usp=sharing)
- [Colab for Defining Unemployment in BLS](https://colab.research.google.com/drive/1WGfhxWrNLSbwfizu2yVaAzuiC2zhJYeY?usp=sharing)
- [Colab for Extracting Data](https://colab.research.google.com/drive/12rANdvd2rwA7mkIF-yKECb8rFuEvJTxt?usp=sharing)
- [Colab for Converting Data](https://colab.research.google.com/drive/1RW4rUS9QxaAEkITVGtThxRniB3ic2c2L?usp=sharing)
- [Colab for Merging Data](https://colab.research.google.com/drive/1RW4rUS9QxaAEkITVGtThxRniB3ic2c2L?usp=sharing)

### Housing
- Housing Insecurity from the U.S. Census' Household Pulse Survey, data downloaded directly from website and unzipped into the google drive folder
- *Jenni Bochenek*
- [Colab for Loading HPS Data (WIP)](https://colab.research.google.com/drive/1RW4rUS9QxaAEkITVGtThxRniB3ic2c2L?usp=sharing)


### Gig Economy
- Data webscraped from Inside Airbnb
- *Jenni Bochenek webscrapped and combined files due to ram and bandwidth availabity to hand off to Shibo Yao and Yifan Yang*
- [Colab for Webscraping from Inside Airbnb](https://colab.research.google.com/drive/1xzqiVfgRlyZM9k86g2GrAHOKKLJYVBaY?usp=sharing)
- [Colab for Merging files from Inside Airbnb](https://colab.research.google.com/drive/11Ir_ePkndMNnKvtK4k1ITmwLTlQpLrbh?usp=sharing)


## SECONDARY DATASETS
### O\*NET
- Data downloaded directly from [O\*NET website](https://www.onetcenter.org/database.html)
- Any link here should be to a Google colab file that either involves acquisition and/or preprocessing.
- *Jenni Bochenek*

### Healthcare
- Data downloaded from Five-Thirty-Eight and data.world.
- Any link here should be to a Google colab file that either involves acquisition and/or preprocessing.
- *Jenni Bochenek*

### Population
- Data from U.S. Census American Community Survey, which estimares US population data at the state level from 2010 to 2019.
- Any link here should be to a Google colab file that either involves acquisition and/or preprocessing.
- *Joe Larson*

## COVARIANT DATASETS
### State Policies
- TBD

### COVID Infection Rates
- TBD

---

# DATA PRE-PROCESSING
TBD

---

# DATA ANALYSIS
TBD

---

# DATA VISUALIZATION
TBD

---
# FINAL REPORT
TBD

---

# RESPONSIBILITY SUMMARY

|    DATASET    | TYPE |  Acquisition  | Pre-processing |   Analysis    | Visualizations |
| ------------- | ---- | ------------- | -------------- | ------------- | -------------- |
|  Employment   | Main | Joe Larson    | Joe Larson     | Joe Larson    | Joe Larson     |
|    Housing    | Main | Jenni Bochenek| Jenni Bochenek | Jenni Bochenek| Jenni Bochenek |
| Gig Industry  | Main | Jenni Bochenek| Jenni Bochenek/Yifan Yang/Shibo Yao | Yifan Yang/Shibo Yao| Yifan Yang/Shibo Yao |
|    O\*NET    | Secondary | Jenni Bochenek | TBD | TBD | TBD |
|    Healthcare    | Secondary | Jenni Bochenek | TBD | TBD | TBD |
|    Population    | Secondary | Joe Larson | Joe Larson | Joe Larson | Joe Larson |
|  State Policy | Covariate | Jenni Bochenek | Jenni Bochenek | ALL | ALL |
| COVID-19 Infection Rates | Covariate | Shibo Yao | Shibo Yao | ALL | ALL |
