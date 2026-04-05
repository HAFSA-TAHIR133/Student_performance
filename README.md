## Student Performance Prediction (Machine Learning Project)

## Project Overview

This project aims to predict whether a student will (Pass or Fail) based on various academic and behavioral factors such as study time, absences, parental support, and extracurricular activities.

The goal is to apply **Exploratory Data Analysis (EDA)** and multiple machine learning models to analyze student performance and compare their results.



## Dataset Description

The dataset contains student-related features, including:

* Age, Gender, Ethnicity
* StudyTimeWeekly (study hours per week)
* Absences
* ParentalEducation & ParentalSupport
* Extracurricular activities (Sports, Music, Volunteering)
* GPA (Grade Point Average)
* GradeClass (used to create target variable)


##  Target Variable

A new column **result** was created:

* **1 → Pass** (GradeClass 1 or 2)
* **0 → Fail** (GradeClass 3 or 4)



##  Exploratory Data Analysis (EDA)

The following analysis was performed using Matplotlib and Seaborn:

*  **Class Distribution** (Pass vs Fail)

*  **GPA Distribution**
*  **Study Time vs GPA (Scatter Plot)**
*  **Correlation Matrix**

### Key Insights:

* Students with higher **GPA** are more likely to pass
* Increased **study time** is positively related to performance
* Higher **absences** negatively impact results



##  Models Used

The following machine learning models were implemented:

1. Logistic Regression
2. Decision Tree Classifier
3. Random Forest Classifier



##  Model Performance

The models were evaluated using:

* Accuracy Score
* Confusion Matrix
* Classification Report

**Best Model:** Random Forest (Highest accuracy)



##  Visualizations

* Bar chart for model comparison
* Confusion matrix for prediction evaluation
* Feature importance graph (Random Forest)


##  Key Learnings

* Importance of EDA before model training
* Comparison of multiple models improves decision-making
* Tree-based models (Random Forest) perform well on structured data
* Feature importance helps understand key factors affecting outcomes



## Tools & Libraries

* Python
* Pandas, NumPy
* Matplotlib
* Scikit-learn
* Seaborn



##  Future Improvements

* Try multiclass classification (predict actual grades)
* Apply feature scaling and hyperparameter tuning
* Use advanced visualization libraries 
* Build a simple web app for predictions


## Conclusion

This project demonstrates how machine learning can be used to analyze student performance and predict outcomes effectively. It highlights the importance of data analysis, model comparison, and visualization in building reliable ML solutions.



##  Author

Hafsa Tahir (Software Engineering Student)
