# Regularized-regression-techniques
Analysis-R-notebook
Linear regression is a statistical technique for supervised learning to predict and describe
the relationship between a dependent and an independent variable [1]. The most widely
used method to fit the linear regression model is the Ordinary Least Squares (OLS). The
primary purpose of the model is generally to use specific data such that future observations
are predicted. Prediction accuracy and model complexity are two essential concepts for the
prediction or explanation of relationships between variables [5]. In these two criteria, the OLS
system shows low performance. OLS has many statistical and numerical problems, leading
to variable estimates of coefficients, low predictive ability, and results that are not easily
interpreted. Some of the problems included multicollinearity, which indicates a number of
predictors higher than the number of observations or high variance.
Regularization techniques such as LASSO, Ridge, and Elastic net regression solved some of
the OLS problems. Ridge regression shrinks the coefficient estimates to zero, thereby improving variability, reducing variance while slightly increasing the bias and enhancing the
overall accuracy of the model. On the other hand, Ridge regression produces models that
are difficult to analyse when the number of predictors is high. By choosing the coefficients to
shrink and shrinking some of them exactly to 0, the second regularization technique known
as LASSO increases both accuracy and model interpretability [10]. Elastic net, a convex
combination of Ridge and LASSO, is another Regularization technique. It works by utilizing
both Ridge and LASSO regressions to penalize the model.
