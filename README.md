## Cost Function
If we try to think of it in visual terms, our training data set is scattered on the x-y plane. We are trying to make a straight line ) which passes through these scattered data points. 

Our objective is to get the best possible line. The best possible line will be such so that the average squared vertical distances of the scattered points from the line will be the least. Ideally, the line should pass through all the points of our training data set. In such a case, the value of cost function will be 0. The following example shows the ideal situation where we have a cost function of 0. 

## Linear Regression

### Gradient Descent Algorithm
Gradient descent (GD) is an iterative first-order optimisation algorithm used to find a local minimum/maximum of a given function. This method is commonly used in machine learning (ML) and deep learning(DL) to minimise a cost/loss function (e.g. in a linear regression).

#### Feature Scaling
This is a technique used to reduce the range of data points such that it is easier to find the local minima than compared to a skewed range of datapoints.

<img width="225" alt="Screenshot 2022-03-14 013410" src="https://user-images.githubusercontent.com/68287058/158111617-3f3702a0-b314-4e5e-8bef-cd4fd3dd87f7.png">

#### Mean Normalization
This is one way of feature scaling. Feature scaling is done using the formula: (x - mean) / n. Here n is the range of datapoints and x is the value of the data point.
The mean value would be 0 after normalization.

