<p align="center" style="font-size: x-large;" >Linear Models in Python</p>
<hr>

The linear model is a statistical model that represents the relationship between a dependent (response) variable and one or more independent variables (predictors). 

Linear models assume that the relationship is linear, hence the first word. This means that changes in a predictor results in a proportional change in the response.

Let's say we wanted to create a linear model to describe the relationship between a student's SAT score, number of AP class, how many hours they sleep, how many extracurriculars they participate in, and their GPA. In mathematical terms, we are looking for coefficients &beta;<sub>i</sub> that model the folloiwng relationship best...

$$
\text{GPA} = \beta_{0} + \beta_{1}\text{(GPA)} + \beta_{2}\text{(SAT)} + \beta_{3}\text{(Num. AP)} + \beta_{4}\text{(Num. Extra-C)} + \epsilon
$$

Where &epsilon; is a normally distributed error term. 

While this relationship is very simple compared to other statistical models, there are many questions left to answer. 
 - How can I tell if this relationship is actually able to be modeled by a linear function of these predictors?
 - What metric should I be using to determine the strength/weakness of a model?
 - How can I estimate how well my model will work on unseen data?
 - What method should I be using to determine my model coefficients? 

In this repository, I will try to explain ways to answer these questions. Here is a gist of what topic each Jupyter notebook covers...

__OLS Regression__
- Mathematical explanation of Ordinary Least Squares (OLS)
- Performing OLS Linear Regressions in Python

__Diagnostics__
- Assumptions behind Linear Regressions
- Checking Linear Regression assummptions with visualizations and statistical tests

__Model Metrics (in progress)__
- Model Summary Statistics
- Predictive Performance Metrics


__Cross Validation__
- Training v.s Testing data
- Implementation of different Cross-Validation methods

__Subset Selection Methods__
- All Subsets Selection
- Forward Selection
- Backward Elimination

__Shrinkage Methods__
- L1 and L2 Regularzation
- Hyperparameter Tuning with GridSearchCV & RandomizedSearchCV

__Dimensionality Reduction Methods (in progress)__
- Principal Components Regression (PCR)
 - Since the mathematical induction and applications of Principal Components Analysis (PCA) is extensive, I have created a separate repo.
- Partial Least Squares (PLS)


