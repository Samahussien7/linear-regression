# linear-regression
linear regression implementation with gradient decent
Apply Linear regression with gradient descent and MSE loss function from scratch (don't use the built-in linear regression in any library) to the following data (X, Y)

Split your dataset into 2 sets. Use 80% of your data for the training of the model and 20% of the data for the testing of the model (used to get the accuracy)
import matplotlib.pyplot as plt
import numpy as np
x = np.arange(200)
delta = np.random.uniform(-50,30, size=(200,))
​
y = .4 * x +3 + delta
​
plt.scatter(x, y)
plt.show()
