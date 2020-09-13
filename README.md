Project Made/Contributor = Ayush Mehra

Problem Statement - The person will pay his loan or not.

This project will classify whether the person who has taken the loan will return it or not.
We will train the model through
1 - Random forest model
2 - Decision tree model.
And compare both of these.

What is  Random Forest Model?

The random forest is a classification algorithm consisting of many decision trees. It uses bagging and feature randomness when building each individual tree to try to create an uncorrelated forest of trees whose prediction by committee is more accurate than that of any individual tree.

What is Decision Tree?

A decision tree is a decision support tool that uses a tree-like graph or model of decisions and their possible consequences, including chance event outcomes, resource costs, and utility.

The difference between these two is a decision tree is built on an entire dataset, using all the features/variables of interest, whereas a random forest randomly selects observations/rows and specific features/variables to build multiple decision trees from and then averages the results.

Data Set - The data set is present in the repository and was taken from the lending club.

The project uses Python's inbuilt sklearn(sklearn.model_selection, sklearn.metrics, and sklearn.ensemble) library to built a random forest model and decision tree model separately and then compares both of them.

When the estimators we took were 150, on computing the random forest model was better than the decision tree.

Panda has been used to create a data frame and we have classified and done a detailed data analysis of the data using Python’s inbuilt matplotlib and seaborn library for the visualization purpose.

The confusion matrix has been created to give a detailed idea about the errors.

The accuracy of the Random Forest Model is 0.85.
The accuracy of Decision Tree Model is 0.73.

(The code is commented for better understanding)

