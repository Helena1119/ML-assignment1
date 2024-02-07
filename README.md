# Machine Learning Assignment--Linear Regression

This is a hands-on lab that implements one-variable linear regression to predict profits for a restaurant franchise. It is a simple but typical exercise using machine learning algorithms and applied to the business domains. 

The purpose of this case is to find cities for opening a new outlet that gives potential higher profits of the restaurant business. Population is one of the significant factors that affect the profit, and we have the dataset of these two elements.

We use x_train to represent the value of the factors that affect the profit and y_train to represent the profit. Then we can create a scatter plot of the data to understand the data through visualization.

To fit the linear regression parameters to the data set, we need to train a linear regression model, and to find the values that get the least cost, we can use a method called gradient descent. With each step of gradient descent, the parameters get closer to the optimal values that achieve the lowest cost. In Python, we import the numpy package to handle matrices and matplotlib to plot graphs.

Finally, we plot the predicted values to see the linear fit. And we can also use the final values to predict on profits. For example, the profit would be $4519.77 for the population of 35000 and $45342.45 for the population of 70000.
