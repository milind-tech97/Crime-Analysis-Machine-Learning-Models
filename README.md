
This project contains two major tasks focusing on big data analytics and machine learning techniques. In the first part, crime data from the UK (covering Cumbria, Leicestershire, and Nottinghamshire) is analyzed using PySpark SQL. Various SQL queries and joins are performed to extract insights about crime patterns and trends, supported by visualizations.
In the second part, machine learning algorithms (Naive Bayes, Logistic Regression, and Decision Tree Classifier) are implemented using PySpark MLlib to predict Titanic passenger survival rates. The project demonstrates the full pipeline, including data preprocessing, feature selection, model training, evaluation, and visualization.

# Technologies used:
- **PySpark SQL for big data querying and analysis**
- **PySpark MLlib for machine learning model development**
- **Matplotlib & Seaborn for visualizations**

# TASK-1: Crime Analysis Using Spark SQL ( Cumbria, Leicester and Nottingham)

# Dataset
In the modernised growing world crime is one of the complex issues which is based on social, economic and physiological factors. The number of crimes reported every year is rising. Currently in the UK the crime rate has increased by 8% from 2021(crimerate.co.uk, 2023). In order to get a better understanding of the crime reported the dataset chosen for this task is from the police open-source data. Where the date range is between the year ‘November 2020’ to ‘November 2022’. And the cities selected for the purpose of analysis are ‘Cumbria Constabulary’, ‘Leicestershire Police’ and ‘Nottinghamshire Police’ which constitutes three cities in total. 
The dataset basically includes the crime data of Cumbria, Leicester and Nottingham in the format of a csv file. The columns in the dataset mainly include crime ID, Month, Reported by, Falls Within, and so on. Using the Spark SQL, trying to perform different kinds of SQL queries and try to get the useful results from the data. Also trying to build a visualisation from the data where it could provide a better insight on providing meaningful information. And obtain a better analysis about the crimes rates and percentage of crime.
After the successful completion of the analysis, we would be able to draw useful insights from the result obtained and would get to know which crime was recorded high for these cities.

# Discussion and conclusions
After performing all the analysis on the crime dataset, we can observe that the highest crime was reported under “Sexual and Violence offence” for three cities. Along with this, the percentage of Crime rates have also increased drastically over the years.

# TASK-2: Prediction of Survival Rate on "TitanicData" Using Machine learning

# Description
The RMS Titanic, a luxury ship, sank in the early hours of April 15,1912 in the North Atlantic after heating an iceberg during its voyage. There were 2,240 passengers and crew on board and nearly 1,500 lost their lives from this terrible disaster and only 705 people were rescued. The ship was built at cost of £1.5 million in Belfast by the White Star shipping line.
From the above context an analysis would be performed to know the percentage of survival rate. The dataset chosen for the Task 2 is the ‘TitanicData’ from the Learningzone shell-module of Big Data Analytics from Assessment section. There are 12 columns in the dataset which consist of information regarding the PassengerId, Passenger class (Pclass), Name, Sex, Age and so on. 
The purpose of the analysis is to predict the survival rate on ‘TitanicData’ by classification models using the Pyspark Machine Learning Library (MLlib) and to note down the accuracy of each model and other useful insights from the result. Here mainly I have used Naive Bayes, Logistic Regression and Decision tree classification to build the Pyspark MLlib model. Finally evaluate the result.

# Discussion and conclusions
In conclusion after performing both the tasks the observation drawn from Task 1 is that the number of crimes reported has increased over time and maximum crimes reported under ‘Violence and sexual offence’ for the three cities remains the same. From Task 2 we can say that the Decision tree classification model provided better results in comparison with the other two models in predicting the survival rate. Before the implementation of the Spark MLlib to get better results, I have cleaned the data by removing the null values and dropped the columns that are not required for the analysis. Due to which the results provided by the model were much more accurate in predicting the survival rate.
