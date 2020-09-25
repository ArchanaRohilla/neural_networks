# Neural Networks and Deep Learning Models
Neural networks (also known as artificial neural networks, or ANN) are a set of algorithms that are modeled after the human brain. 
They are an advanced form of machine learning that recognizes patterns and features in input data and provides a clear quantitative 
output. In its simplest form, a neural network contains layers of neurons, which perform individual computations. These computations 
are connected and weighed against one another until the neurons reach the final layer, which returns a numerical result, or an encoded 
categorical result.


## Project Overview
In this project, a deep learning model is designed which is able to predict the success of a venture paid by a Non-profit foundation. 
This model will be used to determine the future decisions of the company. Only those company projects which are likely to be a success 
will receive any future funding from the foundation.

## Tools
Python, Pandas, Matplotlib, Scikit-learn, TensorFlow
	
## Summary of Analysis

- The data was imported, analyzed, cleaned, and preprocessed (bucketed, encoded and scaled) before fitting into the deep learning 
model. The final model (Model-9) consists of an input layer, two hidden layers and an output layer. First hidden layer consists of 
24 neurons and the second layer consists of 12 neurons. The first hidden layer consists of 24 neurons because there are 11 input 
variables and one target variable in the dataset. The activation function used for the hidden layers is "relu" and for the output 
layer is "sigmoid".

- Out of 13 models, Model-9 is able to acheive the target predictive accuracy higher than 75%. To achieve the target accuracy, the input 
categorial variables were bucketed and encoded before being scaled. The numbers of neurons(24) in the first hidden layer were taken twice the 
number of input variables(12) as per the rule of thumb.To improve it further we can also increase the epochs.


![alt text](https://github.com/ArchanaRohilla/neural_networks/blob/master/Images/Model-9.png)

### Results

![alt text](https://github.com/ArchanaRohilla/neural_networks/blob/master/Images/Model9_Result.png)

## Suggestion
Random forest classifiers can be used to solve this classification problem. The random forest classifier is capable to train on the 
large dataset and predict values in seconds. It is also capable to achieve comparable predictive accuracy on large tabular data with 
less code and faster performance. 