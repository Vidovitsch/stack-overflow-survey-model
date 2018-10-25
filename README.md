# The job satisfaction of software developers

*Can an accurate model be created, given the features denoted in the survey, to predict the job satisfaction of software developers?*

The model will be seen as accurate if at least 90% of the predictions are the same as the target values denoted in the test set. The following approaches can be taken to get to this level of accuracy:
+	Try different classification algorithms
+	Try adding or removing features (selected on ‘weight’)
+	Try increasing or decreasing the regularization parameter
+	Try adding polynomial features (x, x2, x3, … ,xn)

The first approach is used to see which algorithm is best fit for the job initially. The last three approaches are used to solve potential high variance (overfit) or high bias (underfit) problems of the model.
