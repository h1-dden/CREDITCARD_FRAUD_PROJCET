# Credit Card Fraud Detection
This project focuses on building an advanced system using Python, Machine Learning, and Artificial Intelligence techniques to detect fraudulent credit card transactions in real time.

## Dataset

The [CreditCard Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud) provided by Kaggle is used in this project. It contains only numerical input variables which are the result of a PCA transformation Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction amount.  Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.

## Key Contributions and Achievements

### 1. Python Programming: 
Extensive use of Python programming language to implement data preprocessing, model training, and real-time transaction monitoring.

### 2. Machine Learning:
Utilization of various machine learning algorithms, including Logistic Regression, Decision Tree, SVM, and Random Forest Classifier, to create predictive models for fraud detection.

### 3. Artificial Intelligence:
Integration of AI techniques to develop an adaptive system that continuously learns from new data, ensuring the system's effectiveness against evolving fraud tactics.

### 4. Data Preprocessing:
Thorough data preprocessing techniques are applied to optimize input data, including feature scaling, handling missing values, and feature engineering.

### 5. Data Analysis:
In-depth credit card transaction data analysis to identify patterns and anomalies that could indicate fraudulent activity.

### 6. Feature Selection:
Implementation of feature selection methods to choose the most relevant features, improving model efficiency and performance.

### 7. Under Sampling:
Employing under-sampling techniques to address the class imbalance and enhance the models' ability to detect fraudulent transactions accurately.

### 8. Model Evaluation using accuracy_score:
Rigorous evaluation of models using accuracy_score metric to measure their performance and identify the most effective algorithms.

### 9. Cross Validation:
Cross-validation techniques are applied to validate model robustness and fine-tune hyperparameters for optimal results.

### 10. Real-time Fraud Detection:
Integration of the trained models into a real-time credit card transaction processing system, enabling immediate identification and prevention of potentially fraudulent transactions.

## Models Trained and Evaluated

The following machine learning models were trained and evaluated within this project:

### 1. Logistic Regression:
Trained a logistic regression model to predict fraudulent transactions based on the provided features. Evaluated its performance using the accuracy_score metric.

### 2. Decision Tree:
Constructed a decision tree classifier to capture complex decision boundaries in the data. Evaluated its effectiveness in detecting fraud.

###  3. SVM (Support Vector Machine):
Developed a Support Vector Machine model to classify transactions into legitimate and fraudulent categories. Assessed its performance using accuracy_score.

### 4. Random Forest Classifier:
Created an ensemble model using the Random Forest algorithm to harness the power of multiple decision trees. Evaluated its ability to improve fraud detection accuracy.

## Results
The following were the accuracy scores of all the above models:

### 1. Logistic Regression:
Accuracy on Training Data: 95.1%, Accuracy on Test Data: 95%.
Cross Validation score = 93.1%.

### 2. Decision Tree:
Accuracy on Training Data: 100%, Accuracy on Test Data: 90.3%
Cross Validation score = 90%.

### 3. Support Vector Machines 
Accuracy on Training Data: 91.1%, Accuracy on Test Data: 90%.
Cross Validation score = 91%.

### 4. Random Forest
Accuracy on Training Data: 100%, Accuracy on Test Data: 93.4%.
Cross Validation score = 94%.
