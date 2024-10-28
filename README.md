# 🚢 Titanic - Machine Learning from Disaster
## 📄 Overview
This repository contains a machine learning project focused on predicting the survival rate of Titanic passengers based on various features. The project was developed as part of a coursework assignment in the "Machine Learning" course. It explores the use of different classification algorithms to analyze historical data from the Titanic disaster, aiming to understand the factors that influenced passengers' chances of survival.

## 🔍 Project Description
The sinking of the Titanic on April 15, 1912, is one of history's most infamous maritime disasters. This project analyzes the data to identify patterns and features that could help predict the likelihood of survival for passengers. Various machine learning models were employed to build predictive models, including:

Logistic Regression
Random Forest
Naive Bayes
Gradient Descent
k-Nearest Neighbors
The analysis considered factors such as age, gender, ticket class, fare, and the number of family members on board.

## 📁 Datasets
Three main datasets were used for this project:

train.csv: Training dataset containing features and survival labels.
test.csv: Testing dataset without the survival labels.
gender_submission.csv: A sample submission file to illustrate the format for prediction results.

## 🧹 Data Cleaning and Preparation
The data preparation process involved:

Removing irrelevant features such as Name, Cabin, Ticket, and PassengerId.
Handling missing values by either dropping rows (e.g., for the Embarked feature) or replacing missing values with the mode (e.g., for Age and Fare).
Binning the Age and Fare features into categories to simplify the analysis.

## 📊 Data Analysis
Several analyses were performed to understand the data better:

Survival rates by ticket class, fare, age group, gender, and point of embarkation.
Distribution of passenger demographics and their influence on survival rates.
Relationships between the number of family members aboard and survival chances.

## 🧠 Model Training and Evaluation
The data was split into training and validation sets, and multiple models were tested for accuracy. Among the models tested, the k-Nearest Neighbors algorithm showed the best results. However, Logistic Regression was chosen for the final submission on Kaggle due to its balance between simplicity and performance.

## 📈 Results
The final model achieved a 77.03% accuracy in predicting survival on the test set submitted to Kaggle.

## 📌 Conclusion
The project provided insights into the factors affecting survival in the Titanic disaster and demonstrated the application of machine learning techniques in data analysis. The models and methods applied can be extended to other predictive tasks and data science projects.

## ⚠️ Note
This repository contains the code and findings from the project. Some parts of the project may be incomplete, as this is a collection of what was found and gathered over time.

## 📚 References
[Kaggle Titanic Competition](https://www.kaggle.com/competitions/titanic/overview)
