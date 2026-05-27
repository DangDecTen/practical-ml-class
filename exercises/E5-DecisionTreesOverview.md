# E5 - Decision Trees Overview

Write at least 300 words explaining the types of decision trees algorithms and applications.

## Answer

A machine learning algorithm for both classification and regression problem.

Think differently compared to other classification and regression algorithm we have learned.
- In linear regression, you find the linear relationship between the hypothesis functiona and the data. Then use the hypothesis to predict new data.
- In logistic regression, you also find a probability relationship between diffent class of data. Then you set a threshold when you need to classify a data to a class.
- But in decision tree, you create a set of rule to decide the value or the class that the data belong to. Each feature become a rule to classify data into two regions from which minimize the prediction error. In regression trees, the prediction error we need to minimize is the MSE between data value and the average value of corresponding region. In classification tree, we minimize the impurity (e.g. Gini index) of the region so that features in a region are more likely related to a particular class.

Build and tune.
- Decision do not need to normalize the data, but regularization is crucial because it is more likely to overfit than previous regression and classification algorithms.

Visualize tree diagram
- Rules of the decision tree can be visulize into a tree graph, which is highly interpretable.

Regression trees and classification trees.
- Regression trees: 