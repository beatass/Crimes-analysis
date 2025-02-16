# Crimes analysis

The analysis is intented to give the answer about Boston (USA) crime data.  The exploratory data analysis (**EDA**) is mostly aimed **to answer in a few important questions** that come to mind:

- Is it possible to predict where or when a crime will be committed?
- How have crimes changed over the years?
- Does the frequency of crimes change over the day? Week? Year?
- What types of crimes are most common?
- In which area most crimes are committed? 

**and last but not least**

- Which areas of the city have evolved over this time span?

The dataset comes from Kaggle.


## Motivation

In this study the exploratory data analysis (**EDA**) with visualizations of crimes data of Boston (USA) is used to answer to all of above questions.


## Recap

The **crimes_EDA.ipynb file** contains some **EDA** to understand the nature of data about crimes and the underlying distribution in particular to resolve the goals/problems assumed and to answer to all of questions mentioned in the Crimes Analysis section.

**It was performed in two steps:**

    I. Viewing the data state wise from different angles - EDA analysis and data visualization;
    II. Presenting findings and drawing conclusions.
    
After examination if the dataset has any missing values and checking the features within it and their data types, the EDA analysis has been performed. In this study EDA analysis is a clue to help me to answer to all of above questions. So let's back to them. The answer to question **"Is it possible to predict where or when a crime will be committed?"** is positive. First of all let's see that the most crime is committed in the city center (i.e.**where**) and what is more Friday, Saturday night and weekday lunch and departure times are the most prone to crime (i.e. **when**).

In turn the question **"How have crimes changed over the years?"** is correlated with the answer to the next question (see note that the lowest crime rate was in 2015, the year 2017 was the year with the highest crime rate while the crime rate was decreased in 2018).

To answer to question **"Does the frequency of crimes change over the day? Week? Year?"** it is enough to note that the highest crime rate is seen on Friday (i.e. **day**). It seems that the crime was triggered by the fact that many people were out on Friday night due to Saturday being a holiday. Other days there is no significant difference, but Sunday has the lowest rate. The months with the highest crime rates vary according to years, an increase can be was observed in the summer months. The year 2017 was the year with the highest crime rate while the crime rate was decreasing in 2018 (i.e. **year**). It is worth to noting that this fact maybe correlated with missing data for the first 5 months in 2015 and for the last three months in 2018.

The answer to question **"What types of crimes are most common?"** is positive and is easily readable from the distribution of the crimes (the graph illustrating 5 of the most commonly committed crimes). In this graph one can see that the most committed crimes are: **Motor Vehicle Accident Response, Larceny, Medical Assistance Group and Investigate Person**.

The answer of **"In which area most crimes are committed?"** may be embraced by the distribution of the crimes committed in **districs**. It is clear to see that there are districts with the highest crime rates (the highest number of crimes) i.e. **B2, C11 and D4**. In other words the most crimes are committed in the **city center**. The same thing is easy readable from the **longitude and latitude graphs** divided by particular districts. 

And finnaly there is difficult to answer the question **Which areas of the city have evolved over this time span?** since data were uncompleted i.e. there are missing ones for the first 5 months in 2015 and for the last three months in 2018. 


### Technologies

The project is created with Python libraries:

- scikit-learn/pandas/numpy/matplotlib.


#### Running the project:

- To run this project use Jupyter Notebook or Google Colab.


#### Files in this repository

1. The crimes_EDA.ipynb file contains all the codes, plots and relevant descriptions of conducted analysis.



