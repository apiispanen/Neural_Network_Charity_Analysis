# Neural_Network_Charity_Analysis
Exploring neural network programming and prediction models.


### Overview
The purpose of this analyis is to create an accurate predictive model using neural networks for predicting whether or not applicants will be successful if funded by Alphabet Soup. To do this, we will be using the Keras library of Tensorflow, with Python.

#### Technologies Used
-   Python
    - Tensorflow & Keras
    - Pandas
    - Matplotlib
-   Jupyter Notebooks 

## Results

### Compiling, Training, and Evaluating the Model
Here are our results from the trials:
-   <b>Trial 1:</b> Dropped "ASK_AMT"
1 hidden layer - 5 neurons, "tanh" activation
72.4% accuracy

-   <b>Trial 2:</b> Dropped "USE_CASE"
4 hidden layers - 3 neurons in each, "tanh" activation
72.6% accuracy

-   <b>Trial 3:</b> Dropped "USE_CASE" and "ASK_AMT"
1 hidden layer - 5 neurons, "tanh" activation
72.4% accuracy
<br><br>
As seen from these trials, we did not reach our goal of 75% accuracy. We tried adding and removing hidden layers, toggling neurons, and rerunning the analysis with various variables removed. 


## Summary / Conclusions
Although the model was a failure, there was a lot that could be improved upon. For one, accurately diagnosing "noisy" variables may become a key factor in substantially improving the model.