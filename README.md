# Stroke-Prediction

Context
According to the World Health Organization (WHO) stroke is the 2nd leading cause of death globally, responsible for approximately 11% of total deaths.
This dataset is used to predict whether a patient is likely to get stroke based on the input parameters like gender, age, various diseases, and smoking status. Each row in the data provides relavant information about the patient.

Attribute Information
1) id: unique identifier
2) gender: "Male", "Female" or "Other"
3) age: age of the patient
4) hypertension: 0 if the patient doesn't have hypertension, 1 if the patient has hypertension
5) heart_disease: 0 if the patient doesn't have any heart diseases, 1 if the patient has a heart disease
6) ever_married: "No" or "Yes"
7) work_type: "children", "Govt_jov", "Never_worked", "Private" or "Self-employed"
8) Residence_type: "Rural" or "Urban"
9) avg_glucose_level: average glucose level in blood
10) bmi: body mass index
11) smoking_status: "formerly smoked", "never smoked", "smokes" or "Unknown"*
12) stroke: 1 if the patient had a stroke or 0 if not
*Note: "Unknown" in smoking_status means that the information is unavailable for this patient

Nearly 800,000 people in the United States suffer from a stroke each year, with about three in four being first-time strokes. 80% of the time these strokes can be prevented, so putting in place proper education on the signs of stroke is very important.
The objective of this study is to construct a prediction model for predicting stroke and to assess the accuracy of the model. We will explore seven different models to see which produces reliable and repeatable results. The models are: Decision Tree, Logistic Regression, Random Forest, Support Vector Machine, K Nearest Neighbour, Naive Bayes and KMeans Clustering. From the prediction outcome of the models, the best performance model will undergo the cross validation process to evaluate its repeatability.
Conclusion
Various model was used to predict whether a person is subjected to stroke. Naive Bayes model yields a very good performance as indicated by the model accuracy which was found to be 87.28%.
Using the mean cross-validation, we can conclude that we expect the model to be around 87.31% accurate on average.
If we look at all the 10 scores produced by the 10-fold cross-validation, we can also conclude that there is a relatively small variance in the accuracy between folds, hence the model is independent of the particular folds used for training.
Our original model accuracy is 87.28% and the mean cross-validation accuracy is 87.31%. Thus, the 10-fold cross-validation accuracy does result in performance improvement for this model.
Naive Bayes model can be further improve by tuning hyperparameters to get the better result or adjusting the probablity threshold to improve its performance.
