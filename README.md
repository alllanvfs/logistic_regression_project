# Logistic Regression for Heart Disease Prediction

This project uses **Logistic Regression** to predict the presence of heart disease based on clinical data. This is my **first classification model** and is part of my journey in the data science field.

## Project Description

The main goal was to develop a model capable of predicting whether a patient has heart disease or not based on variables such as age, blood pressure, cholesterol levels, among others.

## Dataset

The dataset used contains **303 records** with **14 attributes**, including:
- Age
- Sex
- Resting blood pressure
- Cholesterol
- Maximum heart rate
- Exercise-induced angina
- And other clinical variables

The target variable is the `target` column, which indicates:
- **1:** Heart disease present
- **0:** Heart disease absent

## Technologies Used
- **Python**
- **Pandas** (data manipulation)
- **NumPy** (numerical operations)
- **Scikit-learn** (logistic regression model and metrics)
- **Matplotlib** & **Seaborn** (data visualization)

## Project Steps
1. **Exploratory Data Analysis**
   - Visualization of variables
   - Checking for missing data (no missing values were found)
  
2. **Preprocessing**
   - Standardization of numeric variables using `StandardScaler`
   - Separation of features and target variable

3. **Data Splitting**
   - Split into training (90%) and testing (10%) sets using `train_test_split`
  
4. **Model Training**
   - Use of the **LogisticRegression** model from Scikit-learn

5. **Evaluation**
   - Confusion Matrix
   - Classification Report (Precision, Recall, F1-Score)
   - Accuracy

## Results
The model presented good results for a first project, highlighting:
- Accuracy: **85%**
- F1-Score: **84%**
- ROC Curve indicating good class separation capability

## Future Improvements
- Cross-validation for more robust evaluation
- Implementation of techniques to handle imbalanced classes
- Hyperparameter tuning to improve performance
- Comparison with other classification algorithms (Random Forest, SVM)

---

This project marks the beginning of my journey in the field of Data Science. Feel free to contribute or leave suggestions! 😊
