# Disease_Risk_Prediction
PBL-AI-ML

An end-to-end machine learning system that preprocesses healthcare data, performs exploratory data analysis and feature selection, and builds classification models to accurately predict disease risk.

Problem_Statement--> Design and develop an end-to-end machine learning classification system to predict disease risk using patient clinical data. The project involves selecting a suitable healthcare dataset containing features such as age, gender, blood pressure, cholesterol, glucose levels, heart rate, and lifestyle factors like smoking, alcohol intake, and physical activity. Data preprocessing steps including data cleaning, normalization, and transformation are applied to ensure data quality and consistency.

Exploratory Data Analysis (EDA) is performed to understand the distribution of health parameters, detect anomalies, and analyze relationships between different features using statistical summaries and visualizations. Correlation analysis helps identify important features influencing disease risk. Based on insights from EDA, feature selection techniques are applied to improve model performance and reduce noise.

Machine learning classification models are then developed to predict disease risk using algorithms such as Logistic Regression, K-Nearest Neighbors (KNN), Support Vector Machine (SVM), and Random Forest. The trained models are evaluated using standard performance metrics such as accuracy, precision, recall, F1-score, confusion matrix, and ROC curve to assess their effectiveness. The project demonstrates a complete machine learning pipeline from raw data to final prediction, supporting better healthcare decision-making.

🔍 Phase 1: Data Cleaning & Exploratory Data Analysis

In this phase, the dataset was loaded and examined to understand its structure, features, and data types. Data cleaning steps were performed to handle missing values, remove duplicates, and correct inconsistencies in categorical values such as gender and smoking status.

The target variable Disease_Risk was converted into binary form for classification. Blood pressure values were split into systolic and diastolic components for better analysis.

Exploratory Data Analysis (EDA) was conducted using visualizations such as correlation heatmaps to identify relationships between features. This phase helped uncover patterns, detect anomalies, and understand key factors affecting disease risk, forming a strong foundation for further processing.

⚙️ Phase 2: Feature Engineering & Preprocessing

This phase focused on transforming the cleaned data into a suitable format for machine learning. Numerical conversion was applied to all features, and categorical variables were encoded into numeric form.

Feature selection techniques were used to remove irrelevant and low-variance features, ensuring only important features were retained. Statistical methods such as SelectKBest were applied to improve model efficiency.

The dataset was split into training and testing sets to evaluate model performance. Polynomial feature generation was used to capture complex relationships between variables, and feature scaling was applied to standardize the data. This phase enhanced model accuracy and reduced the chances of overfitting.

🤖 Phase 3: Model Building & Evaluation

In the final phase, multiple machine learning models were implemented and trained using the processed dataset. These models included Logistic Regression, KNN, SVM, and Random Forest.

Each model was evaluated using performance metrics such as accuracy, precision, recall, and F1-score. A comparison of all models was carried out to identify the best-performing algorithm.

A confusion matrix was used to analyze prediction performance, and a ROC curve was plotted to evaluate classification capability. The model with the best F1-score was selected as the final model.

This phase demonstrated the effectiveness of machine learning in predicting disease risk and highlighted the importance of preprocessing and feature engineering in improving model performance.
