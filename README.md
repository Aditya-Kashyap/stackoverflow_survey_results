## Stack Overflow Developer Survey Results:
<p align="center">
  <a href="https://www.udacity.com/">
    <img src='https://course_report_production.s3.amazonaws.com/rich/rich_files/rich_files/5511/s300/udacity-logo.png' alt="Udacity logo" width = 100px>
   </a>
</p>
<h3 align="center"><a href='https://www.udacity.com/course/data-scientist-nanodegree--nd025'>Udacity Data Scientist Nanodegree Program</a></h3>
<h4 align="center">Project I: Write a Data Science Blog Post</h4>



## Table of Contents

  1.  [Objectives](https://github.com/Aditya-Kashyap/stackoverflow_survey_results#Objectives)
  2.  [Summary](https://github.com/Aditya-Kashyap/stackoverflow_survey_results#Summary)
  3.  [View a detailed analysis report on Medium](https://github.com/Aditya-Kashyap/stackoverflow_survey_results#View-a-detailed-analysis-report-on-Medium)
  4.  [Requirements](https://github.com/Aditya-Kashyap/stackoverflow_survey_results#Requirements)
  5.  [Installation](https://github.com/Aditya-Kashyap/stackoverflow_survey_results#Installation)
  6.  [Files in the repo](https://github.com/Aditya-Kashyap/stackoverflow_survey_results#Files-in-the-repo)
  7.  [Licensing and Data Source](https://github.com/Aditya-Kashyap/stackoverflow_survey_results#Licensing,-and-Data-Source)
  8.  [Acknowledgements](https://github.com/Aditya-Kashyap/stackoverflow_survey_results#Acknowledgements)


## Objectives

### 1- Business Understanding

We investigated if North America was a better place to immigrate rather then Europe for a software developer.

For this we need to understand what is important to a person searching for a new job, things such as salary, salary growth, and satisfaction in what they do are important factors that determine which location is a better choice.

For this, we asked 4 questions:

   - How education may influence the salary?
   - Gender Ratio of developers across the globe 
   - The rate of increase in salary with the years of experience
   - More Languages = More Money?

### 2- Data Understanding

The data comes from the stack overflow 2017 survey. the rows are the different respondants to the survey, and the columns are the answer to the survey questions. It contains data that comes as numerical, categorical and text. It has missing values and outliers as well.

### 3- Prepare Data

For the data preparation phase, we gathered the data, assessed it and then proceeded to clean it, focusing on our columns of interest, with python libraries of Numpy and Pandas

### 4- Data Modeling

we graphed different behaviours that were relevant to the 4 questions, with the python libraries matplotlib and seaborn.


## Summary

### 1. How education may influence the salary?
![](Screenshots/1.png)

The developers who own a Doctoral Degree get the highest salary of $78,527, followed by Primary/Elementary School graduates at $62,677 and Master's Degree holder at normal pay of $58,250.

### 2. Gender Ratio of developers across the globe

In this survey, only 2,595 females were recorded out of 34,140 responses which states that there are only 13 female developers over 100 male developers

### 3. The rate of increase in salary with the years of experience
![](Screenshots/3.png)

With no surprise, the pattern is linear over the number of years of experience. Those very new to the tech industry, with less than a year of experience, can expect to get a normal pay of $24,673 (a year-over-year increment of 12.16 percent). Following a year or two, that normal pay hops to $33,953 (a whopping 37.6 percent expansion, year-over-year).

### 4. More Languages = More Money?
![](Screenshots/4.png)

It doesn't make much difference at all. A developer specialized in one programming language get a normal pay of $53,202 whereas the one who is skilled in 9 different languages get a normal compensation of $53,301 (0.18% more).


### View a detailed analysis report on Medium
[![Medium](Screenshots/medium_logo.png)](https://medium.com/@adi.inhere/stack-overflow-developer-survey-exploration-results-154cc420ba0b)


## Requirements

`pandas`, `matplotlib`, `jupyter-notebook` (if running locally)



## Installation

You need to be able to work in a Jupyter Notebook on your computer. The following packages (libraries) need to be installed. You can install these packages via conda or pip.

- Numpy
- Pandas
- Matplotlib
- Seaborn
- jupyterthemes

You will need to download Stackoverflow’s 2017 and 2018 Annual Developer Survey and put in specific folders. You can find the data to download [here](https://insights.stackoverflow.com/survey). 


## Project Motivation

This is a Udacity Nanodegree project. I was interested in using Stackoverflow Developer Survey Data to better understand


## Files in the repo

- [`Stack Overflow Developer Survey.ipynb`](https://github.com/Aditya-Kashyap/stackoverflow_survey_results/blob/master/%20Stack%20Overflow%20Developer%20Survey.ipynb) - Developers Survey Analysis
- [`survey_results_public.csv`](https://github.com/Aditya-Kashyap/stackoverflow_survey_results/blob/master/survey_results_public.csv) - Developers Survey Result Data
- [`survey_results_schema.csv`](https://github.com/Aditya-Kashyap/stackoverflow_survey_results/blob/master/survey_results_schema.csv) - Developers Survey Result Schema


## Licensing and Data Source

Must give credit to Stackoverflow for the data. You can find the Licensing for the data and other descriptive information at the Stackoverflow link available [here](https://insights.stackoverflow.com/survey).

Copyright: [Aditya Kashyap](https://github.com/Aditya-Kashyap)


## Acknowledgements
This project would be incomplete without methning a big thanks to the Stack Overflow Team for Providing this Dataset
And also to the Udacity Team for providing me this opportunity to help and gain knowledge about this Dataset. 

### Data Source
- https://insights.stackoverflow.com/survey/
