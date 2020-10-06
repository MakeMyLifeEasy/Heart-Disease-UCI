# Heart-Disease-UCI

## Introduction

Heart disease describes a range of conditions that affect your heart, which includes blood vessel diseases, such as heart rhythm problems (arrhythmias); coronary artery disease; and heart defects you're born with (congenital heart defects), among others.

Heart disease is one of the biggest causes of morbidity and mortality among the population of the world. Prediction of cardiovascular disease is regarded as one of the most important subjects in the section of clinical data analysis. It is challenging to identify heart disease because of several contributory risk factors such as high blood pressure, diabetes, abnormal pulse rate, high cholesterol and many other factors.

Due to such constraints, up to now, various researches have been done for the diagnosis of heart disease. These researches have used different methods for the detection of heart disease and have achieved relatively high accuracies, of 77% or higher on UCI machine learning repository data sets.

In this project, we will be examining the most used dataset - Cleveland Heart Disease dataset from UCI Repository.

## Data Set Description

The dataset is taken from the Data Mining Repository of University of California, Irvine (UCI). The CAD data sets contain 920 instances collected from Cleveland, Hungarian, Switzerland and VA Long Beach.

## Key Performance Indicators

### Quality KPI

● Measure target(heart disease) accuracy > 90%

### Health KPI

● BMI < 25

● Physical activity of 150 minutes of moderate-intensity OR 75 minutes of vigorous-intensity per week

● Limit alcohol to 1 serving for women or 2 servings for men per day

● Total cholesterol < 200 mg/dL, LDL < 130 mg/dL, HDL > 40 mg/dL, triglycerides < 150 mg/dL

● Blood pressure < 120/80 mmHg

● Fasting blood sugar < 100 mg/dL

### Dimensional Model

The data warehousing environment is profoundly different and inappropriate from the operational environment and techniques to design operational databases. For this reason,
Kimball proposed a new technique which he called dimensional model for data modelling which we will be designing for this project. Dimensional model uses three concepts: measures, facts and dimensions which are powerful in representing the requirement of this research to determine the presence of cardiovascular disease in a patient.

### Conclusion

This project is a great experience, being able to utilize all tools and techniques learned during this semester. We choose the project that we were all interested in and determine what kind of information we wanted to attain from creating this database.

There were two steps that we found most challenging are data profiling including creating the dimensional model and understanding the transformation process, meaning getting it done right in Pentaho. At first, there are many technical terms in this dataset. Therefore, we really need to understand the dataset, the performance key indicators versus the target variables in order to create the dimensional model. Furthermore, the main reason we struggled with the transformation process was a lack of experience in using Pentaho Data Integration (including setting up Pentaho and connecting to Oracle Cloud Database).

Another challenge that we faced during this project is to obtain the final dimensional model in Oracle Database. We were able to import the csv files perfectly fine and did the transformation. However, Oracle DB shows nothing in the end. It took us quite a long time to figure out what went wrong and how to fix it.

If we were to recreate this project, we would have double checked our datasource to make sure all of the fields were consistent and had no null values. The data sources we attained were not as clean and well put together as we expected. There are a lot of more adds on and techniques that we could have tried to implement within this project if we had more knowledge and time, especially during this crisis mode under the Coronavirus situation.

Despite many difficulties in completing this project, it was overall a great learning curve, where we were able to practice on what we have learned in this class about data warehousing, Oracle, Pentaho, Tableau and Power BI.
