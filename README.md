# Car Prediction Project
* Use a dataset made up of 371,528 car sales from the German website "eBay Kleinanzeigen"
* Perform EDA and data cleaning
* Test out several different regression models to find the most accurate
* The accuracy will be evaluated using RMSE (root mean squared error) since the price values can get quite large and by R^2 (coefficience of determination).

## The Models
1. Linear Regression
* The simplest model and the model that will be used as a benchmark to compare to others to
* R^2 score of 0.45 and RMSE of 5807
2. Decision Tree 
* Ensemble method that can often be very accurate, although the main drawback is that it is prone to overfitting and higher variance
* R^2 score of 0.80 and RMSE of 3518 (after tuning of parameters)
3. Random Forest 
* This is a model that builds on decision trees by combining a large number of decision tree to calculate the prediction, this model tends to be more biased but the results have less variance
* R^2 score of 0.88 and RMSE of 2717 (after tuning of parameters)

![3_models](https://user-images.githubusercontent.com/67882633/109438921-38aa0080-7a80-11eb-8452-c5defbcea1ae.PNG)

![boxplots](https://user-images.githubusercontent.com/67882633/109438932-4a8ba380-7a80-11eb-8688-728b6b4115fa.PNG)
