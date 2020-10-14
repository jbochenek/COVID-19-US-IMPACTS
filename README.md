# COVID-19 US IMPACTS
## Capstone Project for DSCI 591, Fall 2020, team COVID-19 US Impacts.

[Whole Project on Google Drive](https://drive.google.com/drive/folders/19lfxsikXBMdrO1NtgSw3vby5qSIUweOT?usp=sharing)

---
# RAW DATASETS
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
