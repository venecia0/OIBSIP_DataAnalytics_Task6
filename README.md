# OIBSIP_DataAnalytics_Task6
Wine Quality Prediction

# Wine Quality Prediction using Machine Learning

## Project Overview

This project aims to predict the quality of wine by analyzing its chemical characteristics. Various machine learning classification algorithms are applied to the dataset to determine which model performs best in predicting wine quality.

## Dataset

**WineQT.csv**

The dataset contains several chemical properties of wine such as acidity levels, density, alcohol percentage, and pH value. These attributes are used as input features to predict the wine quality score.

## Objective

The primary goal of this project is to develop machine learning models capable of classifying wine quality based on its chemical composition and to compare the performance of different algorithms.

## Steps Performed

The following steps were carried out in the analysis:

1. Loaded the dataset and explored its structure
2. Checked for missing or inconsistent values
3. Performed data visualization to understand relationships between variables
4. Separated input features and the target variable
5. Split the dataset into training and testing sets
6. Applied feature scaling using **StandardScaler**
7. Trained multiple machine learning models
8. Evaluated model performance using different metrics and visualizations

## Machine Learning Models Used

* Random Forest Classifier
* Support Vector Classifier (SVC)
* Stochastic Gradient Descent (SGD) Classifier

## Tools & Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## Results

After testing multiple models, the **Random Forest Classifier** achieved the highest accuracy and produced the most reliable classification results for predicting wine quality.

## Conclusion

This project demonstrates how machine learning classification algorithms can be applied to predict wine quality using chemical attributes. It also highlights the importance of data preprocessing, feature scaling, and model comparison when working with real-world datasets.

