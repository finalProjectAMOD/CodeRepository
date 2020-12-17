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

!["Model Deployment"](https://github.com/finalProjectAMOD/CodeRepository/blob/main/Screenshots/Picture1.png?raw=true)

## Installation

Explain how to install/setup/run your project

In order to use the model or to run the project we have created the model and the scale file. Please follow the succeeding steps for fruitful and the proper formatted result. For the sake of the usage, we have created the deployment files i.e. scale and model file using the pythons pickle module (we have created the model deployment files which is being used for creating the API’s , Django and Flask Web Sites).

Software Version – You can install all the libraries using the ‘pip install command’. Also , this project is flexible to run on any version of library you are installing (since we have written the user defined functions and a generic code).

1.	Open any python editor (Integrated Development Environment) or you can also use the Jupyter Notebook. To the customer centric deployment , the results can be generated in just four lines of code.
2.	With this Project, We will share a zip file which consist of:
-	absenteeism_module.py (This python file consist of the methods and functions which will process the input data and generates the result).
-	Absenteeism_new_data.csv (This is the input file which a user or a client will bring to use the model).
-	Model (This model is the COCOM type executable model which generates the probability of the Absenteeism).
-	Scaler (The scaler file act as the input file for any type of method and this is generated using the pickle module).
3.	Create a python file in the same directory which you have extracted (Zip file) and open it.
4.	Once you open the file using the Jupyter notebook or any other IDE , Import all the module from absenteeism_module.py 

!["Picture-2"](https://github.com/finalProjectAMOD/CodeRepository/blob/main/Screenshots/Picture2.png?raw=true)

5.	Now , create a variable of your choice and import the model and scale under the absenteeism model method.

!["Picture-3"](https://github.com/finalProjectAMOD/CodeRepository/blob/main/Screenshots/Picture3.png?raw=true)

6.	And now , Import the input data (the input data can be raw data with outliers and all other error prone components).

!["Picture-4"](https://github.com/finalProjectAMOD/CodeRepository/blob/main/Screenshots/Picture4.png?raw=true)

7.	Now the fourth and the final step (yes it’s the last step), use your variable which you have used for storing the model and scale values. We have a dedicated method written in for generating the probability output and store your results in a csv for visualization and other purpose.

!["Picture-5"](https://github.com/finalProjectAMOD/CodeRepository/blob/main/Screenshots/Picture5.png?raw=true)