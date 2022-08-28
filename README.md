# Heart-Disease-Prediction

This dataset has been taken from https://www.kaggle.com/code/cdabakoglu/heart-disease-classifications-machine-learning/data

This data contains following features:

● age - age in years 

● sex - (1 = male; 0 = female) 

● cp - chest pain type 

● trestbps - resting blood pressure (in mm Hg on admission to the hospital) 

● chol - serum cholestoral in mg/dl 

● fbs - (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false) 

● restecg - resting electrocardiographic results 

● thalach - maximum heart rate achieved 

● exang - exercise induced angina (1 = yes; 0 = no) 

● oldpeak - ST depression induced by exercise relative to rest 

● slope - the slope of the peak exercise ST segment 

● ca - number of major vessels (0-3) colored by flourosopy 

● thal - 3 = normal; 6 = fixed defect; 7 = reversable defect 

● target - have disease or not (1=yes, 0=no)

I have used 0 and 1 to predict whether a person have a heart disease or not in foloowing way:
       0 --> The Person does not have a Heart Disease
       1 --> The Person have a Heart Disease

Algorithm used to design this project is Logistic Regression.

The prgram then divides the dataset into training and testing samples in 80:20 ratio randomly using train_test_split() function available in sklearn module.

Accuracy score is then calculated by comparing with the coreect results of the training dataset.
