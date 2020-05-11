# Machine-Learning-Algo-Revison
Here You will find simple machine learning algo with the description 


The fundamental difference in between Regression and Classification is for a given data <xi, yi>ni=1 the if the yi belongs to Real values then it is a Regression problem and if yi belongs to values like (0,1) or (-1,1) then it is a classification problem.

Linear Regression:

The goal is to find the Best-Fit line which fits both the training and test data as well as possible, if we have only one dependent variable then the Best-Fit line will be a line, if we have more than one dependent variable the it will be a plane or hyperplane.

The Best-Fit line is a line or plane or hyper plane which minimizes the errors in each of the data-points in train and test.

Error for a given data point is calculated as (actual values – predicted value) but the problem with this equation is if the actual data-point is below the best-fit line then the error will be negative and for vice versa it will be positive, so while summing it may cancel out other errors, so we calculate the square of errors, and we try to minimize the square of the errors.

Now the error equation becomes error for a given data-point becomes (actual – predicted)2 , and we just have to sum it for all the data-points, which is called Squared Loss, and if we put this points on a graph it will be a parabola (Equation of parabola passing through origin Y = X2), this is why Linear Regression is also called OLS or LLS.

Sometimes the best-fit line fits the train datasets very well but does not fit the test datasets which is a classic case of Over-fit, and to avoid over-fit or under-fit we use Regularization, because Regularization is the chance in between Over-fit and under-fit, for Linear Regression we use L2 regularization because L1 regularization causes sparsity.
