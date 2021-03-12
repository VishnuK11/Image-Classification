
## [HyperParameter Tuning using RL:]
**Context:**
*/Can we ask AI to find the best Hyper Parameters for the model?/*

Imagine this. You have been given 100hrs to run model training on a task and find the best hyper parameters(HPs) for the model-dataset. How should you balance your time and which hyperparameters should you spend more time tuning?

In this notebook, I explore the oppurutunity for the model to use Reinforcement Learning to decide which HPs are worth spending more epochs training and which aren't. I provide minimum and maximum epochs for the model to operate within. Using validation accuracy as reward, using Q Learning, the AI automatically decides which HPs to continue training for more epochs. I arrive at a best HP for the given number of steps and episodes. 

**Summary:**
Hyper parameter selection and tuning is a challenging task. I wanted to explore the feasibility of applying Reinforcement learning based on Q Learning to determine the hyperparameters like Droupout, Learning Rate and L2 Regularizations. I used a predetermined architecture for classifying the MNIST Digits Dataset. The reward was validation accuracy and to limit compute resources, the epoch was fixed to 2. Using this method, I was able to select the right Hyperparameter for this task. For this data and the architecture selected, the best hyper parameters are Dropout = 0.10,  L2Reg = 0.001, and LR = 0.01.
