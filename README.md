# OneNeuron

Description: In this repository, I created a simple, three layer neural network (input, hidden, output). This was based off of [this website](https://towardsdatascience.com/how-to-build-your-own-neural-network-from-scratch-in-python-68998a08e4f6). Due to the activation function used and setup, the NN can accomplish binary classification problems. With this in mind, I chose two datasets: one with multiclass output (altered to focus on only one of the classes) as well as a pure binary classification set.

Location: Machine Learning Graduate Course at KU

Dates: Apr 10, 2019 to Apr 22, 2019

## Goal
* Develop a neural network from scratch.

## Data
* Iris Dataset - Includes petal length and petal width
* [Statlog German](http://archive.ics.uci.edu/ml/machine-learning-databases/statlog/german/) - Includes a lot of data from people requesting credit

## Analysis
* I performed data rangling on the two data sets (i.e., normalized features, combined data sets, removing unrelevant entries, randomizing entries)
* Converted data with one-hot encoding
* Split data into training 80 and testing 10 and validation 10
* Recreated the function for creating a neural network with forward and back propagation and evaluated with sigmoid function

## Results
* Upon determining whether the provided features are Iris-virginica or not: 
  * Training: 96.67%
  * Testing: 93.33%
  * Validation: 93.33%
* Upon determining good or bad credit:
  * Training: 95.0%
  * Testing: 93.33%
  * Validation: 86.67%

## Repository Contents

| Directory | Description |
| --- | ----------- |
| Data | Contains all of the datasets used in this project. |
| Notebooks | Notebooks used for visualing the data. |



#### Collaboration Consideration
__Ron Andrews and Dalton Hahn__: Discussed the idea of learning rates to the Neural Network Forward/Back Propagation in order to prevent overfitting to quickly. 
