# Income-Classification-Model
The primary goal of this project is to develop a machine learning model capable of predicting an individual's income level based on various socio-economic factors. The classification task categorizes individuals as having an income either above or below $50,000 per year. 
# Dataset
The dataset contains 48,842 instances with 14 attributes. Key features include age, workclass, education, marital status, occupation, relationship, race, sex, capital gain, capital loss, hours per week, and native country. The target variable is a binary classification indicating whether income is greater than $50,000 (">50K") or less than or equal to $50,000 ("<=50K").

# Steps and Methodology
## Data Collection and Understanding:

The dataset was obtained from the UCI Machine Learning Repository.
Exploratory Data Analysis (EDA) was performed to understand the distribution of variables, detect outliers, and identify correlations.
## Data Preprocessing:

Handling Missing Values: Missing values in categorical variables were imputed with the mode of respective columns.
Encoding Categorical Variables: Categorical features were transformed into numerical values using techniques like one-hot encoding.
Feature Scaling: Numerical features were normalized to ensure they contribute equally to the model performance.
## Exploratory Data Analysis (EDA):

Visualizations were created to explore the relationships between features and the target variable.
Insights were derived to inform feature selection and engineering.
## Feature Engineering:

Created new features such as interaction terms and polynomial features to capture non-linear relationships.
Feature selection techniques like Recursive Feature Elimination (RFE) were used to identify the most significant predictors.
## Model Selection and Training:

Several machine learning algorithms were evaluated including Logistic Regression, Decision Trees, Random Forests, Gradient Boosting Machines (GBM), and Support Vector Machines (SVM).
Models were trained using cross-validation to ensure robustness and to mitigate overfitting.
## Model Evaluation:

Model performance was evaluated using metrics such as accuracy, precision, recall, F1-score, and ROC-AUC.
The best-performing model was selected based on these metrics.
## Hyperparameter Tuning:

Hyperparameters of the selected model were optimized using Grid Search and Random Search techniques to enhance model performance.

This project successfully developed a robust machine learning model for income classification, providing valuable insights into the factors influencing income levels. The deployed model can be utilized for various applications, such as targeted marketing, financial planning, and socio-economic research.
