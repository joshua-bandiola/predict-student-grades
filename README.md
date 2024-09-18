# Predict Student Grades

## Description

Given the significance of student performance in the educational process, it is essential to understand how numerous external factors may affect a student's ability to do well on exams.

This project aims to identify a data mining problem and apply an appropriate model to examine how external factors impact students' ability to perform well in exams. 
A binary classification model using logistic regression is built to predict whether a student will pass or fail their exams, achieving an accuracy rate of 73%. The model is selected after comparing its performance with decision trees and SVM models using AUC Scores.

This project focuses on hypothesis testings to address key research questions.
Specifically, the project investigates: 
1. Does the student's gender affect their performance?
2. Does a student's performance differ depending on the parent's educational background?
3. Does a student's race have an effect on how well they perform?
4. Can taking a test preparation course improve a student's performance?
5. Does a student's lunch quality have an effect on their performance?

By analyzing external factors such as family background and access to resources, institutions can better spot gaps where further support may be required.

## Tech Stack

-  **Languages**: Python
-  **Libraries**:
   - NumPy
   - Pandas
   - Scikit-learn (logistic regression, decision trees, SVM)
   - Matplotlib 
   - Seaborn

## Features

- **Data Pre-processing**: Handling missing data, and encoding categorical variables.
- **Feature Engineering**: Extracting and creating features that best explain the relationship between input variables and student performance.
- **Hypothesis Testing**: Shapiro-Wilk test, One-way ANOVA, and Z-tests
- **Model Training and Evaluation**: Using logistic regression for classification, with performance compared to decision trees and SVM
- **Insights**: This project concluded that gender, race/ethnicity, parental level of education, lunch, and test preparation course have a significant impact on the student's overall scores. 



