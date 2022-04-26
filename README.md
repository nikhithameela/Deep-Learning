# Deep-Learning-
  1. Introduction
  2. Objective 
  3. Why Neural Networks
  4. Hyperparameters tuning 
  5. Challenges 
  6. Learnings
# Introduction 
  1. Asset pricing is one of the important aspects of financial analysis <br>
  2. one such analysis using time series data is to be done with deep neural networks <br>
# Objective 
  1.The objective is to explore the hyperparameters of deep neural networks to understand the intuition behind the final architecture <br> 
  2.End goal of the tuning is to have the sharpe ratio more than 5.2 and the R-square ratio to be around 0 using different hyperparameters <br>
# Challenges 
### Why Neural networks 
  - Neural networks with deep architecture can capture any sorts of trend unlike time series models which are confined to few assumptions only
  - If the dataset is huge, it is always advisable to use neural networks for time series forecasting as well
### Hyperparameters considered 
  - Number of Layers 
  - Number of Neurons 
  - Optimizer
  - Activation function 
  - Batch Size 
  - Learning rate 
  - Patience for early stopping <br>
### Hyperparameters analysis
 ![image](https://user-images.githubusercontent.com/89437135/155908180-0935bb02-e187-4f17-ae68-aca8fbf556c6.png) <br>
 ### Challenges encountered 
  - Gradient Vanishing problem 
  - Gradient Exploding problem 
  - Running time 
  - Memory error due to large datasets
 ### Overall Learnings 
  - It is very important to use our intuition while training the deep neural networks as it is not practical to use all the possible combinations
  - There are new combinations that have been tried
    - Kernel Initializer
    - Encountered Vanishing Gradient descent 
    - Encountered Exploding Gradient descent 
    - Importance of Dropout
    - Alternate activation functions

The Modelling exercise is all about trying different parameters and understanding the directions<br>
  &emsp;**“We learned a lot about what not to do!!”**<br>
 	    &emsp;&emsp;&emsp;- Deep Learning thoughts
# Thank You!
