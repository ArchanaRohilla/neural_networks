# Neural Networks

## Summary of Analysis:

- In this project, a deep learning model is designed which is able to predict the success of a venture paid by Alphabet 
soup. This model will be used to determine the future decisions of the company. Only those company projects which are likely 
to be a success will receive any future funding from Alphabet Soup.

- The data was imported, analyzed, cleaned, and preprocessed (bucketed, encoded and scaled) before fitting into the deep learning 
model. The final model (Model-9) consists of an input layer, two hidden layers and an output layer. First hidden layer consists of 
24 neurons and the second layer consists of 12 neurons. The first hidden layer consists of 24 neurons because there are 11 input 
variables and one target variable in the dataset. The activation function used for the hidden layers is "relu" and for the output 
layer is "sigmoid".

- The Model-9 is able to acheive the target predictive accuracy higher than 75%. To achieve the target accuracy, the input categorial
variables were bucketed and encoded before being scaled. The numbers of neurons(24) in the first hidden layer were taken twice the 
number of input variables(12) as per the rule of thumb.To improve it further we can also increase the epochs.

### Model-9

![alt text](JPGS/ProcessFlow.png)

### Results

![alt text](JPGS/ProcessFlow.png)

- Random forest classifiers can be used to solve this classification problem. The random forest classifier is capable to train on the 
large dataset and predict values in seconds. It is also capable to achieve comparable predictive accuracy on large tabular data with 
less code and faster performance. 