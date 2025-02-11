# 🏥 Diabetes Prediction using Machine Learning  

🚀 Predicting the person having diabetes or not using ML algorithms. This project compares various models to determine the most effective one for diabetes diagnosis.  

## 📌 Project Overview  
Diabetes is a chronic condition affecting millions worldwide. Using machine learning, we can predict the likelihood of diabetes based on health parameters like glucose levels, BMI, and blood pressure. This project evaluates **six different ML models** to identify the most accurate one.  

## 🗂 Dataset Description  
The dataset used in this project is the **Pima Indians Diabetes Dataset**, sourced from the UCI Machine Learning Repository. It consists of **768 samples** with **8 numerical features** that are commonly used to diagnose diabetes. These features include:  

- **Pregnancies**: Number of times a patient has been pregnant  
- **Glucose**: Plasma glucose concentration  
- **Blood Pressure**: Diastolic blood pressure (mm Hg)  
- **Skin Thickness**: Triceps skinfold thickness (mm)  
- **Insulin**: 2-Hour serum insulin (mu U/ml)  
- **BMI**: Body Mass Index (weight in kg/height in m²)  
- **Diabetes Pedigree Function**: A function that scores the likelihood of diabetes based on family history  
- **Age**: Patient's age in years  
- **Outcome**: The target variable (1 = Diabetic, 0 = Non-Diabetic)  

## 📊 Models & Performance  
After training on the **Pima Indians Diabetes Dataset**, the models achieved the following accuracy:  

| Model                  | Accuracy | Precision | Recall | F1-Score |
|------------------------|----------|-----------|--------|----------|
| 🔥 **Random Forest**   | **74.02%**  | 69.44%    | 46.29% | 55.55%   |
| 🚀 Gradient Boosting   | **70.77%**  | 60.97%    | 46.29% | 55.55%   |
| 🤖 Logistic Regression | **75.97%**  | 71.79%    | 51.85% | 60.21%   | 
| 🔍 K-Nearest Neighbors | **72.07%**  | 64.86%    | 44.44% | 52.74%   | 
| 🌲 Decision Tree       | **66.88%**  | 53.48%    | 42.59% | 47.42%   | 

💡 **Random Forest or Gradient Boosting** usually provide the highest accuracy, but SVM is also a strong contender depending on hyperparameter tuning.  

## 🔬 How It Works  
1. **Preprocessing:** Standardization & missing value handling  
2. **Model Training:** Logistic Regression, KNN, Decision Tree, Random Forest, SVM, and Gradient Boosting  
3. **Evaluation Metrics:** Accuracy, Precision, Recall, F1-Score, AUC-ROC  
4. **Performance Comparison:** Best model selection based on results  

## 🔍 Key Insights  
- **Random Forest and Logistic Regression** consistently deliver high accuracy.  
- **Gradient Boosting** provides competitive performance and is effective in handling non-linearity in data.  
- **Decision Trees and K-Nearest Neighbors** tend to overfit on smaller datasets, leading to lower performance.  
- **Feature importance analysis** suggests that glucose levels and BMI are the most significant factors in diabetes prediction.  

## 📈 Future Enhancements  
- 🏋️‍♂️ Hyperparameter tuning for improved accuracy  
- 📊 Feature selection for model optimization  
- 🤖 Deep learning implementation using Neural Networks  
- 📌 Deployment of the model as a web application for real-time predictions  

🔗 **Let's build AI-driven healthcare together!** 🚀✨  
📧 Reach out for collaboration!  
