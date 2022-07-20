# Projeto Final de Graduação
Aqui está o código utilizando para escrever o relatório do meu projeto final de Graduação

Machine learning has an increasing importance within society. However, for it to continue to evolve, more data from IoT devices and computing resources are needed, which has become a bottleneck for the scalability of this technology.
In order to seek alternatives to solve the scarcity of resources, the option of migrating the original machine learning configuration in which there is a central server that receives and stores all data from edge devices and builds a model has been studied. A federated architecture, known as distributed machine learning, performs the distribution of decision making, in a way that does not require the sharing of user data, instead, it shares its learning model and  receives trained local models and aggregates them.
However, this proposal still finds some relevant points that should be considered limiting. Thus, this project aims to show a case study of a form of optimization in the selection of users who will participate in the model training, in order to avoid unnecessary processing expenses and to verify if this proposed way is capable of bringing differences that are significant for applications of federated learning on IoT devices.

Here you will find 2 Notebooks that I've wrote with the intention of understanding how entropy can optimize the learning process of a federated machine learning model.

The model created was trained with the Emnist dataset

## PFG-Estudo-de-caso-Entropia-I
This Notebook was create with de objective to understand the Tensorflow Federated library. So part of the code was based on the Tutorial Code https://www.tensorflow.org/federated/tutorials/federated_learning_for_image_classification

In this code I've tried to understand how to create a model of machine learning federated using Tensorflow and Keras, and how to change default configurations of the library Tensorflow federated, by changing the calculus of parameters and hyperparameters. Also, in this notebook, i've calculated different forms of obtain the entropy of the clients data, trying to find the faster option to plug in my code.

This code contains the firsts simulations that i've made using tensorflow federated, some applying the entropy calculos on data clients and others without. Still, there some variatons of number of batches, epochs and rounds for each simulation. 

You will se that some simulations apply a random choice of clients for each round, this was with the objective of eliminate overfitting

## PFG-Estudo-de-caso-Entropia-II

In this notebook some others simulations was created, as a continuation of the first notebook. Here I've made others modifications on batches, epochs and round numbers. 


