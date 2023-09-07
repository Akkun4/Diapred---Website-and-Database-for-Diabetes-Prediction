# Diapred---Website-and-Database-for-Diabetes-Prediction

METHODS
Study used NHANES dataset with health-related variables from 2011-2014
Data pre-processing removed missing values
Feature engineering reduced dimensionality and encoded categorical variables.

![6](https://github.com/Akkun4/Diapred---Website-and-Database-for-Diabetes-Prediction/assets/113637955/b2f331d9-bb2b-476b-a524-613d3a275b7d)



WEBSITE TEMPLATES 

HOMEPAGE

![1](https://github.com/Akkun4/Diapred---Website-and-Database-for-Diabetes-Prediction/assets/113637955/9c6ecdf9-7f79-4cd9-ba4e-63dc4b771bde)

TAKE A TEST 

![2](https://github.com/Akkun4/Diapred---Website-and-Database-for-Diabetes-Prediction/assets/113637955/ad1f36cd-deef-4d10-bc13-47ce2cb4f0bf)

![3](https://github.com/Akkun4/Diapred---Website-and-Database-for-Diabetes-Prediction/assets/113637955/42a65b47-d10d-47cd-8c8e-9c64499329f4)

REAL-TIME STATISTICS

![5](https://github.com/Akkun4/Diapred---Website-and-Database-for-Diabetes-Prediction/assets/113637955/0045bd78-d5e7-433d-b566-ade5e2868fe6)

Framework:
Django used MVC pattern to create 5 models for storing data and user input
Views connect data tables to HTML templates for updating and deleting data
Machine learning and statistical analyses executed via views upon request
Results submitted to HTML templates for display.

Machine Learning and Dashboard for Diabetes Analysis:
RFE used to reduce dimensions with Decision tree estimator
Data split into train and test sets, supervised Decision tree used to train model
HTML website with interactive dashboard and highcharts visualizations
Visualizations show diabetes distribution and HbA1C, age, and cholesterol levels in diabetes, pre-diabetes, and normal conditions
MySQL Connector used to connect SQL database to Django models.


Entity Relationship Diagram
![4](https://github.com/Akkun4/Diapred---Website-and-Database-for-Diabetes-Prediction/assets/113637955/dcc343bc-b7d3-4478-a9ce-1026f4c4aecb)






