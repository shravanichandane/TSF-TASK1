# TSF-TASKS

## TASK - 1 
# Prediction-using-Supervised-ML

## Predicting Student Scores Based on Study Hours

This project aims to predict the percentage of a student based on the number of study hours using supervised machine learning. The task is a simple regression problem with only two variables: the number of study hours and the percentage score.

### Introduction
This repository contains a simple linear regression model that predicts the percentage score of students based on the number of hours they studied. The data used for training and testing the model is provided by a link to a CSV file.

### Dataset
The dataset can be accessed via the following link: [Student Scores Dataset](http://bit.ly/w-data). It contains two columns:
- `Hours`: The number of study hours.
- `Scores`: The percentage scores.

### Prerequisites
- Python 3.x
- Jupyter Notebook or any Python IDE

### Installation
To run this project, you need to have the following libraries installed:
```bash
pip install pandas numpy matplotlib scikit-learn
```
 **Download the dataset:**
   Save the dataset from [here](http://bit.ly/w-data).

## Code 
**Code is given in respository.** 

## Methodology

This section outlines the methodology used in this project to predict student scores based on study hours using a supervised machine learning regression model. The process includes data collection, data preparation, model selection, training, evaluation, and prediction.

### 1. Data Collection
The dataset used for this project is sourced from a publicly available CSV file. The data can be accessed via the following link: [Student Scores Dataset](http://bit.ly/w-data). This dataset contains two columns:
- `Hours`: The number of hours a student studied.
- `Scores`: The percentage score achieved by the student.

### 2. Data Preparation
Data preparation involves several steps to ensure the data is in the correct format and ready for training the model:

1. **Loading the Data:**
   The dataset is loaded into a DataFrame for easy manipulation and analysis.

2. **Exploratory Data Analysis (EDA):**
   Basic exploratory data analysis is performed to understand the data distribution and relationships between variables. This includes visualizing the data to see the correlation between study hours and scores.

3. **Splitting the Data:**
   The data is split into training and testing sets to evaluate the model's performance. Typically, 80% of the data is used for training and 20% for testing.

### 3. Model Selection
For this simple regression task, a linear regression model is selected due to its effectiveness in handling linear relationships between the variables.

### 4. Model Training
The training process involves fitting the linear regression model to the training data. The model learns the relationship between the number of study hours and the corresponding scores.

### 5. Model Evaluation
After training the model, its performance is evaluated using the testing data. The primary evaluation metric used is the Mean Absolute Error (MAE), which measures the average magnitude of errors in the predictions, without considering their direction. This metric provides an understanding of how accurate the model's predictions are.

### 6. Prediction
Once the model is trained and evaluated, it can be used to make predictions on new data. For example, to predict the score for a student who studies for a specific number of hours, the model can provide an estimated percentage score based on the learned relationship between study hours and scores.

### Summary
The methodology followed in this project involves collecting the data, preparing it for analysis, selecting and training a suitable model, evaluating its performance, and finally using the model to make predictions. This systematic approach ensures that the model is reliable and can provide accurate predictions based on the number of study hours.

### License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---
