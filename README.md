# CS115
HW01:
Apply the available plot functions in the guide file and explore other plotting methods to investigate and analyze the "penguins" dataset. Learn how to split the dataset into a training set and a test set (hint: using the train_test_split function from sklearn). Use the training set to train a Decision Tree model and the test set to evaluate the accuracy of the Decision Tree model (hint: using the accuracy_score function from sklearn).
The random_state parameter when using the train_test_split function must be set to your student ID. The random_state parameter when using the decision tree should be fixed at 42.
Try different settings for the max_depth hyperparameter and comment on how this hyperparameter affects the accuracy of the model on the test set. (Write your comments directly in the ipynb file as comments).
HW02:
The assignment should be done in a file named [MSSV]_BiasVarianceTradeoff.ipynb, which should demonstrate the results of the following experiments:

Experiment 1:

Create 03 datasets D1, D2, D3. Each dataset consists of a training set with N=10 data points and a test set with N=10 data points. The data points (x,y) with input value x are randomly generated in the range (0,1), and the target value y = f(x) = sin(1 + x^2) + ε, where ε follows a normal distribution N(0,σ=0.03) as described on slide 58.
For each dataset D1, D2, D3, use the training set to train 9 polynomial regression models with degrees from 1-9 as described on slide 68. You need to plot 9 graphs together in one figure as shown on slide 68.
For dataset D1, calculate the values of E_in (using the training set) and E_out (using the test set) for the 9 models and generate a statistical table of the results as shown on slide 66. The notebook file should display this statistical table.
Experiment 2: Perform the same steps as Experiment 1 with N = 100 data points.

Experiment 3: Perform the same steps as Experiment 1 with N = 1000 data points.

At the end of the ipynb file, provide comments to answer the following questions:

How does increasing the model complexity affect bias?
How does increasing the model complexity affect variance?
How does increasing the size of the training set affect bias?
How does increasing the size of the training set affect variance?
Note: It is mandatory to use numpy.random functions for generating random numbers (e.g., np.random.rand, np.random.random, np.random.randn, ...).
