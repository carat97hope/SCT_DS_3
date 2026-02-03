📌 Task 03: Decision Tree Classifier – Bank Marketing Dataset

📖 Task Overview
The objective of this task was to build a Decision Tree classification model to predict whether a customer would subscribe to a bank term deposit based on their demographic and behavioral attributes. This task focuses on applying supervised machine learning techniques to a real-world dataset and understanding how decision trees make classification decisions.

📊 Dataset Description
Dataset Name: Bank Marketing Dataset
Source: UCI Machine Learning Repository
Records: 4,521 customer entries
Target Variable:
y → Indicates whether the client subscribed to a term deposit (yes / no)
Features Include:
Age, job, marital status, education, balance, housing and personal loan details, contact type, campaign information, and previous marketing outcomes.

🛠️ Tools & Technologies Used
Python
Pandas & NumPy
Scikit-learn
Matplotlib & Seaborn
Google Colab

🔍 Task Implementation Steps
Connected Google Drive to Google Colab and loaded the dataset
Performed exploratory data analysis to understand the structure and distribution of the data
Encoded categorical variables using label encoding to make the data suitable for machine learning models
Split the dataset into training and testing sets
Built and trained a Decision Tree Classifier using Scikit-learn
Evaluated model performance using:
Accuracy score
Classification report
Confusion matrix
Visualized the decision-making process of the model using a Decision Tree diagram
To improve interpretability, only the top levels of the decision tree were visualized, highlighting the most influential features while maintaining readability

📈 Model Evaluation
The model achieved high prediction accuracy on the test dataset
The confusion matrix provided insights into correct and incorrect predictions
The classification report highlighted precision, recall, and F1-score for each class

🎯 Key Learnings
Understanding how decision trees split data based on feature importance
Handling and encoding categorical data for machine learning models
Evaluating classification models using multiple performance metrics
Interpreting and visualizing machine learning models for better explainability
