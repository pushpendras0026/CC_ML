## 📝 Task Summary - CampusPulse Initiative

### 🎯 Objective:
Analyze student survey data to uncover key lifestyle and academic factors that influence student life — with a special focus on predicting romantic relationship status.

---

### 📦 Level 1: Variable Identification Protocol 
- Use EDA (plots, correlations) to identify anonymized features: `Feature_1`, `Feature_2`, `Feature_3`.
- Justify each guess based on statistical patterns.

---

### 🧼 Level 2: Data Integrity Audit
- Identify features with missing or inconsistent data.
- Apply and justify appropriate imputation strategies.

---

### 📊 Level 3: Exploratory Insight Report
- Ask and explore 5+ insightful questions about student behavior and life.
- Use plots and write brief, clear interpretations of findings.

---

### 💘 Level 4: Relationship Prediction Model
- Build classification models to predict if a student is in a romantic relationship.
- Evaluate model performance and reflect on what patterns influence predictions.

---

### 🔍 Level 5: Model Reasoning & Interpretation 
- Visualize decision boundaries using 2D feature pairs.
- Use SHAP for global and local interpretability.
- Explain why the model predicts "Yes" or "No" for specific students.

---

### 🎁 Bonus Level: Mystery Boundary Match 
- Match 5 unknown decision boundary plots to their correct ML models.
- Explain your reasoning based on visual patterns and model behavior.


## Libraries Used
The following Python libraries are required to run this project:

- **pandas**: Data manipulation and analysis  
- **numpy**: Numerical operations  
- **matplotlib**: Data visualization  
- **seaborn**: Statistical data visualization  
- **scikit-learn (sklearn)**: Machine learning tools including preprocessing, model training, evaluation, and model selection  
- **shap**: SHapley Additive exPlanations for model interpretability  
- **xgboost**: Extreme Gradient Boosting classifier  
- **lightgbm**: Light Gradient Boosting Machine classifier  
---
## My Approach

### Techniques Used

- **Encoding Methods:**
  - Ordinal Encoding
  - One-Hot Encoding (OHE)
  - General Trend Encoding

- **Imputation Techniques:**
  - Statistical Imputation (mean, median, mode)
  - K-Nearest Neighbors (KNN) Imputer
This approach ensures that missing values are handled effectively and categorical features are transformed appropriately to improve model performance.
- **Graphs Used:**
  - Heatmap
  - Boxplot
  - Histograms
  - KDE Plots
  - Bar Plots
  - Count Plots
  - % Stack Plots
  - Line plots
-**ML Algorithms And Accuracy**
    - Logistic Regression:0.6897
    - Random Forest:0.7155
    - SVM:0.6207
    - XG Boost:0.6207
    - Light BGM:0.6293
    - Naive Bayes Classifier:0.6724
-**Metrices Used**
 - Precision
 - Recall
 - F1-Score
 - Support
 - Accuracy
 - Macro Avg
 - weighted Avg
## Project Description

All the code and detailed explanations are provided in the Jupyter Notebook.  
Each step is clearly commented and visually explained to make the workflow easy to follow and visually attractive.

## Installation

You can install all dependencies using pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn shap xgboost lightgbm.



