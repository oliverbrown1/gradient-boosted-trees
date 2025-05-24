## Overview

This is an implementation of Gradient Boosted Trees for continuous datasets

First we look at importing the required datasets, then defining helper functions for developing a Regression Tree, then relevant classes defining the Regression Tree implementation. After this, the performance of the Regression Tree is compared with Sklearn's DecisionTreeRegressor, showing that for multiple min_samples_split both implementations show very close mse values with test data. 

Then we implement a Gradient Boosted Regression Tree with 5 Trees, and using Mango, a Python library used to find hyperparameters for expensive models, we look at some different implementations using Mango. The main regularisation technique used for our tree is the minimum number of samples split in each node.

## Dependencies

* Python == 3.9
* Jupyter NoteBook
* Numpy
* Pandas
* Scikit-learn
* Arm-mango
