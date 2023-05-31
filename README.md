# Percision-Recall Trade-off
Two commonly used metrics for classification are precision and recall. Conceptually, precision
refers to the percentage of positive results which are relevant, while recall refers to the percentage
of positive cases correctly classified. Often we face a situation where choosing between increasing
the recall (while lowering the precision) or increasing the precision (and lowering the recall)
becomes necessary. This notebook reads a popular CSV file containing the passenger list of Titanic
and creates a Logistic Regression model with it. The model will help to predict if a person will
survive or not by analyzing other dependent variables from the CSV file. The end goal however is
to increase the precision of the model as much as possible, thus that all the positive predictions
the model makes are correct (increased precision), even if it isn’t able to catch all the positive
predictions (lower recall)
