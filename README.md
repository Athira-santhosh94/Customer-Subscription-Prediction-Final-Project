# Customer-Subscription-Prediction

This project predicts whether a customer will **subscribe to a term deposit** using various machine learning algorithms. It demonstrates the full ML pipeline: data cleaning, handling class imbalance, feature scaling, training multiple models, and comparing results.

##  Project Objective

The goal is to help a financial institution identify potential subscribers more accurately, so they can plan **targeted marketing campaigns** and increase campaign effectiveness.

##  Dataset

- **Source:** Bank Marketing Dataset: https://archive.ics.uci.edu/ml/datasets/bank+marketing
- Contains customer demographic and campaign-related features.
- Target variable: `subscription` (yes/no)

##  Workflow

**Steps implemented:**

1. **Exploratory Data Analysis (EDA):**
   - Checked for missing values, duplicates, outliers.
   - Handled skewness.
   - Categorical variables encoded.

2. **Feature Engineering & Selection:**
   - Selected relevant features based on EDA.

3. **Data Preprocessing:**
   - Handled class imbalance using **SMOTE**.
   - Applied **StandardScaler** to scale features.

4. **Model Building:**
   - Trained **five classifiers**:
     - Logistic Regression
     - Random Forest Classifier
     - Support Vector Classifier (SVC)
     - K-Nearest Neighbors (KNN)
     - Naive Bayes

5. **Model Evaluation:**
   - Compared models using accuracy, classification report, and confusion matrix.
   - Visualized model performance.

## Key Results

- All models achieved high overall accuracy.
- **Random Forest Classifier** gave the best trade-off between high accuracy and reasonable minority class detection.
- Naive Bayes showed higher recall for the minority class but lower precision, highlighting the challenge of class imbalance.

## Conclusion

In this project, I built and compared multiple machine learning models to predict whether a customer will subscribe to a term deposit. After exploring, cleaning, and analyzing the data, I found that the **Random Forest Classifier** gave the best results.

This project shows how data science can help banks target the right customers and run marketing campaigns more effectively. Overall, it improved my skills in data preprocessing, visualization, model building, and evaluation.
