# Loan-Approval-Prediction
The goal of this project is to predict whether a loan application will be approved or rejected, based on various applicant-related features like gender, income, credit history, and loan amount.
----

📥 1. Data Collection and Loading
The dataset is loaded from a CSV file named Loan.csv. It contains both numerical and categorical variables about loan applicants such as:
- Gender
- Marital Status
- Education
- Income (Applicant & Co-applicant)
- Loan Amount
- Credit History
- Loan Status (Target variable)


🧹 2. Data Cleaning and Preprocessing
Missing Values:
- Mode for categorical columns like Gender and Marital Status.
- Mean for numerical values like Loan Amount.
Log Transformation:
- Skewed numerical features like LoanAmount and TotalIncome were log-transformed to normalize their distribution and improve model performance.
Feature Engineering:
- Created a new feature TotalIncome by combining applicant and co-applicant income.
- Extracted a subset of meaningful features for training based on domain knowledge.

  
📊 3. Exploratory Data Analysis (EDA)
Used bar plots to visualize distributions of key categorical variables such as Gender, Marital Status, and Number of Dependents.
Helped in understanding the dataset, identifying imbalances, and preparing for feature selection.


✅ 4. Feature Selection
Selected key columns that are most likely to influence loan approval.
Split the dataset into:
- x: Feature variables.
- y: Target variable (Loan_Status).

  
🧠 5. Model Training and Evaluation
Several machine learning models were trained using scikit-learn, including:
- Logistic Regression
- Decision Tree
- Random Forest
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
  
➤ Steps Taken:
- The data was split into training and testing sets.
- Each model was trained on the training data and evaluated on the test data.
- Model accuracy was calculated and stored for comparison.
- The predictions from the KNN model were displayed in detail.

  
📈 6. Model Comparison
Accuracy scores of all models were sorted and printed to find the best-performing one.
This allows a clear, data-driven choice of which model to use in production or deployment.

📌 Summary
This project effectively demonstrates a complete machine learning pipeline, including:
- Data preprocessing and cleaning
- Feature transformation and engineering
- Model training with multiple classifiers
- Performance evaluation and comparison

