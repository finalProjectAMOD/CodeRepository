# PREDICTING ABSENTEEISM OF EMPLOYEES AT WORKPLACE USING LOGISTIC REGRESSION & GRADIENT BOOSTING ALGORITHM

## Abstract 
Workplace absenteeism plays a key role in demonstrating a company's efficient and profitable ability. Thus, the understanding of employee absenteeism becomes the principle for a company across its different aspects. Since the right assessment of the profile of workers allows such illnesses to be detected by excesses of occurrences. The primary aim of the early absenteeism analysis was to predict the characteristics and groups of employee absence and the reason of absence that make them implement superior absenteeism at work. However, it is still to be explored to forecast the absenteeism period of workers using machine learning classifiers and thus to find out the evidence that should be considered to minimize higher absenteeism at work. We now use two prominent machine learning algorithms in this project, namely Logistic Regression and Gradient Boosting, to predict employee absenteeism time and to discover the insights that prompt employees to perform greater absenteeism at work.

## Description of the Dataset
The dataset we used in this study was obtained from the UCI Machine Learning Repository, which was created from July 2007 to July 2010 at a courier company in Brazil with records of employee absenteeism at work. Firstly, the Universidade Nove de Julho Postgraduate Program in Informatics and Information Management used the dataset for their academic study. The data is consisting of the 700 Rows with 12 Attributes namely ID, Reason for Absence, Date, Transportation Expense, Distance to Work, Age, Daily Work Load Average, Body Mass Index, Education, Children, Pets, Absenteeism Time in Hours. The International Code of Diseases (ICD) attests to the absence of diseases in 21 groups. 

| Code       | ICD Description  
| :------------- | :----------: | -----------: |
| 1          | Certain infectious and parasitic diseases
| 2          | Neoplasms
| 3          | Diseases of the blood and blood-forming organs and certain disorders involving the immune mechanism.
| 4 | Endocrine, nutritional and metabolic diseases
| 5 | Mental and behavioral disorders
| 6   | Diseases of the nervous system
| 7   | Diseases of the eye and adnexa
| 8   | Diseases of the ear and mastoid process
| 9   | Diseases of the circulatory system
| 10   | Diseases of the respiratory system
| 11  | Diseases of the digestive system
| 12   | Diseases of the skin and subcutaneous tissue
| 13   | Diseases of the musculoskeletal system and connective tissue
| 14   | Diseases of the genitourinary system

## Model Deployment
Before the deployment of the model, we first need to consider how end users can interact with the predictions of the model to determine how to deploy a model. We save the model using the Python Pickle Module.

!["Model Deployment"](/Users/sahilnagpal/Desktop/TrentU/MajorProject/CodeRepository/Screenshots/Picture1.png)