# Bike sharing prediction with Neural Network
Developed as coursework for Udacity Deep Learning Nanodegree.

## Introduction
Imagine yourself owning a bike sharing company. You want to protect how many bikes you need because if you have too few you are losing money from potential riders. If you have too many you are wasting money on bikes that are just sitting around.
So, to avoid those scenarios I've trained a neural network to predict from historical data how many bikes you'll need in the near future, taking in count dates, weather and type of riders.

## Project Overview
The neural network has been built in Python using numpy to assist and pandas for data preprocessing.
The project re-uses the structure provided by the [udacity repo](https://github.com/udacity/deep-learning-v2-pytorch/tree/master/project-bikesharing) but the core methods were implemented by me and the hyperparameters were chosen by me too.
The idea of this project is to understand better how gradient descent, backpropagation, and other important concepts of neural networks work before starting with tools like Tensorflow or Pytorch.

## Run notebook
With Anaconda you can run the commands below to install the dependencies in a virtual environent:
> conda create -n "bike-sharing" python=3

> activate bike-sharing

> source activate bike-sharing

> conda install numpy pandas jupyter notebook

And then just:
> jupyter notebook

To dive into details, look at [Predicting_bike_sharing_data.ipynb](https://github.com/matiaslgh/bike-sharing-prediction/blob/master/Predicting_bike_sharing_data.ipynb)

To see the methods to build the NN, look at [my_answers.py](https://github.com/matiaslgh/bike-sharing-prediction/blob/master/my_answers.py)
