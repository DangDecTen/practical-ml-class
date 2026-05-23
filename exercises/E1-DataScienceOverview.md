
# Exercise 1 - Data Science Overview

Write at least 300 words about one of this topics.

- Limitation of Machine Learning Algorithms
- Python vs R vs SAS for Data Science
- Differences of a Data Scientist and a Data Engineer

write a plain txt file using as a name E1-[uniandes username].txt
 
## Answer

### 1. Limitations of ML
To summarize, Machine Learning is great for:
- Problems for which existing solutions require a lot of fine-tuning or long lists of rules: one Machine Learning algorithm can often simplify code and perform better than the traditional approach.
- Complex problems for which using a traditional approach yields no good solution: the best Machine Learning techniques can perhaps find a solution.
- Fluctuating environments: a Machine Learning system can adapt to new data.
- Getting insights about complex problems and large amounts of data.

Main challenges of machine learning:
- Lack of data, complex problem need more data too get more insights of how to solve the problem. With only small data, even complex algorithms can only get the same insight as simpler algorithms. In this case, it is better to use your time and money to get extra data before you can make use of the your complex algorithms.
- Nonrepresenative training data. For both small and large dataset, the data itself may not represent a bigger picture but instead your model can only apply to part of the problem and being bias or making assumption of other part of the problem based on the trained irrelavent problem.
- Poor quality data. There are error, outliers, noise that need to be discard or revised before it can be used. Doing the data cleaning.
- Irrelavent features. Not all features of the data can be apply for such problem, doing some feature selection or extract new features may needed. Doing feature engineering.
- Overfitting the data. How far does your training data tell about the real world? If you cannot answer such question then it is wise not to overfitting the training data but be generalized. Regularization techniques are needed to solve the overfitting problem.
- Underfitting the data. Using a simple model may not good enough to handle this problem, you may need other algorithms or more complex ones to try to fit the data.

### 2. Python or R for Data Science

R tends to be more ergonomic for statistics, data viz, and data analysis, as it was designed for those things and has the incredible tidyverse suite of packages. But cutting edge ML/AI tooling is more developed in Python.