# Introduction
The project involves the analysis of a heart disease dataset using machine learning techniques, with a focus on predicting the presence or absence of heart disease based on various health parameters. The dataset consists of 302 entries and 14 features, including age, sex, cholesterol levels, and more. The objective is to develop a predictive model using a Random Forest Classifier.

# Data Exploration and Preprocessing
- The dataset was loaded into a Pandas DataFrame and explored. Duplicate entries were removed, and no missing values were found. The dataset was then divided into features (X) and target variable (y). Standard scaling was applied to normalize numeric features.

# Exploratory Data Analysis (EDA):
- EDA was conducted using Matplotlib and Seaborn. Histograms were created to visualize the distribution of each feature. A correlation matrix heatmap highlighted relationships between features. The count of individuals with and without heart disease was visualized with a countplot.

# Data Transformation:
- Categorical variables were one-hot encoded using Pandas get_dummies method. This step is crucial for machine learning models to interpret categorical data properly.

# Machine Learning Model:
- A Random Forest Classifier was chosen for its robustness and ability to handle complex datasets. The model was trained and evaluated using cross-validation with varying numbers of estimators. The optimal number of estimators (14) was determined based on the highest accuracy score.

# Tools/Languages/Libraries Used
Programming Languages: Python
Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Plotly

# Conclusion:
The Random Forest Classifier demonstrated an accuracy of approximately 78.5% in predicting the presence or absence of heart disease. The project successfully utilized Python and various libraries for data analysis, exploration, and machine learning. Further optimization and fine-tuning of the model could potentially improve its performance. Overall, this analysis provides insights into the application of machine learning in predicting heart disease based on health parameters.
