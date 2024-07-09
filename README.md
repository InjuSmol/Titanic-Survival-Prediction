# Titanic - Who Will Survive?

## Project Overview
This project analyzes the Titanic dataset to gain insights into survival factors during the Titanic disaster. By utilizing various machine learning models, the goal is to predict which passengers survived based on their socio-economic status, age, gender, and other relevant features.

## Datasets
The dataset for this project can be found on Kaggle and is already split into training and testing sets. The dataset includes various features such as passenger class, age, gender, fare, and number of family members on board. For more information on the dataset, refer to the [Kaggle Titanic Dataset Description](https://www.kaggle.com/c/titanic/data).

## Exploratory Data Analysis (EDA)
### Objectives
1. **Data Cleaning**: Remove outliers and handle missing values.
2. **Feature Exploration**: Analyze socio-economic status, age, gender, and other features to understand their relationships and importance.
3. **Survival Distribution**: Visualize the distribution of survival victims based on various features.
4. **Correlation Analysis**: Identify important features for the prediction task.
5. **Non-Numerical Features**: Extract and analyze information from categorical data.

### Steps
- **Data Cleaning**: Explain the process of handling missing values and removing outliers.
- **Feature Exploration**: Use visualizations to explore relationships between socio-economic status, age, gender, and other features.
- **Survival Distribution**: Visualize the survival rates across different passenger classes, genders, and age groups.
- **Correlation Analysis**: Perform a correlation analysis to identify the most significant features.
- **Non-Numerical Features**: Describe the methods used to convert categorical data into numerical formats suitable for modeling.

## Modeling and Question Answering
### Models Used
1. **Logistic Regression**: A simple and interpretable model that estimates the probability of survival.
2. **K Nearest Neighbors (KNN)**: A non-parametric method that classifies passengers based on their proximity to other passengers.
3. **Gradient Boosting Classification**: An ensemble method that builds multiple decision trees to improve prediction accuracy.

### Objectives
1. **Model Training**: Train three different models on the training set and predict outcomes on the test set.
2. **Model Explanation**: Briefly introduce the machine learning algorithms behind each model.
3. **Model Evaluation**: Evaluate the performance of each model based on accuracy and other metrics.
4. **Error Analysis**: Discuss reasons for any inaccuracies in the predictions.
5. **Evaluation Metrics**: Use Precision, Recall, and F-score to evaluate model performance.
6. **Cross-Validation**: Split the data further to include a cross-validation set and assess the impact on model performance.

### Steps
1. **Build Models**: Implement Logistic Regression, K Nearest Neighbors, and Gradient Boosting Classification models.
2. **Train and Test**: Train the models on the training set and evaluate them on the test set.
3. **Model Explanation**: Provide a brief overview of how each model works.
4. **Performance Evaluation**: Compare the performance of the models using accuracy, Precision, Recall, and F-score.
5. **Cross-Validation**: Implement cross-validation to improve model reliability and performance.

### Evaluation Metrics
- **Accuracy**: The proportion of correctly predicted survival outcomes.
- **Precision**: The proportion of true positive predictions among all positive predictions.
- **Recall**: The proportion of true positive predictions among all actual positive cases.
- **F-score**: The harmonic mean of Precision and Recall, providing a balance between the two metrics.

## Results
Summarize the key findings from the EDA and the performance of the models. Highlight which features were most important for predicting survival and discuss the effectiveness of each model.

## Contributions: 
### Nick DiMeglio’s Contributions:
- Created models and accuracy for the data
- Split data into training and testing data
- Helped Clean data
- Helped in visualization of data
### InjuSmol’s Contributions:
- Created 5 fold cross verification
- Found the F-score, Recall value and Precision Value
- Helped Clean Data
- Helped in visualization of data

```

