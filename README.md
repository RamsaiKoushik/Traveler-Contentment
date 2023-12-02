# Traveler-Contentment

## Data Analysis and Classification Report

**Introduction**

This report details the data preprocessing, exploratory data analysis (EDA), and machine learning models employed to analyze and predict passenger contentment in the airline industry.

**Data Preprocessing and Exploratory Data Analysis**

- **Removing Duplicate Rows:** Removed duplicate rows from the dataset and set the 'id' column as the index.
- **Initial Data Inspection:** Identified columns with null values, particularly 'Arrival Delay in Minutes,' for subsequent preprocessing steps.
- **Data Distribution Visualization:** Presented histograms for selected columns to observe data distribution.
- **Scatter Plot: Arrival and Departure Delays:** Provided scatter plots for these columns to observe their distribution.
- **Encoding Categorical Columns:** Identified categorical columns for one-hot encoding.
- **Handling Missing Values:** Addressed missing values by filling null values with column means.
- **Outlier Detection and Removal:** Detected outliers and performed removal for selected columns.
- **Correlation Analysis:** Visualized correlations using a heatmap to understand feature relationships.

**Model Training and Prediction**

- **Model Training:** Trained classification models including Random Forest, Logistic Regression, XGBoost, and K-Nearest Neighbors (KNN).
- **Model Evaluation:** Evaluated each model's performance on both validation and training datasets.

    - **Logistic Regression:** Test set accuracy: 0.877, Training set accuracy: 0.874
    - **Random Forest:** Test set accuracy: 0.963, Training set accuracy: 1.000
    - **XG Boost:** Test set accuracy: 0.963, Training set accuracy: 0.976
    - **KNN:** Test set accuracy: 0.927, Training set accuracy: 0.947

- **Making Predictions on the Test Data:** Utilized the trained Random Forest model to make predictions on the test data and saved the predictions in a CSV file for submission.

This report outlines the comprehensive process of data analysis, preprocessing, model training, and evaluation performed on the airline passenger satisfaction dataset.

