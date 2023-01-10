# Predict-Diabeetus

https://colab.research.google.com/drive/1Ia2zAuXSEPojGHlUCpc_Fu6ZY-FVXMAP#scrollTo=3f79ac6a

Data was collected from: https://www.kaggle.com/datasets/houcembenmansour/predict-diabetes-based-on-diagnostic-measures

You will need the diabetes.csv, which is in the repository.

Predicts if a patient is more likely to have or not have diabetes. Also predicts likelihood of having diabetes. A KNeighborsClassifier model is trained on data for patients who were confirmed to have or not have diabetes as well as many risk factors, such as glucose levels, total cholesterol, HDL cholesterol, weight, age, and blood pressure. The model's hyperparameters are tuned for optimal accuray and precision using RandomizedSearchCV and GridSearchCV. One the model is tuned, it makes preditions on wheter new patients have diabetes or not.

Click the link at the top of the readme and follow the instructions on that page.
