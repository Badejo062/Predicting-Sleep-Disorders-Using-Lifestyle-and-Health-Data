**Researcher Name: - Tope Badejo**

**Predicting Sleep Disorders Using Lifestyle and Health Data**

**Overview**__

This project explores how lifestyle behaviors and physiological health indicators influence the risk of sleep disorders using a data-driven approach. The analysis is conducted within the context of Personal Health Informatics (PHI), a field focused on using personal health data and digital technologies to improve health monitoring and preventive care.
Using the Sleep Health and Lifestyle dataset, this project investigates how variables such as sleep duration, stress levels, physical activity, heart rate, BMI, and blood pressure relate to sleep disorders. Machine learning models are used to identify patterns and predict individuals who may be at higher risk of developing sleep-related conditions.
The goal of this project is to demonstrate how predictive analytics can support digital health monitoring systems and personalized healthcare interventions.


**Research Objectives**
 
This project aims to answer the following research questions:
Which lifestyle and health factors are associated with sleep disorders?
Can machine learning models accurately predict sleep disorder risk?
Which predictors contribute most strongly to sleep health outcomes?
How can predictive models support Personal Health Informatics systems and digital health monitoring platforms?
Dataset
The dataset used in this project is the Sleep Health and Lifestyle Dataset, which contains lifestyle and physiological information related to sleep health.
Key variables include:
Age
Gender
Sleep Duration
Sleep Quality
Stress Level
Physical Activity Level
Heart Rate
Blood Pressure
BMI Category
Sleep Disorder
These variables allow us to examine how behavioral and physiological factors contribute to sleep disorders.
Dataset Source: Kaggle (Sleep Health and Lifestyle Dataset)
Exploratory Data Analysis
Exploratory data analysis was conducted to identify patterns and relationships between lifestyle behaviors and sleep health outcomes.
Key visualizations include:
Distribution of sleep disorders
Sleep duration vs sleep disorder status.
Stress level vs sleep disorder.
Physical activity level vs sleep disorder
Correlation heatmap of health variables
These visualizations help reveal important behavioral trends influencing sleep health.


**Machine Learning Models**

To evaluate predictive performance, the following machine learning models were implemented:
Logistic Regression
Decision Tree
Random Forest
The dataset was split into training and testing sets using a 70/30 train-test split. Model performance was evaluated using:
Accuracy
F1 Score
ROC-AUC
The Random Forest model demonstrated the best predictive performance, highlighting the value of ensemble methods in modeling complex health relationships.


**Feature Importance**

Feature importance analysis identified several influential predictors of sleep disorders, including:
Stress Level
Sleep Duration
Physical Activity Level
Heart Rate
BMI Category
These findings suggest that both behavioral habits and physiological health indicators play critical roles in sleep health outcomes.
Personal Health Informatics Implications
This project demonstrates how predictive analytics can support Personal Health Informatics systems by enabling:
Early detection of sleep health risks
Personalized health monitoring
Preventive lifestyle recommendations
Digital health decision support systems
Such predictive models could be integrated into wearable devices, mobile health applications, and remote health monitoring platforms to help individuals manage their sleep health more effectively.


**Limitations**

Several limitations should be considered:
The dataset is based on self-reported data, which may introduce reporting bias.
The sample population may not fully represent broader demographics.
The analysis is cross-sectional and does not capture long-term health patterns.
Future research could integrate wearable device data and longitudinal health records to improve predictive accuracy.


**Future Research**

Future work in Personal Health Informatics could expand this research by incorporating:

Wearable device data (e.g., Fitbit, Apple Watch)

Continuous sleep monitoring systems

Mobile health applications

Electronic health records

Combining these data sources with advanced machine learning techniques could significantly enhance personalized health monitoring systems.
Technologies Used
Python
Pandas
NumPy
Scikit-learn.
Matplotlib
Seaborn
Repository Structure
Example repository structure:
sleep-disorder-prediction.
sleep_disorder_notebook.ipynb
README.md
research_report.pdf
dataset_information.md

**Author**

**Tope Badejo**
**Master’s in Project Management – Lasell University**
**Research interest: Personal Health Informatics, Digital Health Analytics, and Behavioral Health Data Science**

Link:- https://github.com/Badejo062/Predicting-Sleep-Disorders-Using-Lifestyle-and-Health-Data
