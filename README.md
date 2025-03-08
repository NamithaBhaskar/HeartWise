### ❤️ HeartWise - Predicting Tomorrow’s Heart Health  

#### Overview  
Heart disease remains a leading cause of death worldwide. **HeartWise** is a machine learning-based project aimed at **early detection of heart disease** using predictive modeling. The dataset, derived from the **Cleveland Heart Disease database**, contains 14 medical attributes, including **age, cholesterol, blood pressure, and chest pain type**.  

#### 🛠️ Key Features  
- **Custom Miss Forest Imputer** 🌲: A modified version using **RandomForestClassifier (for categorical data)** and **RandomForestRegressor (for continuous data)** for robust **iterative imputation** of missing values.  
- **Exploratory Data Analysis (EDA)** 📊: Visual insights into **age, gender, cholesterol, and exercise-induced angina** correlations with heart disease.  
- **Predictive Modeling** 🤖: Built **Random Forest, Gradient Boosting, Logistic Regression, KNN, and XGBoost models**, with the best performance achieved using a **Stacking Classifier (Random Forest + Gradient Boosting → XGBoost)**.  

#### 🔍 Results  
- **Best Model:** Stacking Classifier  
- **Validation Accuracy:** `82.8%`  
- **Best F1 Score:** `0.84 (macro & weighted avg)`  

#### 📂 Repository Structure  
┣ 📜 data/ # Heart disease dataset <br>
┣ 📜 code/ # Jupyter Notebooks <br>
┣ 📜 presentation/ # Project presentation <br>

#### 🛠️ Technologies Used  
- **Python** (Pandas, NumPy, Scikit-learn)  
- **Machine Learning** (Random Forest, XGBoost, Stacking Classifier)  
- **Data Imputation** (Custom Miss Forest Imputer)  
- **Statistical Analysis & Visualization** (Matplotlib, Seaborn)  

#### 🚀 Future Scope  
- **Enhancing Model Interpretability** using SHAP values  
- **Deploying as an API/Web App** for real-world usability  
- **Incorporating additional health metrics** for better predictions  

---
