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

### Data Preprocessing
- Target Variables:
In the model, our target variable is what we're trying to learn about, which in this situation is the "IS_SUCCESSFUL" variable.
- Feature Variables:
With the exception of the ID columns "EIN" & "NAME", the other variables in this model are the feature variables.
- Other Variables:
Identifier variables such as the "EIN" and "NAME" columns are not important to the model and should be dropped from our input data prior to generating the model.

### Compiling, Training, and Evaluating the Model
Here are our results from the trials:
-   <b>Trial 1:</b> Dropped "ASK_AMT"
1 hidden layer - 5 neurons, "tanh" activation
72.4% accuracy

-   <b>Trial 2:</b> Dropped "USE_CASE"
5 hidden layers - 3 neurons in each, "relu" activation
72.6% accuracy

-   <b>Trial 3:</b> Dropped "USE_CASE" and "ASK_AMT"
4 hidden layer - 3 neurons in each, "tanh" activation
72.6% accuracy
<br><br>
As seen from these trials, we did not reach our goal of 75% accuracy. We tried adding and removing hidden layers, toggling neurons, and rerunning the analysis with various variables removed. 


## Summary / Conclusions
Although the model was a failure, there was a lot that could be improved upon. For one, accurately diagnosing "noisy" variables may become a key factor in substantially improving the model. To work with other tools for modeling, classification models such as a logistic regression could prove to be more beneficial to predicting success of the applicants. Since logistic regression works with predicting a binary classifier (i.e. 0/1, success or not), it could provide greater insight. Logistic regression can be more beneficial due to the fact that it is more transparent, and therefore changing the model can be more intuitive than the neural network model, which feels more like guesswork than calculated changes to optimize the model's strength.