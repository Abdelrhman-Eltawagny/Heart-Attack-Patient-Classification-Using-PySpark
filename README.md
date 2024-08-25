# Heart-Attack-Patient-Classification-Using-PySpark
This project focuses on building a classification model to identify heart attack patients using PySpark. The primary objective was to determine the most important features influencing heart attack occurrences and to build a predictive model that accurately classifies patients based on these features.The project involved hypothesis testing and statistical analysis to identify key factors, followed by the development of a logistic regression model for classification.

## Project Objectives:

- Feature Selection: Perform hypothesis testing to identify the most significant features that impact heart attack occurrences.
- Statistical Analysis: Use statistical methods to analyze the relationship between various features and the likelihood of a heart attack.
- Model Building: Develop a logistic regression model using PySpark to classify patients as heart attack patients or not, based on selected features.
- Evaluation: Evaluate the model’s performance using appropriate metrics to ensure it provides accurate classifications.

## Key Steps:

- Data Exploration: Loaded and explored the dataset to understand its structure and key characteristics.
- Hypothesis Testing: Applied statistical hypothesis testing to determine which features were most impactful.
- Feature Engineering: Selected the most important features based on statistical analysis.
- Model Development: Used PySpark's MLlib to develop a logistic regression model.
- Model Evaluation: Assessed model performance using metrics such as accuracy, precision, recall, and AUC.

## Libraries and Tools Used:

- PySpark (sql, ml): For data processing and machine learning in a distributed environment.
- Empiricaldist: For working with empirical distributions.
- Pandas: For data manipulation and preprocessing.
- NumPy: For numerical operations.
- Matplotlib & Seaborn: For data visualization and analysis.
- SciPy: For statistical analysis and hypothesis testing.
