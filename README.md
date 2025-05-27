# CSE4334-5334-Assignment-2-solution

Download Here: [CSE4334/5334 Assignment 2 solution](https://jarviscodinghub.com/assignment/cse4334-5334-assignment-1-solution-2/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

Problem 1
(Logistic regression, 40pts) Implement a perceptron for logistric regression. For your training data, generate 2000 training instances in two sets of random data points (1000 in each) from multi-variate normal
distribution with
µ1 = [1, 0], µ2 = [0, 1.5], Σ1 =

1 0.75
0.75 1 
, Σ2 =

1 0.75
0.75 1 
(1)
and label them 0 and 1. Generate testing data in the same manner but include 500 instances for each class,
i.e., 1000 in total. Use sigmoid function for your activation function and cross entropy for your objective
function. You will implement a logistic regression for the following questions. Initialize the starting weight
as w = [1, 1, 1]. During training, stop your loop when the objective function (i.e., cross entropy) does not
decrease any more (below certain threshold) or when the gradient is close to 0 or the iteration reaches 10000.
Set your thresholds properly so that the iteration doesn’t reach 10000 for all the learning rate that you will
be using.
1. Perform batch training using gradient descent. Divide the derivative with the total number of training
dataset as you go through iteration (it is very likely that you will get NaN if you don’t do this.).
Set your learning rate to be η = {1, 0.1, 0.01}. How many iterations did you go through the training
dataset? What is the accuracy that you have? What are the edge weights that were learned?
2. Perform online training using gradient descent. Set your learning rate to be η = {1, 0.1, 0.01}. Set
your maximum number of iterations to 10000. How many iterations did you go through your training
dataset? What is the accuracy that you have? What are the edge weights that were learned? Compare
the learned parameters and accuracy to the ones that you got from batch training. Are they the same?
Explain in your report.
Instructor: W. H. Kim (won.kim@uta.edu), TA: Priyank Arora (priyank.arora@mavs.uta.edu) Page 1 of 2
CSE4334/5334 Data Mining Assignment 1
3. Write your own code to draw ROC curve and computing area under the curve(AUC). Evaluate the
performance of your LR classifier with batch training with η = {1, 0.1, 0.01}.
