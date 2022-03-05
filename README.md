# Crimes analysis

The analysis is intented to give the answer about Boston (USA) crime data using unsupervised machine learning and k-means clustering.**The EDA analysis is mostly aimed to answer in a few questions:**

- Is it possible to predict where or when a crime will be committed?
- How has crime changed over the years?
- Does the frequency of crimes change over the day? Week? Year?
- What types of crimes are most common?
- In which area most crimes are committed? 

and last but not least

- Which areas of the city have evolved over this time span?


## Motivation

In this study the exploratory analysis (**EDA**) with visualizations of crimes data of Boston (USA) as well as **unsupervised machine learning and k-means clustering** have been performed to make a relevant predictions and to answer to all of above questions.

The project is created with Python libraries:

- scikit-learn/pandas/numpy.


## Recap

The **crimes_EDA.ipynb file** contains some exploratory data  (EDA analysis) to understand the nature of data about crimes and the underlying distribution in particular to resolve the goals/problems assumed and to answer to all of questions mentioned in the Crimes Analysis section.

It was performed in two steps:

    I. Viewing the data state wise from different angles - EDA analysis and data visualization;
    II. Presenting findings and drawing conclusions.
    
After examination if our dataset has any missing values and checking the features within it and their data types, the EDA analysis has been performed. In this study EDA analysis is a cue to help us to answer to all of above questions. So let's back to them. The answer to question **"Is it possible to predict where or when a crime will be committed?"** is positive. First of all let's see that the most crime is committed in the city center (i.e.where) and what is more Friday, Saturday night and weekday lunch and departure times are the most prone to crime (i.e. when).

In turn the question **"How has crime changed over the years?"** is correlated with the answer to the next question (see note that the lowest crime rate was in 2015, the year 2017 was the year with the highest crime rate while the crime rate was decreased in 2018).

To answer to question **"Does the frequency of crimes change over the day? Week? Year?"** it is enough to note that the highest crime rate is seen on Friday (i.e. day). It seems that the crime was triggered by the fact that many people were out on Friday night due to Saturday being a holiday. Other days there is no significant difference, but Sunday has the lowest rate. The months with the highest crime rates vary according to years, an increase can be was observed in the summer months. The year 2017 was the year with the highest crime rate while the crime rate was decreasing in 2018 (i.e. year). It is worth to noting that this fact maybe correlated with missing data for the first 5 months in 2015 and for the last three months in 2018.

The answer to question **"What types of crimes are most common?"** is positive and is easily readable from the distribution of the crimes (the graph illustrating 5 of the most commonly committed crimes). In this graph one can see that the most committed crimes are: Motor Vehicle Accident Response, Larceny, Medical Assistance Group and Investigate Person.

The answer of **"In which area most crimes are committed?"** may be embraced by the distribution of the crimes committed in **districs**. It is clear to see that there are districts with the highest crime rates (the highest number of crimes) i.e. **B2, C11 and D4**. In other words the most crime is committed in the **city center**. The same thing is easy readable from the **longitude and latitude graphs** divided by particular districts. 





### Running the project:

- To run this project use Jupyter Notebook or Google Colab.

## Files in this repository

1. The crimes_EDA.ipynb file contains all the codes, plots and relevant descriptions of conducted analysis.
2. The crimes_KMeans.ipynb file contains all the codes, plots and relevant descriptions of conducted analysis.


## Relevant information

The dataset consists of the following input variables:


- **Offense Code** - it is a given code of an incident;
- **Offense Code Group** - it is a code for offence's group;
- **Offense Description** - it is a description of the committed crime;
- **District** - it is a place where the crime was committed;
- **Incident Number** - it is a given number of crime ;
- **Reporting Area** - area where the crime was committed;
- **Shooting** - is a type of incident;
- **Occured On Date** - it is a date when the crime was committed;
- **Year** - it is a year when the crime was committed;
- **Month** - it is a month when the crime was committed;
- **Day Of Week** - it is a day when the crime was committed;
- **Hour** - it is an hour when the crime was committed;
- **UCR Part**;
- **Street** - it is a name of street where the crime was committed;
- **Lat** - it is the latitude of the place where the crime was committed;
- **Long** - it is the longitude of the place where the crime was committed.

