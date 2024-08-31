# Salary_Prediction_using_XGBoost

Libraries Used: Pandas, Numpy, Seaborn, Matplotlib, SKlearn.

The project involved predicting the salaries of fresh graduates with degrees like B.Tech, M.Tech, and MCA, based on their specialization and MCAT scores, which include sections on English, Logical Reasoning, and Quantitative Aptitude.


Perfomed data cleaning by removing null values, handling outliers, and eliminating duplicate rows. Analyzed and retained only the necessary columns for model accuracy, discarding those with direct correlations to reduce dimensionality.

Using feature engineering, combined specializations with fewer than 10 students into an "Other" category to simplify the model. This approach was used wherever necessary to enhance model performance. Categorical variables were converted into numerical labels using Label Encoding. Applied StandardScaler to normalize the data, as required for regression models.

Utilized an XGBoost Regressor for salary prediction. The dataset was split into 80% training and 20% testing data. After fitting the training data to the model, predictions were made on the test set, followed by evaluating the performance using the R² score.

Developed various visualizations to identify outliers, examine relationships between different features, and understand the factors contributing to higher salaries. Specifically analyzed the impact of different features on the target variable, ensuring only relevant columns were included to enhance model performance.

Outcome: The model achieved an R² score of 0.098
