# Depression Survey Analysis

## Project Overview

This project analyzes socio-demographic factors affecting depression and builds a machine learning model to predict depression levels. The dataset consists of socio-demographic information such as age, gender, financial stress, job satisfaction, academic pressure, and more. The project utilizes **Python** and libraries like **Pandas**, **NumPy**, **Matplotlib**, and **Scikit-Learn** to perform Exploratory Data Analysis (EDA), feature engineering, and machine learning model training.

## Dataset

- **Dataset Size**: 2,556 entries
- **Features**: The dataset contains socio-demographic factors such as:
  - Age
  - Gender
  - Academic Pressure
  - Job Satisfaction
  - Financial Stress
  - Profession (Student/Working Professional)
  - Sleep Duration
  - Dietary Habits
  - And more...

## Tools and Technologies

- **Python**: Programming language used for data manipulation and machine learning.
- **Pandas**: Data processing and manipulation.
- **NumPy**: Numerical operations.
- **Matplotlib & Seaborn**: Data visualization.
- **Scikit-learn**: Machine learning algorithms and model evaluation.
- **Jupyter Notebooks**: For interactive analysis and documentation.

## Steps and Methodology

### 1. **Exploratory Data Analysis (EDA)**
   - Analyzed socio-demographic data to uncover trends and patterns.
   - Visualized distributions, correlations, and potential outliers using **Matplotlib** and **Seaborn**.

### 2. **Feature Engineering**
   - Applied encoding techniques: **Ordinal Encoding**, **Label Encoding**, and **One-Hot Encoding** for categorical variables.
   - Handled missing values and outliers to ensure clean data for model training.

### 3. **Machine Learning Model Building**
   - Built and evaluated several machine learning models, including:
     - **Logistic Regression**
     - **Random Forest**
     - **Decision Tree**
     - **K-Nearest Neighbors (KNN)**
     - **Naive Bayes**
   - Optimized models using performance metrics such as **accuracy**, **precision**, **recall**, and **F1-score**.

### 4. **Hypothesis Testing**
   - Conducted **parametric** and **non-parametric** hypothesis testing to validate relationships between socio-demographic variables and depression levels.

### 5. **Model Evaluation**
   - Evaluated models using **accuracy**, **precision**, **recall**, and **F1-score**.

## Result
- The models were evaluated based on accuracy, precision, recall, and F1-score.
- Logistic Regression performed the best among the models, showing high accuracy and strong predictive performance.
