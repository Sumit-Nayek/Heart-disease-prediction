# Heart-disease-prediction
Here I have tried different binary classification approaches to find the optimal acuuracy
## Introduction
Public health estimates indicate that India accounts for approximately 60% of the world’s heart disease burden , despite having less than 20% of the world’s population. Heart disease is the number one cause of mortality and a silent epidemic among Indians.
India, particularly the city of Hyderabad in the state of Andhra Pradesh, is currently the diabetic capital of the world.Indians have been affected by high rates of diabetes, metabolic syndrome, hypertension, and smoking.These are major risk factors for cardiac disease.
## Data Description
Here we have taken the data from a secondary source.But data has good usability through out the community So In our data we have 12 columns and   917 rows . Here the variables are  Age,gender, Chestpain Type ,Resting Blood presure, serum cholestrol , Fasting Blood presure, Maximum heart rate achive, Excercise included angina , Oldpeak , the slope of the peak exercise ST segment, ST depression induceed by ecercise relative to rest , Target variable (HeartDisease). Here some are quantitative variable and some are qualitative variable. Quantitative variables are Age, Resting Blood Presure ,Serum Cholestrol, Fasting blood sugar, Maximum heart rate achive, Old Peak and  Qualtivative variables are Gender ,Chest pain type, Resting Electrocardio graphic result,Excercise included angina,the slope of the peak exercise ST segment. This database includes 76 attributes, but all published studies related to the use of a subset of 12 of them . The cleveland database is the only one used by ML researchers to date .One of the major task on this dataset is to predict based on the given attributes of the patient that wheather that particular person has heart disease or not and other is the experemental task to diagnose and find out various insights from this dataset which could help in understanding the problem more.

## Objectives
The objective of this study is to propose an efficient Supervised algorithm which can predict the heart disease almost with 90% accuracy . This Study can be helpful in medical science and in future it can be use a tools to develop a early warning device to the patient. To obtain the objective we do the following steps-
EDA of the data set
Data Pre processing
Applying different algorithm
Comparing the Accuracy of the algorithms

## Data preprocessing

Here we have use lot of different algorithm for this reason we have to prepare the data set multiple times just to feed in into the models .First we check the data for null values and NA’s . After that we use the Categorical data to create dummy variables for the model.

