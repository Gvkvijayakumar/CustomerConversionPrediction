# CustomerConversionPrediction
Target is to predict whether the contacted customer will opt an insurance - Customer conversion prediction

Historical telephonic campaign details, prediction was  done whether he will take  customer to insurance company

Dataset have  the category of features  age , job , marital status, call type, education qualification , call duration, day , month, previous call outcome and number of calls
This is an Supervised Learning and binary classification problem.

The datset has 40K+ records and 35K+ records are under the category No. Since majority of the data falls under one target class, this is an imbalanced data.
Exploratory Data Analysis is done. The data is cleaned, encoded (Label encoding), Splitting , scaling (standardization) has been done.
Data visualization is done using  by plotly library

The models are bulit using different Machine Learning Algorithms,

Logistic Regression K-Nearest Neighbor Algorithm Decision Tree Max Voting Classifier Random Forest Algorithm XGBoost

The final model XGBoost has AUROC 92 % and Accuracy 88 %....
