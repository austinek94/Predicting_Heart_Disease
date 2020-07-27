# Objective: Predict the probability of heart disease given patient data

## Data columns:
* age
* sex
* chest pain type (4 values)
* resting blood pressure
* serum cholestoral in mg/dl
* fasting blood sugar > 120 mg/dl
* resting electrocardiographic results (values 0,1,2)
* maximum heart rate achieved
* exercise induced angina
* oldpeak = ST depression induced by exercise relative to rest
* the slope of the peak exercise ST segment
* number of major vessels (0-3) colored by flourosopy
* thal: 3 = normal; 6 = fixed defect; 7 = reversable defect
* target: According to the discussions on the dataset,0 is for people with heart disease and 1 is no heart disease.

** Results:
* Chest pain, maximum heart rate achieved, and the slope of the peak exercise ST segment had lower correlations than the rest of the columns
* Logistic Regression, KNN, Gradient Boosting, RandomForestClassifier, and SVM were the models used.
* Achieved a ~91% score using GridSearch and cross validation on AUC scoring metric
