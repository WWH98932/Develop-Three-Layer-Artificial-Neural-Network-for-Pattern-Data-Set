# Develop-Three-Layer-Artificial-Neural-Network-for-Pattern-Data-Set
UCLA Master of Applied Economics Econ 413 Assignment

You will use the assignment Apply the Artificial Neural Network to Logistic Regression for Pattern Data Set as a base to do this assignment. 

Review the slides of this week, and change Layer 1 as per the following:  
- Use the solution notebook of the previous pattern data assignment as base of your notebook. 

- Change the activation function to tanh (you may reuse what you developed in the previous assignment on activation functions)

- Create a function for derivative of tanh (you may reuse what you developed in the previous assignment on activation function)

- Implement the derivatives ∂J/∂W1 and ∂J/∂W2 as given in the slides 

- Use these derivatives to implement the update formulas for updating W1 and B1 (W2 and B2 are already being calculated). 

- Note that Layer 0 will remain as is (2 input 2 neurons, unit activation, zero B0, identity matrix as W0, and no updates)

- Use (ONLY) 1000 iterations to compute the model parameters and the cost function.  Record cost function at every 100th iteration in a Python list named cost_sample[].

- Plot the change in cost function against iterations. You can reuse the plotting from the previous assignments. (Cost Function should be plotted for each iteration and not just for each 100th iteration)

- Use the determined model parameters to predict the output for the test data (make sure to do full forward propagation to make the prediction and not just the Layer 2 inputs. In fact, you can simply reuse the forward propagation relations). 

- Compare the predicted output and actual output for the test data and determine percent accuracy

- In the end cleanly print the following:

  * cost_sample

  * percent accuracy

  * model parameters (W1, B1, W2, B2) 
