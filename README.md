# MentalHealthSurvey
This is an exploratory analysis of a survey conducted in Austin, Texas on attitudes toward mental health, and mental health issues in employees. 

The main aim of this project is to visualize the entire dataset in an accessible manner, and then explore the answers to questions that stand out, as well as relationships between variables. We do not aim to conduct predictive analysis or establish any hypothesis as we are unaware of how the data was sampled. The dataset is quite small, and the observations/answers to some questions were not sufficient.  

The exploration is divided into 3 main parts: Data Cleanup, Data Visualization, Data Analysis. 
Data Cleanup: The first part reads and cleans the data. Certain columns such as the age, country and gender of the employees had redundant values and/or values that didn't make sense - and thus needed to be cleaned up. Data cleaning also involves grouping data in columns that have a large number of unique values.

Data Visualization: The second part of the analyses visualizes the entire dataset in the form of a dashboard with 4 main parts: An individual's attributes, their family mental health history, their employer's attributes and questions around attitudes on mental health in their workplace. 

Data Analysis: The third part is the crux of the project. We first conduct a spearman correlation to look at the relationships between various questions asked in the survey. We then explore and visualize the answers to two main questions - 
 1. What are the attributes of an employee who does seek mental health treatment, and what are the attributes of an employee who does not seek treatment?
 2. What are the demographics of employees who work remotely?
