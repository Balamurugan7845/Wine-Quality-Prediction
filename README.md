# Wine Quality Prediction using Machine Learning

## Overview
This project predicts the **quality of red wine** using Machine Learning techniques based on its chemical properties. 
The dataset contains multiple features such as acidity, alcohol content, pH level, and sulphates that influence wine quality.

A **Random Forest Classifier** is used to train the model and predict the wine quality. The dataset is first preprocessed,
analyzed using visualizations, and then split into training and testing data to evaluate model performance.

---

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Random Forest Classifier
- Matplotlib
- Seaborn
- Jupyter Notebook (Anaconda)

---

## Dataset
Dataset used: **winequality-red.csv**

Features include:
- fixed acidity
- volatile acidity
- citric acid
- residual sugar
- chlorides
- free sulfur dioxide
- total sulfur dioxide
- density
- pH
- sulphates
- alcohol

Target variable:
quality

---

## Machine Learning Workflow
1. Import required libraries
2. Load the dataset
3. Data preprocessing
4. Data visualization
5. Train-test split
6. Train Random Forest model
7. Evaluate model accuracy
8. Predict wine quality

---

## Model Used
**Random Forest Classifier**

Advantages:
- Reduces overfitting
- Provides better accuracy
- Works well with complex datasets

---

## Example Prediction

Input:
(7.9, 0.32, 0.51, 1.8, 0.341, 17.0, 56.0, 0.9969, 3.04, 1.08, 9.2)

Output:
Predicted Wine Quality: 6

---

## Project Structure

Wine-Quality-Prediction/                                                                                                                                          
│                                                                                                                                                                 
├── winequality-red.csv                                                                                                                                           
├── wine_quality_prediction.ipynb                                                                                                                                 
├── README.md                                                                                                                                                     
└── requirements.txt

---

## Author
Balamurugan S  
Computer Science Student  
Interested in Machine Learning and Data Science
