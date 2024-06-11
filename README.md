# Employee_Attrition_Classifier
* This notebook contains a classifier model for determining whether an employee is retained in company or not based on several factors given in the train and test sets.
* The categorical columns are frequency encoded which makes the encoding technique very robust. If more categories are added they can be accounted for very easily using this method.
* The drawback of this method of encoding is the possibility of multimodal categories. In which case, the solution is to change the encoding technique to a one hot encoder.

## The models used
* Logistic regression classifier
* Decision Trees
* Ensemble Techniques
    * Random Forest Regression
    * Bagging and Boosting Techniques
    * XGBoosting
    * AdaBoosting

## The best model
* Random Forest Regression: This classification technique turns out to be the best using a hyperparameter tuning technique using GridSearchCV
