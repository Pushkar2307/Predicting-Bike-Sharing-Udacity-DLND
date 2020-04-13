# Predicting-Bike-Sharing-Udacity-DLND

# Project Description

Developed as coursework for Udacity Deep Learning Nanodegree. In this project, I built a neural network to predict daily bike rental ridership.

## Getting Started

This Bike-Sharing-Dataset has the number of riders for each hour of each day from January 1 2011 to December 31 2012. The number of riders is split between casual and registered, summed up in the cnt column. You can see the first few rows of the data above.

### Prerequisites

* Python 3.7
* Numpy 
* Pandas
* Matplotlib


## Jupyter Notebook

This jupyter notebook describe the whole project from udacity, from the beginning to the end.
The neural network is implemented in the file `my_answer.py` and used from the jupyter notebook.

### Parameters of training

To change to interations, the amount of hidden nodes and some other parameters for the neural network, you can adapt these global constants inside the python file `my_answer.py'.

```python
#########################################################
# Set your hyperparameters here
##########################################################
iterations      = 5000      # 5000 / 10000 / 100000 / 200000
learning_rate   = 0.6       # 0.6     
hidden_nodes    = 20        # 20
output_nodes    = 1         # 1
```
