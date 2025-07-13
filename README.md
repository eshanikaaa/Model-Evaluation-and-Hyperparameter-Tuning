# Wine Classification using Multiple Machine Learning Models

This project trains and evaluates multiple machine learning models on the  Wine dataset from scikit-learn. It includes:
- Model performance evaluation (accuracy, precision, recall, F1-score)
- Hyperparameter tuning using **GridSearchCV** and **RandomizedSearchCV**
- Final model comparison and selection
  
# Dataset
- **Name:** Wine Recognition Dataset  
- **Source:** scikit-learn built-in datasets  
- **Features:** 13 chemical properties of wines  
- **Target:** 3 wine cultivars (multiclass classification)

# Models Used
- Logistic Regression  
- Random Forest  
- Support Vector Machine (SVM)  
- Decision Tree  
- Naive Bayes  

Each model is evaluated using:
- Accuracy
- Precision (weighted)
- Recall (weighted)
- F1-Score (weighted)

# Hyperparameter Tuning
GridSearchCV (on Random Forest)
Tuned the following:
- n_estimators
- max_depth
- min_samples_split

# Final Output
After evaluation, the best-performing tuned model is selected based on **F1-Score** and a detailed classification report is displayed.

