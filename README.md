## Cost Function
If we try to think of it in visual terms, our training data set is scattered on the x-y plane. We are trying to make a straight line ) which passes through these scattered data points. 

Our objective is to get the best possible line. The best possible line will be such so that the average squared vertical distances of the scattered points from the line will be the least. Ideally, the line should pass through all the points of our training data set. In such a case, the value of cost function will be 0. The following example shows the ideal situation where we have a cost function of 0. 

<img width="450" alt="Screenshot 2022-03-14 013410" src="https://user-images.githubusercontent.com/68287058/169163795-07cd0cdb-b7ae-4625-9294-a6be16ab5ce5.png">

<img width="450" alt="Screenshot 2022-03-14 013410" src="https://user-images.githubusercontent.com/68287058/169163798-01c7ff8f-5ff8-42fa-bb69-b3556105cda3.png">

<img width="450" alt="Screenshot 2022-03-14 013410" src="https://user-images.githubusercontent.com/68287058/169163799-6cc21005-16ca-4e86-a809-0e06ebb58dab.png">

## Gradient Descent
So we have our hypothesis function and we have a way of measuring how well it fits into the data. Now we need to estimate the parameters in the hypothesis function. That's where gradient descent comes in.

Imagine that we graph our hypothesis function based on its fields \theta_0 and \theta_1 (actually we are graphing the cost function as a function of the parameter estimates). We are not graphing x and y itself, but the parameter range of our hypothesis function and the cost resulting from selecting a particular set of parameters.

We put \theta_0 on the x axis and \theta_1 on the y axis, with the cost function on the vertical z axis. The points on our graph will be the result of the cost function using our hypothesis with those specific theta parameters. The graph below depicts such a setup.

<img width="450" alt="Screenshot 2022-03-14 013410" src="https://user-images.githubusercontent.com/68287058/169163799-6cc21005-16ca-4e86-a809-0e06ebb58dab.png">

## Linear Regression

### Gradient Descent Algorithm
Gradient descent (GD) is an iterative first-order optimisation algorithm used to find a local minimum/maximum of a given function. This method is commonly used in machine learning (ML) and deep learning(DL) to minimise a cost/loss function (e.g. in a linear regression).

#### Feature Scaling
This is a technique used to reduce the range of data points such that it is easier to find the local minima than compared to a skewed range of datapoints.

<img width="450" alt="Screenshot 2022-03-14 013410" src="https://user-images.githubusercontent.com/68287058/169720263-a4e43ef6-b139-4395-9551-3164523523a8.png">

#### Mean Normalization
This is one way of feature scaling. Feature scaling is done using the formula: (x - mean) / n. Here n is the range of datapoints and x is the value of the data point.
The mean value would be 0 after normalization.

