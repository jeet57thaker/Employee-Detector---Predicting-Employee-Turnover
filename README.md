# Employee-Detector---Predicting-Employee-Turnover
Used various models to find out Employee turnover based off various features.


The company wants to determine the possibilities of their employee turnover. We are given with cartian parameters based off which the company want to design a model. The parameters for data collection are:
  Satisfaction
  Evaluation
  ProjectCount
  AverageMonthlyHours
  YearsAtCompany
  WorkAccident
  Promotion 
  Department
  Salary

The target variable is Exit which shows wether the employee has left the comapany or not.

First of all, we have calculated the exit rate for the entire data set. This rate was about 76% employess stayed and about 24% left the company.
Then we saw the correlation amog the parameters, where it is seen that the employees doing more projects andworked more hours are highly evaluated. Also, satisfaction and exit are negatively correlated.

Then we plotted some of the exploratory analysis using seaborn plots, mainly against of the target variable to see how the employyes leaves the company and what the most impactful parameters.
The analysis is plotted in following manner:
  Salary Vs. Exit (Count Plot)
  Department Vs. Exit (Count Plot)
  ProjectCount Vs. Exit (Count Plot)
  Evaluation Vs. Exit (KDE Plot)
  AverageMonthlyHours Vs. Exit (KDE Plot)
  Satisfaction Vs. Exit (KDE Plot)
  
  After analyzing various features, we did some feautre engineering and converted all the variables in tho categorical to feed it into the models. Splitting the dataset into training and testing sets. we fitted the Decision Tree Model on training set and get the importances of the features.
  Then we plotted the Importances of Features using Decision Tree.
  
In the modelling work, we first designed Base Rate Model and calculated accuracy which came out to be 50%
followed by Logistic Regression mModel whose accuracy is also 76%
Decision Tree Accuracy is 94%
Random Foresy Classifier Accuracy is 98%
 AdaBoost Model Accuracy is 92%
 
 At last we plotted the grahp to compare the results of the models.
  
