
# Data Science Lab Final Project: Crime Rate Prediction in Israeli Cities

## Overview
This project aims to analyze and predict crime rates in various Israeli cities from 2014 to 2019. By integrating demographic, geographic, election data, and crime statistics, we aim to create a predictive model that can assist policymakers and law enforcement agencies in developing effective strategies for crime prevention and enhancing public safety.

## Research Goal
The central hypothesis of this project is: "Can we predict a decrease/increase in crime proportions for different cities across Israel?" Our objective is to discern patterns and factors influencing crime rates across these cities, providing a foundation for informed decision-making.

## Methodology
Our methodology encompasses several key stages:

### Data Collection and Cleaning
- Gathering diverse datasets and translating them into English.
- Removal of irrelevant features and handling missing values.

### Data Pre-Processing
- Normalizing numerical features using techniques like Min-Max normalization or standard scaling.

### Exploratory Data Analysis (EDA)
- Analyzing data distributions, correlations among features, and identifying outliers.

### Feature Engineering & Selection
- Developing new features and transforming and encoding existing ones.
- Selecting the most relevant features using methods like correlation analysis or the LASSO algorithm.

### Model Building
- Employing machine learning algorithms such as SVM, Random Forest, and AdaBoost to build and test predictive models.

## Key Findings and Conclusion
Our models have shed light on various factors affecting crime rates in different cities. The findings are as follows:

- **SVM (Support Vector Machine):** Exhibited the highest recall, proving its effectiveness in identifying true positives. However, it also had a higher rate of false positives.
- **Random Forest:** Showed slightly better precision than SVM but had a lower overall accuracy. It provided a more balanced performance, with fewer false positives at the expense of lower recall.
- **AdaBoost:** This model had the lowest performance in terms of recall, precision, and accuracy, indicating limited predictive capability in this context.

Despite some limitations, these models collectively demonstrate the potential of machine learning techniques in predicting crime rate trends.

## Future Work
To enhance the project's outcomes, our future focus will include:
- Acquiring more comprehensive and detailed data for a deeper analysis.
- Exploring a broader range of machine learning models and techniques.
- Investigating the impact of various socio-economic factors on crime rates more closely.

## Research Question Analysis

### Hypothesis Question
"Can we predict a decrease/increase in crime proportions for different cities across Israel?"

### Answer to the Research Question
Based on our model outcomes, we can confirm that predicting changes in crime rates in different Israeli cities is feasible to a certain extent. While no model was perfect, SVM and Random Forest, in particular, showed significant potential in forecasting crime rate trends. These insights are crucial for authorities to develop more effective crime prevention strategies.

## Overall Conclusion
Our analysis indicates that while there is no one-size-fits-all model, the use of machine learning techniques such as SVM and Random Forest is valuable in predicting crime rate trends. These models, despite their individual limitations, collectively provide useful predictions and insights.

## Contributors
- Raphael Damouny
- Moran Farraj
