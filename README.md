Multiple linear regression, an extension of simple linear regression, is a statistical method used to model the relationship between multiple independent variables X_1, X_2,..., X_p and a single dependent variable Y by fitting a linear equation to the observed data. The multiple linear regression equation can be expressed as Y = a + b_1X_1 + b_2X_2 + ... + b_pX_p where a is the intercept and b_1, b_2,..., b_p are the slopes associated with each independent variable. It is related to machine learning as it is a supervised learning technique that involves algorithms with labelled data. Multiple linear regression can serve as a benmark in order to develop and be compared to more complex model as it predicts a continuous target variable and makes use of feature selection.

The task was completed in Jupyter Notebook using the data in the diabetes.csv file which aims to predict the extent of the disease for a person in terms of the different attributes about them such as age and BMI. The independent variables and the dependent variables are differentiated and assigned to x and y respectively using the df.drop() function. The training and test sets which consist of 80% and 20% of the data respectively are generated. MinMaxScaler and StandardScalar from sklearn.preprocessing are used and then fit on the train set. The fit scalers are used to transform the train and test sets. A multiple linear regression model is generated with all of the independent variables on the train set. the intercept and coefficients of the train model are printed and the predictions for the test set are generated. The R-Squared value which detemines how well the data fits the regression model is computed. 
