# omniglot challenge
This repository contains the python coded jupyter notebooks and data sets of omniglot challenge question along with a readme.

## The problem has been inspired by [Fellowship.AI, demo challenge](https://fellowship.ai/challenge/)

   1. The model has been trained using tensforflow backend in Keras.
   
   2. It tries to solve the problem of image verification when the quantity of data available for training Deep Learning models is   less.
   
   3. The model has been implemented to solve the problem based on the paper by **Gregory et. al** [Siamese Neural Networks for One-Shot Image Recognition](https://www.cs.cmu.edu/~rsalakhu/papers/oneshot1.pdf).
   
      * The ideas from the paper have been used to extend the model for few shot learning.
      
   4. [Omniglot](https://github.com/brendenlake/omniglot), dataset has been used for training the model.
   
      * The dataset has **1623** character classes, each with **20** examples.
      
      * The model tries to build a few shot classifier using the ides presented in the paper by Gregory et. al for the dataset.
      
