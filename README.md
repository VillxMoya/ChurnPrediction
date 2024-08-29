# Churn Prediction with Machine Learning
The  project intends to find the main drivers of churn for a company's clients. To do this, four different predictive are tested to classify the data and compared against using different metrics to then select a final one. The final and selected model is then finetuned for better fitness, adjusting its parameters. These four models are: 

* Logistic Regression
* Decision Tree
* SVM
* XGBoost

Finally, with the finetuned model, the most important features are found using Permutation Importance and Impurity Importance (the built-in feature importance tool in Sklearn for example). These are then discussed and delivered as the main drivers of churn for this specific case. 

Feature importance does not imply causality, as it is merely a way to specify which variable helped improve the accuracy of the model (as a short and simple explanation), but it's a starting point from where one can find the driving forces behind a specific event such as the one used for this project. 
